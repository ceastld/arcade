# 游廊 · Arcade

大厅只负责收录和打开游戏。每个小游戏在自己的仓库里单独 build、单独发布。

## 加一个新游戏

1. 把游戏单独发布到任意静态地址（例如另一个 GitHub Pages）。
2. 在本仓库的 `games.json` 里追加一条：

```json
{
  "id": "my-game",
  "title": "游戏名",
  "subtitle": "英文或短名",
  "blurb": "一句话",
  "url": "https://ceastld.github.io/my-game/",
  "hue": 200,
  "tag": "标签"
}
```

3. 只推送这个大厅仓库。不用重新 build 其它游戏。

大厅地址发布后是 `https://ceastld.github.io/arcade/`。
