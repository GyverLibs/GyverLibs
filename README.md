# GyverLibs - библиотеки от AlexGyver
![Logo](/libs.png)
[![Foo](https://img.shields.io/badge/README-ENGLISH-blueviolet.svg?style=for-the-badge)](https://github-com.translate.goog/GyverLibs/GyverLibs?_x_tr_sl=ru&_x_tr_tl=en)
[![Foo](https://img.shields.io/badge/ПОДПИСАТЬСЯ-НА%20ОБНОВЛЕНИЯ-brightgreen.svg?style=social&logo=telegram&color=blue)](https://t.me/GyverLibs)

- [Arduino](#arduino)
- [esp8266/esp32](#esp)
- [Processing](#processing)
- [JavaScript](#js)

<a id="arduino"></a>
## Arduino библиотеки
### Датчики:
- [GyverPing](https://github.com/GyverLibs/GyverPing) - библиотека для ультразвукового дальномера HC-SR04
- [GyverMAX6675](https://github.com/GyverLibs/GyverMAX6675) - лёгкая библиотека для драйвера термопары MAX6675
- [GyverHTU21D](https://github.com/GyverLibs/GyverHTU21D) - лёгкая библиотека для датчика температуры и влажности HTU21D
- [GyverINA](https://github.com/GyverLibs/GyverINA) - лёгкая библиотека для модулей power-monitor'ов INA219 и INA226
- [Psychrometer](https://github.com/GyverLibs/Psychrometer) - библиотека для определения влажности по сухому и мокрому термометру для Arduino
- [Tachometer](https://github.com/GyverLibs/Tachometer) - библиотека тахометра для Arduino без привязки к железу
- [GyverNTC](https://github.com/GyverLibs/GyverNTC) - библиотека для работы с NTC термисторами по закону Стейнхарта-Харта
- [GyverHX711](https://github.com/GyverLibs/GyverHX711) - библиотека работы с датчиками веса (АЦП) HX711 для Arduino
- [GyverBME280](https://github.com/GyverLibs/GyverBME280) - библиотека для работы с BME280 по I2C для Arduino
- [GyverDS18](https://github.com/GyverLibs/GyverDS18) - легкая библиотека для работы с 1-Wire термометрами DS18B20
- [GyverDS3231](https://github.com/GyverLibs/GyverDS3231) - библиотека для работы с микросхемой реального времени DS3231
- [microDS3231](https://github.com/GyverLibs/microDS3231) - лёгкая библиотека для работы с RTC DS3231 для Arduino

### Железки ввод:
- [GyverHub](https://github.com/GyverLibs/GyverHub) - панель управления для esp8266, esp32 и других Arduino. Конструктор интерфейса. Интеграция в умный дом
- [EncButton](https://github.com/GyverLibs/EncButton) - лёгкая библиотека для энкодера и/или кнопки с огромным количеством возможностей
- [GyverJoy](https://github.com/GyverLibs/GyverJoy) - библиотека для удобной работы с джойстиком
- [NecDecoder](https://github.com/GyverLibs/NecDecoder) - лёгкая библиотека для декодирования ИК протокола NEC
- [AnalogKey](https://github.com/GyverLibs/AnalogKey) - библиотека для работы с аналоговой клавиатурой для Arduino

### Железки вывод:
- [GyverBlinker](https://github.com/GyverLibs/GyverBlinker) - таймер со счётчиком для мигания светодиодом и других задач
- [GyverBeeper](https://github.com/GyverLibs/GyverBeeper) - генерация писка по таймеру
- [QuickCharge](https://github.com/GyverLibs/QuickCharge) - библиотека для управления адаптерами с поддержкой технологии QuickCharge 2.0/3.0
- [GyverShift](https://github.com/GyverLibs/GyverShift) - библиотека для удобного управления каскадом сдвиговых регистров 74HC595 и 74HC165
- [RGBLED](https://github.com/GyverLibs/RGBLED) - библиотека для управления RGB светодиодами и лентами для Arduino
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
- [GyverSegment](https://github.com/GyverLibs/GyverSegment) - мощная библиотека для любых дисплеев с 7-сегментными индикаторами
- [GyverMAX7219](https://github.com/GyverLibs/GyverMAX7219) - самая резкая библиотека для матриц MAX7219 на диком западе
- [GyverOLED](https://github.com/GyverLibs/GyverOLED) - лёгкая и быстрая библиотека для OLED дисплея
- [GyverTM1637](https://github.com/GyverLibs/GyverTM1637) - бибилотека для 7 сегментного дисплея на чипе TM1637 с кучей приколюх
- [CharDisplay](https://github.com/GyverLibs/CharDisplay) - графический движок на символах: полноценное рисование, индикаторы загрузки, графики

### Алгоритмы:
- [Stamp](https://github.com/GyverLibs/Stamp) - хранение и преобразование времени
- [Stack](https://github.com/GyverLibs/Stack) - библиотека для удобной работы с массивами любого типа данных типа std::vector или массивов в js
- [SunPosition](https://github.com/GyverLibs/SunPosition) - определение положения солнца по геолокации и времени
- [OVS](https://github.com/GyverLibs/OVS) - повышение разрядности измерений (оверсэмплинг)
- [Approxy](https://github.com/GyverLibs/Approxy) - линейный аппроксиматор данных
- [GyverPID](https://github.com/GyverLibs/GyverPID) - библиотека PID регулятора для Arduino
- [uPID](https://github.com/GyverLibs/uPID) - лёгкая универсальная библиотека PID регулятора
- [GyverFilters](https://github.com/GyverLibs/GyverFilters) - библиотека с некоторыми удобными фильтрами для Arduino
- [Forecaster](https://github.com/GyverLibs/Forecaster) - библиотека для определения прогноза погоды по давлению для Arduino
- [StringN](https://github.com/GyverLibs/StringN) - лёгкий и быстрый статический String-билдер
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
- [StringUtils](https://github.com/GyverLibs/StringUtils) - набор инструментов для работы со строками
- [GSON](https://github.com/GyverLibs/GSON) - парсер и сборщик данных в формате JSON для Arduino
- [FOR_MACRO](https://github.com/GyverLibs/FOR_MACRO) - variadic for macro
- [GVector](https://github.com/GyverLibs/GVector) - библиотека для работы с 2-х мерными векторами

### Связь:
- [GyverHTTP](https://github.com/GyverLibs/GyverHTTP) - очень простой и лёгкий HTTP сервер и полуасинхронный HTTP клиент
- [EasyHID](https://github.com/GyverLibs/EasyHID) - программная реализация USB мыши и клавиатуры
- [GyverWire](https://github.com/GyverLibs/GyverWire) - библиотека для передачи любых данных по проводу/ИК каналу/радио 433 МГц
- [UART_RF](https://github.com/GyverLibs/UART_RF) - библиотека для передачи любых данных по радио 433 МГц через UART
- ~[GyverTransfer](https://github.com/GyverLibs/GyverTransfer) - интерфейс для передачи данных (Stream-совместимый) по проводу, радио и ИК~
- ~[Gyver433](https://github.com/GyverLibs/Gyver433) - библиотека для радиомодулей 433 МГц и Arduino~
- [GParser](https://github.com/GyverLibs/GParser) - простой и быстрый парсер строк в отдельные подстроки и числа для Arduino
- [AsyncStream](https://github.com/GyverLibs/AsyncStream) - библиотека для асинхронного чтения объектов Stream (Serial итд)
- [GyverBus](https://github.com/GyverLibs/GyverBus) - библиотека для общения по протоколу GBUS
- [GyverUART](https://github.com/GyverLibs/GyverUART) - лёгкая библиотека для работы с последовательным портом (аналог Serial)
- [MicroUART](https://github.com/GyverLibs/MicroUART) - ещё более лёгкая библиотека для работы с последовательным портом

### Системное:
- [GyverMenu](https://github.com/GyverLibs/GyverMenu) - динамическая система меню
- [GTimer](https://github.com/GyverLibs/GTimer) - лёгкий и универсальный программный таймер
- [Looper](https://github.com/GyverLibs/Looper) - лёгкий псевдо-многопоточный событийно-ориентированный фреймворк
- [GyverDB](https://github.com/GyverLibs/GyverDB) - база данных для хранения данных
- [GyverIO](https://github.com/GyverLibs/GyverIO) - быстрые функции для работы с пинами AVR, ESP8266, ESP32
- [Pairs](https://github.com/GyverLibs/Pairs) - хранение данных в текстовом виде в формате "ключ":значение
- [EEManager](https://github.com/GyverLibs/EEManager) - Менеджер EEPROM - библиотека для уменьшения износа памяти
- [GyverOS](https://github.com/GyverLibs/GyverOS) - библиотека лёгкого диспетчера задач для Arduino
- [GyverPower](https://github.com/GyverLibs/GyverPower) - библиотека для управления энергопотреблением МК AVR
- [buildTime](https://github.com/GyverLibs/buildTime) - парсинг и получение даты и времени компиляции из констант DATE и TIME
- [pgm_utils](https://github.com/GyverLibs/pgm_utils) - набор удобных инструментов для работы с PROGMEM
- [GTL](https://github.com/GyverLibs/GTL) - набор шаблонных инструментов
- [Benchmark](https://github.com/GyverLibs/Benchmark) - измерение времени выполнения кода

### Периферия МК (только AVR):
- [GyverTimers](https://github.com/GyverLibs/GyverTimers) - настройка и контроль прерываний по аппаратным таймерам ATmega328p, ATmega2560
- [GyverWDT](https://github.com/GyverLibs/GyverWDT) - библиотека для управления WDT на AVR ATmega328p/32U4/2560 & ATtiny85/84/167
- [microWire](https://github.com/GyverLibs/microWire) - лёгкая библиотека со стандартным набором инструментов для работы с аппаратным I2C
- [directTimers](https://github.com/GyverLibs/directTimers) - библиотека для расширенного ручного управления таймерами ATMega2560, ATMega328, ATMega32u4
- [directADC](https://github.com/GyverLibs/directADC) - библиотека для расширенного ручного управления АЦП и компаратором ATmega328
- [GyverPWM](https://github.com/GyverLibs/GyverPWM) - библиотека для расширенной генерации ШИМ на ATmega328 (Arduino UNO/Nano/Pro Mini...)

<a id="esp"></a>
## Библиотеки для ESP8266/ESP32
- [Settings](https://github.com/GyverLibs/Settings) - максимально простой и удобный билдер вебморды для настроек
- [FileData](https://github.com/GyverLibs/FileData) - замена EEPROM, хранение любых данных и переменных в файлах
- [GyverPortal](https://github.com/GyverLibs/GyverPortal) - простой конструктор веб интерфейса для esp8266 и ESP32
- [FastBot2](https://github.com/GyverLibs/FastBot2) - очень быстрая и универсальная библиотека для телеграм бота (новая версия)
- [FastBot](https://github.com/GyverLibs/FastBot) - быстрая библиотека для телеграм бота
- [SimplePortal](https://github.com/GyverLibs/SimplePortal) - простой менеджер WiFi для esp8266 для задания логина-пароля WiFi и режима работы
- [GyverNTP](https://github.com/GyverLibs/GyverNTP) - библиотека для получения точного времени с NTP сервера для esp8266/esp32
- [rtc_utils](https://github.com/GyverLibs/rtc_utils) - обёртка для более удобного использования RTC памяти на esp8266
- [EspSleep](https://github.com/GyverLibs/EspSleep) - сон для esp8266 на любой (очень большой) период
- [WiFiConnector](https://github.com/GyverLibs/WiFiConnector) - асинхронное подключение к WiFi с автоматическим созданием AP
- [AutoOTA](https://github.com/GyverLibs/AutoOTA) - библиотека для автоматической проверки ОТА обновлений проекта с GitHub и других источников

<a id="processing"></a>
## Библиотеки для Processing
- [PPlot](https://github.com/GyverLibs/PPlot) - виртуальный плоттер (новая версия)
- ~[ProcessingPlotter](https://github.com/GyverLibs/ProcessingPlotter) - виртуальный плоттер в стиле ардуиновского~
- [cards_ui](https://github.com/GyverLibs/cards_ui) - простенькая библиотека интерфейса для Processing

<a id="js"></a>
## JS библиотеки
- [SVPlot.js](https://github.com/GyverLibs/SVPlot.js) - вывод графиков
- [ProcessingCanvas.js](https://github.com/GyverLibs/ProcessingCanvas.js) - Processing API для HTML Canvas
- [UI.js](https://github.com/GyverLibs/UI.js) - простая модульная панель управления
- [Component.js](https://github.com/GyverLibs/Component.js) - объектный билдер DOM/SVG элементов
- [bson.js](https://github.com/GyverLibs/bson.js) - распаковщик бинарного JSON
- [Packet.js](https://github.com/GyverLibs/Packet.js) - упаковщик и распаковщик данных в бинарный буфер
- [DragBlock.js](https://github.com/GyverLibs/DragBlock.js) - получение событий движения курсора с блока
- [utils.js](https://github.com/GyverLibs/utils.js) - набор утилит
- [Serial.js](https://github.com/GyverLibs/Serial.js) - удобный класс для работы с Serial
- [Websocket.js](https://github.com/GyverLibs/Websocket.js) - обёртка на WebSocket с автоматическим переподключением

![](https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=GyverLibs&theme=github)
![](https://github-profile-summary-cards.vercel.app/api/cards/stats?username=GyverLibs&theme=github)
![](https://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=GyverLibs&theme=github)
