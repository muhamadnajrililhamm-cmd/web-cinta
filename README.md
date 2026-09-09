# Savira Birthday Love Experience

Template birthday romantis interaktif, mobile-first, dengan PIN, musik lokal, cinematic intro, amplop, surat, foto URL, GIF, memories, birthday scene, pertanyaan akhir, dan WhatsApp.

## Jalankan
npm install
npm run dev

## Build
npm run build

## Edit cepat
Buka `src/main.jsx`, cari `const CONFIG`.
- `name`: nama penerima
- `senderName`: nama pengirim
- `pin`: PIN
- `whatsapp`: nomor WhatsApp format internasional tanpa +
- `music`: file musik di public/music
- `photos`: ganti URL foto
- `gifs`: ganti URL GIF

## Musik
Masukkan lagu sendiri ke `public/music/our-song.mp3`.
Browser memerlukan interaksi user; musik dimulai setelah PIN benar.

## Catatan
Nomor WhatsApp contoh harus diganti sebelum deploy. URL foto/GIF juga bisa diganti kapan saja dari CONFIG.
