# Exercício de Complexidade

## Introdução

Esse trabalho consiste em verificar a relação tempo/tanho da entrada de algoritmos
de diferentes classes de complexidade. Para isso você deve seguir as etapas mostradas
abaixo.

## 1 - Implementar os algoritmos
Implementar pelo menos um algoritmo para cada uma das seguintes classes de complexidade:

Complexidade | Sugestão
-------------|----------
O(log(n))    | (busca binária)
O(n)         | (busca sequencial)
O(n*log(n))  | (*merge sort*)
O(n²)        | (*bubble sort*)

## 2 - Verificar o tempo de execução

Executar cada algoritmo verificando seu tempo de execução para valores crescentes
de n (tamanho da entrada). Por exemplo: Verificar o tempo de execução para entradas
de tamanho 100, 200, ..., 500.

## 3 - Gerar o csv
Gerar um arquivo csv com os valores gerados no experimento, **comparando os algoritmos 
2 a 2**. Você pode gerar csv com o seguinte formato:

Uma matriz onde a primeira coluna é composta pelos valores de n, e as colunas seguintes
compostas pelo tempo de execução de cada algoritmo correspondentes aos tamanhos de entrada
da primeira coluna. Exemplo:


	tam,bubble,merge
	100,0.1,0.2
	200,0.5,0.4
	300,0.10,0.8
	400,0.15,6.4
	500,0.25,16.5


No exemplo de arquivo acima, para n = 10, o algoritmo 1 lovou 0.1 segundos para executar e o
algoritmo 2 levou 0.2 segundos.

**Obs.:** Os valores de uma linha devem ser separados por ','

## 4 - Gerar o gráfico

Gerar um gráfico a partir do arquivo csv. Você pode gerar o gráfico utilizando o *Calc*
do *LibreOffice*. Sugerimos que você crie um Gráfico de Linhas para representar o csv.

### 4.1 - Comparar O(n) e O(log(n))
Gere um gráfico comparando as classes O(n) e O(log(n)) para n = 100, n = 200, ..., n = 50000.

### 4.2 - Comparar O(n*log(n)) e O(n²)
Gere um gráfico comparando as classes O(n*log(n)) e O(n²) para n = 10, n = 20, ..., n = 2000.

## Exercício extra

Implemente um algoritmo recursivo para calcular o n-ésimo número de Fibonacci e verifique
até que valor de n você consegue executar em menos de 1 segundo.
