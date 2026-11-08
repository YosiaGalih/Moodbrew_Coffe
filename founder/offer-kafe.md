# Offer: Kopiyo

> Metode: lensa Offers dari `founder-board/lenses.md` (ringkasan kerangka kerja yang dipublikasikan, bukan kata-kata penulisnya). Semua angka dalam Rupiah. Biaya dihitung dengan `unit_economics.py` pada `founder/numbers.json` (model per tamu). Pembeli adalah **simulasi**; angka beli adalah batas atas.

## Ringkasan

| | Pitch v1 (kopi saja) | **Offer v2 (pitch saat ini)** |
|---|---|---|
| Panel 20 orang yang sama (seed 2611) | 5 beli · 15 tidak (**25%**) | 12 beli · 8 tidak (**60%**) |
| Pembelian bulan pertama (total) | 6 | 17 |
| Kontribusi per tamu | ±Rp15.000 (1 gelas) | **Rp23.594** (59%) |
| Break-even | 87 gelas/hari ≈ 67 tamu (di harga Rp23.500) | **56 tamu/hari** |
| Margin di rencana | −10% | **+5%** (60 tamu/hari) |

**Peringatan:** dari 7 pembeli baru, **3 adalah pemburu promo yang hanya datang selama promo 14 hari dan bilang tidak akan kembali** (P002, P003, P012). Jadi angka 60% berisi sekitar 15 poin "pembeli promo". Pembeli yang bertahan diperkirakan sekitar 45%, dan itu masih batas atas.

## 1. Daftar masalah (dengan kata-kata pembeli)

Diambil dari jawaban panel v1 (`founder/panel-v1-kafe/results.md`), panel GoFood, dan keluhan di `founder/competitors.md`.

**Sebelum datang**
1. "Tempat baru, belum ada rating atau review di Google Maps." (trust, panel)
2. "Belum ada yang ngomongin di TikTok/IG." (trend, panel)
3. "Tempat baru biasanya ramai sebentar terus sepi." (panel)
4. "Saya nggak ngerti kopi, takut salah pesan atau merasa bodoh di depan barista." (profil, panel P009)
5. "Kopi hitam itu asam dan pahit, saya nggak suka." (profil)
6. "Rp20 ribu tanpa promo, di chain ada beli 1 gratis 1." (price, panel)
7. "Rp22 ribu terlalu murah untuk single origin, beansnya segar?" (P016)
8. "Sudah punya tempat nongkrong langganan." (habit, panel)
9. "Parkir di Rawamangun susah, jam pulang kerja macet." (panel, kompetitor)
10. "Teman-teman belum tentu mau ke tempat ini." (panel)

**Saat di tempat**

11. "Pulang kerja capek dan lapar, tidak ada info makanan." (alasan menolak nomor satu di v1)
12. "Slowbar pasti lama nunggunya." (panel)
13. "Kadang perlu balas kerjaan sebentar." (larangan laptop, panel)
14. "Nongkrong lama jadi pesan lebih dari satu gelas, lebih mahal dari warkop." (P017)
15. "Saya ke sini untuk ngobrol sama teman, bukan dengar barista jelasin kopi." (P006)
16. Musik keras, gerah. (keluhan kompetitor, tipis)
17. Pelayanan lambat, pesanan tidak datang. (keluhan kompetitor)
18. "Nggak kelihatan cakep buat foto." (P010)
19. Menu membingungkan untuk orang awam. (P009)

**Sesudah**

20. "Kalau kopinya nggak cocok, rugi."
21. Rasa tidak konsisten. (keluhan kompetitor nomor satu)
22. "Apa alasan balik minggu depan?"
23. Ceritanya hilang begitu pulang. (syarat board C2: Coffee Story tanpa AI)

## 2. Solusi: dinilai, dipangkas, ditumpuk

Nilai bagi pembeli 1–5 (5 = sangat bernilai). Biaya 1–5 (5 = mahal), dari angka di `numbers.json`.

