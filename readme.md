# Portal Cautivo para configurar dispositivo ESP32


La propuesta consiste en la implementación de un dispositivo basado en ESP32 que utiliza Modbus y comunicación WiFi, el cual puede ser configurado a través de una pantalla cautiva. Al presionar un botón tres veces, el dispositivo entra en modo servidor web, convirtiéndose en un punto de acceso WiFi. Cualquier usuario que se conecte a esta red será redirigido automáticamente a una página con un formulario donde podrá ingresar la configuración deseada. Una vez que el usuario guarda los parámetros, el dispositivo se ajusta a la nueva configuración y regresa al modo normal, intentando conectarse a la red WiFi y a la red Modbus seleccionadas. Esta solución permite una configuración sencilla y accesible, mejorando la experiencia del usuario en la puesta en marcha del dispositivo.

### Link de la pagina de configuracion que quiero implementar en mi dispositivo ESP32
 [Link](https://microdevg.github.io/portal_cautivo_esp32/)
