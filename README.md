# Wokwi-Project-ESP32
Projeto de Simulação de Sensor DHT22 com MQTT<br>
Este projeto foi desenvolvido como parte da disciplina de Instrumentação Eletrônica da Universidade Estadual do Maranhão (UEMA). Ele utiliza a plataforma de simulação Wokwi e se comunica via WebSocket MQTT.

Descrição do Projeto<br>
O objetivo deste projeto é medir a temperatura e umidade utilizando um sensor DHT22, e publicar essas medições em um broker MQTT. A comunicação é realizada através de uma conexão Wi-Fi simulada na plataforma Wokwi.

Integrantes da Equipe <br>
João Marcos Vidal Lacerda <br>
Luiz Felipe Freitas Ferreira <br>
Lucas de Menezes Pereira <br>
Pedro Lucas Tomazeti Fernandes <br>
Rebeca Cristina Sousa Vieira de Carvalho

Componentes Utilizados
```
Sensor DHT22: Sensor de temperatura e umidade.
MQTT Broker: Utilizado para comunicação MQTT. O broker utilizado neste projeto é o broker.mqttdashboard.com.
Wi-Fi: Conexão simulada com a rede Wokwi-GUEST.
```
Configurações do MQTT
```
MQTT_CLIENT_ID: "pedro-tomazeti-micropy"
MQTT_BROKER: "broker.mqttdashboard.com"
MQTT_USER: ""
MQTT_PASSWORD: ""
MQTT_TOPIC: "instrum-eletro"
```
Funcionamento
```
Inicialização do Sensor DHT22: O sensor é inicializado no pino 18.
Conexão Wi-Fi: O dispositivo se conecta à rede Wi-Fi simulada Wokwi-GUEST.
Conexão ao Broker MQTT: Uma conexão é estabelecida com o broker MQTT broker.mqttdashboard.com.
Medição e Publicação: O código mede a temperatura e a umidade utilizando o sensor DHT22, e publica essas medições no tópico MQTT instrum-eletro a cada segundo, caso haja uma nova medição.
```
Plataforma de Simulação <br>
Este código é projetado para ser executado na plataforma de simulação Wokwi, que permite a simulação de microcontroladores e outros componentes eletrônicos.

Disciplina <br>
Este projeto foi desenvolvido para a disciplina de Instrumentação Eletrônica da Universidade Estadual do Maranhão (UEMA).