| # | Solusi | Menjawab | Nilai | Biaya | Keputusan |
|---|---|---|:-:|:-:|---|
| S1 | Menu makanan pendek "teman ngobrol": roti bakar, pisang goreng, mie, rice bowl (titip dari UMKM lokal) Rp15.000–28.000 | 11, 14 | 5 | 3 | **Ambil, ini inti.** HPP sekitar 38% [estimasi] |
| S2 | Jalur cepat: es kopi susu dari konsentrat siap saji, keluar dalam 3 menit | 12 | 4 | 1 | **Ambil** |
| S3 | Cicip Dulu: 3 tegukan kecil beans aktif, barista bantu pilih dengan 2 pertanyaan | 4, 5, 19 | 4 | 1 | **Ambil** (±Rp300/tamu) |
| S4 | Garansi seduh ulang dengan beans lain | 20, 5 | 4 | 1 | **Ambil** (±Rp171/tamu) |
| S5 | Kartu beans: origin, proses, roastery, tanggal sangrai, catatan rasa; dibawa pulang | 7, 23 | 3 | 1 | **Ambil** (±Rp200/tamu) |
| S6 | Sesi Ngobrol 2–4 orang: teko 2 beans + camilan berbagi, Rp85.000 | 10, 14 | 5 | 2 | **Ambil** |
| S7 | Gelas kedua Rp15.000 di kunjungan yang sama | 14 | 4 | 2 | **Ambil** (menaikkan belanja per tamu) |
| S8 | Reservasi meja lewat WhatsApp | 10 | 3 | 1 | **Ambil** |
| S9 | Aturan "HP boleh, laptop tidak" ditulis jelas | 13 | 3 | 1 | **Ambil** |
| S10 | Barista "baca meja": cerita kopi hanya kalau diminta (kartu di meja dibalik) | 15 | 3 | 1 | **Ambil** |
| S11 | Standar ruang: musik maksimal setara suara ngobrol, ventilasi/AC | 16 | 3 | 2 | **Ambil** (masuk ops) |
| S12 | Resep ditimbang (dosis, rasio, suhu, waktu) untuk setiap gelas | 21 | 4 | 1 | **Ambil** (masuk ops) |
| S13 | Acara mingguan gratis 30 menit ("Kamis Seduh Bareng") | 22, 3 | 3 | 2 | **Ambil** (komunitas, syarat board C7) |
| S14 | Ajak Teman: 14 hari pertama, minuman kedua untuk teman setengah harga | 1, 8, 10 | 4 | 2 | **Ambil** (Rp1,2 jt sekali) |
| S15 | Satu sudut yang dirancang untuk foto | 18, 2 | 3 | 2 | **Ambil** (brief brand) |
| S16 | Info parkir motor jelas, dan lokasi dipilih yang ada parkir | 9 | 4 | 2–4 | **Kriteria lokasi** (ops); tidak dijanjikan di pitch sampai lokasi pasti |
| S17 | Paket Pulang Kerja: es kopi susu + pisang goreng ±Rp30.000 (usulan dari P014 di re-test) | 14, 6 | 4 | 2 | **Uji di pop-up** |
| S18 | Kartu stempel: kunjungan ke-6 V60 gratis | 22 | 3 | 2 | Tunda sampai ada data kunjungan ulang |
| — | Beli-1-gratis-1 / cashback e-wallet permanen | 6 | 3 | 5 | **Buang.** Pemburu promo tidak kembali setelah promo (P002, P003, P012) |
| — | Wifi dan colokan laptop | 13 | 4 | 1 | **Buang.** Bertentangan dengan inti konsep |
| — | Chat AI pemesanan (Customer App MoodBrew) | 4 | 1 | 5 | **Buang** (syarat board C1) |
| — | Bundle GoFood gratis ongkir | — | 2 | 4 | **Buang.** Panel GoFood 0/20 |

## 3. Tumpukan offer

**Nama offer: "Pulang Kerja, Ngopi-yo"**, dengan paket grup "Sesi Ngobrol". Nama perusahaan diputuskan di `/founder-brand`.

- **Inti** (hasilnya, bukan bahannya): *tempat melepas lelah bareng teman sepulang kerja, sampai tengah malam. Kopi diseduh di depan kamu, makanan yang mengenyangkan, dan meja tanpa laptop.*
- **Bonus**, masing-masing mematikan satu keberatan:
  1. **Cicip Dulu** (3 beans, gratis): mematikan "nggak ngerti kopi / takut salah pesan / kopi hitam asam".
  2. **Gelas kedua Rp15.000**: mematikan "nongkrong lama jadi mahal".
  3. **Kartu beans dibawa pulang**: mematikan "beansnya segar?" dan menjadi Coffee Story tanpa AI.
