---
slug: first-blog-post
title: 블로그 2번쨰 공부
authors:
  name: 서 정우
  title: 첫 github page를 만들었습니다.
  url: https://github.com/jjungwooseo
  image_url: https://github.com/jjungwooseo.png
tags: [welcome, homepagw]
---

오늘은 30일 수업을했다. 오늘은 코드명을 치지않아도 yarn build가 돌아가는
github page 를 만들었다. 먼저 .github \ workfolows를 만들고  deploy.yml
파일을 만든다.  그리고 도큐사우루스 사이트에 .github/workflows/deploy.yml
을 복사하여 붙어넣기 한다. 그리고 github token에  ${{ secrets.GH_ACTIONS_TOKEN }} 로 바꾸어준다  그리고 github에서 열쇠를 만든다. 
그러면 명령어를 치지않아도  github page로 npm yarn build가 다 가능하여 편하다.
