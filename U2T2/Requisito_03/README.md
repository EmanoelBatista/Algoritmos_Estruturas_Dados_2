# Requisitos 3

## Objetivo
- Reproduzir a tabela disponibilizada no [documento do trabalho](https://github.com/ivanovitchm/datastructure/blob/main/lessons/week_09/U2T2.pdf)
- Implementar a tabela no formato markdown juntamente com a interpretação dos resultados cuja o texto deverá ter entre 500 a 1000 palavras.
 
### Tabela 
- A tabela foi criada com base nesta [análise](https://github.com/EmanoelBatista/Algoritmos_Estruturas_Dados_2/blob/main/U2T2/Requisito_03/requisitos_03.ipynb).

|                 | Quantidade de vértices | Quantidade de arestas | Degree Assortativity Coefficient | Quantidade de componentes conectados | Tamanho do Componente Gigante (GCC) | Coeficiente de Clustering |
|---------------------|-------------------------|-----------------------|----------------------------------|-------------------------------------|-----------------------------------|---------------------------|
| com-Youtube              |      1134890      |     2987624     |          -0.028332126333519572           |           1134890             |          1             |       0.04040113888093932       |
| ca-AstroPh              | 18772           | 396160         | 0.20518714346398922                    | 290                       | 17903                     | 0.6305932411707943             |
| web-Google              | 875713           | 5105039         | -0.06520019402435487                   | 371764                      | 434818                      | 0.3698306814797672             |
| loc-Gowalla              | 196591           | 1900654         | -0.02925474163485361                    | 1                      | 196591                      | 0.23672372971033598             |
| sx-askubuntu              | 159316           | 596933         | -0.10278842628952252                    | 97174                       | 59813                      | 0.07696177166103574             |

## Interpretação dos resultados
- Nesta atividade, analisamos diferentes redes complexas com base em conjuntos de dados reais. Cada rede representa um contexto específico, como redes de colaboração, redes de páginas da web, redes de mídia social, e redes de perguntas e respostas online. Foi calculado e interpretado métricas essenciais, como a quantidade de vértices e arestas, o coeficiente de assortatividade de grau, a quantidade de componentes conectados, o tamanho do componente gigante e o coeficiente de clustering. A análise dessas métricas nos ajuda a compreender a estrutura e a dinâmica de cada rede, bem como a identificar tendências importantes para as aplicações específicas dessas redes. Essa análise é crucial para entender o comportamento e as interações dentro de redes complexas do mundo real.
### 1. com-Youtube
   - A rede "com-Youtube" é uma rede de grande escala com muitos vértices e arestas, mas é altamente fragmentada em vários componentes isolados. Ela apresenta uma tendência disassortativa de grau e um coeficiente de agrupamento relativamente baixo. Esses resultados podem ser úteis para entender a estrutura e dinâmica da rede e podem ter implicações em diversas aplicações, como análise de redes sociais e disseminação de informações.
### 2. ca-AstroPh
   - A rede de colaboração "ca-AstroPh" é uma rede extensa com muitos vértices e arestas, e ela exibe uma assortatividade positiva, sugerindo a formação de grupos de colaboradores coesos. A presença de múltiplos componentes conectados indica a existência de várias comunidades menores dentro da rede, enquanto o GCC representa a maior e mais coesa comunidade. O alto coeficiente de clustering médio destaca a tendência à formação de grupos locais de colaboração na área de astrofísica. Esses resultados são importantes para a compreensão da estrutura e da dinâmica das redes de colaboração científica.
### 3. web-Google
   - A rede de páginas da web "web-Google" é uma rede massiva com uma quantidade significativa de vértices e arestas. Ela exibe uma assortatividade negativa em relação ao grau, refletindo a natureza da Web, onde páginas populares estão interconectadas com páginas menos populares. A rede é altamente fragmentada em vários componentes conectados, com um GCC representando a maior comunidade de páginas interconectadas. O alto coeficiente de clustering médio sugere a formação de grupos locais de páginas interconectadas. Esses resultados são fundamentais para a compreensão da estrutura da World Wide Web e seu funcionamento.
### 4. loc-Gowalla
   - A rede de rede social online baseada em localização "loc-Gowalla" é uma rede de grande escala com muitos usuários e conexões. Ela exibe uma assortatividade ligeiramente negativa, o que sugere que os usuários com graus de conexão diferentes interagem entre si. A presença de um único componente conectado indica que a rede é altamente coesa e não possui grupos isolados. O alto coeficiente de clustering médio destaca a tendência à formação de grupos locais de interações. Esses resultados são relevantes para entender como os usuários interagem em uma rede social baseada em localização e como as conexões se distribuem na plataforma.
### 5. sx-askubuntu
   - A rede temporal "sx-askubuntu" é uma rede com uma quantidade considerável de usuários e interações. Ela exibe uma assortatividade negativa em relação ao grau, sugerindo que os usuários com graus de conexão diferentes se conectam entre si. A rede é altamente fragmentada em vários componentes conectados, com um GCC representando a maior comunidade. O coeficiente de clustering médio destaca a tendência à formação de grupos locais de interações na plataforma de perguntas e respostas do Ask Ubuntu. Esses resultados são relevantes para entender como os usuários se relacionam e colaboram em um ambiente de perguntas e respostas online.

