---
layout: page
title: About
permalink: /about/
image: jshoon2.jpg
---

## "Profile"

#### 학교

- 건국대학교(2010.03 - 2017.08)
  환경과학과(4.21 / 4.5)

#### 직장

- 신세계아이앤씨(2019.04 - 현재)
  AI팀 - AI개발

#### 메일

- jshjsh06@naver.com

#### 깃헙

- https://github.com/jshjsh06



---



## "Introduce"

#### 관심분야

- AI, Data Engineering, Database, Sales Forecasting



#### 자기소개

- 데이터 분석 및 AI 개발자로 현 신세계아이앤씨 AI Lab팀에서 근무하고 있습니다. 주로 유통 업계의 데이터 분석 및 수요예측의 프로젝트를 진행하고 있습니다. 특히, 수요예측 서비스의 메인 개발자로 대형 마트에 해당 서비스를 적용한 경험이 있습니다.

  데이터 분석을 진행함에 있어 자신만의 시야에 갇히지 않기 위해 직무의 팀 구성원들과 적극적으로 커뮤니케이션하며 협업해오고 있습니다. 또한 분석 도메인의 지식을 충분히 탐구하고 이해하며, 데이터를 집요하게 파고들어 유의미한 인사이트를 발굴할 수 있도록 노력하고 있습니다.

  끊임없이 배우고 성장하는 일을 좋아합니다. 이를 위해 새로운 일에 도전하고 다양한 시도를 접목하기 위해 노력하고 있습니다. AWS 인프라, 도커, 하둡 에코시스템 등 다양한 지식을 습득하고 적용할 수 있도록 교육과 배움에 적극적으로 임하고 있습니다.

  

#### 경력

**신세계아이앤씨, AI Lab팀 내 AI 개발(2019.04 - 현재)**

- 대형마트 일반 상품 수요예측 서비스 개발
- 대형마트 행사 상품 초도발주 수요예측 서비스 개발
- 대형마트 명절 사전예약 상품 매출 분석 및 예측
- 대형마트 신선상품의 실물재고 분석 및 예측
- Google Causal Impact를 활용한 행사 상품 요인 분석
- 날씨 요소가 매출에 미치는 영향 분석
- 백화점 챗봇 구축 참여

**환경사회학 연구실, 학부생 연구원(2015.02 ~ 2017.08)**

-  '귀산촌 활성화 연구' 프로젝트 참여. 귀산촌 600만 개 원자료 데이터 분석



#### 주요 활동 및 수상실적

- 2018 삼성멀티캠퍼스X멋쟁이사자처럼 아이디어톤 및 해커톤 최우수상
- 2020 고용노동부 주관 신세계아이앤씨 인턴 서비스기반의 웹 프로그래밍 구현과정 최종 프로젝트 1위
- 신세계아이앤씨 외부 매체 활동
  - 유통업 수요예측 서비스 사업 확대 기사 : https://www.news1.kr/articles/?3897513
  - AI 분석 파트 내 수요예측 서비스 소개 블로그 : https://post.naver.com/viewer/postView.nhn?volumeNo=26919904&memberNo=42472601



#### class

- AWS 기반 빅데이터 분산처리 기술 교육(2020.12)

- 신세계아이앤씨 - 서비스기반의 웹 프로그래밍 구현과정(2019.01 - 2019.03)

- 딥러닝 기반 핵심 산업별 빅데이터 분석 전문가 과정(2018.09 - 2019.01)

- 지능형 IoT 서비스 개발 전문가(2017.12 - 2018.07)

  

#### 보유 기술

**Programming Language**

- Python, Java, Javascript, Ruby

**Frontend & Backend Framework**

- Spring

**IoT**

- Raspberry PI, Cortex-M4

**Infra**

- AWS, GCP, Docker

**Database**

- PostgreSQL, Oracle



---



## Work Experience

#### 1. 대형마트 수요예측 서비스 개발

- 대형마트에서 판매하는 일상/가공 상품 대상 **클라우드 기반 AI 수요예측 서비스**를 구축하였습니다. 상품 특색에 맞춰 학습을 진행하여 일자별, 상품별 판매량을 예측합니다.

  물류 또는 점포에서 진행하는 **발주의 정확도가 낮다면 재고비용이 상승하거나 결품이 나타나게 되어 기회 손실이 발생**합니다. 이러한 Pain point를 해결하는 것에 초점을 맞추었습니다.

  **상품의 판매 이력, 가격, 행사, 타임라인 등 다각도로 데이터를 분석**하여 수요예측 모델을 구축하였습니다.

  ＊데이터 전처리 및 파생변수 생성

  ＊판매 기반 클러스터링 생성

  ＊XGBoost 및 앙상블 모델 구축

  ＊전체 서비스 구조 설계 및 구현

  

