# Catatan CFO: Kopiyo

> Semua angka dalam Rupiah (`$` di tabel alat di bawah berarti Rp). Setiap angka berasal dari output `unit_economics.py` atau input yang tercatat di [cfo-sources.md](cfo-sources.md). Banyak input masih **estimasi**, terutama kapasitas, renovasi, porsi makanan, dan ramp. Ini bukan nasihat keuangan, pajak, atau hukum. **Minta akuntan memeriksa struktur usaha, biaya gaji/BPJS, PBJT, dan PPh sebelum uang keluar.**

## Kebenaran yang tidak nyaman lebih dulu

**Rencana dasar (ruko Rp150 juta/tahun, 3 staf digaji UMP, founder tidak di bar) baru balik modal sekitar 8 tahun setelah tahun pertama.**

- Di 60 tamu/hari, laba bulanan hanya **Rp3,3 juta**. Startup Rp207,9 juta ditambah kerugian tahun 1 berarti sisa minus **Rp280,8 juta** di akhir bulan 12. Pada laju Rp3,3 juta/bulan, itu butuh sekitar 85 bulan lagi.
- Ini bukan bisnis yang layak dalam bentuk ini. **Versi ramping layak diuji** (lihat cara 1 + 2 di bawah).

## Margin

- **Kontribusi per tamu: Rp23.594 (59%)** dari belanja rata-rata Rp40.000.
- **Margin di rencana 60 tamu/hari: +5%.** Break-even: **56 tamu/hari**, dari kapasitas sekitar 96 (58% okupansi setiap hari).
- **Tahun 1 rugi operasional Rp72,9 juta.** Sesuai ramp, bulan 9 adalah bulan pertama yang untung.

## Angka yang paling perlu dijaga: volume (ramp)

- **Volume −20%** (48 tamu/hari di rencana): margin **−9%**, tahun 1 **−Rp152,4 juta**.
- Break-even 56 tamu/hari dan rencana 60 hanya berjarak 4 tamu. Jaraknya terlalu tipis.
- **Cek ramp terhadap panel** [Menebak]:
  - Bulan 1 = 23 tamu/hari ≈ 690 kunjungan. Panel v2 menyebut 1,4 kunjungan per pembeli di bulan pertama, jadi dibutuhkan sekitar 490 orang berbeda.
  - Dengan tingkat beli sekitar 45% (60% dikurangi pembeli yang hanya datang karena promo), sekitar 1.100 orang di target harus melihat dan mempertimbangkan Kopiyo di bulan pertama.
  - Kalau tingkat beli nyata hanya setengahnya, dibutuhkan sekitar 2.200 orang.
  - Untuk brand tanpa reputasi, itu target marketing yang berat tapi mungkin. Jangan percaya ramp ini sampai uji pop-up (`/founder-launch`) memberi angka nyata.

**Angka kedua yang perlu dijaga: PBJT 10%.**

- Di rencana, omzet sekitar Rp72 juta/bulan, di atas ambang Rp42 juta. PBJT wajib.
- Model ini menganggap pajak **ditambahkan di atas harga menu**.
- **Jika harga menu sudah termasuk pajak** (setara belanja bersih Rp36.364): break-even **66 tamu/hari**, margin **−5%**, tahun 1 **−Rp134,1 juta**. Tulis jelas di menu "harga belum termasuk PBJT 10%", atau naikkan harga.

## Kas

- **Kas yang dibutuhkan sebelum usaha membiayai dirinya sendiri: Rp289,8 juta** (output alat, dengan sewa dibayar bulanan).
- **Kenyataannya, ruko di Rawamangun biasanya disewa setahun di muka.** Dengan sewa tahun pertama Rp150 juta dibayar di depan, puncak kebutuhan kas menjadi **sekitar Rp376,3 juta** (hitungan dari output bulanan alat).
- **Versi ramping (cara 1 + 2): Rp207,8 juta**, atau **sekitar Rp292,5 juta** dengan sewa setahun di muka.

