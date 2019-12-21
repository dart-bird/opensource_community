# 오픈소스 커뮤니티
**작성시작일자:** 2019년 12월 11일

### ◎ 계기
현재 수준에서 코드작성, 오류 발견 등 난이도는 어려워서 접하기 쉬운 번역을 하기로 했다.  
취미가 게임이기에 게임 관련 주제로 서치를 해봤다.

### ◎ 살펴보기
서치를 하던 도중, 오픈소스 게임 커뮤니티 사이트, [FreeGameDev Forums](https://forum.freegamedev.net) 를 발견함.
* [Art & Assets](https://forum.freegamedev.net/viewforum.php?f=6) - **게임 디자인 게시판**
* [Design & Ideas](https://forum.freegamedev.net/viewforum.php?f=5) - **게임 아이디어 게시판**
* [Legal & Business](https://forum.freegamedev.net/viewforum.php?f=7) - **라이센스 게시판**
* [Programming](https://forum.freegamedev.net/viewforum.php?f=3) - **게임 프로그래밍 게시판**
* [Infrastructure & Leadership](https://forum.freegamedev.net/viewforum.php?f=4) - **소통 게시판**

이 사이트에는 이렇게 다양한 폼이 구성되어 있었고 하나, 둘 살펴보았다.

### ◎ 첫 발을 들이다
[FreeGameDev Forums](https://forum.freegamedev.net) 에서 살펴보던 도중, [Art & Assets](https://forum.freegamedev.net/viewforum.php?f=6)에서 많은 글들 중에 [The “Translators wanted!” thread](https://forum.freegamedev.net/viewtopic.php?f=6&t=11388) 라는 제목과 함께 올라온 글을 보았고 번역을 하고 싶은 나에게 딱 좋은 글이였다.  
그래서 이 사이트에 가입을 하려고 회원가입을 하였는데 빨간 공지와 함께 가입인사글을 남겨야 한다고 되어있어서 "Hi i'm krumaska, from Korea" 와 함께 작성하여 업로드 했다.  
![Introduce_yourself_img](https://user-images.githubusercontent.com/51515055/70618204-97a21080-1c55-11ea-86b6-aeb5c7dafb4e.PNG)  

### ◎ 한국인?
그 다음 날 확인을 해봤는데, 한국인이라는 말에 금시초문인 반응이였다.  
아무래도 이 커뮤니티 사이트가 잘 알려지지 않은데다가 한국인은 처음이라 그랬던거 같다.  
질문은 이랬다. **"무엇이 너를 이 사이트에 오게 만들었는가?"**  
그래서 현재 1학년 수업인 오픈소스 수업을 듣고 있고, 첫 기여를 하고 싶다고 답글을 남겼다.
  
  ![reply_img](https://user-images.githubusercontent.com/51515055/70618384-05e6d300-1c56-11ea-8572-4c837d10d987.png)  
  
운명이라고 답글을 남겼는데, 아주 좋은 소식이라는 말과 함께 엄청난 환영을 해줬다.  
그리고 **"관심 있어하는 어떤 오픈소스게임을 기여하고 싶습니까?"** 라는 말에 아직, 프로그래밍 실력이 부족하고 이에 해석을 하고 싶은데 좋은 프로젝트를 추천해달라고 부탁을 했더니  
![reply_img2](https://user-images.githubusercontent.com/51515055/70770612-6c343880-1db1-11ea-98a6-763697a6c281.png)  
라는 답변을 받았고 위에서 찾았던 글을 소개해 주었다.  이에 답변에 고맙다는 표시를 했다.  
대부분 여기서 처음 시작하는거 같다.

### ◎ 탐방후 시작  
[The “Translators wanted!” thread](https://forum.freegamedev.net/viewtopic.php?f=6&t=11388) 이글에서 번역할 게임을 찾던 도중에 opensurge라는 이름의 소닉게임처럼 만든 오픈소스 게임을 알게되었다.  
![opensurge_translation_wanted](https://user-images.githubusercontent.com/51515055/71114368-f4339b80-2212-11ea-8500-38ad25176102.png)  
위 사진과 같이 번역을 모집하고 있었고 들어가보니 한국어로 번역된 파일이 없었다.  
그리고 가이드 [opensurge 번역가이드](http://opensnc.sourceforge.net/wiki/index.php/Translation_Guide) 가 있어서 읽어 보았는데, english.lng 파일을 기준으로 번역해서 pull request 요청을 하라고 적혀져 있었다.
그래서 같은 목적으로 기여하는 친구와 함께 반반 나눠서 lng 파일을 번역하기로 했다.  

### ◎ 시작부터...
시작부터 앞서서 lng파일을 보니  
`LANG_AUTHOR                 "Alexandre Martins"       // translation author`  
위 문구와 함께 번역자 이름을 적는공간이 있었는데, 이것을 친구와 같이할 경우에는 어떻게 표기를 해야하는지 가이드라인에는 없어서 이메일을 통해 질문을 해보았다.  
![image](https://user-images.githubusercontent.com/51515055/71307389-199df080-2431-11ea-94bf-eb6272f47d5c.png)
위 사진은 질문을 하고 답장을 얻은 사진인데, 일단 굉장히 친절하게 답변을 해주었고 번역에 대한 환영을 해주었다.  그래서 답장으로 고맙다고 말하고 최선을 다 해보겠다고 말했다.  

### ◎ 해석 반영 문제
해석이 게임에 반영이 안되서 파일을 뒤져본 결과, 한글은 따로 고딕 ttf 파일을 사용해야 반영이 된다는 것을 알았고, 이에 대해 Gothic.ttf 를 추가해달라고 하였다.  
![image](https://user-images.githubusercontent.com/51515055/71307120-ed807080-242c-11ea-93a4-a22f0600c519.png)  


이후에 그래픽 사이즈에 맞게 바꾸려고 폰트적용을 시켜 보았지만, 다른 언어도 같이 작아져서 fnt 파일 형식을 내가 생각한 방식으로 작성하면 어떻겠냐고 물어보면서 [OpenSurge](https://github.com/alemart/opensurge) 레포에 [이슈](https://github.com/alemart/opensurge/issues/15)를 남겼다.

마지막으로 내가 제안한대로 적용을 시켜주었고, 이에 대해 감사표시를 했다. 

### ◎ 해석완료! 그리고 Pull Request
친구와 함께 해석을 완료한 뒤, [PR](https://github.com/alemart/opensurge/pull/16)을 했다.  
해석반영이 불가한 비트맵 부분은 추후에 원하면 반영하라고 주석처리를 통해 남겼다.  

### ◎ 마무리하며 ...
오픈소스 커뮤니티 활동을 하면서 **아 이게 바로 커뮤니티 활동이구나** 라면거 깨달았고 오픈소스 커뮤니티 활동이 이렇게 활발하게 일어난다는 사실을 몸소 느겼다.  
해외 쪽은 메일 답장을 느리게 할 줄 알았지만, 나의 착각이였다.  
이렇게 기여를 하는 활동이 막상 힘들 줄 알았지만 생각보다 재미있었고 **전혀** 힘들지 않았다. (하지만 한번 시작하면 끝낼 때 까지 계속 책임을 져야한다!!) 정말로 누구든 마음만 있으면 할 수 있다!  
그리고 이후에는 기여를 해석이 아닌 다른 종류로 해보고 싶은 마음이 들었다.
