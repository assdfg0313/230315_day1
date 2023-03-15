Git Hub에 내 파일 등록하는 법

1. git init

2. git add .
  U -> A

3. git commit -m "first commit"
  A 글자 사라짐

4. git branch -M main 
  branch(?) 관리, 근본은 master -> main

5. git remote add origin https://github.com/assdfg0313/230315_day1.git
  github 연결 (본인 주소)
  안되는 경우 : config 에러 => 메일과 이름 필요
   이미지: https://cdn.discordapp.com/attachments/1082543246984614010/1085466335313670164/image.png

6. git push -u origin main
   github에 저장

** .gitignore 파일에 들어가는 것

git hub에 업로드되지 말아야 할 파일

ex1. 대용량 dependency 패키지들
ex2. 실행파일들
ex3. 보안 민감 파일 (private key, 패스워드, 보안키 등)