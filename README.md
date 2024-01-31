# 여행 보험 패키지 상품 구매 예측(Travel Insurance Prediction)

<code><image height = "400"
src=https://github.com/siilver94/Travel-insurance-prediction/assets/57824945/249884b1-acc5-4dc8-9834-20ab3e1c2794></code>

<br/>

## 프로젝트 소개

과거 고객 이력을 기반으로 여행 보험 구매 여부를 예측하는 프로젝트입니다.

<br/>

## 프로젝트 구조

**1. 데이터 정보**
   
- 여행 보험 회사의 2019년 고객 데이터베이스로부터 데이터 추출
- 약 2000명의 고객에 대한 정보
  
<br/>

  
**2. 데이터 Feafures**

- **Age:** 고객의 나이
- **Employment Type:** 고객이 종사하는 업종
- **GraduateOrNot:** 고객이 대학을 졸업했는지 여부
- **AnnualIncome:** 고객의 연간 소득 (인도 루피, 50,000 루피 단위로 반올림)
- **FamilyMembers:** 고객 가족 구성원 수
- **ChronicDisease:** 만성 질병 여부
- **FrequentFlyer:** 최근 2년 동안 4회 이상 항공편을 예약한 여부
- **EverTravelledAbroad:** 외국 여행 경험 여부 (회사 서비스 이용과 무관)
- **TravelInsurance:** 2019년 소개 행사에서 여행 보험 패키지 구매 여부 (예측 대상)

<br/>
 
## 목표

- 여행 보험 구매 여부 예측(TravelInsurance 예측: `purchased`, `not purchased`)
  
- 예측 성능 평가를 위한 `accuracy_score` 사용


<br/>

  
### 시각화 및 상관분석

- `Plotly` 라이브러리를 활용한 시각화
- 변수 간 상관 관계 분석

<br/>


### 모델링

- `DecisionTreeClassifier`를 활용한 모델링
 
<br/>

 
### 사용 기술

**언어:** `Python`

**라이브러리:** `Scikit-learn`, `Plotly`


<br/>


### 평가 지표

`accuracy_score:` 모델의 전체 예측 정확도

<br/>



## 리뷰


해당 프로젝트를 진행하면서 고객 이력을 통한 여행 보험 구매 예측 모델 구축 경험과 Decision Tree 알고리즘의 이해와 활용 방법 숙지하고 Plotly를 이용한 시각화 능력 향상시켰습니다.

데이터에서 인사이트를 도출하는 과정이 흥미로웠고, 고객 특성에 따른 여행 보험 구매 패턴을 파악하는 것이 가치 있었습니다.

초기 데이터에서 불일치가 있어 처리하는 데 시간이 걸렸지만, 정확한 데이터로 변환하여 모델링에 활용했고 어떤 모델을 선택해야 할지에 대한 고민이 있었지만, Decision Tree가 데이터에 적합하다고 판단하여 선택했습니다.

추후 모델 성능 향상을 위한 파라미터 튜닝 및 다양한 알고리즘 적용과 모델 결과를 활용하여 여행 보험 패키지를 고객에게 효과적으로 마케팅하는 전략 수립하면 더 좋을 것이라고 판단됩니다.