**[수요예측 서비스 전체 인프라]**

＊AWS 기반 인프라 구축

＊AWS ECR을 통한 도커 사용

![]({{ site.baseurl }}/images/demand_forecasting_infra1.jpg)



**[수요예측 서비스 프로세스 개요]**

＊일자별 판매데이터 수신 및 처리 모듈 구성

＊일정 주기별 모델 갱신 및 최신화 진행

＊일자별 앙상블 모델을 통한 예측 진행

![]({{ site.baseurl }}/images/demand_forecasting_infra2.PNG)



#### 2. 대형마트 명절 사전예약 상품 매출 분석 및 예측

- 대형마트에서 설날 및 추석 **명절 1~4주 전 기간동안 판매하는 사전예약 상품의 매출 추이를 분석하고 매출 예측**을 진행하는 프로젝트를 수행했습니다. 

  사전예약 기간 동안에는 2가지의 핵심 요인이 있습니다. 첫번째는 사전예약 기간 동안에는 일정 금액 이상 구매시마다 상품권 지급하며 각 금액 구간마다 지급율이 다릅니다. 두번째는 사전예약 기간은 1~3차 기간으로 구간을 나누어 진행하며 각 구간마다 상품권 지급율이 다릅니다. 이러한 핵심 요인을 중점으로 **과거의 매출, 경쟁사의 상품권 지급율 및 사전예약 기간 등을 종합적으로 분석**하여 매출 예측을 진행했습니다. 

  **2020년 추석 기준 최종 98%의 매출 예측 적중률**을 산출했습니다.

  ＊연도, 명절 종류, 행사 차수, 할인 금액 등 명절 특색을 고려한 데이터 분석

  ＊1~3차 사전예약 구간을 고려한 변수 정의

  ＊Catboost를 사용한 사전예약 매출 예측



**[Catboost 모델]**

＊명절 사전예약 기간에 한정된 판매 이력 데이터만 사용하여 학습 데이터가 적음에도 불구하고 타 모델 대비 정확도가 안정적임

＊과적합 위험도 적음

＊범주형 데이터를 명시적인 사전 처리(예: One-hot Encoding) 없이 자동 처리 가능

＊Gradient Boosting 계열 중 약 13~16배 빠른 학습 시간



**[대형마트 명절 사전예약]**

＊특정 금액 이상 구매시 상품권 지급

＊1~3차 사전예약 구간에 따른 상품권 지급율 차등

＊데이터 분석 결과 카드 할인 혜택은 고객에게 큰 구매 욕구를 발생시키지 못함

![]({{ site.baseurl }}/images/holiday_prediscount.jpg)



#### 3. 대형마트 신선상품의 실물재고 분석 및 예측

- 대형마트에서 판매하는 **신선상품의 전산/실사 재고차액을 비교 분석하고, 이를 기반으로 재고차액을 줄이는 프로젝트**를 진행했습니다.

  대형마트에서는 특정 기간마다 매장에 있는 상품들의 실제 재고를 모두 검수하여 이를 전산에 등록하여 전산재고량과 실사재고량을 동기화합니다. 하지만, **전 상품에 대해 인력이 일일히 재고를 검수하는 것에는 상당한 노동력이 필요**합니다. 이를 개선코자 실물재고 예측을 진행했습니다.

  해당 프로젝트에서는 **데이터 전처리가 가장 큰 핵심**이었습니다. 상품별 재고량에 이상치가 상당수 포함이 되어있을뿐만 아니라 중복데이터, 재고수량과 금액 불일치 등 데이터가 온전하지 못했습니다. 해당 프로젝트에서는 **재고데이터를 정밀하게 전처리를 진행하는 것에 초점**을 맞추었습니다.

  그 결과 **점포당 재고차액에 대해 평균 42.4% 개선율**을 산출했습니다.

  ＊재고량 이상치 기준 수립 및 전처리 진행

  ＊재고 단가, 재고 금액의 이상치 기준 수립

  ＊141개 점포 기준 분석 진행

  ＊이상 데이터에 대한 과적합 영향도를 줄일 수 있는 Catboost 사용



**[데이터 전처리 프로세스]**

＊실사/전산 재고차액이 크게 발생하는 상품 기준 분석

＊점포별 이상치 분석 진행 후 통합 이상치 제어 기준 수립

