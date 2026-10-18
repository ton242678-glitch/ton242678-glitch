<div align="center">

# 你好，我是 Ton

**自动化专业在读 · 控制逻辑与机器人学习 · 可运行的项目实践**

把学习中的问题做成小作品，用演示、测试和文档记录实现过程。

[电机互锁在线实验](https://ton242678-glitch.github.io/motor-interlock-lab/) · [纸飞机在线试玩](https://ton242678-glitch.github.io/paper-flight-battle/) · [浏览全部仓库](https://github.com/ton242678-glitch?tab=repositories)

</div>

## 关于我

我是一名自动化专业学生，这里记录课程之外的编程练习、开源项目改进和交互作品。

- **控制与自动化**：练习状态机、正反转互锁、急停恢复和控制过程可视化。
- **机器人与 AI 工程**：学习视觉语言动作模型（VLA）的代码结构，围绕评估记录、模型服务通信和异常处理做小范围改进。
- **真机与仿真**：参与 OpenViTac 相关实践，参与方向为机器人真机实践与仿真实践。
- **交互与应用开发**：用浏览器和桌面应用，把程序做成可以操作、查看结果的作品。

近期希望继续学习时间序列分析、负荷预测和能源数据可视化，把已有的控制与交互开发经验用于数据应用。

## 项目导航

| 项目 | 可以看到什么 | 直接入口 |
| --- | --- | --- |
| **电机互锁实验** | 控制状态机、互锁与急停、操作记录 | [在线体验](https://ton242678-glitch.github.io/motor-interlock-lab/) · [仓库](https://github.com/ton242678-glitch/motor-interlock-lab) |
| **StarVLA 通信扩展** | WebSocket 超时、异常请求处理、本地通信演示 | [改进说明](https://github.com/ton242678-glitch/starvla-deploy-kit/blob/starVLA_dev/docs/deployment_extensions_zh.md) · [仓库](https://github.com/ton242678-glitch/starvla-deploy-kit) |
| **Spatial-Forcing 评估扩展** | 动作窗口修复、参数检查、实验结果导出 | [改进说明](https://github.com/ton242678-glitch/spatial-forcing-eval/blob/master/docs/evaluation_extensions_zh.md) · [仓库](https://github.com/ton242678-glitch/spatial-forcing-eval) |
| **OpenViTac 实践资料** | 真机与仿真实践方向、视触觉任务理解与论文导读 | [项目资料](https://github.com/ton242678-glitch/openvitac-practice) · [源码 Fork](https://github.com/ton242678-glitch/openvitac) |
| **Windows 桌宠** | Electron / TypeScript、托盘与窗口交互、动画 | [运行说明与素材预览](https://github.com/ton242678-glitch/nailong) |
| **纸飞机大战** | Canvas 动画、游戏循环、碰撞检测与浏览器音效 | [在线试玩](https://ton242678-glitch.github.io/paper-flight-battle/) · [仓库](https://github.com/ton242678-glitch/paper-flight-battle) |

## 重点项目与实践

### 电机互锁可视化实验

**想解决的问题**：让正反转互锁、方向冲突和急停恢复的控制过程更容易观察和理解。

**实现内容**：浏览器交互界面、可独立运行的控制状态机、操作记录，以及配套说明与自动测试。

**使用技术**：JavaScript · HTML / CSS · 状态机 · Node.js 测试

[打开在线实验](https://ton242678-glitch.github.io/motor-interlock-lab/) · [查看实现](https://github.com/ton242678-glitch/motor-interlock-lab) · [测试与构建记录](https://github.com/ton242678-glitch/motor-interlock-lab/actions)

### StarVLA 部署通信扩展

基于 [StarVLA](https://github.com/starVLA/starVLA) 的开源衍生实践，重点学习模型服务的通信与异常处理。

**本仓库新增**：连接与响应等待超时、代理设置隔离、异常请求处理，以及无需 GPU 或模型权重的本地 WebSocket 通信演示。

**验证方式**：本地回环通信、异常场景测试和 Windows / Ubuntu 自动检查。演示中的人工策略用于验证通信流程。

**使用技术**：Python · WebSocket · MessagePack · GitHub Actions

[运行与改进说明](https://github.com/ton242678-glitch/starvla-deploy-kit/blob/starVLA_dev/docs/deployment_extensions_zh.md) · [查看代码](https://github.com/ton242678-glitch/starvla-deploy-kit) · [自动测试记录](https://github.com/ton242678-glitch/starvla-deploy-kit/actions)

### Spatial-Forcing 评估扩展

基于 [Spatial-Forcing](https://github.com/yifanwu-victor/Spatial-Forcing) 的开源衍生实践，重点学习评估流程、动作执行顺序和结果记录。

**本仓库新增**：动作窗口时间顺序修复、配置检查、JSON 进度记录，以及 CSV 汇总工具。

**验证方式**：围绕动作选择、参数边界、结果状态和统计口径进行 CPU 单元测试，并保留跨平台自动检查记录。

**使用技术**：Python · JSON / CSV · 评估工具 · GitHub Actions

[实现与统计口径](https://github.com/ton242678-glitch/spatial-forcing-eval/blob/master/docs/evaluation_extensions_zh.md) · [查看代码](https://github.com/ton242678-glitch/spatial-forcing-eval) · [自动测试记录](https://github.com/ton242678-glitch/spatial-forcing-eval/actions)

### OpenViTac · 视触觉机器人实践

**参与方向**：机器人真机实践与仿真实践。

OpenViTac 围绕视觉与触觉结合的机器人操作，研究对应仿真与真机任务中的策略评估。项目资料仓库整理了论文导读、四类能力与任务对应关系，以及官方入口。

**相关方向**：机器人操作 · 视触觉 · 仿真与真机

[我的项目资料](https://github.com/ton242678-glitch/openvitac-practice) · [源码 Fork](https://github.com/ton242678-glitch/openvitac) · [项目官网](https://fvl-repo.github.io/OpenViTac/) · [原论文](https://arxiv.org/abs/2610.10384v1)

## 正在积累的技能

| 方向 | 项目中用到的内容 |
| --- | --- |
| 编程与数据 | Python、JavaScript、TypeScript、JSON / CSV |
| 控制与交互 | 状态机、互锁逻辑、Canvas、Electron |
| 工程实践 | Git、WebSocket、自动测试、GitHub Actions、运行文档 |

## 学习与开发记录

我希望每个项目都能说明：问题是什么、改了哪一部分、怎样运行，以及现有证据支持什么结论。

- 开源衍生项目保留上游作者、许可和来源，具体新增内容写在各仓库说明中。
- 学习与开发中使用 AI 辅助，通过代码检查、测试和运行记录核对产出。
- VLA 项目当前展示的是通信与评估工具的工程实践；真实模型性能和机器人实验结果需另行验证。
