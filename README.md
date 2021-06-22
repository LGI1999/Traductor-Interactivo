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

MOTIVACIONES DEL PROGRAMA

La particular funcionalidad del programa nace de mi método de estudiar en ingles, ya que esta manera de tener una palabra en ingles con sus significados es la manera en que
estudio ingles pero antes del programa lo hacia con un cuaderno. 

FUTURAS MEJORAS

Estructura de la base de datos: Mi idea actual es quitar la tabla donde están todos los significados y reemplazarla por una tabla con los significados en español y una tabla
intermedia entre la tabla con las palabras en ingles y esta nueva tabla con las palabras en español, esto para no repetir los significados en español.

Clases: Considero que la separación actual de los métodos no es muy intuitiva, por eso quiero organizar los diferentes métodos para así tener clases que tengan un significado
bien marcado y se entienda de mejor manera el código. Igualmente esta todo comentado, pero creo que no le vendría mal esta organización.

Minijuegos: Esto no lo tengo muy definido todavía, pero tengo unos cuantos minijuegos en mente, como uno en donde se muestre una palabra en español y se deba ingresar los diferentes
significados en ingles que tiene esa palabra.

Interfaz: La interfaz necesita una completa mejora, desde el diseño hasta el ajuste de tamaño de los diferentes controles que tienen los formularios.

COMANDOS

Dentro del formulario donde se nos permite agregar o modificar una palabra al apretar la tecla "enter" en todos los campo de textos (exceptuando el campo de texto donde se
ingresa la palabra a traducir) se acciona el agregado o la modificación. Esto tambien ocurre con el campo de texto que se encuentra en el formulario en donde esta la tabla con las
palabras y se utiliza para ingresar el filtro deseado, pero en vez de agregar o modificar una palabra, muestra el resultado del filtro en la tabla.

Dentro del formulario donde se nos permite agregar o modificar una palabra al apretar la tecla "escape" en el campo de texto en donde se encuentra la palabra en ingles a traducir
se cierra este formulario mostrándonos el formulario en donde se encuentra la tabla que contienen todas las palabras registradas.
