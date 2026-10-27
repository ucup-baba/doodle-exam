# 📐 Doodle Exam — Ujian Matematika Teorema Pythagoras Kelas VIII

Aplikasi web interaktif untuk asesmen mandiri dan ujian matematika materi **Teorema Pythagoras & Aplikasinya** untuk siswa Kelas VIII SMP/MTs dengan tema visual doodle buku catatan matematika (*notebook style*).

🔗 **Live Website (GitHub Pages):** [https://ucup-baba.github.io/doodle-exam/](https://ucup-baba.github.io/doodle-exam/)

---

## ✨ Fitur Utama

- **🎨 Desain Doodle Notebook Interaktif:** Tampilan kertas bergaris ramah siswa, ornamen geometri dinamis, dan warna pastel yang menarik.
- **⏱️ Timer Ujian 100 Menit & Auto-Save:** Timer real-time yang tahan refresh halaman (*anti-reload reset*) dengan penyimpanan otomatis via LocalStorage.
- **🤲 Doa Sebelum Ujian:** Pop-up doa kelapangan dada dan kemudahan belajar beraksara Arab, transliterasi Latin, dan terjemahan bahasa Indonesia.
- **💡 10 Kutipan Motivasi Terverifikasi:** Menampilkan kutipan semangat belajar dari tokoh-tokoh inspiratif (B.J. Habibie, Ki Hadjar Dewantara, Shakuntala Devi, Einstein, Galileo, dll.) yang berganti di setiap sesi.
- **📊 20 Butir Soal Terstruktur:**
  - **10 Pilihan Ganda** (Nomor 1–10, termasuk 3 soal HOTS)
  - **2 Mencocokkan Pasangan** (Nomor 11–12, 6 pasang konteks & perhitungan)
  - **3 Pilihan Kompleks / Lebih dari Satu** (Nomor 13–15)
  - **5 Soal Esai & Uraian** (Nomor 16–20, mencakup soal beranak & HOTS kontekstual)
- **🖼️ Gambar Pendukung Soal:** Gambar statis (tanpa petunjuk) untuk soal geometri.
- **✍️ Isian Esai Terstruktur & Koreksi Otomatis:** Input jawaban akhir berupa angka atau bentuk akar (√) lengkap dengan pilihan dropdown satuan (m, m², cm, cm², cm³, mm, km, Rp, dll.) yang langsung dikoreksi otomatis oleh sistem.
- **🔒 Panel Guru & Administrasi:** Akses kunci jawaban, rubrik penilaian, indikator kisi-kisi, dan penanda soal HOTS (terproteksi kode akses guru `GURU8`).
- **☁️ Integrasi Google Sheets / Google Apps Script:** Dilengkapi skrip `Code.gs` untuk merekam rekap skor dan jawaban siswa secara langsung ke Google Spreadsheet.

---

## 🚀 Cara Menjalankan Secara Lokal

Cukup buka berkas `index.html` di peramban web modern apa pun (Google Chrome, Firefox, Safari, Microsoft Edge). Tidak memerlukan server backend khusus.

```bash
# Clone repository
git clone https://github.com/ucup-baba/doodle-exam.git

# Masuk ke direktori
cd doodle-exam

# Buka di browser
xdg-open index.html   # Linux
open index.html       # MacOS
start index.html      # Windows
```

---

## 🛠️ Teknologi yang Digunakan

- [Tailwind CSS CDN](https://tailwindcss.com/)
- [Phosphor Icons](https://phosphoricons.com/)
- Google Fonts: *Fredoka*, *Nunito*, *Amiri*
- Vanilla JavaScript (ES6+)
- Google Apps Script (Opsional)
