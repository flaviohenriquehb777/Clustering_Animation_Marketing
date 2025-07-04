# Segmentação de Clientes para Marketing com K-Means

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

Este projeto utiliza o algoritmo de K-Means para realizar a segmentação de clientes em grupos distintos, com o objetivo de otimizar campanhas de marketing. A segmentação foi feita com base em dados sintéticos representando diferentes tipos de clientes. A visualização do processo de clusterização é apresentada por meio de animações criadas com Matplotlib.

## 🚀 Demonstração

Veja a animação do processo de segmentação de clientes:

<p align="center">
  <img src="media/animacao_clientes_loop.gif" alt="Animação de Segmentação de Clientes" width="700"/>
</p>

## 🎯 Objetivo

O objetivo principal deste projeto é demonstrar como a segmentação de clientes pode ser feita utilizando técnicas de Machine Learning. O K-Means foi utilizado para agrupar os clientes em 4 clusters, cada um representando um tipo de cliente com base em seu comportamento ou características.

## 💻 Tecnologias Utilizadas

* **Python**: Linguagem de programação utilizada para o desenvolvimento do projeto.
* **NumPy**: Biblioteca para manipulação de dados numéricos e criação dos dados sintéticos.
* **Matplotlib**: Utilizada para criar as visualizações e animações.
* **Scikit-Learn**: Biblioteca para implementar o algoritmo de K-Means e realizar a clusterização.
* **IPython Display**: Para exibir o vídeo da animação dentro de notebooks.
* **Pillow (via Matplotlib backend)**: Utilizado para o salvamento da animação em formato de vídeo.
* **FFmpeg**: Ferramenta externa (geralmente necessária no sistema) para o Matplotlib salvar vídeos MP4.

## ⚙️ Como Funciona

1.  **Geração de Dados Sintéticos**: São gerados dados aleatórios representando 4 grupos de clientes com diferentes características.
2.  **Clusterização com K-Means**: O algoritmo de K-Means é utilizado para agrupar os dados em 4 clusters, cada um representando um tipo de cliente:
    * `client_sport`
    * `client_toys`
    * `client_clothes`
    * `client_tech`
3.  **Animação do Processo**: O processo de segmentação é animado para mostrar como os pontos dos dados são agrupados ao longo do tempo.
4.  **Visualização e Salvamento**: A animação final é salva como um vídeo `.mp4` e pode ser visualizada diretamente no notebook ou em qualquer reprodutor de vídeo.

## 🚀 Como Executar

Para rodar este projeto em seu ambiente local, siga os passos abaixo:

1.  **Clone o repositório**:

    ```bash
    git clone [https://github.com/SeuNomeDeUsuario/Segmentacao_clientes_marketing.git](https://github.com/SeuNomeDeUsuario/Segmentacao_clientes_marketing.git)
    cd Segmentacao_clientes_marketing
    ```

2.  **Instalar as dependências**:
    Certifique-se de ter as bibliotecas necessárias instaladas. Recomenda-se criar um ambiente virtual.

    ```bash
    python -m venv venv
    source venv/bin/activate  # No Windows, use `venv\Scripts\activate`
    pip install -r requirements.txt
    ```
    * **Importante:** Para salvar a animação como MP4, você também precisará ter o `ffmpeg` instalado no seu sistema operacional e acessível via PATH. Você pode baixá-lo do site oficial do FFmpeg.

3.  **Rodar o Código**:
    O código principal para a geração da animação está no arquivo `Segmentacao_clientes_marketing.ipynb` na raiz do projeto (ou dentro de uma pasta `notebooks` se você mover). Você pode executá-lo em um ambiente Jupyter Notebook ou Jupyter Lab:

    ```bash
    jupyter notebook Segmentacao_clientes_marketing.ipynb
    ```

    Após a execução do notebook, o vídeo da animação será salvo na pasta `media/`.

## 🤝 Contribuições

Contribuições são bem-vindas! Se você tiver ideias para melhorias, novas funcionalidades ou encontrar algum problema, sinta-se à vontade para abrir uma *issue* ou enviar um *pull request*.

## 📄 Licença

Este projeto está licenciado sob a Licença MIT - veja o arquivo [LICENSE](LICENSE) para mais detalhes.

## 📧 Contato

Se você tiver alguma dúvida ou sugestão, entre em contato:

* **Nome**: Flávio Henrique Barbosa
* **LinkedIn**: [Flávio Henrique Barbosa | LinkedIn](https://www.linkedin.com/in/fl%C3%A1vio-henrique-barbosa-38465938)
* **Email**: flaviohenriquehb777@outlook.com

---
