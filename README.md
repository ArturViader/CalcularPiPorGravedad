# CalcularPiPorGravedad
Cálculo de los primeros decimales de Pi con varios métodos y también con un método propio gravitatorio
Método que he inventado para trazar círculos perfectos simulando dos ejes con gravedad.
No se si este algoritmo ya existía o he descubierto algo. El pi calculado se acerca mucho.

El programa empieza simulando un objeto al lado de un centro de atracción que lo atrae.
La gravedad aumenta al alejarse del centro y disminuye llegando a 0 en el centro.
El resultado es que el objeto oscila de lado a lado como si fuera un péndulo.

Al llegar al punto medio del movimiento, punto de máxima velocidad se inicia otro movimiento de una dimensión idéntico para el eje y.

Con las coordenadas x e y se obtiene un círculo.

He logrado ajustar las componentes vertical y horizontal a la perfección manipulando el tiempo, aplicando un freno a las fuerzas para ello.

He aumentado la resolución mucho para que se acerque a pi. Suma unidades de 0,0000000000001 y la pantalla mide más de 1 millón.
La imagen 1080p solo representa una pequeña parte de esa inmensa resolución.
Cambiando a 4k se logra un decimal más.

El pi obtenido contiene muchas cifras del que nos dice la ciencia:
3.1415926535

Para obtener pi he obtenido en cada ciclo de ejecución o momento de tiempo la velocidad x y la velocidad y aplicándoles el teorema de pitágoras para obtener la velocidad real en dos dimensiones. De esta forma calculo la distancia recorrida.

Para llegar a más decimales se necesitarían una resolución y un tiempo de ejecución muy altos.
