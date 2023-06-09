Este é um projeto de Ciência de Dados que tem como objetivo desenvolver um modelo de máquina preditiva para avaliar a
probabilidade de um cliente, ou um conjunto de clientes, deixarem o banco, o que é conhecido como 'churn'.

O projeto consiste em três macro-etapas:

* Análise exploratória dos dados, com extração de insights valiosos que podem serutilizados pelo time de negócios;
* Pré processamento dos dados, com codificação de variáveis catgóricas, balanceamento do dataframe e padronização dos dados;
* Modelagem de máquina preditiva, com análise de desempenho e otimização do algoritmo, de forma a obter um modelo
  final passível de ser implementado em produção (deploy do modelo).

Foram escolhidos os seguintes classificadores para a modelagem da máquina preditiva:
* Regressão Logística
* Random Forest
* XGBoost

A métrica principal para avaliação do desempenho dos modelos é o Recall (Revocação), pois a pretensão é de que se reduza ao
máximo a classificação de Falsos Negativos, ou seja, é preterível que um cliente que não tenha a pretensão de deixar o banco,
seja classificado como 'churn', do que um cliente iminente a deixar o banco seja classificado como 'não churn'.
