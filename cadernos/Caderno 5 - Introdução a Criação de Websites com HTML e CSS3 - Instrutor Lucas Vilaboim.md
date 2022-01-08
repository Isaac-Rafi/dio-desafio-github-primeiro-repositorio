# INTRODUÇÃO A CRIAÇÃO DE WEBSITES COM HTML E CSS3
## Aula 43 - Introdução ao HTML5 e CSS3
### Instrutor: Lucas Vilaboim

**HTML criação e modificações:**

- Criando: 1991 - HTML 1
- Nova versão: 1995 - HTML 2
- Nova versão: 1997 - HTML 3
- Nova versão: 1997 - HTML 4
- Nova versão: 2014 - HTML 5



**Elemento HTML:**

Tag de abertura - qual tipo de elemento - (a tag pode ter um atributo) - conteúdo - e tag de fechamento



**Estrutura:**

<!DOCTYPE html>
<html>
    <head>
        <meta charset="utf-8">
        <title>Site de Teste</title>
    </head>
    <body>
     Isaac Rafi
    </body>
</html>


[Material de Apoio HTML 5](<>)





## AULA 44 - Semântica parte 1

### Instrutor: Lucas Vilaboim

Durante muitos anos o < div > era o padrão, com html 5 vieram a ter:

- < section >
- < aside >
- < header >
- < footer >
- < article >





## AULA 45 - Semântica parte 2

### Instrutor: Lucas Vilaboim

< !DOCTYPE html >
< html >
    < head >
        < meta charset="utf-8" >
        < title >Site de Teste< /title >
    < /head >
    < body >
     < header >
       < h1 >Name< /h1 >  
     < /header >
     < section >
         < header >
             < h2 >Post< /h2 >
         < /header >
         < article >
             < header >
                 < h3 >Post #1< /h3 >
             < /header >
         < /article >
     < /section >
     < footer >
     < /footer >
    < /body >
< /html >

html acima



## AULA 46 - Tags para textos

### Instrutor: Lucas Vilaboim

< h1 > Título da página < h1 >

< h2 > título de seção < h2 >

< h3 > título de artigo < h3 >

< p > conteúdo do artigo < p > (para paragrafo; código; vídeo)



## AULA 47 - Tags para links

### Instrutor: Lucas Vilaboim

< a > link < /a > (âncora, interliga vários conteúdos na web)

< a href="linkedin.com/in/vilaboim">Linkedin< /a >

< a href="mailto:lucas@vilaboim.com">E-mail< /a >

< a href="tel:+5511999999999">Tel< /a >

< a target="_blank">Link< /a > (serve para indicar como vai ser aberto)



## AULA 48 - Exercício Prático

### Instrutor: Lucas Vilaboim

