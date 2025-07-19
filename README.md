# multi-jbd-esp32-oled-ble-and-relays-esphome-yaml

JBD BMS multiple read via ble and display on Oled and Relay control of external appliances
push button and menu

I have used esphome, a Esp32-devkit-v1 board, a capacitive touch switch and a 128 x 64 oled for this project, with a 4-relay board to control external devices.

The capacitive touch switch on single press moves through pages of information, an on double click shows a menu to manually toggle the relays.
The relays are also automatically controlled based on the battery state of charge (soc). My application was to turn a pumnp on once batteries are full- this also turns on the inverter to run the pump and a fridge... these can obviously be modified to suit your own application.

This code has been extroplated from other code and I thank all who have posted here and elsewhere on the internet to enable me to piece this puzzle together.

Connections:

ESP Pins

D12 - switch

D27 - Oled SCK

D26 - Oled SDA

D25 - Oled RES

D33 - Oled DC

D32 - Oled CS

D5 - Relay1

D18 - Relay2

D15 - Relay3

D4 - Relay4

