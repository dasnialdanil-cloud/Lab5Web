# Lab5Web — Praktikum 5: JavaScript Dasar dan Manipulasi HTML

**Mata Kuliah:** Pemrograman Web — Pertemuan 6
**Nama:** _(DANIEL DASNIAL)_  **NIM:** _(312510492)_  **Kelas:** _(I252A)_

## Tujuan Praktikum
1. Memahami sintaks dasar JavaScript dan cara menyisipkan JavaScript pada HTML.
2. Menggunakan variabel, tipe data, operator, percabangan, perulangan, dan function.
3. Menampilkan informasi melalui console, alert, prompt, dan elemen HTML.
4. Memanipulasi konten serta gaya elemen HTML menggunakan JavaScript.
5. Membuat interaksi sederhana pada form dan melakukan validasi input.
6. Mendokumentasikan pekerjaan praktikum beserta hasil pengujiannya.

## Struktur Folder
```
Lab5Web/
├── index.html        # Latihan 1–8
├── script.js
├── kalkulator.html   # Mini Project
├── kalkulator.js
├── eksperimen.html   # Eksperimen mandiri & Tugas H.7
├── eksperimen.js
├── style.css
├── JAWABAN.md        # Jawaban pertanyaan bagian H
└── screenshots/      # Letakkan screenshot di sini
```

## Cara Menjalankan
1. Ekstrak folder, buka dengan Visual Studio Code.
2. Buka `index.html` di browser (klik dua kali atau ekstensi Live Server).
3. Buka Console: klik kanan → Inspect/Periksa → Console.

## Langkah Kerja dan Hasil
| Latihan | Deskripsi | Cara Uji | Screenshot |
|---|---|---|---|
| 1 | Output ke halaman & Console | Buka halaman; teks menjadi "Hello World" dan Console menampilkan pesan yang sama. Output halaman tampil bagi pengguna, Console untuk developer. | `screenshots/latihan1.png` |
| 2 | Alert & prompt | Isi nama → sapaan; Cancel/kosong → "Nama belum diisi." | `screenshots/latihan2.png` |
| 3 | Function aritmetika | Klik tombol; hasil `operasiDasar(9, 4)` tampil di halaman dan Console. Pembagian/modulus dengan 0 ditangani. | `screenshots/latihan3.png` |
| 4 | if–else nilai | Uji 75, 59, 60, 101, huruf, kosong, Cancel. | `screenshots/latihan4.png` |
| 5 | switch | Uji 1–5 dan angka lain. | `screenshots/latihan5.png` |
| 6 | Genap/ganjil | Uji positif, negatif, 0, desimal (2.5), kosong. | `screenshots/latihan6.png` |
| 7 | Ubah warna latar | Klik tiga tombol warna. | `screenshots/latihan7.png` |
| 8 | Checkbox menu | Centang/lepas; total berubah otomatis (format `id-ID`). | `screenshots/latihan8.png` |
| Mini Project | Kalkulator nilai | Nilai akhir = 30% tugas + 30% UTS + 40% UAS, validasi 0–100, 4 skenario uji. | `screenshots/miniproject.png` |
| Eksperimen 1–6 | Lihat `eksperimen.html` | — | `screenshots/eksperimen.png` |

### Hasil Skenario Mini Project
| Tugas | UTS | UAS | Nilai Akhir | Predikat | Status |
|---|---|---|---|---|---|
| 85 | 78 | 88 | 84.10 | B | Lulus |
| 60 | 55 | 65 | 60.50 | C | Lulus |
| 40 | 30 | 45 | 39.00 | E | Belum lulus |
| 120 | 80 | 90 | — | — | Ditolak (di luar 0–100) |

## Pertanyaan dan Tugas
Lihat [JAWABAN.md](JAWABAN.md).

## Pengumpulan
1. Buat repository `Lab5Web` di GitHub.
2. `git init && git add . && git commit -m "Praktikum 5 JavaScript"`
3. `git remote add origin <URL>` lalu `git push -u origin main`
4. Kirim URL repository melalui e-learning/ecampus.
