# Descrição de hardware


 - RaspBerry Pi
    Roda o servidor local, com o Home Assistant configurado para emular um acessório certificado (Phillips Hue)

- Node MCU
    Conecta por MQTT com o Raspberry Pi e executa a ação determinada
    
- Módulo Rele
    Funciona como interruptor recebendo o comando do Node MCU e ligando/desligando a lâmpada
    
- Amazon Alexa
    Recebe e interpreta os comandos de voz do usuário
    
- Um dispositivo ligado ao Rele para ligar e desligar de acordo com o comando
