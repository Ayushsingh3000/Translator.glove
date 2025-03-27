Sign Language Translator (Text-to-Speech) using Arduino, ESP32, and Flux Sensors

Overview

This project is a Sign Language Translator that converts hand gestures into text and speech using an ESP32, flux sensors, and Arduino. The system aims to assist individuals with speech impairments by providing real-time conversion of sign language into audible speech.

Components Used

ESP32 (Microcontroller)

Arduino (Programming and control)

Flux Sensors (For detecting finger movements)

Text-to-Speech Module (For voice output)

OLED Display / LCD (For text output)

Battery / Power Supply

Working Principle

Hand Gesture Detection:

Flux sensors placed on gloves detect finger movements.

The sensors measure the magnetic field variations as fingers move.

Data Processing:

The ESP32 reads the sensor values and processes them.

Using predefined gesture mappings, the microcontroller identifies the corresponding text.

Text-to-Speech Conversion:

The recognized text is displayed on the OLED/LCD screen.

The text is then converted to speech using a TTS (Text-to-Speech) module.

Installation & Setup

Hardware Setup:

Connect the flux sensors to the ESP32 analog input pins.

Integrate the TTS module for speech output.

Connect the display module for text output.

Ensure proper power connections.

Software Requirements:

Arduino IDE

ESP32 Board Manager installed in Arduino IDE

Libraries:

Wire.h (for I2C communication)

Adafruit_GFX.h and Adafruit_SSD1306.h (for OLED display)

SpeechSynthesis.h (for TTS conversion)

Code Uploading:

Write or upload the Arduino code for gesture recognition and speech output.

Compile and upload the code to the ESP32 using the Arduino IDE.

Usage

Wear the glove with integrated flux sensors.

Perform sign language gestures.

The ESP32 processes the gestures and converts them into text.

The text is displayed on the OLED/LCD screen.

The TTS module converts the text into speech.

Applications

Assistive Technology for people with speech impairments.

Educational Tool for learning sign language.

Real-time Communication between sign language users and non-sign language users.

Future Improvements

Machine Learning Integration for improved accuracy.

Wireless Communication using Bluetooth/Wi-Fi.

Multilingual Speech Output.

Contributors

[Your Name]

License

This project is open-source and licensed under the MIT License.
