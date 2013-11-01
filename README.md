# Sobre

Aqui são disponibilizados os estilos utilizados pela [One.Stop.Transport](https://www.ost.pt). Com eles, é possível tornar as aplicações desenvolvidas mais próximas do contexto da OST.

Este projecto encontra-se em desenvolvimento e tem como objectivo explicar como compilar os estilos numa aplicação *web* a submeter no [catálogo de aplicações](https://www.ost.pt/store/web) da OST.


# Instruções

* Instalar um [compilador de LESS](http://lesscss.org/) para CSS;
* Correr a instrução na linha de comandos (na directoria raiz deste projecto):

	`lessc -x bootstrap/bootstrap.less > bootstrap/bootstrap.css`
	
* Importar esse ficheiro no código HTML:

	`<link href="bootstrap.css" rel="stylesheet">`

# Sugestões / Problemas

Em caso de problema ou sugestão, por favor use o nosso [fórum de suporte](https://support.ost.pt).