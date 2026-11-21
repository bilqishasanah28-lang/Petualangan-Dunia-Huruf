# Petualangan Dunia Huruf

**Kenali Huruf, Rangkai Suku Kata, Temukan Kata!**
Gim edukasi interaktif Bahasa Indonesia Fase A (Kelas I SD), berdasarkan Buku Siswa "Aku Bisa!" Kelas I (Edisi Revisi 2023), Bab 1 "Bunyi Apa?", hlm. 8–12.

- 5 pulau (level): Taman Alfabet, Kastil Huruf, Hutan Bunyi, Jembatan Suku Kata, Kota Kata
- Pulau terbuka berurutan; bintang dan kemajuan tersimpan di perangkat (localStorage)
- HTML5/CSS3/JavaScript murni, tanpa instalasi dan tanpa server khusus
- Layar 16:9, untuk papan interaktif, laptop, tablet, dan HP (mode mendatar). Mendukung sentuhan, mouse, dan papan ketik

## Cara pasang di GitHub Pages
1. Buat repositori baru di GitHub (mis. `petualangan-dunia-huruf`), pilih **Public**.
2. Unggah **semua isi folder ini** (bukan foldernya): `index.html`, folder `assets/`, `docs/`, `README.md`, dan `.nojekyll`.
   Pastikan `index.html` berada di akar repositori.
3. Buka **Settings → Pages**. Pada *Build and deployment* pilih **Deploy from a branch**, branch `main`, folder `/ (root)`, lalu **Save**.
4. Tunggu 1–3 menit. Alamatnya: `https://NAMA-AKUN.github.io/NAMA-REPO/`.

Catatan: nama file dan folder bersifat huruf besar-kecil (case sensitive) di GitHub. Jangan mengubah nama file di `assets/`.

## Struktur
```
index.html            game (semua kode)
assets/
  backgrounds/        latar tiap pulau dan peta
  characters/         maskot dan Boni
  icons/              ikon pulau
  objects/            gambar benda (bola, batu, dst.)
  effects/            bintang
  developer/          foto pengembang (tab Info Gim)
  audio/              musik latar dan efek jawaban benar/salah
  audio/huruf/        (opsional) rekaman suara huruf a.mp3 … z.mp3
docs/                 prompt pembuatan aset visual dan musik
```

## Mengubah isi
Buka `index.html` dengan editor teks, lalu cari:
- `const INFO = {…}` — nama pengembang, sekolah, tahun, versi, foto (tab Pengembang)
- `const LSPK = {…}` — ejaan suara tiap huruf bila suara perangkat kurang tepat
- `const LETTER_AUDIO = false` — ubah ke `true` setelah file rekaman huruf (`assets/audio/huruf/a.mp3` dst.) tersedia
- `const HAVE = new Set([…])` — daftar aset gambar yang dipakai. Tambahkan kunci baru bila menambah gambar

## Catatan
- Suara pembaca memakai fitur suara bawaan perangkat (bahasa Indonesia). Hasilnya dapat berbeda antar perangkat. Rekaman sendiri paling akurat.
- Font Fredoka/Andika dimuat dari Google Fonts bila ada internet. Tanpa internet, game memakai font bawaan perangkat.
- Pastikan lisensi musik latar dan efek suara di `assets/audio/` sesuai dengan cara kamu membagikan gim ini.
