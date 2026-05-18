# digital-guestbook-sitepak-riau
Sistem Informasi Tamu Elektronik KPU Riau (SITEPAK RIAU) untuk pencatatan, monitoring, dan manajemen kunjungan tamu secara modern dan efisien.

Aplikasi web berbasis frontend (HTML/CSS/JS) yang dirancang untuk digitalisasi pencatatan kehadiran tamu dan survei kepuasan pelayanan di lingkungan kantor **Komisi Pemilihan Umum (KPU) Provinsi Riau**.

Aplikasi ini mengintegrasikan formulir digital dengan fitur dokumentasi foto (selfie/identitas) yang tersimpan otomatis secara real-time.

---

## ✨ Fitur Utama

*   **Registrasi Tamu Digital:** Terintegrasi langsung dengan Google Forms via `iframe` yang aman dan stabil.
*   **Pengambilan Foto & Upload Otomatis:** Fitur untuk mengambil foto selfie menggunakan kamera HP secara langsung (*capture*) atau mengunggah file identitas, yang kemudian otomatis diunggah ke Google Drive melalui Google Apps Script.
*   **Penamaan File Otomatis Berbasis Waktu:** File foto yang diunggah akan dinamai secara otomatis dengan format: `Tamu_DD-MM-YYYY_HH-MM-SS`.
*   **Survei Kepuasan Pelayanan:** Alur aplikasi yang mengarahkan tamu secara otomatis untuk mengisi survei setelah pendaftaran selesai.
*   **Desain Responsif & Elegan:** Menggunakan tema warna resmi KPU (Maroon & Emas) yang dioptimalkan untuk perangkat mobile maupun tablet digital.

---

## 🛠️ Teknologi yang Digunakan

*   **Frontend:** HTML5, CSS3 (Custom Variables & Flexbox), Vanilla JavaScript (ES6+).
*   **Fonts & Icons:** Google Fonts (Poppins), Font Awesome v6.4.0.
*   **Integrasi Pihak Ketiga:** 
    *   Google Forms (Sebagai database input data tamu dan survei).
    *   Google Apps Script (Sebagai backend *serverless* untuk menjembatani upload foto ke Google Drive).
---

## 🚀 Cara Instalasi & Penggunaan

Aplikasi ini bersifat *serverless* pada sisi frontend, sehingga Anda hanya perlu menjalankan file HTML-nya.

1. **Clone Repositori ini:**
   ```bash
   git clone [https://github.com/username-anda/buku-tamu-kpu-riau.git](https://github.com/username-anda/buku-tamu-kpu-riau.git)
