
## Resumen

En esta actividad, asumirás el papel de un analista de ciberseguridad que trabaja para una empresa que aloja el sitio web de cocina yummyrecipesforme.com. Los visitantes del sitio web experimentan un problema de seguridad al cargar la página web principal. Tu trabajo consiste en investigar, identificar, documentar y recomendar una solución al problema de seguridad. 

Al investigar el evento de seguridad, revisarás un registro de tcpdump. Tendrás que identificar los protocolos de red utilizados para establecer la conexión entre el usuario y el sitio web. Los protocolos de red son las reglas y estándares de comunicación que los dispositivos en red utilizan para transmitir datos. Desafortunadamente, los actores maliciosos también pueden utilizar protocolos de red para invadir y atacar redes privadas. Saber identificar los protocolos utilizados habitualmente en los ataques te ayudará a proteger la red de tu organización contra este tipo de eventos de seguridad.

Para completar la tarea, también tendrás que documentar lo que ocurrió durante el incidente de seguridad. A continuación, recomendarás una medida de seguridad que se podría implementar para prevenir problemas de seguridad similares en el futuro.

Asegúrate de completar esta actividad antes de continuar. En la siguiente parte del curso, podrás ver un ejemplo completo para compararlo con tu propio trabajo. No podrás acceder al modelo hasta que hayas finalizado esta actividad. 

## Escenario

Analiza el siguiente caso. Luego, completa las instrucciones paso a paso.

Eres un analista de ciberseguridad para yummyrecipesforme.com, un sitio web que vende recetas y libros de cocina. Un panadero descontento ha decidido publicar las recetas más vendidas del sitio web para que el público pueda acceder a ellas de forma gratuita. 

El panadero ejecutó un ataque de fuerza bruta para acceder al host de la web. Introdujo repetidamente varias contraseñas predeterminadas conocidas para la cuenta administrativa hasta que acertó con la correcta. Después de obtener las credenciales de acceso, pudo acceder al panel de administración y modificar el código fuente del sitio web. Incrustó una función de JavaScript en el código fuente que pedía a los visitantes que descargaran y ejecutaran un archivo al visitar el sitio web. Tras ejecutar el archivo descargado, los clientes eran redirigidos a una versión falsa del sitio web donde las recetas del vendedor ya estaban disponibles de forma gratuita.

Varias horas después del ataque, varios clientes enviaron correos electrónicos al servicio de asistencia de yummyrecipesforme. Se quejaban de que el sitio web de la empresa les había pedido que descargaran un archivo para actualizar sus navegadores. Los clientes afirmaron que, tras ejecutar el archivo, la dirección del sitio web cambió y sus computadoras personales comenzaron a funcionar más lentamente. 

En respuesta a este incidente, el propietario del sitio web intenta iniciar sesión en el panel de administración, pero no lo consigue, por lo que se pone en contacto con el proveedor de alojamiento del sitio web. Tú y otros analistas de ciberseguridad reciben el encargo de investigar este incidente de seguridad.

Para abordarlo, creas un entorno sandbox para observar el comportamiento sospechoso del sitio web. Ejecuta el analizador de protocolos de red tcpdump y escribes la URL del sitio web, yummyrecipesforme.com. En cuanto se carga el sitio web, se te pide que descargues un archivo ejecutable para actualizar tu navegador. Aceptas la descarga y permites que el archivo se ejecute. Entonces observas que tu navegador te redirige a una URL diferente, greatrecipesforme.com, que está diseñada para parecerse al sitio original. Sin embargo, las recetas que vende tu empresa ahora se publican ahora gratuitamente en el nuevo sitio web.  

Los registros muestran el siguiente proceso:

El navegador solicita una resolución DNS de la URL yummyrecipesforme.com.

El servidor DNS responde con la dirección IP correcta. 

El navegador inicia una solicitud HTTP para la página web.

El navegador inicia la descarga del malware.

El navegador solicita otra resolución DNS para greatrecipesforme.com.

El servidor DNS responde con la nueva dirección IP.

El navegador inicia una solicitud HTTP a la nueva dirección IP.

Un analista de alto nivel confirma que el sitio web se vio comprometido. El analista verifica el código fuente del sitio web. Nota que se ha agregado código JavaScript para solicitar a los visitantes del sitio web que descarguen un archivo ejecutable. El análisis del archivo descargado encontró un script que redirige los navegadores de los visitantes de yummyrecipesforme.com a greatrecipesforme.com. 

El equipo de ciberseguridad informa que el servidor web se vio afectado por un ataque de fuerza bruta. El panadero descontento pudo adivinar la contraseña fácilmente porque la contraseña de administrador seguía siendo la contraseña predeterminada. Además, no había controles para prevenir un ataque de fuerza bruta. 

Tu trabajo es documentar el incidente en detalle, incluida la identificación de los protocolos de red utilizados para establecer la conexión entre el usuario y el sitio web.  También debes recomendar una acción de seguridad a tomar para prevenir ataques de fuerza bruta en el futuro.