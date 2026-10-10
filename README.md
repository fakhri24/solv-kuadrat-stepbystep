# SuperMath: Step-by-Step Solver & Interactive Trainer Persamaan Kuadrat 📐✨

Media Pembelajaran Interaktif Matematika SMA Fase E (Kurikulum Merdeka) untuk menguasai konsep dan penyelesaian **Persamaan Kuadrat** $ax^2 + bx + c = 0$ secara komprehensif, runtut, dan menyenangkan.

🌐 **Live Demo (GitHub Pages):** [https://fakhri24.github.io/supermath-persamaan-kuadrat/](https://fakhri24.github.io/supermath-persamaan-kuadrat/)

---

## 🎯 Fitur & Keunggulan

### 1. 🧮 Mode Solver (Penjabaran 3 Metode Lengkap)
Menyajikan langkah-langkah aljabar mendalam dengan notasi matematika berstandar LaTeX (**KaTeX**):
- **Metode 1: Pemfaktoran Aljabar**:
  - Algoritma pencarian pasangan faktor $p \cdot q = a \cdot c$ dan $p + q = b$ dilengkapi tabel uji pasangan faktor.
  - Penulisan bentuk $\frac{(ax + p)(ax + q)}{a} = 0$, penyederhanaan kurung, dan penyelesaian akar.
  - *Catatan Edukatif Otomatis*: Mendeteksi saat diskriminan $D < 0$ atau bukan kuadrat sempurna (akar irasional/imajiner) dengan rekomendasi beralih ke Rumus ABC.
- **Metode 2: Melengkapkan Kuadrat Sempurna**:
  - Langkah pembagian kedua ruas dengan $a$ agar koefisien $x^2 = 1$.
  - Pemindahan konstanta $c$ ke ruas kanan.
  - Penambahan kuadrat dari setengah koefisien $x$, yaitu $\left(\frac{b}{2a}\right)^2$, pada kedua ruas.
  - Faktorisasi kuadrat sempurna $\left(x + \frac{b}{2a}\right)^2$ hingga penarikan akar.
- **Metode 3: Rumus Kuadratik / ABC**:
  - Substitusi presisi nilai $a, b, c$ ke dalam rumus $x = \frac{-b \pm \sqrt{b^2 - 4ac}}{2a}$.
  - Evaluasi diskriminan $D = b^2 - 4ac$ dan kategorisasi sifat akar.
  - Penyederhanaan bentuk radikal akar atau konjugat bilangan imajiner $i$.
- **🔊 Audio Narator Edukatif (Web Speech API)**:
  - Narator suara berbahasa Indonesia di setiap metode untuk memandu siswa auditori langkah demi langkah secara alami.
  - Animasi visualizer soundwave saat narasi aktif.

---

### 2. ⚡ Mode Trainer & Kuis Latihan Mandiri
Uji pemahaman dan kecepatan analisis aljabar dengan sistem adaptif 3 tingkat kesulitan:
- **Level 1 (Faktorisasi Mudah, $a=1$)**: Akar-akar bilangan bulat rasional.
- **Level 2 (Koefisien $a > 1$ atau Akar Pecahan)**: Melatih pemfaktoran lanjutan dan pecahan.
- **Level 3 (Soal Tantangan Diskriminan & Teorema Vieta)**: Analisis nilai $D$, $x_1 + x_2$, $x_1 \cdot x_2$, dan sifat-sifat akar.
- **Fitur Kuis Interaktif**:
  - Validasi fleksibel (urutan akar $x_1$ dan $x_2$ bebas tertukar, mendukung pecahan misal `3/2` atau desimal `1.5`).
  - Efek audio feedback sintetis (**Web Audio API**) dan animasi visual.
  - Sistem skor dinamis, bonus streak berturut-turut, dan indikator akurasi.
  - Pembahasan solusi lengkap berformat KaTeX saat siswa membutuhkan bantuan.
  - Log riwayat pengerjaan soal sesi ini.

---

## 🛠️ Spesifikasi Teknis
- **Single-File Architecture (`index.html`)**: HTML5 murni, vanilla JavaScript (ES6+), dan Tailwind CSS CDN.
- **Math Engine**: KaTeX CDN (Fast Math Rendering).
- **Audio & Accessibility**: Web Speech API (`SpeechSynthesis`) & Web Audio API (Synthesizer).
- **Zero Build Tools**: Dapat dijalankan luring (offline) cukup dengan membuka file di peramban, maupun daring melalui GitHub Pages.

---

## 🚀 Menjalankan Secara Lokal
Cukup buka file `index.html` langsung di browser kesayangan Anda:
```bash
open index.html # di macOS
# atau klik ganda index.html di File Explorer
```

Dibuat dengan ❤️ untuk pembelajaran matematika SMA Indonesia yang lebih interaktif dan bermakna.
