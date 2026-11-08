# Catatan CFO: Lapak Malam (rencana v3)

> `numbers.json` sekarang berisi **rencana lapak malam** (format yang dipilih founder pada 8 Nov 2026). Rencana ruko lama ada di [cfo-ruko.md](cfo-ruko.md) dan `numbers-ruko.json`. Semua angka dalam Rupiah (`$` di tabel alat = Rp). Ringkasan, skenario, dan opsi Jogja ada di [lapak-malam.md](lapak-malam.md). Banyak input masih **estimasi**, terutama sewa teras, porsi makanan, ramp, dan kapasitas. Ini bukan nasihat keuangan atau pajak; minta akuntan atau KPP mengecek PPh dan PBJT.

## Margin

- **Kontribusi per tamu: Rp14.105 (50%)** dari belanja rata-rata Rp28.000.
- **Break-even: 21 tamu/malam**, dari kapasitas sekitar 37. Rencana 28 tamu/malam, buka 17 malam/bulan.
- **Margin di rencana: +14%.**
- **Tahun 1 (operasional): +Rp3,7 juta.** Laba bulan ke-12 Rp1,9 juta.
- Startup Rp19,1 juta. Alat seduh sudah dimiliki, jadi dihitung Rp0.

## Angka yang paling perlu dijaga

1. **Jumlah tamu.** Tamu −30% membuat tahun 1 rugi Rp14,8 juta.
2. **Belanja per tamu.** Di Rp24.000, break-even naik ke 29 tamu/malam dan usaha hanya impas.

## Kas

**Sekitar Rp24,7 juta** sebelum usaha membiayai dirinya sendiri (rencana dasar). Versi solo sekitar Rp19,5 juta. Dalam skenario buruk (tamu −30%), sekitar Rp33,9 juta.

## Tiga cara memperbaiki margin (dijalankan dengan alat)

| Cara | Break-even/malam | Tahun 1 |
|---|---:|---:|
| Rencana dasar | 21 | +Rp3,7 jt |
| Teras lebih murah (Rp600 rb, bukan Rp1,5 jt) | 17 | +Rp14,5 jt |
| Tanpa helper berbayar (solo; tidak disarankan untuk Jumat–Sabtu) | 12 | +Rp27,3 jt |
| Belanja per tamu Rp32.000 (+Rp4.000, misalnya lewat makanan atau gelas kedua) | 16 | +Rp21,2 jt |

## Syarat board

| Syarat | Status |
|---|---|
| C1 Aplikasi dibekukan | Terpenuhi: kasir pakai Qasir sekitar Rp58 ribu/bulan dan QRIS statis |
| C8 Uji nyata sebelum biaya besar | **Diubah bentuknya:** lapak (sekitar Rp19 juta) adalah ujinya, dengan review 8 minggu pada 2 Feb 2027 sebelum ada keputusan kios atau ruko |
| C11 Yogyakarta ditunda | Dipertahankan. Opsi Jogja dihitung (Lampiran B), dan hasilnya rugi dengan operator berbayar |

---

# Lampiran A: Lapak malam Rawamangun (`numbers.json`), output alat


Every number below comes from the input file. Nothing is looked up or guessed.

## One tamu (rata-rata belanja per kunjungan)

| line | per tamu (rata-rata belanja per kunjungan) |
| --- | ---: |
| Price | $28,000.00 |
| Minuman 1,25 per tamu: campuran 40% V60 (bahan Rp7.050), 45% es kopi susu (Rp7.900), 15% kopi tubruk (Rp3.400) [estimasi campuran] | -$8,610.00 |
| Makanan angkringan: 70% tamu x Rp9.000 x HPP 65% (sebagian titipan, sebagian buat sendiri) [estimasi] | -$4,095.00 |
| Waste 5% bahan minuman [estimasi] | -$430.00 |
| Cup take-away 20% tamu x Rp1.600 | -$320.00 |
| Cicip Dulu + garansi seduh ulang [estimasi] | -$300.00 |
| PPh Final UMKM 0,5% (orang pribadi: Rp500 jt omzet pertama/tahun bebas; dimasukkan agar konservatif) | -$140.00 |
| QRIS statis (MDR 0% untuk transaksi <= Rp100.000) | -$0.00 |
| **Contribution** (what each tamu (rata-rata belanja per kunjungan) leaves to pay the fixed costs) | **$14,105.00** (50%) |

## The margin that matters

Fixed costs: $4,828,250 a month (Sewa/numpang teras ruko atau rumah yang tutup sore (listing Jaktim Rp0,6-2,5 jt/bulan; research/lokasi-rawamangun.md) $1,500,000, Helper Jumat-Sabtu 5 jam (18.00-23.00) x 8,7 malam x Rp45.475/jam (UMP DKI / 126, PP 36/2021) $1,970,000, Gas LPG untuk kettle [estimasi] $250,000, Angkut/titip alat (kalau tidak bisa disimpan di lokasi) [estimasi] $400,000, Iuran kebersihan/warga dengan kuitansi [estimasi] $150,000, Marketing (cetak kartu Ajak Teman, konten) [estimasi] $500,000, Aplikasi kasir Qasir Pro (Rp699 rb/tahun) $58,250).

- **Break-even: 21 tamu (rata-rata belanja per kunjungan)s a day.** Below that you lose money every month.
- **Profit margin at your plan** (28 a day): **14%** of every sale, after every cost.
- Capacity: 37 a day.

## Year 1, month by month

