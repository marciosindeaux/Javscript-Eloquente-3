### Introdução

"Nós pensamos qure criamos os sistemas para nossos propositos. Nós acreditamos que estamos fazendo deles a nossa propria imagem...Mas os computadores não são como nós. Eles são apenas a projeção de uma pequena parte de nós mesmos: a parte que se dedica a lógica, ordem, regra e clareza."
-  Ellen Ullman, Close to the Machine: Technophilia and its Discontents (Adaptado)

![](https://github.com/marciosindeaux/Javscript-Eloquente-3/blob/introducao/Introdu%C3%A7%C3%A3o/statics/chapter_picture_00.jpg?raw=true)

Este livro é sobre passar instruções para um computador. Computadores são tão comuns quanto ferramentas hoje em dia, mas eles são um pouco masi complexos e fazer eles executarem as tarefas que voce quer nem sempre é facil.

Se a tarefa que voce vai executar no seu computador for fomum , como mostrar seus emails, ou calcular algo, voce pode simplesmente abrir o programa apropriado e realizar tal ação. Porem, se for algo unico, provavelmente não haverá aplicativo para isso.

É ai que entra a programação. Programação é o ato de construir programas, isto é, um conjunto de instruçãoes que vão dizer ao computador o que fazer. Porque computadores são idiotas, e a programação quase sempre é tediosa,e as vezes frustrante.

Mas, se voce pode superar esse fato, a programação pode ser recompensadora. Ela permite que voce faça coisas em segundo , que demorariam horas, caso fizesse de um jeito convencional. Alem de ser uma ótima forma de exercitar o raciocinio lógico.

A programação é feita com uma Liguagem de programação. Uma linguagem de programação é um idioma (asssim como o inglês e portugues) criado artificialmente para instruir os computadores. É muito interessante como a maneira mais eficaz para se comunicar com um computador se baseia muito como nos comunicamos uns com os outros. Como idiomas humanos, as linguagens de programação permitem que palavras e frases sejam combinadaas de novas formas, sendo assim possivel se expressar de formas diferentes.

A algum tempo, interfaces baseadas em linguagens, como BASIC e propt DOS, nas decadas de 1980 e 1990, eram o principal meio de interação com o computador. Com o tempo , esses prompts foram substituidas por interfaces visuais, que são mais intuitivas porem te dão menos liberde. Se voce procurar, as linguagens ainda vão estar lá. Uma dessas linguagens é o JavaScript, que é incorportada em todos os navegadores web modernos, e portanto, está disponivel em quase todos os dispositivos.

Esse livro vai tentar fazer com que voce se familiarizem com essa linguagem, para que voce possa fazer coisas uteis e divertidas com ela.

### Na Programação

Alem de introduzir o javascript, nesse livro vamos introduzir os principios básicos da programação. A programação em si não é dificil. As regras fundamentais são simples e faceis, mas os programas construidos com elas tendem a ser complexos e gerar suas proprias regras. Dessa forma voce vai estar construindo seu proprio labirinto, e as vezes pode se perder nele.

Haverá momentos em que ler esse livro  vai ser terrivelmente frustrante. Se voce for novo em programação vai haver muito material para digerir. Será necessário criatividade e interdiciplinaridade para que entenda e faça conexões adicionais.

Cabe a voce fazer o esforço necessário. Quando voce estiver se esforçando para seguir o livro, não se julgue, voce está bem e precisa ter isso em mente. Faça um apequena pausa, releia outra parte do material e certifique-se de entender os exemplos e exercicios. Aprender é um trabalho arduo, mas tudo que que aprende é seu , e tornará outros aprendizados mais faceis.

"Quando a ação deixar de ser lucrativa, reúna informações; quando a informação se tornar inútil, durma". 
- Ursula K. Le Guin, The Left Hand of Darkness

Um programa é muitas coisas. É um pedaço de texto digitado por um programador, é a força motriz de um computador, são dados na memória do computador. Analogias que tentam comparar programas a objetos com o qual estamos acostumados a lidar tendem a falhar. Uma analogia superficialmente correta é que um programa é uma máquina: Muitas partes estãop envolvidas,e para tudo funcionar, temos que considerar as maneiras pelas quais as partes se conectam e contribuem para a operação como um todo.

Um computador é uma máquina física que hospedas essas máquinas imaginárias. Os proprios computadores só podem fazer coisas simples. A razão pelo qual são uteis é porque fazem essas coisas simples em velocidades assustadoramente altas. Um programa pode combinar varias dessas ações simples para realizar procedimentos extremamente complexos e complicados.

Um programa é uma construção do nosso pensamento. Não tem custo e nem peso, porem pode crescer facimente.

Mas não importa o tamanho ou a complexidade do programa. Caso ele cresça desenfreadamente, vai acabar confundindo seu proprio criador. Manter os programas sob controle, para que não cresçam sem controle é um dos principais desafios dos programadores. Qaund um proframa funciona, é lindo, A ate da programação é a habilidade de controlar a complexidadde dos programas.

Alguns programadores acreditam que essa complexidade é melhor gerenciada usando um conjunto de téquinacas conhecidas eem seus programas. Eles proporam regras estritas (as "melhores praticas") descrevendo as formas que os programas devem ter e fazendo com que els cuidadosamente permaneçam dentro de uma zona de segurança.

Isso não é apenas chato, como é ineficiente. Novos problemas exigem novas soluções. As areas da programação são vastas, jovens e ainda estão no processo de evolução, e é variado o suficiente para ter abordagens diferentes. Existem muitos esrros terriveis de se cometer no design de programas, e voce deve ir em frente, comete-los e compreendelos. A noção de como pe um bom programa é delenvolvida na pratica, e não aprendida com uma lista de regras.

### Proque a linguagem importa ?

No inicio, quando não havima linguagens de programalção, programas eram basicamente algo assim:

```
00110001 00000000 00000000
00110001 00000001 00000001
00110011 00000001 00000010
01010001 00001011 00000010
00100010 00000010 00001000
01000011 00000001 00000000
01000001 00000001 00000001
00010000 00000010 00000000
01100010 00000000 00000000
```

Esse é um programa para adicionar numeros de 1 até 10 e colocar no terminal o resultado: 1 + 2 + ... + 10 = 55. Ele poderia ser executado em uma simples e hipotética máquina. Para programar os primeiros computadores, era necessário colocar grandes conjuntos de interruptores na posição correta, ou fazer furos em titras de papelão e alimentar o computador com aquilo. Voce provavelmente consegue imaginar o qunto esse trabalho era tedioso e sujeito a erros. Até mesmo escrever programas simples exigia uita experiencia e disciplina. O programas mais complexos eram quase impossiveis de serem feitos.

É claro que inserir manualmente eses padrões misteriosos de bits (zeros e uns) deu ao programador uma profunda sensação de ser um grande mago poderoso. E ssi temq ue valer a pena em termos de satisfação no trabalho.

Cada linha previamente programada ´continha uma unica instrução. Ela pode ser escrita dessa forma:
```
1. Armazene o numero 0 na posição da memoria numero 0
2. Armazene o numero 1 na posição da memoria numero 1
3. Armazene o valor da memoria da posição 1 , na posição de memória 2.
4.Subtraia o numero 11 dao vavalor da memoria na posição 2
5.Se o valor da memoria na posição 2 for 0 vá até a instrução 9
6. Adicione o valor da memoria na posição 1 , para a posição 0
7. Some 1 ao valor da memória na posição 1 e adicione.
8.Va até a instrução 3
9.Mostre o resultado armazenado na memória de posição 0
```

Embora agora as coisas pareçam um pouquinho masi claro que aquele monte de bits, as coisas ainda parecem um pouco obscuras. O uso de nomes , ao invez de numeros pode ajudar.

```
"total" vale 0
"contador" vale 1
[repita]
"compare" tem valor de "contador"
subtraia 11 de "compare"
SE "compare" for 0, vá até [fim]
adicione "count" em "total"
adicione 1 em "count"
Vá até [repita]
[fim]
mostre "total"
```

Voce consegue ver como esse programa funciona nesse ponto? A s duas primeiras linhas colocam na memória os valores iniciais: `total` será usando para construir o resoltado do calculo e `contador` manterá a contagem e mostrará para qual numero estamos olhando. As linhas que usam `compare` são provavelmente a mais extranhas. O programa quer ver se `count` é igual a 11 para decidir se para de funcionar ou não. Como nossa máquina hipotética é rmuito primitiva, ela só pode testar se o numero é zero e tomar uma decisão a partir disso. Então ela usa o espaço da memória, chamado de `compare`, para verificar o valor de `compare` - 11, e toma uma decisão em cima disso. As proximas 2 linhas adicionam o valor de `contador` em `total` e aumenta a contagem em 1 toda vez que o programa decidir que o `contador` ainda não é 11.

Esse é o mesmo programa em JavaScript: 

```js
let total = 0, contador = 1;
while (contador <= 10) {
  total += contador;
  contador += 1;
}
console.log(total);
// → 55
```

A versão acima nos fornece mais algumas vantagens em relação a anterior. Mais importante: não há necessidade de especificar como quer3emos que o programa salte de um passo para outro. A construção do while já cuida disso. Ele continua executando o código entre colchetes (bloco de codigo) enquanto a condição dada, `contador <= 10` (`contador` menor ou igual a 10), for mantida. Não precisamos mais criar um valor temporário para compara-lo com 0, porque isso era apenas um detalhe desinteressnate. Parte do poder das linguagens de programação é cuidar de coisas chatas e desinteressantes.

No final do programa, depois do fim do bloco do `while`, a operação `console.log` é usada para msotrar os resultados.

Se hipoteticamente tivessemos algo que gerasse todos os numeros entre 2 numeros (tal como uma função `range`) e algo que somasse um conjunto de numero (tal como uma função `sum`), a aparencia do programa seria algo assim:

```js
console.log(sum(range(1, 10)));
```

A moral do problema é que mesmo um simples programa pode ser expresso de forma loga ou curta, legivel ou ilegivel. A primeira versão do programa era completamente obscura, enquanto a ultima é quase uma frase em inglês : mostre a soma dos numeros entre 1 e 10 (incluindo eles). Veremos mais a frente como implementar tais operações.

Uma boa Linguagem de programação ajuda o programador, permitindo que ele mostre as alçoes que o computador deve executar em um alto nivel. Ela ajuda a omitir detalhes, fornece blocos de construção conveniente e até permite que voce defina seus proprios blocos.
