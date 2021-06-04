# [2021.6.4]중간시험(2차) - Git

# About
- 개발에 필수인 Git의 개념과 동작 원리에 대해 확인해 봅니다.
- 간단한 실습을 통해 기초적인 Git 사용법과 명령어를 정리할 수 있습니다.
- 내가 이전에 썼던 블로그를 보면서 진행 하셔도 됩니다.
- 기억이 나지 않는 부분이 있으면 구글 검색을 하셔도 좋습니다.
- 테스트 시간은 `총 1시간`입니다.


# Test
## Task 1: Git Repository 생성 & Git 폴더 초기화
1. 자신의 github에 `wecode`라는 repository를 만든다
2. 내 컴퓨터에서 Desktop > `test` 폴더 밑에 `wecode`라는 폴더를 만든다.
3. wecode폴더에서 `git init`으로 초기화 한다.

## Task 2: Git 폴더에 파일 생성 & ㅈ내용 작성 및 Repository에 push
1. wecode 폴더 하위에 1부터 50의 자연수 중 짝수를 구하는 함수가 있는 파일을 생성한다.
2. github repository에서 볼 수 있도록 올린다.
- `git remote add origin https://github.com/jemizem/wecode.git`
- `git add .`
- `git commit -m "Add: 최초커밋"`
- `git push origin master`


## Task3: 새로운 branch 생성 및 & PR 메시지 작성
1. `feature/README` 브랜치를 생성하고, 해당 브랜치에서 README.md를 만든다.
- `git branch feature/README`
- `git checkout feature/README`
- `touch README`
- `git add .`
- `git commit -m "Add: README.md 추가"`
- `git push origin feature/README`
- * `git status`로 현재 상태 확인!


## Teask4: 완료한 과제를 `구글 클래스룸`에 제출

