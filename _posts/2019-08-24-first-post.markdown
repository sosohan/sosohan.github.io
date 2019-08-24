---
layout: post
title: first-post
date: 2019-08-24 11:51:00
thumbnail: scribble.png

---

첫 포스팅.. 
일단 템플릿에 맞춰 쓰고 있는데 어떻게 나오려나??
첫 커밋이자.. 첫 티켓이자.. 첫 할일은.. 
git 과 jira 연동해서 티켓으로 브랜치 관리하려고 시도 해보았다. 
우선 문제가 몇가지 있었는데.

## 로그인이 안 된다. 
우선 회사에서 사용하는 jira url 과 거기서 쓰는 id & password 사용할 경우 테스트 연결 성공했었다.
근데 연습 삼아 셋팅한 개인 jira software에서는 연결이 안 된다...
구글링해서 연결하는 방법을 찾기는 찾았는데. 왜 안되는지는 아직도 모르겠다. 다른 셋팅이 있는 건가?
내가 사용한 방법은 atlassian 홈페이지에서 api 인증 토큰 발급 받아서 했다. 또 name 에는 name을 안 쓰고 이메일 썼다.
흑.. 왜 그런건지는 jira에 좀 더 익숙해지면서 알아가는 걸로.. 

![jira-api-token](https://sosohan.github.io/assets/img/20190814/jira-api-token.jpg)

![jira-intellij-test](https://sosohan.github.io/assets/img/20190814/jira-intellij-test.jpg)

로그인은 결국 해서 연결은 했지만 티켓이랑 연동해서 브랜치 관리가 안됨 주의..;)

## 폰트 변경
첫 포스트를 릴리즈 해보았는데 너무 안 예쁘다... ㅋㅋㅋ

![first-post](https://sosohan.github.io/assets/img/20190814/first-post.png)

폰트 변경은 대체 어떻게 하는거지..??
html 태그로 존재하는 기울기, 굵게 등등의 간단한 변경만 가능하다. 
폰트 주입해서 쓰려면??.
폰트 관련 스크립트 링크를 default.html인지 post.html 인지에 import해서 사용하는 거 같다. 
근데 잘 안돼서 일단은 패스....


##소감
이렇게 일일이 태그 비슷한 코드 써가면서 작성하는 줄 몰랐다..
블로그 사용할 때는 항상 텍스트 에디터가 있었기 때문에 텍스트를 읽기 좋게 꾸미는 일이
간단한 일이라는 생각에 익숙해져 있었다. 
어렵군..

