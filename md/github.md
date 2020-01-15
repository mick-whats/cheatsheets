# githubチートシート

## tips

### 最速でプロジェクトをgithubにpushする方法

```sh
mkdir hoge
cd hoge
vi README.md
#　適当にREADME作る
git add --all
git commit -m "initial commit"
hub create
git push -u origin master
hub see
```

[hubでGithubをちょっと便利に。 \- Qiita](https://qiita.com/ken0nek/items/ce50c6e5b59867c19f79)