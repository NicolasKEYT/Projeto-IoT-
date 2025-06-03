# Projeto-IoT-

Este projeto implementa um sistema de monitoramento de consumo de energia elétrica utilizando tecnologias de IoT.

O ESP32 realiza a leitura de corrente por meio do sensor SCT-013-030 e envia os dados via MQTT para o Node-RED, que processa as informações e as armazena no InfluxDB. Os dados são visualizados em tempo real através de dashboards no Grafana e, quando há consumo elevado, o sistema envia alertas automáticos via WhatsApp usando a API CallMeBot. O projeto busca promover o uso consciente de energia, alinhado aos objetivos de sustentabilidade, com foco na eficiência energética e na redução do desperdício.