< !DOCTYPE html >
< html >
    < head >
        < meta charset="utf-8" >
        < title >Site de Teste< /title >
    < /head >
    < body >
     < header >
       < h1 >Name< /h1 >  
     < /header >
     < section >
         < header >
             < h2 >Posts< /h2 >
         < /header >
         < article >
             < header >
                 < p >
                    O < a href="https://code.visualstudio.com/docs" target="_blank" >Visual Studio Code< /a > é um editor de código-fonte leve, mas poderoso, que é executado em sua área de trabalho e está disponível para Windows, macOS e< a href="mailto:seunome@email.com" target="_blank" >Linux< /a >. Ele vem com suporte integrado para JavaScript, TypeScript e Node.js e tem um rico ecossistema de extensões para outras linguagens (como C ++, C #, Java, Python, PHP, Go) e tempos de execução (como .NET e Unity) .
                 < /p >
                 < h3 >Post #1< /h3 >
             < /header >
         < /article >
     < /section >
     < footer >< /footer >
    < /body >
< /html >






## AULA 49 - Tag img

### Instrutor: Lucas Vilaboim

< img >  

< img src="img/avatar.jpg"> (source é obrigatório e guarda o caminho)

< img alt="Foto de Lucas Vilaboim"> (mostra a descrição da foto e leitores de tela usa a descrição para mostrar o que significa)



## AULA 50 - Exercício Prático

### Instrutor: Lucas Vilaboim

< !DOCTYPE html >
< html >
    < head >
        < meta charset="utf-8" >
        < title >Site de Teste< /title >
    < /head >
    < body >
     <  header >
         <img src="https://lh4.googleusercontent.com/BajM7QA_nec0N7ugD7rgYjpMJgaU3Sy5UzH4Dt656pM0Zl5UZJ0-aEWlxTUEW-OyAJhjlQ=w1280" alt="whatsapp">
         < h1>Name< /h1>  
     < /header>
     < section>
         < header>
             < h2>Posts< /h2>
         < /header>
         < article>
             < header>
                 < p>
                    O <a href="https://code.visualstudio.com/docs" target="_blank">Visual Studio Code</a> é um editor de código-fonte leve, mas poderoso, que é executado em sua área de trabalho e está disponível para Windows, macOS e <a href="mailto:seunome@email.com" target="_blank">Linux</a>. Ele vem com suporte integrado para JavaScript, TypeScript e Node.js e tem um rico ecossistema de extensões para outras linguagens (como C ++, C #, Java, Python, PHP, Go) e tempos de execução (como .NET e Unity) .
                 < /p>
                 < h3>Post #1< /h3>
                 <img src="https://lh4.googleusercontent.com/Qyb_es3OuqczEgJ4rdvTBslaj9r5wp-S25pVKdzStGaQdCoCzHngR8ZrIg27B1PS7g9Sj_Ds5T19ttVWrA1HTKXE5ChvmvOkf81Q88m893Yh3ifdz7vctmBgXuT3xbV2Tg=w1280" alt="Jeus">
             < /header>
         < /article>
     < /section>
     < footer>
     < /footer>
    < /body>
< /html >



## AULA 51 - Tag li, ul e ol

### Instrutor: Lucas Vilaboim

Listas = agrupar coleção de itens

< ul > (itens sem importância)

Item 1 

Item 2



< ol >  = itens de importância

1. item 1
2. item 2



< li >



## AULA 52 - Exercício Prático

### Instrutor: Lucas Vilaboim

< !DOCTYPE html >
< html >
    < head>
        < meta charset="utf-8">
        < title>Site de Teste< /title>
    < /head>
    < body>
     < header>
         < img src="https://lh4.googleusercontent.com/BajM7QA_nec0N7ugD7rgYjpMJgaU3Sy5UzH4Dt656pM0Zl5UZJ0-aEWlxTUEW-OyAJhjlQ=w1280" alt="whatsapp">
         < h1>Name< /h1>  
     < /header>
     < section>
         < header>
             < h2>Posts< /h2>
         < /header>
         < article>
             < header>
                 < p>
                    O <a href="https://code.visualstudio.com/docs" target="_blank">Visual Studio Code</a> é um editor de código-fonte leve, mas poderoso, que é executado em sua área de trabalho e está disponível para Windows, macOS e <a href="mailto:seunome@email.com" target="_blank">Linux</a>. Ele vem com suporte integrado para JavaScript, TypeScript e Node.js e tem um rico ecossistema de extensões para outras linguagens (como C ++, C #, Java, Python, PHP, Go) e tempos de execução (como .NET e Unity) .
                 < /p>
                 < h3>Post #1< /h3>
                 < img src="https://lh4.googleusercontent.com/Qyb_es3OuqczEgJ4rdvTBslaj9r5wp-S25pVKdzStGaQdCoCzHngR8ZrIg27B1PS7g9Sj_Ds5T19ttVWrA1HTKXE5ChvmvOkf81Q88m893Yh3ifdz7vctmBgXuT3xbV2Tg=w1280" alt="Jeus">
             < /header>
         < /article>
     < /section>
     < footer>
         < ol>
             < li>
                 < a href="mailto:seunome@email.com>"> seunome@email.com</a>
             < /li>
             < li>
                 < a href="https://sites.google.com/view/nome-do-site" target="_blank">Parts Car Auto< /a>
             < /li>
             < li>
                 < a href="https://github.com/nome" target="_blank">GitHub< /a>
             < /li>
         < /ol>
     < /footer>
    < /body>
< /html>




# Introdução e Conceitos Básicos do CSS3

## AULA 53 - Exercício Prático

### Instrutor: Lucas Vilaboim

**Nosso objetivo é:**

O que são seletores? **Elementos HTML**

Conceitos básicos?

Principais seletores?



**Requisitos básicos:**

- Um editor de texto (VSCode)
- Um navegador (Chrome)
- Noção de HTML



**ID x Classe:** podem representar quaisquer tipos de elementos.

< header id="header" class="header" >< /header >

< header class="header" >< /header >

no css: **.header** / **#header**



< !DOCTYPE html>
< html>
    < head>
        < meta charset="utf-8">
        < title>Site de Teste< /title>
        < link rel="stylesheet" href="style.css">
    < /head>
    < body>
     < header>
         <img src="https://lh4.googleusercontent.com/BajM7QA_nec0N7ugD7rgYjpMJgaU3Sy5UzH4Dt656pM0Zl5UZJ0-aEWlxTUEW-OyAJhjlQ=w1280" alt="whatsapp">
         < h1 id="title">Name< /h1>  
     < /header>
     < section>
         < header>
             < h2 class="subtitle">Posts< /h2>
         < /header>
         < article>
             < header>
                 < p>
                    O <a href="https://code.visualstudio.com/docs" target="_blank">Visual Studio Code</a> é um editor de código-fonte leve, mas poderoso, que é executado em sua área de trabalho e está disponível para Windows, macOS e <a href="mailto:seunome@email.com" target="_blank">Linux</a>. Ele vem com suporte integrado para JavaScript, TypeScript e Node.js e tem um rico ecossistema de extensões para outras linguagens (como C ++, C #, Java, Python, PHP, Go) e tempos de execução (como .NET e Unity) .
                 < /p>
                 < h3 class="posttitle">Post #1< /h3>
                 <img src="https://lh4.googleusercontent.com/Qyb_es3OuqczEgJ4rdvTBslaj9r5wp-S25pVKdzStGaQdCoCzHngR8ZrIg27B1PS7g9Sj_Ds5T19ttVWrA1HTKXE5ChvmvOkf81Q88m893Yh3ifdz7vctmBgXuT3xbV2Tg=w1280" alt="Jeus">
             < /header>
         < /article>
     < /section>
     < footer>
         < ol>
             < li>
                 <a href="mailto:seunome@email.com>"> mailto:seunome@email.com</a>
             < /li>
             < li>
                 <a href="https://sites.google.com/view/nome-do-site" target="_blank">Parts Car Auto</a>
             < /li>
             < li>
                 < a href="https://github.com/nomei" target="_blank">GitHub< /a>
             < /li>
         < /ol>
     < /footer>
    < /body>
< /html>

HTML acima 



## AULA 54 - Conceitos básicos

### Instrutor: Lucas Vilaboim

Quando estamos fazendo um site o navegador apresenta cada elemento HTML em uma caixa (box model)

margin = são espaçamentos entre elementos

​	border = circulam o *padding* e o content (conseguimos alterar largura e cor)

​		padding = é o espaçamento entre a *border* e *content*

​			content = conteúdo (texto, imagem ou vídeo)



\#title, .subtitle, .posttitle, .post {

  color: blue;

}

.post {

  background: white;

  padding: 10px;

  border: 3px solid black;

  margin: 10px;

}



Material de Apoio CSS3



## AULA 55 - Estilizando Elementos

### Instrutor: Lucas Vilaboim

**Padding**

​	.post {

​	paddin: 15px(top) 10px(right) 5px(bottom) 0(left);

​	}

ou

​	.post {

​	paddin-top: 15px;

​	paddin-right: 15px;

​	paddin-bottom: 15px;

​	paddin-left: 15px;

​	}

**Background**

.post {

backgrundo-color: green;	ou	backgrundo-color: #00880;	ou	backgrundo: #008800;

backgrundo-image: url("bg.png");

backgrundo-position: top;

}

**Border**

largura: pixel, centímetros, milímetros...

cor: blue, #0000ff...

Estilo: sólida pontilhada, tracejada...



border: 3px green solid;

ou

border-top: 2px dotted green;

border-right: 4px dashed pink;

ou

border-top-rigth: #00880;

**Border-radius**

border-radius: 10px; 

border-radius: 10%; 

border-radius: 10% 10% 10% 10%; 



## AULA 56 - Estilizando Textos

### Instrutor: Lucas Vilaboim

**font**

#title {

font-family: Verdana;

}

.post_title {

font-family: Verdana, Arila;	= nós entramos com 2 para caso uma não funcionar

}

###### Web safe font = encontram-se na maioria dos dispositivos

**font-size**

#title {

fonti-size: 18px;

}

ou

.post_title {

fonti-size: 18px;

}

**font-style**

#title {

fonti-style: normal;

}

ou

.subtitle {

fonti-style: italic;

}

*devemos observar se nossa fonte tem suporte ao itálico*

**font-weight**

#title {

fonti-weight: normal;

}

ou

.subtitle {

fonti-weight: bold;

}

**text-transform**

#title {

text-transform: uppercase;

}

ou

.subtitle {

text-transform: lowercase;

}

.post_title {

text-transform: capitalize;

}

**text-decoration**

#title {

text-decoration: underline;

}

ou

.subtitle {

text-decoration: overline;

}

.post_title {

text-decoration: line-through;

}



## AULA 57 - Estilizando Listas

### Instrutor: Lucas Vilaboim

**list-style-type**

ul {

lis-style-type: square;	 =	quadrado

}

ol {

lis-style-type: upper-roman;	= 	algarismo romano maíusculo

}

ul {

lis-style-type: "\1F44D";	=	símbolo (joinha)

}



## AULA 58 - Propriedades de Dimensões e Alinhamentos 

### Instrutor: Lucas Vilaboim

width = largura (px, %, cm)

height = altura (px, %, cm)



max-width = largura máxima

maxheight = altura máxima



margin = espaçamento, também tem valor alto e serve para alinha



text align = para alinha texto (Right, left, center)

