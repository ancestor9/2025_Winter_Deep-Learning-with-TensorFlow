### 1. CNN과 RNN

#### AlexNet의 구조 이해하니? (복습)
<img src = "https://resources-public-blog.modulabs.co.kr/blog/prd/content/259481/Untitled-4.png" height =400>

#### 공간 정보에서 의미 정보로의 전환:
- 마지막 컨볼루션 레이어에서 나온 공간적인 특징들($6 \times 6 \times 256$)을 일렬로 늘어놓은 상태로  이 단계에서는 아직 "어디에 어떤 모양이 있다"는 물리적인 정보가 강하게 남아 있습니다.
-     . 첫 번째 FC 4096: 9216개의 개별 데이터를 조합하여 "이 이미지는 동물의 귀와 눈의 특징을 가지고 있다"와 같은 기초적인 특징들의 조합을 발견
      . 두 번째 FC 4096: 첫 번째 FC에서 나온 정보를 한 번 더 조합하여 "이것은 고양이의 얼굴이다"와 같은 **더욱 고차원적이고 추상적인 의미(Semantic)**를 완성
      . 비선형 복잡도 증가 (Non-linearity)단순히 레이어를 하나만 쓰는 것보다, 두 레이어 사이에 ReLU와 같은 활성화 함수를 넣어 두 번 거치게 되면 모델이 훨씬 더 복잡하고 정교한 관계를 학습할 수 있습니다.레이어를 거듭할수록 데이터는 단순한 '픽셀의 모임'에서 '사물의 개념'으로 변하게 됩니다.
- 이미지 캡셔닝 구조에서는 이 두 번째 FC 4096 레이어가 특히 중요합니다.
-     마지막 FC 4096에서 나온 결과물은 이미지 전체의 내용을 4096개의 숫자로 요약한 **'최종 컨텍스트 벡터'**가 되며(Encoder) ---> Decoder부분이 RNN(디코더)으로 전달되어 "A cat sitting on a chair"라는 문장을 만드는 시작점 (Sequence to Sequence Model)
- [Sequence to Sequence Model, Andrew ng](https://www.youtube.com/playlist?list=PLkDaE6sCZn6F6wUI9tvS_Gw1vaFAx6rd6)

### 2. 시계열데이터 예측(FNN, 1D convnet, RNN)
- chapter13_timeseries-forecasting.ipynb

### 3. 과제
- [자연어 처리를 위한 1D CNN(1D Convolutional Neural Networks)](https://wikidocs.net/80437)

### 4. RNN, LSTM
- 노래의 코드, 박자 등을 encoding하여 딥러닝을 적용
- [순환 신경망 모델 만들어보기](https://tykimos.github.io/2017/04/09/RNN_Layer_Talk/)
