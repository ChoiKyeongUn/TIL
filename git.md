# Git

1. 저장소(repository) 만들기 - git이 관리하는 폴더(directory)

   하위 폴더에서 절대 하지 않아야 함! ( 특별한 경우 제외 )

   이미 init한 repo에서 또 init하지 않는다!

   ```shell
   $ git init
   ```

2.  파일을 스테이징하기

   ```she
   $ gid add 파일명
   ```

3.  파일을 커밋하기

   ```shell
   $ git commit -m '커밋 메시지 내용(변경사항을 요약해서 적음)'
   ```

- 상태 확인하기

  ```shell
  $ git status
  ```

- 내가 누군지 정보 입력하기

  ```shell
  $ git config (--global) user.name 유저이름
  ```

  ```shell
  $ git config (--global) user.email 유저이메일
  ```

- 