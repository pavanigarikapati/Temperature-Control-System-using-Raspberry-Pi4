# Temperature-Control-System-using-Raspberry-Pi4
Temperature Control System using Raspberry Pi 4 is a smart cooling solution that automatically controls fan operation based on room temperature. The DHT11 sensor monitors temperature continuously and sends data to Raspberry Pi 4, which activates the relay to turn the fan ON or OFF automatically, improving comfort and reducing energy usage.

Temperature Control System is a smart automation project developed using Raspberry Pi 4 to control a fan based on room temperature.

Features

- Automatic fan control
- Temperature and humidity monitoring
- Relay-based switching
- Energy efficient operation
- Real-time environmental sensing

Components Required

- Raspberry Pi 4
- DHT11 Sensor
- Relay Module
- Fan
- Jumper Wires
- Breadboard
- Power Supply

Connections

DHT11 Sensor
- VCC → 5V
- GND → GND
- DATA → GPIO4

Relay Module
- VCC → 5V
- GND → GND
- IN → GPIO17

Fan
- Connected through relay COM and NO terminals

Working

The DHT11 sensor continuously measures room temperature and sends the data to Raspberry Pi 4. When the measured temperature reaches or exceeds 30°C, Raspberry Pi activates the relay and turns the fan ON. When temperature drops below the threshold, the fan automatically turns OFF.

Applications

- Smart Home Automation
- Energy Saving Systems
- Automatic Cooling Systems
- Environmental Monitoring

Advantages

- Reduced power consumption
- Improved user comfort
- Automatic operation
- Simple implementation

Future Enhancements

- Mobile app monitoring
- Web dashboard
- IoT integration
- Multi-device control

Conclusion

This project demonstrates an efficient temperature-based fan control system using Raspberry Pi 4 and relay automation for intelligent environmental control.
