# ESTRUTURA DE DADOS ARRAYS E REGISTRO

## AULA 11 - Introdução e Objetivos

### Instrutor: Bruno de Campos Dias

Fez apresentação pessoal e do curso.



## AULA 12 - O Que é Estrutura de Dados

### Instrutor: Bruno de Campos Dias

**O que é estrutura de dados=** é uma estrutura organizada de dados na memória de um computador ou em qualquer dispositivo de armazenamento, de forma que os dados possam ser utilizados de forma correta.

Encontram muitas aplicações no desenvolvimento de sistemas, sendo que algumas são altamente especializadas e utilizadas em tarefas específicas (estrutura de busca, busca recursiva).

Usando as estruturas adequadas através de algoritmos, podemos trabalhar com uma grande quantidade de dados, como aplicações em banco de dados ou serviço de busca.

**Algoritmo=** é um conjunto de instruções estruturadas e ordenadas, seu objetivo é realizar uma tarefa ou operação específica.
Os algoritmos são utilizados para manipular dados nas estruturas de várias formas, como por exemplo: inserir, excluir, procurar e ordenar dados.

**Ex.:**

- Inserir dados
- Excluir dados
- Localizar elemento
- Percorrer todos os itens constituintes da estrutura para visualização
- Classificar, que se resume em colocar os itens de dados em uma determinada ordem (numérica, alfabética, etc.)



**Principais estruturas de dados:**

- Vetores e Matrizes
- Registro
- Lista
- Pilha
- Fila
- Árvore
- Tabela Hash
- Grafos



## AULA 13 - Vetores e Matrizes

### Instrutor: Bruno de Campos Di

**Vetores e Matrizes=** **Arrays** = são estruturas simples que podem auxiliar quando há muitas variáveis do mesmo tipo em um algoritmo.

O **vetor** ou **array uni-dimensional** é uma variável que armazena várias variáveis do mesmo tipo.
O vetor é uma estrutura de dados indexada, que pode armazenar uma determinada quantidade de valores do mesmo tipo.

**Matriz** ou **array multi-dimensional** é um vetor de vetores, uma matriz é um vetor de duas ou mais dimensões.



## AULA 14 - O Que São Registros

### Instrutor: Bruno de Campos Dias

**Registros=** é uma estrutura que fornece um formato especializado para armazenar informações em memória.

**Arrays=** nos permitem armazenar vários dados de um único tipo de dados, o recurso de Registro nos permite armazenar mais de um tipo de dado.

**Ex.:**

- CPF
- Nome
- Endereço
- Contato



Toda estrutura de registro tem um nome (**ex.:** livro), e seus campos podem ser acessados por meio do uso do operador ponto (.). 

Por exemplo, para acessar o preço do livro, poderíamos utilizar a seguinte declaração: **livro.preco**

**Ex.:**

​	programa
​	{
​	funcao inicio()
​	{
​	tipo	//declaração do tipo de dado
​	estrutura_livro = registro
​	nome caracter
​	preco real
​	pagina inteiro
​	fimregistro

​	i inteiro	//declaração das variáveis
​	livro array[] de estrutura_livro
​	escreva("Entre com os nomes, preços e números de páginas de três livros")
​	para i de 1 ate 3 faca
​	leia(livro[i].nome, livro[i].preco, livro[i].paginas)
​	fimpara
​	escreva("Esses foram os dados digitados")
​	para i de 1 ate 3 faca
​	escreva(livro[i].nome, livro[i].preco, livro[i].paginas)
​	fimpara			
​	}
​	}



## AULA 15 - Introdução e Objetivos

### Instrutor: Bruno de Campos Dias

Só falou um pouco sobre: Listas, Pilhas e Filas.



## AULA 16 - O que São Listas

### Instrutor: Bruno de Campos Dias

**Listas=** armazena dados de um determinado tipo em uma ordem específica, a diferença entre os *arrays* é a de que as listas possuem tamanho ajustável, enquanto *arrays* possuem tamanho fixo.

2 tipos de listas:

**Ligadas:** = **uni-direcional** existem os **nós** onde cada um dos **nós** conhece o valor que está sendo armazenado em seu interior além de conhecer o elemento posterior a ele, por isso ela é chamada de lista **ligada**.

**Ex.:**

