# QoE-CAC

**QoE-CAC: Attention- and Communication-Aware Quality of Experience Metric for Immersive Communication Systems Over 5G Mobile Networks**

[![MATLAB](https://img.shields.io/badge/MATLAB-R2021b%2B-orange?logo=mathworks)](https://www.mathworks.com/)
[![Lab](https://img.shields.io/badge/Lab-LABORA--INF--UFG-green)](https://labora.inf.ufg.br/)

---

## 📄 About

This repository contains the MATLAB source code and datasets associated with the following publication:

> **Attention- and Communication-Aware Quality of Experience Metric for Immersive Communication Systems Over 5G Mobile Networks**
> 🔄 *Under review*

The QoE-CAC metric combines attention awareness and communication quality to evaluate the user experience in immersive communication systems (e.g., XR, holographic telepresence) over 5G networks.

---

## 📁 Repository Structure

```
QoE-CAC/
├── QoE_CAC_code/           # MATLAB source code and datasets
│   ├── main.m              # Main script
│   ├── analise_qoe_cac_vs_optimal.m
│   ├── analise_ablacao.m
│   ├── analise_mos.m    
│   ├── analise_dataset_RACA.m    
│   ├── 5Gdataset/          # 5G measurement traces (RACA dataset)
│   └── ...                 # Additional scripts and data files
└── README.md
```

---

## ⚙️ Requirements

- **MATLAB** R2021b or later
- Toolboxes:
  - Communications Toolbox
  - Signal Processing Toolbox
  - Statistics and Machine Learning Toolbox *(if applicable)*

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/LABORA-INF-UFG/QoE-CAC.git
cd QoE-CAC
```

### 2. Open MATLAB and add the project to the path

```matlab
addpath(genpath('QoE_CAC_code'));
```

### 3. Run the main simulation

```matlab
run QoE_CAC_code/main.m
```

---

## 📬 Contact

**LABORA – Computer Networks and Distributed Systems Laboratory**
Instituto de Informática – Universidade Federal de Goiás (UFG)
🌐 [labora.inf.ufg.br](https://labora.inf.ufg.br)

> For questions or issues, please open a [GitHub Issue](https://github.com/LABORA-INF-UFG/QoE-CAC/issues).

---

## 📖 How to Cite

If you use this code in your research, please cite:

```bibtex
@unpublished{qoecac_en,
  author = {de Oliveira Santos, Rosana and Carlos Eduardo and Macedo, Ciro J. A. and de Oliveira-Jr., Antonio Carlos},
  title  = {Attention- and Communication-Aware Quality of Experience Metric for Immersive Communication Systems Over {5G} Mobile Networks},
  note   = {Under review},
}
```

---

## 📝 License

This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.
