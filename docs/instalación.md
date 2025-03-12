# INSTALACIÓN TRES EN RAYA

Este documeneto proporciona las instrucciones necesarias para instalar y ejecutar el juego "Tres en Raya" en tu entorno local.

# 1. Requisitos del sistema:
Antes de instalar el juego, hay que asegurarse de cumplir con los siguientes requisitos:
- Java Development Kit (JDK) 17 o superior: Necesario para compilar y ejecutar el juego.
- Apache Tomcat 9+: para desplegar la aplicación en el servior widfly.
- Widfly: servidor de aplicaciones Java.
-  Navegador web: para poder jugar el juego; ejemplo: Google Chrome, Firefox o Edge.

# 2. Configuración del proyecto en Eclipse:
- Abrimos Eclipse y seleccionamos nuestro espacio de trabajo (workspace).
- Creamos un nuevo proyecto web dinámico (Tic_Tac_Toe).
- Seleccionamos widfly como el servidor objetivo.
- Aseguramos de marcar Generate web.xml deployment descriptor; para que Eclipse cree automáticamente el archivo web.xml, el ual permite definir los Servlets y su acceso en la aplicación.
- El código Java se guardará en src/main/java. 
