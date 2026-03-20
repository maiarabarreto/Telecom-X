# Análise de Churn - Telecom X

## Sobre o projeto

A empresa Telecom X tem enfrentado um problema de alto cancelamento por parte dos clientes. Esta é uma análise dos dados para entender fatores que levam à perda desses clientes.

## Dados Utilizados
Os dados representam informações de clientes, incluindo:
- Status de churn/evasão (variável alvo)
- Perfil demográfico
- Tempo de relacionamento com a empresa
- Serviços contratados
- Informações financeiras

Formato original:
JSON

##Principais Análises e Insights
- Churn e Contrato
Clientes com contrato Month-to-month apresentam maior taxa de evasão
Contratos de longo prazo (anual ou bienal) reduzem drasticamente a evasão
- Tempo de Contrato (Tenure)
Clientes novos são significativamente mais propensos a cancelar
- Análise de Correlação
Correlação negativa entre churn e:
Tempo de contrato, quantidade de serviços
Correlação positiva entre churn e cobrança mensal

## Tecnologias usadas
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white) 
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logo=plotly&logoColor=white) 
![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0?style=for-the-badge&logo=python&logoColor=white)
![Google Colab](https://img.shields.io/badge/Google_Colab-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=black)

## Como rodar o projeto
1. Abra o notebook TelecomX_BR.ipynb no Google Colab ou Jupyter Notebook.
2. Instale as bibliotecas necessárias (caso necessário): pip install pandas matplotlib seaborn
3. Execute as células na ordem para reproduzir toda a análise.

## Autor
Desenvolvido por Maiara Barreto
