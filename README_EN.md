#arduino)
- [esp8266/esp32](#esp)
- [Processing](#processing)

<a id="arduino"></a>
## Arduino libraries
### Sensors:
- [GyverMAX6675](https://github.com/GyverLibs/GyverMAX6675) - lightweight library for MAX6675 thermocouple driver
- [GyverHTU21D](https://github.com/GyverLibs/GyverHTU21D) - lightweight library for HTU21D temperature and humidity sensor
- [GyverINA](https://github.com/GyverLibs/GyverINA) - lightweight library for INA219 and INA226 power-monitor modules
- [Psychrometer](https://github.com/GyverLibs/Psychrometer) - library for determining humidity by dry and wet bulb for Arduino
- [Tachometer](https://github.com/GyverLibs/Tachometer) - tachometer library for Arduino without binding to hardware
- [GyverNTC](https://github.com/GyverLibs/GyverNTC) - library for working with NTC thermistors according to the Steinhart-Hart law
- [GyverHX711](https://github.com/GyverLibs/GyverHX711) - library for working with weight sensors (ADC) HX711 for Arduino
- [GyverBME280](https://github.com/GyverLibs/GyverBME280) - library for working with BME280 via I2C for Arduino
- [microDS18B20](https://github.com/GyverLibs/microDS18B20) - lightweight library for working with DS18B20 1-Wire thermometers
- [microDS3231](https://github.com/GyverLibs/microDS3231) - lightweight RTC DS3231 library for Arduino

### Hardware input:
- [EncButton](https://github.com/GyverLibs/EncButton) - ultra light and fast library for encoder, encoder with button or just buttons
- [GyverJoy](https://github.com/GyverLibs/GyverJoy) - a library for convenient work with a joystick
- [NecDecoder](https://github.com/GyverLibs/NecDecoder) - lightweight NEC protocol IR decoding library
- [AnalogKey](https://github.com/GyverLibs/AnalogKey) - analog keyboard library for Arduino
- [GyverButton](https://github.com/GyverLibs/GyverButton) - library for multifunctional button press handling [deprecated, use [EncButton](https://github.com/GyverLibs/EncButton)]
- [GyverEncoder](https://github.com/GyverLibs/GyverEncoder) - library for advanced work with encoder [deprecated, use [EncButton](https://github.com/GyverLibs/EncButton)]

### Hardware output:
- [QuickCharge](https://github.com/GyverLibs/QuickCharge) - library for managing adapters with support for QuickCharge 2.0/3.0 technology
- [GyverHC595](https://github.com/GyverLibs/GyverHC595) - library for convenient control of 74HC595 shift register cascade
- [GRGB](https://github.com/GyverLibs/GRGB) - library to control RGB LEDs and ribbons for Arduino
- [microLED](https://github.com/GyverLibs/microLED) - ultra lightweight address strip/matrix library
- [ServoSmooth](https://github.com/GyverLibs/ServoSmooth) - library for smooth servo control
- [SoftServo](https://github.com/GyverLibs/SoftServo) - Servo control library (based on millis/micros)
- [GyverRelay](https://github.com/GyverLibs/GyverRelay) - classic relay controller library for Arduino
- [PWMrelay](https://github.com/GyverLibs/PWMrelay) - a library for generating a low-frequency PWM signal for relays (for PID controllers, etc.)
- [GyverDimmer](https://github.com/GyverLibs/GyverDimmer) - library to control triac dimmer with Arduino
- [GyverStepper](https://github.com/GyverLibs/GyverStepper) - a powerful library for controlling stepper motors with Arduino
- [GyverMotor](https://github.com/GyverLibs/GyverMotor) - a library for convenient control of collector motors through a driver
- [AccelMotor](https://github.com/GyverLibs/AccelMotor) - library for advanced control and stabilization of a motor with an encoder for Arduino

### Displays:
- [GyverMAX7219](https://github.com/GyverLibs/GyverMAX7219) - the sharpest library for MAX7219 matrices in the wild west
- [GyverOLED](https://github.com/GyverLibs/GyverOLED) - lightweight and fast library for OLED display
- [SevenSegmentsDisp](https://github.com/GyverLibs/SevenSegmentsDisp) - *[finalized]* library for TM74HC595 seven-segment display modules
- [GyverTM1637](https://github.com/GyverLibs/GyverTM1637) - library for 7-segment display on TM1637 chip with lots of fun stuff

### Algorithms:
- [OVS](https://github.com/GyverLibs/OVS) - increasing the bit depth of measurements (oversampling)
- [Approxy](https://github.com/GyverLibs/Approxy) - linear data approximator
- [GyverPID](https://github.com/GyverLibs/GyverPID) - PID controller library for Arduino
- [GyverFilters](https://github.com/GyverLibs/GyverFilters) - library with some handy filters for Arduino
- [Forecaster](https://github.com/GyverLibs/Forecaster) - library for determining weather forecast by pressure for Arduino
- [mString](https://github.com/GyverLibs/mString) - SHARP AS DIARRH AND LIGHT AS A FEATHER STRING REPLACEMENT
- [VolAnalyzer] (https://github.com/GyverLibs/VolAnalyzer) - library for amplitude sound analysis on Arduino
- [Clap](https://github.com/GyverLibs/Clap) - library for recognizing claps into a microphone
- [Random16](https://github.com/GyverLibs/Random16) - library for fast generation of 16 bit random numbers
- [Hamming](https://github.com/GyverLibs/Hamming) - a library for packing and unpacking data using the Hamming algorithm (redundant data for recovery)
- [TimeRandom](https://github.com/GyverLibs/TimeRandom) - a library for generating a set of random numbers with reference to time
- [UnixTime](https://github.com/GyverLibs/UnixTime) - Converter unix time stamp to date and time and vice versa for Arduino
- [GyverGFX](https://github.com/GyverLibs/GyverGFX) - lightweight 2D graphics library for displays and matrices
- [GyverFIFO](https://github.com/GyverLibs/GyverFIFO) - universal ring buffer for Arduino
- [GyverLBUF](https://github.com/GyverLibs/GyverLBUF) - line buffer for Arduino
- [fixed](https://github.com/GyverLibs/fixed) - implementation of fixed point calculations for Arduino
- [FFT_C](https://github.com/GyverLibs/FFT_C) - Fourier transform library in C (for esp8266)
- [BitPack](https://github.com/GyverLibs/BitPack) - library for packing bit flags into a byte array (space saving) for Arduino
- [CRT](https://github.com/GyverLibs/CRT) - library with a set of functions for CRT LED correction

### Connection:
- [EasyHID](https://github.com/GyverLibs/EasyHID) - USB mouse and keyboard software implementation
- [GyverTransfer](https://github.com/GyverLibs/GyverTransfer) - interface for data transfer (Stream-compatible) by wire, radio and IR
- [GParser](https://github.com/GyverLibs/GParser) - simple and fast parser for strings into separate substrings and numbers for Arduino
- [AsyncStream](https://github.com/GyverLibs/AsyncStream) - library for asynchronous reading of Stream objects (Serial, etc.)
- [Gyver433](https://github.com/GyverLibs/Gyver433) - library for 433 MHz radio modules and Arduino
- [GyverBus](https://github.com/GyverLibs/GyverBus) - library for communication via GBUS protocol
- [GyverUART](https://github.com/GyverLibs/GyverUART) - a lightweight library for working with a serial port (similar to Serial)
- [MicroUART](https://github.com/GyverLibs/MicroUART) - even more lightweight serial port library

### System:
- [TimerMs](https://github.com/GyverLibs/TimerMs) - multifunctional software timer on millis() system timer for Arduino
- [EEManager](https://github.com/GyverLibs/EEManager) - EEPROM manager - library for smartCranberries for memory wear
- [GyverOS](https://github.com/GyverLibs/GyverOS) - lightweight task manager library for Arduino
- [GyverPower](https://github.com/GyverLibs/GyverPower) - library for power management of MK AVR
- [buildTime](https://github.com/GyverLibs/buildTime) - parsing and getting compilation date and time from DATE and TIME constants
- [GyverTimer](https://github.com/GyverLibs/GyverTimer) - full timer based on system millis() / micros()

### MK Peripherals (AVR only):
- [GyverTimers](https://github.com/GyverLibs/GyverTimers) - configuring and controlling interrupts on ATmega328p, ATmega2560 hardware timers
- [GyverWDT](https://github.com/GyverLibs/GyverWDT) - library to control WDT on AVR ATmega328p/32U4/2560 & ATtiny85/84/167
- [microWire](https://github.com/GyverLibs/microWire) - lightweight library with a standard set of tools for working with hardware I2C
- [directTimers](https://github.com/GyverLibs/directTimers) - library for advanced manual control of ATMega2560, ATMega328, ATMega32u4 timers
- [directADC](https://github.com/GyverLibs/directADC) - library for advanced manual control of ADC and ATmega328 comparator
- [GyverPWM](https://github.com/GyverLibs/GyverPWM) - library for extended PWM generation on ATmega328 (Arduino UNO/Nano/Pro Mini...)

<a id="esp"></a>
## Libraries for ESP8266
- [FastBot](https://github.com/GyverLibs/FastBot) - very simple and fast library for telegram bot
- [SimplePortal](https://github.com/GyverLibs/SimplePortal) - simple WiFi manager for esp8266 to set WiFi login-password and operation mode
- [GyverPortal](https://github.com/GyverLibs/GyverPortal) - simple web interface builder for esp8266 and ESP32
- [GyverNTP](https://github.com/GyverLibs/GyverNTP) - library for getting exact time from NTP server for esp8266/esp32

<a id="processing"></a>
## Libraries for Processing
- [ProcessingPlotter](https://github.com/GyverLibs/ProcessingPlotter) - virtuosplotter in arduino style
- [cards_ui](https://github.com/GyverLibs/cards_ui) - simple interface library for Processing