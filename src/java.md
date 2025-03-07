# CLASES JAVA 

Las clases Java son el corazón de la aplicación que permite el funcionamiento, la interacción y la extensibilidad del juego TicTacToe. 
Ayuda a garantizar una experincia agradable para el usuario.

Hacemos uso de PACKAGE GAME, que es un contenedor en Java que agrupa todas las clases relacionadas con la lógica y funcionalidad del juego TicTacToe.
  
1. Clase cell.java:
   Define el estado de cada celda del tablero, la cual puede ser "X" ó "O" o vacía (null).
  
![WhatsApp Image 2025-03-06 at 6 01 52 PM](https://github.com/user-attachments/assets/6a684b83-3a67-41dc-9a9b-48e2297af128)


2. Clase GameBean.java:
Contiene la lógica del juego y el estado del tablero (un arreglo de celdas).

![WhatsApp Image 2025-03-06 at 6 02 15 PM](https://github.com/user-attachments/assets/2dffd13a-1ec6-4b6e-8cd0-c6793cf7e571)
![WhatsApp Image 2025-03-06 at 6 02 36 PM](https://github.com/user-attachments/assets/d103d934-70b7-4a4d-92f0-028d6243b283)
![WhatsApp Image 2025-03-06 at 6 02 53 PM](https://github.com/user-attachments/assets/66955033-dfca-4f21-b2c9-260fe9dbd21c)
![WhatsApp Image 2025-03-06 at 6 03 13 PM](https://github.com/user-attachments/assets/161a33eb-b34b-49eb-9e01-e150ff4679ec)
![WhatsApp Image 2025-03-06 at 6 03 29 PM](https://github.com/user-attachments/assets/30ede063-b505-4afe-9329-96c91e0f7451)
![WhatsApp Image 2025-03-06 at 6 03 45 PM](https://github.com/user-attachments/assets/62849935-2805-494c-9056-8fdca6a54f30)



3. Clase EntryServlet.java:
Se encarga de manejar las peticiones del usuario al iniciar el juego. Este Servlet se conectaría con el GameBean para actualizar el estado del juego y manejar la lógica de juego. 

![WhatsApp Image 2025-03-06 at 6 04 20 PM](https://github.com/user-attachments/assets/97c0ad8a-b4b8-4ae1-b490-72997f8ba4bb)
![WhatsApp Image 2025-03-06 at 6 04 40 PM](https://github.com/user-attachments/assets/ef6cbd61-ab4f-4117-9e35-044f6efdab4c)



4. Clase GameServlet.java:
Inclluye funcionalidades adicionales, como reiniciar el juego. 

![WhatsApp Image 2025-03-06 at 6 05 02 PM](https://github.com/user-attachments/assets/91707594-53d0-4794-9837-5555fd87fca9)
![WhatsApp Image 2025-03-06 at 6 05 23 PM](https://github.com/user-attachments/assets/02275c20-756d-4893-a31f-b8d02c3e915a)
![WhatsApp Image 2025-03-06 at 6 05 41 PM](https://github.com/user-attachments/assets/dfff0906-46bc-4370-babf-a87a04365171)


