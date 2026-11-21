# Prompt Aset — Petualangan Dunia Huruf (gaya kartun 3D)

Cara pakai: di ChatGPT, **kirim dulu blok "STYLE GLOBAL"**, lalu kirim prompt aset satu per satu di percakapan yang sama supaya gayanya konsisten. Maskot dan Boni dibuat paling awal; pakai hasilnya sebagai gambar referensi untuk aset lain ("pakai gaya dan palet yang sama dengan gambar sebelumnya").

---

## STYLE GLOBAL (kirim pertama)

```
Kamu akan membuat seri aset game edukasi anak SD kelas 1 (usia 6-8 tahun) berjudul "Petualangan Dunia Huruf". Pakai gaya yang SAMA untuk semua gambar:
- Render 3D kartun bergaya film animasi modern: bentuk bulat dan empuk (soft, chubby), material seperti plastik/kain lembut, pencahayaan studio hangat dengan soft shadow dan rim light, kulit dan permukaan halus, mata besar ekspresif berkilau, kedalaman dan volume jelas. TANPA outline hitam, bukan gaya flat 2D, bukan realistis.
- Palet: biru langit (#6EC6FF), kuning matahari (#FFD447), hijau mint (#7BE0B8), oranye (#FF9F43), ungu pastel (#B9A3FF), pink (#FF7FB0). Cerah tapi tidak menyilaukan.
- Tanpa teks, tanpa huruf, tanpa watermark, tanpa logo, tanpa tanda tangan, kecuali kalau diminta.
- Tidak menakutkan, tidak ada objek tajam atau gelap.
Balas "siap" dulu, lalu tunggu prompt aset berikutnya.
```

---

## A. KARAKTER (folder `characters/`)

### 1. `character-guide.png` — Maskot pemandu (dibuat PERTAMA)
```
Buat karakter maskot: anak laki-laki kelas 1 SD yang ceria dan menggemaskan, kepala besar proporsional chibi, rambut cokelat tua pendek dengan jepit rambut bintang kuning di sisi kanan, kulit sawo cerah, pipi merah muda, mata besar bulat berkilau, senyum lebar terbuka. Kaos oranye, celana biru, sepatu biru tua. Berdiri tegak menghadap depan, tangan kanan melambai di samping kepala, tangan kiri di samping badan. Seluruh badan terlihat dari kepala sampai sepatu. Latar belakang transparan (PNG). Rasio vertikal 3:4. Gaya 3D sesuai style global.
```
Lanjutan (opsional, untuk variasi): `Buat karakter yang sama persis dengan pose: (a) melompat gembira kedua tangan terangkat, (b) sedikit sedih kepala menunduk, (c) menunjuk ke kanan. Latar transparan.` Simpan sebagai `character-guide-cheer.png`, `-sad.png`, `-point.png` kalau mau dipakai nanti.

### 2. `character-boni.png` — Boni
```
Buat karakter anak laki-laki kelas 1 SD bernama Boni, gaya sama dengan maskot sebelumnya tetapi wajah dan pakaian berbeda: rambut hitam pendek rapi, kaos biru, celana pendek abu-abu, tersenyum ramah, melambaikan satu tangan. Seluruh badan terlihat. Latar transparan (PNG), rasio 2:3.
```

---

## B. BACKGROUND (folder `backgrounds/`, rasio 16:9)

Aturan komposisi untuk SEMUA background (tambahkan di akhir tiap prompt):
```
Komposisi: area tengah dan sepertiga bawah dibiarkan relatif kosong dan tenang (tempat kartu huruf dan tombol), dekorasi utama di sisi kiri, kanan, dan garis horizon bawah. Bagian atas hanya langit lembut. Tanpa teks. Rasio 16:9 landscape, resolusi tinggi.
```

