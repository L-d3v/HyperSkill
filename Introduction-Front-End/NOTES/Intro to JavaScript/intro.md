# Introdução ao JavaScript:

- JavaScript é uma linguagem de programação que pode ser utilizada para o desenvolvimento de Front-End e Back-End;


- No Front-End, junto do HTML e CSS, o JavaScript auxiliar na criação de animação/interações em uma página Web;


- No Back-End, o JS pode ajudar no gerenciamento de dados do usuário, trabalhando junto de um banco de dados e coordenando tarefas junto de um servidor;


- O JavaScript segue um padrão para continuar alinhado aos recursos e melhorias no desenvolvimento Web, esse padrão é chamado de **ECMAScript (ES)**


## Java VS. JavaScript:

- Java e JavaScript são linguagens de programação, mas completamente diferentes. Por mais que possuem uma semelhança no nome, ambas foram desenvolvidas separadamente, assim como suas sintaxes e propósitos são diferentes uma das outras;


- A idéia por trás dos similares (nomes), trata-se de uma estratégia de Marketing, visando capitalizar a crescente popularidade do Java. O JavaScript em questão, iniciou recebendo o nome de Mocha, onde posteriormente foi renomeado para LiveScript e depois para o famoso JavaScript;

## Primeiro Programa: 

- Qualquer programa escrito em uma linguagem de programação é chamado de **_script_**;


- No JS, um script simples que imprima um texto é feito da seguinte forma:

  
    `console.log ("I'm starting to learn JavaScript")`


- Atualmente, qualquer navegador (moderno) possui um programa integrado que permite a execução do JS diretamente. Dessa forma, o _Script_ acima seria impresso dentro do console do navegador;

- O conjunto de palavras "Hello, World!" é chamado de **String**, para que uma string seja considerada, é preciso que a mesma esteja entre aspas simples ( ' ' ) ou duplas ( " " );

## Primeiro Código:

- Ao iniciar no mundo da programação, é dito sobre uma tradição que se deve iniciar um programa que exiba "Hello, World!", para executar essa tradição, podemos inserir no console o seguinte comando:
    

    `console.log("Hello, World!")`


- Ao pressionar `Enter` o comando que deverá ser exibido é "Hello, World!".

### Imprimindo Scripts:

- Uma função é uma sequência de instruções que pode ser reutilizada em um programa. Quando há a presença dos parênteses seguido do nome de uma função, ela é chamada para obter o resultado


- A função `console.log` é um bloco de código que permite que você envie informações para o console, ou seja, ela é responsável por imprimir informações e frequentemente utilizada para encontrar erros no código;


- A função `console.log` também pode produzir strings vazias (Strings sem informações), assim, quando reproduzida, retornará apenas uma nova linha;
    Ex.

    ```
    console.log("I");
    console.log("");
    console.log("Know");
    console.log();
    console.log("JavaScript");
    ```

- Em ambos os casos, quando impresso um valor vazio, seja ele utilizando aspas ou não, o resultado será o mesmo;

- Outros casos que gera a quebra de linha:
    
    - **\n** : Ao inserir dentro do conjunto que será impresso, irá gerar a quera de linha;


### Possíveis Erros:

