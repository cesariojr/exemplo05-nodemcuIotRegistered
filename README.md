# exemplo05-nodemcuIotRegistered

Jose Maria Cesario Jr
   Exemplo IBM Watson IoT Platform
   Hardware: new NodeMCU LoLin V3 + BMP180
   
   
![alt text](https://github.com/cesariojr/exemplo05-nodemcuIotRegistered/blob/master/materials.png)

   Logica:
   1. efetua conexao com a rede WiFi
   2. obtem as grandezas de temperatura, pressao e altitude do sensor BMP180
   3. conecta no servidor MQTT quickstart do IBM Watson IoT Platform
   4. publica a JSON string para o topico quickstart:MAC_ADDRESS
   
   referencias Bluemix e IoTF:
   Author: Ant Elder
   https://developer.ibm.com/recipes/tutorials/connect-an-esp8266-with-the-arduino-sdk-to-the-ibm-iot-foundation/
   
   referencias conversao float para string
   http://www.hobbytronics.co.uk/arduino-float-vars
   http://forum.carriots.com/index.php/topic/61-wireless-gardening-with-arduino-cc3000-wifi-modules/page-2
