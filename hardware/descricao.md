# Descrição de hardware


 * RaspBerry Pi
  -  Roda o servidor local, com o Home Assistant configurado para emular um acessório certificado (Phillips Hue)
    ![](/hardware/RaspberryPI.jpeg)
    
* Node MCU
    - Conecta por MQTT com o Raspberry Pi e executa a ação determinada (junto com o Rele na imagem abaixo)
    
* Módulo Rele
    - Funciona como interruptor recebendo o comando do Node MCU e ligando/desligando a lâmpada
    ![](/hardware/NodeMCU.jpeg)
    
* Amazon Alexa
    - Recebe e interpreta os comandos de voz do usuário
    ![](/hardware/Alexa.jpeg)
    
* Um dispositivo ligado ao Rele para ligar e desligar de acordo com o comando
