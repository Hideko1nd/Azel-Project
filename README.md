# Kantor Mahasiswa · Asisten Serbaguna

Website kantor 3D bergaya game sandbox: 27 asisten AI untuk mahasiswa, upload file,
lantai B2 (ruang server), lantai B3 (ruang developer + Dev Console Rachel),
mode malam dengan UFO, mode jalan (avatar) dan mode bangun.

## Cara membuka di VS Code
1. Buka VS Code → **File → Open Folder…** → pilih folder `kantor-mahasiswa` ini.
2. Pasang ekstensi **Live Server** (VS Code akan menyarankannya otomatis).
3. Klik kanan `index.html` → **Open with Live Server**.

## Penting
- **Fitur AI** (asisten menjawab, Rachel, Kernel Kantor) hanya aktif saat halaman
  dibuka sebagai artifact di claude.ai. Di Live Server, tampilan kantor, mode jalan,
  mode bangun, mode malam, dan B2/B3 tetap jalan, tapi asisten tidak bisa menjawab.
- Di Live Server, file & dunia disimpan di browser (IndexedDB/localStorage).
- Butuh internet untuk font Google dan pembaca file (pdf.js, mammoth, SheetJS, JSZip).

## Mengubah tampilan & perilaku
Semua bagian yang bisa diganti ada di blok **CONTEKAN** paling atas `index.html`.
Tekan **Ctrl+F** lalu cari `GANTI:` untuk melompat ke tiap bagian.
