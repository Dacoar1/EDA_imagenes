# EDA IMAGENES
El objetivo de este trabajo es crear un buscador de imagenes similares en base a descriptores de imagen 

Este proyecto se divide en varias partes:

La primera parte tratará de seleccionar los algoritmos o técnicas que nos permitan crear estas representaciones vectoriales de las imágenes. 

Seguidamente se realizará un análisis exhaustivo y visualización de las características de cara a estudiar la efectividad de las técnicas seleccionadas. 

Una vez hecho esto se realizarán diferentes experimentos para realizar la búsqueda, estos experimentos servirán para demostrar que técnicas son más efectivas en este caso, que sucede dependiendo de los vectores empleados y que pasaría si combinamos varias características extraídas con diferentes algoritmos en la búsqueda.

Se comienza realizando un EDA del dataset de las imagenes

Para poder realizar estas busquedas es necesario conocer los descriptores utilizados, en este caso serán 

- Color: Histograma RGB
- Forma: Histograma de gradientes orientados (HOG)
- Textura: Patrones binarios locales (LBP)

Para realizar la búsqueda se va a crear una base de datos que almacene todos los vectores de características de todas las imágenes. Lo que interesa ahora es extraer de cada imagen el vector de características de cada una de las tres técnicas empleadas.

La segunda parte del proyecto consiste en la Generación automática de descripción FEN en tableros de ajedrez
El objetivo de este proyecto es desarrollar un sistema que sea capaz de convertir una foto de una posición de ajedrez a un formato estructurado que pueda ser comprendido por motores de ajedrez, como la notación Forsyth-Edwards (FEN), ampliamente utilizada.

La notación Forsyth-Edwards (FEN) es un método estándar para describir una posición particular en un juego de ajedrez. Es útil para registrar juegos o para configurar tableros de ajedrez en una posición específica. La notación FEN encapsula toda la información necesaria para continuar un juego desde un punto particular.
