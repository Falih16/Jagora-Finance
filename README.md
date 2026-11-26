# Jagora Finance (Versi Flat — Siap Upload GitHub & GitHub Pages)

Folder ini sengaja disusun **tanpa subfolder** agar seluruh file bisa langsung di-drag & drop ke GitHub Web UI dan langsung berjalan di **GitHub Pages** tanpa `npm install` atau proses build.

## Daftar File (Semua di Root)
- `index.html` — Halaman utama aplikasi
- `app.js` — Aplikasi lengkap (Double-Entry Ledger Engine + UI React)
- `styles.css` — Stylesheet Tailwind CSS terkompilasi + DM Sans
- `jagora-logo.png` — Logo Jagora Technologies transparan
- `jagora-demo-backup.json` — File data demo siap impor lewat tombol **Pulihkan**
- `README.md` — Panduan penggunaan & deploy

## Cara Upload ke GitHub (Tanpa Subfolder)
1. Buat repository baru di GitHub (misalnya `jagora-finance`).
2. Klik **uploading an existing file** atau **Add file → Upload files**.
3. Buka folder `jagora-finance-github`, pilih **semua 6 file sekaligus** (`Ctrl+A`), lalu drag & drop ke GitHub.
4. Klik **Commit changes**.

## Cara Mengaktifkan Online Gratis (GitHub Pages)
1. Buka tab **Settings → Pages** di repository GitHub Anda.
2. Pada **Build and deployment → Source**, pilih **Deploy from a branch**.
3. Pilih branch **`main`** dan folder **`/ (root)`**, lalu klik **Save**.
4. Tunggu ±1 menit, aplikasi langsung online dan siap digunakan!

## Penyimpanan Data
- Di GitHub Pages (static hosting), semua data otomatis tersimpan di `localStorage` browser Anda setiap perubahan atau saat menekan **Simpan** / `Ctrl+S`.
- Gunakan tombol **Backup** untuk mengunduh file cadangan `.json` agar aman dipindahkan antar perangkat, dan **Pulihkan** untuk memuatnya kembali (termasuk mencoba `jagora-demo-backup.json`).
