# Introdução

> "Nós pensamos que criamos os sistemas para nossos propósitos. Nós acreditamos que estamos fazendo deles a nossa própria imagem...Mas os computadores não são como nós. Eles são apenas a projeção de uma pequena parte de nós mesmos: a parte que se dedica a lógica, ordem, regra e clareza."
> -  Ellen Ullman, Close to the Machine: Technophilia and its Discontents (Adaptado)

![](https://github.com/marciosindeaux/Javscript-Eloquente-3/blob/introducao/Introdu%C3%A7%C3%A3o/static/chapter_picture_00.jpg?raw=true)

Este livro é sobre passar instruções para um computador. Computadores são tão comuns quanto ferramentas hoje em dia, mas eles são um pouco mais complexos e fazer eles executarem as tarefas que você quer nem sempre é fácil.

Se a tarefa que você vai executar no seu computador for comum, como mostrar seus e-mails, ou calcular algo, você pode simplesmente abrir o programa apropriado e realizar tal ação. Porem, se for algo único, provavelmente não haverá aplicativo para isso.

É aí que entra a programação. Programação é o ato de construir programas, isto é, um conjunto de instruções que vão dizer ao computador o que fazer. Porque computadores são idiotas, e a programação quase sempre é tediosa, e às vezes frustrante.

Mas, se você pode superar esse fato, a programação pode ser recompensadora. Ela permite que você faça coisas em segundo, que demorariam horas, caso fizesse de um jeito convencional. Além de ser uma ótima forma de exercitar o raciocínio lógico.

A programação é feita com uma Linguagem de programação. Uma linguagem de programação é um idioma (assim como o inglês e português) criado artificialmente para instruir os computadores. É muito interessante como a maneira mais eficaz para se comunicar com um computador se baseia muito como nos comunicamos uns com os outros. Como idiomas humanos, as linguagens de programação permitem que palavras e frases sejam combinadas de novas formas, sendo assim possível se expressar de formas diferentes.

A algum tempo, interfaces baseadas em linguagens, como BASIC e prompt DOS, nas décadas de 1980 e 1990, eram o principal meio de interação com o computador. Com o tempo, esses prompts foram substituídos por interfaces visuais, que são mais intuitivas porem te dão menos liberdade. Se você procurar, as linguagens ainda vão estar lá. Uma dessas linguagens é o JavaScript, que é incorporada em todos os navegadoras web modernos, portanto, está disponível em quase todos os dispositivos.

Esse livro vai tentar fazer com que você se familiarizem com essa linguagem, para que possa fazer coisas uteis e divertidas com ela.

## Na Programação

Além de introduzir o JavaScript, nesse livro vamos introduzir os princípios básicos da programação. A programação  não é difícil. As regras fundamentais são simples e fáceis, mas os programas construídos com elas tendem a ser complexos e gerar suas próprias regras. Dessa forma você vai estar construindo seu próprio labirinto, e as vezes pode se perder nele.

Haverá momentos em que ler esse livro  vai ser terrivelmente frustrante. Se você for novo em programação vai haver muito material para digerir. Será necessária criatividade e interdisciplinaridade para que entenda e faça conexões adicionais.

Cabe a você fazer o esforço necessário. Quando você estiver se esforçando para seguir o livro, não se julgue, você está bem e precisa ter isso em mente. Faça um apequena pausa, releia outra parte do material e certifique-se de entender os exemplos e exercícios. Aprender é um trabalho árduo, mas tudo que você aprende é seu, e tornará outros aprendizados mais fáceis.

> Quando a ação deixar de ser lucrativa, reúna informações; quando a informação se tornar inútil, durma". 
> - Ursula K. Le Guin, The Left Hand of Darkness

Um programa é muitas coisas. É um pedaço de texto digitado por um programador, é a força motriz de um computador, são dados na memória do computador. Analogias que tentam comparar programas a objetos com o qual estamos acostumados a lidar tendem a falhar. Uma analogia superficialmente correta é que um programa é uma máquina: muitas partes estão envolvidas, e para tudo funcionar, temos que considerar as maneiras pelas quais as partes se conectam e contribuem para a operação na totalidade.

Um computador é uma máquina física que hospedas essas máquinas imaginárias. Os próprios computadores só podem fazer coisas simples. A razão pelo qual são uteis é porque fazem essas coisas simples em velocidades assustadoramente altas. Um programa pode combinar varias dessas ações simples para realizar procedimentos extremamente complexos e complicados.

Um programa é uma construção do nosso pensamento. Não tem custo e nem peso, porem pode crescer facilmente.

Mas não importa o tamanho ou a complexidade do programa. Caso ele cresça desenfreadamente, vai acabar confundindo seu próprio criador. Manter os programas sob controle, para que não cresçam sem controle é um dos principais desafios dos programadores. Quando um programa funciona, é lindo, A ate da programação é a habilidade de controlar a complexidade dos programas.

Alguns programadores acreditam que essa complexidade é melhor gerenciada usando um conjunto de técnicas conhecidas em seus programas. Eles propuseram regras estritas (as "melhores praticas") descrevendo as formas que os programas devem ter e fazendo com que eles cuidadosamente permaneçam dentro de uma zona de segurança.

Isso não é apenas chato, como é ineficiente. Novos problemas exigem novas soluções. As áreas da programação são vastas, jovens e ainda estão no processo de evolução, e é variado o suficiente para ter abordagens diferentes. Existem muitos erros terríveis de se cometer no design de programas, e você deve ir em frente, comete-los e compreendê-los. A noção de como um bom programa é desenvolvido na prática, e não aprendida com uma lista de regras.

## Porque a linguagem importa?

No início, quando não haviam linguagens de programação, programas eram basicamente algo assim:

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

Esse é um programa para adicionar números de 1 até 10 e colocar no terminal o resultado: 1 + 2 + ... + 10 = 55. Ele poderia ser executado em uma simples e hipotética máquina. Para programar os primeiros computadores, era necessário colocar grandes conjuntos de interruptores na posição correta, ou fazer furos em tiras de papelão e alimentar o computador com aquilo. Você provavelmente consegue imaginar o quanto esse trabalho era tedioso e sujeito a erros. Até mesmo escrever programas simples exigia muita experiencia e disciplina. Os programas mais complexos eram quase impossíveis de serem feitos.

É claro que inserir manualmente esses padrões misteriosos de bits (zeros e uns) deu ao programador uma profunda sensação de ser um grande mago poderoso. E isso tem que valer a pena em termos de satisfação no trabalho.

Cada linha previamente programada continha uma única instrução. Ela pode ser escrita dessa forma:

```
1. Armazene o número 0 na posição da memória numero 0.
2. Armazene o número 1 na posição da memória numero 1.
3. Armazene o valor da memória da posição 1, na posição de memória 2.
4. Subtraia o número 11 do valor da memória na posição 2.
5. Se o valor da memória na posição 2 for 0 vá até à instrução 9.
6. Adicione o valor da memória na posição 1, para a posição 0.
7. Some 1 ao valor da memória na posição 1 e adicione.
8. Vá até a instrução 3.
9. Mostre o resultado armazenado na memória de posição 0.

```

Embora agora as coisas pareçam um pouquinho mais claras que aquele monte de bits, as coisas ainda são um pouco obscuras. O uso de nomes, ao invés de números pode ajudar.

```
"total" vale 0
"contador" vale 1
[repita]
"compare" tem valor de "contador"
subtraia 11 de "compare"
SE "compare" for 0, vá até [fim]
adicione "contador" em "total"
adicione 1 em "contador"
Vá até [repita]
[fim]
mostre "total"
```
Você consegue ver como esse programa funciona nesse ponto? As duas primeiras linhas colocam na memória os valores iniciais: `total` será usando para construir o resultado do cálculo e `contador` manterá a contagem e mostrará para qual numero estamos olhando. As linhas que usam `compare` são provavelmente a mais estranhas. O programa quer ver se `count` é igual a 11 para decidir se para de funcionar ou não. Como nossa máquina hipotética é muito primitiva, ela só pode testar se o número é zero e decidir a partir disso. Então ela usa o espaço da memória, chamado de `compare`, para verificar o valor de `compare` - 11, e decide em cima disso. As próximas 2 linhas adicionam o valor de `contador` em `total` e aumenta a contagem em 1 toda vez que o programa decidir que o `contador` ainda não é 11.

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

A versão acima nos fornece mais algumas vantagens em relação a anterior. Mais importante: não há necessidade de especificar como queremos que o programa salte de um passo para outro. A construção do while já cuida disso. Ele continua executando o código entre colchetes (bloco de código) enquanto a condição dada, `contador <= 10` (`contador` menor ou igual a 10), for mantida. Não precisamos mais criar um valor temporário para compara-lo com 0, porque isso era apenas um detalhe desinteressante. Parte do poder das linguagens de programação é cuidar de coisas chatas e desinteressantes.

No final do programa, depois do fim do bloco do `while`, a operação `console.log` é usada para mostrar os resultados.

Se hipoteticamente tivéssemos algo que gerasse todos os números entre 2 numeros (tal como uma função `range`) e algo que somasse um conjunto de número (tal como uma função `sum`), a aparência do programa seria algo assim:

```js
console.log(sum(range(1, 10)));
```

A moral do problema é que mesmo um simples programa pode ser expresso de forma loga ou curta, legível ou ilegível. A primeira versão do programa era completamente obscura, enquanto a última é quase uma frase em inglês: mostre a soma dos números entre 1 e 10 (incluindo eles). Veremos mais a frente como implementar tais operações.

Uma boa Linguagem de programação ajuda o programador, permitindo que ele mostre as ações que o computador deve executar em um alto nível. Ela ajuda a omitir detalhes, fornece blocos de construção conveniente e até permite que você defina seus próprios blocos.

## O que é o JavaScript ?

JavaScript foi uma linguagem criada em 1995 para criar programas para paginas web no navegador Netscape. A linguagem foi adotada pela maioria dos navegadores visuais. Ele fez com que as aplicações web modernas fossem possíveis: aplicações não qual era possível interagir diretamente sem precisar recarregar a pagina para cada simples ação. JavaScript também é usado em sites mais tradicionais para fornecer interatividade e inteligencia.
 
É importante dizer que JavaScript não tem quase NADA a ver com a linguagem de programação Java. A similaridade do nome é inspirada em considerações de marketing. Quando o JavaScript foi introduzido no mercado, a Linguagem Java estava fortemente comercializada e com grande popularidade. Alguém pensou que fosse uma boa ideia tentar tirar proveito desse sucesso. Agora estamos presos ao nome.
 
Após a adoção do JavaScript fora do Netscape, um documento padrão foi escrito para descrever como a linguagem JavaScript deveria funcionar, de forma que vários softwares que alegavam suportar JavaScript estivesse falado a verdade. Esse documento foi chamado de ECMAScript standard, em homenagem à organização internacional ECMA, que fez a padronização. Na prática, os nomes ECMAScript e JavaScript são sinônimos.
 
Há quem diga coisas terríveis sobre o JavaScript. Muitas dessas coisas são verdade. Quando fui a escrever algo em JavaScript pela primeira vez, rapidamente passei a desprezá-lo. A linguagem aceitava quase tudo que eu digitava, mas interpretava de uma forma completamente diferente do que eu queria. Isso tinha muito a ver com o fato de que eu não ter, na época, ideia do que estava fazendo, é claro, mas há um problema real aqui: o JavaScript é ridiculamente liberal. A ideia por trás desse design era tornar a programação em JavaScript mais fácil para iniciantes. Na verdade, isso dificulta encontrar problemas em seus programas porque o sistema não mostrará para você.
 
Essa flexibilidade também tem suas vantagens. Ela deixa espaço para muitas técnicas que são impossiveis em linguagens mais rígidas. Após aprender a lidar com a linguagem corretamente  e trabalhar com ela por um tempo, aprendi a gostar do JavaScript.
 
Existem várias versões do JavaScript. ECMAScript 3 era a versão amplamente suportada na época da ascensão do JavaScript para o domínio, isso entre 2000 e 2010. Durante esse período, também existia um trabalho em andamento de uma versão 4. Completamente ambiciosa, que planejava uma série de melhorias radicais e extensões para a linguagem. Mudar uma linguagem amplamente usada acabou sendo politicamente difícil, e o trabalho na versão 4 foi abandonado em 2008, gerando assim uma versão 5 muito menos ambiciosa e com pequenas melhorias, que foi lançada em 2009. Apenas em 2015 foi lançado o ECMAScript 6, uma grande atualização com a implementação de algumas ideias planejadas na versão 4. Desde então temos novas atualizações todos os anos.
 
O fato de a linguagem estar evoluindo com o tempo, significa que os navegadores, que rodam essa linguagem precisam estar constantemente atualizados. E se você estiver usando uma versão antiga de um navegador, pode ser que ele não ofereça suporte a todos os recursos. Os designers da linguagem possuem o cuidado de realizar e implementar mudanças sem quebrar aplicações já existentes. Nesse livro, vamos usar a versão do JavaScript lançada em 2017.
 
Navegadores não são a única plataforma que usam JavaScript. Alguns bancos de dados como MongoDB e CouchDB usam JavaScript como linguagem de consulta. Muitas plataformas para desktop e servidores geram um grande ambiente para programação JavaScript fora do navegador, sendo o mais notável deles o Node.js.

## Codigo, e o que fazer com ele

Código é o texto que compõe os programas. A maioria dos capítulos desse livro contém uma grande quantidade de código. Eu acredito que ler e escrever código são partes indispensáveis ao aprendizado da programação. Tente apenas não olhar os exemplos, leia eles atentamente e entenda eles. Isso pode parecer lento e confuso inicialmente, mas eu prometo que rapidamente você vai pegar isso. A mesma coisa vale para os exercícios. Não assuma que você entende os exercícios até que tenha realmente escrito a solução.
 
Eu recomendo que você execute suas soluções em um interpretador JavaScript mais atual. Dessa forma, você receberá um feedback imediato sobre se o que está fazendo está funcionando e, espero, você ficará tentado a experimentar e ir além dos exercícios.
 
Se você estiver lendo esse livro no seu navegador, poderá editar e rodar todos os exemplos dos programas apenas clicando neles.
 
Se você deseja rodar alguns desses programas fora do site desse livro, alguns cuidados são necessários. Muitos exemplos são independentes e devem funcionar normalmente em qualquer ambiente JavaScript. Mas o código nos capítulos posteriores geralmente é escrito para um ambiente específico (o navegador ou Node.js) e só pode ser executado lá. Além disso, muitos capítulos definem programas maiores, e as partes do código que aparecem neles dependem uma das outras ou de arquivos externos. A [sandbox](https://eloquentjavascript.net/code/)  do site do livro fornece arquivos Zip contendo scripts e aquivos de dados necessários para executar o código de um determinado capítulo.

## Visão geral do livro
Esse livro é dividido em 3 partes: os primeiros 12 capítulos (que abordam a linguagem JavaScript), os 7 capítulos seguintes (que abordam sobre navegadoras web) e os 2 últimos capítulos (que são dedicados a Node.js e outros ambientes de desenvolvimento JavaScript).
 
Ao decorrer desse livro, existem 5 capítulos de projeto, que descrevem programas maiores para lhe dar uma ideia do que é programar de verdade. Nós trabalharemos com um [robô de entregas](), uma [linguagem de programação](), um [jogo de plataforma](), um [programa de pintura em pixels]() e um [website dinâmico]().
 
Da parte do livro que aborda a linguagem JavaScript, os quatro primeiros capítulos vão introduzir estruturas básicas na linguagem. Estruturas de [controle]() (como a palavra while que você viu acima), [funções]() e [estruturas de dados]()  serão abordados. Depois deles, você já vai estar apto a escrever programas básicos. Nos capítulos [5]() e [6]() serão introduzidas técnicas para uso de funções e objetos para escrever códigos mais abstratos e manter as complexidades sobre controle.
 
Depois disso, virá o [primeiro capitulo e desafio](). Após, a explicação sobre a linguagem continuará, com capítulos de [tratamento de erros e correções de bugs](), [expressões regulares]() (uma importante ferramenta para trabalhar com erro), [modularidade]() (outro mecanismo de defesa contra complexidade) e [programação assíncrona]() (para lidar com eventos que demandam mais tempo). Por fim, surgirá o [segundo capitulo de desafio](), concluindo assim a primeira parte do livro.
 
Na segunda parte, do capítulo [13]() ao [19]() descreve as ferramentas que o JavaScript do navegador tem acesso. Você vai aprender a mostrar coisas em tela (Capítulos [14]() e [19]()), responder aos inputs do usuário ([Capitulo 15]()), e se comunicar usando a internet ([Capitulo 18]()). Existem novamente 2 capítulos de projeto nessa parte.
 
Depois disso, na terceira parte, será descrito no [Capitulo 20]() a ferramenta Node.js, e no [Capitulo 21]() será construído um pequeno website com a ferramenta. 

## Tipografia e convenções

Nesse livro, textos escritos com uma fonte `monoespaçadas` representam elementos de um programa. Algumas vezes esses elementos representam fragmentos de um programa e outras vezes representam um programa completo. Os programas (dos quais você já viu alguns) são escritos da seguinte forma:

```js
function factorial(n) {
  if (n == 0) {
    return 1;
  } else {
    return factorial(n - 1) * n;
  }
}
```

Para mostrar a saída esperada de um programa, usaremos a notação `// -> `. Apos esse simbolo vira a saída esperada.

```js
console.log(2*5)
// -> 10
```

Boa Sorte!
