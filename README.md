# Portal Layanan Akademik

Contoh proyek tugas Pertemuan 5 — Responsive & Accessible Web Client.

## Struktur folder

```text
portal_layanan_akademik/
├── index.html
├── css/
│   └── styles.css
├── evidence/
│   └── README.md
└── README.md
```

## Cara menjalankan

1. Ekstrak folder proyek.
2. Buka `index.html` di browser, atau gunakan ekstensi Live Server di Visual Studio Code.
3. Tidak membutuhkan JavaScript, framework, package manager, atau koneksi internet.

## Fitur yang diterapkan

- HTML semantik: `header`, `nav`, `main`, `section`, `article`, `form`, dan `footer`.
- Tiga kartu layanan: Surat Aktif Kuliah, Transkrip Sementara, dan Cuti Akademik.
- Form permohonan dengan nama, email, NIM, jenis layanan, keperluan, konfirmasi, dan validasi HTML.
- CSS mobile-first dengan Flexbox dan Grid.
- Breakpoint tablet dan desktop.
- Skip link, label form yang terhubung, fokus keyboard yang terlihat, kontras teks, dan dukungan reduced motion.
- Tidak memakai gambar eksternal sehingga tidak ada gambar informatif yang membutuhkan atribut `alt`.

## Batasan

Ini adalah antarmuka front-end statis. Form memakai validasi browser, tetapi belum menyimpan atau mengirim data ke server. `action="#"` digunakan sebagai placeholder untuk demonstrasi; integrasi backend diperlukan untuk pemrosesan nyata.

## Pengujian yang perlu dilakukan

Lihat `evidence/README.md` untuk daftar pemeriksaan dan screenshot yang perlu diambil. Jangan mengisi laporan dengan hasil yang belum benar-benar diuji.
