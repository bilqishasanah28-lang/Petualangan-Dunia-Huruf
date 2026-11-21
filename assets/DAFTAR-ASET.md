# Daftar Aset — Petualangan Dunia Huruf

Sudah terpasang: maskot, Boni, 6 background, 5 ikon pulau, 9 objek (bola, batu, biru, topi, dadu, apel, meja, ikan, lampu), dan bintang. Semua gambar utama sudah lengkap. File cadangan belum dipakai: icons/ui-card-frame.webp (bingkai kartu). Setelah menambah file baru, daftarkan kuncinya di `HAVE` pada index.html.

Game berjalan tanpa file ini (memakai ilustrasi SVG sementara).
Untuk memakai gambar sendiri: simpan file di folder yang sesuai (PNG transparan, kecuali background),
lalu di `index.html` ubah `const IMAGE_MODE = false;` menjadi `true`. Gambar yang belum ada otomatis diganti placeholder.

| File | Folder | Ukuran saran | Dipakai di |
|---|---|---|---|
| character-guide.webp | characters/ | 800×1060 | Maskot pemandu (semua layar) |
| character-boni.webp | characters/ | 600×900 | Gambar kata BONI |
| bg-main-world.webp | backgrounds/ | 1920×1080 | Splash, Menu, Hasil |
| bg-alphabet-garden.webp | backgrounds/ | 1920×1080 | Level 1 |
| bg-letter-castle.webp | backgrounds/ | 1920×1080 | Level 2 |
| bg-sound-forest.webp | backgrounds/ | 1920×1080 | Level 3 |
| bg-syllable-bridge.webp | backgrounds/ | 1920×1080 | Level 4 |
| bg-word-city.webp | backgrounds/ | 1920×1080 | Level 5 |
| icon-island-garden.webp | icons/ | 640×420 | Pulau Level 1 di menu |
| icon-island-castle.webp | icons/ | 640×420 | Pulau Level 2 |
| icon-island-forest.webp | icons/ | 640×420 | Pulau Level 3 |
| icon-island-bridge.webp | icons/ | 640×420 | Pulau Level 4 |
| icon-island-city.webp | icons/ | 640×420 | Pulau Level 5 |
| object-ball.webp | objects/ | 600×600 | BOLA |
| object-stone.webp | objects/ | 600×600 | BATU |
| object-blue-color.webp | objects/ | 600×600 | BIRU |
| object-hat.webp | objects/ | 600×600 | TOPI (pengecoh Level 3) |
| object-dice.webp | objects/ | 600×600 | DADU (pengecoh) |
| object-apple.webp | objects/ | 600×600 | APEL (pengecoh) |
| object-table.webp | objects/ | 600×600 | MEJA (pengecoh) |
| object-fish.webp | objects/ | 600×600 | IKAN (pengecoh) |
| object-lamp.webp | objects/ | 600×600 | LAMPU (pengecoh) |
| effect-star.webp | effects/ | 256×256 | Cadangan (efek bintang saat ini digambar lewat kode) |

Audio opsional (folder audio/): isi `AUDIO_FILES` di index.html, mis. `{'be':'audio/huruf-b.mp3','ba':'audio/suku-ba.mp3','bola':'audio/kata-bola.mp3'}`, lalu `AUDIO_MODE = true`.
Tanpa rekaman, game memakai suara bawaan perangkat bila tersedia.


## Musik latar
| File | Folder | Keterangan |
|---|---|---|
| bgm-main.mp3 | audio/ | "The Playful Path", ±90 detik, diputar berulang. Volume pelan, mengecil saat suara pembaca bicara, mati lewat tombol suara. |
