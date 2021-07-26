# Data Mining - BI Master PUC-Rio
## Scripts desenvolvidos durante a disciplina de DM

### Índice
  
- [Análise Exploratória](#analise-exploratoria)
- [Pré processamento](#pre-processamento)
- [Classificação](#classificacao)
- [Associação](#associação)

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



