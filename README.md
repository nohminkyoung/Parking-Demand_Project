
팀원 3명
tem_github : https://github.com/kkkkyoung/parking_project

## 주제 : 데이콘 주차수요 예측 AI 경진대회(머신러닝을 이용한 아파트단지 주차수요예측)
- url : https://dacon.io/competitions/official/235745/overview/description

### 진행순서 
1. 문제유형 파악 및 평가지표 선정(수치예측/MAE사용-데이콘 측 평가규칙)
2. 데이터 탐색 - 데이터 시각화,결측치 확인, 상관관계 파악 등
3. 데이터 전처리 
4. 교차검증을 통한 모델선정
5. 예측
6. 성능 올리기

### 결과
- 1차시도(단지코드를 이용한 그룹화) : 113점
- 2차시도(test데이터의 버스정류장 이상치값을 평균으로 대체 추가) : 149점
- 3차시도(단지코드와 임대건물구분 두가지를 이용해 그룹화) : 112점
- 4차시도(전용면적을 범주화 한 후 새로운 컬럼으로 추가) : 120점
- 5차시도(3차시도에서 비슷한 값을 가진 데이터 삭제-전용면적별세대수,임대보증금) : 113점

### 미흡사항 및 보안할 점
- 분석에 대한 진행이 체계적으로 이루어질 수 있도록 분석방안에 대한 계획을 우선적으로 수립하면 좋겠다
- 데이터의 분포가 치우쳐져있기 때문에 로그변환을 실시해봤으면 좋았을것 같다
- 데이터들에 대한 도메인지식이 부족했다
