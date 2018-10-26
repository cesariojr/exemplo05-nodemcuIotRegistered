# exemplo05-nodemcuIotRegistered

# Exemplo IBM Watson IoT Platform
Esse exemplo mostra a conexão de um dispositivo NodeMCU conectado como registered device na IBM Watson IoT Platform, usando o plano Lite.

## Hardware
* NodeMCU Amica ou LoLin V3
* Sensor Barômetro BMP180
* Cabos de conexão
   
![alt text](https://github.com/cesariojr/exemplo05-nodemcuIotRegistered/blob/master/materials.png)

Lógica:
1. Efetuar conexao com a rede WiFi
2. Obter as grandezas de temperatura, pressao e altitude do sensor BMP180
3. Conectar no serviço IBM Watson IoT Platform como registered device
4. Publicar as grandezas obtidas do sensor através de um payload JSON, através do protocolo MQTT para o serviço IBM Watson IoT Platform
   
Referências
* https://developer.ibm.com/recipes/tutorials/connect-an-esp8266-with-the-arduino-sdk-to-the-ibm-iot-foundation/ (Author: Ant Elder)
* http://www.hobbytronics.co.uk/arduino-float-vars (conversao float para string
