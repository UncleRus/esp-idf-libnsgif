# Libnsgif for ESP-IDF

## What is Libnsgif?

Libnsgif is a decoding library for the GIF image file format, written in C.
It was developed as part of the NetSurf project and is available for use by
other software under the MIT licence.

## How to include in ESP-IDF project

Clone this repository recursively to `components` directory of your ESP-IDF
project:

```
cd my_esp_project/components
git clone --recursive https://github.com/UncleRus/esp-idf-libnsgif.git libnsgif
```

Or add it as submodule:

```
cd my_esp_project/components
git submodule add https://github.com/UncleRus/esp-idf-libnsgif.git libnsgif
git submodule update --init --recursive
```

## How to use

See [example](https://github.com/UncleRus/EvLamp/blob/master/main/effects/gif.c).

## Links

https://www.netsurf-browser.org/projects/libnsgif/

## TODO

Examples
