# Sensor de Temperatura para Plantas
Este projeto consiste em um código em C++ para um sistema de sensor de temperatura que utiliza três luzes de LED para indicar a temperatura ambiente em uma plantação de tomates, pimentas do reino e manjericão.

## Funcionalidade
O sensor de temperatura é conectado a um sensor analógico (A0) para medir a temperatura ambiente. Com base na leitura do sensor, o programa controla as três luzes de LED de acordo com os seguintes critérios:

Luz Azul: Acende quando a temperatura está abaixo de 23 graus Celsius, indicando que está frio demais para as plantas.
Luz Amarela: Acende quando a temperatura está entre 23 e 28 graus Celsius, indicando a faixa de temperatura ideal para o crescimento saudável das plantas.
Luz Vermelha: Acende quando a temperatura excede 28 graus Celsius, indicando que está muito quente para as plantas.
Hardware necessário
Arduino ou microcontrolador compatível.
Sensor de temperatura.
3 LEDs (azul, amarelo e vermelho).
Resistores adequados para limitar a corrente dos LEDs.
Conexões e fios necessários.

## Configuração
Antes de executar o programa, siga as etapas abaixo para configurar o hardware:

Conecte o sensor de temperatura ao pino analógico A0 do Arduino.
Conecte o LED azul ao pino 7 do Arduino.
Conecte o LED amarelo ao pino 6 do Arduino.
Conecte o LED vermelho ao pino 5 do Arduino.
Insira os resistores adequados em série com cada LED para limitar a corrente.
Uso
Carregue o código fornecido no Arduino IDE ou no ambiente de desenvolvimento adequado.
Compile e faça o upload do código para o Arduino.
Abra o monitor serial na velocidade de 9600 baud para visualizar as leituras de temperatura.
Observe as luzes de LED para determinar a faixa de temperatura em que as plantas se encontram.

## Notas
Certifique-se de fornecer energia adequada ao Arduino e aos LEDs.
Ajuste os limiares de temperatura no código, se necessário, para atender às necessidades específicas da sua plantação.
Este projeto oferece uma solução simples e visualmente indicativa para monitorar a temperatura ambiente em uma plantação de tomates, pimentas do reino e manjericão. Utilizando as luzes de LED, os agricultores podem ter uma noção rápida da temperatura e tomar as medidas apropriadas para garantir o crescimento saudável das plantas.