## Tiga cara memperbaiki margin (semua dijalankan dengan alat)

| # | Cara | Yang berubah | Break-even/hari | Margin di rencana | Tahun 1 | Laba bulan ke-12 |
|---|---|---|---:|---:|---:|---:|
| — | **Rencana dasar** | — | 56 | 5% | −Rp72,9 jt | Rp3,3 jt |
| 1 | **Founder ikut di bar** (2 staf + founder tanpa gaji) | Biaya tetap −Rp6,79 jt/bulan | **46** | **14%** | **+Rp8,5 jt** | Rp10,1 jt |
| 2 | **Ruang lebih kecil** (sewa Rp106 jt/tahun, renovasi Rp50 jt) | Sewa −Rp3,67 jt/bulan, startup −Rp25 jt | 51 | 10% | −Rp28,9 jt | Rp7,0 jt |
| 3 | **Belanja per tamu +10%** (Rp44.000, lewat harga atau porsi makanan/Paket Pulang Kerja) | Harga per tamu | 48 | 13% | −Rp5,6 jt | Rp10,5 jt |
| 1+2 | **Versi ramping** | Gabungan | **41** | **19%** | **+Rp52,5 jt** | **Rp13,8 jt** |
| 1+2+3 | Ramping + belanja Rp44.000 | Gabungan | 35 | — | — | Rp21,0 jt |
| 1+2, volume −20% | Ramping, tamu lebih sedikit | Volume | 41 | 9% | −Rp26,9 jt | — |

**Catatan cara 2:** ruang lebih kecil berarti kursi lebih sedikit. Dengan 24 kursi, kapasitas turun ke sekitar 77 tamu/hari [estimasi]. Break-even 41–51 masih muat, tapi rencana 60 tamu/hari menjadi 78% okupansi.

**Balik modal versi ramping:** sekitar 9,5 bulan setelah bulan 12, jadi **sekitar 22 bulan sejak buka**. Itu masih di atas 12 bulan, tapi masuk akal untuk kedai kopi. Rencana dasar butuh sekitar 97 bulan.

## Syarat board soal uang (`founder/board.md`)

| Syarat | Status |
|---|---|
| C1 Bekukan MoodBrew AI, pakai POS siap pakai | **Terpenuhi di angka**: POS Moka Rp299 ribu/bulan, biaya pengembangan aplikasi Rp0 |
| C4 Harga dari angka, bukan dari "tidak terlalu mahal" | **Terpenuhi**: V60 Rp25.000, es kopi susu Rp22.000 dari rentang panel dan hitungan margin (`pricing.md`) |
| C8 Uji nyata sebelum menandatangani sewa | **Belum.** Ini yang paling penting, karena volume adalah angka yang paling menentukan |
| Rencana dasar menghasilkan untung | **Tidak terpenuhi.** Tahun 1 rugi, balik modal sekitar 8 tahun. Hanya versi ramping yang untung di tahun 1 |

## Pertanyaan yang hanya bisa dijawab founder

1. Apakah kamu sendiri akan bekerja di bar setiap hari, minimal di jam ramai? Ini satu-satunya cara terbesar memperbaiki angka.
2. Berapa modal yang kamu punya? Rencana dasar butuh sekitar Rp376 juta, versi ramping sekitar Rp292 juta. Keduanya dengan sewa setahun di muka.
3. Ada penawaran sewa nyata (luas, jumlah kursi, parkir motor)? Angka sewa dan kapasitas di sini masih dari listing publik dan tebakan.

---

# Unit economics: Kopiyo: slowbar di Rawamangun dengan offer v2 (kopi + makanan + Sesi Ngobrol). Semua angka dalam Rupiah; alat mencetak '$' = Rp.

Every number below comes from the input file. Nothing is looked up or guessed.

## One tamu (rata-rata belanja per kunjungan)

