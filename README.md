## Projeto de Controle de Validade de Produtos

Este projeto utiliza o Arduino e um display LCD para criar um sistema de controle de validade de produtos em mercados. O objetivo é evitar o desperdício de alimentos verificando a proximidade da data de validade dos produtos e alertando os mercados para oferecer descontos.

### Pré-requisitos

- Arduino Uno
- Display LCD
- Potenciômetro
- 3 LEDs
- 3 Resistores
- Painel e cabos machos
- Biblioteca LiquidCrystal

### Configuração

1. Conecte o display LCD aos pinos do Arduino conforme indicado no código.
2. Conecte os LEDs aos pinos especificados no código.
3. Faça as conexões corretas do potenciômetro, resistores e cabos.
4. Carregue o código para o Arduino.

### Uso

1. Execute o programa no Arduino.
2. Insira a data atual quando solicitado no Monitor Serial.
3. Insira a data de validade do produto quando solicitado no Monitor Serial.
4. O sistema calculará a diferença de dias entre as datas e acenderá o LED correspondente à situação do produto (verde para validade maior que 10 dias, amarelo para validade próxima de 10 dias, vermelho para validade vencida).
5. A diferença de dias será exibida no display LCD.
6. Repita o processo para verificar a validade de outros produtos.

### Outras Informações Relevantes

- O código do projeto foi escrito em linguagem C++ e está comentado para facilitar o entendimento.
- Certifique-se de realizar as conexões dos componentes corretamente, seguindo o esquema fornecido.
- O sistema calcula a diferença de dias considerando anos comuns e bissextos.
- É importante fornecer as datas no formato especificado ("DD/MM/AAAA") para que o sistema possa interpretá-las corretamente.
- O Monitor Serial é utilizado para inserir as datas e exibir informações sobre o processo. Certifique-se de configurar a velocidade de comunicação serial correta (9600 bps).
- Caso deseje interromper o programa antes de verificar a validade de outro produto, digite "0" quando solicitado.

### Autores

Márcio Gastaldi - RM98811
Arthur Bessa Pian-RM99215
Davi Desenzi - RM550849
Miguel Milok - RM98494
João Victor Soares Rodrigues - RM551410

Este documento fornece as informações necessárias para utilizar o sistema de monitoramento de validade de alimentos utilizando o Arduino. Siga as instruções fornecidas e desfrute do projeto! 
