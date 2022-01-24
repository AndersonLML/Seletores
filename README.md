# Seletores

<p>Tabela de Seletores</p>
________________________________________________________________________
<!--ts-->

* [Seletor_Universal](#Seletor-Universal)
* [Seletor_de_Texto](#Seletor-de-Texto)
* [Seletor_de_Classe](#Seletor-de-Classe)
* [Seletor_de_ID](#Seletor-de-ID)
* [Seletor_de_Filho](#Seletor-de-Filho)
* [Seletor_de_Descendente](#Seletor-de-Descendente)
* [Seletor_de_Irmao_Adjacente](#Seletor-de-Irmao-Adjacente)
* [Seletor_de_Irmao_Geral](#Seletor-de-Irmao-Geral)

<!--te-->

# Seletor-Universal
Aplica-se em todos os 
elementos no documento
<p>Exemplo</p>
*{}
Seleciona todos os elementos da 
página

# Seletor-de-Texto
Seleciona elementos pelo 
tipo
<p>Exemplo</p>
H1, h2, h3 {}
Seleciona os elementos h1, h2 e
h3

# Seletor-de-Classe
Seleciona um elemento cujo 
atributo class tem o valor 
especificado depois do 
ponto
<p>Exemplo</p>
verde{}
Seleciona qualquer elemento cujo 
atributo class tem o valor “verde”
p.verde{}
Seleciona somente elemento <p> cujo 
atributo class tem o valor “verde”

# Seletor-de-ID
Seleciona um elemento cujo 
atributo id tem o valor 
especificado após o símbolo 
de cerquilha ou jogo da 
velha
<p>Exemplo</p>
#cabecalho{}
Seleciona o elemento cujo atributo id 
tem o valor “cabecalho”

# Seletor-de-Filho
Seleciona um elemento que 
é filho direto de outro
<p>Exemplo</p>
li>a {}
Seleciona quaisquer elementos <a> 
que são filhos de um elemento <li> 
(mas não outros elementos a na 
página

# Seletor-de-Descendente
Seleciona um elemento que 
é descendente de outro 
elemento especificado (e 
não apenas filho direto 
desse elemento)
<p>Exemplo</p>
p a {}
Seleciona quaisquer elementos <a>
que residem dentro de um elemento 
p, mesmo e houver outros 
elementos aninhados entre eles

# Seletor-de-Irmao-Adjacente
Seleciona um elemento que 
é o irmão próximo de outro
<p>Exemplo</p>
h1+p {}
Seleciona o primeiro elemento p
depois de qualquer elemento h1
(mas não outros elementos p)

# Seletor-de-Irmao-Geral
Seleciona um elemento que 
é um irmão de outro, 
embora ele não precise ser o 
elemento diretamente 
precedente
<p>Exemplo</p>
h1~p {}
Se houvesse dois elementos <p> que 
fossem irmãos de um elemento <h1>, 
essa regra se aplicaria ao dois