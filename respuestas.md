aN 

UNIVERSIDAD MESOAMERICANA 

|**Formato**|**Peso en KB**|**¿Se ve peor? ¿Dónde exactamente?**|
|---|---|---|
|**Original**|42 KB|Se ve bien, es la mejor calidad.|
|**JPG**|42 KB|Al hacer zoom la calidad baja|
|**PNG**|292 KB|Es como la original|
|**WebP**|24 KB|Los bordes tienen se ven pixelados y de colores con zoom.|
|**AVIF**|44 KB|Los bordes se ven borrosos.|



# **¿Cuál eligió para su hoja de vida y por qué?** 

La fotografía mide 980x980. La mejor es avif para que cargue mas rápido, y es el que esta de primero dentro de la etiqueta de picture. 

# **¿El resultado se parece al de la imagen de clase o salió distinto? Si salió distinto, ¿qué tiene su foto que la otra imagen no tenía?** 

Es diferente en comparación al de la clase. El que coloque en mi hoja de vida tiene colores mas definidos y no tiene ningún degradado, entonces el PNG que es el mas pesado ocupa solo 292 KB en comparación al de la clase, el avif era el mas ligero en mi caso fue el JPG. 

# **Pregunta 1** 

**Su formulario tiene un campo de fecha con un calendario que aparece al hacer clic. Averigüe si ese calendario se puede cambiar de color, de tamaño o de tipografía. Explique qué encontró y por qué es así.** 

R: El color no es posible modificar el navegador es el encargado de la apariencia, el tamaño del calendario tampoco es posible de modificar solo el input y la tipografia tampoco es posible de modificar. Ocurre porque es un elemento nativo de cada navegador y permite una accesibilidad por ello no es posible personalizarla es como un estándar para el type = date. 

# **Pregunta 2** 

**En clase escribió required y min en su HTML. Averigüe qué son :valid e :invalid, y explique qué relación tienen con esos atributos que ya escribió.** 

R: Son pseudo clases de CSS que sirven para la validación de formularios (Client side form Validation Api) Sirve para evaluar en tiempo real si la entrada dentro de un input, select o textarea cumple con las restricciones 

# **Pregunta 3** 

**Su img tiene width y height con las dimensiones reales del archivo. Si esa imagen se abre en un teléfono, va a salirse de la pantalla. Averigüe qué hace falta para que se adapte al ancho disponible, y por qué no alcanza con cambiar los números del width.** 

Lo que se hace es que la imagen sea responsiva, esto se logra de forma efectiva con CSS, utilizando el atributo de max-width: 100% para hacer que la imagen se ajuste al ancho disponible del teléfono. 

