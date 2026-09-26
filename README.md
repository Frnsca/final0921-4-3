# Catatan Keuangan Pribadi

Aplikasi PWA catatan keuangan pribadi yang dirancang untuk Android dan iPhone dan dapat berjalan 100% offline setelah file aplikasi pertama kali dibuka/dipasang.

## Fitur
- 2 bahasa: Bahasa Indonesia dan 繁體中文
- 3 mata uang: IDR, MYR, NTD
- Satu tombol untuk sembunyikan/tampilkan saldo
- Tambah, edit, hapus akun, kategori, dan transaksi
- Jenis akun: Bank, E-Wallet, Cash
- Transfer antar akun
- Tabungan terpisah dari saldo utama
- Mode terang dan gelap
- Tampilan mobile dengan kartu akun yang dapat digeser horizontal
- Ikon aplikasi lucu panda memegang koin
- Penyimpanan data lokal dengan `localStorage`
- Service Worker untuk cache offline/PWA
- Tidak memakai server, database online, atau API eksternal

## Upload ke GitHub
Upload **semua file yang ada di root ZIP** ke repository GitHub Pages. Jangan masukkan folder pembungkus tambahan.

Setelah GitHub Pages aktif, buka alamat Pages repository di Android/iPhone. Browser akan menyimpan cache aplikasi dan data ke perangkat. Untuk penggunaan seperti aplikasi, pilih **Add to Home Screen / Tambahkan ke Layar Utama**.

## Catatan data
Semua data transaksi, akun, kategori, dan tabungan disimpan lokal pada perangkat/browser. Menghapus data situs/browser dapat menghapus data aplikasi.

- Ikon emoji untuk kategori pemasukan dan pengeluaran
- Seluruh label antarmuka dan kategori dilokalkan ke Bahasa Indonesia / 繁體中文
- Nominal awal 0 dapat langsung diganti dengan mengetik angka baru.
