<!--
---
name: Pirate Audio 3W Amp
class: board
type: audio
formfactor: pHAT
manufacturer: Pimoroni
description: I2S digital audio to 3w stereo amplifier
buy: https://shop.pimoroni.com/products/pirate-audio-3w-stereo-amp
github: https://github.com/pimoroni/pirate-audio
image: 'pimoroni-pirate-audio-3w-stereo-amp.png'
pincount: 40
eeprom: no
power:
  '2':
ground:
  '25':
  '39':
pin:
  '12':
    name: I2S
  '35':
    name: I2S
  '40':
    name: I2S
  '22':
    name: Amp Enable
    active: high
  '29':
    name: Button A
  '31':
    name: Button B
  '36':
    name: Button X
  '38':
    name: Button Y
  '33':
    name: LCD Backlight
  '21':
    name: LCD Data/Command
  '19':
    name: LCD SPI MOSI
    mode: SPI
  '23':
    name: LCD SPI SCLK
    mode: SPI
  '26':
    name: LCD SPI CS
    mode: SPI
install:
  'devices':
  - 'i2s'
-->
# Pirate Audio: 3W Stereo Amp

Fully supported by Mopidy plugins to create an album-art-displaying digital audio player based on the Raspberry Pi.

* I2S DAC
* 3W Stereo Amplifier
* 240x240 SPI LCD
* 4 Playback control buttons