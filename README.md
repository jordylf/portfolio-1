<div align="center">

# JORDY — Creative Portfolio

**Motion Design · Video Editing · Graphic Design · 3D**

Portofolio kreatif Jordy Lian Ferdinand, juga dikenal sebagai **Ody**.
Kumpulan karya yang memadukan ritme, gerak, dan desain visual dalam pengalaman galeri interaktif.

[Instagram](https://www.instagram.com/jordyy.lf) · [TikTok](https://www.tiktok.com/@prwdences) · [Email](mailto:jordylian92@gmail.com) · [Sociabuzz](https://sociabuzz.com/odysaurus)

</div>

---

## Tentang proyek

Website ini menjadi ruang untuk memperkenalkan diri dan menampilkan karya pilihan saya sebagai graphic designer, motion designer, dan backend developer. Perjalanan kreatif saya dimulai dengan Adobe After Effects pada 2017, dari membuat anime music video hingga mengerjakan motion graphics, intro, dan visual untuk streaming.

Dengan tampilan gelap, tipografi Manrope dan Sora, serta pratinjau video pada kartu koleksi, pengunjung dapat menjelajahi karya dan membuka gambar maupun video langsung dari halaman portofolio.

## Koleksi karya

| Koleksi | Isi |
| --- | --- |
| **Edited Gaming Moments** | Edit gameplay dengan subtitle, meme, momen lucu, dan potongan video yang mengikuti timing komedi. |
| **Motion Graphic** | Animasi tipografi, karya anniversary, dan visual untuk organisasi maupun proyek personal. |
| **Anime / Kpop Edit** | Edit anime dan K-pop dengan sinkronisasi musik, transisi, dan efek visual. |
| **Design** | Poster, banner iklan digital, sampul buku, dan desain media sosial. |
| **3D** | Animasi teks 3D, loop visual, dan eksperimen komposisi adegan. |

## Fitur

- **Layout responsif** untuk desktop, tablet, dan ponsel.
- **Pratinjau video** yang diputar berulang tanpa suara pada kartu koleksi.
- **Halaman detail koleksi** dengan tautan langsung melalui hash URL, seperti `#/works/motion-graphic`.
- **Galeri media interaktif** dengan modal untuk melihat gambar dan memutar video.
- **Media dari berbagai sumber**, termasuk video lokal, YouTube, TikTok, dan Instagram.
- **Navigasi keyboard** pada kartu media menggunakan Enter atau Space.
- **Tautan kontak dan ketentuan komisi** yang tersedia di halaman utama.

## Teknologi

Website dibangun menggunakan **HTML5, CSS3, dan JavaScript murni**, tanpa framework atau proses build. Data koleksi disimpan di `script.js`, sehingga konten dapat diperbarui langsung dari satu tempat.

Font dimuat melalui Google Fonts. Git LFS digunakan untuk menyimpan video `video/roblox lagi.mp4` yang berukuran besar.

## Menjalankan secara lokal

Pastikan Git dan Git LFS tersedia, lalu jalankan:

```bash
git lfs install
git clone https://github.com/jordylf/portfolio-1.git
cd portfolio-1
git lfs pull
```

Buka **`index.html`** di browser modern. Tidak ada dependensi aplikasi yang perlu diinstal.

Jika menggunakan Laragon, letakkan proyek di dalam folder `www` dan buka melalui alamat lokal proyek. Koneksi internet diperlukan untuk memuat Google Fonts dan media dari platform eksternal.

## Struktur proyek

```text
portfolio-1/
├── index.html       # Struktur halaman, profil, dan kontak
├── styles.css       # Tampilan, animasi visual, dan layout responsif
├── script.js        # Data koleksi, navigasi, galeri, dan modal
├── assets/          # Gambar karya desain
├── video/           # Video lokal dan pratinjau koleksi
├── .gitattributes   # Konfigurasi Git LFS
├── .gitignore       # File yang tidak disertakan dalam Git
└── README.md
```

Foto profil disimpan di direktori utama proyek dan digunakan oleh `index.html`.

## Memperbarui konten

Untuk menambahkan karya, ubah array **`works`** di `script.js`. Setiap koleksi memiliki judul, deskripsi, video pratinjau, dan daftar media. Jenis media yang didukung adalah `image`, `video`, `youtube`, `tiktok`, dan `instagram`.

Simpan gambar baru di `assets/` atau video di `video/`, lalu sesuaikan nilai `src` pada data media. Profil, tautan sosial, dan ketentuan komisi dapat diubah di `index.html`; warna dan layout diatur melalui `styles.css`.

## Kontak & penggunaan karya

Untuk pertanyaan, kolaborasi, atau komisi, hubungi **[jordylian92@gmail.com](mailto:jordylian92@gmail.com)** atau **[Instagram @jordyy.lf](https://www.instagram.com/jordyy.lf)**.

Jangan mengklaim karya yang ditampilkan sebagai karya sendiri. Berikan kredit yang sesuai dan hubungi saya untuk membahas penggunaan karya atau kebutuhan komisi. Ketentuan komisi selengkapnya tersedia pada bagian **Term of Service** di website.
