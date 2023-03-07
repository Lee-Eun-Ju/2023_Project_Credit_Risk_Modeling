# 2023_Project_Credit_Risk_Modeling
Credit Risk Modeling in Python 2023 (Udemy)

### 1. Credit Risk (What is credit risk? Why it is important?)

#### 1) Credit vs Debtor
- Creditor(채권자) : 미래에 상환할 것이라는 신뢰하에, 채무자에게 신용(상품과 서비스)을 제공
- Debtor(채무자) : 상품과 서비스를 이용하며, 이자를 지불
- Ex) 신용카드 - 신용 한도까지 사용 후 금액과 이자를 상환  
  Ex) 주택 담보 대출 - 거주지의 지분에 대해 돈을 빌리고 갚지 못할 경우를 대비하여 거주지 자체가 부채를 충당  
  Ex) 에셋 파이낸싱 - 기업이 장비를 얻기 위해 합의된 기간동안 정기적인 요금을 지불

#### 2) Credit Risk
- Credit Risk : 채무자가 채권자에게 대출금을 상환하지 않을 가능성  
  (1) Default(채무불이행) : 채무 원금과 이자를 지급받지 못해 발생하는 손실 발생   
  (2) Collection Cost(회수 비용) : 미상환 부채를 회수하기 위한 비용 발생
  
- 채무불이행 위험을 줄이기 위한 방법  
  (1) 미상환 부채를 충당할 담보 요구  
  (2) 신용 위험이 높은 대출자의 이자율 조정  
  => 채무자의 신용 평가, 즉 신용 위험을 정확히 측정하는 것이 중요
  

### 2. Expected loss (EL) and it's components

#### 1) Expected Credit Loss
- 예상 손실의 종류  
  (1) 차용인의 특정 요인  
  (2) 경제 환경  
  (3) 차용인의 특정 요인과 경제 환경의 조합  
  
- 대출기관의 손실은 전체 경제 환경에 영향을 줄 가능성이 높으므로  
  신용위험과 관련된 예상 손실을 추정하는 것이 중요! = 기대신용손실(Expected credit loss)

#### 2) Credit Risk Modeling Framework
- 신용위험모델링 = 채무불이행 확률(PD) * 채무불이행 손실(LGD) * 채무불이행 익스포저(EAD)  
  (1) PD (Probability of Default): 채무자가 부채를 전액 또는 제때에 상환할 수 없거나 상환할 의사가 없을 가능성 (시간지평)  
  (2) LGD (Loss Given Default): 채무자가 채무 불이행시 손실되는 자산의 몫 (총 익스포저에서 대출기관이 회수할 수 없는 비율)  
  (3) EAD (Exposure at Default): 채무불이행시 대출기관이 리스크에 노출되는 총 가치 (은행이 잃을 수 있는 최대 금액)  

- Ex) 500,000 달러의 집 구매 / 대출 기관 : 구입 금액의 80% 지원  
  => 400,000달러 중 채무자는 40,000달러 상환, 미상환 잔액: 360,000 => EAD = 360,000  
  => 주택 소유자 4명 중 1명이 채무 불이행했다는 경험적 증거 => PD = 25%  
  => 채무불이행 시, 은행이 집을 팔아 342,000달러 회수 가능 => LGD = 18,000/360,000 = 5%  
  => 신용위험 = 25%(PD) * 5%(LGD) * 360,000(EAD)  
  
  
### 3. Capital Adequacy, Regulations, and the Basel II Accord
  
  
### 4. Basel II approaches: SA, F-IRB, and A-IRB


### 5. Different ffacility types (asset classes) and credit risk modeling approaches




  
