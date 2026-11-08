# Offer v3: Lapak Yok (nama kerja)

> Format lapak malam. Versi kafe ada di [offer-kafe.md](offer-kafe.md), dengan daftar 23 masalah pembeli yang sebagian besar masih berlaku. Dokumen ini hanya mencatat **yang berubah untuk lapak**, berdasarkan panel lapak (`panel/results.md`) dan syarat board rapat kedua (D1, D2, D10). Pembeli adalah simulasi; angka beli adalah batas atas.

## Hasil panel untuk pitch lapak (sebelum offer v3)

**10 beli · 10 tidak (50%)**, rata-rata 1,7 kunjungan di bulan pertama, 17 pembelian total. Ini orang yang sama dengan panel lain (seed 2611):

| Pitch | Beli |
|---|---:|
| Kafe v1 (kopi saja) | 5/20 (25%) |
| Kafe v2 (dengan makanan dan offer) | 12/20 (60%) |
| **Lapak** | **10/20 (50%)** |
| GoFood | 0/20 (0%) |

**Siapa yang membeli lapak:**
- **Membeli:** semua mahasiswa/fresh graduate (4/4), semua yang rutin nongkrong (4/4), semua pecinta kopi (2/2), dan semua pemburu promo (3/3, tetapi hanya selama promo).
- **Turun dibanding kafe v2:** profesional mapan (40%, dari 60%). Mereka mengeluhkan tikar dan kenyamanan duduk 2–3 jam.
- **Tidak membeli sama sekali (0%):** pengikut tren TikTok, pembaca review, yang loyal ke tempat langganan, dan yang bekerja dengan laptop.

Tanpa pemburu promo, pembeli sekitar 7/20 (35%).

**Keberatan yang berulang, dan jawabannya di v3:**

| Keberatan (panel lapak) | Jawaban v3 |
|---|---|
| Belum ada review atau buzz TikTok (4 trust + 4 habit) | **Tidak bisa dijawab oleh offer.** Hanya tamu nyata dan waktu. Kanalnya ajakan teman (`marketing.md`) |
| Duduk di tikar 2–3 jam pegal (P007, P008, P019) | **Bangku atau kursi bersandaran, bukan tikar** (`brand.md`, `ops.md`) |
| 15 kursi bisa penuh saat rombongan datang (P004, P014, P018, P020) | **Reservasi meja grup lewat WhatsApp** untuk Jumat–Sabtu |
| Parkir motor susah (P003, P004, P007, P010) | **Kriteria tempat:** ada parkir motor yang jelas, diumumkan di IG dan Google Maps (D4) |
| V60 diseduh satu per satu, nunggu lama (P001, P020) | Es kopi susu ≤3 menit, **waktu tunggu V60 disebut sebelum bayar** (D3), menu malam solo dipangkas (D2) |
| Promo 2 minggu terlewat oleh yang menunggu review (P017) | **Kartu Cap Yok permanen, tanpa tanggal berakhir**, menggantikan promo 2 minggu |
| V60 Rp22.000 di angkringan dicurigai beansnya biasa (P016) | **Kartu beans: roastery + tanggal sangrai**, ditambah cicip |

## Tumpukan offer v3

**Satu kalimat (syarat board):** *Slowbar berbentuk lapak.* Kopi adalah alasan datang, makanan adalah alasan bertahan.

- **Inti:** tempat melepas penat bareng teman sepulang kerja. Kopi diseduh di depan kamu, duduk di bangku, bebas laptop.
- **Paket** (syarat D1, target belanja rata-rata ≥Rp29.000–30.000):
  - **Pulang Kerja** Rp25.000: es kopi susu + nasi kucing + gorengan. Semuanya siap saji, jadi bisa di malam solo.
  - **Seduh** Rp27.000: V60 + kue/roti, dengan kartu beans.
  - **Sesi Bareng** Rp75.000, 3–4 orang, **hanya Jumat–Sabtu**: teko V60 dua beans + sepiring sate/gorengan.
- **Gelas kedua Rp12.000** (es kopi susu atau tubruk) untuk yang duduk lama.
- **Bonus:** cicip (malam solo: cium bubuk dua beans; Jumat–Sabtu: tegukan kecil) dan kartu beans dibawa pulang.
- **Garansi:** tidak cocok di tegukan pertama, diseduh ulang dengan beans lain, gratis.
- **Kartu Cap Yok (menggantikan Ajak Teman 2 minggu):** 1 cap per malam belanja ≥Rp25.000. 5 cap = gelas ke-6 gratis. Cap bonus jika membawa teman yang baru pertama kali datang. Tanpa tanggal berakhir. Biaya ±Rp595/kunjungan (`marketing.md` §5). Kartu ini menjangkau penunggu review dan tidak mengundang pemburu promo yang hilang setelah 2 minggu.

## Menu menurut malam (syarat D2)

| | Rabu–Kamis (founder sendiri) | Jumat–Sabtu (founder + helper) |
|---|---|---|
| Kopi | V60 (2 beans), es kopi susu konsentrat, tubruk | Sama, ditambah teko Sesi Bareng |
| Makanan | Siap saji: nasi kucing, gorengan, kue/roti | Ditambah roti bakar dan sate (kompor untuk kettle dan pemanggang) |
| Buka | 19.00, atau **19.30** jika pemasangan lewat 19.00. Jam itu yang ditulis | 18.00 (helper mulai memasang 17.30) |

## Biaya (alat CFO, `numbers.json`)

Belanja per tamu Rp29.000:

| Biaya variabel per tamu | Rp |
|---|---:|
| Minuman pertama | 6.890 |
| Gelas kedua (35%) | 2.412 |
| Makanan (75% tamu, HPP ±62%) | 4.190 |
| Waste | 465 |
| Cup | 320 |
| Cicip + garansi | 250 |
| Kartu Cap Yok | 595 |
| PPh 0,5% | 145 |
| **Total** | **15.267** |
| **Kontribusi** | **Rp13.733 (47%)** |

Hasilnya, sebelum biaya nyata dari `ops.md`: break-even 21 tamu/malam, tahun 1 +Rp2,1 juta. **Setelah biaya nyata** (jam helper sebenarnya, es, galon, gas dua kompor): break-even **26 tamu/malam**, tahun 1 **−Rp11,8 juta**. Untuk kembali untung, offer harus menaikkan belanja ke **≥Rp32.000/tamu** (break-even 22) dan ops harus mendapat penghematan dari tuan rumah. Rinciannya di `cfo.md`.

**Kalau semua makanan titipan (HPP ±72%, tidak memasak di akhir pekan):** kontribusi Rp13.063, break-even 22, tahun 1 **−Rp0,9 juta**. Selisih antara untung dan rugi di tahun 1 ditentukan oleh keputusan kecil seperti ini, jadi catat HPP makanan sejak malam pertama.

## Belum diuji

Offer v3 (paket, kartu cap, bangku, reservasi) belum dites ulang ke panel. **Ujinya adalah delapan minggu pertama**, dengan ambang board D9.
