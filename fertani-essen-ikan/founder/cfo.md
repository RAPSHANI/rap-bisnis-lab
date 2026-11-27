# Catatan CFO (v2, 27 Nov 2026, setelah data supplier)

**Kesimpulan:** data supplier memperbaiki angka, tetapi belum mengubah gambaran besarnya. Dengan paket 2/3 botol, ongkir rata-rata Rp18.325, dan HPP yang dikembalikan saat retur, setiap order diterima menyisakan **Rp14.310 (9%)** pada CPA Rp45.000 dan RTS 25%. Batas impasnya **CPA Rp55.733 per order masuk**. Turun harga 10% atau biaya naik 15% masih membuat rugi. Keyakinan: tinggi untuk strukturnya, rendah untuk CPA dan RTS (belum ada data nyata).

**Apa yang berubah dari v1:** ongkir lebih murah (Rp18.325 vs estimasi Rp20.000), opsi 1 botol dihapus, dan supplier memastikan HPP kembali saat retur. Margin naik dari 2% ke 9%, sebagian karena target CPA diturunkan ke Rp45.000. Pada CPA Rp50.000 sisa per order masih Rp7.644.

## Laba per order diterima menurut CPA × RTS
| RTS | CPA maks impas | CPA 30rb / 40rb / 45rb / 50rb / 60rb / 75rb |
|---|---|---|
| 15% | Rp68.050 | 44.765 / 33.001 / 27.118 / 21.236 / 9.471 / -8.176 |
| 25% | Rp55.733 | 34.310 / 20.977 / 14.310 / 7.644 / -5.690 / -25.690 |
| 35% | Rp43.415 | 20.639 / 5.254 / -2.438 / -10.131 / -25.515 / -48.592 |

## Uji iklan Rp2.500.000
- Terbaik (CPA Rp35rb, RTS 15%): ~71 order, 61 diterima, laba ~Rp2,36 juta.
- Dasar (CPA Rp45rb, RTS 25%): ~56 order, 42 diterima, laba ~Rp596 ribu.
- **Terburuk (CPA Rp75rb, RTS 35%): ~33 order, 22 diterima, rugi ~Rp1,05 juta**, ditambah Rp0,5 juta kreatif.

## Kas: bayar di depan
Setiap order menahan sekitar **Rp67.218** (HPP Rp48.893 + ongkir Rp18.325) sampai COD cair, dan ini perlu dikonfirmasi apakah ongkir juga dibayar di depan. Kalau 56 order tersebar dalam 3 minggu dan pencairan COD 10–14 hari, uang yang tertahan pada puncaknya sekitar **Rp2–2,5 juta**. Dana retur (HPP) kembali lebih lambat lagi.

## Pembagian modal Rp6.000.000 (revisi)
| Pos | Jumlah |
|---|---|
| Iklan Fase 1 (7 hari, ~Rp170rb/hari) | Rp1.200.000 |
| Iklan Fase 2 (14 hari, hanya jika lulus gerbang) | Rp1.300.000 |
| Talangan HPP + ongkir (bayar di depan) | Rp2.500.000 |
| Produk uji + kreatif | Rp500.000 |
| Cadangan rugi ongkir retur | Rp500.000 |

**Stop-loss:** (1) kreatif mati setelah Rp150rb tanpa order; (2) setelah Rp600rb, CPA > Rp65.000 → stop; (3) Fase 2 hanya jika CPA ≤ Rp45.000 dan RTS ≤ 25% dari ≥20 paket selesai; (4) **batas rugi total Rp1.500.000**.

## Tiga cara memperbaiki margin (dihitung)
1. RTS 25% → 15% (konfirmasi WA, bonus prabayar): CPA maks Rp55.733 → Rp68.050; laba @CPA 45rb Rp14.310 → Rp27.118.
2. CPA 45rb → 35rb: laba per order naik ~Rp13.333 (RTS 25%).
3. Porsi 3 botol 65% → 85%: margin sebelum iklan paket 3 botol ~Rp90.255 vs 2 botol ~Rp79.605, jadi rata-rata naik ~Rp2.130 per order.

