# Amp Smart Lighting Controller

## Description

An ESP32 based lighting controller designed for lighting up bicycles, scooters, skateboards, and other micromobility.

## Features

* 3 axis, low noise, low zero-g error accelerometer (LIS2DHH12TR)
* Power supervisor + 2A regulated 3.3V output for long lengths of LEDs (WS2812B or SK6812 are supported out of the box)
* USB C Power Delivery compatible charging (does not implement the USB PD spec)
* One button input connected to the ESP32 through the power supervisor
* One WS2812B LED for status input
* DIO5158 LiPo charger with charging and done charging indications
* Pin connections for LiPo battery (2000 mAh recommended, 1000 mAh doable)
* MessagePack based configuration for lighting
* Bluetooth LE for signaling indicators, brakes
* Customizable and scriptable lighting modes
* Over the Air updates over WiFi
* BLE Mesh (will be enabled in a future firmware update)
* Re-programmable over 6 pin programming header or via USB C so that you can load up your own firmware
* 4 channels of output (power + signal) for LED strips

## More Information

You can purchase a pre-assembled unit from the [Amp website](https://ridewithamp.com/store/amp-beta-0.5)

Alternatively, you can assemble a PCB with your preferred board manufacturer using the Gerbers provided in this repository or modify the project to your needs using the KiCad 5 project files.

## License

[Strong Reciprocal CERN Open Hardware License v2](License.md)