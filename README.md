# YueHaifeng

**UAV Control · Simulation · Flight Visualization**  
Zhejiang University

关注无人机控制、仿真与可视化。这里整理我的公开项目、代码练习与开源探索。

UAV control, simulation, and visualization projects, with code experiments and open-source explorations.

## 项目 · Featured project

### [EV50 VTOL 视景演示](https://github.com/HaifengYue/dji-ev50-showcase)

基于 **Blender · TypeScript · Three.js** 的无人机视景演示，将三维模型、任务展示和飞行记录回放放在同一套界面中。

- **模型观察**：三维飞机模型与固定视角预览
- **任务展示**：预设飞行任务与 MAVLink 风格遥测可视化
- **日志回放**：本地 PX4 ULog 的只读转换与回放

<a href="https://github.com/HaifengYue/dji-ev50-showcase">
  <img src="https://raw.githubusercontent.com/HaifengYue/dji-ev50-showcase/main/previews/aircraft/perspective.png" alt="EV50 VTOL 三维模型的透视预览" width="600" />
</a>

<sub>视景演示与日志可视化，不是飞控、物理仿真器或工程 CAD。</sub>

[项目代码](https://github.com/HaifengYue/dji-ev50-showcase) · [使用说明](https://github.com/HaifengYue/dji-ev50-showcase/blob/main/docs/USER_GUIDE.md) · [接口文档](https://github.com/HaifengYue/dji-ev50-showcase/blob/main/docs/API.md)

## 开源探索 · Open-source explorations

以下仓库基于上游项目 fork，保留各项目的原始归属与许可证。

| 仓库 | 方向 | 上游 |
| --- | --- | --- |
| [Isaac Drone Racer](https://github.com/HaifengYue/isaac_drone_racer_2) | 基于 Isaac Sim / Isaac Lab 的强化学习无人机竞速 | [原始项目](https://github.com/kousheekc/isaac_drone_racer) · [fork 来源](https://github.com/Amin-Yazdanshenas/isaac_drone_racer_2) |
| [XTDrone](https://github.com/HaifengYue/XTDrone) | PX4、ROS 2 与 Gazebo 无人机仿真 | [robin-shaun/XTDrone](https://github.com/robin-shaun/XTDrone) |
| [PX4-Autopilot](https://github.com/HaifengYue/PX4-Autopilot) | 开源飞控代码 | [PX4/PX4-Autopilot](https://github.com/PX4/PX4-Autopilot) |

## 代码练习 · Code experiments

[Learning-code](https://github.com/HaifengYue/Learning-code)：无人机控制相关的学习代码，包含 [Python 控制器](https://github.com/HaifengYue/Learning-code/tree/master/Python_MC_Controller) 与 [Simulink / C / Python](https://github.com/HaifengYue/Learning-code/tree/master/Simulink_C_Python) 相关实验。
