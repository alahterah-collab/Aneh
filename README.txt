PROYEK VERCEL - PLAYER DARI HTML SUMBER

Isi:
- index.html: halaman player responsif, memakai URL embed yang ditemukan di HTML sumber.
- vercel.json: konfigurasi header dasar untuk Vercel.

Deploy:
1. Ekstrak ZIP.
2. Upload folder/proyek ke GitHub.
3. Import repository ke Vercel sebagai proyek Static.
4. Framework Preset: Other; Build Command dan Output Directory dikosongkan (atau output directory ".").
5. Deploy.

Batasan:
HTML sumber mencantumkan embed https://www.porngem.com/embed/444482 dan URL MP4 dengan token sementara, tetapi tidak memberikan endpoint API resmi untuk refresh token. Tombol muat ulang hanya meminta ulang URL embed; ia tidak memperbarui token. Jika embed sumber sendiri menjawab "File not found", proyek statis tidak bisa memperbaikinya sendiri tanpa API/embed aktif dari penyedia.
