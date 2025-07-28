# DIY-Smart-Speaker-for-HA

## This project focuses on building a smart speaker using an ESP32-S3 Zero, programmed with ESPHome, for seamless integration with Home Assistant.

To ensure optimal audio quality and volume, we’ve opted for a USB-powered active speaker.
This is because speakers connected directly to the Max98357 amplifier tend to have poor sound quality.
Active speakers are ideal for this DIY project as they include a built-in amplifier.

**Here are the components for this smart speaker:**

- ESP32-S3 Zero microcontroller
- MAX98357 I²S Amplifier
- USB-powered active speaker box (e.g., 2x3W 5V AD8403)
- WS2812B LEDs (for visual indicators or effects)
- USB 5V DC power supply

## Circuit Diagram:

Below is a diagram showing how I connected the MAX98357 amplifier to the I2S bus of the microcontroller, and then the output of the MAX98357 to the input of the USB speaker.

![This is wiring diagram.](https://forgani.com/wp-content/2025/07/voice_web.jpg)

> [!NOTE]
> For more information: [DIY-Smart-Speaker](https://forgani.com/electronics-projects/diy-smart-speaker-for-home-assistant/).
