# E-commerce 고객 세분화 분석

DACON 데이터셋을 활용한 RFM & Cohort 기반 고객 군집화 프로젝트

---

## 프로젝트 개요

E-commerce 거래 데이터를 활용하여 고객을 세분화하고, 각 세그먼트별 특성을 분석하여 맞춤형 마케팅 전략을 수립합니다.

---

## 분석 내용

### 1. 데이터 탐색 (EDA)
- 데이터 품질 검증
- 기초 통계량 및 분포 분석

### 2. 데이터 전처리
- 결측값 처리
- 파생 변수 생성

### 3. 고객 세분화
- RFM 분석 (Recency, Frequency, Monetary)
- K-means 클러스터링 (6개 군집)

### 4. 클러스터별 특성 분석
- RFM 프로필 비교
- 마케팅 비용 효율성 분석
- 구매 주기 패턴 분석

### 5. Cohort 분석
- 전체 및 군집별 Cohort 분석
- 월별 평균 매출액 추이

---

## 기술 스택

- Python 3.11.4
- pandas, numpy
- matplotlib, seaborn
- scikit-learn

---

## 실행 방법

```bash
pip install pandas numpy matplotlib seaborn scikit-learn

jupyter notebook Dacon_고객세분화분석_리팩토링.ipynb
```

**한글 폰트 설정 (Linux/Colab 환경)**

```bash
sudo apt-get install -y fonts-nanum
sudo fc-cache -fv
rm ~/.cache/matplotlib -rf
```
