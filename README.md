# Medidor de Umidade do Ambiente com Arduino Uno

### Materiais utilizados

- Arduino Uno
- Sensor DHT11
- Display de led de sete segmentos com 4 dígitos
- Leds vermelha e amarela
- Protoboard e jumpers

### Ferramentas

- Para planejar e simular o funcionamento do código utilizar-se-á a ferramenta TinkerCad, observadas suas limitações
- Para desenvolver o código foi utilizada a ferramenta Arduino IDE

### Descrição do projeto

#### Objetivo

O objetivo do projeto é desenvolver um sistema que realize a medição da umidade do ambiente e indique níveis críticos de umidade, além de demonstrar o valor atual através do led de 7 segmentos. 

#### Detalhamento

O sistema segue o seguinte fluxo:

1. O sensor DHT11 mede a umidade do ambiente e envia o valor para o Arduino
2. O Arduino verifica o valor medido, analisa as seguintes condições e realiza as atividades relacionadas:
	1. Se a umidade estiver abaixo de 30%, acende a led vermelha
	2. Se a umidade estiver entre 31% e 45%, acende a led amarela
	3. Se a umidade estiver acima de 45%, nenhuma ação é necessária