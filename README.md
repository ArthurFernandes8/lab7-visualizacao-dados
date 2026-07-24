# Cidades-irmãs pelo mundo

Projeto final da disciplina de **Visualização de Dados** — Grupo J.

Integrantes: Arthur Araujo, Jefferson Brasil, José Maciel, Rafael Cavalcante e Vinícius Nóbrega.

## Sobre o projeto

A visualização apresenta a rede de conexões entre cidades-irmãs ao redor do mundo. É possível explorar conexões internacionais e nacionais, aplicar recortes por hemisfério, continente e país, além de destacar os países mais conectados.

## Como executar

- URL: https://arthurfernandes8.github.io/lab7-visualizacao-dados/

## Como usar

- Escolha o modo de visualização e o tipo de conexão.
- Use os filtros de hemisfério, continente e país para restringir os dados exibidos.
- Clique em um país no mapa para consultar o total de conexões e seus parceiros.
- Use **Limpar** para restaurar os filtros iniciais.

## Estrutura

- `index.html`: página da entrega, visualização e dados incorporados.
- `vendor/echarts.min.js`: biblioteca ECharts utilizada na visualização.
- `vendor/worldmap.js`: geometria do mapa-múndi.
- `linked-cities/`: arquivos CSV originais usados na preparação dos dados.

Os dados de cidades e conexões utilizados na página estão incorporados no próprio `index.html`, conforme a orientação da disciplina. A pasta `vendor` deve acompanhar o arquivo HTML na entrega.
