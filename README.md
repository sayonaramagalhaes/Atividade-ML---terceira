# Atividade-ML---terceira
Repositório Terceira Atividade Machine Learning

Este repositório contém um exemplo básico de rede neural utilizando o PyTorch.
A rede é composta por duas camadas totalmente conectadas fully connected e usa a função de ativação ReLU. 
O código inclui a definição do modelo, a escolha de otimizadores e o treinamento, com a opção de comparar o desempenho de diferentes otimizadores.
O código utiliza dois otimizadores:
SGD e o Adam  e  o scheduler StepLR que tem como função, reduzir a taxa de aprendizado, ajudando a otimizar o treinamento.
O treinamneto pode ser utilizado a EWMA as médias exponenciais ponderadas, ao final é possível visualizar o gráfico de perda 
dos otimizadores ao longo das épocas do treinamento.

O código visualizar gradiente, traz o modelo simples de rede neural, usando o otimizador Adam, gerando gráficos que mostram como os gradientes evoluem durante o treinamento, em sua forma original e em uma escala adaptada.  
O código visualizações  gráficas, demonstra como diferentes schedulers de taxa de aprendizado afetam o processo de treinamento de um modelo simples, gerando a visualização  da  evolução da taxa de aprendizado ao longo das épocas para diferentes tipos de schedulers, através de gráficos.
