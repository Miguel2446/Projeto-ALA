# Análise de Preconceito com Python

![GitHub repo size](https://img.shields.io/github/repo-size/leticiatavaresds/Projeto-ALA?color=a21360&style=for-the-badge)
![GitHub language count](https://img.shields.io/github/languages/count/leticiatavaresds/Projeto-ALA?color=a21360&style=for-the-badge)
![Made With](https://img.shields.io/badge/Made%20With-Python;%20Jpyter%20Notebook-lightgrey?color=a21360&style=for-the-badge)
![GitHub repo file count](https://img.shields.io/github/directory-file-count/leticiatavaresds/Projeto-ALA?color=a21360&style=for-the-badge)
![GitHub last commit](https://img.shields.io/github/last-commit/leticiatavaresds/Projeto-ALA?color=a21360&style=for-the-badge)


# Índice

- [Introdução](#introdução)
- [Trabalhos Futuros](#trabalhos-futuros)
- [Licença](#licença)

# Introdução

O projeto apresenta a construção de um método de classificação de preconceito em textos aplicado em frases retiradas da internet em português brasileiro, onde todas possuiam discurso de ódio.

Na proposta foi utilizada uma metodologia para a análise do preconceito com base no aprendizado de máquina que envolvia o método de Fatorização de Matriz Não-Negativa. Para isso, foram realizadas as etapas de coleta de frase com teor preconceituoso, rotulação manual de cada frase, pré-processamento dos dados, construção de uma matriz com os dados, fatorização da matriz e análise do resultado.

O resultado obtido não foi satisfatório devido a baixa qualidade do dataset que além de possuir poucos documentos, não está balanceado e possue muitas frases parecidas, contendo assim um vocablário pequeno. Além disso, o tema escolhido possuem mensagens difíceis de serem rotuladas até mesmo pelos humanos, com isso as incertezas nas classificações também podem ser justificadas por essa qestão. Dessa forma, fica visível a dificuldade deste tipo de classificação já que envolve conceitos de opinião e pontos de vista.

# Trabalhos Futuros

A partir dos resultados obtidos, nota-se que alguns pontos merecem
atenção especial, como construir um dataset melhor e testar outros métodos para verificar se é possível obter um resultado com uma qualidade melhor.

Podem ser feitas também análises específicas sobre os termos mais comumente utilizados por usuários do Twitter para abordar um tipo de preconceito poderiam ser realizadas. Além disso, utilizar a geolocalização para identificar regiões que mais comentam sobre tais assuntos identificando a polaridade das mensagens. 

Com isso,  pretende-se dar continuidade a este projeto nas seguintes direções:

*  Obter um dataset maior e mais balanceado a partir de uma API fornecida pla rede social "twitter".
*  Procurar bibliotecas mais eficientes para o pré-processamento de textos em português brasileiro, se necessário, tentar construir uma ou trabalhar com documentos em inglês, já que para esse idioma é possível encontrar bibliotecas com boa qualidade.
* Calcular a acurácia do resultado
* Aplicar outros métodos como o LDA, para comparar os resultados obtidos e assim definir o melhor.
* Incluir informacões geográficas – como latitude e longitude dos emissores dos tweets, permitindo a geracão de grafos associados e o estudo da difusão dos tipos de preconceito;
*Criar uma função para analisar novos documentos de textos e classificá-los.

# Licença

The MIT License (MIT) 2022 - Letícia Tavares. Leia o arquivo [LICENSE.md](https://github.com/leticiatavaresds/Projeto-ALA/blob/master/LICENSE.md) para mais detalhes.

[⬆ Voltar ao topo](#análise-de-preconceito-com-python)<br>
