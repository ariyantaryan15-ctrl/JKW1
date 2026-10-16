BluMeal — versi HTML + CSS + JS (tanpa server)
===============================================
Isi folder:
  index.html  -> struktur halaman (Hari Ini, Menu, Progres, Profil)
  style.css   -> tampilan (tema terang hijau-oranye)
  script.js   -> semua logika + data bahan & resep
  images/     -> foto resep

Cara menjalankan di VS Code:
  1. Ekstrak ZIP, buka foldernya di VS Code (File > Open Folder).
  2. Klik kanan index.html > "Open with Live Server" (extension Live Server),
     atau cukup klik dua kali index.html untuk membuka di browser.

Catatan:
  - Data (profil, bahan, catatan makan, berat) disimpan di localStorage browser.
  - Alasan rekomendasi memakai "rule-based AI" (aturan + perhitungan skor),
    tidak memanggil API AI luar, jadi bisa jalan offline.
  - Font diambil dari Google Fonts (butuh internet); tanpa internet memakai font bawaan.
