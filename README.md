# Challenge Predicting Hotel Cancellations


Cenário
Você está apoiando um hotel com um projeto destinado a aumentar a receita de suas reservas de quartos. Eles acreditam que podem usar a ciência de dados para ajudá-los a reduzir o número de cancelamentos. 
O Desafio

Usar habilidades para produzir recomendações para o hotel sobre quais fatores contribui para que uma reserva seja atendida ou cancelada.

https://app.datacamp.com/learn/competitions/predict-hotel-cancellation
Solução

Utilizei da linguagem Python para o tratamento dos dados, esse foi o processo realizado. 

- Limpeza de Dados: Verificação de valores ausentes, duplicados e colunas irrelevantes. 
- Preparação de Dados: Codificação de variáveis categóricas, escala de variáveis numéricas e divisão dos dados em conjuntos de treinamento e teste. 
- Treinamento de Modelo: Treinamento de modelo de regressão logística no conjunto de treinamento. 
- Avaliação do Modelo: Avaliação de desempenho do modelo treinado no conjunto de teste usando precisão, recall, F1-score e ROC-AUC. 
- Interpretação do Modelo: Interpretação do modelo treinado para identificar as características mais importantes que contribuem para o cancelamento usando os coeficientes do modelo de regressão logística

Insights
1º Os clientes que precisam de uma vaga de estacionamento têm maior probabilidade de cancelar sua reserva. Isso pode ser devido a vários fatores, como disponibilidade limitada de vagas de estacionamento ou taxas mais altas de estacionamento.
2º Os clientes que reservam um determinado tipo de quarto têm maior probabilidade de cancelar a reserva. Isso pode indicar que os clientes têm preferências específicas por determinados tipos de quarto e podem ser mais propensos a cancelar se não conseguirem garantir o quarto que desejam.
3º Certos meses são mais ou menos propensos a cancelamentos, indicando que a sazonalidade pode desempenhar um papel no comportamento do cliente.

Recomendações gerais para o hotel:
Incentivar os clientes a fazerem solicitações especiais, já que número de solicitações especiais foi identificado como o preditor mais importante no modelo. 
Fornecer incentivos ou descontos para clientes recorrentes, já que os clientes recorrentes foi identificado como um importante preditor. 
Garantir que espaços de estacionamento adequados estejam disponíveis para os clientes que os necessitem, pois espaço de estacionamento solicitado foi identificado como um importante preditor.
Oferecer uma variedade de tipos de quartos aos clientes, pois tipo de quarto solicitado foi identificado como um importante preditor. 
Considerar o impacto do mês de chegada nas reservas, como o mês de chegada teve uma pontuação de importância relativamente alta de 1,070. 
Prestar atenção ao número de adultos e crianças em cada reserva, pois o número de crianças e o número de adultos foram identificados como preditores importantes.

Obrigado por ler até aqui ❤
Agradeço seu interesse e apoio!