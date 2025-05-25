---
layout: post
title: "바이오파운드리가 뭐야"
date: 2025-05-25
excerpt: "요즘 핫한 바이오파운드리에 대해서 일목요얀하게 정리해봄."
tags: [sample post, readability, test]
permalink: /posts
lang: kr
comments: true
---


# 바이오파운드리가 뭐야?

요즘 뉴스 보면 자꾸 이 단어가 보여서 실험 중간에 끄적여봄.

## 최근 생명과학계 뉴스 스크랩해보니..

며칠 전에도 그랬음. 실험 기다리면서 넷 다 뒤져보다가 “한국도 바이오파운드리 만든다”는 기사를 봤음.

국가에서 1,200억 넘게 투자해서 공공 바이오파운드리 만든다 하고,

2025년부터는 합성생물학 육성법도 본격 시행이라던데…

...음? 우리나라가 이런 걸 한다고?

뭔가 거창한 단어라 남의 나라 얘기인 줄만 알았는데, 이제는 “공용 바이오파운드리 구축” 이런 단어가 과기부 문서에 써 있음.

게다가 미국, 영국, 호주 쪽은 이미 몇 년 전부터 글로벌 협력 센터 같은 것도 만들고 있었다고 함.

(그동안 나만 몰랐던 거 같아서 왠지 억울함…)

그래서 궁금해졌음. 바이오파운드리, 그게 정확히 뭐길래 다들 설치고 난리인 건지.

지금 내가 실험실에서 피펫으로 해결하려는 걸, 그쪽은 이미 로봇으로 돌리고 있는 거 아님?

## 오늘도 실험실은 바쁨

그럼 그렇지.

어제는 인서트 방향 뒤집힘. 오늘은 콜로니 안 뜸. 내일은 시퀀싱 안 맞을 예정임.

하루종일 미니프렙 하다가, 전기영동 돌리고, 밴드 안 보이면 잠깐 현타 오고,

다시 플라스미드 짜는 설계표 열어보다가 “이거 왜 했지” 생각하면서 고개 끄덕여봄.

실험은 반복임. 가끔 감동적이게 성공도 함.

근데 대부분은... 복붙과 삽질 사이 어딘가에 있음.

## 바이오파운드리란?

결론부터 말하자면,

바이오파운드리는 우리가 매일 피땀눈물 넣는 DBTL 싸이클을 자동화해주는 시스템임.

DBTL = Design – Build – Test – Learn.

즉,

설계하고 (Design),

유전자 회로 만들고 (Build),

실험하고 (Test),

그 결과로 다음 걸 더 잘 설계하게 배우는 과정 (Learn).

근데 이걸 우리가 맨날 손으로 하잖음?

근데 바이오파운드리는 “그걸 기계로 빠르게, 정확하게, 대량으로 돌리자”는 마인드임.

## 말하자면 생명과학계의 ‘공장’ 같은 것

Foundry란 말 자체가 반도체 업계에서 쓰던 용어임. 설계는 외부에서 받고 생산만 맡는 곳.

여기서 영감 받아서 나온 개념임.

Biofoundry = 생물학적 부품(유전자, 회로, 균주 등)을 설계해서 넘기면, 기계가 알아서 만들어주는 공장.

예를 들어, 어떤 대사경로를 최적화하려고 한다고 해봄.

전통적 방법이면:

→ 클로닝 설계하고 → PCR 하고 → 벡터에 넣고 → transformation 하고 → 발현 테스트하고...

이걸 50번쯤 반복함.

근데 바이오파운드리는:

→ 설계 파일 넘기면 → 로봇이 조립하고 → 자동으로 발현 테스트하고 → 데이터 뽑고 → AI가 해석하고 → 다시 설계해줌.

사람은? 커피 마시면서 결과 지켜보면 됨. (꿈 같…)

## 뭐가 좋은데?

피펫팅 실수 없음. 로봇 손 떨지 않음.

하루에 10개 실험 돌릴 거, 100개 돌릴 수 있음.

결과도 깔끔하게 데이터베이스에 저장됨. 엑셀 따로 안 열어도 됨.

재현성? 비교 불가. 실험자 기분 따라 달라지는 그런 일 없음.ㅋ

실패도 자산으로 남음. 머신러닝이 학습함. 다음 설계를 더 똑똑하게 뽑아냄.

