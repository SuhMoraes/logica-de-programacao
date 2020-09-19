<h1 align="center">Lógica de Programação </h1>
 
<h2>Introdução</h2>

   <p>O computador é bom em duas coisas: executar muitas tarefas  rapidamente e armazenar muitos dados. Porém não possui nenhuma experiência prévia, pois ele é programado para executar tarefas.

 Toda parte lógica de um software, toda parte de tomada de decisão é feita pelo programador. É dele o papel de mapear todas as possibilidades e instruir o computador dependendo de cada possibilidade.</p>
 
<h2> Criando um programa </h2>
 
 Todo algoritmo começa com bloco início.
  ~~~
  inicio {
  }
 ~~~
 Onde é delimitado no abrir e fechar chaves ```{ }```. O conteúdo somente será executado se estiver dentro das chaves.
  
  >O programa é executado de cima para baixo, da esquerda para direia.
 
 
 <h2>Atribuição do tipo inteiro</h2>
 
 <p>Existe outro caractere que é um outro tipo de dado: o tipo inteiro. Capaz de armazenar número inteiros. <br>
 Vou criar uma variável do  tipo inteiro para armazenar a idade de uma pessoa.
 
 ~~~
 inicio {
     inteiro: idade;
     
     idade = 30;
  }
   ~~~~
  Fique atento, pois não posso armazenar um texto dentro da idade, porque o tipo inteiro armazena somente números. Não é necessário colocar aspas entre os números.
  
  Outro detalhe importante é colocar valores dentro de uma variável se ela existir previamente; <br>
   Vamos a ordem de declaração:
  
  <strong> Declaro: </strong>
  
  ~~~ 
  inicio {
           caractere: texto;
           inteiro: idade;
   }          
    
 ~~~~
 
 <strong> Defino um valor </strong>
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
 
 <h2>Atribuição do tipo Real</h2>
 
<p> Real é também um tipo numérico, porém aceita casas decimais.
 
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
 
 <h2>Concatenação</h2>
<p>Concatenção server para concatenar informações (juntar informações), deixando o código um pouco mais limpo. Vamos ao exemplo:<br>

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

<h1>Comando Input - Entrada de Dados</h1>

<p>Input é a entrada de informações armazenadas no computador. E esses dados serão usados posteriomente produzindo informações de saída.</p>

No vídeo abaixo iremos ler o nome fornecido pela pessoa. Com o código pronto iremos:
  
1. Colocar o `// `, para comentar o nome. 
>Observação: O `// `  serve para comentar o que está no código, pois o que é comentado não é executado.

2. Colocar o comando `leia`.

3. Vamos executar :arrow_forward:.



  






















