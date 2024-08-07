# Formação em Dados
Aqui estão os cases e desafios que vou completando na minha especialização em dados pela escola DNC.
### Assuntos abordados:
    - Framework CRISP-DM
    - Bibliotecas Pandas, Numpy, SKlearn, Matplotlib, Seaborn
    - Data Cleaning e Data Wrangling (tratamento de nulos, outliers, feature engeneering, pipelines)
    - Modelos de machine learning como, regressão, clusteriazação, árvores de decisão entre outros são alguns dos modelos utilizados nesse repositório.

## Previsão do resultado de um e-commerce utilizando o Power BI
Neste desafio, tivemos que construir um painel gerencial para um e-commerce que almeja estudar as suas vendas e assim, traçar a melhor estratégia para alavancar seus
resultados. Recebemos duas bases de dados, uma com dados das vendas e outra com informações dos clientes. Com isso, foram criadas duas páginas para que os analistas possam
visualizar as seguintes métricas: quantidade total e valor total de vendas, contagem e valor total de vendas por data, quantidade e valor total por categoria e crie os filtros necessários para fornecer ao usuário a melhor experiência.

Conceitos utilizados: ETL, DAX, Segmentação de Dados, Gráficos de Colunas, Cartões.

## Dashboard com principais indicadores de desempenho de uma empresa de Marketing utilizando o Power BI
Nesse desafio, uma empresa de Marketing Digital precisava atingir uma meta ambiciosa e identificar os melhores planos de ação para alcançá-la. Para
isso, ela decidiu criar um dashboard no Power BI que permita acompanhar os principais indicadores de desempenho. Com esses dados, a equipe pode avaliar o
desempenho de cada campanha, identificando oportunidades de otimização e escolher os melhores planos de ação para alcançar a meta do quarter.

Conceitos utilizados: ETL, DAX, Filtros, Gráficos de Barras, Colunas, Linhas, Cartões, Mapas

## Modelo de Regressão Linear para empresa de Marketing
Nesse desafio tivemos que construir um modelo de regressão linear com base nos em uma base de dados de uma empresa de publicidade que buscava entender os melhores meios de venda de seus produtos através do investimento em determinados canais de comunicação como Facebook, Youtube, para a prospecção de leads para a empresa. A ideia era prever o retorno de vendas que pode ser gerado a partir de um determinado investimento em publicidade.

## Preparação de base de dados para uma empresa de e-commerce
Nesse desafio foram utilizados conceitos de Data Cleaning e Data Wrangling para realizar a estruturação e limpeza do dataset. O case consistia na utilização dos conceitos aprendidos em aula para realizar um levantamento dos indicadores de RFM em uma empresa de e-commmerce. A empresa forneceu sua base de dados com mais de 500.000 linhas sobre vendas realizadas em diversos países, e assim realizando o tratamento dos valores faltantes, outliers e soluções de agrupamento e agregação, foi possível chegar no cálculo do RFM para a companhia.

## Painel Gerencial de um E-commerce
Nesse case, desenvolvi um dashboard em Power BI para uma empresa de E-commerce que tinha como objetivo ser uma ferramenta centralizada que permitirá aos gestores visualizar e analisar informações chave sobre o desempenho do e-commerce. Por meio de gráficos, tabelas e filtros interativos, os gestores poderão monitorar as vendas, identificar tendências, tomar decisões estratégicas e acompanhar o crescimento do negócio.
Conceitos utilizados:
    - Figma (Design)
    - DAX(DIVIDE, SUMX, Colunas Calculadas)
    - Cartões
    - Gráficos de Barras com Nsuperiores
    - Gráfico de Linhas com análise preditiva para os próximos 3 meses
    - Gráfico de colunas e linhas.

## Predição de Churn
Nesse case, foi fornecido uma base de dados com mais de 7000 clientes com dados demográficos, de contrato e pagamento de uma empresa de Telefonia. O objetivo do negócio era prever para um cliente novo, se ele seria um churn ou não. Por meio do framework CRISP-DM, foi possível construir um modelo para a predição desejada pela empresa.
Conceitos Utilizados:
    - Data Cleaning (dropna, dropduplicates, removing outliers)
    - Data Wrangling (LabelEncoder, StandardScaler)
    - Pandas, Numpy, Matplotlib, Seaborn
    - LogisticRegression, RandomForest, DecisionTreeClassifier, SVM

## Predição de Churn em Plataforma de Streaming
Nesse desafio foi fornecida uma base de dados real de clientes de uma plataforma de streaming com mais de 30000 linhas. A diretoria está preocupada com o alto índice de usuários cancelando as suas assinaturas. Eles acreditam que é possível prever se um usuário tem mais chance de deixar a plataforma antes que isso aconteça, e com base nessa informação tomar ações para reduzir o churn. O objetivo é criar um modelo de classificação capaz de prever se um usuário tem mais chance de cancelar a sua assinatura na plataforma ou não. Para isso, a empresa forneceu uma base de dados em csv contendo dados sobre as contas dos clientes.
Conceitos e bibliotecas utilizadas:
    - EDA 
    - Data Cleaning (dropna, dropduplicates, fillna)
    - Data Wrangling (LabelEncoder, MinMaxScaler)
    - Pandas, Numpy, Matplotlib, Seaborn
    - LogisticRegression, RandomForest, GridSearchCV

## Predição do preço de seguro de vida
Nesse case foi dada uma base de dados com clientes de uma empresa de seguro com informações como o sexo, idade, se a pessoa é fumante ou não, a região onde a pessoa mora e o imc dela. O objetivo do case era prever o valor do seguro de vida para um potencial novo cliente. Foram utilizados conceitos de limpeza e estruturação dos dados, análise estatística descritiva e inferencial, as bibliotecas pandas, numpy, seaborn e skleran e também conceitos de otimização dos hiperparâmtros do modelo com maior R2 Score, que para o nosso case foi o RandomForestRegressor. Utilizamos o modelo GridSearch para buscar os melhores hiperparâmetros para o modelo vencedor.


## Agrupamento de perfis de clientes de um e-commerce
Nesse desafio foi fornecida uma base de dados de um e-commerce, no qual a empresa estava buscando entender melhor o comportamento de seus clientes para personalizar as suas campanhas de marketing.  Para isso, a empresa disponibilizou uma base de dados em csv contendo dados sobre clientes, produtos e transações da loja realizadas entre os anos de 2010 e 2011. Foram utilizados conceitos de data cleaning, data wrangling, estatística descritiva e as bibliotecas pandas, numpy, seaborn, sklearn e yellowbrick. O modelo escolhido para a clusterização foi o KMeans e assim encontramos 4 perfis bem distintos de clientes.

