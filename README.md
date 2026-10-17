<div align="center">

# Ton · Automation & Robotics

**自动化学习与机器人实践记录**

控制逻辑可视化 · VLA 工程复现 · 可运行的小作品

[电机互锁实验](https://ton242678-glitch.github.io/motor-interlock-lab/) · [纸飞机试玩](https://ton242678-glitch.github.io/paper-flight-battle/) · [全部仓库](https://github.com/ton242678-glitch?tab=repositories)

</div>

## 我在学习什么

把自动化和机器人学习中遇到的问题，做成能运行、能解释、能验证的小项目。

- **控制逻辑**：状态机、互锁、异常恢复和可视化实验。
- **机器人与 VLA 工程**：评估流程、模型服务通信、实验记录与复现工具。
- **交互开发**：浏览器小游戏、桌面应用与动画交互。

## 重点项目

### 01 · 电机互锁可视化实验

用浏览器演示电机正反转互锁、方向冲突、急停恢复和操作记录。控制模型可以脱离界面单独运行，配有状态机说明和测试。

**JavaScript · 状态机 · 控制逻辑**
[在线体验](https://ton242678-glitch.github.io/motor-interlock-lab/) · [代码与说明](https://github.com/ton242678-glitch/motor-interlock-lab) · [验证记录](https://github.com/ton242678-glitch/motor-interlock-lab/actions)

### 02 · StarVLA 部署通信扩展

基于 StarVLA 改进元数据与推理响应等待、代理设置和请求容错，提供无需模型权重的本地 WebSocket 演示。

**Python · WebSocket · 工程测试**
[代码与运行步骤](https://github.com/ton242678-glitch/starvla-deploy-kit) · [改进说明](https://github.com/ton242678-glitch/starvla-deploy-kit/blob/starVLA_dev/docs/deployment_extensions_zh.md) · [自动测试](https://github.com/ton242678-glitch/starvla-deploy-kit/actions)

### 03 · Spatial-Forcing 评估扩展

修复动作窗口的时间顺序，增加参数检查和 JSON/CSV 实验记录，让评估行为与结果更容易核对。

**Python · 评估流程 · 可复现记录**
[代码与运行步骤](https://github.com/ton242678-glitch/spatial-forcing-eval) · [实现与统计口径](https://github.com/ton242678-glitch/spatial-forcing-eval/blob/master/docs/evaluation_extensions_zh.md) · [自动测试](https://github.com/ton242678-glitch/spatial-forcing-eval/actions)

## 兴趣作品

| 项目 | 学习内容 | 入口 |
| --- | --- | --- |
| Windows 桌宠 | Electron、TypeScript、托盘与窗口、拖拽和互动动画 | [代码与运行说明](https://github.com/ton242678-glitch/nailong) |
| 纸飞机大战 | JavaScript / Canvas、游戏循环、碰撞检测与浏览器音效 | [在线试玩](https://ton242678-glitch.github.io/paper-flight-battle/) · [代码](https://github.com/ton242678-glitch/paper-flight-battle) |

## 怎样记录学习过程

写清问题、实现入口和运行步骤，用测试、演示和简短复盘记录进展。开源衍生项目保留上游来源，明确新增改动与验证范围。

VLA 项目当前主要验证工程、评估和通信流程；人工策略演示不代表真实模型效果。原论文、模型和原始成果归上游作者。
