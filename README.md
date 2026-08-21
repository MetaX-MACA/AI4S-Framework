# AI4S-Framework

本项目汇集了多个可用于**沐曦（MetaX）GPU** 的 AI4S 框架适配与科学计算解决方案。我们专注于构建高性能、易适配的AI for Science（AI4S）软件栈，助力您在生物信息学、流体力学、材料科学等前沿领域的科研与开发工作。

## 📂 项目结构与说明

本文件夹以**聚合分发**方式提供多个相互独立的开源项目，各项目作为独立程序分别置于各自子目录中，我方仅将其聚合打包传输，并未将其组合为单一作品。各项目分别受其自带许可证约束，您在使用或分发任一项目前，须遵守该项目对应许可证的条款。如各项目内另附有我方提供的Patch文件或适配文件，系针对相应开源项目的修改或组合，此文件的许可证放置于对应文件夹中。


### 框架支持

以下是目前已适配沐曦GPU的核心AI框架与科学计算模型概览：

| 名称 | 类别 | 核心任务/技术 | 适用场景 |
| :--- | :--- | :--- | :--- |
| **[DeepXDE](https://github.com/MetaX-MACA/AI4S-Framework/tree/main/DeepXDE)** | AI框架（科学计算） | 物理信息神经网络（PINN）求解偏微分方程，支持多种后端（PyTorch, PaddlePaddle等）。 | 计算流体力学、固体力学、传热学等物理场模拟与反问题求解。 |
| **[PaddleScience](https://github.com/MetaX-MACA/AI4S-Framework/tree/main/PaddleScience)** | AI框架（科学计算套件） | 基于飞桨（PaddlePaddle）的科学计算套件，支持物理机理驱动、数据驱动及数理融合求解方式。 | 流体仿真、材料设计、地球科学、天气预报等复杂工程与科学问题。 |
| **[PhysicsNeMo](https://github.com/MetaX-MACA/AI4S-Framework/tree/main/PhysicsNeMo)** | AI框架（科学计算） | 物理信息与数据驱动的 AI 物理仿真深度学习框架，支持神经算子、GNN、Transformer、PINN 等多种建模范式。 | 计算流体力学、天气气候、分子动力学、地球科学等物理场模拟与预测。 |
| **[NeuralOperator](https://github.com/MetaX-MACA/AI4S-Framework/tree/main/NeuralOperator)** | AI框架（科学计算） | 面向 PDE 与连续物理场建模的 Operator Learning 框架，提供 FNO、TFNO 等神经算子模型，用于学习输入物理场、参数场或初边值条件到输出解场之间的映射。| 流体、传热、结构、气象等 PDE 问题的代理建模、场预测和快速推理，也是 AI4S 中 Operator Learning 的重要基础框架。|
| **[PINA](https://github.com/MetaX-MACA/AI4S-Framework/tree/main/PINA)** | 科学机器学习框架 | 简化和加速科学机器学习（SciML）解决方案的开发 |  物理信息神经网络（PINN）、数据驱动建模、降阶建模以及偏微分方程求解 |



>更多框架和应用正在持续适配与添加中，敬请关注。


---

## 🚀 快速开始

### 环境与依赖

*   **硬件**: 需具备沐曦（MetaX）GPU（如曦云C系列、曦索X系列科学计算GPU）。
*   **基础软件**: Linux操作系统，沐曦GPU运行时环境及MXMACA软件栈。
*   **主要依赖**: Python 3.8+，**PyTorch（适配沐曦GPU版本）**, **PaddlePaddle 适配沐曦GPU版本）**，以及各子项目特定的依赖库。

### 安装与使用

具体安装与使用步骤，请参阅各子项目文件夹内的独立指南（如`README.md`或`UserGuide`）。

---

## ⚠️ 合规与许可证声明

在使用本仓库中的任何资源前，请仔细阅读并遵守以下声明：

1.  **独立项目**：本仓库中的每个子项目均为独立的开源项目，保留其原有的许可证和版权声明。我方仅提供聚合分发服务，不对这些项目的功能、安全性或合规性做额外担保。
2.  **使用责任**：您有责任理解并遵守每个子项目自带的许可证条款。在使用或分发任何子项目时，请确保完全符合其许可证要求。
3.  **修改与组合**：如子项目内包含由我方提供的Patch文件或适配文件，这些特定文件的许可证将放置于对应的子文件夹中，请在使用时一并遵循。

---

## 🤝 贡献与反馈

欢迎通过GitHub Issues或Pull Requests提出建议、报告问题或贡献新的适配模型与框架。让我们一起推动国产算力生态与AI4S领域的革新！

**感谢您对沐曦GPU生态及AI for Science发展的关注与支持！**