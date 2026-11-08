# Pricing: Kopiyo

> Semua angka dalam Rupiah. Jawaban harga berasal dari **20 pembeli simulasi** (`founder/panel/`), bukan pelanggan sungguhan: dipakai untuk memilih *apa yang diuji*, bukan sebagai bukti. Hitungan margin berasal dari `unit_economics.py` dengan `founder/numbers.json` versi awal (kopi saja, tanpa makanan); CFO akan memperbaruinya.

## Catatan untuk founder: harga murah, margin tipis

**Saya tidak setuju strategi "harga murah, margin tipis, orang kembali karena rasa" untuk slowbar.**

- **Alasannya:** margin tipis hanya jalan kalau volumenya tinggi, dan slowbar punya batas volume: kursi × jam buka ÷ lama duduk.
- **Asumsi yang dipakai** [Menebak, perlu diganti angka nyata dari tempat yang disewa]: 30 kursi, buka 8 jam, tamu duduk sekitar 2,5 jam, 1,3 gelas per tamu. Hasilnya, kapasitas maksimal sekitar **125 gelas/hari** di okupansi 100%.
- **Di harga rata-rata Rp21.000** (V60 Rp22.000, es kopi susu Rp20.000), **break-even adalah 104 gelas/hari, atau 83% okupansi setiap hari, termasuk Senin sore.**
  - Di rencana 75 gelas/hari, margin **−23%**.
  - Tahun 1 rugi operasional sekitar Rp197 juta.
  - Kas yang dibutuhkan sebelum balik modal sekitar **Rp395 juta**.
- **Jika harga turun 10% lagi, break-even naik ke 125 gelas/hari, sama dengan kapasitas maksimal.** Pada titik itu kedai tidak bisa untung, seramai apa pun.

Pelanggan yang kembali karena rasa memang menaikkan okupansi, tetapi tidak menaikkan kapasitas. Jadi:

- **Yang akan saya lakukan sebagai gantinya:** kopinya tetap terjangkau, di bawah median kompetitor, tetapi uang dicari dari **belanja per tamu** (makanan, paket sesi ngobrol) dan dari **biaya tetap yang lebih kecil** (tempat lebih kecil, jam buka sore–malam saja, founder ikut di bar). Ini dikerjakan di `/founder-offer` dan `/founder-cfo`.
- **Risiko jika tetap pada harga murah dan margin tipis:** kedai penuh tapi tetap rugi, dan cara keluarnya biasanya memangkas staf atau waktu seduh. Artinya memangkas pengalaman yang kamu jual.

## 1. Harga yang direkomendasikan

| Menu | Harga | Posisi |
|---|---:|---|
| Es kopi susu Kopiyo | **Rp22.000** | Untuk yang tidak mau menunggu seduhan manual. Masih di bawah median panel untuk "mulai terasa mahal" (Rp28.000) |
| V60 single origin | **Rp25.000** | Di bawah median kompetitor (Rp26.000–27.500), di atas titik IPP panel (Rp18.020) |

**Mengapa angka ini:**

- **Rentang yang bisa diterima panel slowbar: Rp12.016 sampai Rp30.010** (PMC → PME). Titik IPP, di mana jumlah yang bilang "murah" sama dengan yang bilang "mahal", ada di **Rp18.020**. Detail di [pricing-curve.md](pricing-curve.md).
- **Kompetitor** (dari [competitors.md](competitors.md), hanya 4 harga dan sebagian besar data 2022–2023):

  | Tempat | Harga |
  |---|---:|
  | Jung | Rp20.000 |
  | Anastomosis | Rp26.000 |
  | Kopi Nako, jaringan | Rp29.000 |
  | Kalea | Rp40.000 |
  | Kopi Kenangan Mantan (substitusi) | Rp18.000 |
  | Point Coffee Americano (substitusi) | Rp20.000–25.000 |

  V60 Rp25.000 tetap "tidak terlalu mahal" untuk Rawamangun tanpa menjadi yang termurah. Jadi yang termurah hanya untuk sehari, sampai ada yang memotong harga lagi.
- **Margin dari alat CFO** (kopi saja, rencana 75 gelas/hari):

  | Rata-rata per gelas | Kontribusi/gelas | Break-even/hari | Margin di rencana | Tahun 1 |
  |---|---:|---:|---:|---:|
  | Rp21.000 (pitch awal) | Rp12.453 (59%) | 104 | −23% | −Rp196,6 jt |
  | **Rp23.500 (rekomendasi)** | **Rp14.953 (64%)** | **87** | **−10%** | **−Rp142,7 jt** |
  | Rp24.000 | Rp15.453 (64%) | 84 | −7% | −Rp131,9 jt |
  | Rp27.000 | Rp18.453 (68%) | 71 | +5% | −Rp67,2 jt |

**Harga yang direkomendasikan pun masih rugi di rencana ini.** Masalahnya bukan harga kopi per gelas. Masalahnya, satu tamu yang duduk 2,5 jam hanya membelanjakan sekitar Rp30.000, sementara biaya tetap sekitar Rp38,8 juta/bulan. Harga saja tidak bisa memperbaikinya. Itu tugas offer (belanja per tamu) dan CFO (biaya tetap).

