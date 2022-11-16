# Data Mining - BI Master PUC-Rio

#### Professora: [Manoela Kohler](https://github.com/manoelakohler).
#### Monitor: [Felipe Borges](https://github.com/FelipeBorgesC).

## Scripts desenvolvidos com os alunos durante a disciplina de DM

### Índice
  
- [Análise Exploratória](#analise-exploratoria)
- [Pré processamento](#pre-processamento)
- [Classificação](#classificacao)
- [Associação](#associação)
- [Agrupamento](#agrupamento)
- [Regressão](#regressao)
- [Previsão de Séries Temporais](#series)

<h2 id="analise-exploratoria">
  
[Análise Exploratória](https://github.com/manoelakohler/DataMining/tree/main/01_An%C3%A1liseExplorat%C3%B3ria)
  
</h2>

  - **Mushrooms:** Entendimento e classificação de uma base de cogumelos [`mushrooms.ipynb`](https://github.com/manoelakohler/DataMining/blob/main/01_An%C3%A1liseExplorat%C3%B3ria/mushroom.ipynb). A base é composta por amostras de 23 espécies de cogumelos. Cada espécie é identificada como definitivamente comestível, definitivamente venenosa, ou de consumo desconhecido e não recomendado. Esta última classe foi combinada com a venenosa. O guia (de onde foram retiradas as características dos cogumelos) afirma claramente que não existe uma regra simples para determinar a comestibilidade de um cogumelo.
    - Gráficos analisados
      - Boxplots
      - Gráficos de dispersão
      - Gráficos de barras
      - Histogramas
      - entre outros
    - Inferência
      - Árvore de decisão (classificação)
      
  - **Iris:** Entendimento e classificação de uma base de flores [`iris.ipynb`](https://github.com/manoelakohler/DataMining/blob/main/01_An%C3%A1liseExplorat%C3%B3ria/iris.ipynb). Base com 150 registros, 4 atributos (largura e comprimento da pétala e da sépala) e 3 classes (setosa, virginica e versicolor). A ideia é fazer uma análise exploratória dos dados e posteriormente criar um classificador que consiga inferir a espécie de uma flor baseado nas dimensões da pétala e da sépala.
    - Gráficos analisados
      - Parallel Plot
      - Deviation Plot
      - Andrews Curves
      - Pie Plot
      - Boxplots
      - Gráficos de dispersão
      - Gráficos de barras
      - Histogramas
      - entre outros
    - Inferência
      - Árvore de decisão (classificação)


<h2 id="pre-processamento">
  
[Pré processamento](https://github.com/manoelakohler/DataMining/tree/main/02_Pr%C3%A9Processamento)
  
</h2>

  - **Secom:** Entendimento, pré processamento e classificação de uma base de um processo de fabricação de semi-condutores [`Secom.ipynb`](https://github.com/manoelakohler/DataMining/blob/main/02_Pr%C3%A9Processamento/Secom.ipynb). Um complexo processo de fabricação de semi-condutores moderno é normalmente feito sob vigilância consistente através do monitoramento de sinais, variáveis coletadas de sensores e pontos de medição de processo. No entanto, nem todos estes sinais são igualmente valiosos num sistema de monitoramento específico. Os sinais medidos contêm uma combinação de informações úteis, informações irrelevantes, bem como ruído. Engenheiros tipicamente têm um número muito maior de sinais do que são realmente necessários. Se considerarmos cada tipo de sinal como uma característica, então a seleção da característica pode ser aplicada para identificar os sinais mais relevantes. Os Engenheiros de Processo podem então usar estes sinais para determinar os fatores chave para o processo de produção. Isso poderá trazer benefícios para o processo, como redução do tempo e diminuição nos custos de produção.
  
    - Gráficos e medidas resumo para análise exploratória      
    - Pré processamento
      - Tratamento de missing
      - Remoção de atributos com variância zero
      - Balanceamento da base de dados
      - Normalização
      - PCA
    - Inferência
      - SVM (classificação)

<h2 id="classificacao">
  
[Classificação](https://github.com/manoelakohler/DataMining/tree/main/03_Classifica%C3%A7%C3%A3o)
  
</h2>

 - **Análise de Crédito Bancário:** Entendimento, pré processamento e classificação de uma base de análise de crédito [`Secom.ipynb`](https://github.com/manoelakohler/DataMining/blob/main/02_Pr%C3%A9Processamento/Secom.ipynb). A base de dados contém 2077 exemplos de créditos concedidos ou não. Possui 11 atributos de entrada e 2 classes de saída. A saída indica se o cliente pagou o empréstimo (=1) ou se não pagou (=0). 
 
    - Medidas resumo para análise exploratória      
    - Pré processamento
      - Normalização
    - Inferência (classificação)
      - SVM
      - Árvore de Decisão
      - Random Forest
    - Tuning de hiperparâmetros
      - GridSearch


 - **Câncer de Mama:** Entendimento, pré processamento e classificação de uma base de análise de crédito [`Credito_SVM.ipynb`](https://github.com/manoelakohler/DataMining/blob/main/03_Classifica%C3%A7%C3%A3o/Credito_SVM.ipynb), [`Credito_AD.ipynb`](https://github.com/manoelakohler/DataMining/blob/main/03_Classifica%C3%A7%C3%A3o/Credito_AD.ipynb) e [`Credito_RF.ipynb`](https://github.com/manoelakohler/DataMining/blob/main/03_Classifica%C3%A7%C3%A3o/Credito_RF.ipynb). Base de dados de características de tumores de mama, como raio, textura, perímetro e área do tumor, totalizando 30 atributos. A base consite em 569 registros de tumores (357 benignas e 212 malignas).
 
    - Medidas resumo para análise exploratória      
    - Pré processamento
      - Normalização
    - Inferência (classificação)
      - KNN
      - Regressão Logística
    - Tuning de hiperparâmetros
      - GridSearch
    - Pós procecssamento
      - Análise das confianças nas inferências para tornar a inferência mais conservadora, ou seja, evitar classificar um tumor maligno como benigno (o pior caso de erro).


<h2 id="associacao">
  
[Associação](https://github.com/manoelakohler/DataMining/tree/main/04_Associa%C3%A7%C3%A3o)
  
</h2>

 - **Transações em um mercado francês:** Entendimento, pré processamento e associação de itens de um mercado utilizando o algoritmo Apriori [`Market_Apriori.ipynb`](https://github.com/manoelakohler/DataMining/blob/main/04_Associa%C3%A7%C3%A3o/Market_Apriori.ipynb) e o FP-Growth [`Market_FPGrowth.ipynb`](https://github.com/manoelakohler/DataMining/blob/main/04_Associa%C3%A7%C3%A3o/Market_FPGrowth.ipynb). Lista de transações (compras) em um mercado francês: Cada linha da base é uma transação; Cada transação tem de 1 a N itens; Existem 119 produtos diferentes no mercado; Base tem 7501 transações feitas no decorrer de 1 semana.
 
    - Pré processamento
      - Transformação de transações em uma matriz esparsa
    - Inferência (classificação)
      - Apriori
      - FP-Growth
    - Pós processamento
      - Geração de regras a partir de conjuntos de itens frequentes

<h2 id="agrupamento">
  
[Agrupamento](https://github.com/manoelakohler/DataMining/tree/main/05_Agrupamento)
  
</h2>

- **Base artificial:** Visualização, análise utilizando K-Means [`Kmeans_Artificial.ipynb`](https://github.com/manoelakohler/DataMining/blob/main/05_Agrupamento/01_ArtificialData/Kmeans_Artificial.ipynb) e o método Hierarquico [`Hierarquico_Artificial.ipynb`](https://github.com/manoelakohler/DataMining/blob/main/05_Agrupamento/01_ArtificialData/Hierarquico_Artificial.ipynb). Base de dados artificial criada com o intuito de facilitar a visualização dos dados em 2D e os grupos formados. Nos scripts estão desenvolvidas as análises utilizando o algoritmo de agrupamento K-Means, através das métricas WCSS e Davies Bouldin, e o algoritmo Hierárquico.
 
    - Visualização da base de dados no plano 2D
    - Treinamento dos modelos
      - K-Means
      - Hierarquico
    - Avaliação dos tipos de métricas e escolha do número ótimo de clusters
      - Método do Cotovelo
      - Inversão de Sinal
      - Maior Distância Vertical

- **Clientes de um Shopping:** Visualização, análise das variáveis e definição dos grupos: K-Means [`Kmeans_Mall.ipynb`](https://github.com/manoelakohler/DataMining/blob/main/05_Agrupamento/02_MallCustomers/Kmeans_Mall.ipynb) e o método Hierarquico [`Hierarquico_Mall.ipynb`](https://github.com/manoelakohler/DataMining/blob/main/05_Agrupamento/02_MallCustomers/Hierarquico_Mall.ipynb). Base de dados de clientes de um shopping com as informações sobre ganho e consumo dos clientes. Nos scripts estão desenvolvidas as análises através dos algoritmos de agrupamento K-Means e Hierárquico.
 
    - Visualização da base de dados no plano 2D - Ganho vs Consumo
    - Treinamento dos modelos
      - K-Means
      - Hierarquico
    - Avaliação dos tipos de métricas e escolha do número ótimo de clusters
      - Método do Cotovelo
      - Inversão de Sinal
      - Maior Distância Vertical

- **Clusterização baseada em Densidade:** Visualização, análise das formas e regiões densas e aplicação do algoritmo DBSCAN [`DBscan.ipynb`](https://github.com/manoelakohler/DataMining/blob/main/05_Agrupamento/03_BIData/DBscan.ipynb). Base de dados artificial criada com o objetivo de exibir a dificuldade em definir a quantidade ideal de cluster para uma base de dados ruidosa e complexa. O objetivo é verificar o desempenho do algoritmo DBSCAN para conjuntos de dados menos comportados, de acordo com a definição de pontos densamente conectados.
 
    - Visualização da base de dados no plano 2D
    - Treinamento do modelo
      - DBSCAN
    - Avaliação do número ótimo de clusters
      - Definir a quantidade de clusters 
      - Encontrar a distância máxima ótima (*eps*)
      - Analisar resultado


<h2 id="regressao">
  
[Regressão](https://github.com/manoelakohler/DataMining/tree/main/06_Regress%C3%A3o)
  
</h2>

- **Regressão - Startups:** Entendimento, pré processamento e aplicar a regressão [`Startups_LR.ipynb`](https://github.com/manoelakohler/DataMining/blob/main/06_Regress%C3%A3o/01_Startups/Startups_LR.ipynb). Base de dados com informações diversas sobre Startups. Com cerca de 50 Startups com um total de 4 variáveis independentes: Gastos com P&D, Gastos administrativos, Gastos com marketing e o Estado; e 1 variável dependente (resposta): o Lucro. O case tem como objetivo criar um modelo capaz de prever o lucro baseado nessas 4 variáveis independentes para auxiliar os futuros investidores.
 
    - Tratar variáveis categóricas
    - Separar (Treino e Teste)
    - Normalizar
    - Treinamento do modelo
      - Regressão Linear
    - Avaliação diferentes métricas
    - Examinar retirada de variavéis independentes

- **Regressão - Aluguel de Bikes:** Entendimento, pré processamento e aplicar a regressão [`Bike_DT_RF.ipynb`](https://github.com/manoelakohler/DataMining/blob/main/06_Regress%C3%A3o/02_Bike/Bike_DT_RF.ipynb). Case sobre o tempo de uso de bicicletas. A base de dados conta com 9 variáveis independentes: Estação do ano, Feriado, Dia da semana, Dia de trabalho, Tempo Climático, Temperatura, Sensação Térmica, Humidade e Velocidade do vento; e tem como variável de resposta: Horas de uso. O exercício tem como objetivo estimar a quantidade de horas de uso de bike pelos seus clientes de acordo com essas 9 variáveis independentes.
 
    - Analisar a base de dados
    - Separar (Treino e Teste)
    - Treinamento do modelo
      - Árvore de Decisão
      - Random Forest
    - Avaliar resultados


<h2 id="series">
  
[Previsão de Séries Temporais](https://github.com/manoelakohler/DataMining/tree/main/07_Previs%C3%A3o_de_S%C3%A9ries_Temporais)
  
</h2>

- **Previsão de Séries Temporais - Aluguel de Bikes:** Entendimento, pré processamento e aplicar a Árvore de Decisão [`air_DT_solução.ipynb`](https://github.com/manoelakohler/DataMining/blob/main/07_Previs%C3%A3o_de_S%C3%A9ries_Temporais/air_DT_solu%C3%A7%C3%A3o.ipynb) e Random Forest [`air_RF_solução.ipynb`](https://github.com/manoelakohler/DataMining/blob/main/07_Previs%C3%A3o_de_S%C3%A9ries_Temporais/air_RF_solu%C3%A7%C3%A3o.ipynb). Estudo de caso sobre o número de passageiros de companhias aéreas. O objetivo do exercício é prever a quantidade de clientes ao longo do tempo.
 
    - Analisar a série temporal
    - Organização da série
      - Janelamento
      - Horizonte de previsão
    - Separar (Treino e Teste)
    - Treinamento do modelo
      - Árvore de Decisão
      - Random Forest
    - Avaliar resultados
