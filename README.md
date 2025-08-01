# esphome ABL-1W1108
Esphome component for communication with my ABL-1W1108

Based on the original ABL custom modbus protocol implementation by @jrv
I had to make some modifications, since I use an external meter and since I am using a different ESP32 board with integrated RS485

### My hardware
- ABL 1W1108 "eMH1" Wallbox
- Lilygo T-CAN485 (esp32 with integrated RS485)
- Eastron SDM72D (since my eMH1 comes without meter)
