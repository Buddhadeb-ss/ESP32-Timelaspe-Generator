# ESP32-CAM Timelapse

A implementation of esp32 cam to take picture and later turning it into a video.

A simple ESP32-CAM project that captures JPEG frames to an SD card and
converts them into a timelapse video.

## Demo
[▶ Watch the timelapse](demo/timelapse.mp4)

## How it works
### Image Capture Workflow

ESP32-CAM Power On

⬇

Camera Initialization

⬇

SD Card Initialization

⬇

Image Capture

⬇

Filename Generation

⬇

JPEG Image Storage

⬇

Frame Buffer Release

⬇

100 ms Delay

⬇

Repeat Capture Cycle

## Documentation
Step-by-step setup and usage guide:
- [Build and Usage Guide](tools/guide.md)
