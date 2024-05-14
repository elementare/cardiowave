![MioCard (1)](https://github.com/elementare/cardiowave/assets/135054073/39e01939-f992-45da-9c9c-bcbabbb3096e)
# Previsão de Arritmia com Redes Neurais Convolucionais

## Lore
Dia 5 de maio de 1573, Na calma da noite estrelada de Iluminis, um murmúrio de preocupação se espalhava pelos corredores do palácio real. O Rei Milu Iluminarius MLVI, o soberano cuja luz guiava o reino, estava mergulhado em uma batalha silenciosa contra uma adversidade invisível.

EdnaEnsineide, a acadêmica aposentada, uma vez conselheira real de destaque, agora encontrava-se nas sombras do palácio, seus olhos cansados refletindo a angústia que assolava o reino. Ela sabia que algo estava errado com o Rei, algo que ia além das ameaças externas que o cercavam.

Os cientistas do reino, liderados por Edna e auxiliados pelo empresário misterioso João Gruta, haviam detectado os sinais perturbadores que emanavam do coração do Rei. As batidas descompassadas, os suspiros cansados, todos apontavam para uma aflição que nenhum deles ousava nomear, PODERIA SER A TERRIVEL ARRITIMIA CARDIACA!.

Enquanto isso, Klunk, o bárbaro meio-orc, estava decidido a fazer o que pudesse para ajudar seu Rei. Com sua lealdade inabalável e determinação feroz, ele permanecia ao lado do monarca, pronto para enfrentar qualquer desafio que se apresentasse.

Em uma noite silenciosa, enquanto as estrelas cintilavam no céu escuro, os cientistas do reino reuniram-se em um laboratório secreto, determinados a encontrar uma solução para a aflição do Rei. Usando seus conhecimentos em magia e ciência, eles criaram um artefato mágico capaz de ler os batimentos cardíacos do Rei com precisão incomparável.

O Coração de Cristal, como foi chamado, brilhava com uma luz suave e pulsante, refletindo a essência do coração do Rei. Com ele, os cientistas podiam observar os ritmos irregulares que assombravam o monarca, como as ondas inconstantes de um oceano agitado.

Enquanto o Rei Milu descansava, envolto pela luz suave do Coração de Cristal, os cientistas lançaram sua magia mais poderosa. Com um esforço conjunto, eles criaram uma rede neural encantada, capaz de prever as flutuações no ritmo cardíaco do Rei e antecipar os momentos de perigo.

E assim, através da união de magia e ciência, os sábios de Iluminis encontraram uma maneira de proteger seu Rei querido. Com o Coração de Cristal e a rede neural encantada, eles vigiariam os batimentos do coração do Rei, mantendo-o a salvo das sombras que o cercavam.

E embora a batalha contra a aflição do Rei estivesse longe de terminar, havia esperança no coração do povo de Iluminis. Pois, enquanto a luz do Coração de Cristal brilhasse, o Rei Milu continuaria a guiar seu reino com coragem e determinação, enfrentando os desafios que o destino lhes reservava.

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
