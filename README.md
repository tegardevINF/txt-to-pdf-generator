# 📄 TXT → PDF Converter

> Konversi file teks `.txt` ke PDF langsung di browser — tanpa server, tanpa install, tanpa ribet.

![HTML](https://img.shields.io/badge/HTML-5-orange?style=flat-square&logo=html5)
![CSS](https://img.shields.io/badge/CSS-3-blue?style=flat-square&logo=css3)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6-yellow?style=flat-square&logo=javascript)
![jsPDF](https://img.shields.io/badge/jsPDF-2.5.1-red?style=flat-square)
![License](https://img.shields.io/badge/license-MIT-green?style=flat-square)

---

## ✨ Fitur

| Fitur | Keterangan |
|---|---|
| 📂 Drag & Drop | Seret file `.txt` langsung ke area upload |
| 📝 Preview & Edit | Lihat dan edit teks sebelum dikonversi |
| ⚙️ Ukuran Kertas | Pilih A4, Letter, atau Legal |
| 📏 Margin | Atur margin 5mm – 40mm via slider |
| 🔤 Ukuran Font | Atur font 8pt – 24pt via slider |
| 🌙 Dark / Light Mode | Toggle tema gelap dan terang |
| 📜 Riwayat Konversi | Tersimpan otomatis di browser (maks. 10 entri) |
| ⚡ Tanpa Backend | Semua proses berjalan 100% di browser |

---

## 🚀 Cara Menjalankan

### Opsi 1 — Buka Langsung (Paling Mudah)

```bash
# 1. Clone repo ini
git clone https://github.com/username/txt-to-pdf-converter.git

# 2. Masuk ke folder
cd txt-to-pdf-converter

# 3. Buka file di browser
# Windows: start txt-to-pdf.html
# macOS:   open txt-to-pdf.html
# Linux:   xdg-open txt-to-pdf.html
```

Atau cukup **double-click** file `txt-to-pdf.html` — langsung jalan di browser!

### Opsi 2 — Download ZIP

1. Klik tombol **Code → Download ZIP** di halaman repo
2. Ekstrak file ZIP
3. Double-click `txt-to-pdf.html`

> **Catatan:** Koneksi internet diperlukan saat pertama kali membuka agar library jsPDF dapat dimuat dari CDN.

---

## 🛠️ Tech Stack

- **HTML5** — Struktur halaman
- **CSS3** — Styling & animasi (tanpa framework)
- **Vanilla JavaScript** — Logika konversi & UI
- **[jsPDF 2.5.1](https://github.com/parallax/jsPDF)** — Generate file PDF di sisi klien
- **Google Fonts** — DM Sans, DM Mono, Syne
- **localStorage** — Penyimpanan riwayat konversi

---

## 📁 Struktur File

```
txt-to-pdf-converter/
└── txt-to-pdf.html     # Seluruh aplikasi dalam satu file
```

Aplikasi ini sengaja dibuat dalam **satu file HTML** agar mudah dibagikan dan dijalankan tanpa konfigurasi apapun.

---

## 📸 Screenshot

| Dark Mode | Light Mode |
|---|---|
| *(tambahkan screenshot di sini)* | *(tambahkan screenshot di sini)* |

---

## 🤝 Kontribusi

Kontribusi sangat diterima! Silakan:

1. Fork repo ini
2. Buat branch baru (`git checkout -b fitur-baru`)
3. Commit perubahan (`git commit -m 'Tambah fitur baru'`)
4. Push ke branch (`git push origin fitur-baru`)
5. Buka Pull Request

---

## 📄 Lisensi

Proyek ini dilisensikan di bawah [MIT License](LICENSE).

---

<p align="center">Dibuat dengan ❤️ menggunakan HTML, CSS & JavaScript murni</p>
