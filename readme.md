# Waveshare ESP32 E-Paper Driver (Modified)

This repository is based on the [official demo code from Waveshare](https://www.waveshare.com/wiki/E-Paper_ESP32_Driver_Board), originally written for various e-Paper displays using the ESP32 Universal E-Paper Driver Board.

🎯 **Goal**: Extend and adapt the demo code to support additional displays, especially the **13.3" Spectra 6 (epd13in3e)**.

## ⚙️ Features

- 📦 Based on Waveshare's official ESP32 E-Paper demo code
- ✅ Added support for new EPD variant: `epd13in3e` (13.3" Spectra 6)
- 🧪 Image upload and rendering via ESP32 web interface (ongoing improvement)
- 🔧 Flexible for further e-Paper variants and custom display integration

## 🧰 Requirements

- ESP32 Universal E-Paper Driver Board
- 13.3" Waveshare Spectra 6 display (or compatible)
- Arduino IDE or PlatformIO
- Libraries: `GxEPD`, `WiFi`, `ESPAsyncWebServer`, `SPI`, etc.
- External 5V power supply recommended

## 🚀 Getting Started

1. Clone this repo:
   ```bash
   git clone https://github.com/yourusername/waveshare-epd-esp32.git
   cd waveshare-epd-esp32
   ```

2. Open `ESP32.ino` in Arduino IDE.

3. Install required libraries listed in `libraries.txt`.

4. Flash to your ESP32 board.

5. Visit the ESP32's IP address (shown in Serial Monitor) to upload images.

## 🖼️ Display Modes & Notes

- This fork targets **Spectra 6 tri-color e-Ink**.
- Works best with preprocessed images (Floyd–Steinberg dithering + palette conversion).
- For image processing steps, see `/docs/Image_Processing.md` (coming soon).

## 📌 Credits

- Original source: [Waveshare Wiki and GitHub](https://www.waveshare.com/wiki/E-Paper_ESP32_Driver_Board)
- Author of this fork: [Your Name](https://github.com/yourusername)
- License: Same as original unless specified (likely MIT)

## 📷 Screenshots

<!-- Optional: add photos of your hardware or screen output -->

---

Pull requests or suggestions welcome!
