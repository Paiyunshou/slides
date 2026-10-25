# Slides · 项目幻灯片归档

财税与工具两条线的 HTML 幻灯片合集，首页 `index.html` 按「工作」「工具技能」两类归档。

- 在线浏览：https://paiyunshou.github.io/slides/
- 本地目录：`D:\github\slides`

## 新增一个 deck

1. 把 HTML 文件放进本目录（例如 `my-deck.html`）
2. 打开 `index.html`，在「工作」或「工具技能」卡片的 `.list` 里复制一个 `<a class="item">` 块，
   改标题（`.t`）、链接（`href`）、说明（`.m`），并把卡片右上角的 `N DECK` 数字加 1
3. 提交并推送：`git add . && git commit -m "add deck" && git push`

## 设计规范

首页遵循 `DESIGN.md` 的 Monad 风格：羊皮纸底色 #f6f3f1、衬线标题（weight 400）、等宽正文、
1px Ash 描边、40px 卡片圆角、药丸按钮，主色仅有湖蓝 #2b59d1 与 Periwinkle #cfdaf5。
