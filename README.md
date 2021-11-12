# rust-embedded-study-esp32-c3
Rust Embedded programming study for ESP32-C3

## ESP32-C3 chip, devkit
* [Expressif ESP32-C3 SoC EN](https://www.espressif.com/en/products/socs/esp32-c3)
* [Expressif ESP32-C3 SoC CN](https://www.espressif.com/zh-hans/products/socs/esp32-c3)
  - [ESP32-C3 Datasheet v1.1 EN](https://www.espressif.com/sites/default/files/documentation/esp32-c3_datasheet_en.pdf)
  - [ESP32-C3 Datasheet v1.1 CN](https://www.espressif.com/sites/default/files/documentation/esp32-c3_datasheet_cn.pdf)
  - [Expressif Module ESP32-C3-MINI-1 Datasheet v1.0 EN](https://www.espressif.com/sites/default/files/documentation/esp32-c3-mini-1_datasheet_en.pdf)
  - [Expressif Module ESP32-C3-MINI-1 Datasheet v1.0 CN](https://www.espressif.com/sites/default/files/documentation/esp32-c3-mini-1_datasheet_cn.pdf)
  - [Expressif Module ESP32-C3-WROOM-02 Datasheet v1.0 EN](https://www.espressif.com/sites/default/files/documentation/esp32-c3-wroom-02_datasheet_en.pdf)
  - [Expressif Module ESP32-C3-WROOM-02 Datasheet v1.0 CN](https://www.espressif.com/sites/default/files/documentation/esp32-c3-wroom-02_datasheet_cn.pdf)
  - [Expressif DevKit ESP32-C3-DevKitM-1 docs EN](https://docs.espressif.com/projects/esp-idf/en/latest/esp32c3/hw-reference/esp32c3/user-guide-devkitm-1.html)
  - [Expressif DevKit ESP32-C3-DevKitM-1 docs CN](https://docs.espressif.com/projects/esp-idf/zh_CN/latest/esp32c3/hw-reference/esp32c3/user-guide-devkitm-1.html)
  - [Expressif DevKit ESP32-C3-DevKitC-02 docs EN](https://docs.espressif.com/projects/esp-idf/en/latest/esp32c3/hw-reference/esp32c3/user-guide-devkitc-02.html)
  - [Expressif DevKit ESP32-C3-DevKitC-02 docs CN](https://docs.espressif.com/projects/esp-idf/zh_CN/latest/esp32c3/hw-reference/esp32c3/user-guide-devkitc-02.html)
* [Ai-Thinker ESP32-C3 Modules](https://docs.ai-thinker.com/en/esp32c3)
  - ESP-C3-12F: CN EN
  - ESP-C3-32S: CN EN
  - ESP-C3-13: CN EN
  - ESP-C3-13U: CN EN
  - ESP-C3-01M: CN EN
  - ESP-C3-M1:CN EN
  - ESP-C3-M1-I:CN EN 
  - ESP-C3-12F_Kit: CN EN
  - ESP32-C3-32S_Kit: CN EN
  - ESP-C3-01M_Kit: CN EN
  - ESP-C3-13U_Kit: CN EN
  - ESP-C3-13_Kit: CN EN
  - ESP-C3-M1-Kit: CN EN
  - ESP-C3-M1-I-Kit: CN EN

  - Ai-Thinker Modules

    ESP32-C3- | Pkg | Size/mm | Ant | IO total | IO list | IO list | Flash
     --: | -- | -- | -- | -- | -- | -- | -- 
    M1-l | SMD-61 | 12.5x13.2x2.4 | IPEX  | 15 | [0,10][18,21] | GPIO / ADC / UART / PWM / I2C / I2S / SPI | 4M (Int) 
    M1   | SMD-61 | 16.6x13.2x2.4 | OnBrd | 15 | [0,10][18,21] | GPIO / ADC / UART / PWM / I2C / I2S / SPI | 4M (Int)
    01M  | DIP-18 | 18.0x18.0x2.8 | OnBrd | 15 | [0,10][18,21] | GPIO / ADC / UART / PWM / I2C / I2S       | 4M (Int)
    13U  | SMD-18 | 14.0x18.0x3.1 | IPEX  | 15 | [0,10][18,21] | GPIO / ADC / UART / PWM / I2C / I2S       | 4M/2M (Int/Ext) 
    13   | SMD-61 | 20.0x18.0x3.1 | I+O   | 15 | [0,10][18,21] | GPIO / ADC / UART / PWM / I2C / I2S / SPI | 4M/2M (Int/Ext) 
    32S  | SMD-38 | 25.5x18.0x3.1 | I+O   | 22 | [0,21]        | GPIO / ADC / UART / PWM / I2C / I2S / SPI | 4M/2M (Int/Ext) 
    12F  | SMD-22 | 24.0x16.0x3.1 | I+O   | 15 | [0,10][18,21] | GPIO / ADC / UART / PWM / I2C / I2S / SPI | 4M/2M (Int/Ext) 

    * Power: 3.0-3.6V >500mA
    * TTL: 110-4.608Mbps default 115.2k bps
    * Security: WEP/WPA/2-PSK

## Rust programming docs


## Discussion


## ESP32-C3 projects
* [ducktec/esp32c3-hal: An experimental Rust HAL for the ESP32-C3 SoC](https://github.com/ducktec/esp32c3-hal)
  > This is an experimental Rust HAL crate for the ESP32-C3 SoC.
  > 
  > ⚠️ Please note the emphasis on experimental! Very little works (yet) and what works is not comprehsively tested and will almost certainly contain bugs. Please don't use for real projects at this point in time. The API can and will change.
* [xuhongv/ESP32WiFiBleControlProject](https://github.com/xuhongv/ESP32WiFiBleControlProject)
  - WeChat applet Bluetooth + WiFi dual control Ai-Thinker ESP32-C3 module application demonstration
  - [微信小程序蓝牙+WiFi控制安信可ESP32-S/C3S模块应用示范 - 帖子 Post (Chinese)](https://aithinker.blog.csdn.net/article/details/114983580)
* [Rust ESP32-C3 STD "Hello World" - from Jia Ye 知乎](https://zhuanlan.zhihu.com/p/428911351)
 
## Issues and solution


## News

