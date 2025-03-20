# ESP32 Water Tank Monitoring System

## English

### Description
This project uses an ESP32-C3 to monitor water levels in two tanks (upper and lower) and control a pump to transfer water between them. The system features a web interface for monitoring and control, accessible via Wi-Fi.

### Features
- Monitors water levels in upper and lower tanks using sensors
- Automatic pump control based on water levels
- Manual pump control via web interface
- Wi-Fi configuration through web interface
- Access Point mode when Wi-Fi connection fails
- OTA (Over-The-Air) updates
- LED indicators for water levels

### Hardware Requirements
- ESP32-C3 microcontroller
- Water level sensors (6 total: 3 for each tank)
- LEDs for level indication (6 total: 3 for each tank)
- Relay for pump control
- Power supply

### Installation
1. Install the Arduino IDE
2. Install ESP32 board package in Arduino IDE
3. Install required libraries:
   - WiFi
   - WebServer
   - Preferences
   - ESPmDNS
   - SPIFFS
   - ArduinoJson
   - ArduinoOTA
   - EEPROM
4. Upload the code to your ESP32-C3

### Usage
1. Power on the device
2. Connect to the Wi-Fi network created by the device (SSID: ESP32_AP, Password: 12345678) if it's the first time or if it can't connect to a saved network
3. Configure your Wi-Fi credentials through the web interface
4. Access the web interface via the IP address shown in the Serial Monitor or via http://esp32.local/
5. Monitor tank levels and control the pump through the web interface

---

## Português

### Descrição
Este projeto utiliza um ESP32-C3 para monitorar os níveis de água em duas caixas d'água (superior e inferior) e controlar uma bomba para transferir água entre elas. O sistema possui uma interface web para monitoramento e controle, acessível via Wi-Fi.

### Funcionalidades
- Monitora níveis de água nas caixas superior e inferior usando sensores
- Controle automático da bomba baseado nos níveis de água
- Controle manual da bomba via interface web
- Configuração de Wi-Fi através da interface web
- Modo Access Point quando a conexão Wi-Fi falha
- Atualizações OTA (Over-The-Air)
- LEDs indicadores para os níveis de água

### Requisitos de Hardware
- Microcontrolador ESP32-C3
- Sensores de nível de água (6 no total: 3 para cada caixa)
- LEDs para indicação de nível (6 no total: 3 para cada caixa)
- Relé para controle da bomba
- Fonte de alimentação

### Instalação
1. Instale a IDE Arduino
2. Instale o pacote de placas ESP32 na IDE Arduino
3. Instale as bibliotecas necessárias:
   - WiFi
   - WebServer
   - Preferences
   - ESPmDNS
   - SPIFFS
   - ArduinoJson
   - ArduinoOTA
   - EEPROM
4. Faça o upload do código para o seu ESP32-C3

### Uso
1. Ligue o dispositivo
2. Conecte-se à rede Wi-Fi criada pelo dispositivo (SSID: ESP32_AP, Senha: 12345678) se for a primeira vez ou se ele não conseguir se conectar a uma rede salva
3. Configure suas credenciais de Wi-Fi através da interface web
4. Acesse a interface web através do endereço IP mostrado no Monitor Serial ou via http://esp32.local/
5. Monitore os níveis das caixas e controle a bomba através da interface web 
