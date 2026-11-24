# Torsion Manager

[🇮🇩 Bahasa Indonesia](README.md) | [🇬🇧 English](README_EN.md)

> **Modern desktop application for configuration, tuning, and optimization of Force Feedback (FFB) for PXN V10 & PXN V99 racing wheels on Windows.**

---

## 🌟 Overview

**Torsion Manager** is a dedicated desktop utility software designed to make it effortless for PXN racing wheel users (specifically **PXN V10** and **PXN V99** series) to calibrate, tune profiles, diagnose hardware, and monitor real-time telemetry directly from your Windows PC.

No more switching back and forth to a smartphone companion app while sim racing on PC! Torsion Manager gives you comprehensive, real-time control over your entire racing rig ecosystem—from granular Force Feedback (FFB) parameters, pedal linearity curves, shifter, and USB handbrake configurations, to live interactive racing telemetry dashboards.

### ✨ Key Features

- 🔄 **Flexible Connectivity (BLE & USB)**: Fast wireless scanning and pairing via Bluetooth Low Energy (BLE) as well as direct wired USB support.
- 🏎️ **Precision Steering & FFB Tuning**: Adjust steering rotation angle (270° to 900°), return force, damper, friction, and center spring resistance in real time.
- 🦶 **Precise Pedal Calibration**: Customize deadzones, linearity response curves, and precision calibrations for Throttle, Brake, and Clutch pedals.
- 🕹️ **Hardware Test Center**: Interactive input visualizer to diagnose wheel rotation, buttons, paddle shifters, H-pattern shifters, and handbrakes.
- 📁 **Preset Library & Racing Templates**: Pre-configured, motorsport-specific profiles including _Race_, _Drift Pro_, _Offroad_, _SUV_, _Realistic_, and _Extreme_.
- 📊 **Interactive Telemetry & Speedometer Gauges**: Analog and digital dashboard gauges monitoring live RPM, speed, gear selection, and vehicle telemetry.
- ⚙️ **Game INI Manager & Keybinding**: Search game parameters, customize key/button bindings, and seamlessly apply configurations to racing simulators.

---

## 📸 Interface & Feature Screenshots

Here is an overview of the key interfaces and features in Torsion Manager:

### 1. Device Connection (Bluetooth LE & USB)

Automatic scanning and instant pairing with PXN devices via wireless BLE or wired USB with real-time status indicators.

|       BLE Device Scanning        |         Device Found & Connecting          |            USB Connection Mode             |
| :------------------------------: | :----------------------------------------: | :----------------------------------------: |
| ![BLE Scan](docs/01_connect.png) | ![Device Found](docs/02_connect_found.png) | ![USB Connection](docs/20_connect_usb.png) |

---

### 2. Steering & Pedal Tuning Dashboard

Full control over steering wheel rotation range, Force Feedback power, damper resistance, and pedal sensitivity curves.

|           Rotation Angle & FFB Tuning           |         Pedal Sensitivity & Calibration         |
| :---------------------------------------------: | :---------------------------------------------: |
| ![Wheel Dashboard](docs/03_dashboard_wheel.png) | ![Pedal Dashboard](docs/04_dashboard_pedal.png) |

---

### 3. Racing Style Templates & Presets

Select pre-tuned configurations optimized for various motorsport disciplines or craft and save your own custom profiles.

|                Race Template                |                Drift Pro Template                 |            Preset Manager            |
| :-----------------------------------------: | :-----------------------------------------------: | :----------------------------------: |
| ![Race Template](docs/12_template_race.png) | ![Drift Template](docs/13_template_drift_pro.png) | ![Presets List](docs/06_presets.png) |

---

### 4. Hardware Input Test Center

Test every button, axis, paddle shifter, H-shifter gear, and handbrake in real-time to ensure optimal hardware responsiveness.

|       Wheel & Button Test       |              USB H-Shifter Test               |                USB Handbrake Test                 |
| :-----------------------------: | :-------------------------------------------: | :-----------------------------------------------: |
| ![Wheel Test](docs/05_test.png) | ![Shifter Test](docs/16_usb_shifter_test.png) | ![Handbrake Test](docs/18_usb_handbrake_test.png) |

