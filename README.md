# Undangan Digital Adat Batak

Undangan satu halaman responsif untuk ponsel dan laptop. Dibuat sebagai situs statis tanpa database.

## Cara melihat lokal

Buka `index.html` di browser, atau jalankan:

```sh
python3 -m http.server 8765
```

Lalu buka `http://localhost:8765`.

## Sebelum dibagikan

`index.html` saat ini masih berisi penanda yang perlu diganti:

- Nama kedua mempelai dan nama orang tua.
- Foto profil serta 10 foto galeri.
- Jam acara pemberkatan dan pesta adat.
- Informasi bank/e-wallet bila ingin dicantumkan.
- Audio berlisensi/yang dimiliki keluarga, diletakkan di `assets/musik-batak-romantis.mp3`.

Cari teks bertanda `[ ... ]`, `Nama Wanita`, `Nama Pria`, dan `Tambahkan foto` di `index.html`. Untuk foto, ganti elemen placeholder dengan tag `<img src="assets/nama-foto.jpg" alt="...">` dan simpan berkas foto dalam folder `assets/`.

Ucapan pada versi ini tersimpan di penyimpanan browser pengunjung masing-masing, bukan terkumpul untuk pasangan. Untuk RSVP/ucapan bersama semua tamu, hubungkan formulir ke layanan backend seperti Google Sheets/Form atau database sebelum digunakan sebagai undangan final.

## Tanggal dan lokasi

- Sabtu, 1 Mei 2027
- Pemberkatan: GKP Kadipaten
- Pesta adat: Aula GKP Cideres
- Tautan navigasi membuka pencarian lokasi di Google Maps.

## Publikasi

Situs statis ini dapat dipublikasikan melalui GitHub Pages atau hosting statis lain. Pastikan semua nama, foto, waktu, informasi hadiah, dan audio sudah final sebelum membagikan URL kepada tamu.
