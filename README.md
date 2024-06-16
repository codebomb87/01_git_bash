# 01_git_bash
for practice git bash

```
1. git init
2. git remote add origin <github remote repo 주소>
3. git pull origin main
4. git status(add 할 것들 확인)
5. git add *
6. git commit -m 'commit 메세지'
7. git push origin main
```

##01_01_check config
```
# 디폴트 Branch 확인
git config --get init.defaultBranch

# git 설정 보기
cat ~/.gitconfig

# git 초기 설정
git config --global user.name 'codebomb87'
git config --global user.email 'ys0915@korea.ac.kr'

# remote origin 경로 재설정
git remote set-url origin git@github.com:codebomb87/01_git_bash.git
```
