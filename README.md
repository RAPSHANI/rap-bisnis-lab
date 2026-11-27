# rap-bisnis-lab

Lab RAP untuk menguji ide bisnis sebelum mengeluarkan modal. Repo ini berisi 11 skill `founder-*` di `.claude/skills/`, instruksi konteks lokal Indonesia di `CLAUDE.md`, dan (nanti) satu folder per bisnis.

## Sumber dan lisensi
Skill berasal dari [Jakeschincariol/founder-skill](https://github.com/Jakeschincariol/founder-skill), lisensi MIT (lihat `.claude/skills/LICENSE-founder-skill`). Perubahan lokal: format uang di `founder-cfo/unit_economics.py` dan `founder-plan/compile.py` menjadi Rupiah. Set `FOUNDER_CURRENCY=USD` untuk format dolar asli.

## Urutan skill
`founder-board` → `founder-competitors` → `founder-consumer` → `founder-pricing` → `founder-offer` → `founder-cfo` → `founder-marketing` → `founder-brand` → `founder-ops` → `founder-launch` → `founder-plan`

## Tips
- Untuk ide yang masih kasar, jalankan `/founder-consumer --quick` dulu supaya murah dan cepat menangkap keberatan pembeli.
- Panel konsumen adalah simulasi LLM; buy rate adalah batas atas, bukan perkiraan penjualan.

## Catatan plugin
Jika plugin founder-skill juga terpasang, di repo ini yang dipakai adalah `/founder-board` (versi Rupiah), bukan `/founder-skill:founder-board`.
