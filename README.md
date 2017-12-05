# MedicionTanqueESP8266MQTT

Sensor que mide la distancia del tanque que se encuentra vacia, luego con un calculo matematico se obtiene el volumen del tanque lleno.

![Diagrama](https://raw.githubusercontent.com/gsampallo/MedicionTanqueESP8266MQTT/master/esp8266_mqtt_distancia_bb.png)

En el archivo test.py se debe cambiar:
- En la linea 18, el usuario y clave por los correctos.
- En la linea 22, se debe reemplazar ip_broker por la ip correcta del broker al que nos vamos a conectar.

En ambos casos deben ser los mismos que los que utilizamos en el sketch del ESP.