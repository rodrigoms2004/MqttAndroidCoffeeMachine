# Ligando uma cafeteira com Micropython, MQTT e Android


Anotações do Meetup de 03/12/2019

Placa controladora ligada a um relé para controlar uma placa remotamente. 


### O que é MQTT?

MQTT (Message Queue Telemetry Transport)
Projeto IBM, final dos anos 90
Criadores: Andy Stanford-Clark (IBM) Arlen Nipper (Cirrus Link)

#### Características

Procolo leve para redes com restrições de banda

* Paradigma de PUB/SUB, Publish/subscribe( diferente do paradigma Request/Response do HTTP)
* Existencia de um Broker (Middleware)
* Assincrono
* Consome poucos recursos do dispositivo (bateria, processamento, largura de banda)
* Altamente escalável
* Fácil implementação

#### Arquitetura 

Broker, send msg to clients {
  Publisher, publisher data topic to Broker;

  Subscriber, Subscribe a topin in Broker 
}

### Links úteis

[Micropython](https://micropython.org/)

[MQTT ORG](http://mqtt.org/)

[ESP Tool](https://github.com/espressif/esptool)

[Ampy](https://github.com/scientifichackers/ampy)

[MQTT JS](https://github.com/mqttjs/MQTT.js)

[MQTT Mosquitto Broker](https://mosquitto.org/)