- **Garansi:** *tidak cocok di tegukan pertama, kami seduh ulang dengan beans lain, gratis* (sekali per gelas).
  - Biaya pada asumsi klaim 5% dari V60: **±Rp171 per tamu, ±Rp0,3 juta/bulan** di rencana 60 tamu/hari.
  - Kalau klaim naik ke 20%, biayanya ±Rp685/tamu. Kontribusi turun dari Rp23.594 ke ±Rp23.080 dan break-even tetap sekitar 56–57 tamu/hari. **Garansi ini terjangkau.**
  - Garansi rasa, bukan klaim kesehatan.
- **Urgensi (nyata):** Ajak Teman hanya 14 hari pertama, tanggal berakhir ditulis. **Kelangkaan (nyata):** jumlah meja Sesi Ngobrol yang bisa dipesan pada Jumat–Sabtu malam terbatas oleh jumlah meja fisik.

## 4. Value equation (1–10, makin tinggi makin baik bagi pembeli)

| Unsur | v1 | v2 | Yang menggerakkan |
|---|:-:|:-:|---|
| Dream outcome (lepas lelah bareng teman) | 6 | 8 | Makanan, Sesi Ngobrol, meja tanpa laptop sampai 24.00 |
| Kemungkinan berhasil di mata pembeli | 3 | 5 | Garansi seduh ulang, Cicip Dulu, kartu beans. **Masih rendah, karena tidak ada review. Hanya waktu dan tamu sungguhan yang bisa menaikkannya.** |
| Waktu sampai hasil (makin cepat makin tinggi) | 4 | 7 | Jalur cepat 3 menit, makanan langsung pesan |
| Usaha dan pengorbanan (makin ringan makin tinggi) | 4 | 5 | Reservasi WA, menu untuk orang awam, HP boleh. **Parkir dan macet belum terjawab** (tergantung lokasi) |

## 5. Hasil re-test (panel v2, seed yang sama)

- **Beli: 5 → 12 dari 20** (25% → 60%). **Pembelian bulan pertama: 6 → 17** (rata-rata 1,2 → 1,4 per pembeli).
- **Keberatan yang turun:**
  - **"Capek, lapar, slowbar lama" (convenience): 3 → 0 penolak.** Makanan dan jalur 3 menit bekerja.
  - **"Tanpa promo" (price): 3 → 0 penolak.** Tetapi ketiganya hanya beli karena promo 14 hari.
- **Keberatan yang tidak bergerak:**
  - **Langganan lama (habit): 4.** Termasuk pengikut tren yang menunggu tempat ramai di TikTok.
  - **Belum ada review (trust): 3.**
  - **Laptop (need): 1–2.**

  Ini adalah masalah reputasi, persis yang kamu sebut. Tidak ada offer yang bisa menyelesaikannya; hanya tamu nyata, review nyata, dan waktu.
- **Keraguan baru dari pembeli:**
  - "3 menit" diragukan saat ramai jam 19.00 (P008, P015, P018, P020). Janji ini harus diuji di pop-up.
  - Satu malam dengan makanan bisa Rp40.000–60.000, dibanding warkop sekitar Rp20.000 (P004, P017, P018). Inilah alasan usulan Paket Pulang Kerja Rp30.000 (S17).
  - Roast date lebih dari sebulan atau roastery tidak jelas akan membuat pecinta kopi pergi (P001, P016).

## 6. Biaya tumpukan (dari alat CFO)

Per tamu, rata-rata belanja Rp40.000 [estimasi campuran: minuman pertama Rp23.500, 30% gelas kedua Rp15.000, 60% makanan rata-rata Rp20.000]:

| Biaya variabel per tamu | Rp |
|---|---:|
| Minuman pertama | 8.442 |
| Gelas kedua (30%) | 2.533 |
| Makanan (60%) | 4.560 |
| Cicip Dulu | 300 |
| Garansi seduh ulang | 171 |
| Kartu beans | 200 |
| PPh Final 0,5% | 200 |
| **Total** | **16.406** |
| **Kontribusi** | **23.594 (59%)** |

Ditambah peralatan dapur sederhana Rp8 juta (startup), gas Rp0,4 juta/bulan, dan promo Ajak Teman Rp1,2 juta (sekali).

**Hasilnya:** break-even 56 tamu/hari dari kapasitas sekitar 96 (58% okupansi); margin +5% di 60 tamu/hari. **Tahun 1 tetap rugi sekitar Rp72,9 juta, dan kas yang dibutuhkan sekitar Rp290 juta.** Offer memperbaiki unit economics, tapi biaya tetap (sewa Rp12,5 juta + 3 staf Rp20,4 juta) masih terlalu berat untuk tahun pertama. Ini tugas `/founder-cfo`.
