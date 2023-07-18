# esp-tm1637

Esp32-xx component for TM1637. This is essentially a component version of [petrows](https://github.com/petrows/esp-32-tm1637/tree/master) driver with added ESP32-C6 support. This code has been tested on an `ESP32-C6-DevkitC` board.  

## Introduction

This is an library of control TM1637 LCD 7-segment display using ESP-32 IDF toolchain ESP-IDF.

## Features

    Display numbers
    Display raw segment data
    Display floating point numbers

## Important notes

This library uses ets_delay_us() function to generate i2c-like control sequences. Please note - while using within FreeRTOS task will be blocked while data is transmitted.


## Example

The example is available at: main/main.c

## Source Code

The source is available from GitHub petrows/esp-32-tm1637.

## License

The code in this project is licensed under the MIT license - see LICENSE for details.

Inital idea based on Arduino <tm1637.h> library, written by Frankie.Chu Copyright (c) 2012 seeed technology inc.

## Contacts

    Email: bez@ineltek.it
    
