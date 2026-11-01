# NEON APEX · 霓虹竞速

原创轻量 3D 街机赛车网页游戏，基于 Three.js，使用程序生成车辆、赛道和场景。

**[点击开始游戏](https://chenminkai-dot.github.io/neon-apex-racing/)**

## 玩法

- 霓虹环线、落日海岸、赤岩峡谷三条赛道。
- 街头竞速：与 7 辆 AI 赛车进行一圈比赛。
- 计时挑战：单人冲线，挑战最佳用时。
- 自由驾驶：赛道无限循环。
- 氮气冲刺、漂移补充氮气、碰撞减速、双视角、迷你地图与合成引擎音效。
- 手机触摸按钮；最佳成绩按赛道、模式与难度保存在当前浏览器。

## 操作

| 按键 | 功能 |
| --- | --- |
| W / ↑ | 加速 |
| S / ↓ | 刹车 |
| A、D / ←、→ | 转向 |
| Shift | 氮气 |
| 空格 + 转向 | 漂移 |
| C | 切换视角 |
| Esc / P | 暂停 / 继续 |

## 本地运行与更新

用支持 WebGL 的现代浏览器打开 `index.html` 即可离线游玩，所有运行资源均包含在仓库内。
也可在本目录运行 `python -m http.server 8000`，打开 `http://localhost:8000`。

GitHub Pages 从 `main` 分支根目录发布，推送更新后会自动重新部署。`.nojekyll` 用于直接发布静态文件，无需安装依赖或编译。

## 设计参考与第三方许可

玩法方向参考 [Asphalt Legends](https://asphaltlegends.com/?redirection=tle_hub) 的氮气冲刺和 [Horizon Chase Turbo](https://store.playstation.com/en-us/concept/231717/) 的经典街机赛车风格。没有使用上述游戏的代码、车型、美术或音频资源。

第三方库 Three.js 0.128.0 使用 MIT 许可，完整许可见 [assets/LICENSE-three.txt](assets/LICENSE-three.txt)。
