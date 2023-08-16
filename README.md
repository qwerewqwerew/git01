<details open markdown='block'>
  <summary>
    <h2>📌git 작업순서</h2>
  </summary>

  1. git 로컬 작업 순서

     1. 폴더별 최초한번 깃 초기화

         `git init`

     1. 스테이지에 올림

        `git add .`

     2. pc별 최초한번 사용자 등록

        `git config --global user.email "깃허브에 등록한 이메일"`

        `git config --global user.name "깃허브에 등록한 이름"`

     3. 폴더별 최초한번 브렌치 명 변경

        `git branch -M main`

---
2. git 원격 작업 순서

   1. 폴더별 최초 한번
        1. create repository 버튼 클릭후 정보를 입력하여 저장소 생성

     1. 생성된 repository 주소 복사
        1. ex) https://github.com/qwerewqwerew/git01

     2.  vscode로 이동하여 로컬과 원격 repository 연결 (폴더별 최초한번)

          `git remote add origin 원격저장소주소`

          <span style='color:red;font-size:14px;'> 이때 원격저장소 주소는 ii 단계에서 복사한 주소를 붙여넣는다 아래의 예시를 참고하자 <span>

          `git remote add origin https://github.com/qwerewqwerew/git01`



---
1. git 로컬작업
    1. 🚩 편집파일 스테이지로 올림

        `git add .`
    2. 🚩 버전생성

        `git commit -m "커밋메시지"`

    3. 🚩원격저장소에 코드 올림

        `git push origin main`

</details>

---

## 📌수업파일
|날짜|주제/제목|내용|링크|
|---|블루마켓|웹디자인기능사|[text](https://github.com/qwerewqwerew/git01/bluemarket)|
|---|---|---|---|
|---|---|---|---|