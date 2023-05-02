# git-practice

Abstract: This project is to practice git.
[See Demo](https://www.google.com)

## Vim modes

- Normal mode: press `esc` on ANY mode
- Insert mode: press `i` on Normal mode
- Visual mode: press `v` on Normal mode
- Command mode: press `:` on Normal mode

## Installation

```shell
$ git clone {repo address}
$ cd {repo name}
$ vi README.md
```

## How start

```python
def hello(name):
    print(f'hello, {name}')
hello('John Doe')
```

## Features

git 초기설정
>git config --global --list
>이후 다음 값들이 없을 시 설정방법
>git config --global user.email "이메일"
>git config --global core.editor "vim"
>git config --global core.pager "cat"
>git config --global --unset `잘못입력한 값을 정확하게 입력`

*********************************************************

repository 설정(github.com)
>우상단 프로필클릭
> -> Settings
> -> 좌하단 Developer Settings
> -> Personel access tokens
> -> Tokens (classic)
> -> Generate new token (classic)
> -> Note에 이름 작성
> -> Expiration=No expiration(제발이번만쓸것)
> -> 모든것 체크(제발이번만쓸것)
> -> Generate token(이후 새로고침 금지)
> -> terminal에서 `git push origin main`
> -> 닉네임, 패스워드 입력 (안할수도 있음)
> -> 푸쉬됨(깃허브 업로드 완료)

*********************************************************

git으로 파일 생성부터 업로드까지
>touch main.py -> main.py 생성
>vi main.py -> vim으로 main.py 작성
>python main.py -> main.py 실행
>git status -> git 상태확인
>git add main.py -> main.py 파일 추가
>git commit -> 커밋 작성
>git push origin main -> origin main에 업로드

*********************************************************

CLI 명령어(git bash, terminal, ...)
>ls: 파일 목록 표시(list segment)
>ls -a: 숨김파일 포함 모두 표시
>ls -l: 파일 한줄씩 표시(상세)
>cd `파일명`: change directory '파일명'
>mkdir `파일명`: make '파일명' directory
>touch `파일명`: '파일명' 파일 생성
>rm `파일명`: remove '파일명' (주의)
>cat `파일명`: '파일' 병합(concatenate)후 출력
>man `명령어`: '명령어' 알아보기 (manual) // 빠져나가기 q
>python `파이썬파일명`: '파이썬파일' 실행

*********************************************************

vim 입력모드
>Normal mode: esc
>Insert mode: i
>Visual mode: v
>Command mode: : (shift + ;)
>저장&빠져나오기: :wq + enter (wq = write & quit)

wtf????????????????/
