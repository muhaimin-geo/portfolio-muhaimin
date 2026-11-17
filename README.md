# Portofolio Muhaimin

Website portofolio GIS Analyst dan Surveyor berbahasa Indonesia. Situs statis ini tidak memerlukan framework, proses build, atau dependensi.

## Menjalankan secara lokal

Buka `index.html` di browser.

## Memperbarui konten

- Profil, pengalaman, keahlian, dan ringkasan proyek ada di `index.html`.
- Halaman utama menampilkan tiga proyek dan tiga sertifikat pilihan. Tautan proyek dan sertifikat membuka detail atau halaman koleksinya di tab browser yang sama.
- Seluruh daftar dan detail proyek berada dalam satu file `projects.html`. Memilih proyek menampilkan hanya detail proyek tersebut; “Kembali ke semua proyek” membuka daftar lengkap.
- Kartu dan halaman detail proyek menggunakan ilustrasi peta skematis di folder `assets` (bukan peta hasil proyek). Untuk menampilkan hasil proyek asli, ganti `src` pada elemen `<img class="project-map-image">` di `index.html` dan `projects.html`, lalu sesuaikan teks `alt` dengan isi gambar.

- Bagian sertifikat menampilkan gambar JPG di folder `assets`. Gambar sertifikat ditampilkan utuh dan dapat diklik untuk membuka ukuran penuh. Ubah judul dan keterangan di kartu `<article class="certificate-card">` pada `index.html` dan `certificates.html`.

- Detail Proyek Tambora menautkan ke WebGIS langsung.
- Logo dan ikon tab browser menggunakan ilustrasi bumi bergaris koordinat, selaras dengan bidang geodesi.
- Sesuaikan warna, ilustrasi, dan tata letak di `styles.css`.
- Interaksi menu navigasi dan tahun footer ada di `script.js`.

## Menerbitkan dengan GitHub Pages

Repository diterbitkan melalui GitHub Pages dari branch `main` dan folder `/(root)`. Situs tersedia di:

`https://muhaimin-geo.github.io/portfolio-muhaimin/`
