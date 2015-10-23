#### Unoesc Chapecó

#### Pós-graduação em Desenvolvimento Web, Cloud e dispositivos móveis - WebMob

#### Disciplina: HTML5+CSS3

#### Professor: Jean Carlo Nascimento

#### Acadêmico(a): Rodrigo Garbin

### Artigo de revisão de CSS3

##### Funcionalidade: transform - translate

##### O que é?
	Esta funcionalidade causa a translação de um elemento ao longo dos eixos X e/ou Y.

##### Onde usar:
	Em objetos que irão se movimentar na tela ou banners em sites.

##### Como usar:
	seletor { transform: translate(x, y); } 
  	seletor { transform: translateX(x); } 
  	seletor { transform: translateY(y); } 

##### Exemplo de uso:
	seletor {
	  transform: translate(20px, 60px);
	} 




##### Funcionalidade: transform - rotate

##### O que é?
	Esta funcionalidade faz com que o elemento gire no seu proprio eixo ou nos eixos X, Y e Z

##### Onde usar:
	Em objetos que terão animação na pagina.

##### Como usar:
	seletor {transform: rotate(αdeg); } 
	seletor {transform: rotateX(αdeg); } 
	seletor {transform: rotateY(αdeg); } 
	seletor {transform: rotateZ(αdeg); } 

##### Exemplo de uso:
	seletor {
	  transform: rotate(260deg);
	}
	seletor {
	  transform: rotateX(260deg);
	}
	seletor {
	  transform: rotateY(260deg);
	}
	seletor {
	  transform: rotateZ(260deg);
	}





##### Funcionalidade: box-shadow

##### O que é?
	Gera um efeito de sombra no objeto.

##### Onde usar:
	Em caixas de texto ou elementos que flutuam na pagina.

##### Como usar:
	seletor { box-shadow: inset offsetX offsetY raioBlur spread cor; }

##### Exemplo de uso:
	seletor { box-shadow:  9px 31px 27px 0px black; } 





##### Funcionalidade: animation

##### O que é?
	Faz a animação de um elemento

##### Onde usar:
	Em elementos que serão animados na pagina.

##### Como usar:
	seletor { animation: name duration timing-function delay iteration-count direction fill-mode play-state; }

##### Exemplo de uso:
	seletor {
    	animation: mymove 5s infinite;
	}





##### Funcionalidade: recize

##### O que é?
	Permite o usuario redimencionar o tamanho do elemente

##### Onde usar:

##### Como usar:
	seletor {
	  resize: none|both|horizontal|vertical|initial|inherit;
	}

##### Exemplo de uso:
	seletor {
	  resize: vertical;
	}





##### Funcionalidade: @font-face

##### O que é?
	Garante que a fonte especificada vai ser renderizada indiferentemente se tem instalada no
	computador do usuario ou não

##### Onde usar:
	Em todos os elementos;

##### Como usar:
	@font-face {
	  font-family: 'nome da fonte';
	  src: local('nome_fonte_no_computador'), url('local_da_fonte') format('formato_da_fonte');
	}

##### Exemplo de uso:
	@font-face {
	  font-family: 'Arial';
	  font-style: normal;
	  font-weight: 400;
	  src: local('Arial'), local('Arial'), url(https://fonts.gstatic.com/s/Arial/v13/Arial.woff2) format('woff2');
	}





##### Funcionalidade: calc

##### O que é?
	Permite que se definam valores CSS com uso de expressões matemáticas.

##### Onde usar:
	Nas propriedades onde os valores podem ser um resultado de expressões matemáticas.

##### Como usar:
	seletor { propriedade: calc(expressão matemática); }

##### Exemplo de uso:
	seletor {
	 	width: calc(100% - 100px);
	}




##### Funcionalidade: border-radius

##### O que é?

##### Onde usar:

##### Como usar:

##### Exemplo de uso:





##### Funcionalidade: border-radius

##### O que é?

##### Onde usar:

##### Como usar:

##### Exemplo de uso:





##### Funcionalidade: border-radius

##### O que é?

##### Onde usar:

##### Como usar:

##### Exemplo de uso:



### Referencia:
[http://www.maujor.com/tutorial/interativo-css3/](http://www.maujor.com/tutorial/interativo-css3/)
[http://www.w3schools.com/cssref](http://www.w3schools.com/cssref)
