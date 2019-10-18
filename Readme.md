# Preparação do Ambiente

## Instalação e configuração do Arduino IDE:

1. Faça o download da aplicação [Arduino IDE](https://www.arduino.cc/en/main/software)
1. Após instalação, abra o aplicativo e vá em: ***Arquivo > Preferências***
![Arduino IDE: Arquivo > Preferências](assets/images/Arduino-Arquivos-Preferencias.png)
1. Configuração para adicionar placas *ESP8266* e *ESP32*:
    1. No campo `URLs Adicionais para Gerenciadores de Placas` adicione as seguintes linhas, separadas por vírgula (`,`):
        > `https://dl.espressif.com/dl/package_esp32_index.json`
        > `http://arduino.esp8266.com/stable/package_esp8266com_index.json`

        ![Arduino IDE: Preferências](assets/images/Arduino-Preferências.png)