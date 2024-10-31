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

- 理学学士学位，大数据学院，数据科学与大数据专业，均绩：3.73/4.0，专业排名：9/80
- 获复旦大学本科生奖学金一等奖、二等奖、三等奖、优秀学生等奖项

### **复旦大学** `2023.9 -`

- 统计学学硕在读，获复旦大学 2023-2024 学年研究生学业奖学金

## 科研经历

### **在投论文**

**(WWW 2025 Under Review) _Xuetian Chen,_** _Hangcheng Li, Jiaqing Liang, Sihang Jiang, and Deqing Yang. EDGE: Enhanced Grounded GUI Understanding with Enriched Multi-Granularity Synthetic Data. In Proceedings of the 2025 ACM Web Conference (under review)._[[PDF](https://arxiv.org/pdf/2410.19461)][[Repo](https://github.com/chenxuetian/EDGE)] `2024.10`

数据驱动的视觉-语言大模型在 GUI 理解与交互任务上的能力增强方法。设计一套完整的、自动化的数据合成框架，标注网页并合成丰富的多粒度屏幕问答数据，用于训练视觉-语言大模型的 GUI 理解与交互能力。重点训练模型的 GUI Grounding 能力，尤其对难以自动化标注的图标数据和高级问答任务做了增强。

### **正在进行**

- 上述工作的进一步完善：基于自动化网页标注-问答数据合成框架的高质量 GUI 理解与交互数据集构建与质量评估。
- 使用已具备 GUI Grounding 能力的开源视觉-语言大模型（如 Qwen2-VL）构建 GUI 理解与交互的自动化 Agent 框架，实现 Claude Computer Use 演示的效果。
- 视觉-语言大模型训练过程中图文问答数据的组织形式：多轮独立的问答是否能带来更好的训练效果。

### **过往项目** `2022.12 - 2023.6`

**三维计算机视觉**

- 本科毕设：Transformer 架构三维点云实例分割模型。设计并训练点云输入的 Transformer 架构模型，分析相较于传统稀疏卷积网络的优势与不足。
- 项目经历：三维视觉统一模型：将常见目标检测、语义分割、实例分割等常见三维视觉任务统一为点云输入输出，使用统一模型完成多种任务。

## 实习经历

### **字节跳动** `2022.12 - 2023.8 `

_电商广告算法实习生-聚合页方向_<br>

- 深入参与聚合页广告点击率、转化率预估模型的设计和迭代，提升产品效率
- 协同优化聚合页投放链路、流量策略和计费逻辑，提升稳定性
- 独立对接上游需求，开发数据链路，增设监控指标，解决真实产品问题

### **阳狮集团 (Publicis Groupe)** `2021.6 - 2021.9 `

_广告行业数据分析实习生_<br>

- 参与部门 Marketing Mix Modeling (MMM)的算法设计、优化与部署
- 基于 PySpark，结合机器学习算法，提取、处理、分析电商销售数据与评论数据，并将结果可视化

## 学术竞赛

### **全国大学生数学建模竞赛** `2022.9 `

_C 题： 古代玻璃制品的成分分析与鉴别，获上海赛区二等奖_<br>
完成使用稀疏主成分分析法选择重要的化学元素、结合支持向量机模型进行对样品分类、利用 K-Mediods 算法对样品聚类等任务，并结合敏感性分析和 t-SNE 降维算法可视化对模型进行解释和分析。

### **美国大学生数学建模竞赛 (MCM)** `2022.2 `

_Honorable Mention on Problem C: Trading Strategies_<br>
利用 Prophet 对价格数据建立时间序列模型；基于模型的短期预测结果，结合 Markowitz 均值-方差投资组合理论，构建优化问题并求解最优交易策略；综合长短期投资的特点设计长期策略；并进行敏感性分析。

## 课程项目

### **知识图谱** `2023.12`

爬取互联网上的医疗知识，构建图数据库形式的中西医疗领域知识图谱。在此之上，利用 LLM 强大的的自然语言处理、生成，以及函数调用能力，构建智能问答系统，支持复杂的多轮、多跳查询。

### **数据可视化** `2023.12`

全息交通数据可视化分析：设计驾驶画像可视分析和交通态势可视分析系统，简单的前后端分离架构，实现多视图动态展示和联动的效果。[项目地址](https://github.com/chenxuetian/FduDataVisFinal-2023)

### **图像处理与可视化** `2022.6 `

针对全景图像拼接任务，实现 SIFT 特征提取算法从两张图中抽取特征，进一步拟合反向投影变换。经实验，与 OpenCV 的实现结果相近。[项目地址](https://gitee.com/Hu-Icarus/image-process)

### **人工智能** `2021.12 `

分别基于对抗搜素、蒙特卡洛树搜索和强化学习实现五子棋 AI，其中最优 AI 获 Bayesian Elo 评分 1845，时列班级第一。[项目地址](https://github.com/Darkroom-Godot/DATA130008.01-Group-Project-Gomoku)

## 技能与其他

- **计算机技能：** 熟练使用 Python、C/C++、JS、MATLAB、R 等语言，以及 Pytorch、Transformers、LLaMA-Factory 等常用深度学习框架/库。了解组成原理、体系结构、系统、网络等知识，深入自学中。
- **数学基础：** 熟悉运筹、优化、统计、回归、随机过程、统计学习等知识，初步了解测度论、泛函分析的内容。
- **研究兴趣：** 多模态大模型在 GUI 交互上的应用，及其架构设计、训练模式、数据合成；大规模分布式训练与推理系统

<!-- ### Footer

Last updated: May 2013 -->
