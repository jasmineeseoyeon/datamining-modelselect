DataMining-ModelSelect
# 학습 모델 비교 분석 및 성능 평가


### 코드의 목적
의사결정나무(Decision Tree)와 랜덤포레스트(Random Forest) 모델의 성능을 비교한다.<br>
데이터를 효과적으로 분리 및 평가하여 최적의 학습 모델을 선정한다.

---

### 주요 내용
- SMOTE를 이용한 데이터 불균형 문제 해결
- 데이터 분할 (Train/Test)
- 학습 모델 성능 평가 (Accuracy, Precision, Recall, F1-Score)
- 교차 검증 (Cross Validation)
- 학습 곡선 시각화 (Learning curve)

---

### 사용된 라이브러리
- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **scikit-learn**
- **imbalanced-learn**

---

### 데이터 설명
- **데이터셋**: `hotel reservation_original.csv`
- **타겟 변수**: `booking_status`
- **출처**: `kaggle`

---

### 실행 방법

1. Jupyter Notebook을 실행합니다:
   ```bash
   jupyter notebook

3. 브라우저에서 파일을 열고 실행합니다:
   ```bash
   hotel dataset classify accuracy_학습곡선.ipynb
   ```

---

### 주요 결과
- 랜덤포레스트(Random Forest)가 의사결정나무(Decision Tree)보다 성능이 우수함.
- 정확도와 추가적인 성능 지표(Precision, Recall, F1-Score)는 결과 섹션도 함께 출력됩니다.
- 학습 곡선 분석 결과, 랜덤포레스트는 더 안정적이고 일반화 능력이 뛰어난 모델임을 확인.

---
