# Preferensi kerja (wajib diikuti di setiap sesi)

## Gaya penjelasan
- Bahasa Indonesia santai, langsung ke inti.
- **Setiap kode yang dibuat wajib dijelaskan**: apa fungsi tiap bagian, dan langkah demi langkah cara membuatnya sendiri.
- Selalu tunjukkan **cara mendapatkan bahan** yang dipakai, lengkap dengan link:
  - Font → Google Fonts (https://fonts.google.com): cara memilih, menyalin `<link>`, dan memakainya di CSS.
  - Gambar/lukisan → Wikimedia Commons (https://commons.wikimedia.org), utamakan yang domain publik; jelaskan cara mengunduh ukuran besar.
  - Alat → VS Code (https://code.visualstudio.com) + ekstensi Live Server.
- Kalau ada latar "lukisan hidup" (seperti website Van Gogh): jelaskan cara kerja WebGL/shader-nya dan cara mengganti foto/lukisannya sendiri.

## Gaya kode
- Struktur file terpisah dan rapi: `index.html`, `style.css`, `script.js` (+ folder `gambar/`).
- Setiap bagian diberi **label** yang mudah dicari:
  - HTML `<!-- [H1] ... -->`, CSS `/* [C1] ... */`, JS `// [J1] ...` (file tambahan pakai huruf sendiri, mis. `[L1]`).
  - File besar diberi kotak judul di baris paling atas (FILE, JUDUL, ISI, UBAH DI SINI KALAU).
- Kode dibuat **cukup pendek supaya bisa diketik sendiri**; hindari pustaka yang tidak perlu.
- Sertakan tabel "Mau ubah apa? → label/file mana" di akhir penjelasan.
- Selalu beri tahu cara menjalankan: VS Code → klik kanan `index.html` → Open with Live Server.
