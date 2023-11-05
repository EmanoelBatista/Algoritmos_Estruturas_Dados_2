# Requisitos 2

## Objetivo
- Para cada uma das redes escolhidas, fazer um gráfico bipartido sobre a assortatividade em relação ao grau dos nós da rede. Também, interpreta os resultados comparando as diferentes
redes, o texto da interpretação deverá ter entre 500 e 1000 palavras.
- Este [link](https://github.com/EmanoelBatista/Algoritmos_Estruturas_Dados_2/blob/main/U2T2/Requisito_02/requisitos_02.ipynb) contém os códigos e os gráficos para cada rede escolhida.

## Interpretação dos resultados
- No trabalho realizado, foram realizadas análises de assortatividade em relação ao grau dos nós em diferentes redes complexas. O objetivo principal era visualizar como os nós de cada rede estavam organizados em termos de seus graus, isto é, se os nós com graus semelhantes tendiam a se conectar uns aos outros (assortatividade positiva) ou se ocorria o oposto (assortatividade negativa). Um valor positivo indica que os nós com graus semelhantes têm maior probabilidade de se conectar, enquanto um valor negativo sugere que os nós com graus diferentes têm maior probabilidade de se conectar.
- Análise de cada rede:
  - com-Youtube:
    - A rede com-Youtube demonstra uma assortatividade de grau negativa, o que significa que, nessa rede, nós com graus mais elevados têm uma tendência a se conectar com nós que possuem graus mais baixos. Essa característica sugere uma distribuição mais uniforme dos graus entre os nós da rede. Em outras palavras, os canais com um grande número de seguidores interagem não apenas entre si, mas também com canais menos populares. Isso pode ser resultado da natureza diversificada do conteúdo no YouTube e do fato de que criadores de conteúdo com diferentes níveis de popularidade se conectam entre si.

- ca-AstroPh:
Na rede ca-AstroPh, observamos uma assortatividade de grau positiva. Isso significa que pesquisadores com graus de colaboração semelhantes tendem a trabalhar juntos. Essa característica reflete a natureza da colaboração científica, onde cientistas com níveis semelhantes de experiência e envolvimento trabalham em projetos de pesquisa conjuntos. Essa colaboração pode envolver pesquisadores com conhecimentos e contribuições semelhantes, o que leva a uma assortatividade de grau positiva.

- web-Google:
A rede web-Google exibe uma assortatividade de grau negativa. Isso sugere que páginas da web, independentemente de sua popularidade, tendem a se conectar umas às outras. Em outras palavras, o algoritmo de busca do Google não favorece a vinculação entre páginas populares ou não. Ele se baseia em critérios como relevância e conteúdo. Isso resulta em uma distribuição de graus mais aleatória, onde páginas populares podem se vincular a páginas menos populares e vice-versa.

- loc-Gowalla:
A rede loc-Gowalla apresenta uma assortatividade de grau negativa, indicando que usuários ativos que fazem check-in em locais com frequência tendem a interagir com outros usuários que fazem check-in com menos frequência. Isso pode ser devido à natureza do aplicativo Gowalla, onde pessoas que visitam muitos lugares (usuários ativos) podem interagir com aqueles que fazem check-in em menos lugares (usuários menos ativos). Essa diversidade de interações pode criar uma rede mais aberta e heterogênea.

- sx-askubuntu:
A rede sx-askubuntu exibe uma assortatividade de grau negativa, o que sugere que usuários experientes na plataforma interagem com aqueles que estão começando. Em fóruns de suporte, como o Ask Ubuntu, usuários mais experientes geralmente ajudam os iniciantes respondendo a suas perguntas. Isso resulta em uma rede onde nós com graus mais altos (usuários experientes) tendem a se conectar com nós de graus mais baixos (usuários iniciantes), refletindo a dinâmica de apoio na comunidade.
Essas análises detalhadas ajudam a compreender como as redes se organizam em relação à assortatividade de grau e como essa organização está relacionada à natureza e ao propósito de cada rede. Cada rede possui características únicas que moldam suas tendências de assortatividade em relação ao grau.






