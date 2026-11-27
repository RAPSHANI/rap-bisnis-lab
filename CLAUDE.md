# rap-bisnis-lab — instruksi untuk Claude

Repo ini tempat RAP menguji ide bisnis sebelum mengeluarkan modal, memakai 11 skill `founder-*` di `.claude/skills/` (dari github.com/Jakeschincariol/founder-skill, MIT).

## Bahasa dan gaya
- Selalu balas dan tulis dokumen dalam bahasa Indonesia, kecuali istilah teknis.
- Kesimpulan dulu, lalu alasan. Sebutkan tingkat keyakinan (tinggi/sedang/rendah) pada penilaian kunci. Kritik dulu, pujian hanya jika ada alasannya.

## Satu folder per bisnis
Semua skill menulis ke `founder/`. Di repo ini, ganti `founder/` dengan `<nama-bisnis>/founder/`. Folder dibuat saat skill pertama kali dijalankan untuk bisnis itu.
- Kalau bisnisnya belum jelas dari percakapan, tanyakan dulu sebelum menulis file.
- Bisnis baru = folder baru dengan nama huruf kecil dan tanda hubung.
- Saat menjalankan skrip, berikan path lengkap, misalnya `python3 .claude/skills/founder-plan/compile.py --dir nama-bisnis/founder`.

## Konteks lokal (wajib dipakai, karena skill aslinya berasumsi pasar AS)
- Mata uang Rupiah. Semua angka di `numbers.json` dalam Rupiah utuh, tanpa desimal. Skrip CFO dan plan sudah diubah agar menampilkan `Rp` (set `FOUNDER_CURRENCY=USD` untuk format asli).
- Pasar default: Jawa Tengah (Dieng/Wonosobo, Batang), wisatawan domestik, terutama dari Jabodetabek, Jogja, Semarang, Solo, Jawa Timur. Sesuaikan jika bisnisnya berbeda.
- Kanal yang relevan: Instagram, TikTok, Meta Ads, WhatsApp untuk closing, Google Maps, OTA (Traveloka, Tiket.com) untuk akomodasi, GoFood/GrabFood/ShopeeFood untuk F&B, marketplace (Shopee, Tokopedia, TikTok Shop) untuk produk.
- Perizinan: sebutkan yang perlu dicek (NIB/OSS, PIRT atau BPOM, sertifikat halal, izin usaha pariwisata, pajak daerah/PB1), lalu arahkan untuk dikonfirmasi ke dinas atau konsultan. Jangan menyatakannya sebagai kepastian hukum.
- Persona panel konsumen: pakai daya beli, kebiasaan, dan keberatan pasar Indonesia (sensitif harga, jarak dan akses jalan, cuaca, musim libur, ulasan Google/TikTok).

## Cara membaca hasil
- Panel konsumen adalah simulasi LLM yang cenderung setuju. Buy rate = batas atas, bukan perkiraan. Pakai panel untuk menemukan keberatan dan bahasa pembeli.
- Angka yang belum dikonfirmasi pemasok ditandai sebagai estimasi.
- Utamakan perlindungan dari kerugian dan unit economics yang jelas: tonjolkan skenario terburuk, break-even, dan kas yang dibutuhkan.

## Menyimpan hasil
Sesi cloud (Claude Code web) bisa hilang kalau lama tidak aktif. Setelah setiap skill selesai, commit hasil di folder bisnis itu dan push, dengan pesan seperti `nama-bisnis: founder-cfo`.
