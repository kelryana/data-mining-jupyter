# 📊 Data Mining com Jupyter

Projetos de Data Mining e Machine Learning desenvolvidos com Jupyter Notebook, como evolução dos estudos iniciados no Orange Data Mining.

## 🎯 Objetivo

Migrar análises de dados para um ambiente versionável e publicável, gerando artefatos que podem ser compartilhados no GitHub e transformados em artigos técnicos.

## 🛠️ Tecnologias

- **Python 3**
- **Jupyter Notebook**
- **pandas** — Manipulação de dados
- **matplotlib** — Visualização de gráficos
- **seaborn** — Gráficos estatísticos
- **scikit-learn** — Machine Learning e datasets

## 📂 Estrutura

```text
data-mining-jupyter/
├── 01-jupyter-data-mining.ipynb   ← Análise exploratória do dataset Íris
├── venv/                           ← Ambiente virtual
└── README.md
```

## 🚀 Como Rodar

### Pré-requisitos

- Python 3.11+
- Git

### Instalação

```bash
git clone [https://github.com/kelryana/data-mining-jupyter.git](https://github.com/kelryana/data-mining-jupyter.git)
cd data-mining-jupyter
python3 -m venv venv
source venv/bin/activate
pip install notebook pandas matplotlib seaborn scikit-learn
jupyter notebook
```

### 📓 Notebook 01 — Análise do Dataset Íris

Análise exploratória clássica incluindo:

- Carregamento do dataset *built-in* do scikit-learn
- Estatísticas descritivas com pandas
- Visualização com `pairplot` do seaborn
- Interpretação dos padrões entre as espécies


