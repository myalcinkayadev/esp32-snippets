# ESP32 Snippets

The main purpose of this repo is to collect samples that may be needed especially in real-life applications based on IoT, so that research time is shortened and more time is left for development.

## Quickstart
- [Documentation](https://docs.espressif.com/projects/esp-idf/en/latest/esp32)
- [ESP-IDF Offical Examples](https://github.com/espressif/esp-idf/tree/master/examples)

### Prerequisites

- [SDK Environment Setup](https://docs.espressif.com/projects/esp-idf/en/latest/esp32/get-started/index.html#step-1-install-prerequisites)

### Table of contents

* [Snippets](#snippets)
* [Demos](#demos)

## Snippets
* [Base64 Encode Decode with mbedtls](#base64-encode-decode-with-mbedtls)
* [SQLite3](#sqlite3)
* [NFC Pool](#nfc-pool)
* [Websocket client](#websocket-client)
* [Websocket client with protobuf](#websocket-client-with-protobuf)

### Base64 Encode Decode with mbedtls
`main/base64_main.c` – [Example](https://github.com/myalcinkayadev/esp32-base64-mbedtls) of base64 encode and decode  using mbedtls.

### SQLite3
`main/sqlite3_main.c` - [Example](https://github.com/myalcinkayadev/esp32-sqlite3) of sqlite3 adapted for ESP environment.

### NFC Pool
`main/nfc_pool_main.c` – [Example](https://github.com/myalcinkayadev/esp32-libnfc) of nfc pool adapted for ESP environment and written using [libnfc](https://github.com/nfc-tools/libnfc).

### Websocket client

### Websocket client with protobuf

## Demos
* [ESP32 httpd preact application](#esp32-httpd-preact-application)
* [Preact embedded starter](#preact-embedded-starter)

### ESP32 httpd preact application
[Example](https://github.com/myalcinkayadev/esp32-preact-httpd-demo)

### Preact embedded starter
Web app with a modern web framework for an embedded device, due to limited storage(under 100kb) and processing power(single microcontroller and <50 KB of ram)
<br>
[Demo](https://github.com/myalcinkayadev/preact-embedded-starter)
