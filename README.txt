1. 제출파일 목록
    1) README.txt: 코드 실행 방법 설명
    2) Raw : 수집하고 합치기 전 모든 기본 raw 데이터들이 있는 파일
    3) 1_Merge.ipynb : 기본 raw데이터를 합쳐 전체 데이터셋을 구축하는 파일
    4) 2_Preprocessing.ipynb : 전처리 및 시각화 과정이 담긴 파일
    5) 3_FeatureSelect.ipynb : 여러 방법으로 변수 선택한 과정이 담긴 파일
    6) 4_Modeling.ipynb : 다양한 모델과 손실함수로 최적의 모델을 찾는 파일

2. Data 획득 방법
    데이터를 획득 하기위해 국토교통부, 네이버 부동산, KOSIS, 서울 열린데이터 광장, 공공데이터 포털, 한국은행 등을 이용하여 csv파일로 다운로드 받아 사용
    - 국토교통부 : 2018년 부터 2023년 2분기까지 서울 지역의 실거래가 데이터 획득
    - 네이버 부동산 : 2018년 부터 2023년 2분기까지 서울 지역의 실거래가 추가 데이터크롤링 
    - KOSIS, 서울 열린데이터 광장, 공공데이터포털, 한국은행에서 여러 경제지표와 서울 지역별 인구수, 평균연령 데이터 획득

3. 실행 필요 프로그램과 라이브러리
    1) python
    2) jupyter notebook / jupyter lab
    3) 라이브러리 (코드 실행시 설치가능 (별도 설치 불필요))
	- pandas
	- numpy
	- matplotlib
	- seaborn
	- math
	- scikit-learn
	- lightgbm
	- xgboost
	- catboost
	- optuna
	- statsmodels

4. 실행방법
    1) 제출한 압축 파일을 풀기
    2) 코드 파일(*.ipynb)들과 데이터 파일들이 있는 raw폴더(총 44개의 csv파일)가 동일한 작업 폴더인지 확인
    3) jupyter notebook 실행하여
	1) 1_Merge.ipynb
	2) 2_preprocessing
	3) 3_Modeling.ipynb
	순서로 실행