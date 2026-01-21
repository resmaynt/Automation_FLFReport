
# 🚀 FLF Automation System

FLF Automation System adalah aplikasi berbasis **Python + PyQt5** untuk mengotomatisasi
pengolahan data **FLF (Fuel/Lifted Forecast)** dari file Excel dan mengintegrasikannya
ke dalam file **Master / Draft Power BI**.

Aplikasi ini dirancang untuk meminimalkan pekerjaan manual, meningkatkan akurasi,
dan mempercepat proses pembuatan laporan FLF bulanan.

---

## ✨ Fitur Utama

- ✅ Membaca & memproses data FLF dari file Excel
- ✅ Deteksi otomatis header kolom (fleksibel terhadap format)
- ✅ Filter data berdasarkan status (`COMPLETE / COMPLETED`)
- ✅ Normalisasi & mapping nama FLF (Apollo, Zeus, WHS, dll)
- ✅ Otomatis menulis hasil agregasi ke file Master
- ✅ GUI modern berbasis **PyQt5**
- ✅ Dukungan Windows (run.bat) & macOS/Linux

---

## 📁 Struktur Folder

```text
FLF-Automation-System/
│
├── app/                     # Core application logic
│   ├── main_gui_modern.py   # GUI (PyQt5)
│   ├── main_logic.py        # Data processing pipeline
│   ├── config.py            # Konfigurasi (sheet, kolom, opsi)
│   ├── mapping.py           # Normalisasi & mapping FLF
│   └── popup.py             # Dialog konfirmasi
│
├── ui/                      # Qt resources
│   ├── resources.qrc
│   └── resources_rc.py
│
├── Dashboard FLF/            # Dashboard & contoh data
│   ├── Dashboard/
│   └── Excel FLF/
│
├── run.py                   # Entry point aplikasi
├── run.bat                  # Shortcut run (Windows)
├── theme.qss                # Stylesheet (UI theme)
├── requirements.txt         # Python dependencies
├── README.md                # Dokumentasi
└── .gitignore
```
