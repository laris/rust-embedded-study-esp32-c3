# rust-embedded-study-esp32-c3
Rust Embedded programming study for ESP32-C3

## ESP32-C3 chip, devkit, both pdf file cache in datasheets directory
* [Expressif ESP32-C3 SoC EN](https://www.espressif.com/en/products/socs/esp32-c3)
* [Expressif ESP32-C3 SoC CN](https://www.espressif.com/zh-hans/products/socs/esp32-c3)
  - [ESP Product Selector](https://products.espressif.com/#/product-selector)
  - [ESP32-C3 Datasheet v1.1 EN](https://www.espressif.com/sites/default/files/documentation/esp32-c3_datasheet_en.pdf)
  - [ESP32-C3 Datasheet v1.1 CN](https://www.espressif.com/sites/default/files/documentation/esp32-c3_datasheet_cn.pdf)
  - [ESP32­-C3 Technical Reference Manual v0.4 EN](https://www.espressif.com/sites/default/files/documentation/esp32-c3_technical_reference_manual_en.pdf)
  - [ESP32-­C3 Technical Reference Manual v0.4 CN](https://www.espressif.com/sites/default/files/documentation/esp32-c3_technical_reference_manual_cn.pdf)
  - [Module ESP32-C3-MINI-1 Datasheet v1.0 EN](https://www.espressif.com/sites/default/files/documentation/esp32-c3-mini-1_datasheet_en.pdf)
  - [Module ESP32-C3-MINI-1 Datasheet v1.0 CN](https://www.espressif.com/sites/default/files/documentation/esp32-c3-mini-1_datasheet_cn.pdf)
  - [Module ESP32-C3-WROOM-02 Datasheet v1.0 EN](https://www.espressif.com/sites/default/files/documentation/esp32-c3-wroom-02_datasheet_en.pdf)
  - [Module ESP32-C3-WROOM-02 Datasheet v1.0 CN](https://www.espressif.com/sites/default/files/documentation/esp32-c3-wroom-02_datasheet_cn.pdf)
  - [DevKit ESP32-C3-DevKitM-1 docs EN](https://docs.espressif.com/projects/esp-idf/en/latest/esp32c3/hw-reference/esp32c3/user-guide-devkitm-1.html)
  - [DevKit ESP32-C3-DevKitM-1 docs CN](https://docs.espressif.com/projects/esp-idf/zh_CN/latest/esp32c3/hw-reference/esp32c3/user-guide-devkitm-1.html)
  - [DevKit ESP32-C3-DevKitC-02 docs EN](https://docs.espressif.com/projects/esp-idf/en/latest/esp32c3/hw-reference/esp32c3/user-guide-devkitc-02.html)
  - [DevKit ESP32-C3-DevKitC-02 docs CN](https://docs.espressif.com/projects/esp-idf/zh_CN/latest/esp32c3/hw-reference/esp32c3/user-guide-devkitc-02.html)
* [Ai-Thinker ESP32-C3 Modules](https://docs.ai-thinker.com/en/esp32c3)
  - ESP-C3-12F: [CN](https://docs.ai-thinker.com/_media/esp32/docs/esp-c3-12f规格书.pdf) [EN](https://docs.ai-thinker.com/_media/esp32/docs/esp-c3-12f_specification.pdf)
  - ESP-C3-32S: [CN](https://docs.ai-thinker.com/_media/esp32/docs/esp-c3-32s_中文.pdf) [EN](https://docs.ai-thinker.com/_media/esp32/docs/esp-c3-32s_英文.pdf)
  - ESP-C3-13: [CN](https://docs.ai-thinker.com/_media/esp32/docs/esp-c3-13规格书.pdf) [EN](https://docs.ai-thinker.com/_media/esp32/docs/esp-c3-13_specification.pdf)
  - ESP-C3-13U: [CN](https://docs.ai-thinker.com/_media/esp32/docs/esp-c3-13u规格书.pdf) [EN](https://docs.ai-thinker.com/_media/esp32/docs/esp-c3-13u_specification.pdf)
  - ESP-C3-01M: [CN](https://docs.ai-thinker.com/_media/esp32/docs/esp-c3-01m规格书.pdf) [EN](https://docs.ai-thinker.com/_media/esp32/docs/esp-c3-01m_specification.pdf)
  - ESP-C3-M1: [CN](https://docs.ai-thinker.com/_media/esp32/esp-c3-m1_v1.1.1_规格书.pdf) [EN](https://docs.ai-thinker.com/_media/esp32/esp-c3-m1_v1.1.1_specification.pdf)
  - ESP-C3-M1-I: [CN](https://docs.ai-thinker.com/_media/esp32/esp-c3-m1-i_v1.1.1_规格书.pdf) [EN](https://docs.ai-thinker.com/_media/esp32/esp-c3-m1-i_v1.1.1_specification.pdf)
  - ESP-C3-12F_Kit: [CN](https://docs.ai-thinker.com/_media/esp32/docs/esp-c3-12f-kit-v1.0_规格书.pdf) [EN](https://docs.ai-thinker.com/_media/esp32/docs/esp-c3-12f-kit-v1.0_specification.pdf)
  - ESP32-C3-32S_Kit: [CN](https://docs.ai-thinker.com/_media/esp32/docs/esp-c3-32s-kit-v1.0_规格书.pdf) [EN](https://docs.ai-thinker.com/_media/esp32/docs/esp-c3-32s-kit-v1.0_specification.pdf)
  - ESP-C3-01M_Kit: [CN](https://docs.ai-thinker.com/_media/esp32/docs/esp-c3-01m-kit-v1.0_规格书.pdf) [EN](https://docs.ai-thinker.com/_media/esp32/docs/esp-c3-01m-kit-v1.0_specification.pdf)
  - ESP-C3-13U_Kit: [CN](https://docs.ai-thinker.com/_media/esp32/docs/esp-c3-13u-kit-v1.0_规格书.pdf) [EN](https://docs.ai-thinker.com/_media/esp32/docs/esp-c3-13u-kit-v1.0_specification.pdf)
  - ESP-C3-13_Kit: [CN](https://docs.ai-thinker.com/_media/esp32/docs/esp-c3-13-kit-v1.0_规格书.pdf) [EN](https://docs.ai-thinker.com/_media/esp32/docs/esp-c3-13-kit-v1.0_specification.pdf)
  - ESP-C3-M1-Kit: [CN](https://docs.ai-thinker.com/_media/esp32/nodemcu-esp-c3-m1-kit_v1.2.0_规格书.pdf) [EN](https://docs.ai-thinker.com/_media/esp32/nodemcu-esp-c3-m1-kit_v1.2.0_specification.pdf)
  - ESP-C3-M1-I-Kit: [CN](https://docs.ai-thinker.com/_media/esp32/nodemcu-esp-c3-m1-i-kit_v1.2.0_规格书.pdf) [EN](https://docs.ai-thinker.com/_media/esp32/nodemcu-esp-c3-m1-i-kit_v1.2.0_specification.pdf)
   
  - Ai-Thinker Modules

    ESP32-C3- | Pkg | Size/mm | Ant | GPIO | GPIO | GPIO | Flash
     :-- | -- | -- | -- | -- | -- | -- | -- 
    M1-I | SMD-61 | 12.5x13.2x2.4 | IPEX  | 15 | [0,10][18,21] | GPIO / ADC / UART / PWM / I2C / I2S / SPI | 4M (Int) 
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
* [laris/rust-embedded-study-esp32-c3: Rust Embedded programming study for ESP32-C3](https://github.com/laris/rust-embedded-study-esp32-c3)

* [MabezDev/esp32c3-experiments](https://github.com/MabezDev/esp32c3-experiments)
* [esp-rs/esp32c3: Peripheral access crate for the ESP32-C3](https://github.com/esp-rs/esp32c3)
* [ESP32-C3 support · Issue #53 · esp-rs/esp32-hal](https://github.com/esp-rs/esp32-hal/issues/53)
* [ducktec/esp32c3-hal: An experimental Rust HAL for the ESP32-C3 SoC](https://github.com/ducktec/esp32c3-hal)
  > This is an experimental Rust HAL crate for the ESP32-C3 SoC.
  > 
  > ⚠️ Please note the emphasis on experimental! Very little works (yet) and what works is not comprehsively tested and will almost certainly contain bugs. Please don't use for real projects at this point in time. The API can and will change.
  - [riscv-software-src/homebrew-riscv: homebrew (macOS) packages for RISC-V toolchain](https://github.com/riscv-software-src/homebrew-riscv)
* [esp-rs/rust-build: Workflows for building Rust fork esp-rs/rust with Xtensa support](https://github.com/esp-rs/rust-build)
* [esp-rs/esp-idf-template](https://github.com/esp-rs/esp-idf-template)
  > A "Hello, world!" template of a Rust binary crate for the ESP-IDF framework.

* [ivmarkov/rust-esp32-std-demo: Rust on ESP32 STD demo app](https://github.com/ivmarkov/rust-esp32-std-demo)
  > A demo STD binary crate for the ESP32[XX] and ESP-IDF, which connects to WiFi, Ethernet, drives a small HTTP server and draws on a LED screen.
* [imxood/learn-rust](https://github.com/imxood/learn-rust)
* [wuxx/nanoESP32-C3: ESP32-C3 dev board by muselab](https://github.com/wuxx/nanoESP32-C3)
* [xuhongv/ESP32WiFiBleControlProject](https://github.com/xuhongv/ESP32WiFiBleControlProject)
  - WeChat applet Bluetooth + WiFi dual control Ai-Thinker ESP32-C3 module application demonstration
  - [微信小程序蓝牙+WiFi控制安信可ESP32-S/C3S模块应用示范 - 帖子 Post (Chinese)](https://aithinker.blog.csdn.net/article/details/114983580)

## ESP32-C3 Tech posts
* [Rust ESP32-C3 STD "Hello World" - from Jia Ye 知乎](https://zhuanlan.zhihu.com/p/428911351)

## ESP8266, ESP32-S
* [espressif/llvm-project: Fork of LLVM with Xtensa specific patches. To be upstreamed.](https://github.com/espressif/llvm-project)
* [esp-rs/rust: Rust for the xtensa architecture. Built in targets for the ESP32 and ESP8266](https://github.com/esp-rs/rust)
* [esp-rs/esp8266-hal: A experimental hardware abstraction layer for the esp8266 written in Rust.](https://github.com/esp-rs/esp8266-hal)

## ESP8266, ESP32-S Tech Posts
* https://mabez.dev/blog/posts/esp-rust-ecosystem/
* https://www.reddit.com/r/rust/comments/gyxbkv/what_is_the_state_of_rust_on_the_esp8266/
* https://dentrassi.de/2019/06/16/rust-on-the-esp-and-how-to-get-started/ 
* https://githubmemory.com/repo/coenraadhuman/blinky-esp8266-rust
* 

## Issues and solution


## News

