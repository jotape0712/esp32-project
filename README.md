# Sistema de Monitoramento com ESP32, MQTT e Flask

Este projeto foi desenvolvido como parte das atividades da graduação em Engenharia na **PUCPR**. O sistema integra sensores, atuadores e comunicação via MQTT para monitorar e interagir com um ambiente simulado ou real, utilizando uma interface web baseada em Flask.

## 🔧 Funcionalidades

- 🔥 **Sensor de Temperatura NTC** — Monitoramento contínuo da temperatura ambiente.
- 🧯 **Sensor de Gás MQ2** — Leitura de concentração de gás com envio ao broker.
- 🚨 **Sensor de Movimento PIR** — Detecta presença e envia sinal via MQTT.
- 💡 **Relé (LED/Dispositivo)** — Pode ser acionado automaticamente (por temperatura) ou manualmente via interface web.
- 🔊 **Buzzer** — Ativado automaticamente por temperatura alta ou manualmente pela interface.
- 🧠 **Servo motor** — Controlado por comando remoto via MQTT.
- 🌐 **Integração com Flask** — Interface web simples para controle e visualização em tempo real.

## 🧪 Tecnologias Utilizadas

- **ESP32** com MicroPython
- **MQTT** (Broker: HiveMQ)
- **Flask (Python)** para interface web
- **HTML/CSS/JavaScript** para front-end básico
- **Paho MQTT** no lado do servidor
- **Wokwi** para simulações (opcional)
