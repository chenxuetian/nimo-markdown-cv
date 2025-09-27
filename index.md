---
layout: cv
title: 陈学添
email:
  url: mailto:23210980105@m.fudan.edu.cn
  text: 23210980105@m.fudan.edu.cn
phone: 19821231773
---

# **陈学添**

<!--
include contact information from the front matter
Supported arguments:
    - homepage: url, text
    - phone
    - email
-->

{% include cv-contact.html %}

## 教育背景

### **复旦大学** `2023.9 - 2026.6`

- 统计学学硕在读，获复旦大学 2023-2024、2024-2025 学年研究生学业奖学金

### **复旦大学** `2019.9 - 2023.6`

- 理学学士学位，数据科学与大数据专业，均绩：3.73/4.0，专业排名：9/80
- 多次获复旦大学本科生奖学金、优秀学生等奖项

## 实习经历

### **字节跳动** `2025.5 - 至今`
_Tiktok-主端短视频推荐算法-精排推荐大模型_
- \[WIP\] 多模态推荐大模型：
  - \[Owner\] 多模态内容理解大 dense 特征引入推荐模型，确定接入方式、推动训推侧通信和缓存优化、推荐模型内建模方式和生效验证逻辑正探索中。
  - \[Owner\] 多模态特征引入推荐模型，在特征形式 (dense/token)、特征尺度和模型尺度上的 scaling law 验证。
  - \[共建\] 多模态特征产出侧优化提需，包括抽帧方式优化、领域数据适应、对比学习微调、推荐生态任务 post-training 等方案讨论，以及在推荐侧的评估基准设计。
- \[Owner\] Listwise 天级聚合的训练数据流迁移验收和打平全流程，保证 listwise 样本聚合度足够高，确保训练稳定性。
- \[参与\] Backbone 复杂化：推荐大模型 backbone 选型 (MMCN, Transformer, TokenMixer, Wukong)，在迁移新训练框架后适配模型代码，分析离在线收益和异常现象。
- \[Owner\] Multi-epoch 训练，各种数据混合方式的探索与离在线现象和过拟合来源分析。

### **上海人工智能实验室** `2024.12 - 2025.5`

_大模型中心-群体智能项目-Computer Use 应用方向_<br>
- 独立一作主导上述 Computer Use Benchmark 研究，进行背景调研、概念设计、方案设计、落地实现、规模众包等工作，设计了416个评估任务，在自动化程度与泛化范围两个维度上评估智能体的能力与用户真实需求的匹配度，独立一作 ICLR 2026 在投。
- 参与团队成员研究课题，Computer Use 场景的输出动作模式优化，减少推理步骤长度，降低50%任务执行耗时，ICLR 2026 在投。

### **字节跳动** `2022.12 - 2023.8 `

_闭环电商广告算法-流量策略-千川聚合页方向_<br>

- 模型：参与聚合页广告 CTR、CVR 预估模型的迭代与 CTR/CVR 统一模型的架构设计、特征工程。优化模型预估准确度以提升产品效率，提升聚合页消耗和大盘消耗。
- 链路/策略：协同优化聚合页投放链路与计费逻辑，在精排阶段根据聚合页逻辑，增设多条指标打点并设计监控看板，参与问题排查，促进聚合页稳步迭代。

## 科研经历

### **投稿论文**

_**Xuetian Chen**, Yinghao Chen, et al. OS-MAP: How Far Can Computer-using Agents Go in Beatdth and Depth?_ [[PDF](https://arxiv.org/abs/2507.19132)][[Repo](https://github.com/OS-Copilot/OS-Map)]

独立一作，ICLR 2026 在投。日常场景的 Computer Use 能力综合评估基准。提炼出 L1-L5 自动化程度分级框架来解析 Computer Use 核心能力与挑战；基于对日常生活场景的需求分析来设计任务集，以覆盖日常使用场景。结合自动化程度与泛化范围两维度，构建评估矩阵，设计并实现416个评估任务，系统性地评估 Computer Use Agents 的能力。 `2025.5`

**_Xuetian Chen,_** _Hangcheng Li, Jiaqing Liang, Sihang Jiang, and Deqing Yang. EDGE: Enhanced Grounded GUI Understanding with Enriched Multi-Granularity Synthetic Data._[[PDF](https://arxiv.org/pdf/2410.19461)][[Repo](https://github.com/chenxuetian/EDGE)][[OpenReview](https://openreview.net/forum?id=9P8Zut9qul&noteId=jL7OZ2qjwG)] `2024.10`

独立一作，数据驱动的方式增强多模态大模型在 GUI Grounding 任务上的能力。设计一套完整的、自动化的网页标注-数据合成框架，生成丰富的多层次、多粒度屏幕问答，用于训练多模态大模型的 GUI 理解与交互能力，重点关注 Grounding，尤其对难以自动化标注的图标数据针对增强。

_Xinfeng Yuan, Qiushi Sun, Yinghao Chen, Rui Li, **Xuetian Chen**, et al. OS-Catalyst: Advancing Computer-Using Agents Efficiency through Adaptive Action Compression_
设计一套适于 computer use Agent 动作轨迹压缩训练的数据收集流程，通过训练 compute use agent 的动作序列预测能力，减少连续动作间不必要的观察，降低推理过程的步骤数量与50%时间开销。 `2025.5`

### **项目经历**

**_Coldint Subnet Training Competition_** 独立使用 8\*H200 开展 phi3-16.7B 模型的大规模训练，以求在 FineWeb 的子集上获得最小的 next token prediction loss。主导高效数据 pipeline、分布式训练框架的建立，以及 Flash-attention-2 在 phi3 上的适配，提升训练效率 3x。目前正进一步探索高效的算子、优化器、模型融合方案和数据分布技巧，提交模型曾位排行榜第一。`2024.12`

## 学术竞赛

### **全国大学生数学建模竞赛** `2022.9 `

_C 题： 古代玻璃制品的成分分析与鉴别，获上海赛区二等奖_<br>
使用稀疏主成分分析选择重要的化学元素、结合 SVM 模型对样品分类、利用 K-Mediods 算法对样品聚类，并结合敏感性分析和 t-SNE 降维可视化算法对模型进行解释和分析。

### **美国大学生数学建模竞赛** `2022.2 `

_Honorable Mention on Problem C: Trading Strategies_<br>
利用 Prophet 对资产价格数据建立时间序列模型；基于模型的短期预测结果，结合 Markowitz 投资组合理论，构建优化问题并求解最优交易策略；综合长短期投资的特点设计长期策略；并进行敏感性分析。

<!-- ### Footer

Last updated: May 2013 -->
