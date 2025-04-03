# Segmentação de Clientes para Marketing com K-Means 

<br>Este projeto utiliza o algoritmo de K-Means para realizar a segmentação de clientes em grupos distintos, com o objetivo de otimizar campanhas de marketing. A segmentação foi feita com base em dados sintéticos representando diferentes tipos de clientes. A visualização do processo de clusterização é apresentada por meio de animações criadas com Matplotlib.<br><br>

## Objetivo

O objetivo principal deste projeto é demonstrar como a segmentação de clientes pode ser feita utilizando técnicas de Machine Learning. O K-Means foi utilizado para agrupar os clientes em 4 clusters, cada um representando um tipo de cliente com base em seu comportamento ou características.

## Tecnologias Utilizadas

- Python: Linguagem de programação utilizada para o desenvolvimento do projeto.
- NumPy: Biblioteca para manipulação de dados numéricos e criação dos dados sintéticos.
- Matplotlib: Utilizada para criar as visualizações e animações.
- Scikit-Learn: Biblioteca para implementar o algoritmo de K-Means e realizar a clusterização.
- IPython Display: Para exibir o vídeo da animação dentro de notebooks.

## Como Funciona

1. **Geração de Dados Sintéticos:** São gerados dados aleatórios representando 4 grupos de clientes com diferentes características.

2. **Clusterização com K-Means:** O algoritmo de K-Means é utilizado para agrupar os dados em 4 clusters, cada um representando um tipo de cliente:

- client_sport
- client_toys
- client_clothes
- client_tech

3. **Animação:** O processo de segmentação é animado para mostrar como os pontos dos dados são agrupados ao longo do tempo.

4. **Visualização:** A animação final é salva como um vídeo .mp4 e pode ser visualizada diretamente no notebook ou em qualquer reprodutor de vídeo.