＊현업 담당자와 커뮤니케이션을 통한 이상 데이터 의미 파악

![]({{ site.baseurl }}/images/fresh_stock_preprocess.jpg)



#### 4. Google Causal Impact를 활용한 행사 상품 요인 분석

- 대형마트에서 진행하는 **행사 상품 대상으로 판매량이 변화하는 요인을 Google Causal Impact를 사용하여 분석**하는 프로젝트를 진행했습니다.

  대형마트의 행사 담당자들은 일정 주기마다 행사 상품을 선정하고 다양한 프로모션을 적용합니다. 행사가 끝난 후에는 행사 상품의 판매량이 계획 대비 다른 경우 또는 행사 상품으로 인해 다른 상품의 판매량이 변화한 경우 등 다양한 원인 분석에 많은 시간이 투입을 해왔습니다. **데이터 관점으로 행사 상품의 매출 요인에 대한 분석을 진행하여 분석 효율화 및 신뢰성을 높이기 위해** 해당 프로젝트를 진행했습니다.

  행사 상품 요인 분석에는 Google Causal Impact를 사용했습니다. **행사 시작 시점을 Intervention으로 설정하여 상품 판매량에 대한 다양한 요인을 공변량으로 투입**했습니다. **공변량이 설명하지 못하는 외적 요인을 추가 제공**하여 행사 상품 요인 분석을 진행했습니다.

  ＊Google Causal Impact를 활용하여 판매 요인별 영향도 산출

  ＊Causal Effect로 추정할 수 있는 외적 요인 발굴

  ＊신뢰할 수 있는 Causal Impact 결과를 위한 세부 기준 수립



**[Google Causal Impact]**

＊특정 개입(행사, 이벤트 등)이 제품에 미치는 영향을 측정하는데 중점을 둔 모델

＊'변수의 선형회귀', '개입 이전의 시계열', '개입 이후의 시계열' 3가지 요소를 기준으로 사용

![]({{ site.baseurl }}/images/causal_impact_graph.jpg)



**[판매 요인 발굴]**

＊판매에 영향을 미치는 요인을 사전에 분석하여 요인별 영향도 산출

＊금액, 시계열, 행사, 휴점일 등



**[외적 요인 발굴]**

＊판매에 영향을 미친 외적 요인을 사전에 분석하여 판매 원인에 대한 추가 분석

＊결품, 이상 판매, 신상품, 자기잠식상품 등

＊아래 그림은 자기잠식상품 분석 결과로 특정 행사 상품의 판매량이 폭등하면서 이와 연관된 다른 상품들의 판매량이 감소한 것을 볼 수 있음

![]({{ site.baseurl }}/images/cann1.jpg)



#### 5. 날씨 요소가 매출에 미치는 영향 분석

- 대형마트에서 판매하는 **전체 상품 대상으로 특정 기간에 날씨가 매출에 미치는 영향도를 분석**하는 프로젝트를 진행했습니다.

  특정 날씨의 변화는 대형마트의 특정 상품에 대해 매출의 변화를 만들어내는 요인이 되지만 전체 상품에 대비하여 영향도가 적다고 짐작해왔습니다. 하지만, 짐작이 아닌 **실제 과거의 판매 이력과 날씨 요소를 데이터 분석을 통해 신뢰성 있는 원인과 결과를 파악**하기 위해 해당 프로젝트를 진행했습니다.

  **날씨 요소는 기상청 데이터를 API로 수집**하였습니다. 이외에도 **특보, 미세먼지 등 날씨 요소를 추가로 수집하여 날씨 요소와 매출의 관계를 다각적으로 분석**하였습니다. 영향도 분석은 **회귀 기반 XGBoost 모델을 사용**하여 날씨 영향도를 산정했습니다.

  **날씨 분석 결과 상품 분류, 점포별 및 기간에 따라 날씨 영향도는 8~40%의 분포를 가지고 있음**을 확인할 수 있었습니다.

  ＊온도, 습도, 일기, 미세먼지, 특보 등 날씨 데이터 수집

  ＊가격, 할인 등 매출에 영향을 미치는 내부 요인 고려

  ＊XGBRegressor 모형을 사용하여 변수별 계수를 활용하여 날씨 영향도 추출
  

---



## Other Experience

#### 1. 편의점 폐기 상품 할인 플랫폼(팀 프로젝트)

