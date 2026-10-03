Este é o primeiro desafio de projeto do curso de Lógica de Programação da DIO

Nome do do Desafio: Classificador de Nível de Herói
 
Instruções para entrega
# 1️⃣ Desafio Classificador de nível de Herói

**O Que deve ser utilizado**

- Variáveis
- Operadores
- Laços de repetição
- Estruturas de decisões

## Objetivo

Crie uma variável para armazenar o nome e a quantidade de experiência (XP) de um herói, depois utilize uma estrutura de decisão para apresentar alguma das mensagens abaixo:

Se XP for menor do que 1.000 = Ferro
Se XP for entre 1.001 e 2.000 = Bronze
Se XP for entre 2.001 e 5.000 = Prata
Se XP for entre 5.001 e 7.000 = Ouro
Se XP for entre 7.001 e 8.000 = Platina
Se XP for entre 8.001 e 9.000 = Ascendente
Se XP for entre 9.001 e 10.000= Imortal
Se XP for maior ou igual a 10.001 = Radiante

## Saída

Ao final deve se exibir uma mensagem:
"O Herói de nome **{nome}** está no nível de **{nivel}**"


Sobre o projeto
O projeto faz parte da minha jornada de aprendizado em programação e será utilizado como parte do meu portfólio no GitHub.
Fiz umas alterações no codigo proposto porque se o xp fosse igual a 1000 como estava no enunciado (xp<1000), o codigo não iria mostrar nada, então coloquei (xp<=1000) e para simplificar o intervalo de (xp >= 1001 && xp <= 2000), deixei só (xp <=2000) e fiz isso para os demais, deixando mais limpo.