# Aplica-o-do-Algoritmo-Bubble-Sort

# Classificação de Atletas com Bubble Sort

## 1. Identificação do Projeto

**Disciplina:** Algoritmos e Pensamento Computacional  
**Professora:** Profa. Karla Sartin  
**Integrante:** Lucas Eduardo Sousa Silva

## 2. Descrição do Problema

Em competições esportivas, é necessário organizar os resultados
dos participantes para identificar sua classificação.

Este projeto simula uma competição de corrida na qual são
registrados os tempos de 10 atletas. O programa organiza esses
tempos automaticamente, facilitando a visualização dos resultados.

## 3. Objetivo

Desenvolver uma aplicação em linguagem C que utilize o algoritmo
Bubble Sort para ordenar os tempos dos atletas em ordem crescente
ou decrescente.

## 4. Funcionamento do Bubble Sort

O Bubble Sort compara elementos adjacentes de um array e troca
suas posições quando eles estão fora da ordem desejada.

O processo é repetido por meio de estruturas de repetição até
que os elementos estejam ordenados.

Neste projeto, a ordenação crescente apresenta primeiro o menor
tempo, identificando o melhor resultado da corrida. A ordenação
decrescente apresenta primeiro o maior tempo.

## 5. Tecnologias e Ferramentas

- Linguagem C
- Compilador GCC
- Git
- GitHub
- Visual Studio Code ou OnlineGDB

## 6. Como Compilar e Executar

É necessário ter o GCC instalado para utilizar os comandos abaixo.

### Compilação

```bash
gcc competicao.c -o competicao
```

### Execução no Linux

```bash
./competicao
```

### Execução no Windows

```bash
competicao.exe
```

## 7. Exemplo de Entrada e Saída

Exemplo de tempos informados:

12.40, 10.80, 11.50, 9.90, 13.20,
10.20, 11.00, 12.00, 9.70, 10.50

Critério escolhido: crescente.

Resultado esperado:

9.70, 9.90, 10.20, 10.50, 10.80,
11.00, 11.50, 12.00, 12.40, 13.20

O programa também apresenta os resultados originais
e identifica o menor tempo como o melhor resultado.

## 8. Considerações Finais

O desenvolvimento deste projeto permite aplicar conceitos
de arrays, variáveis, estruturas condicionais e laços de repetição.

A implementação do Bubble Sort demonstra como algoritmos podem
ser utilizados para organizar dados de uma situação cotidiana,
contribuindo para a compreensão da lógica de programação.
