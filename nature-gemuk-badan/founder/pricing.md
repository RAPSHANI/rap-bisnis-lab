# Harga: Nature Gemuk Badan (27 Nov 2026)

**Kesimpulan: tidak ada harga yang sekaligus diterima pembeli dan menutup biaya iklan Meta.** Panel menerima ±Rp40rb–130rb (titik tanpa resistensi ±Rp40rb, "terlalu mahal" median Rp150–170rb), pesaing menjual botol identik Rp23–52rb, sedangkan CFO butuh **minimal ±Rp189rb per order** agar CPA Rp35–45rb masih untung. Kalau RAP tetap menguji, pakai **Program 30 Hari Rp189rb sebagai satu-satunya tawaran utama**, jangan turunkan harga, dan anggap uji ini sebagai pengukur CPA/RTS, bukan peluncuran. Keyakinan: tinggi bahwa ada jurang harga; sedang untuk angka panel (simulasi, satuan jawaban harga tidak seragam).

## 1. Yang dikatakan pembeli (simulasi)
| | Panel v1 (rencana RAP, 1/2/3 botol) | Panel v2 (Program 30 Hari) |
|---|---:|---:|
| Beli | 0/20 | 0/20 |
| PMC (terlalu murah di bawah ini) | Rp39.833 | Rp39.942 |
| OPP (resistensi paling kecil) | Rp40.263 | Rp40.113 |
| IPP | Rp75.046 | Rp75.475 |
| PME (terlalu mahal di atas ini) | Rp120.350 | Rp130.313 |
| Median "terlalu mahal" | Rp150.000 | Rp170.000 |

Kurva lengkap: `pricing-curve-v1.md`, `pricing-curve.md` (skrip menulis "$", angkanya Rupiah).

**Catatan kualitas data:** sebagian pembeli menjawab harga per botol, sebagian per paket 30 hari (P017 menyebutnya terang-terangan). Jadi PME Rp120–130rb bisa berarti "per botol" atau "per bulan". Dua-duanya tetap di bawah Rp139rb satuan dan Rp189rb paket.

## 2. Yang dikenakan pesaing (botol identik 60 kapsul)
Rp23.000 / Rp25.500 / Rp43.775 / Rp52.000 / Rp95–99.900 (Tokopedia, lihat `competitors.md`). Median ±Rp44–52rb. Harga per botol RAP: Rp139rb (satuan), Rp79,5rb (B1G1), Rp63rb (B2G1). Untuk 30 hari, pembeli Shopee membayar ±Rp70–155rb (3 botol + ongkir); RAP Rp189rb. **Selisih untuk 30 hari: ±Rp35–120rb.** Itu yang harus dibayar oleh pendampingan, COD, dan rasa aman.

## 3. Yang dibutuhkan bisnis (dari CFO, RTS 25%)
| Harga 3 botol | CPA impas | Laba @CPA 35rb | @CPA 45rb |
|---:|---:|---:|---:|
| Rp149.000 | Rp21.672 | −Rp17.770 | −Rp31.103 |
| Rp169.000 | Rp36.222 | Rp1.630 | −Rp11.703 |
| **Rp189.000** | **Rp50.772** | **Rp21.030** | **Rp7.697** |
| Rp299.000 (6 btl) | Rp72.072 | Rp49.430 | Rp36.097 |

Setiap Rp20rb turun harga = CPA impas turun ±Rp15rb. Harga di bawah Rp169rb untuk 3 botol tidak bisa dibayar iklan Meta.

## 4. Keputusan
**Harga: Program 30 Hari (3 botol) Rp189.000.** Bukan karena pembeli menerimanya (mereka tidak), tapi karena di bawah itu tidak ada CPA realistis yang untung. Jika uji membuktikan pembeli menolak Rp189rb, jawabannya **berhenti**, bukan turun harga.

**Tangga (good / better / best):**
| Rung | Harga | Peran | Alasan naik |
|---|---:|---|---|
| Coba 10 Hari (1 botol) | Rp139.000 | hanya ditawarkan di WA kepada yang menolak paket; tidak diiklankan | laba per order tertinggi (Rp41rb @CPA 22,5rb), tapi 10 hari kemungkinan belum terasa → repeat rendah |
| **Program 30 Hari (3 botol + pendampingan)** | **Rp189.000** | default, satu-satunya di iklan | Rp6.300/hari, dosis pas 30 hari |
| Program 60 Hari (6 botol) | Rp299.000 | jangkar + untuk calon pengantin / yang sudah selesai program 1 | satu-satunya paket yang lolos aturan mentor di CPA realistis |

**Hapus B1G1 Rp159rb.** Labanya paling kecil (Rp4,7rb @CPA 45rb), 20 hari tidak sesuai satuan program mana pun, dan membuat pembeli memilih jalan tengah.

## 5. Tawaran pembukaan
Bonus fisik/digital, bukan diskon: pembeli 50 order pertama mendapat check-in WA tambahan di hari ke-28 dan cetakan tracker. Berakhir saat 50 order atau 31 Des 2026, mana yang lebih dulu. Tanpa harga coret, tanpa "harga normal Rp411rb".

## 6. Yang diuji dengan pembeli nyata
Harga tidak perlu di-A/B pada tahap ini; yang diuji adalah **apakah ada orang yang membayar Rp189rb lewat COD dan menerima paketnya.**
- Uji 1 (CPA): satu harga Rp189rb, dua angle iklan (lihat `marketing.md`). Ukur biaya per chat, closing rate WA, CPA, RTS.
- Uji 2 (hanya jika uji 1 lolos): 50% chat ditawari Program 60 Hari Rp299rb lebih dulu. Ukur porsi yang mengambil.

## 7. Keberatan harga dari panel (verbatim, untuk marketing)
1. "Rp139 ribu buat 10 hari itu mahal buat gue, Curcuma di apotek cuma belasan ribu. Paling gue cari nama 'Nature Gemuk Badan' di Shopee dulu." (v1, P004)
2. "Kapsulnya sama dan mereka sendiri bilang ada di marketplace, di sana ada ulasan dan biasanya lebih murah, jadi ngapain beli di toko baru yang belum ada review." (v2, P002)
3. "Gaji saya cuma sekitar 2,5 juta sebulan, Rp189 ribu itu kerasa." (v2, P003)
