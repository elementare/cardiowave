![MioCard (1)](https://github.com/elementare/cardiowave/assets/135054073/39e01939-f992-45da-9c9c-bcbabbb3096e)
# Previsão de Arritmia com Redes Neurais Convolucionais

## Visão Geral
Bem-vindo ao repositório dedicado à previsão de arritmia utilizando redes neurais convolucionais (CNNs) treinadas com o Conjunto de Dados de Categorização de Batimentos Cardíacos por ECG! Este projeto visa desenvolver e avaliar modelos de CNN para prever a presença de arritmia em sinais de eletrocardiograma (ECG).

## Conjunto de Dados
O Conjunto de Dados de Categorização de Batimentos Cardíacos por ECG é a base deste projeto. Ele contém sinais de ECG pré-processados e segmentados, sendo adequado para treinar modelos de CNN para classificação de batimentos cardíacos.

## Origem do Conjunto de Dados
Nosso conjunto de dados foi derivado do PhysioNet, uma biblioteca de recursos de sinais fisiológicos. O PhysioNet fornece amostras de sinais de ECG com duração de 10 segundos para uma variedade de aplicações médicas e de pesquisa. No entanto, para nosso conjunto de dados específico, realizamos um reamostragem, extraindo apenas 1 segundo dos 10 segundos originais de batimentos cardíacos registrados. Essa abordagem nos permite criar um conjunto de dados mais compacto e focado, mantendo a representatividade dos batimentos cardíacos para análise de arritmias.

## Abordagem
Nossa abordagem consiste em treinar e avaliar modelos de CNN para classificar os sinais de ECG em diferentes categorias de batimentos cardíacos, incluindo arritmias. Vamos explorar diferentes arquiteturas de CNN, técnicas de pré-processamento de dados e estratégias de treinamento para obter o melhor desempenho na previsão de arritmia.

## Estrutura do Projeto

- `notebooks/`: Notebooks de exemplo demonstrando a preparação dos dados, treinamento dos modelos e avaliação dos resultados.
- `results/`: Resultados da avaliação dos modelos, incluindo métricas de desempenho e visualizações.


## Contribuindo
Contribuições para este projeto são bem-vindas! Se você tiver sugestões, melhorias ou gostaria de contribuir com novos modelos, abra um problema ou envie uma solicitação pull.
