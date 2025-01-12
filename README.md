# Atividade-ML---terceirad
Repositório Terceira Atividade Machine Learning

Este repositório contém um exemplo básico de rede neural utilizando o PyTorch.
A rede é composta por duas camadas totalmente conectadas (fully connected) e usa a função de ativação ReLU. 
O código inclui a definição do modelo, a escolha de otimizadores e o treinamento, com a opção de comparar o desempenho de diferentes otimizadores.
O código utiliza dois otimizadores:
SGD e o Adam  e  scheduler `StepLR`que tem como função reduzir  a taxa de aprendizado, ajudando a otimizar o treinamento.
O treinamneto pode ser utilizado a EWMA as médias exponenciais ponderadas, ao final é poosivel visualizar o gráfico de perda 
dos otimizadores ao longo das épocas do teinamento.

 Já o código visualizar gradientes, raz um modelo de redes adaptado para que os graficos de 
