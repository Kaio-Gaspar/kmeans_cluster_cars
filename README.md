# Análise de Clusters para Carros Usados

Este projeto realiza uma análise de clusters em um conjunto de dados de carros usados, utilizando o algoritmo KMeans. O objetivo é segmentar os carros em diferentes grupos com base em características como preço, quilometragem, ano de fabricação e tipo de combustível. O projeto inclui o uso de técnicas de aprendizado de máquina e visualizações para entender os padrões de dados e tomar decisões informadas sobre o comportamento dos carros no mercado.

## Tecnologias Utilizadas

- Python
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn

## Descrição do Projeto

Este repositório contém um estudo de clustering, com o uso do algoritmo KMeans para segmentar carros usados com base em variáveis como:

- **Preço**: Preço do carro.
- **Km**: Quilometragem do carro.
- **Ano**: Ano de fabricação do carro.
- **Potência do motor**: Potência do motor (em HP).
- **Portas**: Número de portas do carro.
- **Kit GNV**: Se o carro possui kit de gás natural (GNV).

O projeto foi estruturado da seguinte forma:

1. **Pré-processamento de Dados**: Limpeza e preparação dos dados para análise, incluindo a transformação de variáveis categóricas em variáveis binárias (usando variáveis dummy).
2. **Modelagem de Clustering (KMeans)**: Aplicação do algoritmo KMeans para agrupar os carros em clusters e análise dos resultados.
3. **Análise dos Clusters**: Comparação das médias das variáveis para entender as diferenças entre os clusters.
4. **Validação do Modelo**: Uso do Método do Cotovelo para determinar o número ideal de clusters.
5. **Visualizações**: Criação de gráficos para representar as diferenças entre os clusters, como a distribuição do preço, quilometragem e outros.

## Objetivo

O objetivo principal deste projeto é identificar padrões ocultos no conjunto de dados de carros usados e entender como variáveis como preço, quilometragem, e ano de fabricação impactam os diferentes clusters. A segmentação dos dados pode ser útil para fins de marketing, precificação e outras análises no setor automobilístico.

## Como Executar

1. Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/analise-clusters-carros.git
