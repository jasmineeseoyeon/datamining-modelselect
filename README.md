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
- **주요 사항**: SMOTE를 사용하여 데이터의 클래스 불균형 문제를 해결했습니다.

---

### 실행 방법
1. 레포지토리를 클론합니다:
   ```bash
   git clone https://github.com/your-username/datamining-modelselect.git
   ```
2. 필요한 라이브러리를 설치합니다:
   ```bash
   pip install -r requirements.txt
   ```
3. 메인 스크립트를 실행합니다:
   ```bash
   python main.py
   ```

---

### 주요 결과
- 랜덤포레스트(Random Forest)가 의사결정나무(Decision Tree)보다 성능이 우수한 것으로 확인되었습니다.
- 정확도와 추가적인 성능 지표(Precision, Recall, F1-Score)는 결과 섹션에 상세히 기록되어 있습니다.
- 학습 곡선 분석 결과, 랜덤포레스트는 더 안정적이고 일반화 능력이 뛰어난 모델임을 확인했습니다.


---
