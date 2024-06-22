## Documentação do Código
## Importação de Bibliotecas:
Foram importadas as bibliotecas essenciais para análise de dados (pandas, numpy), manipulação de conjuntos de dados (train_test_split), construção de modelos de aprendizado de máquina (DecisionTreeClassifier para árvore de decisão e SVC para SVM), avaliação de modelos (accuracy_score, classification_report, confusion_matrix), e visualização (matplotlib.pyplot e seaborn).

## Carregamento dos Dados:
Os dados foram carregados diretamente do seu repositório no GitHub, que contém um arquivo CSV com informações sobre diabetes.

## Separação das Features e do Target:
As features foram separadas do target ('Outcome'), onde X contém todas as features e y contém a variável alvo.

## Divisão dos Dados em Conjuntos de Treinamento e Teste:
Os dados foram divididos aleatoriamente em conjuntos de treinamento e teste, usando 70% dos dados para treinamento e 30% para teste, garantindo reprodutibilidade com uma semente aleatória.

## Criação e Treinamento dos Modelos:
Foram criados e treinados dois modelos de classificação:

## Árvore de Decisão: 
Utilizado o DecisionTreeClassifier com configurações padrão.
SVM (Máquina de Vetores de Suporte): Utilizado SVC com kernel linear.

## Previsão e Avaliação dos Modelos:
Ambos os modelos foram avaliados utilizando métricas como acurácia, precisão, recall, F1-score e matriz de confusão para avaliar seu desempenho.

## Visualização da Árvore de Decisão:
A estrutura da árvore de decisão foi visualizada para entender como o modelo toma decisões baseadas nos atributos das features.

## Visualização da Matriz de Confusão com Seaborn:
Para o modelo SVM, a matriz de confusão foi plotada usando seaborn para uma representação visual mais clara das previsões corretas e incorretas.
