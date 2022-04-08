# < 리뷰분석을 통한 빅데이터 IT회사 선별 >
<br>


## 0. 업로드 파일
 - 리뷰분석을 통한 빅데이터 IT회사 선별(쥬피터 놋북 파일)
 - 리뷰분석을 통한 빅데이터 IT회사 선별(PDF 파일)
<br>
    
## 1.배경&목적  
 - 텍스트데이터를 수집 및 활용하여 배운 것을 바탕으로 프로젝트 한 건을 자율적으로 수행
 - 프로젝트 개요: 이번 프로젝트는 잡플래닛에 등록되어 있는 총 3389개의 IT회사 중에서 빅데이터와 관련 있으면서 실제 현장의 업무 분위기 또한 좋은 IT회사를 선별해내는 것을 목표로 한다. 학부생들은 꿈을 향해 열심히 공부하고 있지만 안타깝게도 사회에 내가 지원하면 좋을 회사들은 어떤 회사들이 있는지, 회사들의 실제 현장 업무 분위기는 어떠한지, 어떤 장단점들이 있는지, 어떤 회사가 나에게 성향적으로 맞을지 알고 판단하기가 쉽지 않다. 이런 현실에서 나 또한 다르지 않다. 그래서 이번 프로젝트를 계기로 내가 지원목표로 하면 좋을 회사를 텍스트 분석을 통해서 찾아내 보고자 한다. 잡 플래닛의 리뷰를 여러 방면으로 분석하고 분석결과를 이용해 각 분석별로 기업들을 선별해낼 것이다. 그리고 선별된 기업들을 교집합하여 빅데이터와 관련이 있으면서 실제 현장의 업무 분위기도 좋은 IT회사들을 최종 선별하도록 한다.
<br>
    
## 2.주최/주관 & 참가 대상
 - 주최&주관: 국민대학교 유재명 교수 텍스트데이터분석 수업
 - 국민대학교 빅데이터경영통계전공 3~4학년 학생
<br>

## 3. 프로젝트 기간  
 - 2021년 1학기
<br>

## 4. 프로젝트 수행 과정
- 프로젝트 목표: 빅데이터 기업이면서 IT부서의 실제 현장 분위기도 좋은 기업들을 찾아내는 것
- 프로젝트 과정:
    - 조건0: 2021년도 1학기 프로젝트 수행 당시 총 3389개의 IT기업 중에서 기업의 리뷰수가 적어도 100개 이상인 기업 297개의 기업 리뷰 데이터 수집 (크롤링)
    - 조건1: 리뷰 데이터를 시각화하여 사람들의 전반적인 만족도를 조사하고 긍정의 비율이 0.5보다 높은 회사들을 선별
    - 조건2: 리뷰 데이터의 장점, 단점을 단어구름화하여 IT부서의 장단점을 살펴보고 장점구름에 있는 단어의 비율이 전체 평균보다 높은 회사들을 선별
    - 조건3: 리뷰 데이터의 기업 한줄평을 감성분석하여 리뷰별 감성예측을 해보고 결과로 나온 긍정토큰들의 비율이 전체 평균보다 높은 회사들을 선별
    - 조건4: 리뷰 데이터의 기업 한줄평을 주제분석하여 빅데이터와 관련된 주제와 단어목록들을 찾아보고
        빅데이터에 가중치를 주고 관련 단어목록의 비율이 높은 회사들을 선별
    - 조건1~조건4를 모두 만족하는 회사들의 데이터를 시각화하여 내가 지원을 목표로 하면 좋을 회사들 최종 선별

 - 프로젝트 목차
    - Part1. 라이브러리
    - Part2. 웹 크롤링
    - Part3. 데이터 전처리
    - Part4. 데이터 EDA
    - Part5. 단어구름
    - Part6. 감성분석 모델링
    - Part7. 주제분석 모델링
    - Part8. 최종 기업선별 및 결론
  
 - 최종선발된 기업들, 긍정비율순
    1. 구글코리아(유)
    2. 네이버(주)
    3. (주)연합뉴스
    4. SK텔레콤(주)
    5. (주)카카오
    6. 라인플러스(주)
    7. (주)넥슨코리아
    8. 이베이코리아(주)
    9. (주)엔씨소프트
    10. 삼성에스디에스(주)
    11. 엔테크서비스(주)
    12. (주)비바리퍼블리카

