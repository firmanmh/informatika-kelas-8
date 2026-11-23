Berikut adalah kode lengkap untuk file **`README.md`** dan **`SECURITY.md`** yang siap Anda salin dan tempelkan ke repositori GitHub proyek pembelajaran Informatika Kelas VIII Anda.

---

### 1. File `README.md`

Buat file baru bernama `README.md` di repositori GitHub Anda, lalu tempelkan kode Markdown berikut:

```markdown
# 📘 Modul Visual & Latihan Interaktif — Informatika SMP Kelas VIII

Situs web pembelajaran mandiri berbasis HTML, CSS, dan JavaScript murni (*Vanilla JS*) dengan ilustrasi grafis SVG bergerak serta latihan soal interaktif untuk siswa **Kelas VIII SMP**.

---

## 🎯 Cakupan Materi Pembelajaran

### 1. Bab 1: Aplikasi Pengolah Kata & Manajemen Clipboard
* **Jenis Aplikasi Pengolah Kata:** Perbandingan visual aplikasi berbasis *Desktop (Offline)* vs *Cloud (Online)*.
* **Antarmuka Utama Interaktif:** Simulasi bagian-bagian jendela pengolah kata (*Quick Access Toolbar, Title Bar, Ribbon, Ruler, Workspace, Status Bar*) dengan penanda klik interaktif.
* **Alur Kerja & Pintasan Keyboard:** Animasi alur pengetikan dokumen hingga penyimpanan serta daftar tombol perintah esensial (`Ctrl+N`, `Ctrl+S`, `Ctrl+Z`, `Ctrl+Y`, `Ctrl+H`, `Ctrl+B/I/U`).
* **Simulasi Bergerak Clipboard:** Visualisasi perpindahan blok data pada perintah **Copy (`Ctrl+C`)**, **Cut (`Ctrl+X`)**, dan **Paste (`Ctrl+V`)**.

### 2. Bab 2: Manajemen File, Folder & Ekstensi Berkas
* **Struktur Direktori Lintas Platform:** Simulasi *File Explorer* untuk **Laptop (Windows)**, **Smartphone (Android/iOS)**, dan **Cloud Storage (Google Drive)** lengkap dengan fitur pembuatan folder baru secara interaktif.
* **Klasifikasi Ekstensi File:** Pengelompokan ekstensi berkas (*Dokumen, Gambar, Audio, Video, Arsip/Kompresi, Aplikasi/Sistem*) beserta aplikasi pembukanya.

### 3. Bab 3: Sistem Komputer & Alur Operasi CPU (*Machine Cycle*)
* **Trilogi Sistem Komputer:** Diagram interaksi antara **Hardware**, **Software**, dan **Brainware**.
* **Klasifikasi Lengkap Perangkat Keras:** Eksplorator filter 25 perangkat keras berdasarkan kategori (*Input, Process, Output, Storage Device*) beserta perbandingan RAM vs ROM, HDD vs SSD, dan Scanner vs Printer.
* **Animasi Siklus Operasi CPU:** Simulasi langkah demi langkah proses **Fetch $\rightarrow$ Decode $\rightarrow$ Execute $\rightarrow$ Store** antara *Control Unit (CU)*, *ALU*, dan *RAM*.

---

## 📂 Struktur Repositori

```text
├── index.html      # Halaman utama modul visual, simulasi SVG, dan kuis interaktif
├── README.md       # Dokumentasi dan panduan penggunaan repositori
└── SECURITY.md     # Kebijakan keamanan dan pelaporan kerentanan proyek

```

---

## 🚀 Cara Menjalankan & Publikasi ke GitHub Pages

1. **Unggah File:** Pastikan file `index.html`, `README.md`, dan `SECURITY.md` sudah berada di cabang utama (`main`) repositori GitHub Anda.
2. **Aktifkan GitHub Pages:**
* Buka tab **Settings** pada repositori GitHub Anda.
* Pilih menu **Pages** di bilah sisi kiri.
* Pada bagian **Build and deployment** $\rightarrow$ **Source**, pilih **Deploy from a branch**.
* Pada bagian **Branch**, pilih `main` dan folder `/ (root)`, lalu klik **Save**.


3. **Akses Situs:** Tunggu 1–2 menit hingga tautan situs muncul di bagian atas halaman *Pages* (format: `https://<username>.github.io/<nama-repositori>/`).

---

## 🛠️ Teknologi yang Digunakan

* **HTML5 & CSS3:** Tata letak responsif (*Mobile-First*) dengan palet warna *Teal-Amber* yang nyaman dibaca siswa.
* **Inline SVG & CSS Keyframes:** Ilustrasi vektor dan animasi bergerak tanpa ketergantungan gambar eksternal.
* **JavaScript (Vanilla JS):** Simulasi interaktif UI, eksplorator folder, filter perangkat keras, animasi siklus CPU, serta bank soal latihan mandiri per bab.

---

## 📄 Lisensi & Penggunaan Pendidikan

Materi dan kode sumber ini bebas digunakan, dimodifikasi, dan dibagikan oleh guru maupun siswa untuk keperluan kegiatan belajar mengajar non-komersial.

```

---

### 2. File `SECURITY.md`
Buat file baru bernama `SECURITY.md` di repositori GitHub Anda, lalu tempelkan kode Markdown berikut:

```markdown
# Kebijakan Keamanan (Security Policy)

## 🛡️ Ruang Lingkup Keamanan Proyek
Proyek **Modul Visual & Latihan Interaktif Informatika Kelas VIII** merupakan situs web statis edukatif (*client-side only*) yang dibangun sepenuhnya menggunakan HTML, CSS, dan JavaScript tanpa basis data (*database*), autentikasi pengguna, maupun penyimpanan data pribadi siswa di server.

### Fitur Keamanan Bawaan
* **Tanpa Pelacakan & Pengumpulan Data Pribadi:** Situs ini tidak mengumpulkan, menyimpan, atau mengirimkan nama, nilai, maupun identitas siswa ke pihak ketiga mana pun.
* **Bebas Dependensi Eksternal:** Seluruh ilustrasi grafis menggunakan SVG internal dan skrip berjalan secara lokal di peramban (*browser*) siswa sehingga meminimalkan risiko serangan rantai pasok (*supply-chain attack*) atau skrip eksternal berbahaya.
* **Kompatibel HTTPS:** Dirancang untuk dijalankan melalui protokol aman HTTPS bawaan GitHub Pages.

---

## 📌 Versi yang Didukung

| Versi / Cabang | Status Dukungan | Keterangan |
| :--- | :--- | :--- |
| `main` (Terbaru) | ✅ Didukung | Mendapatkan pembaruan materi, perbaikan bug, dan keamanan |
| Cabang lama / Fork | ❌ Tidak Didukung | Tidak dikelola secara resmi oleh pemilik repositori |

---

## 🐞 Melaporkan Celah Keamanan atau Bug
Apabila Anda menemukan celah keamanan (seperti potensi *Cross-Site Scripting / XSS* pada pembaruan kode), tautan rusak, atau kesalahan teknis pada simulasi pembelajaran:

1. **Jangan** mempublikasikan detail eksploitasi secara terbuka di kolom komentar umum sebelum diperbaiki.
2. Silakan buka tab **Issues** pada repositori ini dengan label **`bug`** atau **`security`**, atau hubungi pengelola repositori secara langsung melalui profil GitHub pemilik proyek.
3. Sertakan deskripsi singkat mengenai bagian kode atau halaman yang terdampak beserta langkah reproduksinya agar dapat segera ditindaklanjuti.

```
