# Projeto de Captação de Temperatura e Umidade

Este documento apresenta o projeto de captação de temperatura e umidade utilizando um sensor DHT11 e um microcontrolador Arduino. O projeto que esta sendo desenvolvido como parte das atividades acadêmicas do semestre na Faculdade SPTech.

## Objetivo do Projeto

O principal objetivo deste projeto é monitorar e registrar a temperatura e a umidade do ambiente em tempo real, utilizando um sensor DHT11 conectado a um Arduino. O sistema deve ser capaz de:

- Captar a temperatura e a umidade do ambiente.
- Exibir os valores captados em um monitor serial.
- Notificar erros na leitura dos dados.

## Componentes Utilizados

- **Arduino**: Utilizado como o microcontrolador para processar e exibir os dados captados.
- **Sensor DHT11**: Sensor responsável por medir a temperatura e a umidade do ambiente.
- **Protoboard e Fios de Conexão**: Para facilitar a montagem do circuito.


## Funcionamento do Projeto

O projeto funciona da seguinte maneira:

1. **Configuração Inicial**: O sensor DHT11 é conectado ao pino A0 do Arduino. O pino VCC do sensor é ligado ao 5V do Arduino, e o pino GND é conectado ao GND do Arduino.

2. **Leitura dos Dados**: O código faz a leitura dos valores de temperatura e umidade a cada segundo, utilizando a biblioteca DHT.

3. **Exibição dos Dados**: Os valores são exibidos no monitor serial da IDE do Arduino, permitindo ao usuário monitorar o ambiente em tempo real.

4. **Tratamento de Erros**: Se o sensor não conseguir ler os dados corretamente, uma mensagem de erro será exibida.
