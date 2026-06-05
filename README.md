\# QoE-CAC


\*\*QoE-CAC: Attention- and Communication-Aware Quality of Experience Metric for Immersive Communication Systems Over 5G Mobile Networks\*\*

This repository contains the MATLAB source code and datasets associated with the following publication:

> \*\*Attention- and Communication-Aware Quality of Experience Metric for Immersive Communication Systems Over 5G Mobile Networks\*\*

> 🔄 \*Under review\*


Immersive Communication Systems (ICS) represent a new frontier for services that integrate users and applications within highly connected environments, such as online virtual games, augmented reality meetings, and metaverse experiences. The viability of these systems strongly depends on the Quality of Experience (QoE), which requires stringent network resource conditions, particularly ultra-low latency, high bandwidth, and stable communication, to provide truly immersive interactions. Although several QoE metrics have been proposed in the literature, few incorporate the cognitive aspects related to user attention during interactions with virtual environments. This study introduces an innovative metric called Attention- and Communication-Aware Quality of Experience (QoE-CAC), which unifies 5G mobile network communication performance factors and user attention behavior into a single model.

\---



\## 📁 Repository Structure



```

QoE-CAC/

├── QoE\_CAC\_code/           # MATLAB source code and datasets

│   ├── main.m              # Main script

│   ├── analise\_qoe\_cac\_vs\_optimal.m

│   ├── analise\_ablacao.m

│   ├── analise\_mos.m    

│   ├── analise\_dataset\_RACA.m    

│   ├── 5Gdataset/          # 5G measurement traces (RACA dataset)

│   └── ...                 # Additional scripts and data files

└── README.md

```



\---



\## ⚙️ Requirements



\- \*\*MATLAB\*\* R2021b or later

\- Toolboxes:

&#x20; - Communications Toolbox

&#x20; - Signal Processing Toolbox

&#x20; - Statistics and Machine Learning Toolbox \*(if applicable)\*



\---



\## 🚀 Getting Started



\### 1. Clone the repository



```bash

git clone https://github.com/LABORA-INF-UFG/QoE-CAC.git

cd QoE-CAC

```



\### 2. Open MATLAB and add the project to the path



```matlab

addpath(genpath('QoE\_CAC\_code'));

```



\### 3. Run the main simulation



```matlab

run QoE\_CAC\_code/main.m

```



\---



\## 📬 Contact



\*\*LABORA – Computer Networks and Distributed Systems Laboratory\*\*

Instituto de Informática – Universidade Federal de Goiás (UFG)

🌐 \[labora.inf.ufg.br](https://labora.inf.ufg.br)



> For questions or issues, please open a \[GitHub Issue](https://github.com/LABORA-INF-UFG/QoE-CAC/issues).



\---



\## 📖 How to Cite



If you use this code in your research, please cite:



```bibtex

@unpublished{qoecac\_en,

&#x20; author = {de Oliveira Santos, Rosana and Carlos Eduardo and Macedo, Ciro J. A. and de Oliveira-Jr., Antonio Carlos},

&#x20; title  = {Attention- and Communication-Aware Quality of Experience Metric for Immersive Communication Systems Over {5G} Mobile Networks},

&#x20; note   = {Under review},

}

```



\---



\## 📝 License



This project is licensed under the MIT License — see the \[LICENSE](LICENSE) file for details.

