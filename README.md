# LAMRIS INVITATION — Undangan Pernikahan Lamhot & Riris

Undangan digital satu halaman, cinematic, responsif di HP & laptop.
Dipublikasikan publik melalui GitHub Pages.

## Links

- **GitHub repo** : https://github.com/zerotrust14/undangan-batak-2027
- **Live (GitHub Pages)** : https://zerotrust14.github.io/undangan-batak-2027/
- **Custom domain (rencana)** : https://our-beloved-story.com/lamris-invitation

## Isi & fitur

- Cover cinematic **LAMRIS INVITATION**, bisa dibalik dengan klik / swipe.
  Nama tamu diisi pada cover lalu dipakai di form ucapan.
- Opening, kutipan, band motif Gorga, Mempelai tanpa tanggal lahir/zodiak,
  Save The Date + countdown + Add to Calendar, Acara + Google Maps,
  Our Journey (timeline 4 momen), Rumah Bolon (heritage), Our Film,
  **Our Gallery (grid simetris 5×2 di desktop, 2×5 di HP, animasi + lightbox)**,
  Wedding Gift (2 rekening BCA + tombol salin), Best Wish + daftar ucapan.
- Backsound: **Jun Munthe — Pinilit Ni Tondi** (`Backsound/*.mp3`), diputar
  lewat tombol ♫ dan otomatis saat tombol Open Invitation ditekan. Tanpa Spotify.
- Background: `Background/asset-1.jpg` (motif Batak), `asset-2.jpg` (Gorga),
  `asset-3.jpg` (Rumah Bolon).

## Publikasi

Repo sudah PUBLIC dan GitHub Pages sudah aktif (branch `main`, root, HTTPS enforced).
Setiap push ke `main` otomatis mengupdate situs.

### Pasang custom domain nanti

1. Beli domain `our-beloved-story.com`, arahkan DNS:
   - `A`  `@` → `185.199.108.153` (juga .109/.110/.111)
   - `CNAME` `www` → `zerotrust14.github.io`
2. Di GitHub: Settings → Pages → Custom domain → `our-beloved-story.com`,
   centang **Enforce HTTPS**.
3. Tambahkan file `CNAME` di root repo berisi `our-beloved-story.com` (GitHub
   biasanya membuatnya otomatis).
4. Supaya alamat `https://our-beloved-story.com/lamris-invitation` bekerja,
   siapkan redirect dari path tersebut ke root situs di panel domain/hosting,
   atau pindahkan seluruh isi situs ke folder `lamris-invitation/` dan set
   Pages source ke folder tersebut.

## Jalankan lokal

```sh
python3 -m http.server 8765
```
Buka `http://localhost:8765`.

## Catatan privasi

Situs publik — siapa pun dengan link dapat melihat foto, video, dan nomor rekening.
Ucapan tersimpan di browser pengunjung (`localStorage`), belum terkumpul ke pasangan.

## Enhancement

Menunggu foto prewed baru untuk diperbarui.
