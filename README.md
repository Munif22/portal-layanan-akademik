# Bukti Pengujian Browser DevTools

Simpan hasil screenshot pengujian pada folder ini. Contoh nama berkas:

- `01-desktop-1280.png` — tampilan halaman pada viewport 1280 px.
- `02-tablet-768.png` — tampilan halaman pada viewport 768 px.
- `03-mobile-360.png` — tampilan halaman pada viewport 360 px.
- `04-elements.png` — panel Elements yang memperlihatkan struktur HTML semantik.
- `05-network.png` — panel Network setelah halaman di-reload.
- `06-form-validation.png` — validasi browser ketika kolom wajib dikosongkan atau email tidak valid.
- `07-keyboard-focus.png` — indikator fokus saat navigasi menggunakan tombol Tab.

## Langkah pengujian

1. Buka `index.html` di browser.
2. Tekan `F12` atau `Ctrl + Shift + I` untuk membuka DevTools.
3. Aktifkan Device Toolbar (`Ctrl + Shift + M`) dan uji lebar 360, 768, dan 1280 px.
4. Pada setiap ukuran, periksa apakah ada scroll horizontal, teks terpotong, atau kontrol yang terlalu sempit.
5. Di panel Elements, periksa landmark, heading, label form, dan aturan CSS aktif.
6. Di panel Network, aktifkan pencatatan bila perlu lalu reload halaman. Pastikan `index.html` dan `css/styles.css` berhasil dimuat; catat jika ada resource gagal.
7. Coba kirim form dengan kolom wajib kosong dan email yang tidak valid. Pastikan browser menampilkan validasi.
8. Gunakan tombol `Tab` dan `Shift + Tab` untuk memeriksa urutan navigasi serta indikator fokus.
9. Jika tersedia, gunakan Accessibility/Inspector untuk memeriksa nama aksesibel dan struktur heading.

## Template catatan hasil

| Pemeriksaan | Hasil aktual | Catatan/perbaikan |
|---|---|---|
| Viewport 360 px | Isi setelah diuji | Isi setelah diuji |
| Viewport 768 px | Isi setelah diuji | Isi setelah diuji |
| Viewport 1280 px | Isi setelah diuji | Isi setelah diuji |
| Elements/Inspector | Isi setelah diuji | Isi setelah diuji |
| Network | Isi setelah diuji | Isi setelah diuji |
| Validasi form | Isi setelah diuji | Isi setelah diuji |
| Keyboard/focus | Isi setelah diuji | Isi setelah diuji |
| Accessibility Inspector | Isi setelah diuji | Isi setelah diuji |

Catatan: isi hasil berdasarkan pengujian nyata dan tambahkan screenshot sendiri.
