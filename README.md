# cli
git init
git add .
git commit -m "init commit"
git remote add origin $link-dari-github
git push -u origin main

git add . && git commit -m "merubah bagian ..."
git push -u origin main

git checkout -b $nama-branch-baru
git add . && git commit -m "mengubah ... "
git push -u origin $nama-branch-baru
