
# 坦克大战小游戏（HTML5 Canvas）

一个使用原生 **HTML + CSS + JavaScript** 开发的网页版《坦克大战》小游戏，无需任何第三方依赖，打开浏览器即可运行。

## 在线说明

- 项目类型：前端小游戏 / Canvas 实时渲染
- 开发方式：纯原生技术栈（无框架）
- 运行环境：现代浏览器（Chrome / Edge / Firefox）

## 功能特性

- 玩家坦克控制
- 方向键 `↑ ↓ ← →` 控制移动
- `Space` 发射子弹（含射击冷却）
- 敌方 AI 行为
- 自动巡航移动、随机转向
- 随机发射子弹
- 命中与重生机制
- 玩家子弹命中敌人后：得分 +1、敌人延时重生
- 敌方子弹命中玩家后：触发爆炸并 `Game Over`
- 爆炸粒子效果
- 坦克被命中时生成短时爆炸动画
- 障碍物系统
- 地图内固定障碍，坦克不能穿越
- 子弹碰到障碍物即销毁
- HUD 与交互
- 顶部实时显示得分
- 游戏结束弹层 + “重新开始”按钮

## 项目亮点

- 使用 `requestAnimationFrame` 驱动主循环，保证动画流畅性
- 通过状态集中管理（玩家、敌人、子弹、爆炸粒子、得分）保持逻辑清晰
- 基于 AABB（Axis-Aligned Bounding Box）实现高效碰撞检测
- 在单个 HTML 文件中完成结构、样式、逻辑，便于展示与部署

## 技术栈

- HTML5 Canvas
- CSS3
- Vanilla JavaScript (ES6)

## 目录结构

```text
.
└─ tank_game.html   # 完整游戏代码（可直接运行）
```

## 快速开始

1. 克隆或下载项目到本地
2. 直接用浏览器打开 `tank_game.html`
3. 开始游戏

## 操作说明

- `↑ ↓ ← →`：移动坦克
- `Space`：发射子弹
- 玩家被击中后点击“重新开始”可重开

## 可扩展方向

- 多敌人系统与难度递增
- 玩家生命值 / 关卡机制
- 音效与背景音乐
- 道具系统（护盾、连发、加速）
- 本地最高分记录（`localStorage`）

## 项目截图

<img width="1860" height="974" alt="image" src="https://github.com/user-attachments/assets/8bdd093a-7b8e-4aee-b400-4f97ff50aed7" />


```md
![游戏截图](./assets/screenshot.png)
```

## License

MIT
