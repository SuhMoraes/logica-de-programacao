<h1 align="center">Lógica de Programação </h1>

# Indíce

 - [Introdução](#-Introdução)
 - [Criando um programa](#Criando-um-programa])
 - [Atribuição do tipo inteiro](#Atribuição-do-tipo-inteiro)
 - [Atribuição do tipo Real](#Atribuição-do-tipo-Real)

 - [Concatenação](#Concatenação)
 - [Comando Input - Entrada de Dados](#Comando-Input-entrada-de-dados)

 - [Concatenação](#-Concatenação)
 - [Comando Input - Entrada de Dados](#Comando-Input-Entrada-de-Dados)

 - [Aprendendo Média](#Aprendendo-Média)
 - [Calculando juros composto](#Calculando-juros-composto)
 <br> 
 <br> 
 <hr>
 
<h2>Introdução</h2>

<h3>Algoritmo
<br>
 O algoritmo representa uma "sequência finita de ações executáveis que visam obter uma solução para um determinado tipo de problema."
    Representam passos necessários para realizar uma tarefa.
<br>
    
   O computador é bom em duas coisas: executar muitas tarefas  rapidamente e armazenar muitos dados. Porém não possui nenhuma experiência prévia, pois ele é programado para executar tarefas.

 Toda parte lógica de um software, toda parte de tomada de decisão é feita pelo programador. É dele o papel de mapear todas as possibilidades e instruir o computador dependendo de cada possibilidade.</h3>
 
 <br> 
 <br> 
<h1> Criando um programa</h1>
 <br> 
<h2>Comando -Output -> Saída de Dados</h2>
 <hr>

 
 Todo algoritmo começa com bloco início.
  ~~~
  inicio {
    escreva("Olá, meu primeiro código!");
  }
 ~~~
  As chaves  ```{ }```funciona como uma delimitação do código. O conteúdo somente será executado se estiver dentro das chaves.

  O comando ```escreva``` recebe o que  está entre parênteses```()```, chamado de parametro (seria a informação para o programa funcionar).


  Aspas ```" "```, é utilizado para que os textos (String), sejam lidos no programa.

  O ponto e vígula ```;```, exigência de sintaxe do programa.

  Observação: As linhas vazias são ignoradas na execução do código.
  Exemplo:

   ~~~
  inicio {






    escreva      ("Olá, meu primeiro código!");




  }
 ~~~

  
  >O programa é executado de cima para baixo, da esquerda para direia.

  <br>
  <br>

  <h3>Variável</h3>

  <p> Variável é uma unidade básica de armazenamento de informações dentro de um computador. A variável é capaz de armazenar uma informação na memória para que você possa recuperara informação depois.</p>

  <strong>Como funciona uma variável?</strong>
  <p>Toda variável tem um tipo de dado associado, e esse tipo de dado é o tipo de informação usado no código Exemplo:
  Tipo Inteiro: São usados para números inteiros, sem casas decimais.
  String: Cadeia de caractere definido por aspas duplas.
  Tipo Real: Para número com casas decimais.
 </p>

  <br>
  <br>
 
 
 
 <h2>Atribuição do tipo inteiro</h2>
 <hr>
  
 
 <p>O tipo inteiro é um tipo de dado capaz de armazenar número inteiros,ou seja, sem casas decimais. 
 <br>
 Vamos criar uma variável do  tipo inteiro para armazenar a idade de uma pessoa.
 
 ~~~
 inicio {
     inteiro: idade;
     
     idade = 30;
  }
   ~~~~
 <br>
  Fique atento, pois não pode armazenar um texto dentro da variável idade, pois o tipo inteiro armazena somente números. Não é necessário colocar aspas entre os números.
  
  Outro detalhe importante é colocar valores dentro de uma variável se ela existir previamente; <br>
   Vamos a ordem de declaração:
  
  <strong> Declaração: </strong>
  
  ~~~ 
  inicio {
           caractere: texto;
           inteiro: idade;
   }          
    
 ~~~~
 
 <strong> Definindo um valor </strong>
  ~~~
  inicio {
           caractere: texto;
           inteiro: idade;
           
           texto = "Olá, meu nome é Suhailah!";
           idade = 30;
           
           escreva(texto);
           escreva(idade);
     }
           
 ~~~~
       
 <strong>O valor declarado aparece:  </strong>
  
  ~~~ 
  Olá, meu nome é Suhailah!
  30
      
 ~~~~


 
  <br>
  <br>
 
 
 <h2>Atribuição do tipo Real</h2>
 <hr>
 
<p> O tipo real é também um tipo numérico, porém aceita casas decimais.
 
 Enquanto o tipo inteiro trabalha apenas números inteiros sem vírgula, o tipo real trabalha número com vírgulas.
 
 >Atenção! <br>
 >Na linguagem de programação não se usa vírgula `,` e sim, utiliza-se `.`
 
 Vamos executar o tipo Real:
 
 ~~~
  inicio {
           caractere: nome;
           inteiro: idade;
           real: altura;
           
           nome = "Suhailah!";
           idade = 30;
           altura = 1.63
           
           escreva(nome);
           escreva(idade);
           escreva(altura);
     }           
 ~~~~
 
  <strong>Resultado:</strong>
  ~~~ 
  Suhailah!
  30
  1.63      
 ~~~~
 
  <br>
  <br>
 
 
 <h2>Concatenação</h2>
 <hr>
<p>Concatenação é unir 2 (duas) ou mais variáveis por meio de uma linguagem em uma única variável. Vamos ao exemplo:<br>

  <strong>Código:</strong>
</p>

~~~
  inicio {
           caractere: nome;
           inteiro: idade;
           real: altura
           
           nome = "Suhailah";
           idade = 30;
           altura = 1.63;
           
           escreva(nome + " , " + idade + " , " altura);          
     }           
 ~~~~
<strong>Resultado:</strong>
  ~~~ 
  Suhailah, 30, 1.63    
 ~~~~
<p> O operador mais ` + ` é utilizado para concatenar informações.
 A partir do momento que ultilizar o operador mais ` + `, o resultado será um novo texto e esse texto será escrito, como vimos acima. </p>
 
 <p>Podemos criar uma outra varíavel chamada `info`:</p>
 
 
~~~
  inicio {
           caractere: nome;
           inteiro: idade;
           real: altura
           
           nome = "Suhailah";
           idade = 30;
           altura = 1.63;
           
           caractere: info;
           
           info = nome + " , " + idade + " , " altura;  
           
           escreva(info);
     }           
 ~~~~
<strong>Resultado:</strong>
  ~~~ 
  Suhailah, 30, 1.63    
 ~~~~
 
 Estão compreendendo como funciona a varíavel?!
 <p>Basicamente você declara a variável conforme o tipo, armazena o valor correspondente e depois você usa os dados futuramente.<br>
 Essa é a base de funcionamento de qualquer programa.</p>
 <br>
 <br>

<h1>Comando Input - Entrada de Dados</h1>

<p>Input é a entrada de informações armazenadas no computador. E esses dados serão usados posteriomente produzindo informações de saída.</p>

No vídeo abaixo iremos ler o nome fornecido pela pessoa. Com o código pronto iremos:
  
1. Colocar as barras `// `, para comentar o nome. 
>Observação: As barras `// `  serve para comentar o que está no código, pois o que é comentado não é executado.

2. Colocar o comando `leia`.

3. Vamos executar :arrow_forward:.

 ![Input-GitHub](https://ik.imagekit.io/fp3xx2hhnq/Input_zCll7h2NkA.gif)
 
 <p>O comando `leia` recebe duas informações, dois parametros, essa é a terminologia usada em programação. <br>
 
 Os parametros usados são: o texto, é o que se pede na caixa de texto, o local de armazenamento da informação fornecida pelo usuário, que nesse caso é o nome, o qual será armazendo em `nome`.<br>
 
  E da mesma maneira que utilizei em `nome`, pode ser usado em `idade`, e `altura`.</p>

<p><strong>Veja o exemplo: </strong></p>
 
 
![Parametro GitHUb](https://ik.imagekit.io/fp3xx2hhnq/Parametros_L84Z3qh8Ji.gif)
  
  
  

<strong>REGRAS IMPORTANTES!</strong>
1. O nome de variáveis deve sempre começar com <strong>letras</strong>.
2. O nome das variáveis pode ser seguidos de números. Exemplos: <br>
`var = idade2` <br> `var = i1altura`
3. Não pode utilizar símbolos, <strong>execeto</strong> underline `_`.
4. Não pode conter <strong>espaços</strong> em branco.
5. Não pode conter letras com <strong>acentos</strong>.
6. Não pode ser uma <strong>palavra reservada</strong>.



 <br>
 <br>



<h1>Aprendendo Média</h1>

<p> Nessa aula vamos criar um cálculo de média, baseado em três notas de um aluno.</p>

<p>A primeira pergunta que possa vir a sua mente é: "Como se calcula média nas notas de uma aluno?". Acertei?!</p>

<p>Vou mostrar passo a passo como iremos fazer isso.<p>
 
1.Passo: O que vamos precisar primeiro é declarar as notas do tipo real: 
~~~
inicio {
   real: nota1;
   real: nota2;
   real: nota3;
}
~~~

2.Passo: Carregar essas notas nas variáveis. Daremos um Input nas notas geradas.
Exemplo:
~~~
inicio {
   real: nota1;
   real: nota2;
   real: nota3;
   
   leia("Digite a Nota 1!", nota1);
   leia("Digite a Nota 2!", nota2);
   leia("Digite a Nota 3!", nota3);
}
~~~

3.Passo: Fazer a conta da média, que será feita assim: <br>
Soma-se os três valores(`nota1` + `nota2` + `nota3`) e divide o resultado por 3.

```(nota1 + nota2 + nota3) / 3```

4.Passo: Executar o comando escreva, para mostrar a média.

Veja o Exemplo abaixo:
 ~~~
 inicio {
   real: nota1;
   real: nota2;
   real: nota3;
   
   leia("Digite a Nota 1!", nota1);
   leia("Digite a Nota 2!", nota2);
   leia("Digite a Nota 3!", nota3);
   
   real: soma;
   soma = nota1 + nota2 + nota3; 
   
   real: media;
   media = soma / 3;
   
   escreva("A média é " + media);
}
~~~

<strong> Resultado </strong>

![Média GitHub](https://ik.imagekit.io/fp3xx2hhnq/m_dia1_TYokrLs-2.gif)
 <br>
 <br>


<h3> Operadores Aritméticos </h3>

Nome |Símbolo
--------- | ------
Soma | +
Subtração | -
Multipliação| *
Divisão | /

 <br>
 <br>

<h3>Simplificando os códigos</h3>

Na hora de somar as notas, existem uma maneira mais simplificada de somar e dividir tudo na mesma linha e já sair o resultado, veja:

1. Passo: Apague a variável `soma` e os valores declarados.
2. Passo: Adicione na váriável média as três notas;
3. Passo: Adicione os parênteses no antes da `nota1` e após a `nota3`.

![Média GitHub](https://ik.imagekit.io/fp3xx2hhnq/m_dia2_8emmnPqdw.gif)

E existe uma outra forma de simplificação:


![Média GitHub](https://ik.imagekit.io/fp3xx2hhnq/m_dia3_Xxdiih3sN.gif)


<h2> Cálculo de juros compostos</h2>

O algoritmo que será utilizado, será um algoritmo para calcular taxa de juros.

  Para isso, iremos utilizar uma fórmula de juros compostos.
  
  ![Juros Composto GitHub](https://ik.imagekit.io/fp3xx2hhnq/Juros_compostos_1N0wcz4BW.png)  
   
 Temos mais uma coisa a resolver, caso a pessoa compre um carro, será necessário informar o valor inicial `PV`, a taxa de juros a qual será pago, caso financiado `i` e o tempo a ser pago `n`, para sabermos o valor total `FV`.
  
  Vamos distrinchar cada respresentação existente na fórmula.<br>
  <strong>FV</strong> = Valor futuro<br>
  <strong>PV</strong> = Valor Presente<br>
  <strong>i</strong> = Taxa de juros (ex:taxa de juros ao mês)<br>
  <strong>n</strong> = Prazo (Tempo)<br>
  
  Vamos começar criando as váriaveis do tipo real:
   ~~~
   início {
      real: fv;
      real: pv;
      real: i;
      real: n;   
   }
  ~~~
  
  Vamos ler os valores e armazenar:
   ~~~
   início {
      real: fv;
      real: pv;
      real: i;
      real: n;  
      
      leia("Valor atual", pv);
      leia("Taxa",i);
      leia("Tempo",n);      
  }
  ~~~
  
A variável `fv` teremos que calcular:
 ~~~
   início {
      real: fv;
      real: pv;
      real: i;
      real: n;  
      
      leia("Valor atual", pv);
      leia("Taxa",i);
      leia("Tempo",n);   
      
     fv = pv * pot(1 + i)n;
}
  
  ~~~
 Nesse código foi adicionado o `pot` que representa a potenciação. O `pot` recebe duas informações que são: 
 1. O valor da base da potenciação `1 + i `
 2. E o expoente `n`.

 A taxa deverá ser informado pelo usuário e o qual teremos que transformar a taxa em porcentagem.
  ~~~
   início {
      real: fv;
      real: pv;
      real: i;
      real: n;  
      
      leia("Valor atual", pv);
      leia("Taxa",i);
      leia("Tempo",n);   
      
     fv = pv * pot(1 + i /100 , n);
}
  ~~~
 
A prioridade desse código será:

1. `i/100`;
2. Resultado da divisão `+ 1 `;
3. Resultado será elevado a `n`;
4. E o resultado da conta que estava entre parenteses será multiplicado em `pv`;
5. O resultado será `fv`;

Digamos que o i seja o número 2, ficando assim:
1. `2/100`;
2. `0.002 + 1`;
3.`1.002`elevado a n;
4. E o resultado da conta que estava entre parenteses será multiplicado em `pv`;
5. O resultado será `fv`;

No final o `FV` tem o seu resultado.
~~~
   início {
      real: fv;
      real: pv;
      real: i;
      real: n;  
      
      leia("Valor atual", pv);
      leia("Taxa",i);
      leia("Tempo",n);   
      
     fv = pv * pot(1 + i /100 , n);
     
     escreva("FV = " + fv);
}
  ~~~
  
  ![Juros Composto GitHub](https://ik.imagekit.io/fp3xx2hhnq/juroscomposto_Ma3itsbFQ.gif)


<br>
<br>

<h2> Transformando Milhas em Quilômetros</h2>
<hr>

[IMAGEM]

<p>Já sentiu aquela curiosidade, quando você está assistindo filmes ou séries e aparece uma placa na estrada 30 mile e dá aquela curiosidade em saber quanto é em quilômetros. Nessa aula irei mostrar como se faz um programa que converta Milhas em Km.</p>
<br>

Para isso precisamos saber quanto vale 1 milha em km.
![Imagem Milha](https://ik.imagekit.io/fp3xx2hhnq/milha_0Fejhgir9.jpg)

<p>Vamos ao código:
</p>

<p> Iremos declarar o tipo real milha e pedir para ler;</p>

~~~
início {
      real: ml;    
      leia("Digite a milha:", ml)

}
~~~


Depois iremos declarar o tipo real para km, montar uma pequena equação e dar o comando escreva; 

~~~
início {
    real: ml;    
    leia("Digite a milha:", ml);
    
    real: km;
    km = ml *( 1 / 1.61);
   
    escreva("A conversão de Milha ", + ml, " Para Km, é de: " + km);
  }
~~~

 <strong>Resultado</strong>
 
 
 ![Milha em Km](https://ik.imagekit.io/fp3xx2hhnq/milhaemkm_ZEfIWVwHB.gif)
