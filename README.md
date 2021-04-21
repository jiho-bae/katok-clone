# 😊 [카카오톡 클론] 첫 웹사이트 만들기

**HTML**과 **CSS**만을 이용하여 첫 웹사이트를 만들었습니다.

### 구현한 기능

- [x] 로그인 화면
- [x] 메신저 메인 화면
- [x] 메신저 채팅창 목록 화면
- [x] 개인채팅창 화면
- [x] 찾기 화면
- [x] 더보기 화면
- [x] 환경설정 화면

### 특징

- 각 화면마다 하나의 html 파일을 가짐
- HTML & CSS 파일을 분리
  - CSS도 특징에 따라 크게 components, screens, globals로 분리
- CSS의 animation, transition, keyframes를 이용해 인터랙티브를 보완
- fontAwesome에서 이미 만들어진 아이콘 사용
- 특정 크기 `width:645px`를 넘는 브라우저에서는 사이트를 볼 수 없음

### 한계 및 느낀점

##### 한계

- JS 없이는 인터랙티브에 한계가 있다.
  - 채팅, 로그인 기능 등 구현 불가능
  - 말 그대로 볼 수만 있는 사이트
- HTML & CSS 모두 유사한 문장 혹은 구조의 지나친 반복

##### 느낀점

- 사용 범위에 따라 파일을 구분해서 관리하고, 그 파일들을 메인 파일에서 모두 불러와 관리할 수 있는 방법이 매우 편리함을 깨닳음
- JS의 인터랙티브를 이용한 실사용 가능한 어플리케이션! >> **공부**
- 코드의 비효율적인 반복을 개선하는 방법의 필요성

### 체험해보기

[Click Here!](https://jiho-bae.github.io/kokoa-clone/)

### 상세 사진

|                                                                                          로그인                                                                                           |                                                                                        메신저 메인                                                                                        |
| :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
| <img width="250" height="450" alt="스크린샷 2021-04-21 오후 4 49 46" src="https://user-images.githubusercontent.com/67041709/115517853-8eea3180-a2c2-11eb-8411-513b0d6ed5f6.png"> | <img width="250" height="450" alt="스크린샷 2021-04-21 오후 4 49 55" src="https://user-images.githubusercontent.com/67041709/115517947-a75a4c00-a2c2-11eb-83b6-b2fecd61a238.png"> |
|                                                                                  **메신저 채팅창 목록**                                                                                   |                                                                                         **찾기**                                                                                          |
| <img width="250" height="450" alt="스크린샷 2021-04-21 오후 4 50 03" src="https://user-images.githubusercontent.com/67041709/115517966-aaedd300-a2c2-11eb-8806-43d710abf5bf.png"> | <img width="250" height="450" alt="스크린샷 2021-04-21 오후 4 50 10" src="https://user-images.githubusercontent.com/67041709/115517978-ad502d00-a2c2-11eb-9f96-0c1dedfd0e5a.png"> |
|                                                                                        **더보기**                                                                                         |                                                                                       **환경설정**                                                                                        |
| <img width="250" height="450" alt="스크린샷 2021-04-21 오후 4 50 16" src="https://user-images.githubusercontent.com/67041709/115517987-afb28700-a2c2-11eb-82f0-d6bf80bdae3b.png"> | <img width="250" height="450" alt="스크린샷 2021-04-21 오후 4 50 23" src="https://user-images.githubusercontent.com/67041709/115517997-b214e100-a2c2-11eb-9b27-8c732beecf30.png"> |
|                                                                                      **개인 채팅창**                                                                                      |                                                                                    **화면 너비 초과**                                                                                     |
| <img width="250" height="450" alt="스크린샷 2021-04-21 오후 4 50 36" src="https://user-images.githubusercontent.com/67041709/115518007-b3dea480-a2c2-11eb-8f86-d5e306167271.png"> | <img width="250" height="450" alt="스크린샷 2021-04-21 오후 4 56 35" src="https://user-images.githubusercontent.com/67041709/115518012-b50fd180-a2c2-11eb-8bf5-c94bec0fcd09.png"> |
