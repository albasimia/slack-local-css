# slack-local-css
XSSが怖いのでlocalからcssを読み込んでSlackをダークテーマにする。

black.cssは[こちら](https://cdn.rawgit.com/laCour/slack-night-mode/master/css/raw/black.css)からフォーク。
custom.css内はご自由にいじってください。

```
cd /Applications/Slack.app/Contents/Resources/app.asar.unpacked/src/static
git init
git add remote git@github.com:albasimia/slack-local-css.git
git checkout -- .
git pull origin master
```
