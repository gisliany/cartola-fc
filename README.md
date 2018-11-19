# Análise dos dados do Cartola FC

O dataset é composto por dados do repositório [caRtola](https://github.com/henriquepgomide/caRtola). Foram utilizadas todas as 32 rodadas do ano de 2018.

O trabalho foi dividido nas seguintes seções:

**1. Introdução:** Refere-se a análise dos dados brutos. Inicialmente, os dados são importados para que seja possível visualizar as colunas de características, número de linhas, tipos de dados (categóricos, numéricos), existência de dados faltantes e distribuição das instâncias.

**2. Limpeza dos dados:** Aqui é criada a nova base de dados modelada ao problema proposto. A limpeza visa remover atributos desnecessários, combinar atributos, transformar atributos categóricos em numéricos, imputar dados faltantes e normalizá-los. Fazendo uso de pipeline para reconstruir um novo dataset para cada problema abordado.

**3. Clusterização:** Foram realizadas duas análises utilizanado a clusterização por meio do *KMeans*. A primeira foi a análise dos meio campistas: utilizando as características número de bolas roubadas e faltas sofridas é possível agrupar os meio campistas em 4 tipos de performaces. A segunda análise se deu agrupando jogadores de alto valor: buscou-se agrupar os jogadores em grupos de alto e baixo valor, utilizando para isso 3 atributos.

**4. Tomada de decisão:** Foi utilizado o algoritmo classificador *DecisionTree* para prever a posição de 3 jogadores e o algoritmo de regressão para estimar sua pontuação.

## Contribuidores
- [Gisliany Alves](https://github.com/gisliany)
- [Jusciaane Chacon](https://github.com/jusciaane)
- [Marianne Diniz](https://github.com/MarianneDiniz)