<gs-attire attire-url="https://raw.githubusercontent.com/MumukiProject/mumuki-guia-gobstones-villa-mercedes-secundaria/master/assets/attires/config_1587581050568.json"></gs-attire>

Hasta ahora cerramos solo una barrera pero, como el recorrido del tren es largo y no siempre el mismo, vamos a encontrar más de una :sweat_smile:. Por suerte ya creaste todo lo necesario para cerrarlas :raised_hands:. ¡A programar!

<gs-board>
     GBB/1.0
     size 6 3
     cell 0 2 Verde 1 
     cell 1 2 Verde 1 
     cell 2 2 Verde 1 Negro 1 
     cell 4 2 Verde 1 
     cell 0 1 Azul 1 
     cell 1 0 Verde 1 
     cell 2 0 Rojo 1 Negro 1 
     cell 3 0 Rojo 1 Negro 1 
     cell 5 0 Rojo 1 
     head 0 0
</gs-board>

> Dado el tablero anterior, creá el programa para controlar todas las barreras teniendo en cuenta que la longitud del tablero puede cambiar. Comenzaremos en el extremo inferior izquierdo y te dejamos hecha la función `hayBarrera` por si la llegas a necesitar.