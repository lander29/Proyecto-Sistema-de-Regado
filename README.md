# Proyecto Sistema de Riego Automatico
Autores: Lander Hernandez - Amadeo Nguema - Miguel Chilquillo


Este proyecto consiste en un sistema de Riego automático, recogida de datos y subida de esos datos a una página web.

![Sistema de Riego](https://www.hwlibre.com/wp-content/uploads/2019/08/montaje-sistema-riego-automatico-arduino.png)

## En que consiste este Proyecto?

Para este proyecto vamos a usar 4 sensores de humedad, 1 sensor de temperatura, 1 sensor de luz (foto resistor) y 1 motobomba que bombeará agua y con ella regaremos los 4 recipientes que tenemos para simular las plantas, cada recipiente llevará su propia válvula para poder regar cada una individualmente en el caso que sea necesario.  Para ello tenemos la ayuda de un grado de informática de Zubiri, los cuales nos ayudarán con la página web y con el servidor para poder reflejar ahí los datos que vayamos recibiendo de los sensores, los datos que recibiremos serán los datos de la humedad de la tierra, la temperatura y la luz.

Con ayuda de MQTT, NodeRed y NodeMCU hemos hecho un servidor donde llegarán todos los datos que recibamos y desde la página web que nos han diseñado podremos hacer cambios en los datos y podremos regar las plantas cuando queramos indistintamente sea una planta, dos o las cuatro. 

![Node RED](https://2.bp.blogspot.com/-y_MFrFV9gk0/WCUUJZAuG2I/AAAAAAAAC28/Z2C--Gr4iyYXqMU1mhvZsT1nhJ3OyayoQCLcB/s1600/nodes.JPG)

Luego esto lo podremos visualizar desde nuestro servidor web o directamente de un telefono movil, el cual en la misma NodeRED podremos diseñar una interfaz (DashBoard)

![Dash](https://themicrofcontrol.files.wordpress.com/2017/08/deepinscreenshot_select-area_20170813015351.png?w=1350)

 ## Materiales
 
  Para este proyecto se necesitara de los siguientes materiales y programas:
 
 - Arduino NANO
 - Protoboard
 - Rele (5v)
 - Sensor de Humedad (YL - 69)
 - Sensor de Temperatura (DHT11)
 - 4 Motobombas
 - Fotoresistor (LDR)
 - Tubos
 - Raspberry pi 3 B+ 
 - Pantalla Raspberry pi táctil
 - El programa MQTT
 - Node-RED
 - NodeMCU
 
 ## Especificaciones de Los Materiales
 
### Arduino NANO

El Arduino Nano es una pequeña y completa placa basada en el ATmega328. Es muy compacto y puede ser utilizado fácilmente en un protoboard. Tiene más o menos la misma funcionalidad que el Arduino Uno, pero con una presentación diferente. La placa es compatible 100%.

![Ardu Nano](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRrVMlVs2jiMYDlWJXXc8zDGTxShlFnzQg-cg&usqp=CAU)

### Sensor de Temperatura

El DHT11 es un sensor digital de temperatura y humedad de bajo costo y fácil uso. Integra un sensor capacitivo de humedad y un termistor para medir el aire circundante, y muestra los datos mediante una señal digital en el pin de datos (no posee salida analógica).Una de las ventajas que nos ofrece el DHT11, además de medir la temperatura y la humedad, es que es digital. A diferencia de sensores como el LM35, este sensor utiliza un pin digital para enviarnos la información y por lo tanto, estaremos más protegidos frente al ruido.

![DHT11](https://www.dhresource.com/0x0/f2/albu/g5/M01/31/E4/rBVaI1nMZ0OABUG9AATvkHWc5ZY128.jpg)

### Sensor YL-69

Este sensor tiene la capacidad de medir la humedad del suelo. Aplicando una pequeña tensión entre los terminales del módulo YL-69 hace pasar una corriente que depende básicamente de la resistencia que se genera en el suelo y ésta depende mucho de la humedad. Por lo tanto, al aumentar la humedad la corriente crece y al bajar la corriente disminuye.

![YL](https://maxelectronica.cl/2713/sensor-de-humedad-de-suelo-modelo-yl-38-y-sonda-yl-69.jpg) 

### Fotoresistor

Una fotorresistencia es un componente eléctrico, el cual posee una resistencia capaz de variar su magnitud al estar en contacto con distintas magnitudes de intensidad lumínica.

![LDR](https://cdn.shopify.com/s/files/1/0557/2945/products/LDR_x700.jpg?v=1543599244)

### NodeMCU
 
NodeMCU es una plataforma IoT de código abierto. Incluye el firmware que se ejecuta en el SoC Wi-Fi ESP8266 de Espressif Systems y el hardware que se basa en el módulo ESP-12. El término "NodeMCU" se refiere al firmware en lugar de a los kits de desarrollo. El firmware utiliza el lenguaje Lua. Se basa en el proyecto eLua y se basa en el SDK no operativo de Espressif para el ESP8266. Utiliza muchos proyectos de código abierto, como lua-cjson, y spiffs.

### Rele

Es un dispositivo electromagnético . Funciona como un interruptor controlado por un circuito eléctrico en el que, por medio de una bobina y un electroimán, se acciona un juego de uno o varios contactos que permiten abrir o cerrar otros circuitos eléctricos independientes.





































