# Google Form Auto-Fill Random Script

Sebuah script Python menggunakan Selenium untuk mengisi otomatis Google Form dengan pilihan jawaban **random** untuk semua tipe pertanyaan (pilihan tunggal, pilihan ganda, skala, teks, dan textarea), sekaligus dapat menavigasi antar halaman form (klik tombol Next/Berikutnya) dan submit form otomatis.

---

## Fitur

- Isi otomatis semua pertanyaan di Google Form dengan jawaban random.
- Mendukung tipe pertanyaan:
  - Radio button (pilihan tunggal)
  - Checkbox (pilihan ganda)
  - Text input (jawaban singkat, email, angka)
  - Textarea (jawaban paragraf)
- Klik tombol **Next / Berikutnya** untuk pindah ke halaman berikutnya.
- Klik tombol **Submit / Kirim** di halaman terakhir untuk mengirim form.
- Dapat digunakan untuk form Google yang memiliki beberapa section (halaman).

---

## Instalasi

1. Pastikan Python 3 sudah terinstall di sistem Anda.
2. Install Selenium dengan perintah:

   ```bash
   pip install selenium
