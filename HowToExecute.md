***Guia de Execução do Projeto: LaserWeeder com IA***

EEste guia explica como configurar e executar o LaserWeeder no Google Colab de forma simples, utilizando arquivos fornecidos no repositório.

**1. Execução Direta no Google Colab**

**Passo 1: Acesse o Notebook**

Clique no link abaixo para abrir o notebook no Google Colab:

👉 https://colab.research.google.com/github/BrunooPorto/LaserWeeder-Inteligencia-artificial/blob/main/Prot%C3%B3tico_LaserWeeder_Inteligencia_artificial.ipynb

**Passo 2: Baixe os Arquivos Necessários**

->Faça o download dos seguintes arquivos disponíveis no repositório:

->token.json: Credenciais para baixar o dataset automaticamente.

->deepweeds_model.h5: Modelo treinado para predições.

**Dica: O link para download está no GitHub.**

**Passo 3: Faça o Upload dos Arquivos**

->No Google Colab, localize as células que solicitam o upload dos arquivos necessários (token.json e deepweeds_model.h5).

->Carregue os arquivos baixados diretamente na interface do Colab.

**Caso o token.json esteja expirado, basta acessar o link dentro do colab e baixar o dataset no Kaggle.**

**Passo 4: Execute as Células do Notebook**

Siga a ordem das células no notebook, que já está configurado para:

->Fazer o download do dataset automaticamente usando o token.

->Realizar o treinamento, avaliação e teste do modelo.

->Executar predições com imagens de exemplo.

->Exibir métricas de desempenho e gráficos interativos.

->Teste a demonstração interativa para enviar suas próprias imagens e verificar as classificações realizadas pelo modelo.

**2. Recursos Disponíveis no Projeto**

**Treinamento e Avaliação do Modelo**

->Modelo Treinado: Baseado na arquitetura MobileNetV2, com técnicas de aumento de dados e ajuste fino.

**Avaliação:**

->Métricas como precisão, recall e F1-score.

->Matriz de confusão e curvas de aprendizado.

**Predição de Imagens**

->Faça upload de uma imagem para ver a classificação como planta daninha ou planta saudável.

**Visualizações**
->Gráficos interativos mostram o desempenho do modelo e os resultados das predições.

**3. Exemplos Práticos**

**Envio de Imagens:**

->Teste o modelo com imagens reais para verificar sua precisão e funcionamento.

**Análise de Métricas:**

->Explore as tabelas e gráficos disponíveis para entender o desempenho em diferentes classes.


**Com este guia, basta abrir o Google Colab e seguir as instruções no notebook para explorar o projeto e usá-lo facilmente!**
