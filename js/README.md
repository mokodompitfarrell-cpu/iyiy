# WebGIS Jumlah Penduduk Surabaya - MapLibre

Project sederhana untuk belajar membangun WebGIS dari nol menggunakan VS Code, MapLibre GL JS, HTML, CSS, JavaScript, dan GeoJSON.

## Struktur Folder

```text
webgis-surabaya/
├── index.html
├── css/
│   └── style.css
├── js/
│   └── app.js
└── data/
    └── jumlah_penduduk_surabaya.geojson
```

## Cara Menjalankan Lokal

1. Buka folder project di VS Code.
2. Install extension **Live Server**.
3. Klik kanan `index.html`.
4. Pilih **Open with Live Server**.

## Deploy ke GitHub Pages

1. Buat repository baru di GitHub.
2. Jalankan perintah:
   ```bash
   git init
   git add .
   git commit -m "Initial WebGIS Surabaya"
   git branch -M main
   git remote add origin https://github.com/USERNAME/NAMA-REPO.git
   git push -u origin main
   ```
3. Di GitHub, buka **Settings > Pages**.
4. Pada **Build and deployment**, pilih:
   - Source: Deploy from a branch
   - Branch: main
   - Folder: /root
5. Tunggu beberapa menit sampai link publik aktif.
