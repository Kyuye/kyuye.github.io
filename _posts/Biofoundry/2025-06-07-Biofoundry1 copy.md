---
layout: post
title: "바이오파운드리는 무엇인가"
date: 2025-06-07
excerpt: "요즘 핫한 바이오파운드리에 대해서 일목요연하게 정리해본다."
tags: [sample post, readability, test]
permalink: /posts
lang: kr
comments: true
---


## 최근 생명과학계 뉴스 스크랩해보니..

실험 후 여러 바이오 기사를 검색하던 중 “한국도 바이오파운드리 만든다”는 기사를 확인했다.

국가에서 1,200억 원이 넘는 예산을 투자하여 공공 바이오파운드리를 구축한다는 내용이다. 올해인 2025년부터는 합성생물학 육성법이 본격 시행된다고 한다.

우리나라가 이런 사업을 추진하고 있다니 놀라웠다.

이제는 과학기술정보통신부 문서에도 “공용 바이오파운드리 구축” 같은 용어가 사용되고 있다. 미국·영국·호주 등은 이미 수년 전부터 글로벌 협력 센터를 운영해 왔다고 한다.



## 오늘도 실험실은 바쁘다

언제는 인서트 방향이 뒤집혔고, 콜로니가 생기지 않은적도 있었고 시퀀싱 결과가 맞지 않기도 했다. 

하루 종일 실험한 후, 미니프렙 후 전기영동을 돌린 뒤 밴드가 보이지 않거나 시퀀싱 결과가 맞지 않으면 허탈하다.

다시 플라스미드 설계표를 열어보며 “무엇이 잘못 됐는지”를 곰곰이 되새긴다.

실험은 반복의 연속이다. 가끔은 감동적으로 성공하기도 한다. 그러나 대부분은 복붙과 삽질 사이 어딘가에 머문다.


## 바이오파운드리란?

결론부터 말하자면, 바이오파운드리는 매일 파이펫으로 수행하는 DBTL 사이클을 자동화해 주는 시스템이다.

### DBTL = Design – Build – Test – Learn

<img src="https://webzine-eng.snu.ac.kr/web/vol126/img/sub0103_09_15.jpg" alt="biof1">  
출처: 서울공대 웹진  

즉,

1. 설계(Design)
2. 유전자 회로 구축(Build)
3. 실험 수행(Test)
4. 결과 기반 설계 개선(Learn)

사람이 손으로 하던 것을 기계가 빠르고 정확하게, 대량으로 수행하게 만든 개념이다.


## 생명과학계의 ‘공장’에 비유

Foundry라는 용어는 반도체 업계에서 유래했다. 설계는 외부에서 받고 생산만 맡는 곳을 의미한다. 이 개념을 바이오 분야에 적용한 것이 바이오파운드리이다.

Biofoundry는 생물학적 부품(유전자, 회로, 균주 등)을 설계 파일로 전달하면 기계가 자동 제작해 주는 공장이다.

예를 들어 대사경로 최적화를 시도할 때,

* **전통적 방법**: 클로닝 설계 → PCR → 벡터 삽입 → 형질전환 → 발현 테스트를 약 50회 반복한다.
* **바이오파운드리**: 설계 파일 입력 → 로봇 자동 조립 → 자동 발현 테스트 → 데이터 추출 → AI 해석 → 설계 개선

사람은 커피를 마시며 결과를 모니터링하기만 하면 된다.ㅎㅎ

<img src="https://image.dongascience.com/Photo/2023/01/9b25a0c2eb6b12cb393bbea5b3f8374c.jpg" alt="biof">  
출처: 동아사이언스  

## 장점

* 파이펫팅 실수 없음
* 로봇이 떨림 없이 작업한다
* 하루 10회 실험을 100회로 확장 가능하다
* 실험 결과가 자동으로 데이터베이스에 저장된다 → 엑셀 관리 불필요
* 재현성이 뛰어나다 → 실험자 컨디션에 의존하지 않는다
* 실패 데이터도 학습 자산으로 활용된다 → 머신러닝이 다음 설계를 개선한다

실험실 전체를 자동화된 시스템으로 업그레이드하는 셈이다.

## 실제 구성

바이오파운드리는 DBTL 각 단계에 핵심 장비와 소프트웨어를 통합하여 운영한다.

### Design

유전자 회로 설계 도구 활용한다.
최근에는 AI가 최적 조합을 추천한다.

### Build

Liquid handler가 DNA 시료를 혼합한다.
PCR, 클로닝, 형질전환을 자동화하여 휴먼 에러를 최소화한다.

### Test

Plate reader, FACS, LC-MS 등 고속 측정 장비와 연동하여 대량 발현을 확인한다.

### Learn

실험 결과를 자동 저장한다.
머신러닝이 분석하여 “다음은 이 조건을 시도해 보라”고 제안한다.
자동 설계 루프가 실행된다.

## 현재 활용 기관

* Ginkgo Bioworks: 바이오파운드리 선도 기업
* Edinburgh Genome Foundry: 유럽 대표주자, 유전자 부품 제작·표준화 선도 기관
* Australian Genome Foundry: 호주 정부 투자 대형 설비
* MIT-Broad Foundry: 대규모 파운드리 시설

## 한국의 현황

아직 개인 연구자가 이용할 수준은 아니다. 장비가 고가이고 통합 운영 환경이 부족하다.

그러나 KAIST, POSTECH, 서울대, 한국생명공학연구원 등에서 일부 자동화 시도를 진행 중이다. 과기부는 2024년부터 2029년까지 1,263억 원을 투자하여 국가 바이오파운드리 구축 계획을 발표했다. “공공 바이오파운드리 플랫폼”을 마련하여 중소 연구자도 활용할 수 있게 할 예정이다.

머지않아 설계 파일만 전달하면 실험 결과를 자동으로 받아볼 수 있는 세상이 도래할지도 모른다.
물론 모든게 자동화 되는건 단계별로 진행 되야할 것이고 자동화 되더라도 연구자가 더블체킹을 해야할 것이다.

AI와 로보틱스를 전공한 나로서는 바이오파운드리에 관심이 갈 수 밖에 없다.
앞으로 이에 대해서 계속해서 글 올려보려고 한다. 




바이오파운드리는 생명과학 실험 자동화의 정점이다. 반복 실험, 사람의 파이펫팅, 재현성 우려를 모두 기계가 해결한다. 아직은 꿈 같지만 한국도 빠르게 따라잡고 있다. 
언젠가 우리 실험실에도 도입되기를 기대하면서 오늘도 파이펫을 든다.


## 참고논문&출처

Hillson, N. J., et al. (2019). Building a global alliance of biofoundries. Nature Communications, 10, 2040.

Chao, R., et al. (2017). Engineering biological systems using automated biofoundries. Metabolic Engineering, 42, 98–108.

Kitney, R., et al. (2019). Enabling the Advanced Bioeconomy through a Global Biofoundry Network. ACS Synthetic Biology, 8(7), 1564–1567.

https://www.hkn24.com/news/articleView.html?idxno=344159

https://m.dongascience.com/news.php?idx=71428

https://www.sedaily.com/NewsView/2GRH9UIC76

https://zdnet.co.kr/view/?no=20241223211743

https://www.igb.illinois.edu/article/nsf-invest-5m-reliable-and-scalable-biofoundries-biomanufacturing-and-global-bioeconomy

https://agilebiofoundry.org/agile-biofoundry-seqwell-partnership-announcement

https://www.nsf.gov/news/nsf-international-partners-invest-82m-six-2024-global