- No início, há diversas chances de um código possui um erro/falha. Os mais comuns são:

    1. **Nomeação Impropria:** 
       É quando um comando é escrito de forma errada;
       
        Ex.
    
            consle.log("Hello, World!")
  
    2. **Usando letras maiúsculas e minúsculas:**
       O JavaScript diferencia letras maiúsculas de minúscula, dessa forma, é preciso escrever os códigos corretamente:
  
        Ex.

            CONSOLE.LOG("Hello, World!")

    3. **Ausência de Sinal:**
       Quando houver a ausência de algum sinal, seja ele um ponto, ponto e vírgula ou parentese (mais comuns), o código não será executado corretamente:
    
          Ex.
    
              console.log("Hello, World!;

### Comentários:

- Os comentários podem ajudar e melhorar a legibilidade de um código e assim, facilitando o entendimento para manter o código funcionando;


- No caso do JavaScript, o interpretador ignora o texto quando iniciados em formato de comentário;


- Dentro do JavaScript, é possível aplicar os comentários de duas formas:
  
    - **Comentário de Linha Única:** Refere-se aos comentários que ocuparam apenas uma linha, dessa forma, auxiliando no entendimento do fragmento do código em que for aplicado. Para aplicar esse tipo de comentário, utilizamos "//";
  
      Ex.

        ```
        console.log("Nice to see you!"); // Esse código irá mostrar a mensagem no console
        ```

    
- **Comentário Multi-Linha:** Para abranger várias linhas de código, auxiliando a explicar partes complexas do código. Para esse tipo de comentário, utilizamos "/*";

#### Melhores Práticas:

- Utilize os comentários para explicar o "por que" de um código, não apenas "o quê";


- Evite comentários óbvios;


- Atualize os comentários conforme o código evolui;


- Use comentários para melhorar a colaboração entre a equipe;

## Declarando Variáveis:

- Variável pode ser dito como um espaço livre na memória, onde os dados pode ser armazenados, acessados e manipulados quando necessário;


- Em qualquer linguagem de programação, as variáveis são essenciais, já que são elas que permitem que armazenar algum dado e posteriormente, para que os desenvolvedores consiga recuperar ou manipular esse mesmo dado de forma eficiente;


- Para declararmos/criar uma variável é necessário atribuir um valor a ela;


- No JavaScript, há duas formas de declaramos uma variável:

  1. **let:** Define uma variável mutável, ou seja, que o seu valor pode ser alterado;

  2. **const:** Define uma variável de valor absoluto, ou seja, o valor não poderá ser alterado;


- Ao declarar uma variável, busque nomeá-las apropriadamente, utilizamos nomes que descreva do que se trata o conteúdo;

### Variáveis Mutáveis:

- Assim como dito acima, uma variável pode armazenar qualquer tipo de dado, seja textos, números, etc;

- Para entendermos como uma variável mutável funciona, vamos fazer o seguinte:

    ```
    let month = "November";
    ```

- Declaramos a variável "month" e atribuímos o valor "November", que é uma String, dessa forma, conseguimos acessar esse valor utilizando/chamando o nome da variável dentro do console;

    ```
    let month = "November";
    console.log(month);
    ```


- Ao chamar a função e colocar o nome da variável, o conteúdo que será retornado no console será o valor atribuído, nesse caso, a palavra November;


- Para alterar esse o valor armazenado, basta atribuirmos novamente um novo valor para a mesma variável;

    ```
    let month = "November";
    month = "December";

    console.log(month);
    ```

- No caso acima, após o novo valor atribuído para a variável `month`, quando aplicado na função `console.log`, o valor a ser retornado será o último na qual foi atribuído (Nesse caso, o valor será December).


### Constantes:

- Diferentemente das variáveis mutáveis, a variável `const`, quando declarada e atribuída a ela um valor, esse valor não poderá ser alterado;

    ```
    const language = "JavaScript";
    ```

- O valor "JavaScript" na qual foi atribuído se tornaria fixo/absoluto, e em caso de tentativa de alterar esse valor, seria retornado uma mensagem de erro;

    ```
    const language = "JavaScript";
    language = "PHP"; //Uncaught TypeError: Assignment to constant variable.
    ``` 


### Outra Maneira de Declarar Variáveis:

- Outra forma de declarar uma variável é utilizando o `var` que substitui a variável `let`;


- A variável servirá para declarar as variáveis antes da padronização do ECMAScript, onde foi introduzido o `let` e o `const`;


- A diferença entre `var` das variáveis `let` e `const`, é que a `var` é acessível para toda a função, mesmo que esteja fora de seu bloc, enquanto `let` e `const` são limitadas ao bloco definido. Neste caso, variáveis declaradas com `var` possuem um maior potencial de _bugs_ ou erros;


- A sintaxe da variável `var` não se diferencia das demais, sendo assim:

    ```
    var age = 19
    ```

- Outra forma de declarar uma variável é sem o uso de uma palavra-chave (let, const ou var);
    
    Ex.
  
    ```
    age = 19;
    ```
  
#### Melhores Práticas:

- Pratique usar `const` por padrão e mude para `let` somente quando precisar alterar o valor da variável;


- Assim como dito acima, evite a usar a variável `var`, pois a mesma possui pontencial maior de geral/causar erros;


- Evite também declarar variáveis sem o uso de sua definição do tipo (contante ou mutável), pois isso pode criar variáveis globais como o `var`;

## Strings e Numbers:

- Qualquer informação que é usada no JavaScript possui um **tipo**;


- Como propriamente dito, o tipo é responsável para descrever o tipo de dado que será armazenado na memória  quais operações podem ser aplicadas a elas;


- **String** é um tipo de dado usado no JavaScript. Tudo que for informação textual ou que esteja entre aspas (" ") é considerado uma String;
    
  Ex.

    ```
    console.log("Hello, World!");
    console.log('string');
    console.log("R$ 1.800");
    ```
  
- **Numbers** pode ser dito como o tipo de dado mais importante na programação;


- Dentro do JavaScript, podemos usar números positivos, negativos e até zero. Não há limitações em relação a adicionar ou registrar números;
    
    Ex.
    
    ```
    console.log(12);
    console.log(-500);
    console.log(0.50);
    ```
  
- Números inteiros podem contar objetos físicos, enquanto os reais (ponto flutuante) são bons para cálculos estatísticos e científicos;

### Operador Typeof:

- Para reconhecer facilmente o tipo de dado, podemos usar o operador `typeof`;

- Há duas formas de usar esse operador:
    
    * Entre parênteses:

      ```
      console.log(typeof(9)); 
      ```

  * Sem parênteses:

    ```
    console.log(typeof 9); 
    ```  

- O resultado para ambos será o mesmo, o resultado a ser retornado será que o dado "9" é do tipo "number";
