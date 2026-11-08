# Pricing v3: Lapak Yok (nama kerja)

> Format lapak malam. Versi kafe ada di [pricing-kafe.md](pricing-kafe.md). Semua angka dalam Rupiah. Jawaban harga berasal dari **20 pembeli simulasi** yang melihat pitch lapak (`panel/`, seed 2611, orang yang sama dengan panel-panel sebelumnya). Itu bahan untuk memilih apa yang diuji, bukan bukti. Margin dihitung dengan `unit_economics.py` pada `numbers.json`.

## 1. Harga

| Menu | Harga | Posisi terhadap panel lapak |
|---|---:|---|
| **V60 single origin** (2 beans, kartu beans + tanggal sangrai) | **Rp22.000** | Di antara IPP (Rp18.000) dan median "mulai mahal" (Rp24.000), di bawah PME (Rp27.000) |
| **Es kopi susu** (cold brew, ≤3 menit) | **Rp17.000** | Dekat IPP (Rp18.000), di atas median "murah" (Rp13.000) |
| **Kopi tubruk** | **Rp8.000** | Pintu masuk, **bukan headline** (syarat board D10) |
| **Gelas kedua** (es kopi susu atau tubruk) | **Rp12.000** | Menaikkan belanja tamu yang duduk 2–3 jam |
| Makanan | Rp2.500–12.000 | Malam solo hanya siap saji. Roti bakar dan sate hanya Jumat–Sabtu |

**Mengapa V60 tidak diturunkan**, padahal panel lapak menaruh titik "paling sedikit penolakan" (OPP) di Rp12.100:

- **Pembeli V60 adalah pecinta kopi.** Di panel, mereka 2/2 membeli di Rp22.000. Yang keberatan soal harga membandingkannya dengan warkop, dan mereka memang memesan tubruk atau es kopi susu.
- **Board (Offers) memberi syarat** "perkuat stack, jangan turunkan harga". Caranya: kartu beans dengan roastery dan tanggal sangrai, Cicip, dan garansi seduh ulang.
- **Menurut alat CFO, setiap Rp3.000 belanja per tamu memindahkan break-even sekitar 4–6 tamu/malam.** Lihat tabel di bawah.

Rentang lengkap ada di [pricing-curve-lapak.md](pricing-curve-lapak.md):

| Titik | Harga |
|---|---:|
| PMC | Rp10.067 |
| OPP | Rp12.100 |
| IPP | Rp18.000 |
| PME | Rp27.000 |

## 2. Margin di beberapa belanja per tamu (alat CFO, `numbers.json` dengan biaya nyata dari `ops.md`)

| Belanja rata-rata per tamu | Kontribusi/tamu | Break-even/malam (kapasitas ±30) | Margin di 28 tamu/malam | Tahun 1 |
|---:|---:|---:|---:|---:|
| Rp26.000 | Rp10.733 (41%) | 33 (di atas kapasitas) | −7,1% | −Rp24,9 jt |
| **Rp29.000 (rencana v3)** | **Rp13.733 (47%)** | **26** | **+4,0%** | **−Rp11,8 jt** |
| Rp32.000 | Rp16.733 (52%) | 22 | +13,0% | +Rp1,3 jt |

Rp29.000 = minuman pertama rata-rata Rp17.650 + 35% gelas kedua Rp12.000 + 75% makanan rata-rata Rp9.000 [estimasi]. **Target nyata belanja per tamu adalah ≥Rp32.000**, lewat paket, gelas kedua, dan makanan, bukan lewat menaikkan harga V60. Di Rp26.000, break-even melewati kapasitas. Versi hemat ada di `cfo.md`.

## 3. Tangga

| Tingkat | Isi | Harga |
|---|---|---:|
| Masuk | Kopi tubruk + gorengan | ±Rp10.500 |
| **Pulang Kerja** | Es kopi susu + nasi kucing + gorengan | Rp25.000 (tanpa "harga coret") |
| Seduh | V60 + kue/roti, dengan kartu beans | Rp27.000 |
| Sesi Bareng (3–4 orang, **Jumat–Sabtu**) | Teko V60 dua beans + sepiring sate/gorengan | Rp75.000 (Rp19.000–25.000/orang) |

## 4. Penawaran pembukaan

- **Kartu Cap Yok, sejak malam pertama dan tanpa tanggal berakhir:** 1 cap per malam belanja ≥Rp25.000, 5 cap = gelas ke-6 gratis, cap bonus untuk yang membawa teman baru. Biayanya ±Rp595/kunjungan (`marketing.md`). Kartu ini **menggantikan** promo Ajak Teman 2 minggu, yang hanya menarik pemburu promo dan terlewat oleh penunggu review (panel lapak, P017).
- **Tidak ada beli-1-gratis-1 atau cashback e-wallet.** Pemburu promo 3/3 hanya datang selama promo, di panel kafe maupun panel lapak.

## 5. Yang diuji dengan pembeli nyata

| Uji | Varian | Cara | Ukuran |
|---|---|---|---|
| Harga V60 | Rp22.000 vs Rp25.000 | Ganti papan per 2 minggu | % tamu yang memesan V60, % kembali dalam 14 hari |
| Paket Pulang Kerja | Rp25.000 vs Rp27.000 | Sama | % tamu yang mengambil paket, belanja rata-rata |

**Catat setiap malam: jumlah tamu, belanja per tamu, dan lama duduk.** Belanja per tamu adalah angka yang paling menentukan laba di format ini.

## 6. Keberatan harga dari panel lapak (kutipan simulasi, bukan testimoni)

1. "V60 Rp22.000 di lapak teras ruko rasanya kemahalan buat nongkrong biasa." (P006)
2. "Es kopi susu Rp17.000 tanpa promo e-wallet itu lebih mahal dari kopi susu gula aren yang biasa saya beli pakai cashback, dan manual brew buat saya cuma gaya, bukan kebutuhan." (P012)
3. "V60 Rp22.000 di lapak angkringan bikin saya curiga beans-nya biasa saja atau sudah lama di-roast." (P016) **Jawabannya:** kartu beans dengan roastery dan tanggal sangrai.
