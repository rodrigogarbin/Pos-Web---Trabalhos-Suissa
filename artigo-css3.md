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
```css
	seletor { transform: translate(x, y); } 
  	seletor { transform: translateX(x); } 
  	seletor { transform: translateY(y); } 
``` 
##### Exemplo de uso:
```css
	seletor {
	  transform: translate(20px, 60px);
	} 
```



##### Funcionalidade: transform - rotate

##### O que é?
	Esta funcionalidade faz com que o elemento gire no seu proprio eixo ou nos eixos X, Y e Z

##### Onde usar:
	Em objetos que terão animação na pagina.

##### Como usar:
```css
	seletor {transform: rotate(αdeg); } 
	seletor {transform: rotateX(αdeg); } 
	seletor {transform: rotateY(αdeg); } 
	seletor {transform: rotateZ(αdeg); } 
```

##### Exemplo de uso:
```css
	seletor {
	  transform: rotate(260deg);
	}
	seletor {
	  transform: rotateX(260deg);
	}
	seletor {
	  transform: rotateY(260deg);
	}
	seletor 
	  transform: rotateZ(260deg);
	}
```




##### Funcionalidade: box-shadow

##### O que é?
	Gera um efeito de sombra no objeto.

##### Onde usar:
	Em caixas de texto ou elementos que flutuam na pagina.

##### Como usar:
```css
	seletor { box-shadow: inset offsetX offsetY raioBlur spread cor; }
```

##### Exemplo de uso:
```css
	seletor { box-shadow:  9px 31px 27px 0px black; } 
```




##### Funcionalidade: animation

##### O que é?
	Faz a animação de um elemento

##### Onde usar:
	Em elementos que serão animados na pagina.

##### Como usar:
```css
	seletor { animation: name duration timing-function delay iteration-count direction fill-mode play-state; }
```

##### Exemplo de uso:
```css
	seletor {
    	animation: mymove 5s infinite;
	}
```





##### Funcionalidade: recize

##### O que é?
	Permite o usuario redimencionar o tamanho do elemente

##### Onde usar:

##### Como usar:
```css
	seletor {
	  resize: none|both|horizontal|vertical|initial|inherit;
	}
```

##### Exemplo de uso:
```css
	seletor {
	  resize: vertical;
	}
```




##### Funcionalidade: @font-face

##### O que é?
	Garante que a fonte especificada vai ser renderizada indiferentemente se tem instalada no
	computador do usuario ou não

##### Onde usar:
	Em todos os elementos;

##### Como usar:
```css
	@font-face {
	  font-family: 'nome da fonte';
	  src: local('nome_fonte_no_computador'), url('local_da_fonte') format('formato_da_fonte');
	}
```

##### Exemplo de uso:
```css
	@font-face {
	  font-family: 'Arial';
	  font-style: normal;
	  font-weight: 400;
	  src: local('Arial'), local('Arial'), url(https://fonts.gstatic.com/s/Arial/v13/Arial.woff2) format('woff2');
	}
```





##### Funcionalidade: calc

##### O que é?
	Permite que se definam valores CSS com uso de expressões matemáticas.

##### Onde usar:
	Nas propriedades onde os valores podem ser um resultado de expressões matemáticas.

##### Como usar:
```css
	seletor { propriedade: calc(expressão matemática); }
```

##### Exemplo de uso:
```css
	seletor {
	 	width: calc(100% - 100px);
	}
```




##### Funcionalidade: HSLA

##### O que é?
	Com ele é possivel definir o brilho, satiração, tranparência e o hue de uma determinada propriedade;

##### Onde usar:
	Em elementos em que é possivel definir uma cor;

##### Como usar:
```css
	seletor { propriedade: hsla(H, S, L, A); } 
```

##### Exemplo de uso:
```css
	seletor { background: hsla(274, 58%, 94%, 0.3); } 
```




##### Funcionalidade: transform - scale

##### O que é?
	Causa o aumento/redução das dimensões de um elemento ao longo dos eixos x e/ou y.

##### Onde usar:
	Em qualquer elemento.

##### Como usar:
```css
	seletor { transform: scale(x, y); } 
  	seletor { transform: scaleX(x); } 
  	seletor { transform: scaleY(y); } 
```

##### Exemplo de uso:
```css
	seletor {
	  transform: scale(3, 2);
	}
	seletor {
	  transform: scaleX(3);
	}
	seletor {
	  transform: scaleY(2);
	}
```




##### Funcionalidade: rgba

##### O que é?
	Permite definir a opacidade em uma escala decimal de 0 a 1, juntamente com os valores RGB.

##### Onde usar:
	A qualquer elemento.

##### Como usar:
```css
	seletor {
	  background: rgba(cor1, cor2, cor3, opacidade);
	}
```

##### Exemplo de uso:
```css
	seletor {
	  background: rgba(0, 0, 0, 0.5);
	}
```



### Referencia:
[http://www.maujor.com/tutorial/interativo-css3/](http://www.maujor.com/tutorial/interativo-css3/)

[http://www.w3schools.com/cssref](http://www.w3schools.com/cssref)

[https://developer.mozilla.org/pt-BR/docs/Web/CSS/color_value#rgba()](https://developer.mozilla.org/pt-BR/docs/Web/CSS/color_value#rgba())