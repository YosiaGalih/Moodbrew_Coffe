# Catatan CFO: Lapak Yok (rencana v3, dengan biaya nyata dari `ops.md`)

> `numbers.json` = **lapak malam Rawamangun dengan offer v3 dan biaya nyata dari [ops.md](ops.md) §11**. Pembanding:
> - versi hemat: `numbers-lapak-hemat.json`;
> - rencana ruko lama: [cfo-ruko.md](cfo-ruko.md);
> - versi lapak sebelum ops: `numbers-lapak-v3-1-sebelum-ops.json`;
> - opsi Jogja: `numbers-jogja.json`.
>
> Semua angka dalam Rupiah (`$` di tabel alat = Rp). Banyak input masih **estimasi**: sewa teras, porsi makanan, es, galon, gas, ramp, dan kapasitas. Ini bukan nasihat keuangan atau pajak; minta akuntan atau KPP mengecek PPh dan PBJT.

## Kebenaran yang tidak nyaman lebih dulu

**Dengan biaya nyata menjalankan lapak tanpa listrik, rencana lapak merugi di tahun 1.**

- Jam helper yang sebenarnya, es untuk cooler, air galon, dan gas dua kompor menaikkan biaya tetap dari Rp4,83 juta ke **Rp5,98 juta/bulan**.
- Break-even naik ke **26 tamu/malam** dari kapasitas realistis sekitar **30**.
- Tahun 1 **−Rp11,8 juta**.

Tidak ada yang salah dengan konsepnya. Hanya saja, di skala sekecil ini setiap Rp500 ribu biaya tetap menggeser break-even sekitar 2 tamu/malam.

## Margin (rencana `numbers.json`)

| Angka | Nilai |
|---|---|
| Belanja per tamu | **Rp29.000** |
| Kontribusi per tamu | **Rp13.733 (47%)** |
| Biaya tetap | **Rp5,98 juta/bulan** |
| Break-even | **26 tamu/malam** (kapasitas ±30) |
| Margin di rencana 28 tamu/malam | **+4,0%** |
| Tahun 1 (operasional) | **−Rp11,8 juta** |
| Startup | **Rp20,5 juta** (alat seduh sudah dimiliki) |
| Kas dibutuhkan | **±Rp33,8 juta** |

## Jalan kembali ke untung (semua dijalankan dengan alat)

| Skenario | Biaya tetap/bulan | Break-even/malam | Margin di 28 | Tahun 1 | Kas dibutuhkan |
|---|---:|---:|---:|---:|---:|
| **Rencana (biaya nyata)** | Rp5,98 jt | **26** | +4,0% | **−Rp11,8 jt** | Rp33,8 jt |
| **Hemat:** helper 18.00–23.30, air/galon dari tuan rumah, es dibeli sendiri | Rp4,99 jt | 22 | +11,2% | +Rp0,1 jt | Rp27,5 jt |
| Rencana + belanja Rp32.000 | Rp5,98 jt | 22 | +13,0% | +Rp1,3 jt | Rp28,5 jt |
| **Hemat + belanja Rp32.000** | Rp4,99 jt | **18** | +19,5% | **+Rp13,2 jt** | Rp24,4 jt |
| Hemat, tamu −30% | Rp4,99 jt | 22 | −4,3% | −Rp17,9 jt | Rp38,4 jt |

**Artinya:** lapak baru masuk akal jika **dua hal terjadi bersamaan**:
1. **Penghematan operasional.** Air dan galon dari tuan rumah ditulis di perjanjian, dan helper hanya 18.00–23.30.
2. **Belanja per tamu naik ke sekitar Rp32.000** lewat paket, gelas kedua, dan makanan, **bukan lewat harga V60**.

Keduanya harus terbukti di 8 minggu pertama.

## Syarat board

| Syarat | Status |
|---|---|
| C1 Aplikasi dibekukan | Terpenuhi (Qasir + QRIS statis) |
| D1 Paket inti, belanja ≥Rp30.000 | Paket dirancang (`offer.md`). Model memakai Rp29.000; **Rp32.000 dibutuhkan untuk untung yang berarti** |
| D4 Perjanjian tempat (atap, air, toilet, titip gerobak) | **Mempengaruhi angka langsung:** titip gerobak menghemat Rp400 ribu/bulan, air dari tuan rumah Rp250 ribu/bulan |
| D9 Ambang review 2 Feb | **Naikkan ambang tamu dari 21 ke 26 tamu bayar/malam** (break-even biaya nyata). Ambang 21 hanya berlaku jika penghematan tercapai dan tercatat |
| C11 / D11 Kios dan Jogja ditunda | Dipertahankan. Jogja dengan operator rugi (Lampiran C) |

---

# Lampiran A: Rencana lapak dengan biaya nyata (`numbers.json`), output alat


Every number below comes from the input file. Nothing is looked up or guessed.

## One tamu (rata-rata belanja per kunjungan)

