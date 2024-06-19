
# Auditoria Botium Toys

## Escenario

`Este escenario se basa en una empresa ficticia:`

Botium Toys es una pequeña empresa estadounidense que desarrolla y vende juguetes. La empresa tiene una sola sede física. Sin embargo, su presencia en línea ha crecido, atrayendo a clientes de Estados Unidos y del extranjero. Su departamento de tecnología de la información (TI) está sometido a una presión cada vez mayor para dar soporte a su mercado en línea en todo el mundo. 

La gerente del departamento de TI ha decidido que es necesario realizar una auditoría interna de TI. Expresa su preocupación por no tener un plan de acción consolidado para garantizar la continuidad del negocio y el cumplimiento de la normativa, a medida que la empresa crece. Cree que una auditoría interna puede ayudar a asegurar mejor la infraestructura de la empresa y ayudar a identificar y mitigar los posibles riesgos, amenazas o vulnerabilidades de los activos críticos. La gerente también está interesada en `asegurarse de que cumplen con la normativa relacionada con la aceptación de pagos en línea y la realización de negocios en la Unión Europea (UE)`.   

La gerente de TI comienza aplicando `el Marco de Ciberseguridad (CSF) del Instituto Nacional de Estándares y Tecnología (NIST)`, estableciendo un alcance y unos objetivos de auditoría y completando una evaluación de riesgos. El objetivo de la auditoría es proporcionar una visión general de los riesgos que la empresa podría experimentar debido al estado actual de su postura de seguridad. La gerente de TI quiere utilizar los resultados de la auditoría como prueba para obtener la aprobación para ampliar su departamento. 

Tu tarea consiste en `revisar el alcance, los objetivos y la evaluación de riesgos de la gerente de TI`. Luego, realiza una auditoría interna para completar una evaluación de los controles y una lista de verificación de cumplimiento.

### Tareas

