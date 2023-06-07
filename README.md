# SaveFood


**README - Monitor de Validade de Alimentos**

Este projeto consiste na implementação de um sistema utilizando o Arduino para monitorar a validade de alimentos e alertar os usuários sobre a proximidade do vencimento. 
O sistema utiliza um display LCD, um potenciômetro, três LEDs, três resistores, painel e cabos machos.


Instruções de Uso
Monte o circuito conforme o esquema abaixo:

LCD:

Pino RS: 12
Pino E: 11
Pinos D4-D7: 5, 4, 3, 2
LEDs:

LED Vermelho: 6
LED Amarelo: 7
LED Verde: 8
Potenciômetro: Conecte um dos pinos aos 5V, o outro ao GND e o pino do meio ao A0.

Certifique-se de conectar os componentes corretamente e de acordo com o esquema.

Carregue o código no Arduino IDE e faça o upload para a placa Arduino.

No Monitor Serial, digite a data atual no formato "DD/MM/AAAA" e pressione Enter.

Aguarde a exibição da data atual no display LCD por 3 segundos.

Digite a data de validade do alimento no formato "DD/MM/AAAA" e pressione Enter.

Aguarde a exibição da data de validade no display LCD por 3 segundos.

O sistema calculará a diferença de dias entre a data atual e a data de validade do alimento.

Com base na diferença de dias, o sistema acenderá um LED correspondente:

Diferença de dias <= 0: LED Verde aceso.
Diferença de dias <= 10: LED Amarelo aceso.
Diferença de dias > 10: LED Vermelho aceso.
A diferença de dias será exibida no display LCD por 3 segundos.

O sistema perguntará se deseja verificar a validade de outro produto. Digite "1" para Sim ou "0" para Não.

Requisitos e Dependências
Arduino IDE: É necessário ter a Arduino IDE instalada para compilar e enviar o código para a placa Arduino.
Arduino Uno: O código foi desenvolvido e testado utilizando a placa Arduino Uno. Outros modelos podem ser compatíveis, mas podem exigir ajustes no circuito e no código.
Biblioteca LiquidCrystal: A biblioteca LiquidCrystal é utilizada para controlar o display LCD. Certifique-se de tê-la instalada na sua Arduino IDE antes de compilar o código.
Outras Informações Relevantes
O código do projeto foi escrito em linguagem C++ e está comentado para facilitar o entendimento.

Certifique-se de realizar as conexões dos componentes corretamente, seguindo o esquema fornecido.

O sistema calcula a diferença de dias considerando anos comuns e bissextos.

É importante fornecer as datas no formato especificado ("DD/MM/AAAA") para que o sistema possa interpretá-las corretamente.

O Monitor Serial é utilizado para inserir as datas e exibir informações sobre o processo. Certifique-se de configurar a velocidade de comunicação serial correta (9600 bps).

Caso deseje interromper o programa antes de verificar a validade de outro produto, digite "0" quando solicitado.

Autor
Nome: Arthur

Este documento fornece as informações necessárias para utilizar o sistema de monitoramento de validade de alimentos utilizando o Arduino. Siga as instruções fornecidas e desfrute do projeto! 
