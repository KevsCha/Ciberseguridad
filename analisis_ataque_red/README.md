#Analisis, Ataque de Red

## Resumen

En esta actividad, considerarás un escenario en el que un cliente de la empresa para la que trabajas **experimenta un problema de seguridad al acceder al sitio web de la empresa**. Identificarás la causa probable de la interrupción del servicio. A continuación, explicarás cómo se produjo el ataque y el impacto negativo que tuvo en el sitio web.

En este curso, has aprendido sobre varios ataques de red comunes. Aprendiste sus nombres, cómo se llevan a cabo y las características de cada ataque desde la perspectiva del objetivo. Comprender cómo afectan los ataques a una red te ayudará a solucionar problemas en la red de tu organización. También te ayudará a tomar medidas para mitigar los daños y proteger una red de futuros ataques.

Asegúrate de completar esta actividad antes de continuar. En la siguiente parte del curso, podrás ver un ejemplo completo para compararlo con tu propio trabajo. No podrás acceder al modelo hasta que hayas finalizado esta actividad. 

## Escenario

Trabajas como analista de seguridad para una agencia de viajes que anuncia ventas y promociones en el sitio web de la empresa. Los empleados de la empresa acceden regularmente a la página web de ventas de la empresa para buscar paquetes vacacionales que puedan gustar a sus clientes. 

Una tarde, recibes una alerta automatizada de tu sistema de monitoreo que indica un problema con el servidor web. Intentas visitar el sitio web de la empresa, pero recibes un mensaje de error de tiempo de espera de conexión en tu navegador.

Utilizas un detector de paquetes para capturar los paquetes de datos en tránsito hacia y desde el servidor web. Observas un gran número de solicitudes TCP SYN procedentes de una dirección IP desconocida. El servidor web parece estar desbordado por el volumen de tráfico entrante y está perdiendo su capacidad para responder al número anormalmente grande de solicitudes SYN. Sospechas que el servidor está siendo atacado por un actor malicioso.

Desconectas temporalmente el servidor para que el equipo pueda recuperarse y volver a un estado de funcionamiento normal. También configuras el firewall de la empresa para bloquear la dirección IP que estaba enviando el número anormal de solicitudes SYN. Sabes que tu solución de bloqueo de IP no durará mucho, ya que un atacante puede suplantar otras direcciones IP para eludir este bloqueo. Tienes que alertar a tu gerente sobre este problema rápidamente y discutir los siguientes pasos para detener a este atacante y evitar que este problema vuelva a ocurrir. Tendrás que estar preparado para contarle a tu jefe el tipo de ataque que descubriste y cómo estaba afectando al servidor web y a los empleados.

## Conclusión

Analizar este tipo de escenario da un toque mas practico a situaciones que llegan a ocurrir como analista de seguridad, hace familiarizarnos con el entorno, lo primero que hice en este caso es recurrir a los apuntes que tengo sobre ataques de red, observe el escenario y determine que es un ataque Dos de tipo inundacion sinconnizada (SYN flood), tambien me ayudo a responder las siguientes preguntas.

- ¿Qué entiendes actualmente sobre los ataques a la red?

- ¿Con qué tipo de ataque es probable que se produzcan los síntomas descritos en el escenario? 

- ¿Cuál es la diferencia entre una denegación de servicio (DoS) y una denegación de servicio distribuida (DDoS)? 

- ¿Por qué el sitio web tarda tanto en cargarse e informa de un error de tiempo de espera de conexión?

#

[introduccion al analisis de seguimiento de red de microsoft](https://techcommunity.microsoft.com/t5/core-infrastructure-and-security/introduction-to-network-trace-analysis-3-tcp-performance/ba-p/3737115)