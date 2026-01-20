IndoTeks 🇮🇩 - Ultimate Indonesian Typing Test
===============================================

**IndoTeks** adalah aplikasi tes kecepatan mengetik (Typing Test) berbasis web yang dirancang khusus untuk konteks Bahasa Indonesia. Dibangun dengan arsitektur _Single-File_ (HTML, CSS, JS dalam satu dokumen) untuk portabilitas maksimal dan performa tanpa latensi (Zero Latency).

Menggunakan desain **Neo-Brutalism** (Gumroad-style) yang tegas dan minimalis, serta algoritma pengacakan kata cerdas untuk latihan mengetik 10 jari yang efektif.

Fitur Utama
--------------

### 1\. Core Typing Engine

*   **Zero-Latency Input:** Input diproses 100% di _client-side_ tanpa lag server.
    
*   **Physics-Based Caret:** Animasi kursor yang halus dan responsif mengikuti ketukan.
    
*   **Smart Auto-Scroll:** Mekanisme scroll otomatis yang mulus saat berganti baris.
    
*   **Mobile Compatibility:** Responsif dan dapat dimainkan di perangkat seluler.
    

### 2\. Mode Permainan & Konfigurasi

*   **Mode Time:** Balapan melawan waktu (15, 30, 60, 120 detik).
    
*   **Mode Words:** Target jumlah kata (10, 25, 50, 100 kata).
    
*   **Mode Zen:** Mode ketahanan tanpa batas waktu.
    
*   **Tingkat Kesulitan:**
    
    *   `Easy`: Kosakata sehari-hari frekuensi tinggi.
        
    *   `Standard`: Kata berimbuhan, kalimat formal.
        
    *   `Expert`: Istilah teknis, ilmiah, dan birokrasi kompleks.
        
*   **Modifiers:** Opsi tambahan tanda baca (`@`) dan angka (`#`).
    

### 3\. Analitik Mendalam

*   **Net WPM vs Raw WPM:** Perhitungan kecepatan bersih (menghukum typo) vs kecepatan kasar.
    
*   **Akurasi Presisi:** Persentase ketukan benar.
    
*   **Visual Chart:** Grafik performa WPM detik-demi-detik menggunakan `Chart.js`.
    
*   **Character Breakdown:** Detail karakter Benar/Salah/Ekstra/Terlewat.
    

### 4\. Developer Experience (DX)

*   **Single File Architecture:** Mudah diduplikasi, diedit, dan dijalankan secara offline.
    
*   **No Build Step:** Tidak perlu `npm install` atau bundler. Cukup buka di browser.
    
*   **Tailwind CSS (CDN):** Styling modern tanpa file CSS terpisah.
    

🛠️ Teknologi yang Digunakan
----------------------------

*   **HTML5 Semantic:** Struktur dokumen yang rapi dan SEO-friendly.
    
*   **Tailwind CSS:** Framework utility-first untuk desain responsif dan cepat.
    
*   **Vanilla JavaScript (ES6+):** Logika game, state management, dan DOM manipulation.
    
*   **Chart.js:** Visualisasi data hasil tes.
    
*   **Google Fonts:** Menggunakan font `Inter` dan `Space Mono` untuk keterbacaan kode/teks.
    

⌨️ Shortcuts (Power User)
-------------------------

Tombol

Fungsi

`Tab`

Restart Tes Instan

`Esc`

Berhenti / Lihat Hasil

`Ctrl + Backspace`

Hapus satu kata penuh

Instalasi & Penggunaan
-------------------------

Karena proyek ini menggunakan arsitektur satu file, cara menjalankannya sangat mudah:

### Opsi 1: Download Langsung

1.  Download file `index.html` dari repositori ini.
    
2.  Buka file tersebut menggunakan browser modern (Chrome, Edge, Firefox, Safari).
    

### Opsi 2: Clone Repo

    git clone [https://github.com/username-anda/indoteks.git](https://github.com/username-anda/indoteks.git)
    cd indoteks
    # Buka index.html di browser
    

### Opsi 3: Live Demo

Akses versi live di: [https://username-anda.github.io/indoteks](https://www.google.com/search?q=https://username-anda.github.io/indoteks)

Algoritma & Logika
---------------------

### WPM Calculation

IndoTeks menggunakan rumus standar internasional untuk perhitungan WPM:

    (Jumlah Karakter / 5) / Waktu (menit)
    

_Catatan: Net WPM dikurangi penalti kesalahan ketik untuk merefleksikan kecepatan produktif yang sebenarnya._

### Fisher-Yates Shuffle

Untuk memastikan variasi kata yang tidak repetitif, kami menggunakan algoritma pengacakan Fisher-Yates pada dataset kata sebelum disajikan ke pengguna.

Kontribusi
-------------

Kontribusi sangat diterima! Jika Anda ingin menambahkan dataset kata baru atau memperbaiki bug:

1.  Fork repositori ini.
    
2.  Buat branch fitur baru (`git checkout -b fitur-baru`).
    
3.  Commit perubahan Anda (`git commit -m 'Menambah fitur X'`).
    
4.  Push ke branch (`git push origin fitur-baru`).
    
5.  Buat Pull Request.
    

Lisensi
----------

Proyek ini dilisensikan di bawah [MIT License](https://www.google.com/search?q=LICENSE). Bebas digunakan, dimodifikasi, dan didistribusikan.

<div align="center"> <p>Dibuat dengan ❤️ dan ☕ di Indonesia oleh <b>Nando Rifky</b>.</p> </div>
