## Classificador de Nível de Herói
Este e o primeiro desafio de projeto do curso de Logica de Programação da DIO.

## Nome do desafio: Classificador de Nivel de Herói

## Instrucoes para entrega
1. Desafio: Classificador de Nível de Herói
## O que deve ser utilizado
Variaveis

Operadores

Laços de repetição

Estruturas de decisão

## Objetivo
Criar uma variavel para armazenar o nome e a quantidade de experiência (XP) de um herói. Depois, utilizar uma estrutura de decisão para apresentar o nível correspondente a quantidade de XP.

## Classificação
XP menor ou igual a 1.000 = Ferro

XP entre 1.001 e 2.000 = Bronze

XP entre 2.001 e 5.000 = Prata

XP entre 5.001 e 7.000 = Ouro

XP entre 7.001 e 8.000 = Platina

XP entre 8.001 e 9.000 = Ascendente

XP entre 9.001 e 10.000 = Imortal

XP maior ou igual a 10.001 = Radiante

## Saída
Ao final, deve ser exibida uma mensagem:

O Herói de nome {nome} esta no nível de {nivel}

## Exemplo
Neste projeto, o herói utilizado é o Pikachu, com 7.500 XP.

O Herói de nome Pikachu está no nível de Platina

## Sobre o projeto
O projeto faz parte da minha jornada de aprendizado em lógica de programação e será utilizado como parte do meu portfólio no GitHub.

Durante o desenvolvimento, fiz algumas alterações no código proposto no desafio.

Uma das alterações foi na primeira condição. No enunciado original, a condição apresentada é:

xp < 1000

Porém, dessa forma, caso o XP fosse exatamente 1.000, o herói não seria classificado em nenhum nível, pois a próxima faixa começa em 1.001.

Para corrigir essa situação, utilizei:

xp <= 1000

Tambem simplifiquei as demais condições. Por exemplo, em vez de utilizar:

xp >= 1001 && xp <= 2000

utilizei apenas:

xp <= 2000

Isso funciona porque as condições sãoo verificadas em sequencia. Se o programa chegar ao else if (xp <= 2000), significa que a condição anterior (xp <= 1000) ja foi considerada falsa.

Fiz a mesma simplificação nas demais faixas, deixando o codigo mais limpo, simples e fácil de entender.