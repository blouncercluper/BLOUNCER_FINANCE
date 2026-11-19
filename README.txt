BLOUNCER FINANCE — VERSI AWAL 0.1

CARA MENJALANKAN DI LAPTOP
1. Ekstrak file ZIP ini ke sebuah folder.
2. Cara paling mudah: pasang Visual Studio Code dan ekstensi Live Server.
3. Buka folder blouncer_finance di VS Code.
4. Klik kanan index.html > Open with Live Server.
5. Aplikasi akan terbuka di browser.

CARA MEMBUKA DI HP
Agar PWA dapat dipasang dan service worker/offline bekerja, aplikasi perlu disajikan melalui HTTPS atau localhost.
Untuk uji coba lokal, gunakan server pengembangan di laptop dan akses dari HP pada jaringan Wi-Fi yang sama; untuk penggunaan praktis lintas perangkat, unggah folder ini ke layanan hosting statis gratis yang mendukung HTTPS (misalnya GitHub Pages). Tidak perlu membeli domain atau paket hosting berbayar.
Setelah dibuka di Chrome Android, pilih menu browser > Tambahkan ke layar utama / Install app.

PENTING TENTANG DATA
- Data disimpan di IndexedDB browser/perangkat.
- HP dan laptop mempunyai database terpisah; tidak ada sinkronisasi otomatis.
- Gunakan menu Pengaturan & Backup > Ekspor backup untuk menyimpan salinan.
- Di perangkat lain, buka aplikasi lalu Impor backup.
- Jangan menghapus data situs/browser sebelum backup.
- Versi awal ini belum memiliki modul anggaran, stok, dan laporan bisnis terperinci.

FITUR YANG SUDAH BERFUNGSI
- Pemisahan ruang Personal dan Business.
- Tambah dompet berdasarkan ruang aktif.
- Tambah pemasukan/pengeluaran.
- Saldo dompet otomatis berubah.
- Transfer antardompet (tidak dihitung sebagai pemasukan/pengeluaran).
- Dashboard dan daftar transaksi.
- Ekspor/impor backup JSON.

CATATAN
Font online digunakan sebagai peningkatan visual; jika tidak ada internet, browser memakai font cadangan. Fitur inti tetap lokal/offline setelah file aplikasi berhasil dicache.
