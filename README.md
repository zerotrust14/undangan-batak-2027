# Undangan Pernikahan Lamhot & Riris

Undangan digital satu halaman bertema Batak heritage, responsif untuk ponsel dan laptop.
Situs ini dibuat sebagai situs statis dan dipublikasikan melalui GitHub Pages.

## Konten

- Cover cinematic **LAMRIS INVITATION** (balikkan klik / selipkan).
- Mempelai, cerita singkat, video kenangan, galeri simetris 3×4 beranimasi, event+countdown,
  gift, musik latar, dan form ucapan.
- Pemberkatan: Sabtu, 1 Mei 2027, 09.00–11.00 WIB, GKP Kadipaten.
- Pesta adat: Sabtu, 1 Mei 2027, 12.00–18.00 WIB, Aula GKP Cideres.

## Fitur

- **Background**: folder `Background/` digunakan untuk sampul cinematic (`asset-1.jpg`),
  latar Mempelai (`asset-2.jpg`), latar Cerita (`asset-3.jpg`).
- **Backsound**: `Backsound/Jun_Munthe_-_Pinillit_Ni_Tondi.mp3` (Jun Munthe) sebagai musik
  latar, dikendalikan melalui tombol **♫** yang selalu terlihat di pojok kanan bawah.
- **Galeri**: 10 momen dalam grid simetris 3×3 (setara 3×4), zoom + hover animation, lightbox.
- **Ucapan**: tersimpan di `localStorage` per perangkat pengunjung (belum dikirim ke pasangan).
- Tanggal lahir & zodiak profil: **14 April 1997 · Aries** (Lamhot) · **25 Februari 1995 · Pisces** (Riris).

## Privasi dan publikasi

Repositori dan situs ini bersifat publik. Detail nomor rekening, foto, dan video tampil pada
halaman yang dapat diakses siapa saja yang memiliki URL. Pastikan pasangan menyetujui informasi
dan media tersebut sebelum menyebarkan link.

## Mendapatkan akses dari siapa saja (domain)

Situs statis ini bisa diakses dari siapa saja yang memiliki URL publik (GitHub Pages).

### Publikasi pakai GitHub Pages (auto via repo ini)

1. Repo ini berisi `index.html`, `Foto/`, `Video/`, `Background/`, `Backsound/`.
   (Folder `Foto/`, `Video/`, `Background/`, `Backsound/` biasanya tidak tercover `.gitignore`.
   Periksa: `.gitignore` hanya mengabaikan `Video/Video Romantis.mp4`.)
2. GitHub Pages → Settings → Pages → Build and deployment:
   - Source: **Deploy from a branch** → branch `main`.
   - Build output: **(empty)** (jangan centang `Enforce HTTPS` jika belum punya domain kustom).
3. URL publik otomatis: **https://zerotrust14.github.io/undangan-batak-2027/**
   (bergantikan `<owner>.github.io/<repo>` sesuai nama repo Anda).
4. Aktifkan **Enforce HTTPS** bila domain kustom sudah dipasang (recommended).

### Ubah domain buatan publish nanti

- Ganti baris berikut di `README.md` / situs sesuai domain yang dipakai:
  - `https://zerotrust14.github.io/undangan-batak-2027/`
- Fitur `<base href>` tidak wajib untuk GitHub Pages (jalur relatif berfungsi).

## Menjalankan lokal

```sh
python3 -m http.server 8765
```

Buka `http://localhost:8765`.

## Daftar isi file

- `index.html` — situs utama (cover flip, galeri, musik latar, ucapan).
- `Foto/` — foto profil + 10 momen.
- `Video/video-romantis-mobile.mp4` — video romantis (H.264, 720p).
- `Background/asset-1.jpg` — cover cinematic (5000×3571)
- `Background/asset-2.jpg` — latar Mempelai (736×1380)
- `Background/asset-3.jpg` — latar Cerita (600×900)
- `Backsound/Jun_Munthe_-_Pinillit_Ni_Tondi.mp3` — backsound latar (Jun Munthe)
- `README.md` — dokumen ini.
