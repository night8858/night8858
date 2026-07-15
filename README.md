<div align="center">

# Hi, I'm WaterKing 👋

### 机器人系统开发者 · Robotics Systems Developer

专注机器人视觉、嵌入式控制、机械臂与软硬件系统集成。

Building practical robot systems from perception and inference to motion control and deployment.

[![GitHub](https://img.shields.io/badge/GitHub-night8858-181717?style=flat-square&logo=github)](https://github.com/night8858)
[![Email](https://img.shields.io/badge/Email-1007618434%40qq.com-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:1007618434@qq.com)

</div>

## 关于我

- 🤖 曾在 **ROBOCON**竞赛中担任主要负责人，负责机器人方案设计、核心开发和系统集成。
- 👁️ 聚焦机器人感知与视觉推理，实践多相机采集、目标检测、OCR 和边缘端部署。
- ⚙️ 持续投入 STM32、FreeRTOS、机械臂通信与末端执行器控制。
- 🚀 目前主要完善基于 ROS2 的机器狗视觉与机械臂系统，以及吸盘夹爪控制方案。

## 技术栈

![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![STM32](https://img.shields.io/badge/STM32-03234B?style=flat-square&logo=stmicroelectronics&logoColor=white)
![FreeRTOS](https://img.shields.io/badge/FreeRTOS-2F8D46?style=flat-square)
![ROS 2](https://img.shields.io/badge/ROS_2-Jazzy-22314E?style=flat-square&logo=ros&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![OpenVINO](https://img.shields.io/badge/OpenVINO-00A4EF?style=flat-square&logo=intel&logoColor=white)
![TensorRT](https://img.shields.io/badge/TensorRT-76B900?style=flat-square&logo=nvidia&logoColor=white)
![CMake](https://img.shields.io/badge/CMake-064F8C?style=flat-square&logo=cmake&logoColor=white)

- **核心语言：** C、C++，使用 Python 完成辅助工具与自动化任务。
- **嵌入式开发：** STM32、HAL、FreeRTOS、CMake、OpenOCD。
- **机器人与视觉：** ROS2 Jazzy、colcon、OpenCV、YOLO、OpenVINO、PP-OCR、TensorRT。
- **硬件与传感器：** Jetson NX、Intel RealSense、海康工业相机。

## 代表项目

### 1. [toe26_dogvision · ROS2](https://github.com/night8858/toe26_dogvision/tree/ROS2)

基于 **ROS2 Jazzy + colcon** 的机器狗视觉、机械臂控制与算术题识别工作空间，也是目前主要维护的项目。

- 通过共享相机节点为 YOLO 与 PP-OCR 提供统一图像数据，避免重复占用物理相机。
- 使用 OpenVINO 部署 YOLO 目标检测和 PP-OCR 算术表达式识别。
- 集成机械臂串口通信、高层任务编排、断线重连和 ROS2 话题接口。
- 使用统一 Launch 配置组合启动视觉、机械臂和任务节点。

`ROS2` `C++` `OpenVINO` `YOLO` `PP-OCR` `Hikvision MVS`

### 2. [STM32 吸盘夹爪控制](https://github.com/night8858/Cboard_Suction_Gripper_test)

相关仓库：[Cboard_Suction_Gripper_test](https://github.com/night8858/Cboard_Suction_Gripper_test) · [F405_Suction_Gripper](https://github.com/night8858/F405_Suction_Gripper)

面向吸盘夹爪和末端执行器的嵌入式控制工程，基于 **STM32F407、HAL 与 FreeRTOS**，使用 CMake、Ninja、OpenOCD 和 DAPLink 构建调试。目前重点完善安全运动空间、位置限制与上位机集成。

`STM32F407` `FreeRTOS` `CMake` `OpenOCD` `Motion Control`

### 3. [自主排球机器人](https://github.com/night8858/volleyball_3wheel)

相关仓库：[volleyball_3wheel](https://github.com/night8858/volleyball_3wheel) · [RC_Volleyball_vision](https://github.com/night8858/RC_Volleyball_vision)

面向发球、接发球和协作任务的三全向轮机器人系统。下位机采用 **STM32F407** 完成运动控制，上位机使用 **Jetson NX + TensorRT + YOLO** 进行排球识别与视觉推理。

`Omni Wheel` `STM32` `Jetson NX` `TensorRT` `YOLO` `RealSense`

### 4. [Unitree A1 控制](https://github.com/night8858/unitreeA1)

基于 STM32 开发板的 Unitree A1 控制项目，围绕四足机器人控制接口与嵌入式开发展开。

`STM32` `C` `Quadruped Robot`

## 开源与协作

我关注并欢迎以下方向的技术交流与项目协作：

- 机器人感知、多相机系统与视觉推理部署
- ROS2 节点设计、系统集成与任务编排
- STM32、FreeRTOS、执行机构与运动控制
- 机械臂通信、末端执行器与整机联调

如果你对这些方向感兴趣，欢迎通过 [GitHub](https://github.com/night8858) 或 [邮件](mailto:1007618434@qq.com) 联系我。

<!-- ## GitHub 活动

<div align="center">

[![WaterKing's GitHub stats](https://github-readme-stats.vercel.app/api?username=night8858&show_icons=true&hide_border=true&include_all_commits=true&rank_icon=github)](https://github.com/night8858) -->

</div>
