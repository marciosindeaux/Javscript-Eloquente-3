# Valores, Tipos e Operadores

> Abaixo da superfície da máquina, o programa se move. Sem esforço, ele se expande e se contrai. Em grande harmonia, os elétrons se espalham e se reagrupam. As formas no monitor são apenas ondulações na água. A essência permanece invisível abaixo
> - Master Yuan-Ma, The Book of Programming

![](https://github.com/marciosindeaux/Javscript-Eloquente-3/blob/capitulo_01/Parte%2001%20-%20Linguagem/Capitulo%2001/static/chapter_picture_1.jpg?raw=true)

Dentro de um computador, tudo são dados. Você pode ler dados, modificar dados e até criar  dados, mas o que não é dado, não pode ser mencionado. Todos esses dados são guardados como uma grande sequência de bits, portanto são fundamentalmente semelhantes.
 
Bits são qualquer tipo de coisa de dois valores, geralmente descritos como zeros e uns. Dentro do computador eles assumem a forma como Alta ou baixa corrente elétrica, ou sinal forte, ou fraco, etc. Qualquer informação pode ser resumida a zeros e uns, portanto podem ser representados como bits.
 
Como exemplo, vamos expressar o número 13 como bits. Essa ação funciona exatamente igual nos números decimais, mas ao invés de termos 10 dígitos diferentes, temos apenas 2. Quando mudamos de unidade para dezena, ou de dezena para centena, multiplicamos sempre por 10, no caso dos binários é a mesma coisa, porem a multiplicação ocorre por 2 (afinal, é apenas 2 símbolos). Veja o exemplo abaixo:


|0|0|0|0|1|1|0|1|
|-|-|-|-|-|-|-|-|
|128|64|32|16|8|4|2|1|


O número binário que representa 13 é 0001101. Se você observar bem, os dígitos diferentes de 0, 8, 4 e 1, se somados dão  13.

## Valores

Imagine um oceano de bits. Um computador comum possui mais de 30 bilhões de bits em sua memória volátil (RAM e Cache). Em memórias não voláteis (HD ou SSD), temos uma ordem de magnitude muito maior.
 
Para estarmos aptos a trabalhar com tantos dados assim, temos que separa-los em partes que representam informações. No ambiente JavaScript, essas partes são chamadas de valores. Embora os valores sejam feitos de bits, eles desempenham diferentes funções. Cada valor tem um tipo que determina sua função. Alguns valores são números, outros são funções, outros são até mesmo pedaços de textos,, etc.
 
Para criar um valor, você deve apenas dar um nome a ele. Isso é muito conveniente, pois você não precisa ir atrás de memória e gastar operações com isso. Você apenas vai chamar um e, uau, você tem ele. Claro que esses valores não são criados do nada. Cada valor deve ser armazenado em algum lugar e, se você quiser uma quantidade gigantesca deles ao mesmo tempo, pode ser que fique sem memória. Felizmente isso é um problema apenas e você precisar dele simultaneamente. Assim que você não usar mais um valor, ele vai se dissipar e a memória ficará vaga novamente para a criação de novos valores.
 
Esse capitulo vai apresentar elementos atômicos dos programas JavaScript, ou seja, os TIPOS de valores e os operadores que podem atuar com os valores.

## Number (Tipos Numericos)

Valores do tipo Number são, obviamente números. Nos JavaScript eles são escritos da seguinte forma:
 
```js
13
```
 
Use isso em um programa e magicamente o número 13 em bits vai passar a existir na memória do computador.
 
O javascript usa um número de 64 bits para representar os valores do tipo Number. Se em uma escala decimal, dizemos que um número tem n dígitos, então ele pode ser representado por 10<sup>n</sup>. De forma similar podemos representar 64 bits por 2<sup>64</sup> números diferentes que podem ser representados. Isso é aproximadamente 18 quintilhões, é bastante coisa.
 
Antigamente, a memória dos computadores era muito pequena, e as pessoas costumavam usar 8 ou 16 bits para representar um número. Era fácil acidentalmente acontecer o que chamamos de Overflow, quando a informação é maior que o espaço que guardaria ela (quando você quer viajar com muitas roupas, mas sua mala é pequena). Hoje, mesmo os computadores de bolso tem muita memória, então você está livre pata usar blocos de 64 bits, e não vai precisar se preocupar com overflow, mesmo lidando com números quase astronômicos.
 
No entanto, nem todos os números inteiros menores que 10 quintilhões cabem em um Number. Um bit é usando para indicar o sinal do número. Um problema maior é que números não inteiros também são representados, então alguns bits são usados para armazenar a posição do ponto decimal.O número inteiro máximo que pode ser usado é 9 quatrilhões. Mesmo assim, o tipo Number ainda é grande.
 
Números Reais são escritos usando um ponto:
 
```js
9.25
```
 
Para números muito grandes ou muito pequenos no JavaScript, você pode usar na notação cientifica adicionando um "e" (para o expoente) seguido do número do expoente.
 
```js
2.998e8
```
 
Isso seria a mesma coisa que 2.998x10<sup>8</sup> = 299800000
 
Cálculos com números inteiros menores que os 9 quatrilhões mencionados acima são sempre precisos. Infelizmente, cálculos com números reais não são assim. Assim como π (pi) não pode ser expresso com precisão por um número finito de dígitos decimais, muitos números perdem alguma precisão quando apenas 64 bits estão disponíveis para armazená-los. Isso é uma pena, mas causa problemas práticos apenas em situações específicas. O importante é estar ciente disso e tratar os números digitais fracionários como aproximações, não como valores precisos.

## Arintimética

A principal coisa que voce pode fazer com numeros é realizar operações arintiméticas com eles. Operações como adição e multiplicação de 2 Numeros para gerar um terceiro. Voce pode fazer em JavaScript mais ou menos assim:

```js
100 + 4 * 11
```

Os simbolos + e * são chamados de operadores. O primeiro significa adição e o simbolo logo em seguida significa multiplicação. Coloque um operador entre 2 valores e voce produzirá um terceiro.

Mas no exemplo acima, voce sabe se a multiplicação ocorre primeiro ? Ou será que a soma ocorre primeiro ? Como voce deve ter suspeitado, a multiplicação ocorre primeiro, mas como na matemática, voce pode mudar a ordem das coisas adicionando parenteses.

```js
(100 + 4) * 11
```

Para subtração o operador usado é -, e para divisão , o usado é /.

Quando muitos operadores aparecem juntos sem parenteses, a ordem de precedencia que são aplcadas as operações é determinada pela precedencia dos operadores. O operador / e o * tem a mesma ordem de precedencia. Logo abaixo, os operadores + e - possuem também a mesma ordem de precedencia , porem possuem menos ordem que mjultiplicação e divisão. Como foi mostrado, a multiplicação vam antes da soma. Quando varios operadores da mesma ordem de precedencia aprecem juntos uns dos outros como em 1 -2 + 1, eles são aplicados da esquerda para a direita: (1 - 2) + 1.

Mas as regras de precedencia não são algo no qual voce deveria se preocupar. Em caso de duvidas, adicione parenteses.

Existe mais um operador aritimético, que voce não reconhecerá imediatamente. O simbolo de % é usado para indicar "resto da divisão" de um numero em relação ao outro. Por exemplo 312%100 = 12. A precedencia do operador de modulo é a mesma que a divisão e a multiplicação. Voce verá frequentemente esse operador.