- Revisar el correo ficticio de la Gerente del departamento de TI ([correo_ficticio.txt](https://github.com/KevsCha/Ciberseguridad/blob/main/Auditoria_botium/Correo_ficticio.txt))
- Leer los documentos Botium ([alcance y objetivo](https://github.com/KevsCha/Ciberseguridad/blob/main/Auditoria_botium/bottium_alcancesyObejetivos.pdf)) y Botium ([riesgos y activos](https://github.com/KevsCha/Ciberseguridad/blob/main/Auditoria_botium/Bottium_RiesgosyActivos.pdf))
- Hacerces las siguientes preguntas... [Tener en cuenta](#Tener encuenta)
- Hacer la auditoria con el siguiente documento [Evaluacion de control](https://github.com/KevsCha/Ciberseguridad/blob/main/Auditoria_botium/Evaluacion%20de%20Controles.pdf) para ir seleccionando que tipo de control aplicarse segun los activos dados en los anteriores documentos y darle una prioridad baja, media o alta (*MARCAR CON UNA 'X' LOS CONTROLES QUE APLIQUEN*) 
- Inspeccionar las normativas que se puedan aplicar al caso hipotetico (Botium Toys) en el siguiente documento [Lista de control de cumplimiento normativo](https://github.com/KevsCha/Ciberseguridad/blob/main/Auditoria_botium/Lista%20de%20verificaci%C3%B3n%20de%20cumplimiento%20normativo.pdf) (*EXPLICAR EL USO DE LA NORMATIVA SELECCIONADA*)
- `Ejemplos de como deberia haber finalizado la evaluacion de control y la seleccion de normas adecuadas` EXAMPLES [Evaluacion de control](https://github.com/KevsCha/Ciberseguridad/blob/main/Auditoria_botium/Tareas%20Realizadas/Ejemplo_correctos/EXAMPLE_Evaluacion%20de%20Controles.pdf) y [Lista de cumplimiento normativo](https://github.com/KevsCha/Ciberseguridad/blob/main/Auditoria_botium/Tareas%20Realizadas/Ejemplo_correctos/EXAMPLE_Lista%20de%20verificacion%20de%20cumplimiento%20normativo.pdf)


## Tener en cuenta
Tras revisar el alcance, los objetivos y la evaluación de riesgos de la auditoría, ten en cuenta las siguientes preguntas:

- ¿Cuáles son los mayores riesgos para la organización?
- ¿Qué controles son más esenciales implementar de inmediato que en el futuro?
- ¿Qué normativas de cumplimiento debe cumplir Botium Toys para garantizar la seguridad de los datos de clientes y proveedores, evitar multas, etc.? 
## Realizar la auditoria

1. Evaluacion de los controles.
1.1 `Revisa la lista de los activos de Botium Toys` :
- Equipos en las instalaciones para las necesidades comerciales en la oficina.  
- Equipos del personal: dispositivos de usuario final (computadoras de escritorio/portátiles, teléfonos inteligentes), estaciones de trabajo remotas, auriculares, cables, teclados, mouse, estaciones de acoplamiento, cámaras de vigilancia, etc.
- Gestión de sistemas, software y servicios: contabilidad, telecomunicaciones, bases de datos, seguridad, comercio electrónico y gestión de inventario.
- Acceso a Internet.
- Red interna.
- Gestión de acceso a proveedores.
- Servicios de alojamiento del centro de datos.  
- Retención y almacenamiento de datos.
- Lectores de tarjetas de identificación.
- Mantenimiento de sistemas heredados: sistemas obsoletos que requieren supervisión humana. 

1.2 `Revisa el nombre de cada control.`

1.3 `Revisa los tipos de controles y su explicación. `

1.4 `Marca con una X cada control que deba aplicarse.`

1.5 `Anota los niveles de prioridad (alta, media y/o baja; NA si no corresponde).`

[Evaluacion de control](https://github.com/KevsCha/Ciberseguridad/blob/main/Auditoria_botium/Evaluacion%20de%20Controles.pdf) Este es una ejemplo de los controles a aplicar segun los activos de la organizacion y los riesgos que pueden correr, que tan alta o baja se dara la importacion en `aplicar el control` para mitigar riesgos.

2. Lista de Verificacion de cumplimiento Normativo

[Lista de cumplimiento normativo](https://github.com/KevsCha/Ciberseguridad/blob/main/Auditoria_botium/Lista%20de%20verificaci%C3%B3n%20de%20cumplimiento%20normativo.pdf) Se utiliza esta plantilla para seleccionar que normativa se aplica a este caso hipotetico.

`Si tienes dudas en que tipos de controles hay, como se dividen aqui dejo una version en español explicando conceptos, los tipos que existen y sus propositos de cada uno`

## Español version

## Categorías de Controles
Los controles en ciberseguridad se agrupan en tres categorías principales:

- Controles Administrativos/Gerenciales
- Controles Técnicos
- Controles Físicos
`Controles Administrativos/Gerenciales`

Los controles administrativos/gerenciales abordan el componente humano de la ciberseguridad. Estos controles incluyen políticas y procedimientos que definen cómo una organización gestiona los datos y delinean claramente las responsabilidades de los empleados, incluyendo su rol en la protección de la organización. Aunque los controles administrativos suelen basarse en políticas, la implementación de esas políticas puede requerir el uso de controles técnicos o físicos.

`Controles Técnicos`

Los controles técnicos consisten en soluciones tales como cortafuegos, sistemas de detección de intrusos (IDS), sistemas de prevención de intrusos (IPS), productos antivirus (AV), cifrado, etc. Los controles técnicos pueden usarse de diversas maneras para cumplir con los objetivos y metas de la organización.

`Controles Físicos`

Los controles físicos incluyen cerraduras de puertas, cerraduras de armarios, cámaras de vigilancia, lectores de tarjetas de identificación, etc. Se utilizan para limitar el acceso físico a los activos físicos por parte del personal no autorizado.

Estas categorías de controles son esenciales para una defensa en profundidad y deben ser implementadas de manera coordinada para proteger eficazmente los activos de la organización.

### Tipos de Controles

Los tipos de controles incluyen, pero no se limitan a:

- Preventivo
- Correctivo
- Detectivo
- Disuasivo

Estos controles trabajan juntos para proporcionar una defensa en profundidad y proteger los activos.

Los `controles preventivos` están diseñados para evitar que ocurra un incidente en primer lugar. 

Los `controles correctivos` se utilizan para restaurar un activo después de un incidente. 

Los `controles detectivos` se implementan para determinar si un incidente ha ocurrido o está en progreso. 

Los `controles disuasivos` están diseñados para desalentar los ataques.

Revisa las siguientes tablas para detalles específicos sobre cada tipo de control y su propósito.

### Controles Administrativos
| Nombre del Control | Tipo de Control | Propósito del Control |
| :-------- | :------- | :-------------------------------- |
| `Mínimo privilegio`| `Preventivo` | Reducir el riesgo y el impacto general de un insider malicioso o cuentas comprometidas |
| `Planes de recuperación ante desastres`| `Correctivo` | Proporcionar continuidad del negocio |
| `Políticas de contraseñas`| `Preventivo` | Reducir la probabilidad de compromiso de cuentas mediante técnicas de fuerza bruta o de diccionario |
| `Políticas de control de acceso`| `Preventivo` | Fortalecer la confidencialidad e integridad definiendo qué grupos pueden acceder o modificar datos |
| `Políticas de gestión de cuentas`| `Preventivo` | Gestionar el ciclo de vida de las cuentas, reduciendo la superficie de ataque y limitando el impacto general de empleados descontentos y el uso de cuentas por defecto|
| `Separación de funciones`| `Preventivo` | Reducir el riesgo y el impacto general de un insider malicioso o cuentas comprometidas |

### Controles Técnicos
| Nombre del Control | Tipo de Control | Propósito del Control |
| :-------- | :------- | :-------------------------------- |
| `Cortafuegos`| `Preventivo` | Filtrar tráfico no deseado o malicioso que ingresa a la red|
| `IDS/IPS`| `Detectivo` |   Detectar y prevenir tráfico anómalo que coincide con una firma o regla|
| `Cifrado`| `Disuasivo` | Proporcionar confidencialidad a información sensible |
| `Copias de seguridad`| `Correctivo` | Restaurar/recuperar de un evento|
| `Gestión de contraseñas`| `Preventivo` |   Reducir la fatiga de contraseñas|
| `Software antivirus (AV)`| `Correctivo` | Detectar y poner en cuarentena amenazas conocidas|
| `Monitoreo, mantenimiento e intervención manual`| `Preventivo` | Necesario para identificar y gestionar amenazas, riesgos o vulnerabilidades en sistemas desactualizados |

### Controles Físicos
| Nombre del Control | Tipo de Control | Propósito del Control |
| :-------- | :------- | :-------------------------------- |
| `Caja fuerte con control de tiempo`| `Disuasivo` | Reducir la superficie de ataque y el impacto general de amenazas físicas |
| `Iluminación adecuada`| `Disuasivo` | Disuadir amenazas al limitar los lugares de "escondite" |
| `Circuito cerrado de televisión (CCTV)`| `Preventivo/Detectivo` | El circuito cerrado de televisión es tanto un control preventivo como detectivo porque su presencia puede reducir el riesgo de ciertos tipos de eventos, y puede usarse después de un evento para informar sobre las condiciones del evento |
| `Armarios con cerradura (para equipos de red)`| `Preventivo` | Fortalecer la integridad al evitar que personal no autorizado y otros individuos accedan o modifiquen físicamente los equipos de infraestructura de red |
| `Señalización indicando proveedor de servicios de alarmas`| `Disuasivo` | Disuadir ciertos tipos de amenazas al hacer que la probabilidad de un ataque exitoso parezca baja |
| `Cerraduras`| `Disuasivo/Preventivo` | Fortalecer la integridad al disuadir y prevenir que personal no autorizado y otros individuos accedan físicamente a los activos |
| `Detección y prevención de incendios (alarma de incendio, sistema de rociadores, etc.)`| `Detectivo/Preventivo` | Detectar incendios en la ubicación física y prevenir daños a activos físicos como inventarios, servidores, etc. |

Estos controles son esenciales para garantizar una defensa integral y deben ser evaluados y aplicados según corresponda para proteger los activos de la empresa.



## Hice una Correcta auditoria? 

Es normal que al hacer una auditoria por primera vez tengas muchas dudas pero revisando los ejemplos de evaluacion de controles y lista del cumplimiento normativo con tus propios documentos donde documentaste a tu propio criterio la mejor seleccion, ahora tienes que planterte lo siguiente.

- ¿Cuáles fueron el alcance y los objetivos de la auditoría? 

- ¿Cuáles fueron los resultados críticos de la auditoría que deben abordarse de inmediato? (es decir, qué controles y/o políticas deben implementarse con urgencia.

- ¿Cuáles fueron las conclusiones? (es decir, qué controles y/o políticas deben abordarse en el futuro).

- ¿Cómo puedes resumir tus recomendaciones de manera clara y concisa a las partes interesadas?

----------------------------------
#### Respondiendo las preguntas.
- El `alcance` fue todo el programa de seguridad de Botium Toys, se analizo cada activo con su respectivo riesgo y se califico segun criterio. Los `objetivos` lograr el cumplimiento normativo, al seleccionar que norma deberia cumplir Botium Toys (Segun criterio) se logra de alguna forma este objetivo, al elergir el control que se deberia aplicar analizas a cada activo junto al riesgo al que puede sometido y como este control puede ayudar a mitigar el riesgo, es decir que logras *COMPREDER* las fallas en los procedimientos y corregirlos con el `control adecuado o controles adecuados`.
- Se entrego documentos que donde se refleja que Controles y normas aplicar.
- La auditoría interna de TI de Botium Toys ha identificado varias áreas críticas que necesitan atención inmediata para mejorar la seguridad y asegurar el cumplimiento normativo. Los controles recomendados se han categorizado en tres tipos: administrativos, técnicos y físicos, con varias prioridades asignadas según la urgencia y el impacto de cada control.

Numero de controles encontrados: 18 controles

### Control Administrativo 
| Nombre del Control | Prioridad | Recomendacion | Justificacion |
| :----------------- | :-------- | :------------ | :------------ |
| `Principio de mínimo privilegio`| Alta| Implementar el principio de mínimo privilegio para reducir el riesgo y el impacto de accesos no autorizados o cuentas comprometidas. | Esto minimizará el acceso de los empleados solo a la información y recursos necesarios para sus roles específicos, reduciendo la superficie de ataque. |
| `Planes de recuperación ante incidentes` | Alta | Desarrollar y probar regularmente planes de recuperación ante incidentes. | Estos planes aseguran la continuidad del negocio en caso de un incidente significativo, reduciendo el tiempo de inactividad y los impactos financieros. |
| `Políticas de contraseñas` | Alta | Establecer y reforzar políticas de contraseñas que incluyan requisitos de complejidad y caducidad. | Esto disminuirá la probabilidad de compromisos de cuentas a través de ataques de fuerza bruta o adivinación de contraseñas.|
| `Políticas de control de acceso` | Alta | Definir claramente y hacer cumplir las políticas de control de acceso. | Asegura que solo las personas autorizadas puedan acceder a información y sistemas críticos, mejorando la confidencialidad y la integridad. |
| `Políticas de gestión de cuentas` | Alta | Implementar políticas rigurosas para la creación, modificación y eliminación de cuentas. | Reduce la exposición a riesgos relacionados con cuentas inactivas o mal gestionadas, mejorando la seguridad general. |
| `Separación de funciones` | Alta |  Implementar la separación de funciones críticas. | Reduce el riesgo de fraude y errores, mejorando la integridad de los procesos y sistemas. |


### Control Técnico 
| Nombre del Control | Prioridad | Recomendacion | Justificacion |
| :----------------- | :-------- | :------------ | :------------ |
| `Sistema de detección de intrusiones (IDS)` | Alta | mplementar un IDS para monitorear y detectar actividades sospechosas en la red. | Ayuda a identificar amenazas en tiempo real y a tomar medidas rápidas para mitigarlas. |
| `Cifrado` | Alta | Utilizar cifrado para proteger la confidencialidad de datos sensibles. | Asegura que los datos sean inaccesibles en caso de interceptación, protegiendo la información confidencial. |
| `Copias de seguridad` | Alta | Implementar un sistema robusto de copias de seguridad y realizar respaldos regularmente. | Permite la recuperación rápida de datos en caso de pérdida o corrupción, asegurando la continuidad de las operaciones. |
| `Gestión de contraseñas` | Media | Utilizar herramientas de gestión de contraseñas para reducir la fatiga de contraseñas y mejorar la seguridad. | Simplifica la gestión de contraseñas para los usuarios, reduciendo el riesgo de contraseñas débiles o repetidas. |
| `Software de antivirus (AV)` | Media | Implementar y actualizar regularmente software antivirus. | Detecta y elimina amenazas conocidas, protegiendo los sistemas de malware y otras infecciones. |
| `Monitoreo manual, mantenimiento e intervención ` | Alta | ealizar monitoreo manual y mantenimiento regular de los sistemas heredados. | Es esencial para identificar y mitigar amenazas, riesgos y vulnerabilidades en sistemas obsoletos. |

### Control Físico 
| Nombre del Control | Prioridad | Recomendacion | Justificacion |
| :----------------- | :-------- | :------------ | :------------ |
| `Caja fuerte con control de tiempo` | Media |  Utilizar una caja fuerte con control de tiempo para almacenar documentos y activos valiosos. | Protege los activos físicos valiosos y reduce el riesgo de robos. |
| `Cerradura de gabinetes (para equipos de red)` | Alta | Instalar cerraduras en los gabinetes que albergan equipos de red. | Previene el acceso no autorizado a la infraestructura de red, mejorando la integridad del sistema. |
| `Carteles que indican el nombre de la empresa proveedora del servicio de alarmas` | Baja | Colocar carteles visibles indicando la presencia de un sistema de alarmas. | Deter a potenciales intrusos al destacar las medidas de seguridad existentes. |
| `Cerraduras` | Media | Instalar cerraduras en puertas y áreas críticas. | eviene el acceso no autorizado a instalaciones y áreas sensibles. | 
| `Detección y prevención de incendios (alarma de incendios, sistema de rociadores, entre otros)` | Media | Implementar sistemas de detección y prevención de incendios. | Protege los activos físicos y la infraestructura de posibles daños causados por incendios. | 

- A continucacion se muestra un resumen de toda la auditoria simplificando los cambios que se realizaran a fin de mejorar la seguridad y mitigar riesgos futuros. Tambien lo puede visualizar en el siguiente enlace [Resumen Auditoria Botium Toys](https://github.com/KevsCha/Ciberseguridad/blob/main/Auditoria_botium/Tareas%20Realizadas/Resumen%20Auditoria%20Botium%20Toys.pdf) o tambien [Resumen, conclusiones y recomendaciones](https://github.com/KevsCha/Ciberseguridad/blob/main/Auditoria_botium/Tareas%20Realizadas/Resumen%20Auditoria%20conclusiones%20y%20recomendaciones.pdf)
    
    El segundo enlace cumple con las siguiente criterios de evaluacion:

    - Comunicaste de manera clara y concisa el alcance de la      auditoría interna a las partes interesadas.
    - Comunicaste de manera clara y concisa los objetivos de la auditoría interna a las partes interesadas.
    - Comunicaste de manera clara y concisa los hallazgos críticos a las partes interesadas.
    - Comunicaste de manera clara y concisa otros hallazgos no críticos a las partes interesadas.
    - Comunicaste de manera clara y concisa un resumen y las recomendaciones a las partes interesadas.

5 Preguntas que hacerse  para saber si el documento cumple con el objetivo de comunicar o transmitir los resultados de la auditoria.


### Resumen
El objetivo de la auditoría fue evaluar la postura de seguridad actual de Botium Toys, identificar riesgos y recomendar controles para mitigar estos riesgos. Este proceso asegura la continuidad del negocio y el cumplimiento normativo a medida que la empresa crece.

#### *Principales Hallazgos y Recomendaciones:*

1. Fortalecimiento de Políticas y Procedimientos (Controles Administrativos)

- Principio de mínimo privilegio: Limitar el acceso a la información solo a aquellos empleados que lo necesiten para sus funciones. Esto reduce significativamente el riesgo de acceso no autorizado.
- Planes de recuperación ante incidentes: Desarrollar y probar regularmente para asegurar la continuidad del negocio durante incidentes críticos.
- Políticas de gestión de cuentas y control de acceso: Implementar y hacer cumplir políticas robustas para gestionar el ciclo de vida de las cuentas y definir claramente quién puede acceder a qué información.

2. Mejoras en la Infraestructura de Seguridad (Controles Técnicos)

- Sistema de detección de intrusiones (IDS): Implementar un IDS para detectar actividades sospechosas en la red en tiempo real.
- Cifrado de datos: Utilizar cifrado para proteger los datos sensibles, asegurando la confidencialidad de la información crítica.
- Copias de seguridad: Realizar copias de seguridad regulares para asegurar la recuperación rápida de datos en caso de pérdida.

3. Seguridad Física de los Activos (Controles Físicos)

- Cerraduras y gabinetes seguros: Instalar cerraduras en puertas y gabinetes de equipos de red para prevenir accesos no autorizados.
- Sistemas de detección y prevención de incendios: Implementar estos sistemas para proteger los activos físicos de daños por incendios.

#### Plan de Implementación:

- Corto Plazo (1-3 meses): Implementar políticas de control de acceso y gestión de cuentas, e instalar cerraduras en gabinetes de equipos de red.
- Mediano Plazo (4-6 meses): Desarrollar y probar planes de recuperación ante incidentes, e implementar un IDS y cifrado de datos.
- Largo Plazo (7-12 meses): Establecer la separación de funciones críticas y proveer capacitación en seguridad para empleados.

#### Beneficios Esperados:

- Reducción de Riesgos: Mitigación de riesgos asociados con accesos no autorizados, pérdida de datos y amenazas internas.
- Cumplimiento Normativo: Asegurar el cumplimiento con normativas relevantes, como el PCI DSS para pagos en línea y posibles regulaciones de protección de datos.
- Mejora en la Resiliencia del Negocio: Preparación adecuada para responder a incidentes, garantizando la continuidad del negocio.

#### Conclusión:

Implementar estos controles es esencial para fortalecer la seguridad de Botium Toys y garantizar su crecimiento sostenible. Estas medidas protegerán la infraestructura de la empresa, mantendrán la confianza de los clientes y socios comerciales, y asegurarán el cumplimiento normativo.




