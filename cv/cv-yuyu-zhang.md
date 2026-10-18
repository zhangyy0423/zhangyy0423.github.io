# CV — 张宇雨 / Yuyu Zhang

**求职意向**：AI 数据平台 / 数据库内核开发 / 存储引擎 / 多模态数据系统

电话 136-0165-4345 ｜ zhangyy0423@foxmail.com ｜ 上海 ｜ 主页 zhangyy0423.github.io ｜ ORCID 0009-0006-7430-6039

---

## 个人优势

- 6 年+ 数据库内核与后端工程经验：GaussDB、GaiaDB 底层系统实践 + 企业级 AI 数据平台建设，能从数据底座、服务架构和产品功能闭环理解问题。
- **独立科研产出**（2026，personal time）：预注册因果研究方法 + 4 篇论文（1 篇已发 arXiv 在审、1 篇 CPAIOR 2027 投稿、2 篇 in preparation）+ 2 个 DOI 工件 + 1 项发明专利（实审中）。
- 近期聚焦 Foundry 类 AI 数据平台：数据接入、语义建模（Ontology）、任务/工作流编排、工具调用、权限治理与审计。
- 熟悉 C/C++、Linux 调试、性能优化、数据库执行器/存储/兼容框架；复杂系统问题定位与稳定交付经验。
- 熟练使用 Codex、Claude Code 辅助复杂代码理解、重构、测试补齐与文档沉淀，保持人工复核闭环。

## 工作经历

**2025.04 – 至今 ｜ 百度 GaiaDB 数据库 ｜ 数据库内核开发工程师（存储组）**
- 企业级 AI 数据平台开发：数据融合、语义建模、自然语言驱动数据操作等产品基础模块；数据接入、语义层、任务编排、上下文管理、工具调用、权限治理闭环。
- **独立设计 Log Service 容错改进方案**：同步窗口 6GB → 100GB，支持慢节点约 30 分钟不卡写，显著提升写入链路稳定性。
- 参与 GaiaDB 国测项目，获百度小赞。

**2023.03 – 2025.03 ｜ 华为云 GaussDB 数据库 ｜ 数据库内核开发工程师**
- 执行器组：TPCH 打榜，向量化执行引擎性能优化（Numeric/条件表达式/算子），TPCH-33x/100x 整体提升 12%–15%，算术运算单项约 50%。
- M 兼容组骨干：数据类型/运算符/函数兼容开发，支撑金融企业 MySQL 替换；内核代码 8k+、用例 10w+、问题单 50+。
- **Hackathon 软件挑战赛华为一等奖**（大规模分布式任务调度，蒙特卡洛搜索树联合调度算法）；两次部门金 cloud 奖。

**2021.05 – 2023.03 ｜ 上海中冶环保运营管理有限公司 ｜ 能环专员**
- 宝钢炼铁区域除尘节能降耗、集中集控及环保智慧运营平台建设；现场业务理解与跨团队协同。

**2018 ｜ 上海禾赛光电 ｜ 软件实习工程师**
- Qt 开发 Pandar40 雷达固件升级工具。

## 独立科研（2026，personal time and equipment）

**论文（4 篇）**
1. **Equal-Budget MCTS versus Randomized-Restart List Scheduling for DAG Workflows: A Controlled Equal-Budget Computational Study.** arXiv:2610.12542（2026-10，在审）。预注册可复现负结果 + 开放评估协议。
2. **The Three Deaths of Search: A Repair-Rate Accounting of Why Budget-Limited Value Collapses.** arXiv preprint（2026-10，CPAIOR 2027 投稿）。预算受限搜索价值幂律坍缩（斜率≈−1.7）+ 预注册四臂因果阶梯 + 修复率记账 η=ρd·ρeff·f/κ；真实 MIPLIB 实例验证。
3. **The Line That Was Never Written: A Four-Level Elimination Ladder Localizes an Implementation-Determined Search Signature to a Single Initialization Omission.** In preparation（2026）。
4. **When Can Structural Repair Transfer Across Domains? A Repair-Rate Accounting of Search-Value Collapse.** In preparation（2026）。

**DOI 工件（Zenodo，可引用）**
- DAG Budget Scheduling Benchmark Suite — DOI 10.5281/zenodo.22929494
- Heuristic Evaluation Audit Protocol — DOI 10.5281/zenodo.22930513

**发明专利**
- 一种窗口化大邻域结构修复的调度方法及装置（wlns W-ladder）。CNIPA 申请号 2026114949359，2026-09 受理，实质审查中。

## 大学期间科研

- **期刊论文**：马锐, **张宇雨**, 王菲菲, 刘琪瑶, 李嘉琪, 魏金枝*. Ni-BTC/RGO 复合材料的制备及其电化学性能. 《材料工程》2022, 50(6): 124–130. DOI 10.11868/j.issn.1001-4381.2020.000244（第二作者；比电容 468.72 F/g@0.5 A/g）。
- **专利**：一种电化学合成金属有机框架材料 Ni-BTC 的方法（CN110484932A，申请号 201910830552.8，申请日 2019-09，申请人：哈尔滨理工大学）。
- **项目**：省级大学生创新创业项目负责人。
- **竞赛**：全国大学生数学建模省一等奖；中国大学生博弈大赛二等奖；全国大学生数学竞赛三等奖。

## 主要技术

- **AI 与数据平台**：数据接入、语义建模（Ontology）、任务编排、工具调用、权限治理与审计；结合数据库/存储背景的工程落地。
- **数据库内核**：执行器、向量化执行、数据类型系统、兼容框架、存储日志服务；内核问题定位与性能优化。
- **C/C++ / Linux**：gdb 调试、性能分析、工程化交付。
- **存储与可靠性**：日志复制、同步窗口、慢节点处理、故障恢复。
- **LLM 应用**：Prompt 工程、RAG、Function/Tool Calling、上下文管理与评测闭环。
- **AI 工具链**：Codex、Claude Code、GitHub Copilot 辅助研发（含人工复核闭环）。
- **工具**：Git、CMake、Docker、VSCode、gdb、valgrind。

## 教育背景

**2016.09 – 2020.06 ｜ 哈尔滨理工大学 ｜ 环境工程 本科**
GPA 3.32/5.0（专业前 5%）；校优秀毕业生、三好学生、优秀团员、奖学金若干。

## 证书

软考（中级）｜ 华为软件开发能力认证（专业级）｜ CET-4
