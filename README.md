# Wokwi-Project-ESP32
Projeto de Simulação de Sensor DHT22 com MQTT
Este projeto foi desenvolvido como parte da disciplina de Instrumentação Eletrônica da Universidade Estadual do Maranhão (UEMA). Ele utiliza a plataforma de simulação Wokwi e se comunica via WebSocket MQTT.

Descrição do Projeto
O objetivo deste projeto é medir a temperatura e umidade utilizando um sensor DHT22, e publicar essas medições em um broker MQTT. A comunicação é realizada através de uma conexão Wi-Fi simulada na plataforma Wokwi.

```Componentes Utilizados
Sensor DHT22: Sensor de temperatura e umidade.
MQTT Broker: Utilizado para comunicação MQTT. O broker utilizado neste projeto é o broker.mqttdashboard.com.
Wi-Fi: Conexão simulada com a rede Wokwi-GUEST.
```
```Configurações do MQTT
MQTT_CLIENT_ID: "pedro-tomazeti-micropy"
MQTT_BROKER: "broker.mqttdashboard.com"
MQTT_USER: ""
MQTT_PASSWORD: ""
MQTT_TOPIC: "instrum-eletro"
```
