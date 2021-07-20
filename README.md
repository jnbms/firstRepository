`레포지토리`에 익숙해지는 연습을 하고 있습니다 :)

1. `레포지토리`를 생성합니다.
2. 또는 git clone `https:// github.com / {깃허브 아이디} / {레포지토리 이름}.git` 로 디렉토리 파일을 가져옵니다.
3. clone이 아닌 경우, 프로젝트 폴더에서 `git init`으로 초기화 합니다.
4. git add . 로 새로 생성된 모든 파일을 등록합니다.
5. git commit -m "fist commit" 으로 "first commit" 이란 태그(주석)으로 추가한 파일들의 커밋을 설정합니다.
6. git remote add origin `https:// github.com / {깃허브 아이디} / {레포지토리 이름}.git` 로 주소 등록합니다.
7. git push origin main 으로 깃 허브의 main 디렉토리로 변경된 내용을 업로드 합니다.
8. 원격 저장소와 로컬 저장소가 일치하지 않는 오류가 발생할 경우 : git pull --rebase oririn main (origin : 원격 저장소 이름, main : 안의 디렉토리 이름)
