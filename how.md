- Create repo on github and init with README.md
- Create folders and files
- go mod init github.com/samidbb/go_math
- publish:
-- git init
-- git remote add origin https://github.com/samidbb/go_math.git
-- check remote: git remote -v
-- git add -A
-- git commit -m "first commit"
-- git push -u -f origin master





Pushing a minor update:
git commit -m "new function"
git tag -a v1.1.0 -m "new function"
git push --tags