**Syarat board soal uang:** budget, stop-loss, ongkir nyata, dan kebijakan retur sudah terpenuhi. Arus kas COD (lama pencairan, apakah ongkir dibayar di depan) belum.

Bukan nasihat keuangan atau pajak. Proyeksi 12 bulan di bawah hanya ilustrasi dari tool.

---

# Unit economics: Fertani Essen Ikan (dropship, Meta Ads ke landing page, COD) - penawaran v2

Every number below comes from the input file. Nothing is looked up or guessed.

## One order diterima pembeli

| line | per order diterima pembeli |
| --- | ---: |
| Price | Rp158.500 |
| HPP rata-rata 2,65 botol x Rp18.450 (mix 35% paket 2 botol / 65% paket 3 botol, ASUMSI mix) | -Rp48.893 |
| Ongkir kirim rata-rata (ESTIMASI tertimbang dari Rp12.000 Jakarta s/d Rp30.000 Bali) | -Rp18.325 |
| Biaya COD 3% (ESTIMASI) | -Rp4.755 |
| Kerugian retur: RTS 25% x ongkir 2 arah Rp36.650 / 0,75 (HPP dikembalikan supplier) | -Rp12.217 |
| Iklan Meta: CPA Rp45.000 per order masuk / 0,75 diterima (ESTIMASI) | -Rp60.000 |
| **Contribution** (what each order diterima pembeli leaves to pay the fixed costs) | **Rp14.310** (9%) |

## The margin that matters

Fixed costs: Rp150.000 a month (Landing page / form builder + domain (ESTIMASI) Rp150.000).

- **Break-even: 1 order diterima pembelis a day.** Below that you lose money every month.
- **Profit margin at your plan** (6 a day): **9%** of every sale, after every cost.

## Year 1, month by month

| month | order diterima pembelis a day | revenue | profit | cumulative (after Rp500.000 startup) |
| ---: | ---: | ---: | ---: | ---: |
| 1 | 2 | Rp9.510.000 | Rp708.600 | Rp208.600 |
| 2 | 3 | Rp14.265.000 | Rp1.137.900 | Rp1.346.500 |
| 3 | 4 | Rp19.020.000 | Rp1.567.200 | Rp2.913.700 |
| 4 | 5 | Rp23.775.000 | Rp1.996.500 | Rp4.910.200 |
| 5 | 6 | Rp28.530.000 | Rp2.425.800 | Rp7.336.000 |
| 6 | 6 | Rp28.530.000 | Rp2.425.800 | Rp9.761.800 |
| 7 | 6 | Rp28.530.000 | Rp2.425.800 | Rp12.187.600 |
| 8 | 6 | Rp28.530.000 | Rp2.425.800 | Rp14.613.400 |
| 9 | 6 | Rp28.530.000 | Rp2.425.800 | Rp17.039.200 |
| 10 | 6 | Rp28.530.000 | Rp2.425.800 | Rp19.465.000 |
| 11 | 6 | Rp28.530.000 | Rp2.425.800 | Rp21.890.800 |
| 12 | 6 | Rp28.530.000 | Rp2.425.800 | Rp24.316.600 |

- **Year 1 operating profit: Rp24.816.600** on Rp294.810.000 of revenue.
- After the Rp500.000 startup spend: Rp24.316.600.
- Startup money earned back: month 1.
- Cash you need before it pays for itself: **Rp500.000**.

## What if

| scenario | margin at plan | break-even a day | year 1 profit |
| --- | ---: | ---: | ---: |
| Base plan | 9% | 1 | Rp24.816.600 |
| Price -10% | -2% | never | -Rp4.664.400 |
| Volume -20% | 8% | 1 | Rp19.493.280 |
| Unit costs +15% | -5% | never | -Rp15.412.410 |

No red flags in these numbers. They are only as good as the inputs: check every cost against a real quote.
