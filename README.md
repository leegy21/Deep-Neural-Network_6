# Deep-Neural-Network_6

## 숙제 6

### 합성곱 신경망

#### 모델 생성

1. CIFAR10 데이터셋에 대해 합성곱 신경망 모델을 만들다.
   + 몇 개의 Conv2D층을 쌓는다. (각 층 사이에 MaxPooling 2D등을 삽입)
   + 마지막에 Flatten층 Dense층들을 추가
2. 모델 컴파일 및 훈련 (과대 적합 여부 탐지 및 완화)
   + 필요에 따라 DropOut 층, Batch Normalization등 사용 가능
3. confusion matrix등의 내용 확인을 통해 다층 퍼셉트론에 비해 성능 면에서 향상이 있는지 확인

#### 분석

어느 정도 성능을 가진 모델에 대해 다음 분석을 시행
1. 첫번째 합성곱 층에서 학습된 커널을 시각화
   + 예를 들어 커널이 34개이면 8x4그리드로 커널을 시각화
   + 시각화된 커널을 관찰하면서 CNN이 에지, 블롭, 색상 등의 저수준 특징을 어떻게 탐지하는지 이해
   + CNN의 동작 원리에 대한 직관을 줄 수 있는 다른 탐구를 한가지 이상 더 수행(예, Flatten층을 통과한 샘플들이 공간상에서 클래스 별로 잘 구분되는지 시각화하기 등)

