
# MVP - Privacidade e Segurança Cibernética

## Objetivo
Este projeto tem como objetivo desenvolver um MVP (Minimum Viable Product) para aplicar técnicas de aprendizado de máquina 
em um problema de classificação utilizando o dataset **Online Retail II**. 
O foco está em boas práticas de privacidade e segurança cibernética, garantindo reprodutibilidade e documentação clara.

## Dataset Utilizado
O dataset original utilizado neste projeto é o **Online Retail II**, disponível publicamente no UCI Machine Learning Repository.  
Devido ao tamanho do arquivo original, foi incluída neste repositório **uma versão reduzida** contendo apenas 10.000 registros 
para fins de demonstração e para respeitar o limite de upload do GitHub.

- **Download do dataset original (UCI):**
  [https://archive.ics.uci.edu/ml/datasets/online+retail+ii](https://archive.ics.uci.edu/ml/datasets/online+retail+ii)

- **Arquivo reduzido disponível neste repositório:**
  `OnlineRetailII_small.xlsx`

> **Observação:**
> O arquivo reduzido mantém a estrutura original do dataset e permite a execução completa do notebook, porém não representa a totalidade dos dados.

## Tecnologias Usadas
- Python 3.x
- Google Colab
- Pandas
- NumPy
- Scikit-learn
- Matplotlib / Seaborn

## Como Rodar o Notebook
1. Faça o download do arquivo `OnlineRetailII_small.xlsx` deste repositório.
2. Abra o Google Colab: [https://colab.research.google.com/](https://colab.research.google.com/)
3. Faça o upload do notebook `notebook_colab.ipynb`.
4. Execute as células em ordem, garantindo que o arquivo do dataset esteja no mesmo diretório do notebook.

## Conclusões
Este projeto demonstrou o processo completo de preparação, modelagem e avaliação de dados em um cenário de aprendizado de máquina. 
Com a aplicação de boas práticas, foi possível criar uma solução reprodutível e documentada, utilizando uma amostra de dados para 
viabilizar a publicação no GitHub e facilitar a execução do MVP por qualquer usuário.
