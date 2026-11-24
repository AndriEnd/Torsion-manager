# Torsion Manager

> **Aplikasi desktop modern untuk konfigurasi, tuning, dan optimasi Force Feedback (FFB) setir balap PXN V10 & PXN V99 di Windows.**

---

## 🌟 Overview

**Torsion Manager** adalah software utilitas desktop yang dirancang khusus untuk mempermudah pengguna racing wheel PXN (khususnya seri **PXN V10** dan **PXN V99**) dalam melakukan kalibrasi, penyesuaian profil, pengujian perangkat keras, serta pemantauan telemetri langsung dari PC Windows Anda.

Tanpa perlu repot beralih ke aplikasi smartphone saat bermain simulator balap di PC, Torsion Manager memberikan kendali penuh terhadap seluruh ekosistem kemudi Anda—mulai dari karakteristik Force Feedback (FFB), kurva linearitas pedal, shifter, handbrake USB, hingga instrumen telemetri balap real-time.

### ✨ Fitur Utama

- 🔄 **Koneksi Fleksibel (BLE & USB)**: Mendukung pemindaian dan penyambungan nirkabel Bluetooth Low Energy (BLE) serta mode kabel USB langsung.
- 🏎️ **Tuning Kemudi & Force Feedback**: Atur sudut rotasi (270° hingga 900°), efek return force, damper, friction, dan spring centering secara real-time.
- 🦶 **Kalibrasi Pedal Presisi**: Kustomisasi deadzone, kurva respons linearitas, dan kalibrasi akurat untuk Throttle, Brake, dan Clutch.
- 🕹️ **Pusat Pengujian Hardware (Hardware Test Center)**: Visualisasi input interaktif untuk mendiagnosis setir, tombol, paddle shifter, H-pattern shifter, dan handbrake.
- 📁 **Pustaka Preset & Template Balap**: Dilengkapi template siap pakai untuk berbagai disiplin balap seperti _Race_, _Drift Pro_, _Offroad_, _SUV_, _Realistic_, dan _Extreme_.
- 📊 **Monitor Telemetri & Speedometer Interaktif**: Instrumen gauge analog dan digital interaktif untuk memantau RPM, kecepatan, posisi transmisi, dan telemetri kendaraan.
- ⚙️ **Manajemen Parameter Game INI & Keybinding**: Pencarian parameter, pemetaan tombol (keybinding), dan penerapan konfigurasi game simulator secara instan.

---

## 📸 Antarmuka & Tangkapan Layar

Berikut adalah gambaran antarmuka dan beberapa fitur utama yang tersedia di Torsion Manager:

### 1. Koneksi Perangkat (Bluetooth LE & USB)

Pemindaian otomatis dan deteksi perangkat PXN secara nirkabel maupun berkabel dengan indikator status koneksi yang jelas.

|        Pencarian Perangkat BLE        |                Perangkat Terdeteksi                |           Mode Sambungan USB            |
| :-----------------------------------: | :------------------------------------------------: | :-------------------------------------: |
| ![Pencarian BLE](docs/01_connect.png) | ![Perangkat Terdeteksi](docs/02_connect_found.png) | ![Koneksi USB](docs/20_connect_usb.png) |

---

### 2. Dashboard Tuning Kemudi & Pedal

Kendali penuh untuk mengubah sudut rotasi setir, kekuatan Force Feedback, damper, serta kalibrasi deadzone dan kurva sensitivitas pedal.

|          Konfigurasi Sudut Putar & FFB           |          Kalibrasi Sensitivitas Pedal           |
| :----------------------------------------------: | :---------------------------------------------: |
| ![Dashboard Kemudi](docs/03_dashboard_wheel.png) | ![Dashboard Pedal](docs/04_dashboard_pedal.png) |

---

### 3. Template & Preset Gaya Balap

Pilih profil konfigurasi yang telah dioptimalkan untuk berbagai jenis motorsport atau buat preset khusus Anda sendiri.

|            Template Balap (Race)            |                Template Drift Pro                 |             Preset Manager             |
| :-----------------------------------------: | :-----------------------------------------------: | :------------------------------------: |
| ![Template Race](docs/12_template_race.png) | ![Template Drift](docs/13_template_drift_pro.png) | ![Daftar Presets](docs/06_presets.png) |

---

### 4. Pusat Pengujian Input Hardware (Test Center)

Uji respon input setiap komponen perangkat keras secara langsung untuk memastikan semua fungsi berjalan optimal.

|    Pengujian Tombol & Setir     |            Pengujian H-Shifter USB            |              Pengujian Handbrake USB              |
| :-----------------------------: | :-------------------------------------------: | :-----------------------------------------------: |
| ![Test Setir](docs/05_test.png) | ![Test Shifter](docs/16_usb_shifter_test.png) | ![Test Handbrake](docs/18_usb_handbrake_test.png) |

---

### 5. Monitor Telemetri & Speedometer

Visualisasi instrumen balap real-time dengan pilihan tampilan speedometer analog dan digital gauge.

|                  Telemetri Gauge Analog                   |                   Telemetri Gauge Digital                   |                 Speedometer Demo                  |
| :-------------------------------------------------------: | :---------------------------------------------------------: | :-----------------------------------------------: |
| ![Telemetri Analog](docs/21_telemetry_analog_monitor.png) | ![Telemetri Digital](docs/22_telemetry_digital_monitor.png) | ![Speedometer Demo](docs/21_speedometer_demo.png) |

---

### 6. Pengaturan Game INI & Keybinding

Modifikasi dan terapkan file parameter konfigurasi game simulator balap serta sesuaikan binding tombol kemudi.

