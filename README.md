Classificador de Nivel de Heroi
Este e o primeiro desafio de projeto do curso de Logica de Programacao da DIO.

Nome do desafio: Classificador de Nivel de Heroi

Instrucoes para entrega
1. Desafio: Classificador de Nivel de Heroi
O que deve ser utilizado
Variaveis

Operadores

Lacos de repeticao

Estruturas de decisao

Objetivo
Criar uma variavel para armazenar o nome e a quantidade de experiencia (XP) de um heroi. Depois, utilizar uma estrutura de decisao para apresentar o nivel correspondente a quantidade de XP.

Classificacao
XP menor ou igual a 1.000 = Ferro

XP entre 1.001 e 2.000 = Bronze

XP entre 2.001 e 5.000 = Prata

XP entre 5.001 e 7.000 = Ouro

XP entre 7.001 e 8.000 = Platina

XP entre 8.001 e 9.000 = Ascendente

XP entre 9.001 e 10.000 = Imortal

XP maior ou igual a 10.001 = Radiante

Saida
Ao final, deve ser exibida uma mensagem:

O Heroi de nome {nome} esta no nivel de {nivel}

Exemplo
Neste projeto, o heroi utilizado e o Pikachu, com 7.500 XP.

O Heroi de nome Pikachu esta no nivel de Platina

Sobre o projeto
O projeto faz parte da minha jornada de aprendizado em programacao e sera utilizado como parte do meu portfolio no GitHub.

Durante o desenvolvimento, fiz algumas alteracoes no codigo proposto no desafio.

Uma das alteracoes foi na primeira condicao. No enunciado original, a condicao apresentada e:

xp < 1000

Porem, dessa forma, caso o XP fosse exatamente 1.000, o heroi nao seria classificado em nenhum nivel, pois a proxima faixa comeca em 1.001.

Para corrigir essa situacao, utilizei:

xp <= 1000

Tambem simplifiquei as demais condicoes. Por exemplo, em vez de utilizar:

xp >= 1001 && xp <= 2000

utilizei apenas:

xp <= 2000

Isso funciona porque as condicoes sao verificadas em sequencia. Se o programa chegar ao else if (xp <= 2000), significa que a condicao anterior (xp <= 1000) ja foi considerada falsa.

Fiz a mesma simplificacao nas demais faixas, deixando o codigo mais limpo, simples e facil de entender.