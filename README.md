# EnJourneyZ 旅行攻略库

这是一个用于维护个人旅行攻略网页的静态站点。每一趟旅行都放在独立目录中，根目录 `index.html` 作为旅行集合首页，方便本地打开，也方便通过 GitHub Pages 在线分享。

## 目录结构

- `index.html`：旅行攻略集合首页。
- `indonesia/index.html`：国庆印尼旅行攻略。
- `tianjin/index.html`：元旦天津旅行攻略。

## 本地预览

直接双击根目录的 `index.html`，或者打开某个目的地目录下的 `index.html`。

## 在线分享

仓库推送到 GitHub 后，在仓库 `Settings` → `Pages` 中选择：

- Source：`Deploy from a branch`
- Branch：`main`
- Folder：`/root`

发布后可通过 GitHub Pages 地址访问。

## 新增旅行

新增一趟旅行时，建议按下面的方式维护：

1. 在根目录下创建目的地目录，例如 `japan/`、`chengdu/`。
2. 把该目的地的攻略网页保存为 `index.html`。
3. 在根目录 `index.html` 中新增一张入口卡片。
