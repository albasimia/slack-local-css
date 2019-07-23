# slack-local-css

## 2019/7/23時点で使用不可能であることを確認しました。

XSSが怖いのでlocalからcssを読み込んでSlackをダークテーマにします。

black.cssは[こちら](https://cdn.rawgit.com/laCour/slack-night-mode/master/css/raw/black.css)からフォーク。

custom.css内はご自由にいじってください。

```
cd /Applications/Slack.app/Contents/Resources/app.asar.unpacked/src/static
git init
git remote add origin git@github.com:albasimia/slack-local-css.git
git fetch
git reset --hard origin/master
```