|        Parameter Konfigurasi INI         |           Pengaturan Keybinding            |
| :--------------------------------------: | :----------------------------------------: |
| ![Parameter INI](docs/07_ini_params.png) | ![Binding Tombol](docs/09_ini_binding.png) |

---

## 📋 Persyaratan Sistem

Sebelum memulai instalasi, pastikan sistem Anda memenuhi persyaratan berikut:

- **Sistem Operasi**: Windows 10 atau Windows 11 (64-bit)
- **Konektivitas**: Bluetooth Adapter yang mendukung Bluetooth Low Energy (BLE 4.0 atau lebih baru) / Port USB
- **Perangkat yang Didukung**:
  - PXN V10
  - PXN V99
  - Aksesori USB (Shifter & Handbrake)

---

## 🚀 Panduan Instalasi & Menjalankan

Pilih salah satu metode instalasi di bawah ini sesuai kebutuhan Anda:

---

### Metode 1: Menggunakan Installer Windows (Rekomendasi untuk Pengguna)

Cara termudah dan tercepat untuk langsung menggunakan aplikasi tanpa perlu menginstal Python.

1. **Unduh Installer**:
   - Tersedia di folder lokal `Aplication/Torsion-Manager-Setup-1.0.0.exe` atau buka halaman [Releases](https://github.com/) pada repository ini.
   - Unduh/gunakan file installer: `Torsion-Manager-Setup-1.0.0.exe`.

2. **Jalankan Installer**:
   - Klik ganda pada file `Torsion-Manager-Setup-1.0.0.exe`.
   - Jika muncul peringatan _Windows SmartScreen_, klik **More info** lalu pilih **Run anyway**.
   - Ikuti petunjuk wizard instalasi pada layar hingga selesai.

3. **Jalankan Aplikasi**:
   - Buka aplikasi melalui shortcut **Torsion Manager** di Desktop atau melalui menu **Start**.

_(Tersedia juga versi **Portable** dalam folder zip: cukup ekstrak folder dan jalankan `Torsion-Manager.exe`)._

---

### Metode 2: Menjalankan dari Source Code (Developer / Pengguna Lanjut)

Gunakan metode ini jika Anda ingin menjalankan aplikasi dari kode sumber atau berkontribusi pada pengembangan.

#### Langkah 1: Pasang Python

Pastikan Python versi **3.10**, **3.11**, atau **3.12** sudah terpasang di komputer Anda.

> ⚠️ **PENTING**: Saat menginstal Python di Windows, pastikan untuk mencentang opsi **"Add python.exe to PATH"**.

#### Langkah 2: Unduh / Clone Repository

Buka Terminal atau PowerShell, lalu jalankan:

```powershell
git clone https://github.com/username/torsion-manager.git
cd torsion-manager/pxn_v10_desktop
```

_(Atau unduh file ZIP dari repository dan ekstrak ke direktori yang Anda inginkan)._

#### Langkah 3: Siapkan Virtual Environment (Opsional tetapi Disarankan)

Membuat lingkungan virtual Python agar dependensi tidak tercampur dengan paket global:

```powershell
python -m venv venv
.\venv\Scripts\activate
```

#### Langkah 4: Install Dependensi

Pasang semua paket yang dibutuhkan:

```powershell
python -m pip install --upgrade pip
pip install -r requirements.txt
```

#### Langkah 5: Jalankan Aplikasi

- **Opsi A — Menggunakan file batch (Termudah)**:
  Cukup klik ganda pada file `run.bat` di dalam folder proyek, atau jalankan melalui terminal:

  ```powershell
  .\run.bat
  ```

- **Opsi B — Menjalankan via Python langsung**:

  ```powershell
  python run.py
  ```

- **Opsi C — Menjalankan Mode Simulator (Tanpa Setir Fisik)**:
  Jika Anda tidak memiliki setir fisik yang terhubung dan ingin mencoba fitur antarmuka aplikasi:
  ```powershell
  python run.py --simulator
  ```

---

## 🎮 Cara Menghubungkan Setir ke Aplikasi

1. **Nyalakan Setir**:
   - Hubungkan kabel daya dan kabel USB setir PXN V10 atau V99 ke PC.
   - Pastikan setir sudah dalam kondisi menyala (LED indikator menyala).

2. **Pastikan Bluetooth PC Aktif**:
   - Buka **Settings** Windows > **Bluetooth & devices** > pastikan Bluetooth dalam status **On**.

3. **Koneksi di Torsion Manager**:
   - Buka aplikasi **Torsion Manager**.
   - Aplikasi akan otomatis memindai setir terdekat melalui Bluetooth LE.
   - Klik tombol **Sambungkan** pada kartu perangkat yang terdeteksi.
   - Setelah tersambung, lampu status akan berubah hijau dan Anda siap melakukan konfigurasi!

---

## 🛠️ Pemecahan Masalah (Troubleshooting)

| Masalah                                                         | Solusi                                                                                                                                                        |
| --------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `'python' is not recognized as an internal or external command` | Python belum masuk ke Environment Variables Windows. Buka installer Python, pilih **Modify**, dan centang **Add Python to PATH**, lalu restart terminal Anda. |
| **Setir tidak terdeteksi saat pemindaian BLE**                  | Pastikan Bluetooth PC menyala, setir dalam kondisi menyala, dan setir tidak sedang terhubung secara aktif dengan aplikasi di smartphone.                      |
| **Error `bleak` atau izin Bluetooth**                           | Pada Windows 10/11, pastikan izin aplikasi untuk mengakses Bluetooth diaktifkan di **Settings > Privacy & security > Other devices / Radios**.                |

---

## 📄 Lisensi

Didistribusikan di bawah lisensi GNU General Public License v3 (GPL-3.0). Lihat file [LICENSE](LICENSE) untuk informasi lebih lanjut.