| line | per tamu (rata-rata belanja per kunjungan) |
| --- | ---: |
| Price | $29,000.00 |
| Minuman pertama: campuran 40% V60 (bahan Rp7.050), 45% es kopi susu (Rp7.900), 15% tubruk (Rp3.400) = Rp6.890 [estimasi campuran] | -$6,890.00 |
| Gelas kedua Rp12.000 (35% tamu) x bahan Rp6.890 [estimasi porsi] | -$2,412.00 |
| Makanan: 75% tamu x Rp9.000 x HPP ±62% (malam solo Rabu-Kamis: siap saji/titipan ±72%, ±40% tamu; Jumat-Sabtu dengan helper: roti bakar & sate buat sendiri, campuran ±55%, ±60% tamu) [estimasi] | -$4,190.00 |
| Waste 5% bahan minuman [estimasi] | -$465.00 |
| Cup take-away 20% tamu x Rp1.600 | -$320.00 |
| Cicip (cium bubuk/tegukan kecil) + garansi seduh ulang [estimasi] | -$250.00 |
| Kartu Cap Yok: 1 cap per malam belanja >=Rp25.000, 5 cap = gelas ke-6 gratis, cap bonus bawa teman baru (marketing-lapak.md, ±Rp595/kunjungan) [estimasi] | -$595.00 |
| PPh Final UMKM 0,5% (orang pribadi: Rp500 jt omzet pertama/tahun bebas; dimasukkan agar konservatif) | -$145.00 |
| QRIS statis (MDR 0% untuk transaksi <= Rp100.000) | -$0.00 |
| **Contribution** (what each tamu (rata-rata belanja per kunjungan) leaves to pay the fixed costs) | **$13,733.00** (47%) |

## The margin that matters

Fixed costs: $5,983,250 a month (Sewa/numpang teras ruko atau rumah yang tutup sore (listing Jaktim Rp0,6-2,5 jt/bulan; research/lokasi-rawamangun.md) $1,500,000, Helper Jumat-Sabtu 17.30-00.15 (6,75 jam x 8,67 malam x Rp45.475/jam, UMP DKI/126) + BPJS JKK/JKM (ops-lapak.md) $2,675,000, Gas: LPG 5,5 kg + gas kaleng kompor kedua Jumat-Sabtu (ops-lapak.md) [estimasi] $400,000, Angkut alat: Rp0 HANYA jika titip gerobak tertulis di perjanjian (ops-lapak.md; jika tidak, +Rp400 rb) $0, Iuran kebersihan/warga dengan kuitansi [estimasi] $150,000, Marketing (cetak kartu Ajak Teman, konten) [estimasi] $500,000, Aplikasi kasir Qasir Pro (Rp699 rb/tahun) $58,250, Es untuk cooler + ongkir (ops-lapak.md) [estimasi] $450,000, Air galon untuk seduh & minum (ops-lapak.md) [estimasi] $250,000).

- **Break-even: 26 tamu (rata-rata belanja per kunjungan)s a day.** Below that you lose money every month.
- **Profit margin at your plan** (28 a day): **4%** of every sale, after every cost.
- Capacity: 30 a day.

## Year 1, month by month

| month | tamu (rata-rata belanja per kunjungan)s a day | revenue | profit | cumulative (after $20,520,000 startup) |
| ---: | ---: | ---: | ---: | ---: |
| 1 | 10 | $4,930,000 | -$3,648,640 | -$24,168,640 |
| 2 | 13 | $6,409,000 | -$2,948,257 | -$27,116,897 |
| 3 | 16 | $7,888,000 | -$2,247,874 | -$29,364,771 |
| 4 | 18 | $8,874,000 | -$1,780,952 | -$31,145,723 |
| 5 | 20 | $9,860,000 | -$1,314,030 | -$32,459,753 |
| 6 | 22 | $10,846,000 | -$847,108 | -$33,306,861 |
| 7 | 24 | $11,832,000 | -$380,186 | -$33,687,047 |
| 8 | 25 | $12,325,000 | -$146,725 | -$33,833,772 |
| 9 | 26 | $12,818,000 | $86,736 | -$33,747,036 |
| 10 | 27 | $13,311,000 | $320,197 | -$33,426,839 |
| 11 | 28 | $13,804,000 | $553,658 | -$32,873,181 |
| 12 | 28 | $13,804,000 | $553,658 | -$32,319,523 |

- **Year 1 operating profit: -$11,799,523** on $126,701,000 of revenue.
- After the $20,520,000 startup spend: -$32,319,523.
- Startup money earned back: not within year 1.
- Cash you need before it pays for itself: **$33,833,772**.

## What if

| scenario | margin at plan | break-even a day | year 1 profit |
| --- | ---: | ---: | ---: |
| Base plan | 4% | 26 | -$11,799,523 |
| Price -10% | -7% | 33 | -$24,469,623 |
| Volume -20% | -7% | 26 | -$23,799,418 |
| Unit costs +15% | -4% | 31 | -$21,804,751 |

## Red flags

- Year 1 loses money on operations (-$11,799,523).
- The startup spend is not earned back within year 1.

---

# Lampiran B: Versi hemat (`numbers-lapak-hemat.json`), output alat


Every number below comes from the input file. Nothing is looked up or guessed.

## One tamu (rata-rata belanja per kunjungan)

