# Star Wars Data Visualization

Este repositório tem como principal foco realizar testes e explorar as diversas possibilidades de visualização de dados aplicadas ao universo Star Wars, utilizando técnicas atuais para análise dos personagens e elementos clássicos da saga. Através de visualizações modernas e interativas, esse projeto básico busca descobrir padrões, insights e conexões entre personagens, afiliações e eventos.

![imag_sw](https://github.com/user-attachments/assets/4795d20b-5dd2-45b8-bec8-e97fa07e29b5)

## Estrutura

A estrutura do projeto está organizada da seguinte forma atualmente:

- **data/**: Contém o dataset utilizado no projeto. O dataset é o `star_wars_universe_dataset.csv`, que inclui dados dos personagens, suas espécies, afiliações, e outros detalhes.
- **notebooks/**: Para explorar e analisar os dados, incluindo a criação de diferentes visualizações.
- **scripts/**: Scripts Python para manipulação de dados e criação de visualizações automatizadas.
- **visualizations/**: Contém imagens e arquivos gerados das visualizações criadas durante o projeto.
- **README.md**: Documentação do projeto.
- **requirements.txt**: Lista das dependências necessárias para executar o projeto.

## Visão Geral do Projeto

Este projeto utiliza um conjunto de dados simples do universo Star Wars para explorar as possibilidades de visualização, com o objetivo de proporcionar análise visual entre os personagens e suas relações. Simplesmente e resumidamente:

- Entender padrões e conexões entre personagens e suas afiliações.
- Analisar a distribuição de espécies e como os personagens foram introduzidos ao longo da saga.
- Visualizar a diversidade e a evolução dos elementos do universo Star Wars.

## Visualizações Criadas

Algumas as principais técnicas visualizações exploradas até o momento consiste em:

1. **Streamgraph**: Mostra a evolução da distribuição das espécies ao longo dos filmes.
2. **Chord Diagram**: Destaca as conexões entre espécies e afiliações.
3. **Bubble Chart**: Visualiza a distribuição dos personagens por afiliação e espécie.
4. **Network Graph**: Exibe a relação entre personagens e droides companheiros.
5. **Heatmap**: Mapeia a relação entre espécies e afiliações usando um mapa de calor.

## Estrutura do Repositório

A estrutura do repositório está organizada da seguinte forma:

- **data/**: Contém o dataset utilizado no projeto. O arquivo principal é o `star_wars_universe_dataset.csv`, que inclui informações dos personagens, suas espécies, afiliações, e outros detalhes relevantes.
- **notebooks/**: Notebooks do Jupyter usados para explorar e analisar os dados, incluindo a criação de diferentes visualizações.
- **scripts/**: Scripts Python para manipulação de dados e criação de visualizações automatizadas.
- **visualizations/**: Diretório contendo imagens e arquivos gerados das visualizações criadas durante o projeto.
- **README.md**: Documentação do projeto.
- **requirements.txt**: Lista das dependências necessárias para executar o projeto.

## Visão Geral do Projeto

Este projeto utiliza dados do universo Star Wars para explorar as possibilidades de visualização, com o objetivo de proporcionar uma análise rica e visual das interações entre os personagens, afiliações e eventos. Através de diferentes técnicas de visualização de dados, buscamos:

- Entender padrões e conexões entre personagens e suas afiliações.
- Analisar a distribuição de espécies e como os personagens foram introduzidos ao longo da saga.
- Visualizar a diversidade e a evolução dos elementos do universo Star Wars.

## Dataset

O dataset gerado contém dados fictícios dos personagens do universo Star Wars:

- **Name**: Nome do personagem. Exemplo: Luke Skywalker, Darth Vader.
- **Species**: Espécie do personagem, como Human, Droid, Wookiee, etc.
- **Homeworld**: Planeta natal do personagem. Exemplo: Tatooine, Alderaan, Coruscant.
- **Affiliation**: Afiliação do personagem, indicando com qual organização ou grupo ele está associado, como Rebel Alliance, Galactic Empire, Jedi Order, entre outros.
- **First Appearance**: Primeiro filme em que o personagem apareceu, por exemplo, *A New Hope*, *The Empire Strikes Back*, etc.
- **Mission Count**: Número de missões realizadas pelo personagem ao longo da saga.
- **Known Languages**: Número de idiomas conhecidos pelo personagem, útil para mostrar a diversidade cultural no universo Star Wars.

## Visualizações Criadas

Utilizamos várias técnicas modernas de visualização para explorar o dataset, incluindo:

1. **Streamgraph**: Mostra a evolução da distribuição das espécies ao longo dos filmes.
2. **Chord Diagram**: Destaca as conexões entre espécies e afiliações.
3. **Bubble Chart**: Visualiza a distribuição dos personagens por afiliação e espécie.
4. **Network Graph**: Exibe a relação entre personagens e droides companheiros.
5. **Heatmap**: Mapeia a relação entre espécies e afiliações usando um mapa de calor.

Estas e outras visualizações ajudam a entender melhor o universo Star Wars e destacam padrões e relações entre os personagens e suas características.

## Como Utilizar

### Pré-requisitos

Certifique-se de ter instalado o Python 3.7+ e as bibliotecas necessárias. Para instalar todas as dependências, utilize o comando abaixo:

```sh
pip install -r requirements.txt
```

### Executando as Análises no Google Colab

1. **Clone o repositório**:

   ```sh
   git clone https://github.com/nathadriele/star-wars-data-visualization.git
   ```

2. **Navegue até o Google Colab** e faça o upload do notebook desejado, que pode ser localizado na pasta `notebooks/` do repositório.

3. **Carregue o dataset**: Faça o upload do arquivo `star_wars_universe_dataset.csv`, que está na pasta `data/`, para o ambiente do Google Colab.

4. **Execute as células do notebook** para explorar os dados e gerar as visualizações.