- 신세계아이앤씨 인턴 프로젝트에서 편의점 폐기 상품 할인 플랫폼을 구현하여 최종 1위한 프로젝트입니다.

  편의점에서 판매하는 신선 상품들은 유통기한이 짧아 폐기가 필연적으로 발생하게 됩니다. 본사는 폐기 상품 지원 금액으로 인한 비용이 발생하고, 가맹점주는 폐기 상품으로 인해 실질적으로 금액적으로 손해를 보게 됩니다. 이러한 Weak point를 해결하기 위해 편의점 폐기 상품 할인 플랫폼을 기획했습니다.

  해당 플랫폼은 2가지 기능을 제공합니다. 첫번째로 편의점의 유통기한 임박한 상품을 확인하고 할인하여 구입할 수 있도록 합니다. 두번째로 편의점의 상품을 장바구니에 담고 해당 장바구니를 다른 사람과 공유하는 기능을 제공합니다.

  ＊안드로이드 앱을 통한 서비스 구현

  ＊Spring을 통한 POS System 구현

  ＊Firebase 및 Oracle을 통한 데이터베이스 구현



**[구현된 서비스]**

![]({{ site.baseurl }}/images/ssgmart_android.jpg)

![]({{ site.baseurl }}/images/ssgmart_pos.jpg)



#### 2. Kaggle - Facial Keypoints Detection(팀 프로젝트)

- '딥러닝 기반 핵심 산업별 빅데이터 분석 전문가 과정' 수강 당시 팀 프로젝트로 진행한 Kaggle 문제입니다. 사전에 주어지는 이미지 데이터에서 눈, 코, 입과 같은 특정 포인트에 학습하여 새로운 이미지에 대해 해당 포인트 위치를 감지해내는 과제입니다.
  주어진 데이터에서는 사용할 수 없는 이상 이미지 데이터를 구분하는 작업을 진행했습니다. 정제된 데이터를 CNN을 사용하여 학습 및 예측을 진행했습니다.

![]({{ site.baseurl }}/images/facial.png)



#### 3. PT프로그램 소셜커머스 HEATS(팀 프로젝트)

- '지능형 IoT 서비스 개발 전문가' 과정 중 멋쟁이사자처럼 교육단체가 진행한 해커톤에서 PT프로그램 소셜커머스 웹서비스를 구현하여 최우수상을 받은 프로젝트입니다.

  헬스, 골프 등 PT프로그램의 구입을 위해서는 일일이 헬스장을 찾아다니거나 지인을 통해 정보를 얻는 등 불편한 구조였습니다. 이에 착안하여 PT프로그램을 전문적으로 거래하는 소셜커머스를 중심으로 한 스포츠 플랫폼을 만들고자 했습니다. 루비 온 레일즈를 사용하여 PT프로그램 소셜커머스, 운동 장비 추천, 커뮤니티를 핵심 기능으로 웹서비스를 구축하였습니다.

  Ruby on Rails를 활용하여 웹페이지를 구축하고 데이터베이스와 연동하는 역할을 맡았습니다. 또한 실제 결제모듈을 입혀 결제 서비스를 구현했습니다.



**[구현된 서비스]**

![]({{ site.baseurl }}/images/heats.png)



#### 4. 스마트 화분 챗팟(팀 프로젝트)

- '지능형 IoT 서비스 개발 전문가' 과정 중 지능형 IoT 플랫폼 구축 프로젝트에서 4명의 팀원과 함께 스마트 화분 '챗팟'으로 과정 내 1위를 한 프로젝트입니다.

  식물관리를 주제로 집에서 식물을 키우는 사람들에게 반려식물이라는 의미가 부합될 수 있는 3세대 스마트 화분 '챗팟'을 기획했습니다. 자바와 파이썬을 사용하여 메인서버를 중심으로 주기적 또는 사용자 요청에 따라 화분에 해당하는 라즈베리파이의 온도, 습도, 조도 등의 센서값을 체크하여 스마트폰 앱으로 JSON형식으로 데이터를 송수신하도록 했습니다. 이러한 데이터 값을 바탕으로 채팅엔진을 직접 제작하여 소통하는 스마트 화분을 만들었습니다.

  해당 프로젝트의 팀원으로서 Java기반의 Android Studio를 사용하여 안드로이드 앱 제작 역할을 맡으며 바인딩 서비스를 활용하여 서버와 TCP/IP 통신을 구축하였습니다. 그리고 사용자가 핵심적으로 사용하는 UI를 구축하였으며, JSON형식 프로토콜 작성을 통해 라즈베리파이, 서버, 앱 간의 통신을 기획했습니다.



**[서비스 구성도]**

![]({{ site.baseurl }}/images/챗팟_구성도.png)

