﻿# Analysis-of-consumption-data-in-the-metropolitan-area
 
- 수도권 지역을 중심으로 파이썬 pandas를 활용한 소비 데이터 분석 (Consumption data were analyzed using python pandas, centering on districts in the metropolitan area)

- 데이터 전처리 및 시각화 작업의 일부가 데이터 센터에서 이루어짐 (Some of the data preprocessing and visualization took place in the data center)

## Process

### 1. Select a topic

- 지역화폐 활성화를 위한 방안 (Measures to Revitalize Local Currency)

### 2. Data Selection

- SDC통계데이터센터: 내국인 국내카드 소비(신한카드)

### 3. Data Preprocessing

- 업종 재분류 데이터 (Industry reclassification data)
- 분기별 카드 사용량 합병 데이터 (Quarterly Card Usage Merger Data)
- 시군구 지역별 업종에 따른 카드 사용량 분기 데이터 (Quarterly data on card usage by industry in the city and county districts)
- 지역별 업종에 따른 카드 사용량 순위 데이터 (Card usage ranking data by industry by region)
- 나이별 업종에 따른 카드 사용량 데이터 (Card usage data by age industry)
- 나이별 지역에 따른 카드 사용량 데이터 (Card usage data by age region)

### 4. Data Visualization

- 지역 경계데이터: https://github.com/southkorea/southkorea-maps/tree/master/kostat/2018/json
- folium
- matplotlib
- seaborn

### 5. report writing

- report: https://github.com/dania0x4C/Analysis-of-consumption-data-in-the-metropolitan-area/blob/main/report.ipynb

## references

1. 코드포코리아(2024). 지역화폐로 할게요. (https://localpay.codefor.kr/)
2. 김건호, 신기동, 유영성, 김재신, 최윤식, 남승균. (2022). 경기지역화폐 운영제도 개선방안 연구. 경기연구원.
3. 김건호, 김태영, 마주영, 김현. (2021). 지역화폐의 경제적 효과에 관한 연구 : 경기도를 중심으로. 경기연구원.
4. 최준호, 원도연. (2024). 지역화폐와 지역회복력 연구. 지역사회연구
