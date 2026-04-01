# Modelagem de Dados K-Means de clientes de um shopping
**Este projeto apresenta um pipeline completo de análise de dados, abrangendo desde a ingestão e exploração inicial até as etapas de pré-processamento e preparação dos dados. Ao final, é aplicada a técnica de aprendizado não supervisionado K-Means para segmentação de clientes de um shopping, com o objetivo de identificar padrões de comportamento e gerar insights acionáveis.**

 Tecnologia | Versão | Propósito |
|-----------|--------|----------|
| ![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white) | 3.7+ | Linguagem principal |
| ![Pandas](https://img.shields.io/badge/Pandas-150458?logo=pandas&logoColor=white) | Latest | Manipulação de dados |
| ![NumPy](https://img.shields.io/badge/NumPy-013243?logo=numpy&logoColor=white) | Latest | Computação numérica |
| ![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?logo=matplotlib&logoColor=white) | Latest | Visualizações |
| ![Plotly Express](https://img.shields.io/badge/Plotly-Express-3F4F75?logo=plotly&logoColor=white) | Latest | Visualização Interativa|
| ![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0?logo=seaborn&logoColor=white) | Latest | Gráficos estatísticos |
| ![scikit-learn](https://img.shields.io/badge/scikit--learn-compatible-orange?logo=scikit-learn)| Latest| Implementação do K-Means|
| ![StandardScaler](https://img.shields.io/badge/Sklearn-StandardScaler-F7931E?logo=scikitlearn&logoColor=white) | Latest | Padronização de Dados|
| ![OneHotEncoder](https://img.shields.io/badge/Sklearn-OneHotEncoder-F7931E?logo=scikitlearn&logoColor=white) | Latest | Dumificação de dados Categóricos|

## As colunas da minha base são: 
* CostumerID - Identificado único atribuido a cada cliente
* Gender - Gênero do cliente
* Age - Idade do cliente
* Annual Income(K$) - Renda anual do cliente em milhares de dólares
* Spending Score(1 - 100) - Pontuação atribuida pelo shopping com base no comportamento e padrão de gastos do cliente

## O que foi feito:
1 - Feita a importação de todas as bibliotecas necessárias no projeto
 * Importação do CSV
 * Carregamento da base de dados (CSV)
2 - Pré-processamento de Dados:
   **Análise Exploratória Inicial (EDA)**
   * Inspeção dos tipos de dados e estrutura do dataset
   * Identificação de valores únicos por variável
   * Verificação de valores ausentes (missing values)
   * Padronização e renomeação de colunas para melhor legibilidade
  **Tratamento e Análise Exploratória**
   * Detecção de outliers utilizando estatísticas descritivas e visualizações
   * Análise univariada da variável categorica
   * Codificação de variáveis categóricas (dummificação)
   * Análise bivariada para identificação de relações entre variáveis
   **Preparação para Modelagem**
     * Construção de matriz de correlação
     * Padronização das variáveis numéricas (scaling)
 3 - Terceira Etapa do pré processamento de dados:
   * Plot de uma matriz de correlação para medir a correlação entre as variáveis
   * Padronização dos valores
  **Segmentação com 2 Clusters**:
   * Treinamento do modelo K-Means
   * Análise e interpretação dos centróides
   * Criação de labels (clusters)
   * Visualização dos clusters (matriz de dispersão)
   * Avaliação do modelo
  **Segmentação com 3 Clusters**
  * Treinamento do modelo K-Means
  * Análise e interpretação dos centróides
  * Criação de labels (clusters)
  * Visualização dos clusters (matriz de dispersão)
  * Avaliação comparativa dos resultados

## Como Rodar o projeto
1.  Clone o repositório em sua máquina:
 * git clone https://github.com/GrizzoHenrique/ModelagemKmeans
2. Acesse o diretório do projeto
 * cd ModelagemKmeans
3. Configure o ambiente:
 * Cerfique-se de ter o python instalado
 * Instale as dependências necessárias:
   pip install -r requirements.txt

