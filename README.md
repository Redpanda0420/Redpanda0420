# 黄星雨 · Xingyu Huang

**Materials Computation · Machine-Learning Potentials · Agent-driven Scientific Automation**

博士在读 @ 电子科技大学（仪器科学与技术）· 材料计算与电池材料方向
Part-time computational engineer @ 天玑算（材料计算项目交付 · 远程）

[![ORCID](https://img.shields.io/badge/ORCID-0009--0003--1604--7911-a6ce39?logo=orcid&logoColor=white)](https://orcid.org/0009-0003-1604-7911)
[![Email](https://img.shields.io/badge/Email-2729477620%40qq.com-blue?logo=mail.ru&logoColor=white)](mailto:2729477620@qq.com)

---

### 关于我

- 🔬 做**能判对错的 AI4Science**：不是"跑通就算完"，而是把收敛判据、泛函/赝势一致性、平台间能量偏差这些硬指标写进流程。
- ⚙️ 把科研做成**可复跑的流水线**：建模 → 输入生成 → 批量提交 → 监控自愈 → 数据分析 → 出图报告，全链路脚本化 + Agent 驱动。
- 📄 一作论文 2 篇（*ACS Nano*、*J. Power Sources*），研究方向覆盖锂金属负极人工保护层、嵌锂机制与微波化学。

---

### 研究方向

| 方向 | 具体内容 |
|---|---|
| **电池材料计算** | 嵌锂/脱锂机制、人工 SEI 层界面、缺陷形成能与化学势窗口、CI-NEB 迁移势垒 |
| **机器学习势** | DeepMD / MACE 势训练与部署；主动学习闭环（ALIGNN + ensemble 不确定性采样） |
| **科学计算自动化** | 异构算力调度、断点续跑与崩溃自愈、跨平台一致性核验、并行配置标定 |
| **科学 Agent 评测** | 为材料与物理计算构建可复现的评测基准与 rubric（收敛性 / 误差传递 / 结果可证伪性） |

---

### 开源仓库

| 仓库 | 内容 | 状态 |
|---|---|---|
| [**alignn-active-learning**](https://github.com/Redpanda0420/alignn-active-learning) | ALIGNN 主动学习闭环：数据集构建 → 多模型集成训练 → 不确定性采样 → 下一批 VASP 输入 | ✅ 已开源 |
| [**dft-ops-kit**](https://github.com/Redpanda0420/dft-ops-kit) | VASP / CP2K 计算运维工具箱：批量输入生成、U 值扫描汇总、逐原子应力分析 | ✅ 已开源 |
| [**neb-toolkit**](https://github.com/Redpanda0420/neb-toolkit) | NEB 工具：端点一致性核验、迁移路径 3D 可视化、势垒曲线绘制 | ✅ 已开源 |

---

### 技术栈

```
第一性原理    VASP (PBE / DFT+U / HSE06 / NEB-VTST / VASPsol) · CP2K (static · AIMD · CI-NEB)
分子动力学    CP2K-AIMD · GROMACS · LAMMPS · DeepMD
机器学习      PyTorch · ALIGNN · 主动学习 · 不确定度量采样 · SHAP
工程与运维    Python · pymatgen / ASE · Slurm / MPI · 源码编译部署 · 自动化调度与自愈
可视化        OVITO · VESTA · Origin · Matplotlib
```

---

### 论文与专利

**论文**

1. *LiF-Li₃N Surface Treatment for High Cycle Life Lithium Metal Batteries* — **第一作者**, *ACS Nano*
2. *Preparation of a Lithium Negative Electrode Zinc Alloy Protective Layer Using Magnetron Sputtering for Lithium Metal Batteries* — **第一作者**, *Journal of Power Sources*
3. *Dependence of plasma-enhanced fluorination on CNTs precursor for high-quality CFx cathode materials* — 第三作者（在投）

**专利**

1. 复合集流体薄膜应力控制电镀制备装置及工作方法 — CN202310335354.0（第一发明人）
2. 一种复合集流体的制备方法 — CN202310675838X

---

### 项目经历（脱敏）

> 商业项目受保密协议约束，仅列技术范围。

- **锂离子电池正极嵌锂机制**：三工况 AIMD 对照 + 逐原子应力场 3D 分析 + CI-NEB（正/反向 + 应变编码）+ 缺陷与掺杂批算 + 主动学习筛选。
- **反铁电钙钛矿机器学习势**：DFT 小胞造标签 → 短程势 → 长程静电修正 → 大胞电场驱动 MD → 极化/畴/倾角出图；以"态分辨精度"为 Go/No-Go 闸门。
- **III–V 半导体电子结构通用模型**：数据集口径界定、参数封条与批次一致性核验。
- **多机异构算力调度系统**：自建 4090 + 双 V100-32G + P40 机群 + 公有云分区，统一提交、核绑定、跨卡并行、崩溃重试与断点续跑。

---

### 联系我

- 📧 2729477620@qq.com
- 🏫 电子科技大学 · 仪器科学与技术（2029 届博士）
- 🆔 ORCID: [0009-0003-1604-7911](https://orcid.org/0009-0003-1604-7911)

<sub>Last updated: 2026-11</sub>
