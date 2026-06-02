This is an automatic translation and may be incorrect in some places. See the source README and examples for authoritative information.

# GyverLibs - libraries by AlexGyver
![Logo](/libs.png)
[![Foo](https://img.shields.io/badge/ПОДПИСАТЬСЯ-НА%20ОБНОВЛЕНИЯ-brightgreen.svg?style=social&logo=telegram&color=blue)](https://t.me/GyverLibs)

- [Arduino](#arduino)
- [esp8266/esp32](#esp)
- [Processing](#processing)
- [JavaScript](#js)

<a id="arduino"></a>
## Arduino Library
### Sensors:
- [GyverMag](https://github.com/GyverLibs/GyverMag)Library for magnetometers HMC5883L, HMC5983L, QMC5883L
- [GyverPing](https://github.com/GyverLibs/GyverPing)Library for the HC-SR04 ultrasonic rangefinder
- [GyverMAX6675](https://github.com/GyverLibs/GyverMAX6675)Lightweight library for MAX6675 thermocouple driver
- [GyverHTU21D](https://github.com/GyverLibs/GyverHTU21D)Lightweight library for HTU21D temperature and humidity sensor
- [GyverINA](https://github.com/GyverLibs/GyverINA)Lightweight library for INA219 and INA226 power monitor modules
- [Psychrometer](https://github.com/GyverLibs/Psychrometer)- a library for determining humidity by dry and wet thermometer for Arduino
- [Tachometer](https://github.com/GyverLibs/Tachometer)- tachometer library for Arduino without reference to iron
- [GyverNTC](https://github.com/GyverLibs/GyverNTC)- library for working with NTC thermistors according to the Steinhart-Hart law
- [GyverHX711](https://github.com/GyverLibs/GyverHX711)Weight sensor library (ADC) HX711 for Arduino
- [GyverBME280](https://github.com/GyverLibs/GyverBME280)BME280 over I2C library for Arduino
- [GyverDS18](https://github.com/GyverLibs/GyverDS18)Lightweight library for working with 1-Wire DS18B20 thermometers
- [GyverDS3231](https://github.com/GyverLibs/GyverDS3231)- library for working with real-time chip DS3231
- ~[microDS3231](https://github.com/GyverLibs/microDS3231)Lightweight library to work with RTC DS3231 for Arduino~

### Iron input:
- [GyverHub](https://github.com/GyverLibs/GyverHub)Control panel for esp8266, esp32 and other Arduino. Interface designer. Integration into a smart home
- [EncButton](https://github.com/GyverLibs/EncButton)A lightweight encoder library and/or button with a huge number of features
- [uButton](https://github.com/GyverLibs/uButton)Another lightweight but powerful library for a readable source button
- [uEncoder](https://github.com/GyverLibs/uEncoder)Another encoder library with a button (based on uButton)
- [GyverJoy](https://github.com/GyverLibs/GyverJoy)Library for easy work with joystick
- [NecDecoder](https://github.com/GyverLibs/NecDecoder)Lightweight library for decoding NEC IR protocol
- [GyverKey](https://github.com/GyverLibs/GyverKey)Library for working with matrix and analog keyboards
- ~[AnalogKey](https://github.com/GyverLibs/AnalogKey)- library for working with analog keyboards ~

### Iron conclusion:
- [GyverBlinker](https://github.com/GyverLibs/GyverBlinker)- a timer with a counter for flashing with an LED and other tasks
- [GyverBeeper](https://github.com/GyverLibs/GyverBeeper)- timer squeak generation
- [GyverMIDI](https://github.com/GyverLibs/GyverMIDI)Player MIDI files from special files[converter](https://alexgyver.github.io/MIDI/index/)
- [QuickCharge](https://github.com/GyverLibs/QuickCharge)A library for adapter management with QuickCharge 2.0/3 support. 0
- [GyverShift](https://github.com/GyverLibs/GyverShift)- library for easy control of the shift register cascade 74HC595 and 74HC165
- [RGBLED](https://github.com/GyverLibs/RGBLED)- a library for managing RGB LEDs and tapes for Arduino
- [microLED](https://github.com/GyverLibs/microLED)- ultra-lightweight library for working with address tape / matrix
- [ServoSmooth](https://github.com/GyverLibs/ServoSmooth)- library for smooth control of servo drives
- [SoftServo](https://github.com/GyverLibs/SoftServo)Servo software management library (based on millis/micros)
- [GyverRelay](https://github.com/GyverLibs/GyverRelay)Classic relay regulator library for Arduino
- [PWMrelay](https://github.com/GyverLibs/PWMrelay)- a library for generating a low-frequency PWM signal for relays (for PID regulators, etc.)
- [GyverDimmer](https://github.com/GyverLibs/GyverDimmer)- library for managing a simistor dimmer with Arduino
- [GyverStepper](https://github.com/GyverLibs/GyverStepper)Productive library for controlling stepper motors with Arduino
- [GyverMotor2](https://github.com/GyverLibs/GyverMotor2)Library for easy management of collector motors through the driver
- [AccelMotor](https://github.com/GyverLibs/AccelMotor)Advanced motor control and stabilization library with encoder for Arduino
- ~[GyverMotor](https://github.com/GyverLibs/GyverMotor)- library for easy management of collector motors through the driver~

### Displays:
- [GyverSegment](https://github.com/GyverLibs/GyverSegment)A powerful library for any display with 7-segment indicators
- [GyverMAX7219](https://github.com/GyverLibs/GyverMAX7219)The sharpest MAX7219 library in the wild west
- [GyverOLED](https://github.com/GyverLibs/GyverOLED)Lightweight and fast library for OLED display
- [CharDisplay](https://github.com/GyverLibs/CharDisplay)- graphics engine on symbols: full drawing, loading indicators, graphics
- ~[GyverTM1637](https://github.com/GyverLibs/GyverTM1637)- bibilotheque for a 7-segment display on a TM1637 chip with a bunch of stickers~

### Algorithm:
- [Stamp](https://github.com/GyverLibs/Stamp)Storage and transformation of time
- [SunPosition](https://github.com/GyverLibs/SunPosition)determining the position of the sun by geolocation and time
- [OVS](https://github.com/GyverLibs/OVS)- increasing the bit size of measurements (oversampling)
- [Approxy](https://github.com/GyverLibs/Approxy)- linear data approximator
- [GyverPID](https://github.com/GyverLibs/GyverPID)PID regulator library for Arduino
- [uPID](https://github.com/GyverLibs/uPID)Lightweight universal library PID regulator
- [GyverFilters](https://github.com/GyverLibs/GyverFilters)A library with some convenient filters for Arduino
- [Forecaster](https://github.com/GyverLibs/Forecaster)- a library for determining the pressure weather forecast for Arduino
- [StringN](https://github.com/GyverLibs/StringN)Lightweight and fast static String builder
- [VolAnalyzer](https://github.com/GyverLibs/VolAnalyzer)- library for amplitude sound analysis on Arduino
- [Clap](https://github.com/GyverLibs/Clap)Library for recognizing cotton in a microphone
- [Random16](https://github.com/GyverLibs/Random16)A library for fast generation of 16 bits of random numbers
- [Hamming](https://github.com/GyverLibs/Hamming)- a library for packing and decompressing data using the Hamming algorithm (redundant data for recovery)
- [TimeRandom](https://github.com/GyverLibs/TimeRandom)- library for generating a set of random numbers with a time reference
- [GyverGFX](https://github.com/GyverLibs/GyverGFX)Lightweight library of two-dimensional graphics for displays and matrices
- [fixed](https://github.com/GyverLibs/fixed)Fixed-point computing for Arduino
- [FFT_C](https://github.com/GyverLibs/FFT_C)Fourier to C library (for esp8266)
- [BitPack](https://github.com/GyverLibs/BitPack)- library for packing bit flags into byte array (space saving) for Arduino
- [CRT](https://github.com/GyverLibs/CRT)- library with a set of functions for CRT LED correction
- [StringUtils](https://github.com/GyverLibs/StringUtils)- a set of tools for working with lines
- [GSON](https://github.com/GyverLibs/GSON)Parser and data collector for Arduino
- [BSON](https://github.com/GyverLibs/BSON)Parser and data collector in binary JSON format for Arduino
- [FOR_MACRO](https://github.com/GyverLibs/FOR_MACRO) - variadic for macro
- [GVector](https://github.com/GyverLibs/GVector)Library for working with 2-dimensional vectors
- ~[Stack](https://github.com/GyverLibs/Stack)- a library for easy work with arrays of any type of data type std::vector or arrays in js~
- ~[UnixTime](https://github.com/GyverLibs/UnixTime)Converter unix time stamp to date and time and vice versa for Arduino
- ~[GyverFIFO](https://github.com/GyverLibs/GyverFIFO)Universal ring buffer for Arduino~
- ~[GyverLBUF](https://github.com/GyverLibs/GyverLBUF)Linear buffer for Arduino~

### Communication:
- [GyverPush](https://github.com/GyverLibs/GyverPush)Sending push notifications to the browser
- [GyverHTTP](https://github.com/GyverLibs/GyverHTTP)Very simple and lightweight HTTP server and semi-asynchronous HTTP client
- [EasyHID](https://github.com/GyverLibs/EasyHID)Software implementation of the USB mouse and keyboard
- [GyverWire](https://github.com/GyverLibs/GyverWire)- library for transmitting any data via wire/IR channel/radio 433 MHz
- [UART_RF](https://github.com/GyverLibs/UART_RF)A library to transmit any data over 433 MHz radio via UART
- [AsyncStream](https://github.com/GyverLibs/AsyncStream)Library for asynchronous reading of Stream objects (Serial etc.)
- [StreamPacket](https://github.com/GyverLibs/StreamPacket)A simple universal protocol for data transmission via Arduino Stream
- [GyverBus](https://github.com/GyverLibs/GyverBus)Library for communication using the GBUS protocol
- [GyverUART](https://github.com/GyverLibs/GyverUART)Lightweight library for working with serial port (similar to Serial)
- [MicroUART](https://github.com/GyverLibs/MicroUART)An even easier library to work with a serial port
- ~[GParser](https://github.com/GyverLibs/GParser)Simple and fast parser lines into separate substrings and numbers for Arduino~
- ~[GyverTransfer](https://github.com/GyverLibs/GyverTransfer)- interface for data transmission (Stream-compatible) over wire, radio and IR ~
- ~[Gyver433](https://github.com/GyverLibs/Gyver433)Library for 433 MHz and Arduino~

### Systemic:
- [GyverMenu](https://github.com/GyverLibs/GyverMenu)- dynamic menu system
- [GTimer](https://github.com/GyverLibs/GTimer)Lightweight and universal program timer
- [Looper](https://github.com/GyverLibs/Looper)- Lightweight pseudo-multi-threaded event-oriented framework
- [GyverDB](https://github.com/GyverLibs/GyverDB)- database for data storage
- [Table](https://github.com/GyverLibs/Table)Dynamic table for any type of data
- [GyverIO](https://github.com/GyverLibs/GyverIO)Fast functions for working with pins AVR, ESP8266, ESP32
- [Pairs](https://github.com/GyverLibs/Pairs)- storage of data in text form in the format "key": meaning
- [EEManager](https://github.com/GyverLibs/EEManager)EEPROM Manager - library to reduce memory wear
- [GyverOS](https://github.com/GyverLibs/GyverOS)Light Task Manager Library for Arduino
- [GyverPower](https://github.com/GyverLibs/GyverPower)- library for energy management of MK AVR
- [pgm_utils](https://github.com/GyverLibs/pgm_utils)- a set of convenient tools for working with PROGMEM
- [GTL](https://github.com/GyverLibs/GTL)- a set of template tools
- [Benchmark](https://github.com/GyverLibs/Benchmark)Measurement of code execution time
- ~[buildTime](https://github.com/GyverLibs/buildTime)Parsing and obtaining the date and time of compilation from the DATE and TIME constants ~

### Periphery MK (AVR only):
- [GyverTimers](https://github.com/GyverLibs/GyverTimers)Configure and control interrupts on hardware timers ATmega328p, ATmega2560
- [GyverWDT](https://github.com/GyverLibs/GyverWDT)- WDT management library on AVR ATmega328p/32U4/2560 & ATtiny85/84/167
- [microWire](https://github.com/GyverLibs/microWire)Lightweight library with a standard set of tools for working with I2C hardware
- [directTimers](https://github.com/GyverLibs/directTimers)Advanced manual timer management library ATMega2560, ATMega328, ATMega32u4
- [directADC](https://github.com/GyverLibs/directADC)- library for advanced manual control of ADC and comparator ATmega328
- [GyverPWM](https://github.com/GyverLibs/GyverPWM)ATmega328 (Arduino UNO/Nano/Pro Mini...)

<a id="esp"></a>
## Libraries for ESP8266/ESP32
- [Settings](https://github.com/GyverLibs/Settings)- the most simple and convenient builder of web mold for settings
- [FileData](https://github.com/GyverLibs/FileData)Replace EEPROM, store any data and variables in files
- [FastBot2](https://github.com/GyverLibs/FastBot2)Very fast and versatile telegram bot library (new version)
- [FastBot](https://github.com/GyverLibs/FastBot)- Quick library for telegram bot
- [SimplePortal](https://github.com/GyverLibs/SimplePortal)A simple WiFi manager for esp8266 for setting a WiFi login password and operating mode
- [GyverNTP](https://github.com/GyverLibs/GyverNTP)A library for obtaining accurate time from an NTP server for esp8266/esp32
- [rtc_utils](https://github.com/GyverLibs/rtc_utils)- wrapper for easier use of RTC memory on esp8266
- [EspSleep](https://github.com/GyverLibs/EspSleep)Sleep for esp8266 for any (very long) period
- [WiFiConnector](https://github.com/GyverLibs/WiFiConnector)Asynchronous WiFi connection with automatic AP creation
- [AutoOTA](https://github.com/GyverLibs/AutoOTA)A library to automatically check OTA for project updates from GitHub and other sources
- ~[GyverPortal](https://github.com/GyverLibs/GyverPortal)A simple web interface builder for esp8266 and ESP32 ~

<a id="processing"></a>
## Libraries for Processing
- [PPlot](https://github.com/GyverLibs/PPlot)Virtual plotter (new version)
- [cards_ui](https://github.com/GyverLibs/cards_ui)Simple interface library for Processing (fork)
- ~[ProcessingPlotter](https://github.com/GyverLibs/ProcessingPlotter)- virtual plotter in the style of Arduinsky

<a id="js"></a>
## JS Library
- [SVPlot.js](https://github.com/GyverLibs/SVPlot.js)- graphing
- [ProcessingCanvas.js](https://github.com/GyverLibs/ProcessingCanvas.js)Processing API for HTML Canvas
- [UI.js](https://github.com/GyverLibs/UI.js)- simple modular control panel
- [Component.js](https://github.com/GyverLibs/Component.js)Object builder DOM/SVG elements
- [bson.js](https://github.com/GyverLibs/bson.js)- Unpacker of binary JSON
- [Packet.js](https://github.com/GyverLibs/Packet.js)Packer and data unpacker in binary buffer
- [DragBlock.js](https://github.com/GyverLibs/DragBlock.js)- obtaining events of cursor movement from the block
- [utils.js](https://github.com/GyverLibs/utils.js)- utility suite
- [Serial.js](https://github.com/GyverLibs/Serial.js)Convenient class for working with Serial
- [Websocket.js](https://github.com/GyverLibs/Websocket.js)WebSocket wrapper with automatic reconnection n

![](https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=GyverLibs&theme=github)
![](https://github-profile-summary-cards.vercel.app/api/cards/stats?username=GyverLibs&theme=github)
![](https://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=GyverLibs&theme=github)
