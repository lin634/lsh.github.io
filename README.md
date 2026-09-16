# lsh.github.io — 个人主页

个人网站，包含 首页 / 关于我 / 专业技能 / 项目作品 / 联系方式 等页面。

## 🎮 一箭又一箭（在线小游戏）

点击式箭头解谜小游戏，由 Python + Pygame 编写，通过 Pygbag 编译为浏览器可运行的网页版：

- 在线地址：`game/index.html`（站点导航栏「小游戏」）
- 玩法：点击箭头让其飞出棋盘；同方向到边界之间无其他箭头则可飞出，有阻挡则失误 -1；清空全部箭头过关
- 内容：8 个固定关卡（4~25 支箭）+ 随机模式（箭头随机分布、构造保证可通关）
- 网页版源码：`arrow_src/main.py`（重建命令：`python -m pygbag --build arrow_src`，产物复制到 `game/`）
- 内置开源中文字体 Noto Sans SC（SIL Open Font License 1.1）