Primeiro nó	nó	nó	último nó
	->				|		|			<-

​				pedro	joana	
​					   |-------|



**Duplamente ligadas:** = **bi-direcional** = conseguimos andar para trás e para frente, na lista ligada só para frente.

Nó anterior (1)	Nó anterior (2)
<--------------------------
					|			   |
Primeiro 	 nó		  nó
nó -> 	    Pedro		Joana	<- ultimo nó	^
					|			   |									|
----------------------------------------------------
​		próximo nó (1)	próximo nó (2)



## AULA 17 - O Que São Pilhas

### Instrutor: Bruno de Campos Dias

**Pilhas=** é uma estrutura de dados que serve como uma coleção de elementos, e permite o acesso a somente um item de dados armazenados, o acesso aos itens de uma pilha é restrito - somente um item pode ser lido ou removido por vez.



###### 2 tipos de pilha:

**LIFO (Last In First Out)** ou **UEPS (Último Que Entra Primeiro Que Sai):**

Apresenta o seguinte critério: o primeiro elemento a ser retirado é o último que tiver seido inserido.

**E.:**

3º e último que entrou = 1º a sair

2º a entrar = sai depois do que entrou após ele

1º primeiro a entrar = último a sair



**FIFO (First Fn First Out)** ou **PEPS (Primeir que Entra Primeiro que Sai):** 

Apresenta seguinte critério: o primeiro elemento a ser retirado é o primeiro que tiver seido inserido.

3º e último que entrou = último a sair

2º a entrar = sai depois do que entrou antes dele

1º primeiro a entrar = 1º a sair





## AULA 18 - O Que São Filas

### Instrutor: Bruno de Campos Dias

**Filas:** admite remoção de elementos e inserção de novos elementos sujeita à seguinte regra de operação. 
O elemento removido é o que está na estrutura há mais tempo ou seja, o primeiro objeto inserido na fila é também o primeiro a ser removido seguindo o conceito **FIFO (PEPS)**.

Remove  <--			                                 	   ----- Insere
                   |				                                   |

​                | 1 |	| 2 |	| ... |	| n |	| n+1 |





## AULA 19 - Introdução e Objetivos

### Instrutor: Bruno de Campos Dias

Vamos falar sobre: Árvore, Tabela Hash e Grafos.





## AULA 20 - O Que São Árvores 

### Instrutor: Bruno de Campos Dias

**Árvore:** é uma estrutura de dados que organiza seus elementos de formar hierárquica, onde existe um elemento que fica no topo da árvore, chamado de raiz e existem os elementos subordinados a ele, que são chamados de nós ou folhas. 

 |

| 2 |	| 8 |	| 12 |	| 15 |	| 20 |	| 23 |	| 30 |

é um processo de busca que vai passar de numéro em número procurando, se buscarmos o 16 ele vai passar pelo 15 e 20 e não vai achar nada.

**Ex.:**

2	          12	  20                    30
|          	 |		|	                   |
|	           |		|	                   |
------8-------	  	--------23---------
       |			                               |
       |-----------------15--------------|





## AULA 21 - O Que São Tabelas Hash

### Instrutor: Bruno de Campos Dias

**Tabela Hash=** de **dispersão** = **espalhamento**= é uma estrutura de dados especial, que associa chaves de pesquisa a valores.

é uma generalização da idéia de *array*, porém utiliza uma função chamada *hashing* para espalhar os elementos, fazendo com que os mesmos fiquem de forma não ordenada e defina a tabela.

    a			    null
                    b
       d            null
    b		        a
          c			null
             e		e
                    d
                    c   

Permite a associação de "valores" as "chaves".



**Valores:** é a posição ou índices onde os elementos se encontram

**Chave:** parte da informação que compõe o elemento a ser manipulado.



###### Espalhar facilita a busca na estrutura de dados, pois a partir de uma chave podemos acessar de forma rápida uma do *arrya*.





## AULA 22 - O Que São Grafos

### Instrutor: Bruno de Campos Dias

**Grafos=**  são estruturas que permitem programar a relação entre objetos.



**Objetos:** são os **vértices** ou **nós** do **grafo** ( números / círculos ).

os relacionamentos são arestas ( \ ) e  ( /  ).

  6
    \
     4 - - 5
      \    \  \
       \    \   1
        \    \  /
        3 -  2