# Projeto de Classificação Íris

Este projeto foi desenvolvido como requisito da Semana de Imersão do curso *Machine Learning – Aula 1 (20221004)*.  
O objetivo é aplicar algoritmos de Machine Learning no clássico dataset **Íris**, avaliando diferentes técnicas de classificação multiclasse.

## 🔍 Etapas do Projeto
- **Análise Exploratória de Dados (EDA)**: inspeção do dataset, identificação de outliers e análise gráfica.
- **Engenharia de Features**: criação de uma variável *FLAG* para marcação de outliers.
- **Pré-processamento**: divisão em treino/teste, padronização das variáveis numéricas.
- **Modelagem**: aplicação de cinco algoritmos:
  - Regressão Logística
  - Árvore de Decisão
  - Random Forest
  - Naive Bayes
  - KNN
- **Avaliação dos Modelos**:
  - Métricas: Acurácia, F1-macro, Balanced Accuracy
  - Matrizes de confusão gráficas
  - Validação cruzada (5-folds)
- **Comparação com e sem FLAG**: análise do impacto da feature extra no desempenho.

## 📊 Principais Resultados
- **Random Forest** apresentou o melhor desempenho geral e maior robustez.
- A inclusão da FLAG de outliers não trouxe ganhos globais, mas:
  - Melhorou ligeiramente a Árvore de Decisão.
  - Reduziu o desempenho do Naive Bayes.
  - Não alterou significativamente Regressão Logística e KNN.

## 🚀 Como Executar
1. Clone este repositório:
   ```bash
   git clone https://github.com/seuusuario/Projeto-de-Classificacao-Iris.git
