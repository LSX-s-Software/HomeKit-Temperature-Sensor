# HomeKit Temperature Sensor

### A simple temperature & humidity sensor worked with Apple HomeKit. NO additional bridges needed!

Program based on Mixiaoxiao’s [Arduino-HomeKit-ESP8266](https://github.com/Mixiaoxiao/Arduino-HomeKit-ESP8266). Protocol based on Apple's HAP(non-commercial version).

Hardware based on ESP8266 & DHT11.

## HomeKit Setup code

`123-45-678`

## Usage

1. Install Arduino IDE, [Arduino-HomeKit-ESP8266](https://github.com/Mixiaoxiao/Arduino-HomeKit-ESP8266) library, SimpleDHT and ESP8266 board manager.
2. Edit `ssid` and `password` in `wifi_info.h` to connect your Wi-Fi.
3. Change download options according to your ESP8266 module. Compile and download.
4. Reboot and add it to your home in Apple Home app.

## Recommended settings in IDE

- Module: Generic ESP8266 Module
- Debug Level: None (for lower memory use)
- Erase Flash: select **All Flash Contents** when you first upload
- CPU Frequency: 160MHz (avoid connection timeout)
