### Analysis-Project

## 빅콘테스트(신한은행)
### 1. Django로 표현
### 2. 데이터 전처리
#### 2-1. 고객정보의 결측치는 = 미응답으로 처리
#### 2-2. 결측치있는 Column들의 상관계수 높은것 끼리 묶음
RETIRE_NEED(은퇴 후 필요자금)
- INCOM 0.45 (가구소득구간)
- TOT_ASSET 0.33 (총자산)
- ASS_REAL 0.3 (부동산자산)
- TOT_SOBI 0.31 (월총소비)

FOR_RETIRE(노후자금융_월저축액)
- TOT_ASSET 0.31 (총자산)
- ASS_FIN 0.39 (금융자산)
- M_TOT_SAVING 0.49 (월총저축액)
- M_JEOK 0.38 (월저축액_적금)
- M_SAVING_INSUR 0.32 (월저축액_저축성보험)
- TOT_FUND (금융상품잔액_펀드)

TOT_YEA(금융상품잔액_정기예금)
- TOT_ASSET 0.4 (총자산)
- ASS_FIN 0.71 (금융자산)
- TOT ELS_ETE 0.35 (금융상품잔액_ELS/DLS/ETF)
- TOT JEOK 0.34 (금융상품잔액_적금)  

TOT_JEOK(금융상품잔액_적금)
- TOT_ASSET 0.37 (총자산)
- ASS_FIN 0.6 (금융자산)
- M_TOT_SAVING 0.36 (월총저축액)
- M_JEOK 0.33 (월저축액_적금)
- TOT_YEA 0.34 (금융상품잔액_정기예금)
- TOT_FUND 0.32 (금융상품잔액_펀드)

TOT_CHUNG(금융상품잔액_청약)
- ASS_FIN 0.42 (금융자산)
- TOT_JEOK 0.31 (금융상품잔액_적금)
- TOT_FUND 0.32 (금융상품잔액_펀드) 

TOT_FUND(금융상품잔액_펀드)
- TOT_ASSET 0.43 (총자산)
- ASS_FIN 0.69 (금융자산)
- FOR_RETIRE 0.30 (노후자금융_월저축액)
- TOT_JEOK 0.35 (금융상품잔액_적금)
- TOT_CHUNG 0.32 (금융상품잔액_청약)
- TOT_ELS_ETE 0.44 (금융상품잔액_ELS/DLS/ETF)

TOT_ELS_ETE(금융상품잔액_ELS/DLS/ETF)
- TOT_ASSET 0.35 (총자산)
- ASS_FIN 0.57 (금융자산)
- TOT_YEA 0.35 (금융상품잔액_정기예금)
- TOT_FUND 0.44 (금융상품잔액_펀드)

TOT_SOBI(월총소비금액)
- TOT_ASSET 0.40 (총자산)
- ASS_REAL 0.36 (부동산자산)
- M_TOT_SAVING 0.34 (월총저축액)
- RETIRE_NEED 0.31 (은퇴 후 필요자금)
### 3. 데이터 시각화
### 4. 아이디어 도출
