# ESP32-S3 FastLED ESP-IDF Example

Example project to run FastLED on the ESP32-S3 as an ESP-IDF component.
Currently, it's not compiling yet. See https://github.com/FastLED/FastLED/issues/1380

# Prerequisites

- [ESP-IDF Release v4.4.1](https://github.com/espressif/esp-idf/releases/tag/v4.4.1)
- [ESP32 Arduino 2.0.3-RC1](https://github.com/espressif/arduino-esp32/releases/tag/2.0.3-RC1) in `components/arduino`.
- [FastLED master](https://github.com/FastLED/FastLED/commit/08388047ac3e0ebcaafe71563ae2a55421d70c02) with this [CMakeLists.txt](https://github.com/FastLED/FastLED/blob/489baaba551d7e557b4011d8bef3c79da2096ecb/CMakeLists.txt) in `components/FastLED`.

# How to compile

Activate your IDF environment, e.g.

```
$HOME/esp/esp-idf/export.sh
```

Select ESP32-S3 as target, e.g. using the vscode extension or by running

```
idf.py set-target esp32s3
```

Finally, run

```
idf.py build
```
