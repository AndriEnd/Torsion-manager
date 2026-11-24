# Torsion Manager

> **Aplikasi desktop modern untuk konfigurasi, tuning, dan optimasi Force Feedback (FFB) setir balap PXN V10 & PXN V99 di Windows.**

---

## 📋 Persyaratan Sistem

Sebelum memulai instalasi, pastikan sistem Anda memenuhi persyaratan berikut:

- **Sistem Operasi**: Windows 10 atau Windows 11 (64-bit)
- **Konektivitas**: Bluetooth Adapter yang mendukung Bluetooth Low Energy (BLE 4.0 atau lebih baru)
- **Perangkat yang Didukung**:
  - PXN V10
  - PXN V99

---

## 🚀 Panduan Instalasi & Menjalankan

Pilih salah satu metode instalasi di bawah ini sesuai kebutuhan Anda:

---

### Metode 1: Menggunakan Installer Windows (Rekomendasi untuk Pengguna)

Cara termudah dan tercepat untuk langsung menggunakan aplikasi tanpa perlu menginstal Python.

1. **Unduh Installer**:
   - Buka halaman [Releases](https://github.com/) pada repository ini.
   - Unduh file installer versi terbaru: `Torsion-Manager-Setup-1.0.0.exe`.

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

Hak cipta dilindungi undang-undang. Didistribusikan untuk komunitas sim racing dan pengguna setir balap PXN.
