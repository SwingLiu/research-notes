# 研究资料更新 - 2026-04-03 08:59

## 强化学习 + 机器人
## Answer

In 2025, advancements in reinforcement learning for robot manipulation were highlighted by the launch of open-source tools by the Allen Institute for AI, enabling robots to perform manipulation tasks trained solely in virtual environments with zero-shot transfer to real hardware. Additionally, QCraft's $100 million funding round emphasized the company's focus on Level 4 autonomy and general physical AI, with a significant push towards reinforcement learning and world model development. Researchers at Tokyo University of Science also introduced HEAPGrasp, a method that significantly improved robots' success rate in grasping objects with diverse optical properties using only an RGB camera.

---

## Sources

- **Ai2 launches open-source tools for robots trained solely in virtual environments - MLQ.ai** (relevance: 52%)
  https://mlq.ai/news/ai2-launches-open-source-tools-for-robots-trained-solely-in-virtual-environments/
  * Allen Institute for AI launched MolmoBot and MolmoSpaces, enabling robots to perform manipulation tasks trained solely in simulation with zero-shot transfer to real hardware. The Allen Institute for AI has released MolmoBot and MolmoSpaces, open-source tools that allow robots to learn manipulation...

- **QCraft raises $100 million to push toward Level 4 autonomy and physical AI at scale - Robotics & Automation News** (relevance: 25%)
  https://roboticsandautomationnews.com/2026/03/23/qcraft-raises-100-million-to-push-toward-level-4-autonomy-and-physical-ai-at-scale/100026/
  **QCraft, a developer of autonomous driving AI, has announced the completion of a $100 million new Series D funding round.**. Dr Yu stated that QCraft is putting its strategic focus toward the SAE’s Level 4 autonomous driving and general physical AI, while accelerating its international expansion an...

- **HEAPGrasp: A faster, smarter way for robots to handle tricky objects using only RGB camera - eurekalert.org** (relevance: 16%)
  https://www.eurekalert.org/news-releases/1121584
  Researchers develop a new approach that improves robots’ grasping success rate for transparent and shiny objects, beyond reducing handling time. For robots to handle objects autonomously, they must first accurately measure the three-dimensional (3D) shape of the scene using cameras and then plan how...


## 量化交易
## Answer

Quantitative trading algorithmic strategies are expected to evolve significantly by 2025, driven by advancements in AI and blockchain technology. The global foreign exchange turnover surged to $9.51 trillion per day, highlighting the necessity for automated trading systems to handle high-speed environments and maximize market opportunities. Investment firms like AQR have seen substantial returns using AI-infused strategies, doubling their fortunes in a year, indicating a growing reliance on AI for quantitative trading. Hedge funds and quant shops are increasingly adopting AI-driven models to outperform the market, suggesting a transformative shift in algorithmic trading by 2025.

---

## Sources

- **Rule-Based Forex Algorithms and Decentralized Trading Logic - Blockchain Council** (relevance: 39%)
  https://www.blockchain-council.org/info/rule-based-forex-logic/
  # Rule-Based Forex Algorithms and Decentralized Trading Logic. With trading around the world raking in a whopping $9.5 trillion every day, having super-fast execution speeds is a must for anyone who's serious about the markets. The **rule-based forex trading system** at Pivozon targets the daily tim...

- **AI integration and job security take centre stage in finance recruitment: Hays - Asian Business Review** (relevance: 27%)
  https://asianbusinessreview.com/news/ai-integration-and-job-security-take-centre-stage-in-finance-recruitment-hays
  Artificial intelligence (AI) integration is shaping Singapore’s banking and finance hiring landscape in 2026, as employers seek candidates who can embed AI into workflows to enhance efficiency in research and trading, according to a Hays report. Hedge funds are hiring for research and algorithm deve...

- **How 3 Billionaire Investors Used AI To Double Their Fortunes In A Year - Forbes** (relevance: 12%)
  https://www.forbes.com/sites/johnhyatt/2026/03/16/how-3-billionaire-investors-used-ai-to-double-their-fortunes-in-a-year/
  After years of subpar returns, investment firm AQR is on a hot streak thanks to a new AI infused investing strategy and strong tax-friendly returns, beloved by financial advisors. Last year AQR’s core multi-strategy Apex fund, which has $6.7 billion in assets, returned 19.4%, while its Delphi long-s...


## 机器人
## Answer

In 2025, the robotics industry is heavily investing in deep learning to advance physical AI and cognitive robotics. Neura Robotics and Qualcomm Technologies are collaborating to integrate Qualcomm's AI compute, connectivity, and robotics platforms with Neura's deep robotics system expertise, aiming to accelerate scalable, real-world robotic intelligence. The Pittsburgh Robotics Network predicts the next wave of physical AI will include affordable humanoids and scaled autonomous transportation, driven by advancements in robotics and AI. Additionally, deep learning techniques are being applied to medical fields, such as developing foundation models for cardiac MRI through self-supervised methods.

---

## Sources

- **Neura Robotics and Qualcomm enter strategic collaboration to advance physical AI and cognitive robotics - Robotics & Automation News** (relevance: 30%)
  https://roboticsandautomationnews.com/2026/03/15/neura-robotics-and-qualcomm-enter-strategic-collaboration-to-advance-physical-ai-and-cognitive-robotics/99677/
  The collaboration brings together Qualcomm Technologies’ leadership in AI compute, connectivity, and robotics platforms with Neura’s deep robotics system expertise and embodied AI software, with the shared goal of accelerating scalable, real-world robotic intelligence. Qualcomm Technologies’ robotic...

- **From affordable humanoids to robotaxis: Pittsburgh Robotics Network predicts the next wave of physical AI - Robotics & Automation News** (relevance: 22%)
  https://roboticsandautomationnews.com/2026/03/09/from-affordable-humanoids-to-robotaxis-pittsburgh-robotics-network-predicts-the-next-wave-of-physical-ai/99389/
  # From affordable humanoids to robotaxis: Pittsburgh Robotics Network predicts the next wave of physical AI. In this outlook for 2026, Jenn Apicella, executive director of the Pittsburgh Robotics Network, examines the trends shaping the next phase of robotics – from affordable humanoid robots to sca...

- **Building foundation models for cardiac MRI - Nature** (relevance: 21%)
  https://www.nature.com/articles/s41551-026-01638-2
  *Nature Biomedical Engineering* (2026)Cite this article. A video-based deep-learning system was trained to understand the spectrum of human cardiovascular disease by the self-supervised method of contrastive learning, using pairs of cardiac MRI scans and their corresponding text reports that are gen...


---
# 基础研究资料
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
