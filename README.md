# Double Maze - 双人迷宫竞速游戏

一个使用 Pygame 制作的双人迷宫竞速游戏，具有像素艺术风格。

## 游戏特色

- 🎮 双人对战模式
- 📦 像素风格的箱子障碍物迷宫
- 🎲 每次游戏随机生成新的迷宫
- ⏱️ 3分钟倒计时挑战
- 🏆 到达宝箱即可获胜

## 游戏截图

游戏包含：
- 像素风格草地背景
- 箱子堆叠形成的障碍物墙
- 蓝色和红色玩家角色
- 金色宝箱作为终点

## 操作说明

### 玩家控制
- **蓝色玩家（左上起点）**: WASD 键移动
- **红色玩家（左下起点）**: 方向键移动

### 游戏控制
- **R**: 重新开始（生成新迷宫）
- **ESC**: 退出游戏

## 游戏规则

1. 两名玩家同时从各自起点出发
2. 先到达右侧金色宝箱的玩家获胜
3. 如果时间耗尽（3分钟），距离宝箱更近的玩家获胜
4. 不能穿过箱子障碍物

## 安装和运行

### 环境要求
- Python 3.6+
- Pygame
- PIL/Pillow

### 安装依赖

\`\`\`bash
pip install pygame pillow
\`\`\`

### 运行游戏

# Double Maze

Double Maze is a local two-player maze racing game built with Pygame. Each round
generates a new maze and both players race to the golden chest on the right.

This repository contains a small pixel-art themed game with the following highlights:

- Two-player local multiplayer (Blue player: WASD, Red player: Arrow keys)
- Random maze generation (perfect maze using recursive backtracker)
- 3-minute match timer; closer player wins on tie by distance
- Pixel-art visuals and tile-based obstacle rendering

Recent changes (in this branch)
- New start screen with custom background image and retro PressStart2P font
- Colored text and drop-shadows on the start screen and in-game HUD
- Optional looping menu music (place audio file at assets/menu_music.*)

Requirements
- Python 3.6+
- pygame
- pillow (PIL)

Install dependencies
```
pip install pygame pillow
```

Run the game
```
python3 maze_game.py
```

Files of interest
- `maze_game.py` - main game script (entry point)
- `assets/` - images, fonts and optional music
    - `assets/PressStart2P-Regular.ttf` - retro font used by the UI
    - `assets/instruction- background.JPG` - custom start-screen background

Notes
- If you want the menu music, add a file named `menu_music.mp3` / `.ogg` / `.wav` in
    the `assets/` folder.
- To push changes to your GitHub repo, make sure your remote is configured and you
    have push access (we pushed this branch to your remote during the session).

License & credits
- The project is small; include attribution for any third-party assets you add.

Enjoy playing!
