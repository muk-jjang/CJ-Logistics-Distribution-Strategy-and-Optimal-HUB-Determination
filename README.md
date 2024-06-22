# CJ-Logistics-Distribution-Strategy-and-Optimal-HUB-Determination
2023-1 SCM 텀 프로젝트 CJ대한통운 유통전략 및 최적의 HUB 결정

## 문제 정의
1. 온라인 쇼핑시장 확대, 라스트마일에서 정교하고 선택의 다양성이 높은 서비를 원함
2. Last Mile이 물류 프로세스에서 41%의 비용을 차지함

## 해결 방안
앞으로의 물류는 Last Mile의 강세가 지속될 것이라 보고 전략적 계획을 제안함
1. 최적의 HUB 터미널 입지 선정
2. 새로운 HUB를 고려한 물량 할당

## Datasets
1. 서울시 CJ대한통운 택배 유형별 월 데이터
2. 서울시 자치구단위 CJ택배차량 운행량 월별 통계
---
### 1. 최적의 HUB 터미널 입지 선정
- Gravity Model 사용
- 대분류 품목별 착지데이터의합
- 원/건당 단위거리 = (월별 운행시간/운행대수*택배기사시급) / 운행거리 평균

![image](https://github.com/muk-jjang/CJ-Logistics-Distribution-Strategy-and-Optimal-HUB-Determination/assets/122384236/55df4e20-b188-414e-b2fd-1bacf30b0f05)


### 2. 새로운 HUB를 고려한 물량 할당
- Allocation Model 사용
- 여러 Fixed Cost를 재무제표, 토지면적을 보고 추정
![image](https://github.com/muk-jjang/CJ-Logistics-Distribution-Strategy-and-Optimal-HUB-Determination/assets/122384236/baeabdba-a9df-41af-b92a-152dcc93b511)




