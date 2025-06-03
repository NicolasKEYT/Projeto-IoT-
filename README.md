# Projeto IoT: Monitoramento Energético

**Participantes**  
- Caroline Begiato Cabral  
- Guilherme de Souza Ponciano Voz  
- Nicolas Gonçalves Santos  
- Renata Freire Ardito  

---

## Visão Geral

Este projeto implementa um sistema de monitoramento de consumo de energia elétrica utilizando tecnologias de IoT.

O ESP32 realiza a leitura de corrente por meio do sensor SCT-013-030 e envia os dados via MQTT para o Node-RED, que processa as informações e as armazena no InfluxDB. Os dados são visualizados em tempo real através de dashboards no Grafana e, quando há consumo elevado, o sistema envia alertas automáticos via WhatsApp usando a API CallMeBot. O projeto busca promover o uso consciente de energia, alinhado aos objetivos de sustentabilidade, com foco na eficiência energética e na redução do desperdício.

---

## Tecnologias Utilizadas

- **ESP32** (C++ / Arduino)  
- **MQTT** (Mosquitto ou outro broker compatível)  
- **Node-RED** (JavaScript / JSON para fluxos)  
- **InfluxDB 2.x**  
- **Grafana**  
- **API CallMeBot** (WhatsApp)

## Como Executar

1. **Clonar o Repositório**  
   ```bash
   git clone https://github.com/seu-usuario/monitoramento-energetico-iot.git
   cd monitoramento-energetico-iot