| line | per tamu (rata-rata belanja per kunjungan) |
| --- | ---: |
| Price | $29,000.00 |
| Minuman pertama: campuran 40% V60 (bahan Rp7.050), 45% es kopi susu (Rp7.900), 15% tubruk (Rp3.400) = Rp6.890 [estimasi campuran] | -$6,890.00 |
| Gelas kedua Rp12.000 (35% tamu) x bahan Rp6.890 [estimasi porsi] | -$2,412.00 |
| Makanan: 75% tamu x Rp9.000 x HPP ±62% (malam solo Rabu-Kamis: siap saji/titipan ±72%, ±40% tamu; Jumat-Sabtu dengan helper: roti bakar & sate buat sendiri, campuran ±55%, ±60% tamu) [estimasi] | -$4,190.00 |
| Waste 5% bahan minuman [estimasi] | -$465.00 |
| Cup take-away 20% tamu x Rp1.600 | -$320.00 |
| Cicip (cium bubuk/tegukan kecil) + garansi seduh ulang [estimasi] | -$250.00 |
| Kartu Cap Yok: 1 cap per malam belanja >=Rp25.000, 5 cap = gelas ke-6 gratis, cap bonus bawa teman baru (marketing-lapak.md, ±Rp595/kunjungan) [estimasi] | -$595.00 |
| PPh Final UMKM 0,5% (orang pribadi: Rp500 jt omzet pertama/tahun bebas; dimasukkan agar konservatif) | -$145.00 |
| QRIS statis (MDR 0% untuk transaksi <= Rp100.000) | -$0.00 |
| **Contribution** (what each tamu (rata-rata belanja per kunjungan) leaves to pay the fixed costs) | **$13,733.00** (47%) |

## The margin that matters

Fixed costs: $4,991,125 a month (Sewa/numpang teras ruko atau rumah yang tutup sore (listing Jaktim Rp0,6-2,5 jt/bulan; research/lokasi-rawamangun.md) $1,500,000, Helper Jumat-Sabtu 18.00-23.30 (5,5 jam x 8,67 malam x Rp45.475/jam) + BPJS JKK/JKM; founder memasang & membongkar $2,182,875, Gas: LPG 5,5 kg + gas kaleng kompor kedua Jumat-Sabtu (ops-lapak.md) [estimasi] $400,000, Angkut alat: Rp0 HANYA jika titip gerobak tertulis di perjanjian (ops-lapak.md; jika tidak, +Rp400 rb) $0, Iuran kebersihan/warga dengan kuitansi [estimasi] $150,000, Marketing (cetak kartu Ajak Teman, konten) [estimasi] $500,000, Aplikasi kasir Qasir Pro (Rp699 rb/tahun) $58,250, Es untuk cooler, dibeli sendiri di jalan (ops.md) [estimasi] $200,000, Air: Rp0 tambahan jika air/galon dari tuan rumah masuk perjanjian sewa (ops.md) $0).

- **Break-even: 22 tamu (rata-rata belanja per kunjungan)s a day.** Below that you lose money every month.
- **Profit margin at your plan** (28 a day): **11%** of every sale, after every cost.
- Capacity: 30 a day.

## Year 1, month by month

| month | tamu (rata-rata belanja per kunjungan)s a day | revenue | profit | cumulative (after $20,520,000 startup) |
| ---: | ---: | ---: | ---: | ---: |
| 1 | 10 | $4,930,000 | -$2,656,515 | -$23,176,515 |
| 2 | 13 | $6,409,000 | -$1,956,132 | -$25,132,647 |
| 3 | 16 | $7,888,000 | -$1,255,749 | -$26,388,396 |
| 4 | 18 | $8,874,000 | -$788,827 | -$27,177,223 |
| 5 | 20 | $9,860,000 | -$321,905 | -$27,499,128 |
| 6 | 22 | $10,846,000 | $145,017 | -$27,354,111 |
| 7 | 24 | $11,832,000 | $611,939 | -$26,742,172 |
| 8 | 25 | $12,325,000 | $845,400 | -$25,896,772 |
| 9 | 26 | $12,818,000 | $1,078,861 | -$24,817,911 |
| 10 | 27 | $13,311,000 | $1,312,322 | -$23,505,589 |
| 11 | 28 | $13,804,000 | $1,545,783 | -$21,959,806 |
| 12 | 28 | $13,804,000 | $1,545,783 | -$20,414,023 |

- **Year 1 operating profit: $105,977** on $126,701,000 of revenue.
- After the $20,520,000 startup spend: -$20,414,023.
- Startup money earned back: not within year 1.
- Cash you need before it pays for itself: **$27,499,128**.

## What if

| scenario | margin at plan | break-even a day | year 1 profit |
| --- | ---: | ---: | ---: |
| Base plan | 11% | 22 | $105,977 |
| Price -10% | 1% | 28 | -$12,564,123 |
| Volume -20% | 2% | 22 | -$11,893,918 |
| Unit costs +15% | 3% | 26 | -$9,899,251 |

## Red flags

- The startup spend is not earned back within year 1.

---

# Lampiran C: Opsi Jogja dengan operator (`numbers-jogja.json`), output alat


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
