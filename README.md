# portfolio_cliente01
Trabalho Realizado para o Cliente 01

Foi utilizado WordPress 5.2.4, mudança do prefixo das tabelas do WordPress, PHP 7.1.33, tema filho do WordPress (com programação em PHP) e CSS Adicional.

Power Point Enviado Pelo Cliente:

![](https://github.com/paulo-correia/portfolio_cliente01/blob/master/Power_point_enviado.png?raw=true)

Tema Modificado:

![](https://github.com/paulo-correia/portfolio_cliente01/blob/master/Tema_modificado.png?raw=true)

Tema Original:

![](https://github.com/paulo-correia/portfolio_cliente01/blob/master/Tema_original.png?raw=true)

CSS Adicional Aplicado:

```
/* Cirulos em volta dos ícones */
.circle {
	    border:2px solid #EDEDED;    
    height:54px;
    border-radius:50%;
    -moz-border-radius:50%;
    -webkit-border-radius:50%;
    width:54px;
	  margin-top: 23px;
	  margin-bottom: 23px;
	  font-size: 20px;
}
/* Texto a Esquerda */
.txt-left {
	margin-top: 27px;
}
.middle-icon {
vertical-align: -webkit-baseline-middle;	
}
/* Linha acima do segundo container */
.container2 {
	border-top-style: solid;
  border-width: 1px;
}
/* Menu em MAIUSCULAS */
.navigation > li > a {
	padding-top: 10px;
	padding-bottom: 10px;
	text-transform: uppercase;
}
/* Correções para responsivo */
@media (max-width: 991px) {
	.res-icons {
		display: none; }
	.container2 {
		border-top-style: none;
	}
}
@media (min-width: 992px) and (max-width: 1024px) {
	.televendas {
		width: 10.0248%;
		padding-left: 5px;
		padding-right: unset;
	}
	.zapzap {
		width: 11.1625%;
		padding-left: 5px;
		padding-right: unset;
	}
	.email {
		width: 15.2765%;
		padding-left: 5px;
		padding-right: unset;
	}
	.contato {
		width: 15.5765%;
		padding-left: 5px;
		padding-right: unset;
	}
}
@media (min-width: 1025px) and (max-width: 1199px) {
	.televendas {
		width: 10.9248%;
		padding-left: 10px;
		padding-right: 5px;
	}
	.zapzap {
		width: 12.1625%;
		padding-left: 10px;
		padding-right: 5px;
	}
	.email {
		width: 16.0765%;
		padding-left: 10px;
		padding-right: unset;
	}
	.contato {
		width: 10.9129%;
		padding-left: 10px;
		padding-right: unset;
	}
}
@media (min-width: 1200px) {
	.televendas {
		width: 10.0248%;
		padding-left: 10px;
		padding-right: unset;
	}
	.zapzap {
		width: 11.0625%;
		padding-left: 10px;
		padding-right: unset;
	}
	.email {
		width: 13.9765%;
		padding-left: 10px;
		padding-right: unset;
	}
	.contato {
		width: 10.4129%;
		padding-left: 10px;
		padding-right: unset;
	}
}
@media (min-width: 991px) and (max-width: 1200px) {
	.top-bar .col-left {
		text-align: left;
	}
	.social-icon {
		margin-top: -50px;
	}
}
@media (min-width: 768px) and (max-width: 991px) {
	.social-icon {
		margin-top: -50px;
	}
}
@media (max-width: 768px) {
	.float_right {
		text-align: center;
		float: none;
	}
}
@media (max-width: 768px)
{
	.col-left {
		text-align: left !important;
	}
	.float_right {
		text-align: left;
		float: right;
	}
}
```