| month | tamu (rata-rata belanja per kunjungan)s a day | revenue | profit | cumulative (after $19,050,000 startup) |
| ---: | ---: | ---: | ---: | ---: |
| 1 | 10 | $4,760,000 | -$2,430,400 | -$21,480,400 |
| 2 | 13 | $6,188,000 | -$1,711,045 | -$23,191,445 |
| 3 | 16 | $7,616,000 | -$991,690 | -$24,183,135 |
| 4 | 18 | $8,568,000 | -$512,120 | -$24,695,255 |
| 5 | 20 | $9,520,000 | -$32,550 | -$24,727,805 |
| 6 | 22 | $10,472,000 | $447,020 | -$24,280,785 |
| 7 | 24 | $11,424,000 | $926,590 | -$23,354,195 |
| 8 | 25 | $11,900,000 | $1,166,375 | -$22,187,820 |
| 9 | 26 | $12,376,000 | $1,406,160 | -$20,781,660 |
| 10 | 27 | $12,852,000 | $1,645,945 | -$19,135,715 |
| 11 | 28 | $13,328,000 | $1,885,730 | -$17,249,985 |
| 12 | 28 | $13,328,000 | $1,885,730 | -$15,364,255 |

- **Year 1 operating profit: $3,685,745** on $122,332,000 of revenue.
- After the $19,050,000 startup spend: -$15,364,255.
- Startup money earned back: not within year 1.
- Cash you need before it pays for itself: **$24,727,805**.

## What if

| scenario | margin at plan | break-even a day | year 1 profit |
| --- | ---: | ---: | ---: |
| Base plan | 14% | 21 | $3,685,745 |
| Price -10% | 5% | 26 | -$8,547,455 |
| Volume -20% | 5% | 21 | -$8,639,204 |
| Unit costs +15% | 7% | 24 | -$5,420,343 |

## Red flags

- The startup spend is not earned back within year 1.

---

# Lampiran B: Opsi Jogja dengan operator (`numbers-jogja.json`), output alat


Every number below comes from the input file. Nothing is looked up or guessed.

## One tamu (rata-rata belanja per kunjungan)

| line | per tamu (rata-rata belanja per kunjungan) |
| --- | ---: |
| Price | $22,000.00 |
| Minuman 1,25 per tamu (bahan sama dengan Jakarta: beans, susu, filter) [estimasi campuran] | -$8,610.00 |
| Makanan angkringan: 70% tamu x Rp7.000 x HPP 65% [estimasi] | -$3,185.00 |
| Waste 5% bahan minuman [estimasi] | -$430.00 |
| Cup take-away 20% tamu x Rp1.600 | -$320.00 |
| Cicip Dulu + garansi seduh ulang [estimasi] | -$300.00 |
| PPh Final UMKM 0,5% (orang pribadi: Rp500 jt omzet pertama/tahun bebas; dimasukkan agar konservatif) | -$110.00 |
| QRIS statis (MDR 0% untuk transaksi <= Rp100.000) | -$0.00 |
| **Contribution** (what each tamu (rata-rata belanja per kunjungan) leaves to pay the fixed costs) | **$9,045.00** (41%) |

## The margin that matters

Fixed costs: $5,198,250 a month (Sewa teras/kios kecil Jogja (listing Rp650 rb-1,3 jt/bulan; research/opsi-jogja.md) $1,000,000, Operator 4 malam x 6 jam x 17 malam x Rp22.441/jam (UMK Kota Yogyakarta 2026 Rp2.827.593 / 126) $2,290,000, Gas LPG [estimasi] $250,000, Angkut/titip alat [estimasi] $300,000, Iuran kebersihan/warga [estimasi] $100,000, Marketing [estimasi] $400,000, Aplikasi kasir Qasir Pro $58,250, Kunjungan founder Jakarta-Jogja 1x/bulan [estimasi] $800,000).

- **Break-even: 34 tamu (rata-rata belanja per kunjungan)s a day.** Below that you lose money every month.
- **Profit margin at your plan** (28 a day): **-9%** of every sale, after every cost.
- Capacity: 37 a day.

## Year 1, month by month

| month | tamu (rata-rata belanja per kunjungan)s a day | revenue | profit | cumulative (after $24,550,000 startup) |
| ---: | ---: | ---: | ---: | ---: |
| 1 | 10 | $3,740,000 | -$3,660,600 | -$28,210,600 |
| 2 | 13 | $4,862,000 | -$3,199,305 | -$31,409,905 |
| 3 | 16 | $5,984,000 | -$2,738,010 | -$34,147,915 |
| 4 | 18 | $6,732,000 | -$2,430,480 | -$36,578,395 |
| 5 | 20 | $7,480,000 | -$2,122,950 | -$38,701,345 |
| 6 | 22 | $8,228,000 | -$1,815,420 | -$40,516,765 |
| 7 | 24 | $8,976,000 | -$1,507,890 | -$42,024,655 |
| 8 | 25 | $9,350,000 | -$1,354,125 | -$43,378,780 |
| 9 | 26 | $9,724,000 | -$1,200,360 | -$44,579,140 |
| 10 | 27 | $10,098,000 | -$1,046,595 | -$45,625,735 |
| 11 | 28 | $10,472,000 | -$892,830 | -$46,518,565 |
| 12 | 28 | $10,472,000 | -$892,830 | -$47,411,395 |

- **Year 1 operating profit: -$22,861,395** on $96,118,000 of revenue.
- After the $24,550,000 startup spend: -$47,411,395.
- Startup money earned back: not within year 1.
- Cash you need before it pays for itself: **$47,411,395**.

## What if

| scenario | margin at plan | break-even a day | year 1 profit |
| --- | ---: | ---: | ---: |
| Base plan | -9% | 34 | -$22,861,395 |
| Price -10% | -21% | 45 | -$32,473,195 |
| Volume -20% | -21% | 34 | -$30,764,916 |
| Unit costs +15% | -17% | 44 | -$31,351,454 |

## Red flags

- Year 1 loses money on operations (-$22,861,395).
- The startup spend is not earned back within year 1.
