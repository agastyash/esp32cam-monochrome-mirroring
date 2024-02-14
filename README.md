# ESP32-CAM monochrome mirroring

Realtime local processing of frames from an ESP32-CAM, in order to 'mirror' the output video to a monochrome (OLED) display.

### Functionality

The OV2640 camera module directly feeds a dithering algorithm a frame, which is dithered monochromatically using a diffusion matrix. The algorithm outputs an entire grid of pixels to an OLED display when it’s done.

### Performance Expectations

Output bitmap size: 128x64 (SSD1306 resolution)
Framerate (target): 16fps

### Hardware & Software

- AI-THINKER ESP32-CAM
- SSD1306 I2C OLED

- Created using PlatformIO on Visual Studio Code.

### Resources and references

- https://surma.dev/things/ditherpunk/
