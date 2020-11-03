# Filtro de Faixas de Loteria
---

## 1. Escolha de loteria
   
O primeiro passo para filtra dezenas é escolha a loteria das combinações que serão utilizadas na operação. Segue a baixa a imagem das opções de loteria:

![Escolha de loteria](https://imagens-publicas-yure.s3.amazonaws.com/escolha-de-loteria.png)

## 2. Definição da quantidade de faixas e dezenas da loteria

Após ter escolhido a loteria escolha a quantidade de faixas que as dezenas da loteria serão divididas, prencha o intervalo de cada faixa e clique no botão "Gerar dezenas". Segue abaixa a imagem do campo de quantidade:

![Dezenas das faixas](https://imagens-publicas-yure.s3.amazonaws.com/gerar-dezenas-faixas.png)

> **Exemplificando**:  
> Se no campo da faixa F1 forem definidos 1 e 10 como inicio e fim respectivamente, o intervalo de dezenas criado será: [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]. E estas serão as dezenas da faixa F1.


## 3. Filtragem da quantidade min. e máx. de faixas (opcional).

Para definir a quantidade mínima e máxima de faixas das combinações que serão filtradas selecione o checkbox do filtro "Qtd. de Faixas" e preenche os valores dos respectivos limites. Segue abaixo a imagem dos campos:

![Quantidade de faixas](https://imagens-publicas-yure.s3.amazonaws.com/quantidade-maxima-faixas.png)

> **Exemplificando**:  
> Se considerarmos uma combinação qualquer e definirmos que desejamos ter no mínimo 5 e no máximo 6 faixas por combinação:  
>
> **_Exemplo #1_**:  
> [ 01, 11, 12, 27, 35, 60 ] ou seja, [ F1, F2, F2, F3, F4, F6 ] :heavy_check_mark:  
> [ 01, 04, 12, 13, 35, 39 ] ou seja, [ F1, F1, F2, F2, F4, F4 ] :x:

## 4. Filtragem da quantidade min. e máx. de dezenas (opcional).

Para filtar a quantidade especifica de dezenas desejadas em cada faixa coloque o valor mínimo e máximo para cada faixa, se quiser gerar um intervalo default preencha o valor mínimo e máximo e clique no botão "Preencher faixas". Segue abaixo a imagem dos campo:

![Quantidade de dezenas por faixa](https://imagens-publicas-yure.s3.amazonaws.com/quantidade-dezenas-faixas.png)

> **Exemplificando**:  
> Se considerarmos uma combinação qualquer e definirmos que desejamos ter no mínimo 2 e no máximo 3 dezenas na faixa F2 por combinação:  
>
> **_Exemplo #1_**:  
> [ 01, 11, 12, 27, 35, 60 ] ou seja, [ F1, F2, F2, F3, F4, F6 ] :heavy_check_mark:  
> [ 01, 04, 05, 13, 35, 39 ] ou seja, [ F1, F1, F1, F2, F4, F4 ] :x:

## 5. Filtragem da quantidade de dezenas consecutivas (opcional).

Para filtrar a quantidade de dezenas consecutivas, selecione o checkbox do filtro e preencha o valor mínimo e máximo geral e/ou específico de cada faixa. Segue abaixo a imagem dos campos:

![Quantidade de dezenas consecutivas](https://imagens-publicas-yure.s3.amazonaws.com/quantidade-dezenas-consecutivas.png)

> **Exemplificando**:  
> Se considerarmos uma combinação qualquer e definirmos que desejamos ter no mínimo 2 e no máximo 3 dezenas consecutivas em geral por combinação:  
>
> **_Exemplo #1_**:  
> [ 01, 11, 12, 27, 35, 60 ] ou seja, [ F1, F2, F2, F3, F4, F6 ] :heavy_check_mark:  
> [ 01, 04, 15, 18, 35, 49 ] ou seja, [ F1, F1, F2, F2, F4, F5 ] :x:  
>
> Se considerarmos uma combinação qualquer e definirmos que desejamos ter no mínimo 2 e no máximo 3 dezenas consecutivas em geral e no minímo 2 e no máximo 3 na faixa F3 por combinação: 
>
> **_Exemplo #2_**:  
> [ 01, 11, 26, 27, 35, 60 ] ou seja, [ F1, F2, F3, F3, F4, F6 ] :heavy_check_mark:  
> [ 01, 04, 15, 18, 35, 49 ] ou seja, [ F1, F1, F2, F2, F4, F5 ] :x:

## 6. Filtragem da quantidade de dezenas pares/impares (opcional).

Para filtrar a quantidade de dezenas pares e impares, preencha o valor mínimo e máximo de dezenas pares e impares, respectivamente. Segue abaixo a imagem dos campos:

![Quantidade de dezenas pares/impares](https://imagens-publicas-yure.s3.amazonaws.com/quantidade-dezenas-pares-impares.png)

> **Exemplificando**:  
> Se considerarmos uma combinação qualquer e definirmos que desejamos ter no mínimo 3 e no máximo 3 dezenas pares e no mínimo 3 e no máximo 3 impares por combinação:  
>
> **_Exemplo #1_**:  
> [ 01, 11, 12, 27, 32, 60 ] ou seja, [ F1, F2, F2, F3, F4, F6 ] :heavy_check_mark:  
> [ 01, 04, 15, 18, 35, 49 ] ou seja, [ F1, F1, F2, F2, F4, F5 ] :x:  

## 7. Filtragem da quantidade min. e máx do somatório de dezenas (opcional).

Para filtrar o somatório de dezenas de cada combinação, selecione o checkbox do filtro e preencha os limites, minimo e máximo respectivamente. Segue abaixo a imagem dos campos:

![Quantidade min/máx do somatório de dezenas](https://imagens-publicas-yure.s3.amazonaws.com/somatorio-dezenas.png)

> **Exemplificando**:  
> Se considerarmos uma combinação qualquer e definirmos que desejamos ter o somatório de dezenas de valor mínimo de 140 e  valor máximo de 150 por combinação:  
>
> **_Exemplo #1_**:  
> [ 01, 11, 12, 27, 32, 60 ] ou seja, 143 :heavy_check_mark:  
> [ 10, 14, 15, 28, 34, 49 ] ou seja, 150 :heavy_check_mark:  
> [ 01, 04, 15, 18, 35, 49 ] ou seja, 122 :x:  

## 8. Escolha da origem das dezenas.

Após definir os filtro que serão usados é preciso escolhar a fonte de ondem serão captadas as combinações. Existem duas possibilidades, através de upload de um arquivo CSV ou buacando os resultados da Caixa Economica no banco de dados. Segue abaixo a imagem dos campos:

![Origem das dezenas](https://imagens-publicas-yure.s3.amazonaws.com/origem-dezenas.png)

Via upload de arquivo(csv):

![Origem das dezenas](https://imagens-publicas-yure.s3.amazonaws.com/origem-dezenas-arquivo.png)

Via resultados da Caixa no banco de dados: 

![Origem das dezenas](https://imagens-publicas-yure.s3.amazonaws.com/origem-dezenas-caixa.png)