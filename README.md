# Late-for-class-game
What’s the fastest way to get to class? Can you dodge crowds and outmaneuver scooters whizzing all over the place? Give this game a try!
# 上课别迟到 Late for Class

**[English](#english) | [中文](#中文)**

▶️ **Play now / 在线试玩:** https://YOUR-USERNAME.github.io/Late-for-class-game/

---

## English

### About

The bell is about to ring. You're at the dorm and your class is across campus. Get to the classroom door before the countdown hits zero.

The shortest path between two points is a straight line. Campus never lets you take it: there are stairs, construction, crowds, people walking three abreast, and scooter riders who don't brake. Pick your route, grab a ride, and run.

The game is top-down and runs in the browser. It's a single HTML file with no install and no dependencies.

### Controls

| Action | Keyboard | Touch |
|---|---|---|
| Move | `WASD` / Arrow keys | Press and drag anywhere |
| Say "Excuse me" | `Space` / `E` | **借过** button |
| Show the straight line to class | `H` | button |
| Mute | `M` | button |
| Pause | `P` / `Esc` | button |
| Retry after a round | `Enter` | button |

### The map

| Surface | Effect |
|---|---|
| **Path** | Normal speed |
| **Bike lane** | Fast surface, but scooter killers ride here |
| **Stairs** | Slow on foot. Ride onto them and you **crash** and lose your ride |
| **Ramp** | Rideable. Skateboards get a speed bonus here |
| **Plaza** | Raised area, reachable only by stairs or ramps |
| **Grass** | **Off limits.** Keep off the grass |
| **Construction** | 1–2 random segments are closed each round, so the best route changes every time |

Press `H` to show a dashed line from you to the classroom door. Your job is to find the walkable route that stays closest to it.

### Hazards

- **Scooter killers**: they speed down the bike lanes. A flashing red dashed line warns you about a second before one arrives. If you get hit, you fall down, lose your ride and get knocked aside.
- **👻 Ghost killers**: they give no warning and stay invisible until they enter the purple circle around you. Listen for the eerie sound and dodge.
- **Trios**: three people walking side by side take up the whole path. Walk into them and you get shoved back; ride into them and you lose your ride. Press `Space` to say "Excuse me" and they squeeze into single file.
- **🔔 Class-break crowds**: when the bell rings, crowds pour out of the doors that flash yellow. You move at half speed inside a crowd. The classroom door can release a crowd too.

### Items

| Item | Effect |
|---|---|
| 🛴 Abandoned scooter | Fastest ride. Lost if you hit stairs or get hit |
| 🛹 Skateboard | Fast, with extra speed on ramps |
| ☕ Coffee | +30% speed for 6 seconds |
| ⏰ Alarm clock | +4 seconds |

### Difficulty

| Level | Time limit | What changes |
|---|---|---|
| Easy | 40 s | Fewer killers, 1 closed segment, crowds every 14 s |
| Normal | 30 s | Killers aim at you, crowds every 9 s |
| Hard | 24 s | Frequent killers and ghosts, crowds every 7 s |

You earn 1–3 stars depending on how much time is left. Your best time for each difficulty is saved in your browser.

### Tips

- The straight route across the plaza is the shortest, but its stairs make you slow down or get off your ride.
- With a scooter, the long way around on the bike lanes is often faster, if you can survive the killers.
- Don't ride a scooter or skateboard onto stairs.
- Watch for doors flashing yellow before you commit to a path.

### Run locally

Download `index.html` and open it in any modern browser. That's it.

### Tech

Plain HTML, CSS and JavaScript on a `<canvas>`. It uses no frameworks and no game engine, and loads nothing except web fonts.

---

## 中文

### 游戏简介

上课铃马上就要响了。你还在宿舍，教室却在校园另一头。在倒计时结束前冲到教学楼门口！

两点之间直线最短，但校园从来不让你走直线：路上有台阶、施工封路、课间人潮、三人并排霸占步道的同学，还有从不刹车的 scooter 杀手。选好路线，捡辆车，冲！

这是一款俯视角浏览器小游戏。只有一个 HTML 文件，打开就能玩，不用安装。

### 操作方式

| 动作 | 键盘 | 手机 |
|---|---|---|
| 移动 | `WASD` / 方向键 | 按住屏幕任意位置拖动 |
| 喊"借过" | `空格` / `E` | 点 **借过** 按钮 |
| 显示到教室的直线 | `H` | 按钮 |
| 静音 | `M` | 按钮 |
| 暂停 | `P` / `Esc` | 按钮 |
| 结束后再来一次 | `Enter` | 按钮 |

### 地图元素

| 地面 | 效果 |
|---|---|
| **步道 Path** | 正常速度 |
| **车道 Bike lane** | 路面快，但有 scooter 杀手出没 |
| **台阶 Stairs** | 步行变慢；骑着车冲上去会**摔倒**并丢掉车 |
| **坡道 Ramp** | 可以骑车通过，滑板在坡道上还会加速 |
| **中央广场 Plaza** | 高台，只能从台阶或坡道上下 |
| **草坪 Grass** | **禁止进入**，请勿践踏草坪 |
| **施工 Construction** | 每局随机封掉 1–2 段路，所以每局的最优路线都不一样 |

按 `H` 会显示一条从你到教室门口的虚线。你要找的是：能走通、又最接近这条直线的路。

### 危险

- **Scooter 杀手**：在车道上高速冲过。出现前约 1 秒会有闪烁的红色虚线预警。被撞会倒地、丢车、被撞到一边。
- **👻 幽灵杀手**：没有任何预警，进入你身边的紫色虚线圈才会现形。听到怪声就赶紧闪开。
- **三人并排族**：三个人肩并肩占满整条步道。硬闯会被挤开，骑车撞上还会丢车。按 `空格` 喊"借过"，他们会排成一列给你让路。
- **🔔 课间人潮**：下课铃响后，闪黄光的楼门口会涌出一大群人。挤在人群里速度减半。终点教学楼门口也可能涌出人来。

### 道具

| 道具 | 效果 |
|---|---|
| 🛴 没人要的 scooter | 速度最快；冲上台阶或被撞就会丢掉 |
| 🛹 滑板 Skateboard | 速度快，在坡道上额外加速 |
| ☕ 咖啡 Coffee | 6 秒内速度 +30% |
| ⏰ 闹钟 Alarm clock | 时间 +4 秒 |

### 难度

| 难度 | 时间 | 特点 |
|---|---|---|
| 简单 Easy | 40 秒 | 杀手较少，只封 1 段路，每 14 秒一波人潮 |
| 普通 Normal | 30 秒 | 杀手会瞄准你，每 9 秒一波人潮 |
| 困难 Hard | 24 秒 | 杀手和幽灵频繁出现，每 7 秒一波人潮 |

按剩余时间获得 1–3 颗星，每个难度的最快纪录会保存在你的浏览器里。

### 小技巧

- 直穿广场的路线最短，但台阶会让你变慢，骑车的话还得下车。
- 有 scooter 的话，沿车道绕远路往往更快，前提是你躲得过杀手。
- 千万别骑着 scooter 或滑板冲上台阶。
- 选路之前先看一眼有没有门口在闪黄光。

### 本地运行

下载 `index.html`，用任意现代浏览器打开即可。

### 技术说明

用原生 HTML、CSS 和 JavaScript 在 `<canvas>` 上绘制。没有用任何框架或游戏引擎，除了网页字体之外不加载任何外部资源。
