**Detecção de Plantas Daninhas com Deep Learning – Protótipo para o LaserWeeder**

Este projeto apresenta um modelo de Deep Learning desenvolvido para identificar plantas daninhas em imagens, inspirado na aplicação do LaserWeeder na agricultura. O objetivo é demonstrar como técnicas de IA podem ser aplicadas para otimizar o controle de ervas daninhas em plantações, reduzindo custos e impactos ambientais.

**Descrição do Projeto**:
A agricultura de precisão está transformando o setor agroindustrial, e este projeto busca simular o funcionamento de um sistema automatizado para detectar plantas daninhas. Utilizando o dataset DeepWeeds, o modelo foi treinado para classificar imagens de diferentes espécies de plantas.

**O que está incluído no projeto?**
Um modelo de classificação de imagens baseado em TensorFlow/Keras.
Scripts para pré-processamento, treinamento e avaliação.
Interface interativa para predições em tempo real.
Visualizações e métricas de desempenho do modelo.
Dataset
O projeto utiliza o DeepWeeds Dataset, disponível no Kaggle. Este dataset contém imagens de diferentes espécies de plantas daninhas e plantas saudáveis, organizadas em classes, permitindo o treinamento e a avaliação do modelo.

**Estrutura dos Dados:**

Treinamento: Conjunto de imagens usado para treinar o modelo.

Validação: Imagens usadas para avaliar a precisão durante o treinamento.

Teste: Conjunto separado para avaliar a performance final do modelo.

Instalação e Requisitos

Pré-requisitos:

**Python 3.7 ou superior**
**Google Colab (recomendado para executar o projeto)**

**Bibliotecas necessárias:**
TensorFlow;
Keras;
NumPy;
Matplotlib;
Seaborn;
ipywidgets;
PIL

**Passos para execução**

Clone o repositório:

git clone: (https://github.com/BrunooPorto/LaserWeeder-Inteligencia-artificial.git)

**Abra o notebook no Google Colab clicando no botão:**
[![Abrir no Google Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/BrunooPorto/LaserWeeder-Inteligencia-artificial/blob/main/Prot%C3%B3tico_LaserWeeder_Inteligencia_artificial.ipynb)


**Certifique-se de carregar o modelo treinado (deepweeds_model.h5) no notebook para realizar predições.**

Resultados
O modelo alcançou uma precisão de 100% na detecção de plantas daninhas, com visualizações de métricas como a matriz de confusão e gráficos de curva ROC. Esses resultados demonstram a viabilidade de aplicar IA na agricultura.

Autor
Desenvolvido por Bruno Porto

💼 [LinkedIn](https://www.linkedin.com/in/brunoporto1/) 
