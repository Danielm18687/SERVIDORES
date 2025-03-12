# INSTALACIÓN TRES EN RAYA

Este documeneto proporciona las instrucciones necesarias para instalar y ejecutar el juego "Tres en Raya" en tu entorno local.


# 1. Requisitos del sistema:
Antes de instalar el juego, hay que asegurarse de cumplir con los siguientes requisitos:
- Java Development Kit (JDK) 17 o superior: Necesario para compilar y ejecutar el juego.
- Apache Tomcat 9+: para desplegar la aplicación en el servior wildfly.
- Wildfly: servidor de aplicaciones Java.
-  Navegador web: para poder jugar el juego; ejemplo: Google Chrome, Firefox o Edge.


# 2. Configuración del proyecto en Eclipse:
- Abrimos Eclipse y seleccionamos nuestro espacio de trabajo (workspace).
- Creamos un nuevo proyecto web dinámico (Tic_Tac_Toe).
- Seleccionamos widfly como el servidor objetivo.
- Aseguramos de marcar Generate web.xml deployment descriptor; para que Eclipse cree automáticamente el archivo web.xml, el ual permite definir los Servlets y su acceso en la aplicación.
- El código Java se guardará en src/main/java. Para más detalle: https://github.com/Danielm18687/SERVIDORES/blob/TicTacToe/src/java.md


# 3. Desarrollo y Codificación del juego:
- Implementa la lógica del juego en Java dentro de src/main/java.
- webapp/index.html es la página principal del juego.
- webapp/css/estilos/estilos.css son los estilos visuales del tablero.
- webapp/js/script.js es la funcionalidad del juego e interacción.

Revisión con más profundidad acerca de la arquitectura del juego: https://github.com/Danielm18687/SERVIDORES/blob/TicTacToe/docs/arquitectura.md


# 4. Configurar Wildfly en Eclipse:
- Agregamos el servidor a Eclipse desde Servers.
- Seleccionamos a Wldfly como nuevo servidor.
- En la pestaña Servers damos click derecho sobre wildfly y seleccionamos Add And Remove...
- Agregamos el proyecto Tic_Tac_Toe.


# 5. Ejecutar el juego en el navegador:
- Iniciar Apache Tomcat, accedemos a http://localhost:8080/manager/html.
- Desde Eclipse damos click derecho sobre Tic_Tac_Toe.
- Seleccionamos Run As, Run on Server y elegimos Tomcat.
- Eclipse compilará y desplegará la aplicación automáticamente.
- vamos a http://localhost:8080/Tic_Tac_Toe/ en Chrome.
- Ya se puede jugar.

![WhatsApp Image 2025-03-11 at 9 18 42 PM](https://github.com/user-attachments/assets/09dff9da-5618-42d3-920d-134c01ad5074)


