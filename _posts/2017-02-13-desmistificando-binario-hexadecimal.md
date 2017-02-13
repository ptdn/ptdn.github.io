---
layout: post
title: Desmistificando os Sistemas de Numeração Binário e Hexadecimal
---

Desde que o mundo é mundo, o cálculo de sub-redes e endereçamento IPv4 é um dos assuntos que mais "mete medo" em que está começando os estudos de Redes. Este post pretende apresentar os sistemas de numeração, e como este entendimento é necessário para dar os passos seguintes.

## Tudo começou com nossos dedos...

Alguém já parou para se perguntar o porque de termos o sistema decimal como o padrão ao redor do mundo? 

A resposta é até simples. Porque temos 10 dedos nas mãos.

Parece bobo, mas esta facilidade de interpretar as contagens utilizando-se de nossos próprios membros foi fator determinante para que este sistema de numeração fosse o adotado por nós, seres humanos, como o que nos acompanha para nossa vida diária.

Você deve se lembrar das aulas da Tia Maricota, enquanto estava aprendendo a contar e interpretar os algarismos: Unidade, Dezena, Centena, Milhar... O nome correto para este modo de interpretar os números denota-se ***valor posicional***. Significa que, dependendo da ***posição*** na qual o número está em determinado algarismo, ele terá um ***valor*** específico, um "peso". Vejamos um exemplo:

| Valor Posicional | 100 | 10 | 1 |
|------------------|-----|----|---|
| Algarismo        | 2   | 0  | 0 |

Que 200 é 200, todo mundo já sabe. Mas... Porque 200 é 200? Simples:

2 x ***100*** + 0 x ***10*** + 0 x ***1*** = 200

Ou seja: A cada vez que "pulamos" para a direita para analisar o próximo número inserido no algarismo, este terá valor 10x maior do que o anterior.

E isto porque... Estamos no sistema de ***base 10***, claro.

Vamos a mais um exemplo?

| Valor Posicional | 100 | 10 | 1 |
|------------------|-----|----|---|
| Algarismo        | 9   | 9  | 9 |

9 x ***100*** + 9 x ***10*** + 9 x ***1*** = 900 + 90 + 9 = 999

## O Sistema Binário

Você já deve saber a famosa história de que os dispositivos digitais compreendem através do sistema binário, por conta da natureza binária da informação (Presença ou ausência de corrente, sinal, etc). E... O que muda do sistema binário para o decimal?

Apenas que o fator multiplicador do valor posicional deixa de ser 10, para se tornar 2.

Vamos a um exemplo?

| Valor Posicional | 4   | 2  | 1 |
|------------------|-----|----|---|
| Algarismo        | 1   | 1  | 1 |

1 x ***4*** + 1 x ***2*** + 1 x ***1*** = 4 + 2 + 1 = 7

Foi tão rápido, mas acabamos de fazer a nossa ***primeira conversão*** de um algarismo do sistema binário para o decimal!

***111*** (binário) = ***7*** (decimal)

### Exercícios:

Converta os seguintes números do sistema binário para o decimal:

***a***: 1111
***b***: 110
***c***: 01111111

### Respostas:

***a***.

| Valor Posicional | 8 | 4 | 2 | 1 |
|------------------|---|---|---|---|
| Algarismo        | 1 | 1 | 1 | 1 |

***1111*** (binário) = ***15*** (decimal)

***b***.

| Valor Posicional | 4   | 2  | 1 |
|------------------|-----|----|---|
| Algarismo        | 1   | 1  | 0 |

***110*** (binário) = ***6*** (decimal)

***c***.

| Valor Posicional | 128 | 64 | 32 | 16 | 8 | 4 | 2 | 1 |
|------------------|-----|----|----|----|---|---|---|---|
| Algarismo        | 0   | 1  | 1  | 1  | 1 | 1 | 1 | 1 |

***01111111*** (binário) = ***127*** (decimal)

## O Sistema Hexadecimal

Este sistema de numeração (Base 16)também é muito utilizado em Computação, para diversas aplicações. E sabe o motivo?

Ele possui a capacidade de representar códigos binários muito grandes de modo mais legível. Isto se deve a um "truque" matemático: Um conjunto de 4 dígitos binários equivalem, sem perda de interpretação, a um dígito hexadecimal. 

Você deve ter em mente a tabela que relaciona os grupos binários com seus respectivos dígitos hexadecimais. Mas fique tranquilo(a). Ela está logo abaixo:

| Binário | Hexadecimal |
|---------|-------------|
| 0000    | 0           |
| 0001    | 1           |
| 0010    | 2           |
| 0011    | 3           |
| 0100    | 4           |
| 0101    | 5           |
| 0110    | 6           |
| 0111    | 7           |
| 1000    | 8           |
| 1001    | 9           |
| 1010    | A           |
| 1011    | B           |
| 1100    | C           |
| 1101    | D           |
| 1110    | E           |
| 1111    | F           |

A coisa é mais intuitiva do que parece. Vejamos na prática uma conversão de um número binário para hexadecimal:

| Binário     | 1010 | 1010 | 1100 | 1101 |
|-------------|------|------|------|------|
| Hexadecimal | A    | A    | C    | D    |

Simples assim.

### Exercício:

Converte esse endereço MAC para binário pra mim, por favor:

**00:19:B9:FB:E2:58**

### Resposta:

Você vai notar que, uma vez sabendo o "truque" matemático, tudo é muito simples. Veja:

| Endereço MAC (Hexadecimal) | 0    | 0    | 1    | 9    | B    | 9    | F    | B    | E    | 2    | 5    | 8    |
|----------------------------|------|------|------|------|------|------|------|------|------|------|------|------|
| Binário                    | 0000 | 0000 | 0001 | 1001 | 1011 | 1001 | 1111 | 1011 | 1110 | 0010 | 0101 | 1000 |

## Concluindo...

Bom, espero que este pequeno tutorial sobre os sistemas de numeração tenham sido úteis para você. Se você gostou do conteúdo, não deixe de compartilhar com seus amigos e colegas de trabalho! Forte abraço!

> ***Fernando Gomes*** é fundador do PTDN e um jovem de 24 anos apaixonado por Tecnologia da Informação e pelo Ensino. Atualmente é Instrutor de TI  do projeto Naves do Conhecimento no Rio de Janeiro. Nas horas vagas, gosta de passar o tempo ao lado da família e da namorada.




