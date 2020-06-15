# NaiveBayes-Classificacao
Aprendizado Supervisionado - Classificação usando o algoritmo Naïve Bayes

O objetivo do modelo é prever se o paciente terá risco futuro de desenvolver doenças coronárias. A variável alvo TenYearCHD (binária).

O conjunto de dados (dataset) contém 4238 observações e 16 variáveis (atributos). Os dados não estão balanceados entre as classes.

Etapas de desenvolvimento:

1-Análise exploratória / Pré-processamento;
2-O algoritmo Gaussian Naive Bayes apresentou acurácia de aproximadamente 80% (conjunto de teste). No entanto a taxa de precisão da classe 
com menor número de observações ficou em torno de 32% (muito ruim!);
3-Técnicas de balanceamento de classes (up-sample e down-sample);
4-Verificação de variáveis mais relevantes;
5-Eliminação de variáveis fortemente correlacionadas;
6-Nova versão do modelo (63% acurácia, com 63% para a classe 0 e 65% para a classe 1);
7-Uso do algoritmo Random Forest (85% de acurácia, com 86% para a classe 0 e 55% para a classe 1).

 
