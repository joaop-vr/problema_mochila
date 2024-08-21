# Problema da Mochila - Implementação em C

Este projeto implementa a solução para o clássico **Problema da Mochila** (Knapsack Problem) utilizando a linguagem de programação C. O problema da mochila é um problema de otimização combinatória, onde o objetivo é maximizar o valor total dos itens que podem ser colocados em uma mochila, respeitando uma restrição de peso.

## Estrutura do Projeto

O projeto é composto pelos seguintes arquivos:

- **`main.c`**: Contém a função principal do programa, responsável por interagir com o usuário e orquestrar a solução do problema.
- **`bib_main.c` e `bib_main.h`**: Contêm as funções auxiliares e as estruturas de dados utilizadas na solução do problema.
- **`Makefile`**: Script de automação para a compilação do projeto.

## Funcionalidades Implementadas

O programa permite resolver o problema da mochila para diferentes instâncias fornecidas pelo usuário. As funcionalidades principais incluem:

- **Leitura de dados**: O programa lê os valores e pesos dos itens, bem como a capacidade máxima da mochila.
- **Cálculo da solução**: Utiliza algoritmos de otimização para determinar o subconjunto de itens que maximiza o valor total sem exceder a capacidade da mochila.
- **Exibição da solução**: Mostra quais itens foram selecionados, o valor total alcançado, e o peso total utilizado.

## Compilação

### Como Compilar
O projeto inclui um `Makefile` para facilitar a compilação. Para compilar o projeto, basta executar o seguinte comando no terminal:
```bash
make
```
Isso gerará o executável a partir dos arquivos fonte fornecidos.

### Como Executar
Após a compilação, execute o programa com o comando:

```bash
./exec
```
Siga as instruções exibidas para realizar as operações na Tabela Hash.

## Uso do Programa

O programa permite:

- **Inserir os dados**: Especifique o número de itens, seus valores, pesos, e a capacidade da mochila.
- **Executar o algoritmo**: O programa calculará a melhor combinação de itens para maximizar o valor total sem exceder a capacidade.
- **Exibir os resultados**: O programa mostrará os itens selecionados, o valor total e o peso total.

## Estrutura do Código

- **`main.c`**: Gerencia a entrada e saída de dados, além de chamar as funções de solução.
- **`bib_main.c`**: Implementa as funções de cálculo e lógica do problema.
- **`bib_main.h`**: Define as estruturas de dados e declarações das funções.
- **`Makefile`**: Facilita a compilação do projeto, criando o executável a partir dos arquivos fonte.





