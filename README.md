+ git 로컬 작업 순서
  + 폴더별 최초한번 깃 초기화
    + git init
  + 스테이지에 올림
    + git add .
  + pc별 최초한번 사용자 등록
    + git config --global user.email "깃허브에 등록한 이메일"
    + git config --global user.name "깃허브에 등록한 이름"
  + 폴더별 최초한번 브렌치 명 변경
    + git branch -M main

+ git 원격 작업 순서
  + 폴더별 최초 한번
    + create repository 버튼 클릭후 정보를 입력하여 저장소 생성
  + 생성된 repository 주소 복사
    + ex) https://github.com/qwerewqwerew/git01

+ git 로컬 작업
 + 🚩 편집파일 스테이지로 올림
   + git add .
 + 🚩 버전생성
   + git commit -m "커밋메시지"
 + 🚩원격저장소에 코드 올림
   + git push origin main