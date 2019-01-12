---
layout: post
title:  gitpage 이미지 업로드 경로
date:   2019-01-12 10:29:01 -0600
categories: jekyll
---

### github 디렉토리 구조

사용자명.github.io
  └ _posts : 게시글<br>
  └ assets : 이미지 파일이 있는 경로<br>
<br>
<br>
<br>
### 절대경로
<br>
#### https://kimhaegyeong.github.io/assets/thumbs-up.png - 성공
![테스트 이미지]({{ "https://kimhaegyeong.github.io/assets/thumbs-up.png"}})
<br>
#### https://kimhaegyeong.github.io/assets/2019-01-05-workbench-user-and-privileges.jpg - 실패
![테스트 이미지]({{ "https://kimhaegyeong.github.io/assets/2019-01-05-workbench-user-and-privileges.jpg"}})
<br>
<br>
<br>
### 상대경로
<br>
#### /assets/thumbs-up.png - 성공
![테스트 이미지]({{ "/assets/thumbs-up.png"}})
<br>
#### ../assets/thumbs-up.png - 실패
![테스트 이미지]({{ "../assets/thumbs-up.png"}})
<br>
<br>
<br>
<br>
<br>
**image copyright**
designed by turkkub from Flaticon