### 3. `bg-main-world.png` — Splash, Menu, Hasil
```
Dunia fantasi pendidikan yang cerah: langit biru muda dengan awan putih bulat, matahari kuning di kanan atas, pelangi besar di kiri, bukit hijau bergelombang di depan, pulau-pulau kecil melayang di kejauhan, beberapa bintang kecil bersinar. Suasana petualangan yang ceria.
```
### 4. `bg-alphabet-garden.png` — Level 1 Taman Alfabet
```
Taman bunga yang indah: hamparan rumput hijau, bunga warna-warni (merah, kuning, pink, ungu) dengan kelopak bulat, kupu-kupu, pagar kayu pendek putih, jalan setapak berbatu, langit biru muda-hijau muda. Beberapa balok kayu berhuruf TIDAK boleh ada.
```
### 5. `bg-letter-castle.png` — Level 2 Kastil Huruf
```
Kastil dongeng ungu pastel dengan menara kerucut pink dan bendera kuning, berada jauh di kanan, di atas bukit hijau-lavender. Langit gradasi ungu pastel ke pink muda, awan lembut, bintang kecil. Suasana magis tapi ramah anak.
```
### 6. `bg-sound-forest.png` — Level 3 Hutan Bunyi
```
Hutan ceria dengan pohon-pohon bulat hijau cerah di kiri dan kanan, daun besar, jamur kecil lucu, kupu-kupu, burung kecil di dahan, sinar matahari menembus daun. Tambahkan aksen gelombang suara lembut (garis lengkung biru muda) melayang di antara pohon sebagai simbol bunyi. Tengah kosong.
```
### 7. `bg-syllable-bridge.png` — Level 4 Jembatan Suku Kata
```
Sungai biru jernih dengan jembatan kayu melengkung di latar tengah-bawah, pantai berpasir kuning di kedua tepi, langit biru dengan awan, beberapa batu datar di air. Suasana siang yang tenang dan ceria.
```
### 8. `bg-word-city.png` — Level 5 Kota Kata
```
Kota kecil yang ramah anak: deretan gedung dan rumah warna-warni (oranye, kuning, biru, pink, ungu) dengan jendela putih dan atap lucu, pohon bulat kecil, jalan lebar di depan, langit senja hangat oranye-biru muda. Tanpa papan nama dan tanpa teks.
```

---

## C. IKON PULAU MENU (folder `icons/`, PNG transparan, rasio 3:2)

Tambahkan di akhir tiap prompt: `Pulau melayang tunggal dilihat dari samping-atas, dasar tanah cokelat membulat, permukaan rumput hijau, latar transparan, tanpa teks.`

### 9. `icon-island-garden.png`
```
Pulau mungil dengan tiga bunga besar warna merah, kuning, dan pink, dan sebuah papan kayu kecil KOSONG (tanpa huruf).
```
### 10. `icon-island-castle.png`
```
Pulau mungil dengan kastil ungu pastel kecil bermenara tiga beratap pink dan pintu melengkung.
```
### 11. `icon-island-forest.png`
```
Pulau mungil dengan tiga pohon bulat hijau dan dua garis gelombang suara biru muda melayang di atasnya.
```
### 12. `icon-island-bridge.png`
```
Dua pulau kecil yang dihubungkan jembatan kayu melengkung, ada air biru di bawah.
```
### 13. `icon-island-city.png`
```
Pulau mungil dengan tiga bangunan warna-warni (oranye, biru, kuning) bergaris jendela putih.
```

---

## D. OBJEK KATA (folder `objects/`, PNG transparan, persegi 1:1)

Tambahkan di akhir tiap prompt: `Satu objek saja di tengah, tampak jelas dan sederhana untuk anak kelas 1 SD, bayangan lembut tipis di bawah, latar transparan (PNG), tanpa teks, rasio 1:1.`

### 14. `object-ball.png` — BOLA
```
Bola plastik pantai warna-warni dengan segmen merah, kuning, putih, dan biru, ada highlight mengilap.
```
### 15. `object-stone.png` — BATU
```
Sebuah batu abu-abu bulat bergerigi halus, dengan beberapa bintik gelap kecil dan highlight lembut di atas.
```
### 16. `object-blue-color.png` — BIRU
```
Tetesan cat biru cerah besar di atas genangan cat biru kecil, mengilap. Kesan "warna biru" yang jelas.
```
### 17. `object-hat.png` — TOPI (pengecoh)
```
Topi bundar oranye dengan pita merah di pangkalnya.
```
### 18. `object-dice.png` — DADU
```
Dadu putih sudut membulat dengan titik biru tua menunjukkan angka lima.
```
### 19. `object-apple.png` — APEL
```
Apel merah mengilap dengan tangkai cokelat dan satu daun hijau.
```
### 20. `object-table.png` — MEJA
```
Meja kayu persegi panjang sederhana dengan empat kaki, dilihat dari depan.
```
### 21. `object-fish.png` — IKAN
```
Ikan oranye lucu dengan mata besar, sirip ekor, dan senyum kecil, menghadap kiri.
```
### 22. `object-lamp.png` — LAMPU
```
Bola lampu pijar menyala kuning hangat dengan dudukan abu-abu, ada kilau kecil di sekelilingnya.
```

