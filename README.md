# GyverLibs - Arduino библиотеки от AlexGyver
![Logo](/libs.png)
- [Arduino-совместимые](#arduino)
- [esp8266/esp32](#esp)
- [Processing](#processing)

<a id="arduino"></a>
## Arduino библиотеки
### Датчики:
- [GyverMAX6675](https://github.com/GyverLibs/GyverMAX6675) - лёгкая библиотека для драйвера термопары MAX6675
- [GyverHTU21D](https://github.com/GyverLibs/GyverHTU21D) - лёгкая библиотека для датчика температуры и влажности HTU21D
- [GyverINA](https://github.com/GyverLibs/GyverINA) - лёгкая библиотека для модулей power-monitor'ов INA219 и INA226
- [Psychrometer](https://github.com/GyverLibs/Psychrometer) - библиотека для определения влажности по сухому и мокрому термометру для Arduino
- [Tachometer](https://github.com/GyverLibs/Tachometer) - библиотека тахометра для Arduino без привязки к железу
- [GyverNTC](https://github.com/GyverLibs/GyverNTC) - библиотека для работы с NTC термисторами по закону Стейнхарта-Харта
- [GyverHX711](https://github.com/GyverLibs/GyverHX711) - библиотека работы с датчиками веса (АЦП) HX711 для Arduino
- [GyverBME280](https://github.com/GyverLibs/GyverBME280) - библиотека для работы с BME280 по I2C для Arduino
- [microDS18B20](https://github.com/GyverLibs/microDS18B20) - легкая библиотека для работы с 1-Wire термометрами DS18B20
- [microDS3231](https://github.com/GyverLibs/microDS3231) - лёгкая библиотека для работы с RTC DS3231 для Arduino

### Железки ввод:
- [EncButton](https://github.com/GyverLibs/EncButton) - ультра лёгкая и быстрая библиотека для энкодера, энкодера с кнопкой или просто кнопки
- [NecDecoder](https://github.com/GyverLibs/NecDecoder) - лёгкая библиотека для декодирования ИК протокола NEC
- [AnalogKey](https://github.com/GyverLibs/AnalogKey) - библиотека для работы с аналоговой клавиатурой для Arduino
- [GyverButton](https://github.com/GyverLibs/GyverButton) - библиотека для многофункциональной отработки нажатия кнопки
- [GyverEncoder](https://github.com/GyverLibs/GyverEncoder) - библиотека для расширенной работы с энкодером
- [GyverJoy](https://github.com/GyverLibs/GyverJoy) - библиотека для удобной работы с джойстиком

### Железки вывод:
- [QuickCharge](https://github.com/GyverLibs/QuickCharge) - библиотека для управления адаптерами с поддержкой технологии QuickCharge 2.0/3.0
- [GyverHC595](https://github.com/GyverLibs/GyverHC595) - библиотека для удобного управления каскадом сдвиговых регистров 74HC595
- [GRGB](https://github.com/GyverLibs/GRGB) - библиотека для управления RGB светодиодами и лентами для Arduino
- [microLED](https://github.com/GyverLibs/microLED) - ультра лёгкая библиотека для работы с адресной лентой/матрицей
- [ServoSmooth](https://github.com/GyverLibs/ServoSmooth) - библиотека для плавного управления сервоприводами
- [SoftServo](https://github.com/GyverLibs/SoftServo) - библиотека для программного управления Servo (на базе millis/micros)
- [GyverRelay](https://github.com/GyverLibs/GyverRelay) - библиотека классического релейного регулятора для Arduino
- [PWMrelay](https://github.com/GyverLibs/PWMrelay) - библиотека для генерации низкочастотного ШИМ сигнала для реле (для ПИД регуляторов и проч.)
- [GyverDimmer](https://github.com/GyverLibs/GyverDimmer) - библиотека для управления симисторным диммером с Arduino
- [GyverStepper](https://github.com/GyverLibs/GyverStepper) - производительная библиотека для управления шаговыми моторами с Arduino
- [GyverMotor](https://github.com/GyverLibs/GyverMotor) - библиотека для удобного управления коллекторными моторами через драйвер
- [AccelMotor](https://github.com/GyverLibs/AccelMotor) - библиотека для расширенного управления и стабилизации мотора с энкодером для Arduino

### Дисплеи:
- [GyverMAX7219](https://github.com/GyverLibs/GyverMAX7219) - самая резкая библиотека для матриц MAX7219 на диком западе
- [GyverOLED](https://github.com/GyverLibs/GyverOLED) - лёгкая и быстрая библиотека для OLED дисплея
- [SevenSegmentsDisp](https://github.com/GyverLibs/SevenSegmentsDisp) - библиотка для модулей семисегментного дисплея TM74HC595
- [GyverTM1637](https://github.com/GyverLibs/GyverTM1637) - бибилотека для 7 сегментного дисплея на чипе TM1637 с кучей приколюх

### Алгоритмы:
- [OVS](https://github.com/GyverLibs/OVS) - повышение разрядности измерений (оверсэмплинг)
- [Approxy](https://github.com/GyverLibs/Approxy) - линейный аппроксиматор данных
- [GyverPID](https://github.com/GyverLibs/GyverPID) - библиотека PID регулятора для Arduino
- [GyverFilters](https://github.com/GyverLibs/GyverFilters) - библиотека с некоторыми удобными фильтрами для Arduino
- [Forecaster](https://github.com/GyverLibs/Forecaster) - библиотека для определения прогноза погоды по давлению для Arduino
- [mString](https://github.com/GyverLibs/mString) - РЕЗКАЯ КАК ПОНОС И ЛЁГКАЯ КАК ПЁРЫШКО ЗАМЕНА STRING
- [VolAnalyzer](https://github.com/GyverLibs/VolAnalyzer) - библиотека для амплитудного анализа звука на Arduino
- [Clap](https://github.com/GyverLibs/Clap) - библиотека для распознавания хлопков в микрофон
- [Random16](https://github.com/GyverLibs/Random16) - библиотека для быстрой генерации 16 бит случайных чисел
- [Hamming](https://github.com/GyverLibs/Hamming) - библиотека для упаковки и распаковки данных по алгоритму Хэмминга (избыточные данные для восстановления)
- [TimeRandom](https://github.com/GyverLibs/TimeRandom) - библиотека для генерации набора случайных чисел с привязкой ко времени
- [UnixTime](https://github.com/GyverLibs/UnixTime) - конвертер unix time stamp в дату и время и наоборот для Arduino
- [GyverGFX](https://github.com/GyverLibs/GyverGFX) - лёгкая библиотека двухмерной графики для дисплеев и матриц
- [GyverFIFO](https://github.com/GyverLibs/GyverFIFO) - универсальный кольцевой буфер для Arduino
- [GyverLBUF](https://github.com/GyverLibs/GyverLBUF) - линейный буфер для Arduino
- [fixed](https://github.com/GyverLibs/fixed) - реализация вычислений с фиксированной точкой для Arduino
- [FFT_C](https://github.com/GyverLibs/FFT_C) - библиотека преобразования Фурье на С (для esp8266)
- [BitPack](https://github.com/GyverLibs/BitPack) - библиотека для упаковки битовых флагов в байтовый массив (экономия места) для Arduino
- [CRT](https://github.com/GyverLibs/CRT) - библиотека с набором функций для CRT коррекции светодиодов

### Связь:
- [EasyHID](https://github.com/GyverLibs/EasyHID) - программная реализация USB мыши и клавиатуры
- [GyverTransfer](https://github.com/GyverLibs/GyverTransfer) - интерфейс для передачи данных (Stream-совместимый) по проводу, радио и ИК
- [GParser](https://github.com/GyverLibs/GParser) - простой и быстрый парсер строк в отдельные подстроки и числа для Arduino
- [AsyncStream](https://github.com/GyverLibs/AsyncStream) - библиотека для асинхронного чтения объектов Stream (Serial итд)
- [Gyver433](https://github.com/GyverLibs/Gyver433) - библиотека для радиомодулей 433 МГц и Arduino
- [GyverBus](https://github.com/GyverLibs/GyverBus) - библиотека для общения по протоколу GBUS
- [GyverUART](https://github.com/GyverLibs/GyverUART) - лёгкая библиотека для работы с последовательным портом (аналог Serial)
- [MicroUART](https://github.com/GyverLibs/MicroUART) - ещё более лёгкая библиотека для работы с последовательным портом

### Системное:
- [TimerMs](https://github.com/GyverLibs/TimerMs) - многофункциональный программный таймер на системном таймере millis() для Arduino
- [EEManager](https://github.com/GyverLibs/EEManager) - Менеджер EEPROM - библиотека для уменьшения износа памяти
- [GyverOS](https://github.com/GyverLibs/GyverOS) - библиотека лёгкого диспетчера задач для Arduino
- [GyverPower](https://github.com/GyverLibs/GyverPower) - библиотека для управления энергопотреблением МК AVR
- [buildTime](https://github.com/GyverLibs/buildTime) - парсинг и получение даты и времени компиляции из констант DATE и TIME
- [GyverTimer](https://github.com/GyverLibs/GyverTimer) - полноценный таймер на базе системных millis() / micros()

### Периферия МК (только AVR):
- [GyverTimers](https://github.com/GyverLibs/GyverTimers) - настройка и контроль прерываний по аппаратным таймерам ATmega328p, ATmega2560
- [GyverWDT](https://github.com/GyverLibs/GyverWDT) - библиотека для управления WDT на AVR ATmega328p/32U4/2560 & ATtiny85/84/167
- [microWire](https://github.com/GyverLibs/microWire) - лёгкая библиотека со стандартным набором инструментов для работы с аппаратным I2C
- [directTimers](https://github.com/GyverLibs/directTimers) - библиотека для расширенного ручного управления таймерами ATMega2560, ATMega328, ATMega32u4
- [directADC](https://github.com/GyverLibs/directADC) - библиотека для расширенного ручного управления АЦП и компаратором ATmega328
- [GyverPWM](https://github.com/GyverLibs/GyverPWM) - библиотека для расширенной генерации ШИМ на ATmega328 (Arduino UNO/Nano/Pro Mini...)

<a id="esp"></a>
## Библиотеки для ESP8266
- [FastBot](https://github.com/GyverLibs/FastBot) - очень простая и быстрая библиотека для телеграм бота
- [SimplePortal](https://github.com/GyverLibs/SimplePortal) - простой менеджер WiFi для esp8266 для задания логина-пароля WiFi и режима работы
- [GyverPortal](https://github.com/GyverLibs/GyverPortal) - простой конструктор веб интерфейса для esp8266 и ESP32
- [GyverNTP](https://github.com/GyverLibs/GyverNTP) - библиотека для получения точного времени с NTP сервера для esp8266/esp32

<a id="processing"></a>
## Библиотеки для Processing
- [ProcessingPlotter](https://github.com/GyverLibs/ProcessingPlotter) - виртуальный плоттер в стиле ардуиновского
- [cards_ui](https://github.com/GyverLibs/cards_ui) - простенькая библиотека интерфейса для Processing
