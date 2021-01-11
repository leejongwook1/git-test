# git test
git test

git init
git status
git add
git commit -m [커밋 명]
git remote add [원격저장소이름] [원격저장소주소]
git push [원격저장소이름] [브런치]
git pull [원격저장소이름] [브런치]
git clone [원격저장소주소]
git diff                                         *수정된 텍스트 비교*
git checkout [파일]                              *Modified 상태를 Unmodified 상태로 되돌림*
git reset [파일]                                 *Staged 상태를 Modified 상태로 되돌림* 
                                                 *commit을 한후 되돌릴때 --soft : Staged로 --mixed : Modified로 --hard : Unmodified로
git reset HEAD~1                                 *commit 1개 전으로 되돌림*
git revert HEAD                                  *현재 commit 위에 이전 commit을 덮어씌움*

git branch [브런치명]                             *브런치 생성*
git checkout [브런치명]                           *HEAD를 브런치로 옮김*

git merge [브런치명]                              *합칠 브런치명으로 작성*
