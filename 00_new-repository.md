# 初期設定
## 新規リポジトリ作成
```
echo "# git-command-line-reference" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/k-ish/git-command-line-reference.git
git push -u origin master
```
## 既存リポジトリをプッシュ
```
git remote add origin https://github.com/k-ish/git-command-line-reference.git
git push -u origin master
```