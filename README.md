# 박윤수

<img src="https://readme-typing-svg.demolab.com?font=Noto+Sans+KR&weight=600&size=24&duration=3500&pause=1500&color=2A9D8F&vCenter=true&width=640&height=40&repeat=true&lines=%EC%9D%98%EB%A3%8C%20%EB%8D%B0%EC%9D%B4%ED%84%B0%EB%A5%BC%20%EB%B6%84%EC%84%9D%ED%95%98%EA%B3%A0%2C%20%EC%98%88%EC%B8%A1%20%EB%AA%A8%EB%8D%B8%EA%B3%BC%20%EC%84%9C%EB%B9%84%EC%8A%A4%EB%A1%9C%20%EC%9E%87%EB%8A%94%20%EA%B0%9C%EB%B0%9C%EC%9E%90" alt="의료 데이터를 분석하고, 예측 모델과 서비스로 잇는 개발자" />

의료·헬스케어 분야에서 데이터와 인공지능으로 더 나은 예측과 의사결정을 돕는 것을 목표로 합니다.

## Tech Stack

**Data · ML**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![LightGBM](https://img.shields.io/badge/LightGBM-02569B?style=flat-square)
![CatBoost](https://img.shields.io/badge/CatBoost-FFCC00?style=flat-square&logo=catboost&logoColor=black)
![SHAP](https://img.shields.io/badge/SHAP-FF0D57?style=flat-square)
![Optuna](https://img.shields.io/badge/Optuna-2C5BB4?style=flat-square)
![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=flat-square&logo=scipy&logoColor=white)
![seaborn](https://img.shields.io/badge/seaborn-4C72B0?style=flat-square)
![Tableau](https://img.shields.io/badge/Tableau-E97627?style=flat-square&logo=tableau&logoColor=white)

**Deep Learning**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![torchvision](https://img.shields.io/badge/torchvision-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![timm](https://img.shields.io/badge/timm-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![Grad-CAM](https://img.shields.io/badge/Grad--CAM-FF6F00?style=flat-square)
![CUDA](https://img.shields.io/badge/CUDA%20GPU-76B900?style=flat-square&logo=nvidia&logoColor=white)

**Web**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

## Projects

### 만성질환 생활습관 챌린지 웹 서비스
`2026.05–06` · 팀 프로젝트 4명 · [Repository](https://github.com/yunsu27/AH_03_01)

국민건강영양조사 데이터로 고혈압·당뇨·이상지질혈증 여부를 예측하고, 챌린지로 생활습관 개선을 돕는 웹 서비스

- **담당:** 질환 여부 예측 모델링, 챌린지·복약·커뮤니티 풀스택
- 특수 코드 도메인 처리와 파생 변수 설계로 피처 **74 → 172개**
- 성별 분리 2단계 스태킹(Base LightGBM 6종 → Meta 3종), 고혈압 **AUC 0.97**
- 커밋 260개 · **PR 54건 병합** · 팀원 PR 리뷰와 머지

### 칼로리 소모량 예측 AI 해커톤
`2026.02` · 팀 프로젝트 3명 · [Repository](https://github.com/yunsu27/calories-burned-prediction)

운동 시간·심박수·체온과 신체 정보로 소모 칼로리를 예측

- **담당:** 칼로리 소모량 예측 모델링, 발표
- 성별 분리 + Keytel 공식 기준선 위 잔차 학습 + 6개 모델 스태킹
- 리더보드 RMSE **6.40 → 0.29 (95.4% 감소)**, 과적합 해소

### 흡연 여부 데이터 분석 및 시각화
`2026.01` · 팀 프로젝트 4명 · [Repository](https://github.com/yunsu27/smoking-health-analysis)

건강검진 데이터로 흡연 여부에 따른 건강 지표 차이를 통계적으로 검증

- **담당:** 결측치 처리·전처리, 시각화, 가설 검정
- 나이대별 그룹 평균으로 결측치 처리, 파생 변수 5개 설계
- 흡연자 중성지방 **+36.88 mg/dL**, 충치 발생률 **+8.5%p** (t-검정·회귀 분석)

## Education

- **헬스케어 데이터 기반 인공지능 디지털 의료 웹서비스 개발자 양성과정** 수료 · 2025.12–2026.06

## Awards & Certifications

- **2026 K-Health 미개방 의료데이터 활용 경진대회 최우수상** · 2026.11
  - 개인 참가, 417팀 중 2위
  - 과학기술정보통신부·NIPA·건양대학교의료원 주최, 데이콘 운영
- SQL개발자(SQLD) · 2026.09
- 데이터분석준전문가(ADsP) · 2024.06

## Contact

- Email: yseull27@gmail.com