---

### 5. Telemetry & Speedometer Monitor

Real-time simulation instrument clusters featuring customizable analog and digital gauges for speed, RPM, and live telemetry data.

|                  Analog Telemetry Gauge                   |                   Digital Telemetry Gauge                   |                 Speedometer Demo                  |
| :-------------------------------------------------------: | :---------------------------------------------------------: | :-----------------------------------------------: |
| ![Analog Telemetry](docs/21_telemetry_analog_monitor.png) | ![Digital Telemetry](docs/22_telemetry_digital_monitor.png) | ![Speedometer Demo](docs/21_speedometer_demo.png) |

---

### 6. Game INI Tweaker & Keybinding

Easily tweak simulation configuration files and remap wheel buttons to match your preferred game settings.

|            Game INI Parameters            |            Key & Button Binding            |
| :---------------------------------------: | :----------------------------------------: |
| ![INI Parameters](docs/07_ini_params.png) | ![Button Binding](docs/09_ini_binding.png) |

---

## 📋 System Requirements

Before installing, make sure your computer meets the following requirements:

- **Operating System**: Windows 10 or Windows 11 (64-bit)
- **Connectivity**: Bluetooth adapter supporting Bluetooth Low Energy (BLE 4.0 or newer) / USB Port
- **Supported Hardware**:
  - PXN V10
  - PXN V99
  - USB Racing Accessories (Shifter & Handbrake)

---

## 🚀 Installation & Getting Started

Choose one of the installation methods below based on your preference:

---

### Method 1: Using Windows Installer (Recommended for Users)

The quickest and simplest way to run the application without installing Python.

1. **Download Installer**:
   - Available in the local folder `Aplication/Torsion-Manager-Setup-1.0.0.exe` or download the latest release from the [Releases](https://github.com/) page.
   - Run the setup file: `Torsion-Manager-Setup-1.0.0.exe`.

2. **Run Installer**:
   - Double-click `Torsion-Manager-Setup-1.0.0.exe`.
   - If prompted by _Windows SmartScreen_, click **More info** then choose **Run anyway**.
   - Follow the setup wizard instructions to complete installation.

3. **Launch the App**:
   - Open the application using the **Torsion Manager** Desktop shortcut or from the **Start** menu.

_(A **Portable** zip package is also available: extract the folder and run `Torsion-Manager.exe`)._

---

## 🎮 How to Connect Your Wheel

1. **Power On the Wheel**:
   - Connect the power supply and USB cable of your PXN V10 or V99 to your PC.
   - Ensure the wheel base is powered on (LED status indicator is illuminated).

2. **Enable Bluetooth on PC**:
   - Navigate to Windows **Settings** > **Bluetooth & devices** > ensure Bluetooth is switched **On**.

3. **Connect in Torsion Manager**:
   - Open the **Torsion Manager** application.
   - The app will automatically scan for nearby devices via Bluetooth LE.
   - Click the **Connect** button on the discovered device card.
   - Once connected, the status indicator turns green and you are ready to configure!

---

## 🛠️ Troubleshooting

| Issue                                                           | Solution                                                                                                                                                   |
| --------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `'python' is not recognized as an internal or external command` | Python is not added to Windows Environment Variables. Re-run Python installer, choose **Modify**, check **Add Python to PATH**, and restart your terminal. |
| **Wheel not discovered during BLE scan**                        | Verify PC Bluetooth is active, the wheel base is turned on, and the wheel is not currently paired/connected to the mobile smartphone app.                  |
| **`bleak` error or Bluetooth permission denied**                | On Windows 10/11, ensure app permission to access Bluetooth radios is enabled under **Settings > Privacy & security > Other devices / Radios**.            |

---

## 📄 License

Distributed under the GNU General Public License v3 (GPL-3.0). See [LICENSE](LICENSE) for details.
