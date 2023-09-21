# GaryWorld

연습용 레포

## git init

-   git 생성

## git add

-   사용법 : `git add <추가할 경로>`

## git commit -m

-   사용법 : `git commit -m '<메시지>'`
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

1.  `git remote add origin <git주소>` : 원격 레포와 연결

2.  `git branch -M main` : branch를 `main`으로 변경

3.  `git pull origin main` : git pull

### -v

-   사용법 : `git remote -v`
-   git 오리진 확인

## .gitignore

-   파일 업로드
-   예시파일 작성함.

## git restore

사용법

-   `git restore`
-   `git restore --staged <파일명>`

-   변경사항 되돌리기

## git branch

-   branch를 확인

### -M <branch 이름>

-   사용법 : `git branch -M <branch 이름>`

-   메인 branch를 해당 브런치로 변경

### <branch 이름>

-   사용법 : `git branch <branch 이름>`
-   branch 생성

### switch <branch 이름>

-   사용법 : `git switch <branch 이름>`
-   사용하는 branch를 해당 branch로 변경

### 원격 저장소에 브런치 만들기

사용법

-   `git push --set-upstream origin <branch 이름>`
-   `git push -u <branch 이름>`

### -D

-   사용법 : `git branch -D <branch 이름>`
-   해당 브런치 삭제

### 삭제한 branch 복구

사용법

1. `git reflog` : 복구 시점 확인
2. `git checkout -b <삭제한 브랜치명> <커밋 해시값>`

### 브런치 병합

사용법

1. `git switch <main branch>` : default branch로 이동
2. `git merge <원하는 branch>` : default branch와 원하는 branch 병합됨.

## 참고링크

https://paullabworkspace.notion.site/GitHub-435ec8074bcf4353afb947f601a030df