| line | per tamu (rata-rata belanja per kunjungan) |
| --- | ---: |
| Price | $40,000.00 |
| Minuman pertama: bahan rata-rata (V60/es kopi susu, termasuk cup take-away & waste) | -$8,442.00 |
| Gelas kedua Rp15.000 (30% tamu) x bahan Rp8.442 | -$2,533.00 |
| Makanan (60% tamu) x HPP Rp7.600 (±38% dari rata-rata Rp20.000) [estimasi] | -$4,560.00 |
| Cicip Dulu gratis (30% tamu x Rp1.000) [estimasi] | -$300.00 |
| Garansi seduh ulang (5% klaim x 50% V60 x Rp6.850) [estimasi klaim] | -$171.00 |
| Kartu beans cetak (50% tamu x Rp400) [estimasi] | -$200.00 |
| PPh Final UMKM 0,5% dari belanja | -$200.00 |
| Biaya QRIS (MDR 0% untuk transaksi <= Rp100.000) | -$0.00 |
| **Contribution** (what each tamu (rata-rata belanja per kunjungan) leaves to pay the fixed costs) | **$23,594.00** (59%) |

## The margin that matters

Fixed costs: $39,169,000 a month (Sewa ruko ±100-150 m2 Rawamangun (Rp150 jt/tahun) $12,500,000, 3 staf (2 barista + 1 helper/kasir) x Rp6,79 jt (UMP DKI 2026 + BPJS pemberi kerja + THR/12) $20,370,000, Listrik B-2 ±1.250 kWh x Rp1.444,7 [estimasi beban] $1,800,000, Air, galon, internet [estimasi] $800,000, POS Moka Basic $299,000, Marketing rutin [estimasi] $2,000,000, Perawatan, kebersihan, perlengkapan kecil [estimasi] $1,000,000, Gas LPG dapur sederhana [estimasi] $400,000).

- **Break-even: 56 tamu (rata-rata belanja per kunjungan)s a day.** Below that you lose money every month.
- **Profit margin at your plan** (60 a day): **5%** of every sale, after every cost.
- Capacity: 96 a day.

## Year 1, month by month

| month | tamu (rata-rata belanja per kunjungan)s a day | revenue | profit | cumulative (after $207,875,000 startup) |
| ---: | ---: | ---: | ---: | ---: |
| 1 | 23 | $27,600,000 | -$22,889,140 | -$230,764,140 |
| 2 | 29 | $34,800,000 | -$18,642,220 | -$249,406,360 |
| 3 | 35 | $42,000,000 | -$14,395,300 | -$263,801,660 |
| 4 | 40 | $48,000,000 | -$10,856,200 | -$274,657,860 |
| 5 | 45 | $54,000,000 | -$7,317,100 | -$281,974,960 |
| 6 | 49 | $58,800,000 | -$4,485,820 | -$286,460,780 |
| 7 | 52 | $62,400,000 | -$2,362,360 | -$288,823,140 |
| 8 | 54 | $64,800,000 | -$946,720 | -$289,769,860 |
| 9 | 56 | $67,200,000 | $468,920 | -$289,300,940 |
| 10 | 58 | $69,600,000 | $1,884,560 | -$287,416,380 |
| 11 | 60 | $72,000,000 | $3,300,200 | -$284,116,180 |
| 12 | 60 | $72,000,000 | $3,300,200 | -$280,815,980 |

- **Year 1 operating profit: -$72,940,980** on $673,200,000 of revenue.
- After the $207,875,000 startup spend: -$280,815,980.
- Startup money earned back: not within year 1.
- Cash you need before it pays for itself: **$289,769,860**.

## What if

| scenario | margin at plan | break-even a day | year 1 profit |
| --- | ---: | ---: | ---: |
| Base plan | 5% | 56 | -$72,940,980 |
| Price -10% | -6% | 67 | -$140,260,980 |
| Volume -20% | -9% | 56 | -$152,358,384 |
| Unit costs +15% | -2% | 62 | -$114,357,927 |

## Red flags

- Year 1 loses money on operations (-$72,940,980).
- The startup spend is not earned back within year 1.