## 2. Tangga harga (good / better / best)

| Tingkat | Isi | Harga | Alasan naik tingkat |
|---|---|---:|---|
| **Cepat** | Es kopi susu Kopiyo, keluar dalam 3 menit | Rp22.000 | Menjawab keberatan nomor satu panel: "capek, lapar, slowbar lama" |
| **Seduh** | V60 single origin diseduh di depan kamu, plus kartu beans (origin, roastery, tanggal sangrai) | Rp25.000 | Untuk yang ingin pengalaman. Kartu beans menjawab keraguan "Rp22rb terlalu murah untuk single origin, beansnya segar?" (P016) |
| **Sesi Ngobrol** (2–4 orang) | Satu teko seduhan dari 2 beans berbeda untuk dicicipi bersama, plus camilan untuk berbagi | sekitar Rp85.000 (Rp21.000–43.000/orang) | Belanja per meja naik, dibagi rata terasa adil, dan cocok dengan pemicu beli terkuat di panel: diajak teman. Isi dan biayanya dihitung di `/founder-offer`. |

## 3. Penawaran pembukaan

**"Ajak Teman": 14 hari pertama setelah buka, minuman kedua untuk teman yang kamu ajak setengah harga.** Berakhir di tanggal yang ditulis di papan dan di Instagram; tidak diperpanjang.

- **Kenapa bukan beli-1-gratis-1:** pemburu promo di panel 0% beli di harga normal (0 dari 3). Promo gratis menarik orang yang akan hilang saat promo selesai.
- **Kenapa "ajak teman":** ajakan teman adalah pembalik "tidak" yang paling sering muncul di panel. Kopiyo memang dijual untuk kelompok, bukan untuk orang sendirian.
- **Biaya:** setengah harga gelas kedua. CFO perlu memodelkannya di bulan pertama.

## 4. Yang diuji dengan pembeli sungguhan

Pakai pop-up atau soft opening (lihat `/founder-launch`), jangan landing page. Yang dijual adalah suasana.

| Uji | Varian A | Varian B | Cara | Ukuran |
|---|---|---|---|---|
| Harga V60 | Rp25.000 | Rp28.000 | Ganti papan menu tiap sesi pop-up (minimal 4 sesi per harga) | % tamu yang memesan V60, dan % yang kembali dalam 14 hari |
| Paket Sesi | Rp75.000 | Rp95.000 | Sama | % meja berisi 2–4 orang yang mengambil paket |

Catat juga **lama duduk dan belanja per tamu**. Dua angka itu lebih menentukan untung-rugi daripada harga per gelas.

## 5. Keberatan harga dari panel (kutipan simulasi, bukan testimoni)

1. "Rp20 ribu buat es kopi susu tanpa promo apa-apa itu harga penuh, padahal di kedai kopi chain dekat Arion aku bisa dapat beli 1 gratis 1 atau cashback e-wallet." (P002)
2. "Rp20 ribu buat es kopi susu tanpa promo apa-apa, padahal di aplikasi aku biasa dapet beli 1 gratis 1 atau cashback e-wallet." (P003)
3. "Tapi buat rutin, warkop masih jauh lebih murah buat duduk 2-3 jam." (P014, pembeli yang hanya mau coba sekali)

Pola yang perlu dicatat marketing: hampir semua yang menolak karena harga **membandingkan dengan promo aplikasi atau warkop, bukan dengan slowbar lain.** Empat dari lima yang membeli justru menyebut harganya wajar. Pesan marketing jangan bersaing di harga dengan chain. Bedakan dari sisi pengalaman.

## Lampiran: harga GoFood (panel kedua)

- **Panel GoFood:** 0 dari 20 membeli. Rentang yang bisa diterima Rp13.026–28.026, dan median "murah" Rp15.000. Pembeli menghitung Rp22.000 sebagai **Rp30.000–35.000 setelah ongkir dan biaya layanan**.
- **Kontribusi per gelas di GoFood** [Kemungkinan Besar], dengan skema komisi standar 20% + Rp1.000 per produk ([Kontan](https://industri.kontan.co.id/news/gofood-potong-20rp1000-per-produk-terjual-dari-mitra-pelaku-umkm-makin-terjepit); belum ada konfirmasi tarif 2026):

  | Komponen | Rupiah |
  |---|---:|
  | Harga es kopi susu | 22.000 |
  | Komisi GoFood | −5.400 |
  | Bahan, termasuk waste 5% | −8.800 |
  | Cup | −1.600 |
  | **Sisa per gelas** | **±6.200 (28%)** |

  Angka itu belum termasuk promo yang dibutuhkan merchant tanpa rating supaya terlihat.
- **Agar terasa "murah" bagi pembeli GoFood (±Rp15.000), Kopiyo harus menjual di bawah biaya.** GoFood tidak cocok sebagai jalan membangun reputasi; ia hanya cocok sebagai kanal tambahan setelah ada rating dan nama.
