## 📖 详细规则与玩法介绍 (Detailed Game Rules)

五虎棋是在棋盘上进行的双人棋类对战。玩家通过轮流落子，在棋盘上组合出特定的**几何阵型**来获取积分，最终以**积分高者**或达到特定胜利条件者获胜。

### 1. 核心阵型与分值 (Patterns & Scores)
游戏内置自动阵型识别算法，当棋子构成以下几何图形时即可获得相应积分：

* **大五虎 (10分)**：贯穿对角线或核心大方阵的最高级别几何阵型（含通天/长对角）。
* **小五虎 (5分)**：分布在棋盘不同区域的特定五子联动阵型（共支持 9 种不同方位的小五虎判定）。
* **四斜 (4分)**：由 4 颗棋子构成的标准斜线阵型。
* **三斜 (3分)**：由 3 颗棋子构成的基础斜线阵型。
* **小井 (2分)**：由 4 颗棋子构成的紧凑 $2 \times 2$ 井字/方形结构阵型。

### 2. 积分叠加机制 (Additive Scoring)
* 游戏支持**多阵型叠加计分**。如果一次落子同时激活了多个几何阵型（例如一颗子既完成了“小五虎”，又同时凑成了“四斜”与“小井”），系统会自动累加所有符合条件的阵型得分。
* 这种机制极大地提升了游戏的策略深度，玩家需要兼顾防守与创造多重复合阵型。

🚀 快速开始 / 本地运行
由于本项目为纯前端静态页面，无需任何 Node.js 或后端服务器环境：

可以单人对战AI
双人本地或联网对战(两台设备)

## 打开网页直接开玩:
https://maoyincc.github.io/WuHu/



## 📖 Detailed Game Rules & Gameplay

WuHu is a two-player board game played on a grid. Players take turns placing pieces to form specific geometric formations on the board to score points, with the winner determined by the highest score or by achieving specific victory conditions.

### 1. Core Formations & Scores

The game features an automated pattern recognition algorithm that awards points when pieces form the following geometric structures:

* **Grand Tiger (10 pts)**: High-level geometric formations spanning diagonals or core large squares (including straight-line and long diagonal variants).
* **Mini Tiger (5 pts)**: Specific 5-piece linked formations distributed across different regions of the board (supports 9 different directional variations of Mini Tigers).
* **Quad Diagonal (4 pts)**: A standard diagonal formation consisting of 4 pieces.
* **Triple Diagonal (3 pts)**: A basic diagonal formation consisting of 3 pieces.
* **Mini Grid (2 pts)**: A compact $2 \times 2$ square/grid structure consisting of 4 pieces.

### 2. Additive Scoring Mechanism

* The game supports multi-pattern additive scoring. If a single move simultaneously activates multiple geometric formations (e.g., a single piece completes a "Mini Tiger" while also contributing to a "Quad Diagonal" and "Mini Grid"), the system automatically accumulates all qualifying pattern scores.
* This mechanism greatly enhances the strategic depth of the game, requiring players to balance defense while engineering overlapping, multi-layered formations.

---

🚀 Quick Start / Local Execution
Since this project is a purely frontend static page, it requires no Node.js or backend server environment:

* Play solo against AI
* Local two-player or cross-network multiplayer (across two devices)

## Open the webpage and start playing directly:

[https://maoyincc.github.io/WuHu/](https://maoyincc.github.io/WuHu/)
