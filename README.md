# GaryWorld

연습용 레포

## git init

-   git 생성

## git add

-   사용법 : git add <추가할 경로>

## git commit -m

-   사용법 : git commit -m '<메시지>'
    ' ' 따옴표 안 써도 메시지 작성 가능.
-   따옴표 안에 작성시 줄 바꿈 처리(Enter)를 하고 추가로 작성하면 이는 메시지의 세부내용으로 추가됨.

## git status

-   내 git의 현재 상태 확인
-   `Unmodified` : 최근의 커밋과 비교했을 때 바뀐 내용이 없는 상태
-   `Modified` : 최근 커밋과 비교했을 때 바뀐 내용이 있는 상태
-   `Staged` : 파일이 수정되고 나서 스테이지 공간에 올라와 있는 상태이며, `git add` 후의 상태

## git diff

-   이전 기록(commit)을 기준으로 변경사항을 확인.
-   Q를 누르면 종료 가능

## git log

-   commit 히스토리 조회

### -graph

-   그래프로 확인

## git remote

-   git 원격

### -add

사용법

<!-- 원격 레포와 연결 -->

-   git remote add origin <git주소>

<!-- 브런치를 `main`으로 변경 -->

-   git branch -M main

<!-- git pull -->

-   git pull origin main

### -v

-   사용법 : git remote -v
-   git 오리진 확인

## .gitignore

-   파일 업로드
-   예시파일 작성함.
