# 🔐 EncryptDecrypt - AES-256-GCM

EncryptDecrypt adalah aplikasi enkripsi dan dekripsi file secara instan menggunakan **AES-256-GCM**.  
Dengan fitur **klik kanan**, pengguna dapat mengenkripsi dan mendekripsi file dengan mudah.

## 📌 Fitur
- ✅ Menggunakan **AES-256-GCM** untuk keamanan tinggi  
- ✅ Mendukung semua jenis file, termasuk gambar dan dokumen  
- ✅ Integrasi dengan **Windows Context Menu** untuk akses cepat  
- ✅ Penyimpanan kunci aman dalam **config.json**  

## 🚀 Instalasi
1. **Unduh dan Jalankan Installer**
   - **[Download EncryptDecrypt.exe](https://github.com/YD1RUH/Right-Click-Encrypt/releases/tag/beta-V1.0)**
   - Jalankan **`EncryptDecrypt_Setup.exe`** untuk menginstal aplikasi.

2. **Konfigurasi Password**
   - Setelah instalasi, jalankan **`config.bat`** untuk mengatur password enkripsi pertama kali.

3. **Gunakan Klik Kanan untuk Enkripsi/Dekripsi**
   - Klik kanan pada file yang ingin dienkripsi/dekripsi.
   - Pilih **"Encrypt File"** atau **"Decrypt File"** dari menu.

---

## 📂 Struktur Folder
```plaintext
C:\EncryptDecrypt\
│── EncryptDecrypt.exe       # Aplikasi utama
│── config.bat               # Script untuk setup password
│── config.json              # Menyimpan password terenkripsi
│── unins000.exe             # Uninstaller
└── regedit.reg              # Registri untuk integrasi klik kanan
