# Undangan Pernikahan Lamhot & Riris

Undangan digital satu halaman bertema Batak heritage, responsif untuk ponsel dan laptop. Dibuat sebagai situs statis dan dipublikasikan melalui GitHub Pages.

## Konten

- Profil Lamhot Parluhutan Tampubolon dan Riris Anastasia Simanungkalit, biodata dan nama orang tua.
- Cerita singkat pasangan.
- Sepuluh foto, dialog galeri, serta video kenangan yang dioptimalkan untuk web.
- Pemberkatan: Sabtu, 1 Mei 2027, 09.00–11.00 WIB, GKP Kadipaten.
- Pesta adat: Sabtu, 1 Mei 2027, 12.00–18.00 WIB, Aula GKP Cideres.
- Hitung mundur menuju pemberkatan, tautan Google Maps, gift BCA, playlist Spotify, dan formulir ucapan.
- Animasi reveal/zoom yang menghormati pengaturan reduced motion.

## Aset

Foto berasal dari folder `Foto/`. Dua foto profil merupakan crop dari foto pasangan yang diberikan. Video web ada di `Video/video-romantis-mobile.mp4` (H.264, 720p); sumber asli yang lebih besar tidak perlu diunggah. Musik menggunakan embed playlist Spotify publik “The Sound of Batak”; pemutaran bergantung pada koneksi internet dan layanan Spotify.

## Ucapan

Form ucapan saat ini menyimpan data di localStorage browser pengunjung masing-masing. Ucapan belum dikirim ke pasangan atau dibagikan antarpengunjung. Untuk mengumpulkan RSVP/ucapan bersama, perlu menambahkan backend seperti Google Sheets/Form atau database.

## Privasi dan publikasi

Repositori dan situs ini bersifat publik. Detail nomor rekening, foto, dan video tampil pada halaman yang dapat diakses siapa saja yang memiliki URL. Pastikan pasangan menyetujui informasi dan media tersebut sebelum menyebarkan link.

## Menjalankan lokal

```sh
python3 -m http.server 8765
```

Buka `http://localhost:8765`.
