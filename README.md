# Projeto K-Means Pinguins - EBAC

## 🎯 Objetivo
Este projeto faz parte do curso de Data Science da EBAC e tem como objetivo aplicar o algoritmo de clustering não supervisionado K-Means para agrupar e segmentar diferentes espécies de pinguins com base em suas características biológicas e medições físicas.

## 🛠️ Tecnologias Utilizadas
- Python 3.x
- Pandas
- Scikit-learn (KMeans, StandardScaler)
- Seaborn, Matplotlib
- Plotly (Gráficos interativos)

## 📊 Metodologia
1. **Exploração e Limpeza dos Dados**: Identificação e remoção de valores nulos, além da exclusão de variáveis categóricas (`species`, `island`, `sex`) para focar exclusivamente nas características físicas quantitativas.
2. **Análise Descritiva Visual**: Geração de matrizes de dispersão com `pairplot` do Seaborn para analisar correlações e padrões visuais de agrupamento entre as variáveis físicas (comprimento e profundidade do bico, tamanho da barbatana e massa corporal).
3. **Pré-processamento**: Padronização dos dados numéricos utilizando o `StandardScaler` para que variáveis em escalas maiores (como o peso em gramas) não distorçam os cálculos de distância Euclidiana do algoritmo.
4. **Modelagem**: Implementação e treinamento do algoritmo K-Means configurado estrategicamente para a criação de 3 clusters distintos.
5. **Visualização dos Centroides e Clusters**: Plotagem interativa em 2D/3D utilizando a biblioteca Plotly para destacar a distribuição dos grupos e a localização exata de seus centroides.
