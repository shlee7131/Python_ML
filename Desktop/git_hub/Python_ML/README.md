0801

## 넘파이

## 사이킷 런

## 평가 -> 예측 성능 평가 지표

### 정확도

### 오차 행렬

#### 정밀도

- Positive 예측 중 실제 Positive 데이터인 확률

#### 재현률

- 실제 Positivie 데이터 중 positive 예측 확률

##### 임계값

- 임계값이 낮아지면 Positive 예측 확률이 올라가고 재현률이 올라간다, 반대로 정밀도는 낮아진다
- **정밀도와 재현률은 상호 보완적**

#### F1 score

- 정밀도와 재현률이 균형잡힐 수록 높은 점수(한 쪽에 치우지면 안 좋다)

#### ROC 곡선과 AUC

- ROC 곡선은 FPR 에 따른 TPR 의 변화를 나타낸다.
- AUC 는 ROC 곡선의 면적에 해당하며, 1에 가까울수록 좋다
- FPR = FP / (TN+FP) -> 실제 Negative 중 틀릴 확률
- TPR = TP / (FN+TP) -> 실제 Positive 중 맞을 확률, 재현률
