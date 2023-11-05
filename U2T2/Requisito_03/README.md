# Requisitos 3

## Objetivo
- Reproduzir a tabela abaixo para cada uma das redes escolhidas.
- Implementar a tabela no formato markdown juntamente com a interpretação dos resultados cuja o texto deverá ter entre 500 a 1000 palavras.
 
<img src="https://github.com/EmanoelBatista/Algoritmos_Estruturas_Dados_2/blob/main/U2T2/Requisito_03/Tabela.png" alt="Tabela" width="600" height="400">

## Interpretação dos resultados
- Nesta atividade, iremos analisar diferentes redes complexas com base em conjuntos de dados reais. Cada rede representa um contexto específico, como redes de colaboração, redes de páginas da web, redes de mídia social, e redes de perguntas e respostas online. Vamos calcular e interpretar métricas essenciais, como a quantidade de vértices e arestas, o coeficiente de assortatividade de grau, a quantidade de componentes conectados, o tamanho do componente gigante e o coeficiente de clustering. A análise dessas métricas nos ajudará a compreender a estrutura e a dinâmica de cada rede, bem como a identificar tendências importantes para as aplicações específicas dessas redes. Essa análise é crucial para entender o comportamento e as interações dentro de redes complexas do mundo real.

### Tabela
|                 | Quantidade de vértices | Quantidade de arestas | Degree Assortativity Coefficient | Quantidade de componentes conectados | Tamanho do Componente Gigante (GCC) | Coeficiente de Clustering |
|---------------------|-------------------------|-----------------------|----------------------------------|-------------------------------------|-----------------------------------|---------------------------|
| com-Youtube              |      1134890      |     2987624     |          -0.028332126333519572           |           1134890             |          1             |       0.04040113888093932       |
| ca-AstroPh              | 18772           | 396160         | 0.20518714346398922                    | 290                       | 17903                     | 0.6305932411707943             |
| web-Google              | 875713           | 5105039         | -0.06520019402435487                   | 371764                      | 434818                      | 0.3698306814797672             |
| loc-Gowalla              | 196591           | 1900654         | -0.02925474163485361                    | 1                      | 196591                      | 0.23672372971033598             |
| sx-askubuntu              | 159316           | 596933         | -0.10278842628952252                    | 97174                       | 59813                      | 0.07696177166103574             |

## - com-Youtube
- A rede "com-Youtube" é uma rede de grande escala com muitos vértices e arestas, mas é altamente fragmentada em vários componentes isolados. Ela apresenta uma tendência disassortativa de grau e um coeficiente de agrupamento relativamente baixo. Esses resultados podem ser úteis para entender a estrutura e dinâmica da rede e podem ter implicações em diversas aplicações, como análise de redes sociais e disseminação de informações.
