# 깃
### 깃의 워크플로우 
- Working Directory
    - untracked
    - tracked 
        - unmodified
        - modified : 수정이 된 내역만을 Staging Area로 보낼 수 있음 
- Staging Area
- .git directory

---
# 깃 브랜치 전략
## Gitflow
### 브랜치의 종류
1. Feature
2. Develop : Master의 실행가능한 버전을 만들기 위한 과정은 develop 브랜치에서 수행해나간다
3. Release : 제품을 출시하기 위한 브랜치. 
4. Hotfix
5. Master : 가장 최신 버의전은 언제나 실행가능한 버전이어야 한다.

---
# 자주 사용하는 명령어
```shell
$ git status # 현재 브랜치의 상태를 보여주는 명령어 
$ git add [file]
$ git commit [file]
```