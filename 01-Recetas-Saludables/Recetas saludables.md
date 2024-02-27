Recetas saludables


¡Usando selectores CSS, le darás un nuevo estilo a un sitio web de recetas!

Si se queda atascado durante este proyecto o le gustaría ver a un desarrollador experimentado trabajar en él, haga clic en " Desatascarse " para ver un video tutorial del proyecto .

Tareas
5/5 completo _ _
Marque todas las tareas a medida que avanza. Una vez que esté todo completo, podrá completar el proyecto.

Antes de comenzar, eche un vistazo a la estructura del sitio en index.html .

Comience haciendo la imagen en la parte superior de la página un poco más pequeña. Navegue hasta style.css y escriba un selector CSS para la imgetiqueta.

Dentro de sus llaves, escriba:

height: 150px;

Intente experimentar con el 150número y observar los resultados.


Obtén un consejo

El tamaño de fuente de la descripción de la receta debe ser mayor. En style.css , escribe un selector de CSS para la .descriptionclase.

Dentro de sus llaves, agregue el siguiente CSS:

font-size: 20px;


Obtén un consejo

A continuación, diseñemos el tiempo de cocción. El elemento de la línea 15 de index.html tiene el idatributo cook-time. Navegue hasta style.css y agregue un cook-timeselector de ID.

Dentro de sus llaves, escriba:

font-weight: bold;


Obtén un consejo

Ahora, cambiemos las viñetas de la lista de ingredientes a cuadrados en lugar de círculos. Comience escribiendo un selector para los lielementos dentro del .ingredientselemento.

Luego, escribe esto dentro de sus llaves:

list-style: square;


Obtén un consejo

A continuación, hagamos que el tiempo de cada paso de preparación aparezca en gris. En style.css , escriba un selector para pelementos que también tengan una clase de .time.

Luego, dentro de las llaves de este selector, escriba:

color: gray;


Obtén un consejo

Al final de la página, hay un enlace a la receta completa. Hagamos que el enlace tenga un color diferente.

Observe que en index.html , en la línea 42, hay un pelemento con una clase de citation, luego un aelemento dentro con una clase de external-link. Navegue hasta style.css y escriba un selector usando external-linkclass.

Luego, agregue este código dentro de las llaves del selector:

color: SeaGreen;


Obtén un consejo

Finalmente, hagamos la fuente Helvetica en lugar de la Times New Roman predeterminada. En lugar de escribir varios selectores para aplicar la font-familypropiedad, escriba un selector que aplique un font-familyatributo a todo el texto a la vez.

El selector debe apuntar a los elementos h1, h2, py li.

Para cambiar su fuente, incluya esta línea de código dentro de las llaves:

font-family: Helvetica;


Obtén un consejo
¡Has superado la línea de meta! Si ha terminado, asegúrese de marcar todas las tareas de este proyecto.