---
layout: post
title: Desmistificando os Sistemas de Numeração Binário e Hexadecimal
---

<p>Desde que o mundo é mundo, o cálculo de sub-redes e endereçamento IPv4 é um dos assuntos que mais &quot;mete medo&quot; em que está começando os estudos de Redes. Este post pretende apresentar os sistemas de numeração, e como este entendimento é necessário para dar os passos seguintes.</p>
<h2 id="tudo-começou-com-nossos-dedos...">Tudo começou com nossos dedos...</h2>
<p>Alguém já parou para se perguntar o porque de termos o sistema decimal como o padrão ao redor do mundo?</p>
<p>A resposta é até simples. Porque temos 10 dedos nas mãos.</p>
<p>Parece bobo, mas esta facilidade de interpretar as contagens utilizando-se de nossos próprios membros foi fator determinante para que este sistema de numeração fosse o adotado por nós, seres humanos, como o que nos acompanha para nossa vida diária.</p>
<p>Você deve se lembrar das aulas da Tia Maricota, enquanto estava aprendendo a contar e interpretar os algarismos: Unidade, Dezena, Centena, Milhar... O nome correto para este modo de interpretar os números denota-se <strong><em>valor posicional</em></strong>. Significa que, dependendo da <strong><em>posição</em></strong> na qual o número está em determinado algarismo, ele terá um <strong><em>valor</em></strong> específico, um &quot;peso&quot;. Vejamos um exemplo:</p>
<table>
<thead>
<tr class="header">
<th>Valor Posicional</th>
<th>100</th>
<th>10</th>
<th>1</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>Algarismo</td>
<td>2</td>
<td>0</td>
<td>0</td>
</tr>
</tbody>
</table>
<p>Que 200 é 200, todo mundo já sabe. Mas... Porque 200 é 200? Simples:</p>
<p>2 x <strong><em>100</em></strong> + 0 x <strong><em>10</em></strong> + 0 x <strong><em>1</em></strong> = 200</p>
<p>Ou seja: A cada vez que &quot;pulamos&quot; para a direita para analisar o próximo número inserido no algarismo, este terá valor 10x maior do que o anterior.</p>
<p>E isto porque... Estamos no sistema de <strong><em>base 10</em></strong>, claro.</p>
<p>Vamos a mais um exemplo?</p>
<table>
<thead>
<tr class="header">
<th>Valor Posicional</th>
<th>100</th>
<th>10</th>
<th>1</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>Algarismo</td>
<td>9</td>
<td>9</td>
<td>9</td>
</tr>
</tbody>
</table>
<p>9 x <strong><em>100</em></strong> + 9 x <strong><em>10</em></strong> + 9 x <strong><em>1</em></strong> = 900 + 90 + 9 = 999</p>
<h2 id="o-sistema-binário">O Sistema Binário</h2>
<p>Você já deve saber a famosa história de que os dispositivos digitais compreendem através do sistema binário, por conta da natureza binária da informação (Presença ou ausência de corrente, sinal, etc). E... O que muda do sistema binário para o decimal?</p>
<p>Apenas que o fator multiplicador do valor posicional deixa de ser 10, para se tornar 2.</p>
<p>Vamos a um exemplo?</p>
<table>
<thead>
<tr class="header">
<th>Valor Posicional</th>
<th>4</th>
<th>2</th>
<th>1</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>Algarismo</td>
<td>1</td>
<td>1</td>
<td>1</td>
</tr>
</tbody>
</table>
<p>1 x <strong><em>4</em></strong> + 1 x <strong><em>2</em></strong> + 1 x <strong><em>1</em></strong> = 4 + 2 + 1 = 7</p>
<p>Foi tão rápido, mas acabamos de fazer a nossa <strong><em>primeira conversão</em></strong> de um algarismo do sistema binário para o decimal!</p>
<p><strong><em>111</em></strong> (binário) = <strong><em>7</em></strong> (decimal)</p>
<h3 id="exercícios">Exercícios:</h3>
<p>Converta os seguintes números do sistema binário para o decimal:</p>
<p><strong><em>a</em></strong>: 1111 <strong><em>b</em></strong>: 110 <strong><em>c</em></strong>: 01111111</p>
<h3 id="respostas">Respostas:</h3>
<p><strong><em>a</em></strong>.</p>
<table>
<thead>
<tr class="header">
<th>Valor Posicional</th>
<th>8</th>
<th>4</th>
<th>2</th>
<th>1</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>Algarismo</td>
<td>1</td>
<td>1</td>
<td>1</td>
<td>1</td>
</tr>
</tbody>
</table>
<p><strong><em>1111</em></strong> (binário) = <strong><em>15</em></strong> (decimal)</p>
<p><strong><em>b</em></strong>.</p>
<table>
<thead>
<tr class="header">
<th>Valor Posicional</th>
<th>4</th>
<th>2</th>
<th>1</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>Algarismo</td>
<td>1</td>
<td>1</td>
<td>0</td>
</tr>
</tbody>
</table>
<p><strong><em>110</em></strong> (binário) = <strong><em>6</em></strong> (decimal)</p>
<p><strong><em>c</em></strong>.</p>
<table>
<thead>
<tr class="header">
<th>Valor Posicional</th>
<th>128</th>
<th>64</th>
<th>32</th>
<th>16</th>
<th>8</th>
<th>4</th>
<th>2</th>
<th>1</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>Algarismo</td>
<td>0</td>
<td>1</td>
<td>1</td>
<td>1</td>
<td>1</td>
<td>1</td>
<td>1</td>
<td>1</td>
</tr>
</tbody>
</table>
<p><strong><em>01111111</em></strong> (binário) = <strong><em>127</em></strong> (decimal)</p>
<h2 id="o-sistema-hexadecimal">O Sistema Hexadecimal</h2>
<p>Este sistema de numeração (Base 16)também é muito utilizado em Computação, para diversas aplicações. E sabe o motivo?</p>
<p>Ele possui a capacidade de representar códigos binários muito grandes de modo mais legível. Isto se deve a um &quot;truque&quot; matemático: Um conjunto de 4 dígitos binários equivalem, sem perda de interpretação, a um dígito hexadecimal.</p>
<p>Você deve ter em mente a tabela que relaciona os grupos binários com seus respectivos dígitos hexadecimais. Mas fique tranquilo(a). Ela está logo abaixo:</p>
<table>
<thead>
<tr class="header">
<th>Binário</th>
<th>Hexadecimal</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>0000</td>
<td>0</td>
</tr>
<tr class="even">
<td>0001</td>
<td>1</td>
</tr>
<tr class="odd">
<td>0010</td>
<td>2</td>
</tr>
<tr class="even">
<td>0011</td>
<td>3</td>
</tr>
<tr class="odd">
<td>0100</td>
<td>4</td>
</tr>
<tr class="even">
<td>0101</td>
<td>5</td>
</tr>
<tr class="odd">
<td>0110</td>
<td>6</td>
</tr>
<tr class="even">
<td>0111</td>
<td>7</td>
</tr>
<tr class="odd">
<td>1000</td>
<td>8</td>
</tr>
<tr class="even">
<td>1001</td>
<td>9</td>
</tr>
<tr class="odd">
<td>1010</td>
<td>A</td>
</tr>
<tr class="even">
<td>1011</td>
<td>B</td>
</tr>
<tr class="odd">
<td>1100</td>
<td>C</td>
</tr>
<tr class="even">
<td>1101</td>
<td>D</td>
</tr>
<tr class="odd">
<td>1110</td>
<td>E</td>
</tr>
<tr class="even">
<td>1111</td>
<td>F</td>
</tr>
</tbody>
</table>
<p>A coisa é mais intuitiva do que parece. Vejamos na prática uma conversão de um número binário para hexadecimal:</p>
<table>
<thead>
<tr class="header">
<th>Binário</th>
<th>1010</th>
<th>1010</th>
<th>1100</th>
<th>1101</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>Hexadecimal</td>
<td>A</td>
<td>A</td>
<td>C</td>
<td>D</td>
</tr>
</tbody>
</table>
<p>Simples assim.</p>
<h3 id="exercício">Exercício:</h3>
<p>Converte esse endereço MAC para binário pra mim, por favor:</p>
<p><strong>00:19:B9:FB:E2:58</strong></p>
<h3 id="resposta">Resposta:</h3>
<p>Você vai notar que, uma vez sabendo o &quot;truque&quot; matemático, tudo é muito simples. Veja:</p>
<table>
<thead>
<tr class="header">
<th>Endereço MAC (Hexadecimal)</th>
<th>0</th>
<th>0</th>
<th>1</th>
<th>9</th>
<th>B</th>
<th>9</th>
<th>F</th>
<th>B</th>
<th>E</th>
<th>2</th>
<th>5</th>
<th>8</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>Binário</td>
<td>0000</td>
<td>0000</td>
<td>0001</td>
<td>1001</td>
<td>1011</td>
<td>1001</td>
<td>1111</td>
<td>1011</td>
<td>1110</td>
<td>0010</td>
<td>0101</td>
<td>1000</td>
</tr>
</tbody>
</table>
<h2 id="concluindo...">Concluindo...</h2>
<p>Bom, espero que este pequeno tutorial sobre os sistemas de numeração tenham sido úteis para você. Se você gostou do conteúdo, não deixe de compartilhar com seus amigos e colegas de trabalho! Forte abraço!</p>

> ***Fernando Gomes*** é fundador do PTDN e um jovem de 24 anos apaixonado por Tecnologia da Informação e pelo Ensino. Atualmente é Instrutor de TI  do projeto Naves do Conhecimento no Rio de Janeiro. Nas horas vagas, gosta de passar o tempo ao lado da família e da namorada.




