
FuenteS: Oxygen light 300, y la Montserrat extrabold 800
El kit de fontawesome, ya que hay varios iconos 
Enlaces a los estilos 

HTML: 1 página dividida en 3 bloques: Navigation, Hero section, footer, y un page-bottom al final.

CSS: common, navigation, hero, footer, page-bottom, y una hoja aparte para los botones (buttons).

ESTRUCTURA:

-NAVIGATION WRAPPER

Se trata de una barra con tres secciones, alineado con FLEXBOX, en la izquierda se encuentra el logo, seguido el “explore-wrapper, el cual he alineado con GRID, para poder incluir el encabezado de la sección encima, y los botones los he alineado dentro del este, con FLEXBOX. Seguido un botón de spark con un chevron. A la izquierda de la barra se encuentra el “login-wrapper”, con cuatro botones, uno de ellos de nuevo con un chevron dentro, un icono de lupa, que actúa como botón, el cual llamo de  FONTAWESOME. Los botones se encuentran definidos en el css propio, así como su hover.



-HERO SECTION
Fondo con gradiente entre gris y negro
Dividido en dos columnas, con FLEXBOX. He evitado que se desborde hacia abajo con overflow: hidden.


	-LEFT COLUMN
		-TOP HEADER 
			Dividido con FLEXBOX, column.
			Texto con una parte en <strong>, definido en css
                		*el icono de la mano, lo he copiado de la web https://emojis.wiki/es/mano-saludando/
		-BOTTOM HEADER
			Texto en menor tamaño que el anterior 
		-BUTTONS WRAPPER
			dos botones, definidos individualmente. Divididos con flexbox, y space-between
	-RIGHT COLUMN
			Dividido con FLEXBOX, column.
		-IMAGE HEADER
			Se trata de un texto de encabezamiento, con dos colores, que además actúa como botón
		-IMAGE
			le he aplicado un ligero sombreado, le he definido el tamaño, y la he dejado pegada al margen inferior/derecho de la sección.
			
-FOOTER
		Color de fondo gris. Cuatro botones, alineados con FLEXBOX, space-evenly, con borde en gris un tono mas claro que el fondo.

-PAGE BOTTOM
		Fin de la página

BIBLIOGRAFÍA

Además de los recursos del propio curso, he consultado varias webs y foros, entre ellas:
	https://www.w3schools.com/
	https://developer.mozilla.org/en-US/
	https://google.github.io/styleguide/htmlcssguide.html
	https://es.stackoverflow.com/