---

## E. EFEK & HURUF (folder `effects/`, `letters/`)

### 23. `effect-star.png`
```
Satu bintang kuning emas lima sudut bersudut membulat empuk seperti permen dengan highlight putih lembut, latar transparan, rasio 1:1.
```
### 24. `letter-card-frame.png` (opsional, folder `letters/`)
```
Bingkai kartu huruf kosong: persegi membulat putih krem dengan tepi biru muda tipis dan bayangan lembut di bawah, bagian tengah polos kosong, tanpa huruf, latar transparan, rasio 5:6.
```

---

## Tips hasil gambar
- Gaya 3D: kalau hasil terlalu realistis atau terlalu gelap, tambahkan "lebih cerah, lebih bulat, lebih kartun"; kalau muncul outline hitam, minta "tanpa outline".
- Placeholder di game saat ini masih 2D datar; begitu gambar 3D dipasang, semuanya otomatis diganti.
- Jika latar tidak benar-benar transparan, minta: "Ulangi dengan latar transparan sungguhan (PNG alpha), bukan kotak-kotak." atau hapus latar lewat Canva/remove.bg.
- Ukuran dari ChatGPT biasanya 1024-1536 px; itu cukup. Untuk background 16:9, kalau hasilnya 3:2, crop atau minta "perluas ke rasio 16:9".
- Cek tiap objek tidak mengandung teks/huruf tak sengaja.
- Simpan sesuai nama file persis, lalu ubah `IMAGE_MODE` jadi `true` di index.html.

---

# MUSIK & SUARA (Gemini)

Catatan: **versi game sekarang belum memutar musik latar** (hanya efek suara buatan kode). Setelah musiknya jadi, aku bisa pasang pemutar loop yang mengikuti tombol suara. Siapkan file `audio/bgm-main.mp3` (dan opsional yang lain).

### M1. `bgm-main.mp3` — Musik latar utama (satu lagu untuk semua layar)
```
Buat musik latar instrumental untuk game edukasi anak SD kelas 1, bisa diulang mulus (seamless loop), durasi sekitar 90 detik, tempo 100 BPM, tangga nada mayor. Suasana ceria, hangat, penuh petualangan, tidak ramai. Instrumen: ukulele petik, glockenspiel, marimba, xylophone, bass lembut, perkusi ringan (shaker, tepukan tangan). Melodi sederhana mudah diingat. Tanpa vokal, tanpa lirik, tidak menyentak, volume dinamis rendah supaya anak tetap fokus mendengar suara pelafalan huruf.
```
### M2. `bgm-menu.mp3` (opsional, jika ingin musik menu berbeda)
```
Instrumen pendek 60 detik, seamless loop, 90 BPM, ceria dan santai bernuansa pulau tropis: ukulele, marimba, seruling lembut. Tanpa vokal.
```
### M3. `jingle-win.mp3` — Fanfare hasil akhir
```
Fanfare kemenangan pendek 6-8 detik, meriah tapi lembut, bell, glockenspiel, trompet kecil, dan tepukan tangan anak-anak di akhir. Tanpa vokal.
```
### M4–M7 (opsional, mengganti efek suara buatan kode)
- `sfx-correct.mp3`: `Efek suara 1 detik: nada naik riang "ting-ting-ting" dari glockenspiel, menandakan jawaban benar.`
- `sfx-wrong.mp3`: `Efek suara 1 detik: dua nada turun lembut dari marimba "dung-dung", ramah, tidak menakutkan.`
- `sfx-star.mp3`: `Efek suara 0,6 detik: kilau bintang bell tinggi "tring" disertai sparkle.`
- `sfx-click.mp3`: `Efek suara 0,2 detik: klik pop lembut seperti gelembung kecil.`

## Rekaman suara pelafalan (opsional, direkam guru, bukan musik)
Lebih natural daripada suara bawaan perangkat. Simpan di `audio/`, daftarkan di `AUDIO_FILES`:
- Huruf: `a, be, ce, de, e, ef, ge, ha, i, je, ka, el, em, en, o, pe, ki, er, es, te, u, ve, we, eks, ye, zet`
- Suku kata: `ba, bi, bu, be, bo`
- Kata: `bola, biru, boni, batu`
- Pengecoh (opsional): `topi, dadu, apel, meja, ikan, lampu`
