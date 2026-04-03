# 强化学习常用算法总结

## 1. DQN (Deep Q-Network)
- **原理**: 将Q学习与深度神经网络结合，学习状态-动作价值函数
- **核心**: 经验回放 + 目标网络 提高稳定性
- **应用**: Atari游戏、机器人控制

## 2. PPO (Proximal Policy Optimization)
- **原理**: 近端策略优化，通过限制策略更新幅度稳定训练
- **类型**: On-policy（在线策略）
- **应用**: Robot manipulation, 游戏AI

## 3. SAC (Soft Actor-Critic)
- **原理**: 基于最大熵的Actor-Critic算法，同时最大化回报和熵
- **类型**: Off-policy（离线策略）
- **应用**: 连续动作空间任务（机器人运动）

## 4. DDPG (Deep Deterministic Policy Gradient)
- **原理**: 确定性策略梯度，适合连续动作
- **类型**: Off-policy
- **应用**: 连续控制任务

---

# 运动控制核心知识

## 1. 控制系统基础
- PID控制：比例-积分-微分控制
- 状态空间控制
- 轨迹规划

## 2. 机器人运动控制
- 位置/速度/加速度控制
- 运动学逆解
- 动力学建模

## 3. 关键数学工具
- 线性代数（矩阵运算、变换）
- 李雅普诺夫稳定性理论
- 卡尔曼滤波

---

# 视觉感知核心知识

## 1. 相机模型
- 针孔相机模型
- 内参/外参矩阵
- 畸变校正

## 2. 几何变换
- 旋转矩阵、四元数
- 欧拉角
- 坐标系转换

## 3. 深度学习视觉
- CNN图像分类/检测
- Transformer (ViT)
- NeRF神经辐射场

---

# 视差算法 (Disparity)

## 经典方法
- **SAD**: Sum of Absolute Differences
- **SSD**: Sum of Squared Differences
- **NCC**: Normalized Cross-Correlation
- **SGBM**: Semi-Global Block Matching

## 深度学习方法
- MC-CNN
- DispNet
- RAFT-Stereo

## 公式
- 深度 Z = b × f / d
  - b: 基线距离, f: 焦距, d: 视差

---

# 3D Gaussian Splatting (3DGS)

## 核心原理
1. **场景表示**: 用数百万个3D高斯分布表示场景
2. **渲染**: 将3D高斯投影到2D图像（splatting）
3. **优化**: 用梯度下降优化协方差矩阵

## 优点
- 实时渲染（1080p @ 30+ FPS）
- Photorealistic质量
- 可微分化

## 应用
- 3D重建
- VR/AR
- 虚拟现实渲染
- 动态场景重建

## 学习资源
- 论文: "3D Gaussian Splatting for Real-Time Radiance Field Rendering"
- 教程: https://papers-100-lines.medium.com/3d-gaussian-splatting-tutorial
- 工具: NeRF Studio, gsplat

---

# A股信息

## 当前状态
- Tushare Token已配置
- 股票列表接口可用 ✅
- 指数接口权限不足 ❌

## 可用数据
- 股票基本信息（代码、名称、行业、上市日期）
- 财务报表数据
- 基金净值

## 待解决
- 需要开通指数行情权限（index_daily）
