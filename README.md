# TraductorInteractivo
Traductor de ingles a español en el cual el usuario es quien establece las traducciones

ESPECIFICACIONES:

Lenguaje de programación: Java (APK 15)

Motor de base de datos: Sql server 2019

FUNCIONALIDAD:

El programa permite al usuario ingresar una palabra en ingles y a la misma asignarle sus diferentes significados (hasta 10) y en el caso de que esta palabra
sea un verbo pasado como por ejemplo "fell" permite señalar cual es la forma en presente de ese verbo, que en el caso del ejemplo seria "fall". Todo esto que se ingresa
se muestra en una tabla en donde se ven todas las palabras en ingles con sus respectivos significados, separados por conjuntos de 10, conjuntos que se representan como
paginas. Además se puede tanto modificar como eliminar cada palabra con su respectivo conjunto de significados. 

Otra funcionalidad que hay es el filtro, el cual permite buscar en base a 4 criterios, el numero de una pagina (conjunto de palabra), la palabra en ingles que es traducida,
una de las traducciones al español y la forma en presente de un verbo en pasado.

COMANDOS

Dentro del formulario donde se nos permite agregar o modificar una palabra al apretar la tecla "enter" en todos los campo de textos (exceptuando el campo de texto donde se
ingresa la palabra a traducir) se acciona el agregado o la modificación. Esto tambien ocurre con el campo de texto que se encuentra en el formulario en donde esta la tabla con las
palabras y se utiliza para ingresar el filtro deseado, pero en vez de agregar o modificar una palabra, muestra el resultado del filtro en la tabla.

Dentro del formulario donde se nos permite agregar o modificar una palabra al apretar la tecla "escape" en el campo de texto en donde se encuentra la palabra en ingles a traducir
se cierra este formulario mostrándonos el formulario en donde se encuentra la tabla que contienen todas las palabras registradas.
