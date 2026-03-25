# Projeto referente ao módulo 33 do curso de ciência de dados da EBAC
**Neste projeto é feito todo o processo de uma análise completa de dados desde o seu carregamento passando por todas a fases de pré-processamento de dados
até a aplicação do algoritimo de aprendizado não supervisionado k-means em uma base de clientes de um shopping**

## As colunas da minha base são: 
* CostumerID - Identificado único atribuido a cada cliente
* Gender - Gênero do cliente
* Age - Idade do cliente
* Annual Income(K$) - Renda anual do cliente em milhares de dólares
* Spending Score(1 - 100) - Pontuação atribuida pelo shopping com base no comportamento e padrão de gastos do cliente

## O que foi feito:
* Feita a importação de todas as bibliotecas necessárias no projeto
* Importação do CSV
* Primeira Etapa do pré-processamento de dados:
  * Verificação de tipos de dados
  * Verificação de valores únicos 
  * Verificação de valores nulos ou faltantes
  * Verificação de valores unicos presentes em cada coluna
  * Renomeação de colunas para facilitar o tratamento posterior
* Segunda Etapa do pré-processamento de dados:
  * Verificação de outliers com o describe() e também com gráficos
  * Análise univariada da variável categorica
  * Dumificação das variáveis e criação de um dataframe
  * Análise Bivariada
* Terceira Etapa do pré processamento de dados:
  * Plot de uma matriz de correlação para medir a correlação entre as variáveis
  * Padronização dos valores
* Aplicação do algoritimo de Aprendizado não supervisionado k-means utilizando dois clusters:
  * Criação dos Centroides
  * Verificação do formato dos centroides
  * Construção da matriz de dispersão
    * Revertendo a padronização dos centroides
    * Criando as Etiquetas
    * Plotando a matriz de dispersão
    * Avaliando o modelo
* Aplicação do algoritimo de Aprendizado não supervisionado k-means utilizando três clusters:
  * Criação dos Centroides
  * Verificação do formato dos centroides
  * Construção da matriz de dispersão
    * Revertendo a padronização dos centroides
    * Criando as Etiquetas
    * Plotando a matriz de dispersão
    * Avaliando o modelo
## Como Rodar o projeto
* Clone o repositório em sua máquina
* Abra o arquivo Profissao Cientista de Dados M33 A1 Pratique em um ambiente python
* Execute o código celula por celula

## Tecnologias utilizadas:
![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python&logoColor=white)
![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter&logoColor=white)

![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas&logoColor=white)

![Plotly Express](https://img.shields.io/badge/Plotly-Express-3F4F75?logo=plotly&logoColor=white)
![Plotly Graph Objects](https://img.shields.io/badge/Plotly-Graph%20Objects-3F4F75?logo=plotly&logoColor=white)

![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-11557C)
![Seaborn](https://img.shields.io/badge/Seaborn-Statistical%20Plots-4C72B0)

![StandardScaler](https://img.shields.io/badge/Sklearn-StandardScaler-F7931E?logo=scikitlearn&logoColor=white)
![KMeans](https://img.shields.io/badge/Sklearn-KMeans-F7931E?logo=scikitlearn&logoColor=white)
![OneHotEncoder](https://img.shields.io/badge/Sklearn-OneHotEncoder-F7931E?logo=scikitlearn&logoColor=white)
