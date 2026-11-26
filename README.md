# Dashboard ODP & Homepass (GitHub Pages + Google Sheets)

Dashboard interaktif visualisasi data ODP dan Homepass jaringan FTTH yang dapat langsung di-hosting di **GitHub Pages** dan tersinkronisasi otomatis dengan **Google Sheets** setiap **1 menit**.

## Cara Menggunakan

1. **Siapkan Google Sheets:**
   - Buka Google Sheets Anda, klik **Bagikan (Share)**, lalu ubah akses umum menjadi **Siapa saja yang memiliki link (Pelihat)**.
2. **Aktifkan GitHub Pages:**
   - Unggah `index.html`, `.nojekyll`, dan `README.md` ke repository GitHub Anda.
   - Masuk ke **Settings** > **Pages** > pilih **Deploy from a branch** (`main` / `root`) lalu klik **Save**.
3. **Hubungkan Google Sheets:**
   - Buka URL website GitHub Pages Anda, tempel link Google Sheets pada kolom yang tersedia, lalu klik **Simpan & hubungkan**.
   - *(Opsional)* Jika ingin link Google Sheets langsung terpasang permanen untuk semua pengunjung, buka `index.html` dan isi baris `const DEFAULT_SHEET_URL = 'LINK_GOOGLE_SHEETS_ANDA';`.
