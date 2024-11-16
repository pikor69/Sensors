# Sensors (ESPNow, MQTT, Json)

## ESP based sensors using Json for packet data and ESPNow &lt;> MQTT transmission.

The basic setup consists of esp8266 or esp32-based sensors using ESPNow to transmit JSON packets to the MQTT Gateway.
Gateway is made of two microcontrollers, one ESP based receiving ESPNow packets and transmitting them over the serial connection to the MQTT Sender.
MQTT Sender can be anything like ESP, Pico or Pi using WiFi or wired Ethernet to send packets to MQTT broker.

What you do next is up to you, I use NodeRED to process the data.

