# Análise de Churn - Telecom X

## Sobre o projeto

A empresa Telecom X tem enfrentado um problema de alto cancelamento por parte dos clientes. Esta é uma análise dos dados para entender fatores que levam à perda desses clientes.
Importei os dados que estavam em um json aninhados. Na fase de limpeza, notei que alguns campos da coluna Churn estavam vazios, assim substitui por Nan. Transformei a coluna total charges para float para poder trabalhar com números e os campos vazios também substitui por Nan. 
Com base nos gráficos gerados, notamos que menos da metade dos clientes estão cancelando os serviços com a Telecom X. Destes, não notamos diferença significativa entre idade, acima ou abaixo de 65 anos, ou gênero. É possível notar que clientes com menor tempo de contrato tem uma evasão maior. Clientes com contrato mês a mês tem evasão maior que aqueles com contrato de um ou dois anos. Clientes com gastos mensais maiores também tem maior evasão. E o método de pagamento com maior evasão é o cheque eletrônico. 
Com base nos dados e gráficos, podemos sugerir substituição do contrato mês a mês para contrato anual ou bianual. E também substituir a forma de pagamento de cheque eletrônico para cartão de crédito automático, que apresentou menor evasão.  

## Tecnologias usadas
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white) 
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logo=plotly&logoColor=white) 
![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0?style=for-the-badge&logo=python&logoColor=white)

![Google Colab](https://img.shields.io/badge/Google_Colab-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=black)

## Como rodar o projeto

## Autor
Desenvolvido por Maiara Barreto
