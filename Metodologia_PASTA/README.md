Compara el ejemplo con tu actividad terminada. Revisa tu trabajo utilizando cada uno de los criterios del ejemplo. ¿Qué hiciste bien?  ¿En qué aspectos podrías mejorar? Las respuestas a estas preguntas te servirán como guía a medida que avances en el curso.  

Nota: El ejemplo representa una forma posible de completar la actividad. Es probable que la tuya difiera en algunos aspectos. Lo importante es que tu actividad incluya información en cada etapa del proceso. El modelado de amenazas es una práctica avanzada en ciberseguridad. Normalmente, es necesario contar con experiencia en el campo, un profundo conocimiento de la tecnología informática y la participación de muchas personas diferentes.

Repasemos cada etapa de este ejercicio de modelado de amenazas con metodología PASTA:

### Etapa I: Definición de objetivos comerciales y de seguridad
Resumen: Estos objetivos se definen al principio, al formular preguntas generales sobre el propósito de la aplicación. Por ejemplo, ¿de qué manera la aplicación hace que el negocio gane dinero? Comprender la respuesta a estas preguntas ayuda a guiar el trabajo detallado que seguirá.

Recomendaciones: Una aplicación de compras como esta tendrá que procesar los pagos. A partir de esta descripción, sabemos que se debe contar con ciertas tecnologías para que la información se mantenga privada y segura y que se cumpla con el Estándar de Seguridad de Datos para la Industria de Tarjetas de Pago, o PCI-DSS.

### Etapa II: Definición del alcance técnico
Resumen: El objetivo aquí es comprender la superficie de ataque mediante la identificación de las tecnologías que la aplicación utiliza y la comprensión de sus dependencias.

Recomendaciones: Las API (interfaces de programación de aplicaciones) facilitan el intercambio de datos entre clientes, socios y empleados, por lo que deben priorizarse. Manejan una gran cantidad de datos confidenciales al conectar varios usuarios y sistemas. Sin embargo, se deben considerar detalles como cuáles son las API que se están utilizando antes de priorizar una tecnología sobre otra. En otras palabras, pueden ser más propensas a vulnerabilidades de seguridad porque la superficie de ataque es mayor.

### Etapa III: Descomposición de la aplicación
Resumen: La tercera etapa se basa en la etapa anterior e implica investigar cómo los componentes de la aplicación se comunican entre sí. El objetivo es revisar cómo funciona la aplicación y cómo se implementan actualmente los controles de seguridad.

Recomendaciones: El diagrama de flujo de datos de muestra indica cómo una solicitud de búsqueda típica pasa a través de diversas capas. Algo que puedes hacer es asegurarte de que la base de datos MySQL esté utilizando sentencias preparadas al ingresar las consultas.

### Etapa IV: Análisis de amenazas
Resumen: El objetivo principal de la etapa cuatro es considerar los tipos de amenazas que podrían afectar a tu aplicación. Esto se relaciona con las tecnologías que ya evaluaste. Otro aspecto que debes considerar es los tipos de datos que tu aplicación procesará.

Recomendaciones: Los ataques de inyección son comunes para las bases de datos SQL. El secuestro de sesiones es posible porque la aplicación comunica cookies entre varias capas. Es importante considerar la superficie de ataque tecnológico y cualquier amenaza relevante para tu producto, a fin de implementar efectivamente tus responsabilidades de seguridad de la información.

### Etapa V: Análisis de vulnerabilidades
Resumen: La etapa cinco consiste en asociar las vulnerabilidades de los activos con amenazas potenciales. El objetivo es identificar posibles problemas con el diseño de la aplicación o su base de código, en función de las pruebas de seguridad que realices.

Recomendaciones: La falta de sentencias preparadas puede hacer que nuestra base de datos SQL sea vulnerable a los ataques de inyección. Además, el secuestro de sesión se hace posible si las cookies se manejan mal entre las fuentes de entrada y salida.

### Etapa VI: Modelado de ataques
Resumen: En esta etapa, el objetivo es vincular las amenazas y vulnerabilidades identificadas en los pasos anteriores mediante el uso de árboles de ataque. El propósito de esto es mostrar que las amenazas potenciales que identificaste son realmente viables. Recursos como MITRE ATT&CK y la lista CVE® son referencias útiles para encontrar evidencia que valide la información que incluiste en tu árbol de ataques.

Recomendaciones: Este ejemplo de árbol de ataques muestra cómo los datos de usuario son vulnerables a los ataques que se identificaron antes. Al igual que el diagrama de flujo de datos de muestra, un árbol de ataque real para una aplicación móvil sería mucho más complejo que esto.

### Etapa VII: Análisis de riesgos e impacto
Resumen: El objetivo de la etapa final de la metodología PASTA es identificar formas de mitigar los riesgos que se detectaron en las etapas IV a VI y planificar los riesgos restantes que no se pueden remediar.

Recomendaciones: El cifrado SHA-256, los procedimientos de respuesta a incidentes, la política de contraseñas y el principio de mínimo privilegio son algunos ejemplos de controles técnicos, operativos y de gestión que pueden implementarse antes del lanzamiento para reducir el riesgo.