# AirMouse

Turn your Android phone into a powerful **Bluetooth keyboard, mouse, media remote, presenter, and gamepad** for any PC, laptop, TV, or device that accepts Bluetooth input — featuring a fully customizable, widget-based control system.

---

## 💡 Overview

**AirMouse** turns your smartphone into a versatile wireless input device. Whether you need a quick remote control for presentations, a media controller for your smart TV or PC, a touch trackpad, or a dedicated gaming layout, AirMouse gives you full control with low latency and seamless connectivity.

---

## ✨ Key Features

* **🖱️ Air Mouse & Trackpad:** Use your phone’s gyroscope/accelerometer or screen as a precise optical mouse or trackpad with custom sensitivity controls.
* **⌨️ Full Keyboard Support:** Complete layout with modifier keys (Ctrl, Alt, Shift, Fn, Meta/Super), function keys (F1–F12), and key combinations.
* **🎮 Gamepad & Presenter Mode:** Pre-configured layouts for gaming, slide control (PowerPoint, Keynote), and media playback.
* **🎨 Fully Customizable Widgets:** Drag-and-drop buttons, sliders, and controls to build your own custom remote interface.
* **🔌 Direct Bluetooth HID:** Connects directly via standard Bluetooth HID profile — **no extra software required on the target device** in most setups.

---

## 🛠️ Project Structure

```text
AirMouse/
├── .github/workflows/   # CI/CD automated build pipelines
├── app/                 # Main Android application source code
├── gradle/              # Gradle wrapper and build configurations
├── receiver/            # Desktop companion / receiver modules
├── store/               # Play Store assets, screenshots, and graphics
├── LICENSE              # Open-source license (MIT)
├── README.md            # Repository documentation
└── build.gradle.kts     # Main build configuration script
