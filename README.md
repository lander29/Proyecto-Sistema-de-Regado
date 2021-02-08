# Proyecto Sistema de Regado
Este proyecto consiste en un sistema de Riego automático, recogida de datos y subida de esos datos a una página web.

![Sistema de Riego](https://www.hwlibre.com/wp-content/uploads/2019/08/montaje-sistema-riego-automatico-arduino.png)

## En que consiste este Prouecto?

Para este proyecto vamos a usar 4 sensores de humedad, 1 sensor de temperatura, 1 sensor de luz (foto resistor) y 1 motobomba que bombeará agua y con ella regaremos los 4 recipientes que tenemos para simular las plantas, cada recipiente llevará su propia válvula para poder regar cada una individualmente en el caso que sea necesario.  Para ello tenemos la ayuda de un grado de informática de Zubiri, los cuales nos ayudarán con la página web y con el servidor para poder reflejar ahí los datos que vayamos recibiendo de los sensores, los datos que recibiremos serán los datos de la humedad de la tierra, la temperatura y la luz.

Con ayuda de MQTT, NodeRed y NodeMCU hemos hecho un servidor donde llegarán todos los datos que recibamos y desde la página web que nos han diseñado podremos hacer cambios en los datos y podremos regar las plantas cuando queramos indistintamente sea una planta, dos o las cuatro. 

![Node RED](https://lh3.googleusercontent.com/proxy/3Cnxm1JpSfZbwNI-HGrV-_MTpXTAWPuL-nfSZP08ceSWVpzslsMaBBwA-WYJY3wlMkJU1nbhEY70weUYBWe8DLKUgbr9yy2oeI2WeY_0LwibJMvA5bvI6wZrINNQCBssLWpx9klsun-jpHpsxKAG8DjaVAZZwnUbQw5IUNZ1S9Dj6uEV87hZfX2e)
