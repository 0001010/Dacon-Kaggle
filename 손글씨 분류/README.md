# ✏손 글씨 (숫자) 분류 경진대회(Dacon)
Dacon Competition으로 손글씨를 분류
	- 평가지표는 Accuracy
	- train 5000개, test 5000개의 데이터이고 0~9까지의 label 존재
	- pre-trained모델 사용 X
	- Public 8위(93%), Private 13위(92.05%)

[Competition Link](https://dacon.io/competitions/official/235838/overview/description)


### ✅Base : [Baseline Link]https://github.com/0001010/Dacon-Kaggle/blob/main/%EC%86%90%EA%B8%80%EC%94%A8%20%EB%B6%84%EB%A5%98/dacon_mnist_baseline.ipynb

### 💪시도(Baseline + 여러가지 방법)
1. sub_image_aug기준 0.895 epoch 100
2. sub_image_aug2기준 0.908 epoch 100 + 150
3. sub_image_aug3기준 0.91 epoch 400
4. sub_image_aug6기준 0.93 원래 레이어 + conv층 추가(필터 32) epoch 400
