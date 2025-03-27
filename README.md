# MNIST-Classifier

Project Title: Handwritten Digit Classification Model (MNIST)
1. 모델 개요
이 프로젝트는 MNIST 손글씨 숫자 분류 문제를 해결하기 위한 모델을 학습한 결과입니다.
모델은 딥러닝을 활용하여 0부터 9까지의 숫자를 예측하는 분류 모델입니다.

2. 학습 과정 및 정확도
모델을 100 epochs 동안 학습시키면서, 훈련 데이터와 테스트 데이터에 대한 정확도 변화를 기록하였습니다.
아래의 그래프는 각 epoch에 따른 **훈련 정확도(train accuracy)**와 **테스트 정확도(test accuracy)**의 변화를 보여줍니다.
```
Epoch 99 | Loss: 82.6760 | Train Acc: 0.9013 | Test Acc: 0.9044
```
훈련 정확도는 학습이 진행될수록 지속적으로 증가하고 있으며,

테스트 정확도는 훈련 정확도와 비슷하게 증가하면서 안정적인 결과를 보여주고 있습니다.

3. 정확도 그래프

이 그래프에서:

파란색 선은 훈련 정확도를 나타내며,

주황색 선은 테스트 정확도를 나타냅니다.

x축은 epoch을 나타내며, y축은 정확도입니다.

학습이 진행됨에 따라, 훈련 정확도와 테스트 정확도 모두 향상되었음을 확인할 수 있습니다.

