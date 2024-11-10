# Exploração, Análise e Visualização de Dados: Star Wars

Este projeto básico é dedicado à exploração e análise visual do universo Star Wars, utilizando técnicas atuais de visualização de dados para examinar personagens, espécies, afiliações e eventos que compõem esta incrivel saga.

O principal objetivo é criar um ambiente interativo que permita explorar diferentes tipos de visualizações, para entender padrões, descobrir insights ocultos e analisar conexões complexas entre os elementos do universo de Star Wars, utilizando uma ampla variedade de visualizações modernas — como gráficos hierárquicos, diagramas de rede e visualizações temporais —, este simples projeto visa ilustrar as relações dinâmicas e evolutivas dos personagens e suas respectivas afiliações, oferecendo uma perspectiva interessante sobre a narrativa. 

Este repositório exemplifica como técnicas de visualização de dados podem ser aplicadas de forma prática, transformando números em narrativas visuais interessantes.

![imag_sw](https://github.com/user-attachments/assets/4795d20b-5dd2-45b8-bec8-e97fa07e29b5)

## Dataset SW

O dataset gerado contém dados fictícios dos personagens e relações do universo Star Wars:

![image](https://github.com/user-attachments/assets/2aaedfbc-7094-4c1c-a764-dc6e047adc70)

## Estrutura Básica

A estrutura do projeto está organizada da seguinte forma atualmente:

- **data/**: Contém o dataset utilizado no projeto. O dataset é o `star_wars_universe_dataset.csv`, que inclui dados dos personagens, suas espécies, afiliações, e outros detalhes.
- **notebooks/**: Para explorar e analisar os dados, incluindo a criação de diferentes visualizações.
- **scripts/**: Scripts Python para manipulação de dados e criação de visualizações automatizadas.
- **visualizations/**: Contém imagens e arquivos gerados das visualizações criadas durante o projeto.
- **README.md**: Documentação do projeto.
- **requirements.txt**: Lista das dependências necessárias para executar o projeto.

## Exploração Visual e Análise de Dados

Atualmente, as principais visualizações exploradas consiste em:

1. Boxplot - Comparação do Número de Missões por Afiliação
Representa a distribuição do número de missões realizadas pelos personagens, categorizadas por suas afiliações. O boxplot destaca a mediana, quartis, e possíveis valores atípicos, ajudando a identificar padrões de variação nas missões por afiliação.

2. Histogram with KDE - Histogramas com Estimativa de Densidade Kernel
Combina um histograma e uma curva suave de densidade para mostrar a distribuição dos personagens de acordo com um atributo específico, proporcionando insights sobre a densidade e a distribuição dos dados.

3. Treemap - Composição Hierárquica de Espécies por Afiliação
Exibe uma visualização hierárquica das espécies dentro de cada afiliação. Cada retângulo representa uma espécie, e o tamanho reflete o número de personagens daquela espécie em uma determinada afiliação.

4. Swarm Plot - Distribuição de Personagens por Espécie e Afiliação
Mostra a distribuição de personagens por espécie e afiliação, distribuindo cada ponto para evitar sobreposição. Essa visualização permite ver tanto o número de personagens quanto sua dispersão em relação às diferentes afiliações.

5. Heatmap - Relação entre Espécies e Afiliações
Representa a relação entre espécies e afiliações por meio de uma matriz de calor. As cores indicam a intensidade da relação, permitindo identificar afiliações com uma concentração maior ou menor de personagens de cada espécie.

6. Pairplot - Relação entre Atributos Numéricos
Cria múltiplos gráficos de dispersão para comparar todos os atributos numéricos entre si. Isso ajuda a detectar correlações, tendências e padrões entre diferentes atributos dos personagens.

7. Sunburst Chart - Relação Hierárquica Entre Personagens, Espécies e Afiliações
Oferece uma visão hierárquica dos personagens em relação a suas espécies e afiliações, mostrando a contribuição de cada camada hierárquica de forma concêntrica.

8. Circular Packing Chart - Representação de Hierarquias de Personagens por Afiliação e Espécie
Representa a hierarquia dos personagens, espécies e afiliações em círculos aninhados. Cada círculo representa uma afiliação ou espécie, proporcionando uma visualização compacta das hierarquias envolvidas.

9. Sankey Diagram - Fluxo entre Espécies e Afiliações
Destaca o fluxo entre diferentes espécies e suas afiliações, mostrando como os personagens se movem entre diferentes facções ou afiliações e destacando os principais grupos.

10. Network Graph - Relações Entre Personagens e Droides Companheiros
Representa as relações de proximidade entre personagens e seus droides companheiros, destacando conexões importantes, formando uma rede que ajuda a identificar relacionamentos complexos.

11. Parallel Coordinates Plot - Comparação Entre Atributos dos Personagens
Mostra a comparação de múltiplos atributos dos personagens em uma visualização única, onde cada linha representa um personagem e atravessa diferentes eixos que representam atributos.

12. Bubble Chart - Comparação de Afiliação e Espécie Usando o Tamanho das Bolhas
Compara as afiliações e espécies dos personagens, representando a quantidade de personagens por meio do tamanho das bolhas, facilitando a análise do tamanho relativo de cada grupo.

13. Violin Plot - Distribuição de Conhecimento de Línguas por Afiliação
Mostra a distribuição do número de idiomas conhecidos pelos personagens de cada afiliação, proporcionando uma visão detalhada da densidade e variabilidade desses atributos.

14. Stacked Bar Chart - Comparação Entre Espécies e Atributos Numéricos
Exibe comparações entre diferentes espécies e seus atributos, destacando as contribuições de cada atributo empilhadas em uma única barra para facilitar a análise de proporção.

15. Donut Chart - Distribuição de Espécies
É uma variação do gráfico de pizza e visualiza a proporção dos personagens de diferentes espécies de uma maneira clara e atraente, com uma abertura no centro.

16. Horizontal Bar Chart - Número de Personagens por Afiliação
Um gráfico de barras horizontal que mostra o número de personagens por afiliação, facilitando a comparação visual entre as afiliações.

17. Trellis Chart (FacetGrid) - Relação Entre Número de Missões e Conhecimento de Línguas por Afiliação
Mostra múltiplos gráficos menores para comparar o número de missões e idiomas conhecidos por afiliação, proporcionando uma visão comparativa detalhada.

18. Lollipop Chart - Comparação do Número de Personagens por Espécie
Representa o número de personagens por espécie, com linhas conectando cada espécie ao valor correspondente, lembrando o formato de um pirulito, o que facilita a análise dos valores.

19. Marimekko Chart - Relação Entre Espécie e Afiliação
Mostra a proporção de personagens por espécie e afiliação, usando largura e altura para representar duas dimensões simultaneamente.

20. Funnel Chart - Introdução dos Personagens ao Longo dos Filmes
Permite visualizar o número de personagens introduzidos ao longo dos filmes da saga, representando a diminuição ou aumento da introdução de personagens ao longo do tempo.

21. Density Contour Plot - Visualizar Concentração de Atributos
Exibe a concentração dos atributos em uma visualização de contorno, destacando regiões de alta densidade nos dados.

22. Correlograma (Correlation Matrix Plot) - Análise de Correlação Entre Atributos
Apresenta a correlação entre os atributos numéricos, permitindo identificar relações fortes ou fracas entre variáveis, destacando visualmente as correlações positivas e negativas.

23. Dumbbell Plot - Comparação do Número de Personagens por Espécie Entre Dois Grupos
O dumbbell plot compara a quantidade de personagens entre dois grupos, destacando as diferenças de uma maneira visual clara e objetiva.

24. Radial Bar Chart - Comparação dos Atributos dos Personagens
É uma variação do gráfico de barras que organiza as barras de forma radial, facilitando a visualização de múltiplos atributos dos personagens em um formato circular.

25. Streamgraph - Evolução da Distribuição de Espécies ao Longo dos Filmes
Destaca a evolução da distribuição das espécies ao longo dos filmes, mostrando como as proporções das espécies mudam ao longo do tempo.

26. Icicle Chart - Análise de Hierarquia de Atributos do Universo Star Wars
É usado para analisar hierarquias dentro do universo Star Wars, representando a relação entre atributos de forma hierárquica em uma estrutura descendente.

27. Chord Diagram 3D - Visualização de Conexões em Três Dimensões Entre Espécies, Afiliações e Planetas
Representa uma versão tridimensional do diagrama de cordas, usado para visualizar as conexões complexas entre espécies, afiliações e planetas.

28. Cluster Dendrogram - Agrupamento dos Personagens com Base nos Atributos
Agrupa personagens com base em seus atributos, mostrando as similaridades entre os personagens em uma estrutura de árvore hierárquica.

29. Matrix Plot (Matriz de Bolhas) - Relação de Personagens, Espécies e Afiliações
Representa a relação entre espécies e afiliações, variando o tamanho das bolhas para indicar a contagem de personagens.

30. 3D Scatter Plot - Análise dos Atributos dos Personagens em um Gráfico Tridimensional
Mostra uma análise dos atributos dos personagens em três dimensões, proporcionando uma visualização interativa e detalhada dos atributos numé.

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
