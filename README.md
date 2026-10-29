# 데이터로 문제를 발견하고, 개선을 만드는 데이터 분석가 이원빈입니다.

> **사용자 행동 데이터를 기반으로 문제를 정의하고, 지표 설계와 실험을 통해 운영 판단의 근거를 제시합니다.**

글로벌 앱마켓의 사용자 행동과 콘텐츠 성과를 분석해 온 데이터 분석가입니다.

SQL과 Python을 활용한 **행동 로그 분석, A/B Test, KPI 설계, 데이터 품질 기준 수립** 업무를 수행했습니다.  
단순한 지표 산출에 그치지 않고, 서비스 목표에 맞는 측정 기준을 정의하고 분석 결과가 실제 운영 의사결정으로 이어지도록 연결해 왔습니다.

---

## About Me

### Experience

**글로벌 앱마켓 운영 데이터 분석 직무 수행**  
`2024.08 ~ 2026.10`

- SQL, Python 기반 사용자 행동 및 콘텐츠 성과 분석
- A/B Test 설계 및 통계적 검증
- 신규 서비스 사용자 참여 KPI 및 집계 기준 설계
- 체류시간 로그 이상치 분석 및 데이터 품질 기준 수립
- 주간 성과 분석 및 정기 리포트 운영

### Education

**경기대학교**  
응용통계학 학사 · 융합데이터공학 부전공  
`2017.03 ~ 2024.02`

### Training & Certification

- KT AIVLE School 5기 DX 컨설턴트 과정 수료
- 데이터분석 준전문가(ADsP)

---

## Key Data Projects

### 01. 운영 기준 전환 A/B Test

`SQL` `Python` `A/B Testing` `Statistics`

기존 운영 기준과 신규 기준의 성과를 비교하기 위해 한국과 브라질을 대상으로 A/B Test를 설계하고 통계적으로 검증했습니다.

- 핵심 지표: **Click → Download CVR**
- 한국 CVR: **7.41% → 11.43% (+54%)**
- 브라질 CVR: **15.56% → 26.97% (+73%)**
- Proportion Z-Test 및 Fisher Exact Test를 활용한 통계 검정
- 분석 결과를 기반으로 신규 운영 기준 전환

---

### 02. 사용자 참여 KPI 설계

`SQL` `KPI Design` `Event Log`

신규 서비스의 사용자 참여 수준을 측정하기 위해 1Depth와 2Depth 행동 로그를 하나의 성과 체계로 정의했습니다.

- **Full Engagement / 1Depth Engagement / 2Depth Engagement** 정의
- 사용자 × 날짜 × 콘텐츠 단위 행동 로그 집계
- 주간 Unique User 기반 KPI 산출 로직 설계
- 집계 SQL 및 정기 리포트 구축
- 유관 부서 KPI로 채택

---

### 03. 체류시간 로그 품질 기준 수립

`Python` `EDA` `Data Quality`

체류시간 로그 분포를 분석해 평균과 최대값을 왜곡하는 이상 로그를 확인하고 제외 기준을 수립했습니다.

- 체류시간 분포 및 이상치 EDA
- **300초 초과 로그 약 0.56%** 확인
- 스크롤 조건, 1초 미만 로그 제외 등 대안 기준 비교
- 최종 **300초 초과 로그 제외 기준** 적용
- 고객사 통계 시스템 산출 기준에 반영

---

### 04. 저성과 콘텐츠 Cutoff 기준 분석

`SQL` `Python` `Distribution Analysis`

반복 전시 콘텐츠의 성과 판단 기준을 마련하기 위해 Full Engagement 분포를 분석하고 저성과 구간을 검토했습니다.

- 주차별 콘텐츠 성과 데이터 집계
- Histogram, KDE, CDF 기반 성과 분포 분석
- Percentile 비교를 통한 저성과 구간 탐색
- **P25 Full Engagement = 1,965**
- P25 기반 Cutoff 및 반복 저성과 콘텐츠 **3-Out 기준 검토**

---

## Tech Stack

### Data Analysis

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)

### SQL & Data

![SQL](https://img.shields.io/badge/SQL-336791?style=flat-square)
![Amazon Athena](https://img.shields.io/badge/Amazon_Athena-232F3E?style=flat-square&logo=amazonaws&logoColor=white)
![BigQuery](https://img.shields.io/badge/BigQuery-669DF6?style=flat-square&logo=googlebigquery&logoColor=white)

### Analysis

`A/B Testing` `KPI Design` `EDA` `Data Quality` `Statsmodels`

### Visualization & Reporting

`Matplotlib` `Seaborn` `Excel`

---

## Portfolio

### Data Analysis Code Portfolio

💻 **[data-analysis-portfolio](https://github.com/wonbin-DA/data-analysis-portfolio)**

SQL과 Python을 활용한 프로젝트별 분석 코드와 익명화 Sample Data를 정리합니다.

### Portfolio PDF

📄 **[View Portfolio](./Portfolio_DA.pdf)**


---

## Contact

**E-mail**  
[onebean5475@gmail.com](mailto:onebean5475@gmail.com)
