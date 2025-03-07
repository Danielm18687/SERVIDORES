# CLASES JAVA 

Las clases Java son el corazón de la aplicación que permite el funcionamiento, la interacción y la extensibilidad del juego TicTacToe. 
Ayuda a garantizar una experincia agradable para el usuario.

Hacemos uso de PACKAGE GAME, que es un contenedor en Java que agrupa todas las clases relacionadas con la lógica y funcionalidad del juego TicTacToe.
  
1. Clase cell.java:
   Define el estado de cada celda dle tablero, la cual puede ser "X" ó "O" o vacía (null).
  
![WhatsApp Image 2025-03-06 at 6 01 52 PM](https://github.com/user-attachments/assets/6a684b83-3a67-41dc-9a9b-48e2297af128)


2. Clase GameBean.java:
Contiene la lógica del juego y el estado del tablero (un arreglo de celdas).

![WhatsApp Image 2025-03-06 at 6 02 15 PM](https://github.com/user-attachments/assets/2dffd13a-1ec6-4b6e-8cd0-c6793cf7e571)


4. Clase EntryServlet.java:
Se encarga de manejar las peticiones del usuario al iniciar el juego. Este Servlet se conectaría con el GameBean para actualizar el estado del juego y manejar la lógica de juego. 

![WhatsApp Image 2025-03-06 at 6 04 20 PM](https://github.com/user-attachments/assets/97c0ad8a-b4b8-4ae1-b490-72997f8ba4bb)


4. Clase GameServlet.java:
Inclluye funcionalidades adicionales, como reiniciar el juego. 

![WhatsApp Image 2025-03-06 at 6 05 02 PM](https://github.com/user-attachments/assets/91707594-53d0-4794-9837-5555fd87fca9)

