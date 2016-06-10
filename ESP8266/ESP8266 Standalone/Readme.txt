You will need to add the ESP8266 platform package to your Arduino IDE Board Manager.
Please follow these installation steps: https://github.com/esp8266/Arduino

If you are using a 3-wire chipset (e.g. WS2812B) please use AtmoOrb_ESP8266_NeoPixelBus.
This library features some hardware communication options that FastLED does not.
If you are using any other chipset that is not supported by NeoPixelBus or a 4-wire chipsets (e.g. APA102) please use AtmoOrb_ESP8266_FastLED.