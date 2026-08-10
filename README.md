# Hasna Minatul Mardiah — Portfolio

Portfolio personal one-page dengan desain editorial/minimal modern.

## Struktur
- `index.html` — halaman utama
- `assets/css/style.css` — styling
- `assets/js/script.js` — mobile menu
- `assets/images/` — tempat menaruh foto dan screenshot project

## Cara menambahkan gambar project
Masukkan gambar ke `assets/images/`, lalu ubah elemen:
`<div class="image-placeholder">PROJECT IMAGE</div>`

menjadi:
`<img src="assets/images/nama-file.png" alt="Nama Project">`

Tambahkan CSS jika diperlukan:
`.project-image img{width:100%;height:100%;object-fit:cover;display:block}`

## Catatan
Konten project sudah disusun berdasarkan data yang diberikan. Nomor project dirapikan menjadi 01–09.
Link GitHub/LinkedIn/website dapat diubah langsung di `index.html`.

## Cara menambahkan gambar sertifikat
Semua slot sertifikat sudah tersedia di:
`assets/images/certificates/`

Gunakan nama file berikut agar gambar langsung muncul tanpa mengubah HTML:
- `certificate-01.jpg` sampai `certificate-21.jpg`

Jadi cukup masukkan/rename gambar sertifikat sesuai nomor. Jika sebuah file belum ada, card otomatis menampilkan placeholder `ADD CERTIFICATE IMAGE`.

## Identitas penyelenggara
Setiap card sudah memiliki label penyelenggara (Dicoding, Cisco, DBS Foundation, Oracle, The British Institute, dan MySkill). Bagian pengalaman KAI juga sudah dilengkapi area logo perusahaan.

## Project Images
Masukkan screenshot project ke `assets/images/projects/` dengan nama `project-01.jpg` sampai `project-08.jpg`. Jika belum ada, placeholder akan muncul otomatis. Project yang memiliki link tetap bisa dibuka melalui tombol di masing-masing card.

### Screenshot project dari link
Beberapa project yang memiliki link publik sudah menggunakan screenshot remote otomatis dari halaman project/Google Play atau file screenshot repository. Jika ingin menjadikannya file lokal, simpan screenshot tersebut ke `assets/images/projects/` dengan nama `project-01.jpg`, `project-03.jpg`, `project-07.jpg`, dan `project-08.jpg`; gambar lokal akan menjadi pilihan yang lebih stabil untuk deployment.
