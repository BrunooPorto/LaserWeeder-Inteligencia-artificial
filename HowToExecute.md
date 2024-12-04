Configuração do Ambiente:

Clone este repositório:
git clone https://github.com/BrunooPorto/LaserWeeder-Inteligencia-artificial.git

Instale as dependências:
pip install -r requirements.txt
  
Baixe o dataset DeepWeeds:
-Faça o download manualmente no Kaggle.
-Extraia os arquivos e organize-os na pasta DeepWeeds.

Execução
No Google Colab:
-Abra o notebook no Google Colab.
-Configure o caminho do dataset.
-Execute as células passo a passo para treinar, avaliar e testar o modelo.

Certifique-se de que o dataset está na pasta correta.
Execute o script principal:
Protótico_LaserWeeder_Inteligencia_artificial.ipynb

Recursos Disponíveis
1. Treinamento do Modelo
O modelo foi treinado em um conjunto de dados com 8 classes de plantas daninhas e possui:

Arquitetura: Baseada em MobileNetV2 para eficiência e precisão.
Técnicas aplicadas: Aumento de dados, normalização e ajuste fino.

2. Avaliação do Modelo:

Matriz de confusão.
Métricas de desempenho: precisão, recall, f1-score.
Curvas de aprendizado.

3. Demonstração Interativa:

Interface: Upload de imagens e predição ao vivo usando widgets.
Teste com imagens reais ou de exemplo para validar o modelo.

4. Gráficos:

Desempenho do modelo (precisão e perda).
Predições visuais com títulos interativos.

Exemplos de Uso:
1. Predição de Imagens
Envie imagens de teste para identificar se são plantas daninhas ou plantas saudáveis.

2. Visualização de Métricas
Veja a performance do modelo em diferentes classes através de gráficos e tabelas.

