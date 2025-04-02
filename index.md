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

### **复旦大学** `2019.9 - 2023.6`

- 理学学士学位，数据科学与大数据专业，均绩：3.73/4.0，专业排名：9/80
- 多次获复旦大学本科生奖学金、优秀学生等奖项

### **复旦大学** `2023.9 - 2026.6`

- 统计学学硕在读，获复旦大学 2023-2024 学年研究生学业奖学金

## 科研经历

### **投稿论文**

**_Xuetian Chen,_** _Hangcheng Li, Jiaqing Liang, Sihang Jiang, and Deqing Yang. EDGE: Enhanced Grounded GUI Understanding with Enriched Multi-Granularity Synthetic Data._[[PDF](https://arxiv.org/pdf/2410.19461)][[Repo](https://github.com/chenxuetian/EDGE)][[OpenReview](https://openreview.net/forum?id=9P8Zut9qul&noteId=jL7OZ2qjwG)] `2024.10`

独立一作，数据驱动的方式增强多模态大模型在 GUI Grounding 任务上的能力。设计一套完整的、自动化的网页标注-数据合成框架，生成丰富的多层次、多粒度屏幕问答，用于训练多模态大模型的 GUI 理解与交互能力，重点关注 Grounding，尤其对难以自动化标注的图标数据针对增强。

### **进行中论文**

**_独立一作，即将投稿 NeurIPS 2025_** 日常场景的 Computer Use 能力综合评估基准。提炼出 L1-L5 自动化程度分级框架来解析 Computer Use 核心能力与挑战；基于对日常生活场景的需求分析来设计任务集，以覆盖日常使用场景。结合自动化程度与泛化范围两维度，构建评估矩阵，系统性地评估 Computer Use Agents 的能力。 `2024.12-至今`

### **项目经历**

**_Coldint Subnet Training Competition_** 独立使用 8\*H200 开展 phi3-16.7B 模型的大规模训练，以求在 FineWeb 的子集上获得最小的 next token prediction loss。主导高效数据 pipeline、分布式训练框架的建立，以及 Flash-attention-2 在 phi3 上的适配，提升训练效率 3x。目前正进一步探索高效的算子、优化器、模型融合方案和数据分布技巧，提交模型曾位排行榜第一。`2024.11-至今`

## 实习经历

### **上海人工智能实验室** `2024.12 - 至今`

_大模型中心-群体智能项目-Computer Use 应用方向_<br>

- 独立一作主导上述 Computer Use Benchmark 研究，进行背景调研、概念设计、方案设计、落地实现、规模众包等工作。
- 参与团队成员研究课题，PPO 在 Agent 场景的环境适应与推理增强上的适配，探索 RL 实现 agentic model 的路径
- 带教校内 5 位同学的本科毕设/科研项目，涉及 Computer Use Agent 的数据合成与质量评估、场景应用等方向

### **字节跳动** `2022.12 - 2023.8 `

_闭环电商广告算法-流量策略-千川聚合页方向_<br>

- 模型：深入参与聚合页广告 CTR、CVR 预估模型的迭代，包括特征开发与筛选、推理延时优化等；参与 CTR/CVR 统一模型的架构设计、特征工程，跟进后续测试上线。优化模型预估准确度以提升产品效率，进而提升聚合页消耗和大盘消耗。
- 链路/策略：协同优化聚合页投放链路与计费逻辑，在精排阶段根据聚合页逻辑，增设多条指标打点并设计监控看板，多次参与问题排查，旁听事故复盘，以提升产品稳定性与可控性，促进聚合页稳步迭代。
- 需求对接：独立对接和推进来自链路、前端和产品的多条需求，开发数据链路，解决实际产品问题

### **阳狮集团 (Publicis Groupe)** `2021.6 - 2021.9 `

_广告数据分析_<br>

- 参与 Marketing Mix Modeling (MMM)回归模型的优化与部署。包括添加权重约束、超参数调优、特征合并，换用贝叶斯框架等。
- 基于 PySpark，结合机器学习算法，对电商销售数据和评论数据进行查询、分析、建模、可视化等操作。

## 学术竞赛

### **全国大学生数学建模竞赛** `2022.9 `

_C 题： 古代玻璃制品的成分分析与鉴别，获上海赛区二等奖_<br>
使用稀疏主成分分析选择重要的化学元素、结合 SVM 模型对样品分类、利用 K-Mediods 算法对样品聚类，并结合敏感性分析和 t-SNE 降维可视化算法对模型进行解释和分析。

### **美国大学生数学建模竞赛** `2022.2 `

_Honorable Mention on Problem C: Trading Strategies_<br>
利用 Prophet 对资产价格数据建立时间序列模型；基于模型的短期预测结果，结合 Markowitz 投资组合理论，构建优化问题并求解最优交易策略；综合长短期投资的特点设计长期策略；并进行敏感性分析。

## 技能掌握

- **计算机技能：** 熟练使用 Python、C/C++、JS、MATLAB、R 等语言，以及 Pytorch、Transformers、LLaMA-Factory 等常用深度学习框架/库。了解组成原理、体系结构、系统、网络等计算机知识。
- **数学基础：** 熟悉运筹、优化、统计、回归、随机过程、统计学习等知识，初步了解测度论、泛函分析的内容。

<!-- ### Footer

Last updated: May 2013 -->