그냥 실험실 전체를 자동화된 시스템으로 한 층 업그레이드 하는 셈임.

## 실제 구성은 ?

바이오파운드리는 DBTL 각 단계마다 핵심 장비랑 소프트웨어가 붙어 있음.

### Design

각종 툴로 유전자 회로 설계함

요즘은 AI가 “이 조합 좋을 듯요~” 라고 추천해줌

### Build

liquid handler가 DNA 섞음

PCR, 클로닝, transformation도 자동으로

휴먼 에러 거의 없음

### Test

고속 측정 장비로 대량 발현 확인

plate reader, FACS, LC-MS 등 장비랑 다 붙어 있음

### Learn

실험 결과를 데이터베이스에 저장

ML 알고리즘이 분석해서 “다음은 이 조건 해봐”라고 제안함

자동 설계 루프 돌입

## 지금 누가 쓰고 있음?

Ginkgo Bioworks: 거의 살아있는 바이오파운드리 기업임. 공장형 미생물 제작소 수준.

Edinburgh Genome Foundry: 유럽판 대표주자. 유전자 부품 제작 및 표준화 선도 중.

Australian Genome Foundry: 호주 정부가 투자해서 만든 거대 설비.

MIT-Broad Foundry: 그냥 이름에서부터 스케일 보임.

## 한국은? 현실은 좀 다름

솔직히 말하면, 아직 일반 연구자 개인이 쓸 수 있는 수준은 아님.

장비 하나하나가 비싸고, 그걸 통합해서 돌릴 수 있는 환경이 없음.

하지만,

KAIST, POSTECH, 서울대, 한국생명공학연구원 등에서 일부 자동화 시도 중임

과기부는 2024~2029년 동안 1,263억 원 투자해서 국가 바이오파운드리 구축 계획 발표함

“공공 바이오파운드리 플랫폼”을 만들어서 중소 연구자들도 활용할 수 있게 할 거라고 함

진짜 그런 날이 오면…

진짜 내 실험 디자인만 넘기고 실험 결과 자동으로 받아보는 세상...

조금만 더 기다리면 가능할지도 모름.

## 그래서 결론은..

바이오파운드리는 생명과학 실험 자동화의 끝판왕 같은 존재임

반복 실험, 사람 손 피펫팅, 재현성 걱정 → 다 기계가 해결함

아직은 꿈 같지만, 한국도 조금씩 따라잡는 중임

언젠가 우리 실험실에도 도입되길 바라면서… 오늘도 피펫을..듦..

## 참고논문&출처

Hillson, N. J., et al. (2019). Building a global alliance of biofoundries. Nature Communications, 10, 2040.

Chao, R., et al. (2017). Engineering biological systems using automated biofoundries. Metabolic Engineering, 42, 98–108.

Kitney, R., et al. (2019). Enabling the Advanced Bioeconomy through a Global Biofoundry Network. ACS Synthetic Biology, 8(7), 1564–1567.

https://www.hkn24.com/news/articleView.html?idxno=344159&utm_source=chatgpt.com

[https://m.dongascience.com/news.php?idx=71428&utm_source=chatgpt.com](https://www.hkn24.com/news/articleView.html?idxno=344159&utm_source=chatgpt.com)

[https://www.sedaily.com/NewsView/2GRH9UIC76?utm_source=chatgpt.com](https://www.hkn24.com/news/articleView.html?idxno=344159&utm_source=chatgpt.com)

[https://zdnet.co.kr/view/?no=20241223211743](https://www.hkn24.com/news/articleView.html?idxno=344159&utm_source=chatgpt.com)

[https://www.igb.illinois.edu/article/nsf-invest-5m-reliable-and-scalable-biofoundries-biomanufacturing-and-global-bioeconomy?utm_source=chatgpt.com](https://www.hkn24.com/news/articleView.html?idxno=344159&utm_source=chatgpt.com)

[https://agilebiofoundry.org/agile-biofoundry-seqwell-partnership-announcement/](https://www.hkn24.com/news/articleView.html?idxno=344159&utm_source=chatgpt.com)

[https://www.nsf.gov/news/nsf-international-partners-invest-82m-six-2024-global?utm_source=chatgpt.com](https://www.hkn24.com/news/articleView.html?idxno=344159&utm_source=chatgpt.com)