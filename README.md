# Face_Detection_LED_UART_STM32

# STM32F401RE + Python OpenCV Object Detection with UART Control

This project demonstrates using an STM32F401RE microcontroller to control an LED based on face detection using OpenCV in Python.

## 🧠 Project Features

- Uses Haar Cascade in Python OpenCV to detect faces.
- Sends serial data via UART to STM32 to:
  - Turn ON LED when a face is detected.
  - Turn OFF LED when face disappears or OpenCV window is closed.
- Automatically turns OFF LED after 3 seconds of no UART activity.




