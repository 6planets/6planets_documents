# Idea Sprint

![](../Images/symbol.png)

## Cotents
[8/30 회의](#15-08-30)

<a name="15-08-30">
## 8/30 회의

### 박준호
- 한국노동패널 (https://www.kli.re.kr/klips/ko/main/main.jsp)
-- 노동과 관련되어 실제 설문조사하여 데이터를 모아두고 있음
- R언어에서 SAS 파일 읽기 방법
```
install.packages("sas7bdat")
library(sas7bdat)
klips <- read.sas7bdat("klips15h.sas7bdat")
# read.sas7bdat 사용시 약간의 시간이 걸립니다.
# 멈춘게 아닙니다. read하는데 10분 기다린 것 같습니다.
```
- R언어에서 엑셀파일 읽기 방법
```
install.packages("openxlsx")
library(openxlsx)
cost <- read.xlsx('cost.xlsx')
head(cost)
```

### 이가은
- 아이디어 트위터나 온라인상 기사에서 주가,경제관련 지수를 예측한 텍스트 데이터를 분석, 실제 주가와 경제지수의 변화가 얼만큼 일치하였는가?

참고) 미스터 마켓(Mr. Market)이란 가치투자 이론의 창시자 벤저민 그레이엄(Benjamin Graham)이 변덕스러운 주식시장을 의인화해 표현한 말입니다. 미스터 마켓은 약간 정신병을 앓고 있어서 기업의 좋은 면을 볼 때는 행복감으로 크게 올랐다가도 어떤 때는 심한 우울증에 빠져 크게 내려앉는 성격을 갖고 있습니다. 이 때문에 미스터 마켓은 조울증 환자라는 별명이 있기도 합니다.

### 임선희
- 네이버지도 api, D3.js 활용해 맛집 지도 만들기:
http://slownews.kr/43212
https://github.com/southkorea/southkorea-maps
- 데이터시각화 활용 실례 :
http://www.bloter.net/archives/236338
- 디자인 소스 참고 :
http://bl.ocks.org/mbostock

기대 수준에 못미치는 데이터를 얻는 이슈가 있음.
토픽을 제시하고 논의할때 데이터 소스까지 같이 논의해야할 것  같음.
소스 : 공공데이터, MOU, 스크래핑

### 이봉규
- 공공데이터에 올라온 시각화된 내용을 우리가 더욱 좋은 시각화 방법으로 제작해본다.

### 김소소
- 열정페이의 경우 탐사보도에서 <인터뷰>나 <서베이>를 통해 자료를 만드는 경우가 많았다.
- 해외의 경우, <뉴욕타임즈>나 <가디언>에서 임금을 시각화로 표현해둔 자료가 있다.

### 김우석
#### Visual Insight 발표
챕터 1 ~ 2장 내용

### 다음 안건
- 한가지 주제를 프로토타입삼아 진행해보는 것은 어떨까?
-- 열정페이
-- 난민
-- 여론과 주식의 관
-- 공공데이터 시각화
-- 어벤저스 (트위터 여론 이용)
- Visual Insight 챕터 분류
-- 챕터 3 김소소
-- 챕터 4 임선희
-- 챕터 5 이봉규
-- 챕터 6 이가은
-- 챕터 7 박준호
