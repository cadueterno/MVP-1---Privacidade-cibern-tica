
# MVP - Detecção de Crise Epiléptica

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/SEU_USERNAME/mvp-epileptic-seizure/blob/main/Notebook_Seizure_MVP.ipynb)

## 🎯 Objetivo
Este projeto tem como objetivo desenvolver um MVP (Minimum Viable Product) para detecção de crises epilépticas usando aprendizado de máquina.  
O modelo é treinado para classificar sinais cerebrais (EEG) como **"crise" (seizure)** ou **"não crise" (non-seizure)**, auxiliando na análise médica e no diagnóstico de epilepsia.

---

## 📊 Dataset Utilizado
- **Nome:** Epileptic Seizure Recognition  
- **Fonte:** [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Epileptic+Seizure+Recognition)  
- **Descrição:**  
  O dataset contém **11.500 amostras**, cada uma com **178 atributos** representando dados de EEG.  
  A coluna `y` (classe) indica:
  - `1` → Crise epiléptica (Seizure)
  - `2, 3, 4, 5` → Não crise (Normal ou outras atividades cerebrais)

No projeto, as classes 2 a 5 foram agrupadas como **"Não crise"**, resultando em um problema de **classificação binária**.

---

## 🧰 Tecnologias Usadas
- Python 3.10+
- Google Colab
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- TensorFlow/Keras (opcional, para CNN 1D)
- XGBoost

---

## 📂 Estrutura do Projeto
```
mvp-epileptic-seizure/
│
├── Notebook_Seizure_MVP.ipynb   # Notebook principal com código e relatório
├── README.md                     # Descrição do projeto
└── data/
    └── data.csv (opcional, ou download via notebook)
```

---

## 🚀 Como Rodar o Notebook

### 1. Executar direto no Google Colab
Clique no badge abaixo para abrir o notebook diretamente no Colab:  

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/SEU_USERNAME/mvp-epileptic-seizure/blob/main/Notebook_Seizure_MVP.ipynb)

Não é necessário instalar nada localmente.

---

### 2. Executar localmente (opcional)
**Passos:**
```bash
# Clonar repositório
git clone https://github.com/SEU_USERNAME/mvp-epileptic-seizure.git

# Entrar na pasta
cd mvp-epileptic-seizure

# Criar ambiente virtual
python -m venv venv
source venv/bin/activate   # Linux/Mac
venv\Scripts\activate    # Windows

# Instalar dependências
pip install -r requirements.txt

# Rodar Jupyter Notebook
jupyter notebook
```

---

## 📈 Resultados
- **Modelos testados:**
  - Regressão Logística (Baseline)
  - Random Forest
  - XGBoost
  - Rede Neural Convolucional 1D (opcional)

- **Métricas usadas:**
  - Acurácia
  - F1-Score
  - Matriz de Confusão

O melhor modelo encontrado foi o **XGBoost**, atingindo resultados consistentes na detecção de crises.

---

## 📝 Conclusões
O modelo conseguiu identificar padrões em sinais cerebrais e demonstrou potencial para auxiliar no diagnóstico de epilepsia.  
Com mais dados e otimização, este MVP pode ser expandido para um sistema robusto de suporte a decisões médicas.

---

## 📜 Licença
Este projeto está licenciado sob a [MIT License](LICENSE).

---

## 👨‍💻 Autor
- **Carlos Eduardo Silva dos Santos**
- Contato: [Seu LinkedIn ou Email]
