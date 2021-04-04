Aula 1 - Introdução
    Pode realizar operações Client-side
    Geralmente realiza as operações Frontend
    Node.js - Pode realizar operações Backend
    ReactNative - Cria apps

Aula 2 - COnfig Ambiente
    Renderização começa de forma vertical, de cima para baixo
    Javascript trabalha com as árvores de elementos em tela

Aula 3 - Variaveis e dados
    Não tem tipagem estatica, não precisa definir o tipo de valor (se é string, int, etc..)
    começa pela palavra var
    tipos de variaveis: string, inteiro, float, boolean, vetores, objetos (recebe varias variaveis em uma só)

Aula 4 - Operações matemáticas
    % não faz porcentagem, é o simbolo para calcular o modulo (resto da divisao);

Aula 5 - Funcoes
    as variaveis definidas na função não sao globais, precisa definir duas vezes;

Aula 6 - COndicionais
    para fazer um if, usar ==
    === além de verificar o valor das variaveis, verifica o tipo da variavel
    switch case

Aula 7 Operadores logicos
    and, or, not
    and = &&
    or = ||
    not = !==

Aula 8 COndicoes Ternarias
    só executa quando tem duas condicoes dentro do if
    Serve para encurtar a forma de digitar uma condição, utiliza o ?

Aula 9 estruturas de repetição
    for e while
    for = sempre qe souber o tamanho do intervalo

    while = quando nao sabemos quantas vezes o fluxo vai ser executado

Aula 10 intervalo e timeout
    funcao que executa varias vezes dentro de um intervalo
    setTimeout executa apenas uma vez, depois de um tempo pre definido

    ************** Manipulando a DOM *************+

Aula 1 - Eventos inline
    DOM é a arvore de elementos dentro do HTML

Aula 2 - Manipulando a DOM
    getElementsByTagName() - pega pelo nome da tag, sempre retorna um vetor

    +++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++

    AULA NOVA DE js
    Object = Objeto, é um dado estrutural, todo objeto tem uma propriedades ou atributos
    propriedades: cor, tamanho são os atributos
    funcionalidade são metodos
    Objeto é aberto por {}

    Array = vetores
    é uma lista
    Agrupamento de dados
    [lista1, lista2, etc..]

    Dados primitivos
    *string
    *Numbeer
    *boolean
    *undefined
    *Symbol
    *BiginT

    Dados estruturais
    *Object
        *Array
        *Map
        *set
        *Date
        *...
    *Function

    Primitivo estrutural
    * null

Variaveis
    var 
    let
    const

fortemente tipada: é atribuida o tipo de valor é a variavel (int, str, etc..
JS é fracamente tipada, não é necessario definir
para ver o tipo de variavel usar typeof

SCOPE
Scope deterina a visibilidade de alguma variavel no JS
Block Statement é criado um novo escopo, criado atraves de uma chave {}

var é global e podera funcionar foora de um escopo de bloco
se a var é declara depois da chamada ele vai apresentar o erro undefinined, pois joga a variavel para o começo do codigo, mas nao defini valor para ela, esse conceito se chama hoisting

const e let são locais e só funcionam no escopo onde foi criada

Para chamar um Object dentro de um console.log, usar: ${person.name}