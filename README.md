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



