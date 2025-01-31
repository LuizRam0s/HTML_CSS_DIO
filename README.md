Foco aqui è praticar os conceito deixando o site visivelmente bonito

Seletores CSS
Os seletores CSS são usados para “encontrar” (ou selecionar) os elementos HTML que você deseja estilizar.

Podemos dividir os seletores CSS em cinco categorias:

Seletores simples (selecione elementos com base no nome, id, classe)

Seletores combinadores

(selecionam elementos com base em um relacionamento específico entre eles)

Seletores de pseudoclasse

(selecionam elementos com base em um determinado estado)

Seletores de pseudoelementos

(selecionam e estilizam uma parte de um elemento)

Seletores de atributos

(selecionam elementos com base em um atributo ou valor de atributo)

Cores
Podemos definir as cores pelos seguintes métodos:

*Hexadecimal:

p{color: #ff004d;} 
ff defini o qual vermelho terá, 00 será o verde e 4d o azul

*Rgb e rgba: defini a cor por numeração, de 0 a 255 sendo que para cada número colocado será pra o quanto de cor terá sendo três o red, Green e blue. O rgba é uma extensão de rgb sendo o a Alpha que defini a opacidade da cor de 0.0 a 1.0

h1{color: rgba(200, 167, 100, 0.6);}
*Hsl e hlsa: defini a cor através da matriz, saturação e leveza, sendo matriz de 0 a 360, saturação e leveza de 0% a 100%. O hsla é uma extensão do hsl colocando um Alpha para a opacidade

p {color: hsla(240, 50%, 60% 0.4);}
⚠️⚠️Propriedade Apreviada
Para encurtar o código, também é possível especificar todas as propriedades de fundo em uma única propriedade

** background APREVIADA

body { background: #ffffff url("img_tree.png") no-repeat right top; }
/*ordem pra apreviar é: color, image, repeat, attachment e position*/
**border APREVIADA

div{border: 5px solid red}
/*ordem: width, style, color*/
**margin APREVIADA