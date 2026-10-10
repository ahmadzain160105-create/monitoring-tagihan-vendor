MONITORING VERIFIKASI BERKAS TAGIHAN VENDOR — VERSI SEDERHANA

CARA MENJALANKAN (TANPA INSTALASI):
1. Ekstrak ZIP ini ke folder yang mudah ditemukan.
2. Buka folder hasil ekstrak.
3. Klik dua kali index.html.
4. Website demo akan terbuka di browser.

Tidak perlu menginstal XAMPP, Laravel, PHP, Composer, atau database.

FITUR:
- Dashboard ringkasan status tagihan.
- Daftar data tagihan vendor.
- Cari vendor/nomor tagihan dan filter status.
- Tambah, edit, dan hapus data tagihan.
- Data disimpan secara lokal di browser yang digunakan.

CATATAN PENTING:
- Ini prototipe/demo dengan data simulasi, bukan sistem resmi PLN.
- Tidak terhubung ke sistem PLN dan tidak mengirim data ke server.
- Data yang diedit hanya tersimpan pada browser/perangkat ini. Jika data situs browser dihapus, data lokal bisa hilang.
- Gunakan data fiktif; jangan memasukkan informasi rahasia atau dokumen asli.

Mengembalikan data awal demo: buka Developer Tools > Console, jalankan:
localStorage.removeItem("demo-monitoring-tagihan-v1");
Lalu refresh halaman.
