### 이미지 분류와 전이학습(Deep learning for Image Classification & Transfer Learning)
- Deep Learning with Pyton 책의 Chapter 8장의 내용과 코드(chapter08_image_classification.ipynb)

#### 1. CNN의 직관적 이해 
- [Master CNN Concepts with Interactive Learning!](https://www.101ai.net/vision/vizdemo)
-     * 이미지 데이터는 Fully Connected Neural Network을 합슥에 적합하지 않은가?
      * 이미지 데이터를 입력으로 받아 cortex 와 같이 특징을 추출하는 방법은 무엇인가? Filter Kernel?
      * 14_1_image_representation_for_cnns,  14_2_cnn_translation_invariance,  14_3_local_patch_filter 노크북 코드의 직관적 이해?
#### 2. CNN(Convolutional Neural Networks)의 모델 아키텍처
<img width="827" height="407" alt="image" src="https://github.com/user-attachments/assets/cb96063d-bb19-4f30-9c4b-11fc07bc5233" />

-     * LLM에게 내적과 행렬의 크기 변환에 대해 물어보고 수학의 Convolution 연산을 이해하는가? 각 레이어의 행렬식의 구조와 연산을 이해하는가?
      * Filter Kernel 함수의 역할을 이해하는가?
      * Loss Function과 Optimation을 통해 어떤 Parameter를 추정하는지 설명할 수있나?
      * Convolution Layer 종단층에 왜 FNN을 연결하는가? layers.GlobalAveragePooling2D() ?
  
#### 3. 아래 내용을 이해하고 설명할 수있는가?
<img src="https://miro.medium.com/v2/resize:fit:1100/format:webp/1*h1S9FFDHmmj5yY_Y3uMcgw.gif" style="width:400px; height:300px;">

<div style="display:flex; gap:10px;">
  <img src="https://miro.medium.com/v2/resize:fit:640/format:webp/1*Boz5FkpCxJyHj5mdNrbTTA.gif" width="400" height="300">
  <img src="https://miro.medium.com/v2/resize:fit:640/format:webp/1*Q7NXeOlDkm4xlNrNQOS67g.gif" width="400" height="300">
</div>

#### 4. 실습하기
-      * chapter08_image_classification.ipynb 의 코드를 이해하는 가?
       * 전이학습의 모델 아키텍처 구성을 이해하는가? 왜 전체 parameter를 학습하지 않는가?

#### 5. CNN Mechanism
- 아래를 클릭하고 설명할 수 있는가?
-      * Fatten 레이어의 역할은 무엇이지? 없어도 상관없는가?
- [CNN_Convolutional Neural Network](https://poloclub.github.io/cnn-explainer/)
- [Demo Video "CNN Explainer: Learning Convolutional Neural Networks with Interactive Visualization"](https://www.youtube.com/watch?v=HnWIHWFbuUQ)

#### 참고자료
- [But what is a convolution?](https://www.youtube.com/watch?v=KuXjwB4LzSA)
- [Convolutionary Neural Network](https://hackernoon.com/dl05-convolutional-neural-networks-1d3bb7fff586)
- [Deep Learning Bible](https://wikidocs.net/177768)
- [유튜브-1](https://www.youtube.com/watch?v=Em63mknbtWo)
- [유튜브-2](https://www.youtube.com/watch?v=2-75C-yZaoA)

