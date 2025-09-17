
# MVP - Classificação de Clientes em Alto e Baixo Valor

## Objetivo
O objetivo deste projeto é desenvolver um MVP de aprendizado de máquina para **classificação de clientes de uma loja online em alto e baixo valor**, com base no histórico de compras.  
A análise busca identificar padrões de comportamento de compra e prever quais clientes possuem maior potencial de gasto futuro, permitindo ações estratégicas para retenção e marketing.

---

## Dataset utilizado
- **Nome:** Online Retail II  
- **Fonte:** [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/online+retail+ii)  
- **Descrição:**  
  Conjunto de dados contendo transações de uma loja de varejo online, cobrindo os anos de 2010 e 2011.  
  Possui informações como:
  - InvoiceNo: número da fatura
  - StockCode: código do produto
  - Description: descrição do produto
  - Quantity: quantidade comprada
  - InvoiceDate: data da transação
  - UnitPrice: preço unitário
  - CustomerID: identificador do cliente
  - Country: país do cliente

---

## Tecnologias usadas
- **Linguagem:** Python  
- **Bibliotecas:**
  - pandas
  - numpy
  - matplotlib
  - seaborn
  - scikit-learn
  - xgboost
- **Plataforma:** Google Colab

---

## Como rodar o notebook
1. Baixe o dataset **OnlineRetailII.xlsx** do link oficial do UCI.  
2. Acesse [Google Colab](https://colab.research.google.com/).  
3. Abra o notebook `notebook_colab.ipynb` pelo GitHub ou faça upload direto.  
4. Execute as células na ordem apresentada:
   - Importação das bibliotecas
   - Carregamento dos dados
   - Limpeza e preparação
   - Engenharia de atributos
   - Treinamento e avaliação de modelos

---

## Conclusões
- O MVP conseguiu classificar clientes de alto e baixo valor com métricas satisfatórias (accuracy, precision, recall e F1-score).  
- Foram avaliados dois modelos principais: **Random Forest** e **XGBoost**, ambos apresentando bom desempenho.  
- Limitações:
  - As features utilizadas foram básicas (quantidade, número de faturas e total gasto).  
  - Futuras melhorias podem incluir variáveis de recência, frequência e categorias de produtos.
- O projeto demonstra a aplicação prática de aprendizado de máquina para problemas de negócio em dados reais.

---

## Estrutura do projeto
```
mvp-privacidade-cibernetica/
│
├── notebook_colab.ipynb   # Notebook completo com o MVP
├── README.md               # Documentação do projeto
└── OnlineRetailII.xlsx     # Dataset original (não incluído no repositório final, apenas link)
```
