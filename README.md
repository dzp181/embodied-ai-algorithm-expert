# 具身智能算法专家团 (Embodied AI Algorithm Expert Team)

由「主理人 + 感知 + 规划 + 学习」四位算法专家组成的具身智能团队，覆盖感知、运动规划与强化学习，从建模、仿真到 Sim-to-Real 部署的全流程方案，并在功能完成后按规范推送到 GitHub。

## 类型

Team 型（1 主理人 + 3 团员）

## 团队成员

- **沈策行（主理人 / 具身算法总架构师）**：编排与裁决，协调三域协作与最终交付。
- **林观微（三维感知算法工程师）**：点云/图像 3D 检测分割、6D 位姿、SLAM、视觉-语言对齐。
- **葛运筹（运动规划与抓取工程师）**：RRT*/轨迹优化、MPC、视觉伺服、抓取姿态生成。
- **励行远（强化学习与部署工程师）**：PPO/SAC、模仿学习、VLA、Sim-to-Real 与 ROS2 部署。

## 功能

- 端到端抓取任务：规划 + 学习协作，含训练与部署。
- 感知模块开发：检测/分割/位姿/建图设计与代码。
- 算法选型评审：三域并行给出候选与对比，主理人裁决。
- GitHub 交付：功能完成即按约定式提交、分支管理与 PR 描述推送。

## 使用示例

- 帮我设计一个机械臂抓取任务的强化学习训练方案
- 写一个基于点云的 3D 目标检测感知模块
- 把训练好的策略部署到实物机器人，给出 Sim-to-Real 方案

## 头像

`avatars/` 下包含团队头像与四位成员头像（team.png、各成员 .png）。可在「我的专家」中手动替换，要求：PNG/JPG，512×512，≤500KB。

## 安装

将专家包目录放到专家目录下：

```
C:\Users\Administrator\.workbuddy\plugins\marketplaces\my-experts\plugins/embodied-ai-algorithm-expert/
```

然后运行注册命令使其可见：

```bash
python3 scripts/register_expert.py <expert-dir>
```

## 打包分享

```bash
zip -r embodied-ai-algorithm-expert.zip embodied-ai-algorithm-expert/
```
