# ARCHIVOS RELACIONADOS CON LA INTERFAZ GRÁFICA DEL JUEGO TRES EN RAYA.

La carpeta webapp contiene en el proyecto contiene los archivos relacionados con la interfaz web y la interacción del usuario.
Esta carpeta es importante en las aplicaciones web, ya que aquí es donde se organizan los archivos que el usuario final verá y con los que interactuará en el navegador.

Está organizada en subdirectorios para imágenes, configuración del servidor y archivos principales que permiten la ejecución del juego en la web.

1. img (imágenes del juego): 
- Esta carpeta se usa para almacenar imágenes necesarias en el juego, como fichas, fondo de pantalla o íconos.
- En los archivos JSP se referencian imágenes desde esta carpeta.
Aquí se encunetra una explicación más detallada del uso de las imágenes: https://github.com/Danielm18687/SERVIDORES/edit/TicTacToe/assets/imagenes.md


2. META-INF:
- Esta carpeta por lo general es administrada por el servidor de aplicaciones y no se debe modificar manualmente, ya que se encuentran archivos de metadatos usados por el servidor.


3. WEB-INF (configuración del servidor y seguridad):
- web.xml: define los servlets utilizados, mapeos de rutas y filtros de seguridad. Aquí se define el acceso de GameServlet.java y EntryServlet.java
- Todos los archivos dentro de WEB-INF están protegidos y no pueden ser accedidos directamente por el usuario final en el navegador.


4. index.jsp (página principal del juego - pantalla de inicio):
- Define la página inicial a la que los usuarios ingresan cuando acceden al juego.
- Encabezado y título del juego:
  
  ![WhatsApp Image 2025-03-15 at 5 23 11 PM](https://github.com/user-attachments/assets/768615a7-1287-4052-8cab-18ecfb5e2d25)

- Botón para iniciar el juego (redirige a game.jsp): 

![WhatsApp Image 2025-03-15 at 5 23 31 PM](https://github.com/user-attachments/assets/c8d135d2-89b0-4b60-928c-f21b925ec265)

5. game.jsp (interfaz donde se juega la partida):
- Aquí se representa de forma gráfica el tablero y se ejecutan las interacciones enre los jugadores.
- Tablero del juego (HTML + CSS + JavaScript para la lógica dinámica).
- Manejo de turnos entre jugadores ("X" y "Y").
- Comunicación con GameServlet. java para procesar movimientos.
- Coondiciones de victoria o empate.


Con esta estructura bien organizada, el juego debería ejecutarse correctamente en el servidor wildfly. 

