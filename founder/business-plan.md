# Lapak Yok (nama kerja; dulu "Kopiyo") · Business plan

**Verdict: Not yet**

> **Catatan pembaca (rencana v3, Lapak Yok):**
> - Semua uang dalam **Rupiah**. Alat mencetak `$`, jadi `$29000.00` = Rp29.000.
> - Semua bagian di bawah sudah untuk **format lapak malam**. Dokumen versi kafe/ruko disimpan sebagai `*-kafe.md` dan `cfo-ruko.md`. Rencana induknya ada di [`lapak-malam.md`](lapak-malam.md).
> - **Jalan ke untung** (`cfo.md`): penghematan dari tuan rumah ditambah belanja ≥Rp32.000/tamu memberi break-even 18 tamu/malam dan tahun 1 +Rp13,2 juta.
> - Panel adalah **pembeli simulasi** yang melihat pitch lapak, dan semua angka keuangan adalah **proyeksi**. Ini bukan nasihat keuangan, hukum, atau pajak.

- ✓ Each tamu (rata-rata belanja per kunjungan) earns $13733.00 before fixed costs (47% contribution).
- ✗ Year 1 operating LOSS: $11,799,523.
- ✓ Break-even is 26 tamu (rata-rata belanja per kunjungan)s a day against a capacity of 30.
- ✓ 10 of 20 simulated buyers buy (50%, the bar is 25%).

| key number | |
| --- | ---: |
| Price | $29000.00 a tamu (rata-rata belanja per kunjungan) |
| Profit margin at plan | 4% per tamu (rata-rata belanja per kunjungan) |
| Break-even | 26 tamu (rata-rata belanja per kunjungan)s a day |
| Year 1 operating profit | $-11,799,523 |
| Startup spend | $20,520,000 |
| Cash needed before it pays for itself | $33,833,772 |
| Startup money earned back | not in year 1 |
| Buyer panel | 10 buy · 10 pass |

## The idea

- **Apa ini:** kedai kopi model *slowbar* yang menjual pengalaman menikmati kopi (diseduh pelan, ngobrol dengan barista dan teman), sengaja **bukan** tempat kerja: tempat untuk ngobrol, santai, dan melepas lelah.
- **Untuk siapa:** orang yang lelah setelah bekerja dan ingin tempat berkumpul dengan teman untuk ngopi dan bercerita. Usia, pendapatan, dan pekerjaan yang lebih spesifik belum ditentukan founder.
- **Apa yang dijual, dengan harga berapa:** kopi seduh slowbar (manual brew) plus pengalamannya. Founder ingin harganya "tidak terlalu mahal" supaya orang bisa merasakan pengalaman kopi secara penuh. **Angka harga per cangkir belum ditentukan** (akan diuji oleh panel konsumen dan modul pricing).
- **Di mana dan bagaimana:** Rawamangun, Jakarta Timur, sebagai lokasi pertama. Yogyakarta disebut sebagai kemungkinan lokasi lain. Penjualan offline (dine-in) di kedai. Cara pelanggan menemukan kedai belum ditentukan.
- **Anggaran dan batasan:**
  - Anggaran modal **belum disebutkan** founder; CFO yang akan menghitung kebutuhannya.
  - Founder berencana membangun aplikasi AI (PRD "MoodBrew AI": AI Coffee Companion + POS + inventori + HPP + pricing + AI Business Copilot) sebagai **alat internal Kopiyo saja**, bukan produk yang dijual ke kedai lain.
  - Sudah diputuskan: tidak melayani orang yang datang untuk bekerja (bukan coworking/WFC).
  - **Ditambahkan founder setelah board (8 Nov 2026):** "Saya belum punya reputasi. Jadi saya berniat membangun rasa kopi ini dari model takeaway dari GoFood." Artinya ada **Fase 1: takeaway/delivery lewat GoFood** untuk membangun reputasi rasa, sebelum (atau sebagai jalan menuju) slowbar fisik. Lokasi dapur Fase 1, menu, dan harganya belum ditentukan.

### Pembaruan dari founder (8 Nov 2026, setelah business plan v1)

Founder menjawab pertanyaan CFO dan memberi batasan baru:

1. **Waktu:** founder masih bekerja kantor pukul 07.30–17.30, jadi hanya bisa membuka usaha **malam hari, sekitar 18.00–24.00**.
2. **Alat dan format:** founder **sudah punya alat slowbar manual lengkap, tanpa listrik.** Kalau menyewa kios tidak memungkinkan, jangan dipaksakan. Founder bersedia berjualan di pinggir jalan dengan konsep **angkringan tenda**, atau kios kecil di tempat yang sepi yang mendukung slowbar, atau mengontrak tempat.
3. **Nama:** dibangun dari ajakan pekerja kantoran yang capek: **"Yok nongkrong" / "Yok ngopi"**, untuk meredakan penat.
4. **Lokasi:** Rawamangun, Jakarta. Founder minta dicarikan tempat strategis di pinggir jalan atau kios kecil yang sewanya tidak mahal.
5. **Yogyakarta:** founder minta dibuatkan opsi berjualan di Jogja.

Konsekuensinya, rencana ruko + 3 staf (`numbers.json` versi v1/v2) diganti oleh **format lapak/kios malam yang dijalankan founder**. Lihat `lapak-malam.md`.

## Summary

**Verdict: Not yet** (dihitung oleh `compile.py` dari `numbers.json`). Dengan biaya nyata menjalankan lapak tanpa listrik (`ops.md`), tahun 1 rugi **Rp11,8 juta**. Uang yang dipertaruhkan kecil (kas ±Rp34 juta), tetapi angkanya belum masuk.

### Yang harus berubah supaya angka masuk

1. **Perjanjian tuan rumah yang menanggung air/galon dan tempat titip gerobak.** Ditambah helper hanya 18.00–23.30. Biaya tetap turun dari Rp5,98 juta ke Rp4,99 juta, break-even dari 26 ke 22, dan tahun 1 menjadi sekitar impas (+Rp0,1 juta). → `ops.md`, `launch.md` (D4)
2. **Belanja per tamu ≥Rp32.000** lewat paket, gelas kedua Rp12.000, dan makanan. **Bukan dengan menaikkan atau menurunkan harga V60.** Digabung dengan poin 1: break-even 18, tahun 1 +Rp13,2 juta. → `offer.md`, `pricing.md`
3. **Buktikan keduanya dalam 8 minggu** (9 Des 2026–2 Feb 2027), dengan ambang yang tidak diturunkan. → `launch.md`

### Apa ini dan untuk siapa

Lapak malam slowbar bergaya angkringan, tanpa listrik, di teras beratap milik orang lain (dengan izin tertulis) di Rawamangun. Buka Rabu–Sabtu malam, dijalankan founder sepulang kerja kantor, dengan helper Jumat–Sabtu. Targetnya geng yang rutin nongkrong sepulang kerja, mahasiswa/fresh graduate, dan pecinta kopi: *"Pulang kerja, yok nongkrong dulu."*

### Tiga angka di balik verdict

| Angka | Rencana (biaya nyata) | Hemat + belanja Rp32.000 |
|---|---:|---:|
| Margin di 28 tamu/malam | **+4,0%** | +19,5% |
| Break-even | **26 tamu/malam** (kapasitas ±30) | 18 |
| Tahun 1 (operasional) | **−Rp11,8 juta** | +Rp13,2 juta |

### Panel dan board

- **Board rapat kedua:** 3 FUND IF, rata-rata 5,3/10 (naik dari 3,7). Syaratnya ada di `board.md` (D1–D11).
- **Panel simulasi pitch lapak:** 10/20 beli (sekitar 35% tanpa pemburu promo).
  - Yang membeli: semua mahasiswa, semua yang rutin nongkrong, dan semua pecinta kopi.
  - 0% beli: pengikut tren TikTok, pembaca review, dan yang loyal ke tempat langganan.
- **Sepakat:** masalah intinya adalah reputasi dan distribusi; jangan memimpin dengan harga; tempat pinjaman dan musim hujan adalah risiko.
- **Board berbeda pendapat:** Offers ingin paket untuk menaikkan belanja, Product ingin menu malam solo dipangkas. Keduanya diakomodasi: paket memakai makanan siap saji, dan menu lengkap hanya Jumat–Sabtu.
- **Panel adalah pembeli simulasi, dan semua angka adalah proyeksi.** Ini bukan nasihat keuangan, hukum, atau pajak.

### Risiko terbesar dan penanganannya

1. **Kelelahan founder.** `ops.md` memperkirakan sekitar 85–90 jam kerja per minggu. **Aturan:** jika dua minggu berturut-turut tidur kurang dari 6 jam atau pekerjaan kantor terganggu, tutup Rabu.
2. **Tempat dan hujan.** Hanya pilih teras beratap dengan perjanjian tertulis (minimal 6 bulan, eksklusif kopi malam). Trotoar dilarang (Perda DKI 8/2007).
3. **Jumlah tamu.** Dengan penghematan, tamu −30% membuat tahun 1 rugi Rp17,9 juta. Ambang GO di review 2 Feb: **≥26 tamu bayar/malam**, atau ≥22 jika penghematan tuan rumah tercatat.

### Yang dibutuhkan untuk mulai

- **Kas sekitar Rp34 juta:** startup Rp20,5 juta ditambah kerugian bulan-bulan awal. Versi hemat sekitar Rp27,5 juta. **Alat seduh sudah dimiliki.**
- **Malam pertama Rabu 9 Desember 2026**, jika tempat, helper, dan status halal sudah jelas.
- **Jogja: nanti.** Dengan operator berbayar, tahun 1 rugi sekitar Rp22,9 juta.

### Satu hal minggu ini

**Survei malam Jl. Balai Pustaka (Rabu–Sabtu, 19.00–22.00) dan tanya 4–6 pemilik teras beratap apakah bersedia menulis dalam perjanjian:** air/galon, toilet, titip gerobak, jangka 6 bulan, dan eksklusif kopi malam. Jawaban mereka menentukan apakah angka ini masuk. Pada hari yang sama, cek "Lapak Yok" di [PDKI](https://pdki-indonesia.dgip.go.id).

## What the board said

**Vote: 2 PASS, 1 FUND IF. Skor rata-rata 3,7/10** (Offers 3, Monopoly 3, Product 5)

Memo lengkap: [offers](board/offers.md) · [monopoly](board/monopoly.md) · [product](board/product.md) · [brief](board/brief.md)

Ini menilai rencana **seperti yang ditulis sekarang**: slowbar murah ditambah pembangunan aplikasi MoodBrew AI lengkap. Ketiga anggota melihat inti yang layak ("tempat ngobrol, bukan tempat kerja"), tetapi dua menolak rencananya.

### Risiko yang diangkat lebih dari satu anggota

1. **Aplikasi AI melawan produknya sendiri dan menghabiskan modal sebelum ada pelanggan.** (3 dari 3 anggota)
   - Customer App P0 menaruh layar di antara tamu dan barista. Yang dijual adalah percakapan dengan barista, dan aplikasi justru mengotomatiskan percakapan itu.
   - Cakupan PRD (app, POS, inventori, HPP, procurement, BI, copilot, multi-outlet, "mitra integrasi") adalah perusahaan software. PRD sendiri mencatat cakupannya terlalu luas.
   - Untuk satu outlet, tidak ada keunggulan yang tidak bisa dibeli kompetitor dalam bentuk POS siap pakai.
2. **Bersaing di harga dengan model yang mahal dijalankan.** (3 dari 3)
   - Seduhan manual itu lambat dan butuh banyak tenaga. Tamu yang datang untuk ngobrol duduk lama. Ditambah harga "tidak terlalu mahal", margin bisa habis.
   - Kalau angkanya tidak tertutup, kedai akan memangkas waktu seduh dan waktu ngobrol, artinya memangkas produknya sendiri.
3. **Belum ada segmen yang bisa dijangkau dan belum ada rencana distribusi.** (Offers, Monopoly)
   - "Orang lelah kerja" berarti hampir semua orang. Belum jelas dari mana 100 pelanggan pertama datang, dan berapa biayanya.
4. **Belum ada bukti, tim, atau barista.** (3 dari 3)
   - Slowbar hidup-mati di tangan barista, dan belum ada nama. Pengalaman founder di F&B belum tercatat.
5. **Yogyakarta mengaburkan fokus.** (3 dari 3) Semua anggota meminta Yogyakarta dihapus sampai Rawamangun untung.

### Di mana anggota berbeda pendapat

- **Lensa Product (FUND IF, 5)** melihat satu hal yang jelas dan bisa dirancang dengan baik: kopi diseduh pelan sambil ngobrol, dengan keberanian bilang "bukan tempat kerja". Masalahnya ada pada eksekusi (aplikasi, cakupan), bukan pada konsep.
- **Lensa Monopoly (PASS, 3)** tidak melihat keunggulan yang bertahan. Siapa pun bisa memasang tulisan "no laptop" dan merekrut barista ramah. Satu-satunya moat yang realistis adalah komunitas lokal dan brand, dan itu belum ada rencananya.
- **Lensa Offers (PASS, 3)** menilai pasarnya belum dipilih dan penawarannya komoditas ("lebih murah"). Lensa ini mau berubah jika harga dibenarkan oleh stack (paket grup, seduhan yang dipandu, garansi), bukan oleh label murah.

### Syarat gabungan (checklist untuk tahap berikutnya)

Diuji oleh skill yang disebut di kurung.

- [ ] **C1. Bekukan MoodBrew AI.** Buka dengan POS siap pakai (QRIS) dan spreadsheet HPP. Hapus Customer App dari peluncuran: memesan dilakukan lewat percakapan dengan barista. Bangun software hanya setelah ada data operasi nyata dan satu masalah spesifik yang terbukti mahal. (`/founder-cfo`, `/founder-ops`)
- [ ] **C2. Coffee Story tanpa AI.** Kartu cetak per beans, atau halaman QR statis, ditambah cerita langsung dari barista. (`/founder-offer`, `/founder-brand`)
- [ ] **C3. Pilih satu segmen** dengan daya beli terukur dan satu kanal untuk menjangkaunya. (`/founder-consumer`, `/founder-marketing`)
- [ ] **C4. Harga dari angka, bukan dari "tidak terlalu mahal".** Harga harus menutup biaya tenaga seduh dan lama duduk tamu yang realistis. (`/founder-pricing`, `/founder-cfo`)
- [ ] **C5. Ganti pembeda "murah" dengan stack** yang membuat harga terasa layak. Contohnya paket ngobrol 2–4 orang, seduhan dipandu barista, meja bebas laptop yang dijamin, reservasi grup, dan garansi seduh ulang. (`/founder-offer`)
- [ ] **C6. Celah nyata di peta kompetitor:** tidak ada tempat "ngobrol tanpa laptop, barista yang dikenal" dalam jangkauan pelanggan yang sama. (`/founder-competitors`)
- [ ] **C7. Rencana 100 pelanggan pertama beserta biayanya.** Diferensiasi dibangun lewat komunitas (acara rutin, pelanggan tetap), bukan harga. (`/founder-marketing`)
- [ ] **C8. Uji nyata sebelum menandatangani sewa atau fit-out penuh:** pop-up atau pre-sale dengan harga sungguhan, dan bukti orang kembali. (`/founder-launch`)
- [ ] **C9. Naskah "lima menit pertama"** (tiga teman masuk pukul 19.30), lalu kerjakan mundur: barista, menu pendek, kursi, cahaya, musik, jam buka, cara menolak laptop dengan sopan. (`/founder-ops`, `/founder-brand`)
- [ ] **C10. Tim:** siapa barista utamanya, dan apa pengalaman F&B founder. (`/founder-ops`)
- [ ] **C11. Yogyakarta keluar dari rencana** sampai Rawamangun menghasilkan untung. (`/founder-plan`)

### Catatan setelah rapat: Fase 1 GoFood (belum dinilai board)

Setelah rapat, founder menambahkan rencana membangun reputasi rasa lewat takeaway di GoFood sebelum membuka slowbar. Board belum menilai rencana ini. Ketua mencatat tiga syarat yang tersentuh langsung:

- **C4/C5 (jangan bersaing di harga):** kategori kopi di GoFood adalah arena yang paling digerakkan promo.
- **C8 (uji nyata):** GoFood memang uji nyata, tetapi yang diuji adalah kopi yang diantar, bukan pengalaman slowbar.
- **C7 (100 pelanggan pertama):** GoFood tidak memberi kontak pelanggan.

CFO memodelkan Fase 1 sebagai skenario terpisah, dan `/founder-launch` membandingkannya dengan uji pop-up.

### Versi terkuat yang bisa dilihat board

**Ini berbeda dari yang dipitch.** Kopiyo yang paling kuat bukan "slowbar murah dengan aplikasi AI". Kopiyo yang paling kuat adalah **ruang ngobrol sepulang kerja di Rawamangun**: tanpa laptop dan tanpa layar, dengan barista sebagai tuan rumah yang mengenal tamunya. Yang dijual adalah *sesi*, bukan cangkir: paket untuk 2–4 orang dengan beberapa seduhan untuk dicicipi bersama, cerita beans yang diceritakan barista dan dibawa pulang sebagai kartu, dan meja yang dijamin bebas laptop. Harganya terasa adil karena dibagi bersama, bukan karena murah. Kedai mungkin hanya perlu buka sore sampai malam, saat pelanggan targetnya ada; CFO harus mengujinya. Moat-nya hanya bisa komunitas: pelanggan tetap, acara rutin, dan barista yang dikenal namanya. Aplikasi AI tidak membangun moat itu. MoodBrew sebaiknya disimpan sebagai proyek tahun kedua, dan itu pun hanya bagian back-office (HPP, stok) jika data menunjukkan masalahnya nyata.

---

## Rapat kedua: Rencana v3 "Lapak Malam" (8 Nov 2026)

**Vote: 3 FUND IF, 0 PASS. Skor rata-rata 5,3/10** (Offers 5, Monopoly 5, Product 6). Naik dari 3,7.

Memo lengkap: [v3-offers](board/v3-offers.md) · [v3-monopoly](board/v3-monopoly.md) · [v3-product](board/v3-product.md) · [brief-v3](board/brief-v3.md)

Skor naik karena taruhan turun dari Rp300 juta lebih ke sekitar Rp25–34 juta, aplikasi dibekukan, Jogja ditunda, dan rencana menguji dirinya dengan angka tertulis. Skor tidak lebih tinggi karena tiga hal: belum ada bukti pembeli nyata, hambatan tiru nol, dan pengalaman di malam solo belum dirancang.

### Risiko yang diangkat lebih dari satu anggota

1. **Jangkar harga turun ke warkop.** (Offers, Monopoly) Di tenda, V60 Rp22.000 dibandingkan dengan kopi angkringan Rp5.000–8.000. Laba bertumpu pada belanja sekitar Rp28.000/tamu yang masih tebakan; di Rp24.000, break-even naik ke 29 tamu.
2. **Tempat pinjaman dan musim hujan.** (3 dari 3) Teras orang bisa ditarik kembali, dan uji 9 Des–2 Feb jatuh di musim hujan. Atap, toilet, dan air belum jelas.
3. **Satu orang, sekitar 75 jam/minggu.** (Monopoly, Product) Pada malam solo Rabu–Kamis, "pelan" bisa berubah menjadi "lama menunggu".
4. **Tidak ada yang menghalangi peniru.** (Monopoly, Offers) Hulu, YO'KOPI, dan angkringan sebelah bisa menambah V60. Pertahanannya hanya pelanggan tetap dan komunitas.

### Di mana anggota berbeda

- **Offers** ingin **satu paket** yang menaikkan belanja ke ≥Rp30.000.
- **Product** ingin **menu dipangkas** di malam solo: tanpa roti bakar dan sate, makanan siap saji.

Keduanya bisa didamaikan: paket memakai makanan siap saji, dan menu lengkap hanya pada Jumat–Sabtu ketika ada helper (lihat `offer.md` v3).

### Syarat gabungan rapat kedua (checklist)

- [ ] **D1. Satu paket inti sebelum 9 Des** dengan target belanja rata-rata ≥Rp30.000. → `offer.md`, `cfo.md`
- [ ] **D2. Pangkas menu malam solo.** Dua beans V60, es kopi susu dari konsentrat, tubruk, dan makanan siap saji. Jangan menerima tamu sebelum lampu, kursi, dan air panas siap. Jika pemasangan solo lewat 19.00, Rabu–Kamis buka 19.30 dan jam itu yang ditulis. → `ops.md`
- [ ] **D3. Naskah lima menit untuk satu orang**, diuji dengan stopwatch: tamu disapa ≤10 detik, minuman atau tegukan di tangan ≤5 menit, waktu tunggu V60 disebut sebelum bayar. → `ops.md`
- [ ] **D4. Perjanjian tempat tertulis:** atap atau rencana hujan, toilet, air, titip gerobak, jangka minimal 6 bulan, dan klausul eksklusif kopi malam. → `ops.md`
- [ ] **D5. Petakan pesaing malam per titik** (jarak jalan kaki, 19.00–24.00) dan verifikasi lokasi YO'KOPI sebelum mengunci tempat. → survei founder
- [ ] **D6. Satu segmen dan satu kanal untuk titik pertama.** Pekerja pulang di Balai Pustaka, atau mahasiswa di depan UNJ. → `marketing.md`
- [ ] **D7. Nama dicek di PDKI sebelum posting publik.** → `brand.md`
- [x] **D8. Panel format lapak dibaca sebelum malam pertama.** Hasil: 10/20 beli, rentang harga Rp10.067–27.000. → `panel/results.md`, `pricing.md`
- [ ] **D9. Review 2 Feb 2027, ambangnya tidak diturunkan.**
  - Ambang dasar: ≥21 tamu bayar/malam, belanja ≥Rp28.000, ≥25% kembali dalam 14 hari.
  - Kepemilikan pasar: ≥40 pelanggan tetap (≥2 kunjungan dalam 30 hari), ≥30% datang karena diajak teman, satu malam ritual tetap, dan satu komunitas yang kumpul rutin.
  - Pengalaman: jika >20% tamu malam solo menunggu minuman pertama >10 menit, tambah helper Kamis atau tutup Kamis.
  - Malam hujan dicatat terpisah.
- [ ] **D10. Jangan memimpin dengan harga.** Tubruk adalah pintu masuk, bukan headline. Jika belanja turun ke Rp24.000, perbaiki offer sebelum menambah malam.
- [ ] **D11. Kios dan Jogja tetap beku** sampai D9 terpenuhi dan usaha untung 3 bulan berturut-turut.

### Versi terkuat menurut board (rapat kedua)

**Slowbar berbentuk lapak, bukan angkringan yang kebetulan menyeduh kopi.** Kopi adalah alasan datang, makanan adalah alasan bertahan.

- **Satu titik beratap** dengan perjanjian tertulis.
- **Malam solo:** menu pendek yang bisa disajikan satu orang tanpa membuat tamu menunggu.
- **Jumat–Sabtu:** menu lengkap dan satu "malam ritual" yang membangun komunitas.
- **Pertahanannya bukan harga, melainkan orang:** 40 pelanggan tetap yang mengajak teman, sebelum ada yang meniru.

## The competition

Tanggal riset: 8 November 2026 · Data mentah: [`competitors.csv`](competitors.csv)

### Ringkasan

- **Ada 10 kompetitor dan 5 substitusi.** Kompetitor terdiri dari 5 Direct dan 5 Indirect, semuanya di Rawamangun atau Kayu Putih (Kec. Pulo Gadung). Hanya **satu** tempat yang secara publik disebut *slow bar*, yaitu **Psswrd Coffee** di Kayu Putih. Di tempat lain, manual brew hanya menu sampingan.
- **Harga manual brew yang terverifikasi: Rp20.000 sampai Rp40.000, median Rp27.500.** Angka ini berasal dari 4 harga, dan sebagian besar datanya dari 2022–2023.
- **Polanya paling jelas di sini: kafe di Rawamangun menjual diri sebagai tempat kerja (WFC).** Ada lebih dari 10 tempat yang dipromosikan untuk kerja atau nugas, termasuk yang ratingnya paling tinggi (Pukul Satu Kopi, 4.9 dari 1.556 ulasan Google). Tidak satu pun yang mengklaim posisi "tempat ngobrol, bukan tempat kerja".
- **Celahnya ada, tetapi sempit.** Yang belum diambil siapa pun adalah gabungan slowbar, jam buka sesudah jam kerja, aturan tanpa laptop, dan harga di bawah median. Kompetitor yang paling dekat ke posisi ini adalah **Hulu Coffee**. Belum ada bukti bahwa permintaan untuk konsep tanpa-WFC memang ada.

> **Catatan metode:** Halaman web tidak bisa dibuka langsung, karena WebFetch diblokir jaringan sesi untuk orami.co.id dan beritajakarta.id, lalu saya berhenti mencoba situs lain. **Semua fakta di bawah ini diambil dari cuplikan hasil pencarian** (WebSearch), dengan tautan ke halaman sumbernya. Kutipan ditulis persis seperti di cuplikan, tetapi belum dicocokkan dengan teks lengkap halamannya. Rating Google Maps diambil dari situs agregator (RestaurantGuru, Wanderlog, Horego, magicpin), bukan dari Google Maps langsung.

---

### 1. Tabel kompetitor (urut dari yang paling langsung bersaing)

| # | Nama | Tipe | Lokasi | Harga item sebanding | Yang dijual / catatan | Rating (jumlah ulasan) |
|---|---|---|---|---|---|---|
| 1 | [Psswrd Coffee](https://food.detik.com/info-kuliner/d-7728410/slurrp-10-slow-bar-di-jabodetabek-punya-racikan-kopi-segar) | Direct | Jl. Kayu Putih Raya 20, Pulo Gadung | tidak terverifikasi | Slow bar + roastery, menjual biji kopi. Menyebut diri "coffee studio", bukan kafe | – |
| 2 | [Hulu Coffee](https://www.instagram.com/hulu.coffee/) | Direct | Jl. Sunan Sedayu 8C2, Rawamangun | tidak terverifikasi (manual brew ada di menu) | Manual brew, espresso, donat kentang. Ada board game dan buku ([Kompasiana](https://www.kompasiana.com/naura1568/68f898c2c925c46673352492/kafe-nyaman-di-rawamangun)). Buka sampai tengah malam | 4.8 (15, [MenuKuliner](https://menukuliner.net/menu/340802/hulu-coffee-rawamangun)) |
| 3 | [Kedai/Toko Kopi Bemo](https://poskota.co/megapolitan/sasar-bapak-bapak-yang-antar-istri-belanja-pasar-rawamangun-hadirkan-kedai-kopi-bemo/) | Direct | Lt. dasar Pasar Rawamangun | tidak terverifikasi (minuman mulai Rp8.000, [detikFood](https://food.detik.com/tempat-makan/d-8437268/5-coffee-shop-enak-di-rawamangun-ada-yang-sudah-bertahan-60-tahun)) | Toko biji kopi sejak 1965, cicip gratis, sekitar 20 varian di kedai ([Harnas, Jan 2026](https://harnas.co.id/2026/01/tak-sekadar-tren-kedai-kopi-bemo-rawamangun-tawarkan-vibes-ngopi-asyik-dengan-menu-ramah-kantong/)). Jam buka toko 06.00–16.00 ([Pos News, Sep 2025](https://www.posnews.co.id/nikmati-kopi-legendaris-kopi-bemo-di-pasar-rawamangun-jakarta-timur/)) | – |
| 4 | [Kalea Coffee & Space](https://www.yummyadvisor.id/jakarta-timur/restoran-kalea-coffee-and-space-pinang-raya-jakarta-timur/menu/) | Direct | Jl. Pinang Raya 10, Rawamangun | **Rp40.000** (V60, menu 2022–2023) | V60, Japanese, Vietnam drip ([Horego](https://guide.horego.com/coffee-shop-rawamangun-tercozy/)). Indoor-outdoor | 4.7 (140 Google, [RestaurantGuru](https://restaurantguru.com/KALEA-Coffee-and-Space-East-Jakarta)) |
| 5 | [Anastomosis Coffee](https://www.carikulinerindonesia.com/15161102/anastomosis-coffee-kayu-putih) | Direct | Jl. Pondasi 50C, Kayu Putih | **Rp26.000** (V60, listing sekitar 3 tahun lalu) | Sejak 2010. V60, Vietnam drip, tubruk, French press, makanan | 4.0 (8, [TripAdvisor](https://www.tripadvisor.com/Restaurant_Review-g294229-d5552697-Reviews-Anastomosis_Coffee-Jakarta_Java.html)) |
| 6 | [Kopi Nako Rawamangun](https://www.kompas.com/food/read/2024/06/04/204056475/5-kafe-di-rawamangun-di-jakarta-timur-ada-yang-cocok-buat-kerja) | Indirect | Jl. Perserikatan, seberang Terminal Rawamangun | **Rp29.000** (V60 single origin, harga jaringan cabang [Kalisari](https://menukuliner.net/menu/383182/kopi-nako-kalisari)/[Ciracas](https://menukuliner.net/menu/383178/kopi-nako-ciracas) 2026) | Kopi susu, manual brew, makanan rumahan. Outdoor berpohon. Menu Rp19.000–59.000 | 4.4 (sekitar 400, [Horego](https://www.horego.com/pulo-gadung/kopi-nako-rawamangun)) |
| 7 | [Jung Coffee](https://megapolitan.kompas.com/read/2022/08/06/01150031/9-tempat-ngopi-di-rawamangun) | Indirect | Jl. Rawamangun Muka Barat, dekat UNJ | **Rp20.000** (Japanese Style Coffee, Kompas Agu 2022) | Kopi susu dan camilan murah. Wifi dan stop kontak. Tempat nugas mahasiswa | – |
| 8 | [Pukul Satu Kopi Rawamangun](https://restaurantguru.com/Pukul-Satu-Kopi-Rawamangun-East-Jakarta) | Indirect | Jl. Waru 20C, Rawamangun | tidak terverifikasi (hero: Kopi Susu PSK Rp18.000/23.000, Kompas 2022) | Kopi susu, dessert, makanan Jepang. Banyak colokan. Buka sampai 24.00 | **4.9 (1.556 Google)** |
| 9 | [Glasmacher (Glas) Coffee](https://wanderlog.com/place/details/13904546/glasmacher-coffee-rawamangun) | Indirect | Jl. Kedondong 16B, Rawamangun | tidak terverifikasi (rentang menu Rp22.000–56.000, [Kompas 2024](https://www.kompas.com/food/read/2024/06/04/204056475/5-kafe-di-rawamangun-di-jakarta-timur-ada-yang-cocok-buat-kerja)) | Kopi susu gula aren, makanan. Live music akhir pekan. WFC | 4.7 (524, Wanderlog) |
| 10 | [Kopi Kenangan Ruko Pisangan](https://magicpin.com/indonesia/Jakarta/Rawamangun/Restaurant/Kopi-Kenangan-Ruko-Pisangan/store/2056751) | Indirect | Pisangan, Pulo Gadung | Rp18.000 (Kopi Kenangan Mantan reguler, harga gerai Jogja, [Mojok Nov 2025](https://mojok.co/pojokan/3-menu-kopi-susu-paling-faforit-dan-laris-di-kopi-kenangan-jogja/)) | Kopi susu grab-and-go dari jaringan nasional | 4.4 (45, magicpin) |
| S1 | [Warkop/kopi pinggir jalan](https://www.babelinsight.id/pekerja-jakarta-warkop-tanggal-tua) | Substitute | mis. Warkop Pemuda, Jl. Pemuda ([Kompasiana](https://www.kompasiana.com/muhammad110706/681d81c3ed641530ef2a7102/ngopi-di-pinggir-jalan-pemuda-catatan-dari-rawamangun)) | Rp5.000 (contoh warkop di Jakarta, bukan Rawamangun) | Kopi sachet/tubruk, gorengan, ngobrol sampai malam | – |
| S2 | [Kopi minimarket](https://shopee.co.id/inspirasi-shopee/menu-point-coffee/) | Substitute | Point Coffee, FamilyMart Sunan Giri | Rp20.000–25.000 (Americano Point Coffee) | Kopi mesin dan kursi di minimarket | – |
| S3 | [Seduh sendiri di rumah](https://www.ruparupa.com/p/hario-coffee-dripper-01-v60-transparan.html) | Substitute | Rumah/kos | Dripper V60 Rp109.900 + biji Rp58.000–350.000 ([Jakarta Post 2022](https://www.thejakartapost.com/culture/2022/12/13/twenties-jakartas-roasteries-for-getting-your-caffeine-jolt.html)) | Kopi enak tanpa suasana dan tanpa barista | – |
| S4 | [Pesan antar](https://gofood.co.id/jakarta/restaurant/hulu-coffee-rawamangun-d9d8460e-d030-4228-ad07-228f36dd6b63) | Substitute | GoFood/GrabFood | tidak terverifikasi untuk V60 (menu Hulu di GoFood Rp16.000–40.000) | Kopi diantar, tanpa pengalaman tempat | – |
| S5 | [Mal dan fast food](https://mojok.co/terminal/rawamangun-daerah-paling-unggul-di-jakarta-timur/) | Substitute | Mall Arion, McD Pemuda | tidak terverifikasi | Tempat duduk ber-AC dan murah | – |

**Juga ditemukan, tapi tidak dimasukkan ke tabel** (datanya kurang atau statusnya tidak jelas):
- Monarki Coffee, Jl. Pondasi 15: V60 Rp36.500 ([carikuliner](https://www.carikulinerindonesia.com/15137494/monarki-coffee-rawamangun), sekitar 1.000 hari lalu). Halaman "review" Monarki lainnya tampak dibuat otomatis, jadi saya abaikan.
- Noesantara Coffee & Culinary, Jl. Tawes 21: kopi Gayo specialty ([Wahana Honda blog](https://www.wahanahonda.com/blog/noesantara-coffee-culinary-hidden-gem-di-rawamangun-yang-nggak-jual-kopi-generik)). Klaim "slow bar" tidak terkonfirmasi.
- Fore Coffee Paus ([Lemon8: "...Spot Nyaman untuk Nikmati Kopi Favorit dan WFH"](https://www.lemon8-app.com/@sabrinafitrianti/7419908849194353168?region=id)).
- Tempat lain: Kopi Peron, Meet/N/Work Coffee & Eatery, Atme Coffee (buka 2025), Arah Coffee, Takana, Double V, P8 Cafe, dan Kedai Locale (pernah menyajikan manual brew menurut [Hipwee](https://www.hipwee.com/list/5-restoran-hits-di-rawamangun-yang-wajib-kamu-coba/), status terkini tidak jelas).
- Upnormal Coffee Roasters Rawamangun ([TripAdvisor](https://www.tripadvisor.com/Restaurant_Review-g294229-d14168067-Reviews-Upnormal_Coffee_Roasters_Rawamangun-Jakarta_Java.html)): status buka tidak terverifikasi.

---

### 2. Rentang harga item sebanding (manual brew / V60)

Saya hanya memakai harga terverifikasi yang ada di tabel, yaitu **4 harga**:

| Tempat | Harga | Item | Tahun data |
|---|---|---|---|
| Jung Coffee | Rp20.000 | Japanese Style Coffee | 2022 |
| Anastomosis Coffee | Rp26.000 | V60 | sekitar 2023 |
| Kopi Nako (harga jaringan) | Rp29.000 | V60 single origin | 2025–2026 |
| Kalea Coffee & Space | Rp40.000 | V60 | 2022–2023 |

- **Terendah: Rp20.000 · Median: Rp27.500 · Tertinggi: Rp40.000** (n = 4).
- Jika harga jaringan Kopi Nako dikeluarkan (karena bukan harga cabang Rawamangun), medianya menjadi **Rp26.000** (n = 3).
- Data di luar tabel tidak mengubah rentang: Monarki Rp36.500, dan Pukul Satu cabang **Bekasi** Rp35.000 ([opaper](https://www.opaper.app/pukul_satu_kopi)). Kalau Monarki ikut dihitung, median dari 5 harga menjadi Rp29.000.
- Pembanding substitusi: warkop **Rp5.000**, Kopi Kenangan Mantan **Rp18.000**, Americano Point Coffee **Rp20.000–25.000**. Sebagai patokan harga premium di luar area: V60 Tanamera Pacific Place **Rp55.680** di Grab ([GrabFood](https://food.grab.com/id/en/restaurant/tanamera-coffee-one-pacific-place-delivery/IDGFSTI00001y07)).
- **Hati-hati:** 3 dari 4 harga berasal dari 2022–2023, dan sebagian adalah harga aplikasi pesan-antar, yang biasanya lebih mahal daripada harga dine-in. Harga sekarang kemungkinan sudah naik.

**Artinya untuk Kopiyo:** "tidak terlalu mahal" berarti V60 di sekitar **Rp20.000–27.500**, yaitu di bawah median. Tetapi Jung (Rp20.000) dan Anastomosis (Rp26.000) sudah berada di kisaran itu. **Harga murah saja tidak cukup untuk membedakan Kopiyo.**

---

### 3. Peta posisi

Saya memilih dua sumbu yang didukung bukti:
- **Horizontal:** kopi sebagai *bahan bakar* (kopi susu, grab-and-go) ↔ kopi sebagai *ritual/keahlian seduh* (manual brew, slow bar).
- **Vertikal:** ruang yang dibangun untuk *kerja/WFC* (colokan, wifi, nugas) ↔ ruang untuk *ngobrol/santai*.

Angka di dalam kurung adalah harga item sebanding atau harga hero.

```
                        RUANG UNTUK NGOBROL / SANTAI
                                    ▲
  Warkop (Rp5rb)                    │                     Hulu Coffee (?) *
  Mal/McD                           │      Kopi Bemo (mulai Rp8rb)
                                    │      — siang hari, di dalam pasar
                                    │                    ┌───────────────┐
                                    │                    │ TARGET KOPIYO │
                                    │                    │ ≤ Rp27.500    │
                                    │                    └───────────────┘
KOPI = BAHAN ◄──────────────────────┼──────────────────────────► KOPI = RITUAL
BAKAR                               │                         Psswrd (slow bar, ?)
  Kopi Kenangan (Rp18rb)            │   Kopi Nako (Rp29rb)
  Point Coffee (Rp20–25rb)          │
                                    │        Anastomosis (Rp26rb)
  Pukul Satu (Rp18–23rb)            │        Kalea (Rp40rb)
  Glasmacher (Rp22–56rb)            │
  Jung (Rp20rb)                     │
                                    ▼
                    RUANG UNTUK KERJA (WFC: colokan, wifi)
```

Dasar penempatan:
- **Pukul Satu, Glasmacher, Jung, Kalea, Anastomosis, dan Kopi Nako** berada di bawah karena masing-masing dipromosikan untuk kerja atau nugas. Buktinya ada di bagian 4.
- **Hulu** ditempatkan di atas karena ada board game, buku, dan bio "Manual Brew"/community space, sementara bukti WFC untuk Hulu tidak saya temukan. Tanda (?) berarti posisinya belum pasti.
- **Psswrd** saya taruh di garis tengah karena suasana ruangnya tidak terverifikasi.
- **Kopi Bemo** unggul dalam keahlian biji kopi dan suasana ngobrol, tetapi tempatnya di pasar dan jam bukanya siang hari.

---

### 4. Apa kata pelanggan: keluhan, diurutkan

Saya mencari ulasan 1–3 bintang untuk 4 kompetitor paling langsung yang punya ulasan publik (Hulu, Kalea, Anastomosis, Kopi Bemo), ditambah 3 tempat nongkrong yang paling dominan (Pukul Satu, Glasmacher, Kopi Nako). Untuk Psswrd tidak ada ulasan yang muncul. Untuk Kopi Bemo, tidak ditemukan keluhan sama sekali; liputannya positif semua.

"Hitungan" di bawah adalah jumlah ulasan atau postingan berbeda yang saya temukan, bukan jumlah ulasan di platformnya. Tema dengan kurang dari 3 ulasan ditandai **tipis**.

| Peringkat | Tema | Hitungan | Di mana | Bukti |
|---|---|---|---|---|
| 1 | **Rasa minuman tidak pas atau tidak konsisten** | 5–6 | Anastomosis (2), Hulu (2), Kalea (1), Pukul Satu (1, mungkin ulasan yang sama dengan #2) | Anastomosis: satu ulasan menyebut kopi disajikan dengan air dingin, satu lagi menyebut kemanisan ([TripAdvisor PH](https://www.tripadvisor.com.ph/Restaurant_Review-g294229-d5552697-Reviews-Anastomosis_Coffee-Jakarta_Java.html)). Kalea: Kalea Signature "cenderung asam" ([PergiKuliner 2022](https://pergikuliner.com/restaurants/jakarta/kalea-coffee-dan-space-rawamangun/reviews/2534941194)). Hulu: kurang manis atau terlalu pahit ([MenuKuliner](https://menukuliner.net/menu/340802/hulu-coffee-rawamangun)) |
| 2 | **Pelayanan lambat / pesanan tidak datang** | 3 | Pukul Satu (2, dari halaman yang sama), Anastomosis (1) | Pukul Satu: "Very bad service, very slow, waiting hour for dessert. Not worth it." ([RestaurantGuru](https://restaurantguru.com/Pukul-Satu-Kopi-Rawamangun-East-Jakarta)). Pengelola juga membalas ulasan lain soal pesanan Teh Telang Leci yang tidak datang (25 Jan 2026) dan soal antrean panjang. Anastomosis: "very bad served" ([TripAdvisor](https://www.tripadvisor.com/Restaurant_Review-g294229-d5552697-Reviews-Anastomosis_Coffee-Jakarta_Java.html)) |
| 3 | **Parkir** | 3 | Kopi Nako, Glasmacher, Kalea | Kopi Nako: tidak ada parkir mobil, diarahkan ke pinggir jalan (ulasan 2021, [PergiKuliner](https://pergikuliner.com/restaurants/jakarta/kopi-nako-rawamangun/reviews/7184321176)). Glasmacher: parkir mobil agak sulit ([Wanderlog](https://wanderlog.com/place/details/13904546/glasmacher-coffee-rawamangun)). Kalea: ulasannya campur, "Parkiran tidak terlalu sempit." ([Menustic](https://kalea-coffee-and-space.menustic.com/)) tetapi ada juga yang menyebut mobil parkir di pinggir jalan |
| 4 | **Bising / musik keras** — *tipis* | 1 keluhan + 1 jadwal live music | Glasmacher | Glasmacher: "it can get quite warm and the music tends to be on the louder side" (ringkasan [Wanderlog](https://wanderlog.com/place/details/13904546/glasmacher-coffee-rawamangun)). "Saat akhir pekan di cafe ini akan ada live music." ([kumparan](https://kumparan.com/jendela-dunia/6-rekomendasi-cafe-di-rawamangun-yang-cozy-1ywgdFDAZfe)). Sebaliknya, Kalea umumnya digambarkan tenang ([RestaurantGuru](https://restaurantguru.com/KALEA-Coffee-and-Space-East-Jakarta)) |
| 5 | **Gerah** — *tipis* | 1 | Glasmacher | Kutipan Wanderlog yang sama dengan di atas |
| 6 | **Harga item terlalu mahal** — *tipis* | 1 | Hulu | Lychee Tea dinilai kemahalan ([MenuKuliner](https://menukuliner.net/menu/340802/hulu-coffee-rawamangun)). Sebaliknya, banyak sumber memuji harga yang terjangkau: Kopi Bemo, Jung, Anastomosis, dan Mojok tentang Rawamangun: "Asli, banyak banget tempat nongkrong dengan harga yang bersahabat di sini." ([Mojok](https://mojok.co/terminal/rawamangun-daerah-paling-unggul-di-jakarta-timur/)) |

#### Bukti yang paling penting untuk konsep ini

**Laptop/WFC: hampir semua kafe menjual diri sebagai tempat kerja. Ada lebih dari 10 tempat:**
- Pukul Satu: "bisa wfc di indoor dan outdoor karena banyak colokan" ([TikTok](https://www.tiktok.com/@asknownjeje_/video/7595376950496054546)).
- Glasmacher: "Coffee Shop Nyaman Buat WFC & Tempat Nongkrong" ([Lemon8](https://www.lemon8-app.com/seputar.kulineran/7234434107424457218?region=id)).
- Kalea: "Work From Coffee Shop di KALEA Coffee & Space" ([blog 2022](https://www.jalanjalankenai.com/2022/12/kalea-coffee-and-space.html)).
- Anastomosis: "...Spot Kerja Nyaman" ([Lemon8](https://www.lemon8-app.com/@meriyanataa/7236744699212644865?region=id)).
- Kopi Nako dan Glasmacher disebut cocok untuk kerja ([Kompas 2024](https://www.kompas.com/food/read/2024/06/04/204056475/5-kafe-di-rawamangun-di-jakarta-timur-ada-yang-cocok-buat-kerja)).
- Atme Coffee: "punya nuansa homey yg cocok buat WFC" ([TikTok 2025](https://www.tiktok.com/@fr.arum_/video/7519146515441405191)).
- Lainnya: Jung (wifi, stop kontak), Kopi Peron, Meet/N/Work, dan Fore Paus ("WFH"). Ada juga daftar [Dealls "23 Coffee Shop Jakarta Timur untuk WFC dan Meeting"](https://dealls.com/pengembangan-karir/coffee-shop-jakarta-timur).

**Perputaran kursi:**
- Pukul Satu disebut ramai menjelang malam, terlebih di akhir pekan ([cuplikan Orami 2023](https://www.orami.co.id/magazine/tempat-nongkrong-di-rawamangun)).
- Indoor Kopi Nako Rawamangun hanya punya dua meja ([Trip.com](https://hk.trip.com/moments/detail/east-jakarta-1458423-124231354?locale=en-HK)).
- Untuk Jakarta secara umum, tidak ada aturan tertulis soal lama duduk di kafe. Pengunjung yang duduk lama mengurangi peluang pembeli baru ([detikFood](https://food.detik.com/info-kuliner/d-7583276/durasi-maksimal-duduk-di-kafe-agar-tak-bikin-barista-kesal)). Ada pula imbauan agar "jangan hanya pesan segelas kopi, lalu nongkrong berjam-jam" ([IDN Times](https://www.idntimes.com/food/dining-guide/etika-nongkrong-sembari-nugas-dan-wfc-di-kafe-00-z5hk4-v9fb7g)).

**Jam buka:** Kopi Bemo, satu-satunya pemain murah yang ahli kopi, buka 06.00–16.00 menurut [Pos News](https://www.posnews.co.id/nikmati-kopi-legendaris-kopi-bemo-di-pasar-rawamangun-jakarta-timur/) (Sep 2025). Jam itu mungkin berlaku untuk toko, bukan kedai. Artinya Kopi Bemo bisa jadi melewatkan jam sesudah kerja.

---

### 5. Celah (gap)

**Yang tidak dikerjakan dengan baik oleh siapa pun, berdasarkan bukti:**

1. **Tempat kopi yang secara terang-terangan "bukan tempat kerja".** Dari semua kafe yang ditemukan, tidak ada yang memosisikan diri anti-laptop. Hampir semuanya justru menjual colokan dan wifi (lihat bagian 4).
2. **Slowbar sebagai inti pengalaman, buka sesudah jam kerja, dengan harga di bawah median.**
   - Slowbar sungguhan (Psswrd) hanya satu, di Kayu Putih, tanpa data harga atau ulasan publik.
   - Di tempat lain, manual brew hanya menu sampingan, bukan tontonan di depan tamu.
   - Pemain ahli kopi yang paling murah (Kopi Bemo) beroperasi siang hari di dalam pasar.
3. **Suasana yang memang dirancang untuk ngobrol.** Keluhan yang paling relevan adalah musik keras, live music, gerah, dan pelayanan lambat (bagian 4). Kopiyo bisa menjadikan suasana tenang dan "menunggu seduhan sebagai tontonan, bukan keluhan" sebagai standar.

**Rumusan celah:** slowbar untuk sesudah jam kerja (kira-kira sore sampai malam), tanpa laptop, dengan barista yang mengajak ngobrol, dan V60 di bawah sekitar Rp27.500. Dari yang terverifikasi, tidak ada yang menggabungkan keempat unsur ini.

**Tetapi, terus terang:**
- **Celahnya sempit.** Hulu Coffee sudah punya manual brew, ruang komunitas, board game, dan buka sampai tengah malam. Hulu hanya perlu sedikit mengubah pesan supaya menempati posisi yang sama.
- **Celahnya mungkin ada karena permintaannya kecil.** Tempat dengan rating dan jumlah ulasan tertinggi (Pukul Satu, 4.9 dari 1.556) justru ramah WFC. Pasar Rawamangun yang dekat kampus (UNJ) dan kantor terbukti menghargai colokan. Konsep tanpa laptop mengorbankan segmen itu. Ini harus diuji ke pembeli sungguhan, misalnya lewat panel konsumen atau pop-up dengan harga nyata, sebelum dijadikan inti merek.

---

### 6. Ancaman: siapa yang paling cepat meniru

1. **Hulu Coffee (paling cepat, hitungan minggu).** Semua bahan sudah dimiliki: manual brew, ruang komunitas, board game, jam malam, dan lokasi di Rawamangun. Cukup dengan mengumumkan "no-laptop hours" atau acara seduh bersama.
2. **Kopi Nako (paling berbahaya dari sisi harga dan skala).** Jaringan ini sudah menjual V60 single origin Rp29.000, menyangrai kopinya sendiri ([Medcom](https://www.medcom.id/rona/wisata-kuliner/wkB73MDK-paduan-sensasi-makan-warteg-kekinian-dan-minum-kopi-rasa-durian); ada gerai "Rumah Sangrai" di [MenuKuliner](https://menukuliner.net/menu/383186/kopi-nako-rumah-sangrai-binamarga)), dan punya ruang outdoor besar di seberang Terminal Rawamangun. Kopi Nako bisa menambah pojok slowbar dan menahan harga di bawah Kopiyo.
3. **Kopi Bemo (paling kuat dari sisi cerita dan pasokan).** Toko kopi sejak 1965 dengan sekitar 30 jenis kopi Indonesia ([Berita Jakarta, Sep 2025](https://www.beritajakarta.id/en/read/60328/potret-jakarta)), harga mulai Rp8.000, dan terus berinovasi: menambah nasi dan mi pada 2026 menurut [Ipol](https://ipol.id/2026/09/kopi-bemo-sang-legenda-yang-tak-henti-lakukan-inovasi/). Kalau Kopi Bemo memperpanjang jam buka atau membuka gerai malam di luar pasar, sulit menyaingi harga dan ceritanya.
4. **Psswrd Coffee.** Sudah menjalankan slow bar dan roastery di kecamatan yang sama, jadi tinggal menambah positioning "tempat ngobrol sepulang kerja".

**Pertahanan yang masuk akal**, sebagai bahan untuk modul brand/offer: aturan ruang yang konsisten (tanpa laptop di jam tertentu), ritual seduh yang menjadi tanda tangan, dan hubungan barista–tamu. Hal-hal ini lebih sulit ditiru jaringan dibanding harga atau menu.

---

### 7. Keterbatasan riset

- **Halaman tidak bisa dibuka langsung.** WebFetch ditolak jaringan sesi (orami.co.id dan beritajakarta.id; kedua host itu perlu diizinkan di pengaturan jaringan jika ingin dibaca penuh). Semua fakta dan kutipan berasal dari cuplikan hasil pencarian, dan beberapa ringkasan pencarian saling bertentangan. Contohnya harga V60 Kopi Bemo: satu ringkasan menyebut Rp25.000 dari Poskota, ringkasan lain tidak menemukannya. Data yang bertentangan seperti itu saya tandai "tidak terverifikasi".
- **Google Maps tidak diakses langsung.** Rating diambil dari agregator yang mungkin sudah tertinggal, dan jumlah ulasannya berbeda antar-platform.
- **Data harga sudah tua dan jumlahnya sedikit.** Hanya 4 harga manual brew yang terverifikasi, sebagian besar dari 2022–2023 dan sebagian dari aplikasi pesan-antar. Harga V60 untuk Psswrd, Hulu, Kopi Bemo, Glasmacher, dan Pukul Satu (cabang Rawamangun) tidak ditemukan.
- **Ulasan negatif sangat sedikit.** Hampir semua tema keluhan berasal dari 1–3 ulasan per tempat, sehingga hanya cukup sebagai indikasi, bukan pola yang kokoh. Untuk Psswrd tidak ada ulasan sama sekali.
- **Jam buka dan status operasi tidak konsisten antar-sumber.** Ini berlaku untuk Kopi Bemo, Hulu, Kalea, dan Jung. Beberapa tempat mungkin sudah tutup (Upnormal, Kedai Locale, De Facto).
- **Permintaan untuk konsep tanpa WFC belum diteliti.** Riset ini hanya memetakan penawaran, bukan minat pembeli.
- **Yogyakarta tidak diteliti.** Fokus riset ini Rawamangun.

## The buyer panel

**10 buy · 10 pass** (50% buy) out of 20 simulated buyers. Seed 2611, so the same cards can be dealt again.

These are simulated buyers, not customers. Use this to find objections and weak spots, then confirm the big ones with real people before you spend.

### By segment

| group | buyers | buy rate |
| --- | ---: | ---: |
| Mahasiswa tingkat akhir / fresh graduate (uang saku atau gaji Rp2–5 juta/bulan) | 4 | 100%  (thin) |
| Karyawan muda (gaji sekitar Rp5–9 juta/bulan) | 9 | 44% |
| Profesional mapan (gaji sekitar Rp10–25 juta/bulan) | 5 | 40%  (thin) |
| Pekerja lokal / wiraswasta / guru / ASN (Rp6–15 juta/bulan) | 2 | 0%  (thin) |

### By buying behaviour

| group | buyers | buy rate |
| --- | ---: | ---: |
| Pecinta kopi yang suka ngulik | 2 | 100%  (thin) |
| Pemburu promo | 3 | 100%  (thin) |
| Nongkrong rutin sepulang kerja | 4 | 100%  (thin) |
| Hemat, kopi seadanya | 2 | 50%  (thin) |
| Ikut tren / FOMO media sosial | 3 | 0%  (thin) |
| Loyal ke tempat langganan | 2 | 0%  (thin) |
| Cari tempat sambil kerja | 2 | 0%  (thin) |
| Cek review dulu | 2 | 0%  (thin) |

### By income

| group | buyers | buy rate |
| --- | ---: | ---: |
| under $91,800,000 | 6 | 67%  (thin) |
| $91,800,000 to $104,733,000 | 7 | 57%  (thin) |
| $104,733,000 and up | 7 | 29%  (thin) |

### Why they pass

| reason | buyers | in their words |
| --- | ---: | --- |
| habit | 4 | "Harganya murah dan es kopi susu 3 menit plus nasi kucing memang menjawab soal capek dan lapar, tapi saya biasanya cuma datang ke tempat yang lagi ramai di TikTok atau IG. Lapak baru 15 kursi di teras ruko belum ada yang posting, jadi saya belum tergerak buat sengaja ke sana." (P005) · "Saya sudah punya warkop langganan dekat rumah yang murah, buka sampai malam, dan teman-teman saya juga kumpulnya di sana. Konsep angkringan plus kopi seduh ini menarik, tapi buat saya isinya mirip dengan tempat yang sudah saya datangi, jadi tidak ada alasan kuat untuk pindah." (P006) |
| trust | 4 | "Saya belum pernah lihat tempat ini rame di TikTok atau IG, teman-teman juga belum ada yang ke sana. Lapak tikar di teras ruko kedengarannya biasa aja, jadi nggak bakal sengaja ke sana; kopi susu tetap pesan ojol aja di kantor." (P011) · "Kedengarannya enak buat nongkrong, tapi tempatnya baru dan belum ada review di Google Maps, jadi bulan pertama aku belum mau coba dulu. Kopi susu sehari-hari aku juga udah biasa pesan lewat ojol di kantor." (P013) |
| need | 2 | "Saya ke kafe itu buat kerja sambil ngopi, bawa laptop. Di sini laptop nggak boleh dan bukanya baru jam 7 malam, padahal saya udah sampai rumah sekitar jam 6, males keluar lagi cuma buat duduk di tikar." (P009) · "Saya ke kafe biasanya buat nyelesaiin kerjaan sambil ngopi, dan di sini laptop malah dilarang. Bukanya juga baru jam 19.00, padahal jam segitu saya sudah sampai rumah, capek, dan malas keluar lagi." (P015) |

### Why they buy

| reason | buyers | in their words |
| --- | ---: | --- |
| price | 5 | "Lokasinya pas sama tempat saya biasa ketemu teman kuliah di Rawamangun, dan promo minuman kedua setengah harga plus cicip gratis bikin saya mau coba bareng teman. Tubruk Rp8.000 dan gorengan murah juga masih masuk kantong, tapi kemungkinan besar saya datang cuma pas dua minggu promo itu." (P002) · "Harganya masuk buat kantong saya, tubruk 8 ribu plus gorengan, dan promo minuman kedua setengah harga itu pas buat ngajak temen nongkrong pulang kerja. Saya coba pas dua minggu promo, tapi habis itu belum tentu balik." (P003) |
| quality | 2 | "V60 single origin Rp22 ribu, diseduh di depan saya dengan kartu asal beans, plus ada nasi kucing dan sate buat ganjal lapar, itu pas buat nongkrong sama teman pulang kantor. Saya coba sekali dulu, kalau beansnya enak saya balik lagi." (P001) · "V60 single origin Rp22.000 diseduh di depan saya plus kartu asal beans itu memang yang saya cari, dan cicip gratis bikin risikonya kecil. Tapi saya tidak datang minggu pertama; saya tunggu review di Maps/TikTok dulu, paling coba sekali di minggu ketiga atau keempat, Jumat malam sepulang kerja." (P016) |
| habit | 1 | "Aku memang nongkrong sama teman tiap minggu habis kantor, dan buka jam 7 malam di Jakarta Timur itu pas, harganya juga masih masuk akal dibanding kafe. Aku mau coba sekali pas promo ajak teman, kalau enak mungkin balik sekali lagi, tapi belum tentu jadi tempat rutin." (P007) |
| need | 1 | "Saya memang nongkrong tiap minggu, dan di sini kopi plus makan bisa sekaligus dengan harga murah, ada es kopi susu yang jadi dalam 3 menit, jadi nggak harus nunggu slowbar. Promo ajak teman bikin saya mau coba sekali bareng geng kantor, kalau enak ya balik lagi." (P008) |
| convenience | 1 | "Baru gajian, dan ini dekat, buka malam pas jam saya nongkrong, ada nasi kucing sama sate jadi saya nggak kelaparan, dan es kopi susunya katanya 3 menit jadi. Saya coba sekali bareng teman pas promo setengah harga, kalau enak balik lagi." (P018) |

### What would flip a no

- Lihat tempatnya ramai dan sering muncul di FYP TikTok/IG, atau teman nongkrong yang ngajak duluan pakai promo minuman kedua setengah harga.
- Kalau teman-teman nongkrong saya sendiri yang ngajak dan pindah kumpul ke sana, saya ikut, apalagi selama promo minuman kedua setengah harga.
- Kalau teman kantor ngajak nongkrong ke sana di Jumat malam, mungkin saya ikut sekali karena ada promo minuman kedua setengah harga dan bisa cicip dulu.
- Kalau lapak ini muncul rame-rame di FYP TikTok temen-temenku dan ada yang ngajak bareng (plus info parkir yang jelas), aku mungkin datang sekali buat coba dan foto.
- Kalau muncul di FYP TikTok dan kelihatan rame, atau ada teman yang ngajak nongkrong ke sana bareng.
- Kalau rating Google Maps-nya udah 4.5 ke atas dengan puluhan review asli, atau ada teman yang udah ke sana dan ngajak aku langsung.
- Kalau teman-teman tongkrongan saya yang ngajak ketemuan di sana Jumat malam, mungkin saya ikut sekali buat makan angkringan sama es kopi susu yang 3 menit itu.
- Teman nongkrong saya sendiri yang ajak ke sana atau cerita kalau tempatnya enak, plus review bagus di Google Maps setelah beberapa minggu buka.
- Rating Google Maps di atas 4,5 dengan puluhan review asli, atau teman yang sudah ke sana ngajak saya langsung.
- Kalau teman tongkrongan saya yang ngajak dan sudah duluan duduk di sana, saya ikut saja karena minuman kedua setengah harga.

Buyers say they would buy **1.7 times** in the first month on average.

20 buyers gave all four price answers. Run founder-pricing's van_westendorp.py on the answers folder.

## Pricing

> Format lapak malam. Versi kafe ada di [pricing-kafe.md](pricing-kafe.md). Semua angka dalam Rupiah. Jawaban harga berasal dari **20 pembeli simulasi** yang melihat pitch lapak (`panel/`, seed 2611, orang yang sama dengan panel-panel sebelumnya). Itu bahan untuk memilih apa yang diuji, bukan bukti. Margin dihitung dengan `unit_economics.py` pada `numbers.json`.

### 1. Harga

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

### 2. Margin di beberapa belanja per tamu (alat CFO, `numbers.json` dengan biaya nyata dari `ops.md`)

| Belanja rata-rata per tamu | Kontribusi/tamu | Break-even/malam (kapasitas ±30) | Margin di 28 tamu/malam | Tahun 1 |
|---:|---:|---:|---:|---:|
| Rp26.000 | Rp10.733 (41%) | 33 (di atas kapasitas) | −7,1% | −Rp24,9 jt |
| **Rp29.000 (rencana v3)** | **Rp13.733 (47%)** | **26** | **+4,0%** | **−Rp11,8 jt** |
| Rp32.000 | Rp16.733 (52%) | 22 | +13,0% | +Rp1,3 jt |

Rp29.000 = minuman pertama rata-rata Rp17.650 + 35% gelas kedua Rp12.000 + 75% makanan rata-rata Rp9.000 [estimasi]. **Target nyata belanja per tamu adalah ≥Rp32.000**, lewat paket, gelas kedua, dan makanan, bukan lewat menaikkan harga V60. Di Rp26.000, break-even melewati kapasitas. Versi hemat ada di `cfo.md`.

### 3. Tangga

| Tingkat | Isi | Harga |
|---|---|---:|
| Masuk | Kopi tubruk + gorengan | ±Rp10.500 |
| **Pulang Kerja** | Es kopi susu + nasi kucing + gorengan | Rp25.000 (tanpa "harga coret") |
| Seduh | V60 + kue/roti, dengan kartu beans | Rp27.000 |
| Sesi Bareng (3–4 orang, **Jumat–Sabtu**) | Teko V60 dua beans + sepiring sate/gorengan | Rp75.000 (Rp19.000–25.000/orang) |

### 4. Penawaran pembukaan

- **Kartu Cap Yok, sejak malam pertama dan tanpa tanggal berakhir:** 1 cap per malam belanja ≥Rp25.000, 5 cap = gelas ke-6 gratis, cap bonus untuk yang membawa teman baru. Biayanya ±Rp595/kunjungan (`marketing.md`). Kartu ini **menggantikan** promo Ajak Teman 2 minggu, yang hanya menarik pemburu promo dan terlewat oleh penunggu review (panel lapak, P017).
- **Tidak ada beli-1-gratis-1 atau cashback e-wallet.** Pemburu promo 3/3 hanya datang selama promo, di panel kafe maupun panel lapak.

### 5. Yang diuji dengan pembeli nyata

| Uji | Varian | Cara | Ukuran |
|---|---|---|---|
| Harga V60 | Rp22.000 vs Rp25.000 | Ganti papan per 2 minggu | % tamu yang memesan V60, % kembali dalam 14 hari |
| Paket Pulang Kerja | Rp25.000 vs Rp27.000 | Sama | % tamu yang mengambil paket, belanja rata-rata |

**Catat setiap malam: jumlah tamu, belanja per tamu, dan lama duduk.** Belanja per tamu adalah angka yang paling menentukan laba di format ini.

### 6. Keberatan harga dari panel lapak (kutipan simulasi, bukan testimoni)

1. "V60 Rp22.000 di lapak teras ruko rasanya kemahalan buat nongkrong biasa." (P006)
2. "Es kopi susu Rp17.000 tanpa promo e-wallet itu lebih mahal dari kopi susu gula aren yang biasa saya beli pakai cashback, dan manual brew buat saya cuma gaya, bukan kebutuhan." (P012)
3. "V60 Rp22.000 di lapak angkringan bikin saya curiga beans-nya biasa saja atau sudah lama di-roast." (P016) **Jawabannya:** kartu beans dengan roastery dan tanggal sangrai.

## The offer

> Format lapak malam. Versi kafe ada di [offer-kafe.md](offer-kafe.md), dengan daftar 23 masalah pembeli yang sebagian besar masih berlaku. Dokumen ini hanya mencatat **yang berubah untuk lapak**, berdasarkan panel lapak (`panel/results.md`) dan syarat board rapat kedua (D1, D2, D10). Pembeli adalah simulasi; angka beli adalah batas atas.

### Hasil panel untuk pitch lapak (sebelum offer v3)

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

### Tumpukan offer v3

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

### Menu menurut malam (syarat D2)

| | Rabu–Kamis (founder sendiri) | Jumat–Sabtu (founder + helper) |
|---|---|---|
| Kopi | V60 (2 beans), es kopi susu konsentrat, tubruk | Sama, ditambah teko Sesi Bareng |
| Makanan | Siap saji: nasi kucing, gorengan, kue/roti | Ditambah roti bakar dan sate (kompor untuk kettle dan pemanggang) |
| Buka | 19.00, atau **19.30** jika pemasangan lewat 19.00. Jam itu yang ditulis | 18.00 (helper mulai memasang 17.30) |

### Biaya (alat CFO, `numbers.json`)

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

### Belum diuji

Offer v3 (paket, kartu cap, bangku, reservasi) belum dites ulang ke panel. **Ujinya adalah delapan minggu pertama**, dengan ambang board D9.

## The numbers

> `numbers.json` = **lapak malam Rawamangun dengan offer v3 dan biaya nyata dari [ops.md](ops.md) §11**. Pembanding:
> - versi hemat: `numbers-lapak-hemat.json`;
> - rencana ruko lama: [cfo-ruko.md](cfo-ruko.md);
> - versi lapak sebelum ops: `numbers-lapak-v3-1-sebelum-ops.json`;
> - opsi Jogja: `numbers-jogja.json`.
>
> Semua angka dalam Rupiah (`$` di tabel alat = Rp). Banyak input masih **estimasi**: sewa teras, porsi makanan, es, galon, gas, ramp, dan kapasitas. Ini bukan nasihat keuangan atau pajak; minta akuntan atau KPP mengecek PPh dan PBJT.

### Kebenaran yang tidak nyaman lebih dulu

**Dengan biaya nyata menjalankan lapak tanpa listrik, rencana lapak merugi di tahun 1.**

- Jam helper yang sebenarnya, es untuk cooler, air galon, dan gas dua kompor menaikkan biaya tetap dari Rp4,83 juta ke **Rp5,98 juta/bulan**.
- Break-even naik ke **26 tamu/malam** dari kapasitas realistis sekitar **30**.
- Tahun 1 **−Rp11,8 juta**.

Tidak ada yang salah dengan konsepnya. Hanya saja, di skala sekecil ini setiap Rp500 ribu biaya tetap menggeser break-even sekitar 2 tamu/malam.

### Margin (rencana `numbers.json`)

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

### Jalan kembali ke untung (semua dijalankan dengan alat)

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

### Syarat board

| Syarat | Status |
|---|---|
| C1 Aplikasi dibekukan | Terpenuhi (Qasir + QRIS statis) |
| D1 Paket inti, belanja ≥Rp30.000 | Paket dirancang (`offer.md`). Model memakai Rp29.000; **Rp32.000 dibutuhkan untuk untung yang berarti** |
| D4 Perjanjian tempat (atap, air, toilet, titip gerobak) | **Mempengaruhi angka langsung:** titip gerobak menghemat Rp400 ribu/bulan, air dari tuan rumah Rp250 ribu/bulan |
| D9 Ambang review 2 Feb | **Naikkan ambang tamu dari 21 ke 26 tamu bayar/malam** (break-even biaya nyata). Ambang 21 hanya berlaku jika penghematan tercapai dan tercatat |
| C11 / D11 Kios dan Jogja ditunda | Dipertahankan. Jogja dengan operator rugi (Lampiran C) |

---

## Lampiran A: Rencana lapak dengan biaya nyata (`numbers.json`), output alat


Every number below comes from the input file. Nothing is looked up or guessed.

### One tamu (rata-rata belanja per kunjungan)

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

### The margin that matters

Fixed costs: $5,983,250 a month (Sewa/numpang teras ruko atau rumah yang tutup sore (listing Jaktim Rp0,6-2,5 jt/bulan; research/lokasi-rawamangun.md) $1,500,000, Helper Jumat-Sabtu 17.30-00.15 (6,75 jam x 8,67 malam x Rp45.475/jam, UMP DKI/126) + BPJS JKK/JKM (ops-lapak.md) $2,675,000, Gas: LPG 5,5 kg + gas kaleng kompor kedua Jumat-Sabtu (ops-lapak.md) [estimasi] $400,000, Angkut alat: Rp0 HANYA jika titip gerobak tertulis di perjanjian (ops-lapak.md; jika tidak, +Rp400 rb) $0, Iuran kebersihan/warga dengan kuitansi [estimasi] $150,000, Marketing (cetak kartu Ajak Teman, konten) [estimasi] $500,000, Aplikasi kasir Qasir Pro (Rp699 rb/tahun) $58,250, Es untuk cooler + ongkir (ops-lapak.md) [estimasi] $450,000, Air galon untuk seduh & minum (ops-lapak.md) [estimasi] $250,000).

- **Break-even: 26 tamu (rata-rata belanja per kunjungan)s a day.** Below that you lose money every month.
- **Profit margin at your plan** (28 a day): **4%** of every sale, after every cost.
- Capacity: 30 a day.

### Year 1, month by month

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

### What if

| scenario | margin at plan | break-even a day | year 1 profit |
| --- | ---: | ---: | ---: |
| Base plan | 4% | 26 | -$11,799,523 |
| Price -10% | -7% | 33 | -$24,469,623 |
| Volume -20% | -7% | 26 | -$23,799,418 |
| Unit costs +15% | -4% | 31 | -$21,804,751 |

### Red flags

- Year 1 loses money on operations (-$11,799,523).
- The startup spend is not earned back within year 1.

---

## Lampiran B: Versi hemat (`numbers-lapak-hemat.json`), output alat


Every number below comes from the input file. Nothing is looked up or guessed.

### One tamu (rata-rata belanja per kunjungan)

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

### The margin that matters

Fixed costs: $4,991,125 a month (Sewa/numpang teras ruko atau rumah yang tutup sore (listing Jaktim Rp0,6-2,5 jt/bulan; research/lokasi-rawamangun.md) $1,500,000, Helper Jumat-Sabtu 18.00-23.30 (5,5 jam x 8,67 malam x Rp45.475/jam) + BPJS JKK/JKM; founder memasang & membongkar $2,182,875, Gas: LPG 5,5 kg + gas kaleng kompor kedua Jumat-Sabtu (ops-lapak.md) [estimasi] $400,000, Angkut alat: Rp0 HANYA jika titip gerobak tertulis di perjanjian (ops-lapak.md; jika tidak, +Rp400 rb) $0, Iuran kebersihan/warga dengan kuitansi [estimasi] $150,000, Marketing (cetak kartu Ajak Teman, konten) [estimasi] $500,000, Aplikasi kasir Qasir Pro (Rp699 rb/tahun) $58,250, Es untuk cooler, dibeli sendiri di jalan (ops.md) [estimasi] $200,000, Air: Rp0 tambahan jika air/galon dari tuan rumah masuk perjanjian sewa (ops.md) $0).

- **Break-even: 22 tamu (rata-rata belanja per kunjungan)s a day.** Below that you lose money every month.
- **Profit margin at your plan** (28 a day): **11%** of every sale, after every cost.
- Capacity: 30 a day.

### Year 1, month by month

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

### What if

| scenario | margin at plan | break-even a day | year 1 profit |
| --- | ---: | ---: | ---: |
| Base plan | 11% | 22 | $105,977 |
| Price -10% | 1% | 28 | -$12,564,123 |
| Volume -20% | 2% | 22 | -$11,893,918 |
| Unit costs +15% | 3% | 26 | -$9,899,251 |

### Red flags

- The startup spend is not earned back within year 1.

---

## Lampiran C: Opsi Jogja dengan operator (`numbers-jogja.json`), output alat


Every number below comes from the input file. Nothing is looked up or guessed.

### One tamu (rata-rata belanja per kunjungan)

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

### The margin that matters

Fixed costs: $5,198,250 a month (Sewa teras/kios kecil Jogja (listing Rp650 rb-1,3 jt/bulan; research/opsi-jogja.md) $1,000,000, Operator 4 malam x 6 jam x 17 malam x Rp22.441/jam (UMK Kota Yogyakarta 2026 Rp2.827.593 / 126) $2,290,000, Gas LPG [estimasi] $250,000, Angkut/titip alat [estimasi] $300,000, Iuran kebersihan/warga [estimasi] $100,000, Marketing [estimasi] $400,000, Aplikasi kasir Qasir Pro $58,250, Kunjungan founder Jakarta-Jogja 1x/bulan [estimasi] $800,000).

- **Break-even: 34 tamu (rata-rata belanja per kunjungan)s a day.** Below that you lose money every month.
- **Profit margin at your plan** (28 a day): **-9%** of every sale, after every cost.
- Capacity: 37 a day.

### Year 1, month by month

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

### What if

| scenario | margin at plan | break-even a day | year 1 profit |
| --- | ---: | ---: | ---: |
| Base plan | -9% | 34 | -$22,861,395 |
| Price -10% | -21% | 45 | -$32,473,195 |
| Volume -20% | -21% | 34 | -$30,764,916 |
| Unit costs +15% | -17% | 44 | -$31,351,454 |

### Red flags

- Year 1 loses money on operations (-$22,861,395).
- The startup spend is not earned back within year 1.

## Marketing

> **Catatan rekonsiliasi (setelah dokumen ini ditulis):** `offer.md`, `pricing.md`, dan `numbers.json` final memakai **Kartu Cap Yok** dari dokumen ini (±Rp595/kunjungan), menggantikan Ajak Teman 2 minggu. Belanja rata-rata menjadi **Rp29.000** (paket + gelas kedua Rp12.000), dengan kontribusi **Rp13.733/tamu** dan break-even **21 tamu/malam**. Batas biaya per pelanggan menjadi **Rp13.733 × 1,7 ≈ Rp23.300**. Angka Rp14.105 / Rp23.900 di bawah adalah dari model sebelumnya.

> **Format baru.** Dokumen ini menggantikan `marketing-kafe.md` (rencana kafe "Kopiyo") **khusus untuk lapak malam**. Yang dipakai ulang dari `marketing-kafe.md`: posisi "untuk ngobrol, bukan kerja", kanal ajakan teman lewat WhatsApp + Google Maps + IG/TikTok, tidak ada GoFood atau beli-1-gratis-1, dan aturan soal review, testimoni, dan kerja sama berbayar.
>
> **Sumber:** `lapak-malam.md` (rencana v3), `pitch.md`, `panel/results.md` dan `panel/answers/` (panel lapak, 20 pembeli simulasi, seed 2611), `pricing-curve-lapak.md`, `cfo.md`, `numbers-lapak.json`, `competitors.md`, `research/nama-yok.md`, `research/lokasi-rawamangun.md`, `board/v3-*.md`, `brand-kafe.md`, `ops-kafe.md`. Juga dibaca: `offer.md` dan `pricing.md` versi lapak, yang ditulis paralel pada 8 Nov 2026 (lihat §5 dan §12).
>
> **Label:** [Pasti] = bukti kuat · [Kemungkinan Besar] = inferensi kuat · [Menebak] = estimasi saya. Semua uang dalam Rupiah.
>
> - **Pembeli panel adalah simulasi.** Kutipan dan kode P001–P020 di sini adalah bahan riset untuk memilih pesan. **Tidak pernah dipakai sebagai kutipan atau testimoni pelanggan** di spanduk, post, pesan WA, atau iklan.
> - Setiap kelompok panel hanya berisi 2–9 orang. Angka beli adalah batas atas. Delapan minggu pertama lapak adalah uji yang sebenarnya.
> - "Lapak Yok" masih **nama kerja**. Tidak ada posting publik sebelum nama dicek di PDKI (`lapak-malam.md` §2). Tempat juga belum terkunci. Bukan nasihat hukum.

### Ringkasan

- **Posisi (rekomendasi):** *Untuk geng yang nongkrong tiap minggu sepulang kerja di Rawamangun, Lapak Yok adalah slowbar malam berbentuk lapak: kopi diseduh di depanmu tanpa listrik, jadi tanpa colokan dan tanpa laptop, ada makanan untuk ganjal lapar, buka sampai 24.00.* Kalimat publik: **"Pulang kerja, yok nongkrong dulu."**
- **Tiga kanal:**
  1. **Ajakan teman lewat WhatsApp** (kanal utama): tuan rumah, pesan siap-teruskan, cap bonus untuk yang membawa teman baru, dan tahan bangku untuk grup.
  2. **Lapaknya sendiri ditambah Google Maps**: spanduk dan cahaya yang terbaca dari jalan pada malam hari, profil Maps untuk lokasi tetap, dan review jujur tanpa imbalan.
  3. **Instagram dan TikTok organik**: konten di balik bar tanpa listrik (lampu, kettle di kompor gas, grinder tangan) dan status kursi secara langsung.
- **Yang tidak dikerjakan:** GoFood, beli-1-gratis-1 atau cashback e-wallet, iklan berbayar (Meta, TikTok, Google), selebgram, dan giveaway. Kreator mikro baru mungkin di bulan 2, dengan syarat (§4.6).
- **Pengganti "Ajak Teman 2 minggu": Kartu Cap Yok, permanen.**
  - 1 cap per malam jika belanjamu ≥Rp25.000.
  - 5 cap = gelas ke-6 gratis.
  - Membawa teman yang baru pertama kali = +1 cap bonus.
  - Tidak ada tanggal berakhir, jadi tamu yang menunggu review di minggu ke-4 mendapat hal yang sama dengan tamu malam pertama.
  - Biayanya **±Rp595 per kunjungan** [Menebak, asumsi di §5]. Ajak Teman lama menghabiskan **Rp8.825 per teman yang memakainya**.
- **Batas biaya untuk memenangkan satu pelanggan: Rp23.900** (Rp14.105 × 1,7). Rencana 30 hari pertama: Rp1,5 juta ÷ 100 pelanggan baru = **±Rp15.000 per orang**.
- **Tiga angka mingguan:**
  1. **Tamu bayar per malam buka.** Harus naik dari ≥10 ke **≥21** (break-even) di minggu 6–8.
  2. **Tamu baru per minggu.** ≥25 di minggu 1–4, ≥40 di minggu 5–8. Di bawah 15 per minggu berarti biaya per pelanggan sudah melewati batas.
  3. **Persentase tamu baru yang kembali dalam 14 hari.** Ubah sesuatu jika di bawah 25%.

---

### 1. Bukti yang dipakai

| Temuan | Sumber | Artinya untuk marketing |
|---|---|---|
| **10 beli · 10 tidak (50%)**, 17 pembelian di bulan 1, atau **1,7 kunjungan per pembeli** | `panel/results.md` | 1,7 adalah lantai untuk batas biaya per pelanggan (§12) |
| **Nongkrong rutin 4/4 membeli** (P007, P008, P014, P018), menyumbang 8 dari 17 pembelian | panel lapak | **Audiens pertama.** Mereka datang berkelompok dan bisa mengajak |
| Mahasiswa/fresh graduate 4/4 (P002, P004, P014, P016, menyumbang 6 pembelian). Pecinta kopi 2/2 (P001, P016, menyumbang 3 pembelian) | panel lapak | Audiens pendukung (posisi B dan C di §2) |
| **Pemburu promo 3/3 membeli, tetapi hanya selama promo 2 minggu** (P002, P003, P012). Mereka menyumbang 5 dari 17 pembelian | panel lapak | Promo berbatas waktu menarik pembeli yang tidak kembali. P002 sendiri menyebut "kartu stempel, beli 5 gratis 1" sebagai alasan untuk rutin datang |
| **Ikut tren 0/3, cek review 0/2, loyal ke langganan 0/2, kerja dengan laptop 0/2** | panel lapak | Tiga kelompok pertama baru datang setelah ada bukti sosial nyata. Kelompok laptop **diterima hilang** |
| **P016 baru akan datang di minggu ke-3 atau ke-4**, setelah ada review. P013, P017, dan P019 juga menunggu review | panel lapak | **Promo 2 minggu terlewat oleh orang-orang ini.** Mekanisme apa pun harus tetap berlaku setelah minggu ke-2 (§5) |
| **Pembalik "tidak": diajak teman disebut di 10 dari 10 jawaban.** FYP TikTok disebut 3/10, rating Maps ≥4,5 dengan "puluhan review asli" 3/10, promo setengah harga 4/10, info parkir 1/10 | "What would flip a no" | Kanal utama: ajakan teman. Maps dan TikTok adalah bukti yang dicek teman yang diajak |
| **Keberatan yang berulang** (dari kolom `objection` di jawaban panel): parkir motor (P003, P004, P007, P010); duduk lesehan pegal 2–3 jam (P007, P008, P018, P019); 15 kursi bisa penuh (P004, P007, P008, P014, P018, P020); menunggu seduhan manual (P001, P008, P011, P015, P018, P020); belum ada review atau buzz (P005, P010, P011, P013, P016, P017, P019); aturan laptop (P002, P009, P014, P015, P019); V60 Rp22.000 di lapak dicurigai beansnya biasa (P001, P006, P016) | `panel/answers/` | Satu hook per keberatan (§7) |
| **Sinyal berhenti datang:** V60 >15 menit (P001), menunggu >10 menit atau tempat penuh (P018), penuh atau lama (P008), ditegur karena laptop 5 menit atau dua kali tidak dapat tempat (P014) | `panel/answers/` | Masalah pengalaman, bukan iklan. Masuk ke cek pendukung (§13) |
| Kontribusi Rp14.105 per tamu. Break-even 21 tamu/malam, rencana 28, 17 malam/bulan. Ramp CFO: bulan 1 10 tamu/malam, bulan 2 13 | `cfo.md`, `numbers-lapak.json` | Dasar batas biaya per pelanggan dan pemicu angka mingguan |
| Anggaran marketing di model: Rp1 juta pembukaan dan Rp500 ribu/bulan. Spanduk dan papan nama (Rp700 ribu) masuk startup | `numbers-lapak.json` | Anggaran kecil, jadi kanalnya harus gratis atau hampir gratis |
| **Ambang review 2 Feb 2027:** rata-rata minggu 6–8 ≥21 tamu bayar/malam, belanja ≥Rp28.000, ≥25% kembali dalam 14 hari, ≥30% datang karena diajak teman. Board menambahkan: ≥40 pelanggan tetap, satu malam ritual tetap, satu komunitas yang kumpul rutin, dan ambang tidak boleh diturunkan | `lapak-malam.md` §7, `board/v3-*.md` | Angka mingguan (§13) disusun supaya ambang ini terbaca jauh sebelum 2 Feb |
| Kafe di Rawamangun menjual diri sebagai tempat WFC. Hulu buka sampai tengah malam. YO'KOPI buka 15.00–24.00 (cuplikan IG, lokasi belum terverifikasi). Warkop/angkringan menjual kopi Rp5.000–8.000 | `competitors.md`, `lapak-malam.md` §1 | Jangan memimpin dengan harga (board D10/Monopoly C4). Pesaing tidak pernah disebut di materi publik |

**Ketegangan yang perlu diakui:** ramp CFO memperkirakan 13 tamu/malam di bulan 2, sedangkan ambang review meminta 21 di minggu 6–8. Tugas marketing adalah menutup selisih itu. Kalau tidak tertutup, jawaban jujurnya adalah ambang gagal, bukan ambang diturunkan.

---

### 2. Positioning

Template: *Untuk \<segmen yang paling banyak membeli\>, yang \<masalah mereka dengan kata-kata mereka\>, \<bisnis\> adalah \<kategori\> yang \<celah\>, tidak seperti \<alternatif terdekat\>.*

**Versi A: geng nongkrong pulang kerja (direkomendasikan)**
> Untuk geng yang nongkrong tiap minggu sepulang kerja di Rawamangun, yang datang "capek dan lapar beneran" lalu duduk 2–3 jam, Lapak Yok adalah slowbar malam berbentuk lapak. Kopinya diseduh di depanmu tanpa listrik, jadi tidak ada colokan dan tidak ada laptop. Ada makanan untuk ganjal lapar, dan bukanya sampai 24.00. Ini berbeda dari kafe Rawamangun yang menjual diri sebagai tempat WFC, dan dari warkop langganan yang tidak menyeduh kopinya di depanmu.

**Versi B: pecinta kopi**
> Untuk pecinta kopi di Jakarta Timur yang curiga "V60 Rp22 ribu di lapak, beansnya biasa saja", Lapak Yok adalah slowbar malam yang menulis roastery, proses, dan tanggal sangrai di kartu beans. Kopinya diseduh oleh orang yang sama setiap malam. Ini berbeda dari kafe yang menjadikan manual brew menu sampingan.

**Versi C: mahasiswa dan fresh graduate**
> Untuk mahasiswa tingkat akhir dan fresh graduate di sekitar UNJ, yang nongkrong selama "tubruk 8 ribu plus gorengan masih masuk kantong", Lapak Yok adalah lapak kopi malam untuk ngobrol lama tanpa jadi mahal. Ini berbeda dari kafe nugas yang penuh colokan.

| Versi | Bukti panel yang mendukung | Kelemahan |
|---|---|---|
| **A** | Nongkrong rutin 4/4 membeli dan menyumbang 8/17 pembelian. Alasan mereka: buka jam 7 malam itu pas, kopi plus makan sekaligus, harga masuk akal dibanding kafe (P007, P008, P018). Tanpa listrik berarti tanpa colokan, jadi aturan "bukan tempat kerja" ditegakkan oleh lapaknya sendiri (board Product v3). Tidak ada kafe WFC di `competitors.md` yang mengambil posisi ini | Kelompok laptop hilang (0/2, diterima). Keberatan fisik (duduk, kursi penuh, parkir) paling berat di segmen ini, jadi pengalaman harus menepati janji sebelum diiklankan |
| B | Pecinta kopi 2/2 membeli (data tipis). P016 akan datang "lebih cepat dan lebih sering" jika roastery dan tanggal sangrai jelas | Kelompoknya kecil (12% target). P016 menunggu review dulu |
| C | Mahasiswa/fresh graduate 4/4 membeli | Memimpin dengan harga mengundang perbandingan dengan warkop Rp5.000–8.000, risiko nomor satu di board Offers. Belanja kecil menyulitkan rata-rata Rp28.000. Pemburu promo ada di kelompok ini (P002) |

**Rekomendasi: Versi A.** Versi B menjadi pesan pendukung (hook H10, kartu beans). Versi C hanya dipakai jika titik pertama di Jl. Pemuda dekat UNJ, lewat komunitas kampus, dan tetap tanpa harga di judul.

**Jawaban untuk board** ("angkringan yang menyeduh kopi, atau slowbar berbentuk lapak?"): **slowbar berbentuk lapak**, sama dengan `offer.md` v3. Kata "angkringan" boleh muncul untuk menjelaskan suasana dan makanannya, tetapi tidak dipakai sebagai kategori. Kategori menentukan pembanding harga: angkringan dibandingkan dengan warkop Rp5.000, slowbar dibandingkan dengan kafe Rp26.000.

**Untuk materi publik** (boleh diperhalus `/founder-brand`): **"Pulang kerja, yok nongkrong dulu."** Kalimat pendukung: *"Kopi diseduh di depanmu. HP boleh, laptop istirahat."*

**Kalau ditiru** (angkringan sebelah menambah V60, atau Hulu dan YO'KOPI mengambil klaim "tanpa laptop"): klaimnya bisa disalin dalam seminggu. Yang lebih sulit disalin:
- pelanggan tetap yang kenal founder di balik bar;
- Seduh Bareng setiap Sabtu sebagai ritual (§8);
- kartu cap yang sudah setengah penuh di dompet tamu;
- grup WA tamu yang biasa menahan bangku lewat founder.

Kompetitor tidak pernah disebut atau disindir di materi publik.

---

### 3. Keberatan yang harus dijawab, dan apa yang harus benar dulu

| Keberatan | Siapa di panel | Jawaban marketing | Yang harus benar sebelum diklaim | Hook |
|---|---|---|---|---|
| **Parkir motor** | P003, P004, P007, P010 | Info parkir yang persis (tempat, tarif, siapa juru parkirnya) di papan lapak, profil Maps, sorotan IG, dan balasan otomatis WA | Dicek sendiri di lokasi bersama pemilik dan juru parkir. Kalau parkirnya buruk, lokasinya yang diganti, bukan teksnya (`offer.md`: kriteria tempat) | H1 |
| **Duduk lesehan pegal 2–3 jam** | P007, P008, P018, P019 | Tunjukkan kursinya: sebagian besar kursi lipat bersandaran, tikar hanya untuk yang mau | Daftar belanja startup diganti dari "bangku + tikar" menjadi kursi bersandaran (`offer.md` v3; cek biayanya dengan CFO dan ops) | H2 |
| **15 kursi bisa penuh** | P004, P007, P008, P014, P018, P020 | (1) Grup ≥4 orang bisa menahan bangku lewat WA, ditahan 15 menit. (2) Status kursi diposting langsung di story/status WA pada Jumat–Sabtu | Aturan tahan bangku tertulis: maksimal 2 meja (8 kursi) per malam Jumat–Sabtu pukul 19.00–22.00, sisanya untuk yang datang langsung | H3, H4 |
| **Menunggu seduhan manual** | P001, P008, P011, P015, P018, P020 | Es kopi susu dari konsentrat untuk yang lapar dan buru-buru. Waktu tunggu V60 disebut **sebelum bayar** (board Product C3) | Klaim "3 menit" hanya jika ≥9 dari 10 pesanan selesai dalam 3 menit saat malam latihan. Angka menit V60 diambil dari stopwatch | H5, H6 |
| **Belum ada review atau buzz** | P005, P010, P011, P013, P016, P017, P019 | Mengaku "kami baru", dengan garansi seduh ulang. Kartu cap tanpa tanggal berakhir untuk yang menunggu review. Review asli diminta ke **semua** tamu, tanpa imbalan | Profil Maps terverifikasi (§4.2). Tidak membeli follower, tidak mengklaim "viral" | H7, H8 |
| **Aturan laptop** | P002, P014, P019 (perlu balas kerjaan); P009, P015 (pekerja laptop) | "Lapak ini nggak punya colokan" sebagai fakta, bukan larangan. HP boleh untuk membalas kerjaan | Benar dengan sendirinya: tidak ada listrik. SOP-06 di `ops-kafe.md` (sopan, pribadi, tanpa mempermalukan) | H9 |
| V60 Rp22.000 di lapak dicurigai beansnya biasa | P001, P006, P016 | Kartu beans: roastery, proses, dan tanggal sangrai | Kartu beans ada untuk setiap beans | H10 |
| Habis promo tidak ada alasan kembali | P002, P003, P012 | Kartu cap permanen (§5). Tidak ada diskon e-wallet atau beli-1-gratis-1 | — | H8 |
| Sudah punya langganan | P006, P020 | Tidak diminta pindah, hanya diminta datang "sekali bareng geng" | — | Template B |

---

### 4. Kanal

| Kanal | Kenapa cocok (atau tidak) untuk lapak ini | Biaya 30 hari | Tanda berhasil | Keputusan |
|---|---|---:|---|---|
| **Ajakan teman lewat WhatsApp** | Pembalik di 10/10 jawaban panel. Satu-satunya kanal yang juga memberi kontak tamu (dengan izin) | ±Rp820 rb | ≥30% tamu baru datang karena diajak teman (ambang 2 Feb). Ada tahan bangku setiap Jumat–Sabtu | **Pilih: kanal utama** |
| **Lapak di jalan + Google Maps** | Jl. Balai Pustaka adalah jalan makan malam: orang sudah lewat di jam bukamu. Maps adalah tempat penunggu review mengecek (P013, P019) | ±Rp310 rb (+ spanduk Rp700 rb dari startup) | ≥25% tamu baru menjawab "lewat depan" atau "Maps". ≥10 review asli di 9 Jan, ≥20 di 2 Feb | **Pilih** |
| **IG + TikTok organik** | Teman yang diajak membuka profil ini sebelum datang. Kelompok ikut tren butuh "ada yang posting" (P005, P010, P011) | ±Rp120 rb (alat) | Simpan, share, dan DM "lokasinya di mana?" per post. ≥10% tamu baru menyebut IG/TikTok | **Pilih: bukti** |
| Komunitas UNJ dan kantor sekitar | Sumber tuan rumah, bukan kanal tersendiri | Rp60 rb (flyer) | Tamu yang menjawab "kampus/kantor" | Bagian dari kanal WA |
| Kreator mikro lokal (berbayar, diungkap) | Membawa kelompok ikut tren (0/3 di panel, "jarang kembali"). Di lapak 15 kursi, mereka bisa mengambil kursi pelanggan tetap di Jumat malam | Rp0 di 30 hari pertama | — | **Tunda ke bulan 2, dengan syarat** (§4.6) |

#### 4.1 Lapaknya sendiri: spanduk, cahaya, dan seduhan yang terlihat dari jalan

Pada pukul 19.00–24.00, lapak ini adalah iklan terbesarnya sendiri. Biayanya sudah ada di startup (spanduk dan papan nama Rp700 ribu, lampu LED baterai Rp600 ribu).

- **Spanduk:** "LAPAK YOK" ditumpuk dua baris (`research/nama-yok.md` §3.1), warna Lampu `#F0A83C` di atas Biru Malam `#232647` (`brand-kafe.md`). Di bawahnya:
  - jam yang lolos uji pasang di malam latihan: "Rab–Kam 19.00–24.00 · Jum–Sab 18.00–24.00", atau 19.30 jika pemasangan solo lewat 19.00 (board Product C2);
  - satu baris "kopi seduh · HP boleh, laptop istirahat".
- **Terbaca dari ±20 m:** tinggi huruf nama ≥20 cm [Menebak, aturan praktis ±2,5 cm per 3 m jarak baca]. Uji pada H-11: berdiri di seberang jalan dan di jalur motor dari dua arah.
- **Cahaya:** spanduk harus disinari lampu baterai. Spanduk gelap tidak terbaca pada malam hari. Meja seduh dihadapkan ke jalan, supaya cahaya lampu, uap kettle, dan gerakan menyeduh terlihat dari motor. Itulah "tontonan" yang membedakan lapak ini dari angkringan biasa.
- **Papan kecil:** "Parkir motor →" (hanya jika benar), dan papan tulis berisi status malam itu ("Kursi masih lega", "V60 malam ini ±8 menit", "Hujan? Tenda terpasang").
- **Semua di dalam batas persil.** Papan berdiri tidak boleh di trotoar, dan spanduk tidak boleh diikat ke tiang listrik, pohon, atau pagar umum. Itu melanggar ketertiban dan mengundang penertiban (Perda DKI 8/2007; `lapak-malam.md` §1) [Kemungkinan Besar]. Tanyakan juga ke kelurahan atau Bapenda apakah papan nama usaha di tempat usaha kena pajak reklame [Menebak].

#### 4.2 Google Maps untuk lapak di lokasi pribadi yang tetap

**Bolehkah?** Kemungkinan besar boleh, dengan syarat.
- Aturan dasar Google: usaha harus **bertemu pelanggan secara langsung pada jam yang dicantumkan** ([eligibility](https://support.google.com/business/answer/13763036)). Lapak di titik yang sama, dengan jam tetap Rabu–Sabtu dan founder di bar, memenuhi aturan itu [Kemungkinan Besar].
- Yang biasanya ditolak adalah kios sementara untuk acara, menurut panduan pihak ketiga (bukan teks resmi Google). Truk makanan keliling tidak diatur secara eksplisit [Kemungkinan Besar].
- **Jadi lapak harus tampil sebagai tempat tetap, bukan pop-up:** titik yang sama setiap malam, jam yang benar, dan spanduk yang sama setiap kali buka.

**Cara memasang:**
1. **Izin tertulis pemilik** juga mencakup izin memakai alamatnya di Google Maps. Masukkan ke perjanjian tempat (`/founder-ops`).
2. **Nama persis seperti di spanduk: "Lapak Yok".** Jangan ditambah kata kunci ("Lapak Yok Kopi Seduh Malam Rawamangun"). Itu melanggar pedoman nama Google dan bisa membuat profil ditangguhkan [Kemungkinan Besar].
3. Kategori kedai kopi. Alamat persil ditambah pin tepat di teras. Jam Rabu–Kamis dan Jumat–Sabtu. Deskripsi berisi tanpa listrik, HP boleh/laptop istirahat, dan info parkir.
4. **Isi tanggal buka (9 Des 2026) dulu, lalu pilih "Verifikasi nanti".** Google sendiri menyarankan urutan ini supaya profil tidak tampil "buka" sebelum waktunya ([opening date](https://support.google.com/business/answer/9174409)).
5. **Verifikasi:** pilihannya tergantung jenis usaha dan wilayah. Video sering disarankan ([verifikasi](https://support.google.com/business/answer/7107242)), dan peninjauan bisa makan waktu sampai 5 hari kerja.
   - Rekam pada malam buka saat spanduk menyala: spanduk, papan nama jalan atau penanda sekitar, alat seduh, dan alat bayar (QRIS).
   - Isi persis yang diminta video mengikuti instruksi di aplikasi [Menebak soal detail].
   - Jadwalnya: rekam pada Rab 2 Des, supaya selesai sekitar H.
6. **Jika pemilik ruko sudah punya profil di alamat yang sama,** Lapak Yok tetap profil terpisah, dengan nama dan jamnya sendiri [Menebak; cek saat mendaftar].
7. **Jika verifikasi ditolak:**
   - jangan membuat alamat palsu atau profil kedua;
   - sementara itu bagikan pin lokasi lewat WA dan lokasi IG;
   - coba lagi setelah 2–4 minggu, dengan foto dan jam yang konsisten.

**Review jujur pertama, tanpa imbalan yang melanggar kebijakan Google:**
- **Boleh:** meminta review ke **semua** tamu, lewat QR di kartu meja, ucapan setelah tamu selesai, dan satu pesan WA ke yang sudah setuju dihubungi.
- **Dilarang** ([kebijakan konten](https://support.google.com/contributionpolicy/answer/7400114); ringkasan pihak ketiga: [Search Engine Land](https://searchengineland.com/google-prohibits-incentivizing-customers-to-remove-or-modify-negative-reviews-387874), [PPC Land](https://ppc.land/google-tightens-maps-review-policy-staff-names-and-quotas-now-banned/)):
  - imbalan apa pun untuk review, termasuk diskon, minuman gratis, atau **cap tambahan**;
  - meminta review hanya ke tamu yang tampak puas (*review gating*);
  - meminta bintang tertentu atau isi tertentu, termasuk meminta tamu menyebut nama founder atau barista;
  - menawarkan sesuatu agar review negatif diubah atau dihapus.
- **Tidak menulis review:** founder, keluarga, helper, kreator, dan **tuan rumah yang dijamu gratis di malam latihan**, karena minuman gratis adalah imbalan.
- **Balas setiap review paling lambat 24 jam,** yang baik maupun yang buruk. Untuk founder yang bekerja kantor, waktunya pagi sebelum berangkat.
- **Harapan yang jujur:** jika 5–10% tamu menulis review [Menebak], hasilnya sekitar 4–8 review di H+16 dan sekitar 15–25 di akhir Januari. "Puluhan review asli dengan rating 4,5+" (P013, P019) baru ada di bulan 2–3. **Karena itulah kartu cap tidak boleh punya tanggal berakhir.**

> Halaman kebijakan Google tidak bisa dibuka dari sesi ini (support.google.com dan whitespark.ca diblokir jaringan sesi). Semua aturan di atas diambil dari cuplikan pencarian. Cek ulang di aplikasi Google Business Profile saat mendaftar.

#### 4.3 WhatsApp

- **WhatsApp Business (gratis).** Isi katalog menu dan harga, label ("tuan rumah", "tahan bangku"), salam otomatis berisi pin lokasi, jam, parkir, dan aturan laptop (template E), serta pesan di luar jam buka.
- **Undangan dan grup:** founder tidak membuat grup besar. Founder menulis pesan siap-teruskan (template B), lalu tuan rumah meneruskannya ke grup tongkrongan, kantor, atau angkatan mereka. Tamu yang memutuskan mau mengirim atau tidak.
- **Daftar siaran:**
  - hanya untuk yang setuju secara tertulis (UU 27/2022 PDP);
  - pesan siaran hanya sampai ke kontak yang menyimpan nomormu [Kemungkinan Besar], jadi minta mereka menyimpan nomor saat mendaftar;
  - paling banyak satu pesan per minggu, dengan cara berhenti "balas STOP".
- **Status WA pada malam buka:** status kursi dan hujan/tidak, hanya yang benar saat itu.
- **Tahan bangku:** grup ≥4 orang, ditahan 15 menit, maksimal 2 meja per malam Jumat–Sabtu pada pukul 19.00–22.00. Cocok dengan Sesi Bareng di `offer.md` v3. Founder sedang menyeduh, jadi salam otomatis memberi tahu bahwa balasan bisa agak lama.

#### 4.4 Instagram dan TikTok

- **Isi:** di balik bar tanpa listrik. Air dididihkan di kompor gas, bloom V60 di bawah lampu, suara grinder tangan, menimbang, membuka kantong beans dan membaca tanggal sangrainya, memasang tenda dalam 30 detik (*timelapse*), dan menutup pukul 24.00. Daftar lengkap ada di §9.
- **Ritme realistis untuk founder yang bekerja kantor:**
  - 3 video per minggu, satu video dipasang di Reels dan TikTok sekaligus;
  - story hanya pada malam buka (status kursi, hujan);
  - rekam sekaligus pada Rabu/Kamis yang lebih sepi atau di malam latihan, lalu jadwalkan lewat Meta Business Suite;
  - total sekitar 3 jam per minggu di luar malam buka.
- **Batas:** wajah tamu hanya tampil dengan izin. Tidak ada angka follower, tidak ada "viral", dan tidak ada foto keramaian rekayasa.

#### 4.5 Komunitas UNJ dan kantor sekitar

- Sumber tuan rumah, bukan kanal tersendiri.
- Kirim pesan ke 3–5 admin organisasi mahasiswa/alumni UNJ dan grup kantor di sekitar Jl. Pemuda, Balai Pustaka, dan Pulogadung. Minta izin satu posting. Flyer hanya di tempat yang mengizinkan.
- **Cek kalender akademik UNJ.** Jika minggu 6–8 (13–30 Jan) jatuh di masa ujian atau libur semester, tamu mahasiswa turun [Menebak]. Catat porsi mahasiswa di tally supaya review 2 Feb tidak salah baca.

#### 4.6 Kreator mikro: bulan 2, dengan syarat

Baru dipertimbangkan sekitar 11 Jan jika **ketiganya** terpenuhi:
- ≥10 review asli dengan rating ≥4,5;
- angka mingguan #3 ≥25%;
- ada kursi kosong di Rabu–Kamis.

Paling banyak satu kreator, maksimal Rp300 ribu dari anggaran bulanan. Penontonnya harus di Jakarta Timur (minta data lokasi audiens), dan kontennya diarahkan ke Rabu–Kamis. **Wajib diungkap**, juga jika imbalannya hanya produk (template F).

#### 4.7 Yang tidak dikerjakan, dan alasannya

1. **GoFood/GrabFood.**
   - Panel GoFood 0/20 (`panel-gofood`).
   - Yang dijual lapak ini adalah kursi dan seduhan di depanmu. Lapaknya tanpa listrik, punya 15 kursi, dan founder sendirian di Rabu–Kamis, jadi pesanan ojol akan memotong waktu ngobrol.
   - Komisi platform memakan sebagian besar dari kontribusi yang tipis (`marketing-kafe.md` §4).
2. **Beli-1-gratis-1, cashback e-wallet, atau promo setengah harga berbatas waktu.**
   - Pemburu promo 3/3 hanya datang selama promo.
   - Gelas gratis menghapus Rp17.000–22.000 pendapatan, sementara kontribusi satu tamu hanya Rp14.105.
   - Board juga melarang memimpin dengan harga (Monopoly C4).
3. **Iklan berbayar (Meta, TikTok, Google Ads).**
   - Anggarannya Rp500 ribu/bulan.
   - Mengiklankan tempat yang belum punya review sama dengan membayar orang untuk melihat keberatan nomor satu.
   - Lapak 15 kursi tidak bisa menampung lonjakan tamu dari iklan.
   - Ditinjau lagi paling cepat setelah review 2 Feb, dan hanya untuk boost post organik terbaik ke Rabu–Kamis.
4. **Selebgram dan giveaway "follow & tag 3 teman".** Menggelembungkan follower dengan pemburu hadiah, bukan tamu yang kembali.
5. **Spanduk liar, flyer di motor, atau papan di trotoar.** Melanggar ketertiban dan membahayakan izin tempat.
6. **Area boleh laptop.** Bertentangan dengan posisi, dan memang tidak ada listrik.
7. **Jogja.** Tidak ada aktivitas marketing di sana (board C11).

---

### 5. Pengganti "Ajak Teman 2 minggu": Kartu Cap Yok

#### Kenapa diganti

- **Pemburu promo 3/3 datang hanya selama promo.** Mereka menyumbang 5 dari 17 pembelian bulan 1.
- **Penunggu review melewatkannya.** P016 baru datang di minggu 3–4, padahal Ajak Teman berakhir di H+13 (Sel 22 Des).
- **Tanggal berakhirnya jatuh tepat sebelum minggu Natal.** Turunnya tamu di minggu 3 jadi tidak bisa dibedakan: karena promo habis, atau karena libur.
- **Diskonnya tidak ada di model CFO.** Model hanya memuat biaya cetak kartu.

Tetapi 4 dari 10 pembalik "tidak" menyebut promo setengah harga. Jadi pengganti harus tetap memberi alasan untuk **mengajak teman**, dan hadiahnya baru dibayar saat tamu **kembali**, yaitu perilaku yang diukur di 2 Feb.

#### Aturannya (ditulis di kartu, sama untuk semua tamu, sejak malam pertama dan seterusnya)

1. **1 cap per orang per malam buka**, jika belanjamu malam itu **≥Rp25.000**.
   - Batas Rp25.000 sama dengan harga Paket Pulang Kerja (`offer.md`), dan mendorong belanja ke rata-rata Rp28.000–29.000 yang dibutuhkan break-even.
   - Tubruk saja tetap pintu masuk yang murah, tanpa cap.
   - Untuk nota bersama, belanja dibagi rata per orang.
2. **5 cap = 1 gelas gratis di kunjungan berikutnya** ("gelas ke-6 gratis"). Berlaku untuk minuman apa saja di menu, satu gelas.
3. **Membawa teman yang baru pertama kali ke Lapak Yok = +1 cap bonus** untukmu malam itu, maksimal +1 per malam. Temanmu mulai dengan kartunya sendiri.
4. **Tidak ada tanggal berakhir** selama Lapak Yok buka. Jika lapak berhenti atau pindah, diumumkan 2 minggu sebelumnya dan kartu dihormati sampai malam terakhir. Jika aturan diubah, hanya untuk kartu baru.
5. **Cap tidak pernah diberikan untuk review, follow, tag, atau posting.** Satu-satunya cara mendapat cap adalah datang dan jajan, atau membawa teman baru.
6. **Kontrol penyalahgunaan:**
   - kartu bernomor;
   - cap memakai stempel khusus, ditambah tanggal tulisan tangan;
   - kartu hilang berarti mulai dari awal.

#### Biaya per tamu

**Asumsi** [Menebak, ganti dengan data minggu 1–8]:
- 60% kunjungan belanja ≥Rp25.000;
- 12% kunjungan membawa teman baru;
- 60% cap akhirnya ditukar (asumsi yang sama dengan `numbers.json` v3);
- HPP gelas gratis Rp6.890, campuran minuman CFO.

| Mekanisme | Biaya kas (HPP) per kunjungan | Terburuk: pendapatan hilang jika gelas gratis menggantikan gelas berbayar | Siapa yang terjangkau | Catatan |
|---|---:|---:|---|---|
| Ajak Teman 2 minggu (pitch lama) | — (diskon) | **Rp8.825 per teman yang memakai** (½ harga, campuran 40% V60 / 45% es kopi susu / 15% tubruk). Kontribusi teman itu tinggal ±Rp5.280. Selama 2 minggu ≈Rp2.650 per kunjungan jika 30% kunjungan memakainya | Teman yang datang 9–22 Des, termasuk pemburu promo | Terlewat oleh penunggu review |
| **Kartu Cap Yok (rekomendasi)** | **±Rp595** (Rp683 jika gelas gratis selalu es kopi susu; Rp992 jika 100% cap ditukar) | ±Rp1.525 | **Semua tamu, kapan pun datang**, termasuk penunggu review | Hadiah di kunjungan ke-6, atau ke-5 jika pernah membawa teman |
| Varian 6 cap (gelas ke-7) | ±Rp496 | ±Rp1.271 | Sama | Dipakai jika CFO ingin biaya tetap di bawah garis kartu cap model v3 (Rp560) |
| Kartu cap di `offer.md`/`pricing.md` v3 (gelas ke-10, cap per gelas) | ±Rp558 | ±Rp1.430 | Semua, tetapi hadiahnya baru setelah ±7–8 kunjungan, tanpa mekanisme teman | Mulai setelah Ajak Teman selesai |
| Gelas ke-6 dengan cap per gelas, tanpa syarat belanja | ±Rp1.116 | ±Rp2.859 | Semua | **Tidak dipilih:** break-even naik ke 22 di kedua model |

**Dampak ke break-even** (biaya tetap Rp4.828.250 ÷ 17 malam = Rp284.015 per malam):
- **Model `cfo.md`** (belanja Rp28.000, kartu cap belum dihitung): kartu ini menggeser break-even dari 20,1 ke **21,0 tamu/malam**. Itu tepat di garis, dan **22 jika dibulatkan ke atas.** Kenaikan belanja rata-rata Rp100 saja, yang memang tujuan syarat ≥Rp25.000, mengembalikannya ke 20,9 (21). Jika data belum menunjukkan itu, pakai varian 6 cap (20,9).
- **Model `numbers.json` v3** (belanja Rp29.000, sudah ada garis kartu cap Rp560): selisihnya hanya +Rp35 per tamu, dan break-even tetap **21** (20,7).
- **Bulan 1 hampir tanpa biaya hadiah.** Pelanggan mingguan baru mencapai 5 cap sekitar minggu ke-4 atau ke-5. Biaya bulan 1 hanya cetak kartu dan stempel (Rp250 ribu dari anggaran pembukaan).

#### Jika founder tetap ingin Ajak Teman

Jalankan **bersama** kartu cap, dan kartu cap dimulai **sejak malam pertama**, bukan setelah 2 minggu. Ajak Teman berlaku Rab 9 Des sampai **Sel 22 Des pukul 24.00**. Tanggal itu ditulis sejak hari pertama dan tidak diperpanjang. Biaya diskonnya (±Rp200–250 ribu dalam 2 minggu [Menebak]) diambil dari cadangan, dan setiap pemakaian dicatat supaya angka minggu 3 bisa dibaca.

#### Kalimat di pitch

Menggantikan baris "Dua minggu pertama: ajak teman…": *"Kartu cap: tiap malam jajan Rp25.000 ke atas dapat 1 cap, 5 cap = gelas ke-6 gratis. Bawa teman yang baru pertama kali, kamu dapat cap bonus. Tanpa tanggal berakhir."*

**Belum diuji ke panel.** Jika sempat sebelum 9 Des, jalankan `/founder-consumer --quick` dengan pitch baru. Jika tidak, ujinya adalah malam latihan dan minggu 1–4.

---

### 6. 100 pelanggan pertama (bulan 1)

Ramp CFO bulan 1: 10 tamu/malam × 17 malam = 170 kunjungan ÷ 1,7 = **±100 orang berbeda.** Angka per sumber di bawah adalah **target dan asumsi**. Tuan rumah dihitung sebagai pelanggan hanya setelah mereka membayar.

| Sumber | Cara | Target orang | Biaya | Kapan |
|---|---|---:|---:|---|
| Tuan rumah | 30 diundang pribadi, ±20 datang ke malam latihan | 20 | Rp250 rb (jamuan, dihitung HPP) | 4–5 Des |
| Teman yang dibawa tuan rumah | ±1,5 orang per tuan rumah, bayar harga normal, langsung mendapat kartu cap | 30 | termasuk kartu | 4–19 Des |
| Lewat depan (spanduk, cahaya, seduhan) | Orang yang makan malam di Balai Pustaka | 25 | spanduk dari startup | dari H |
| Komunitas UNJ dan kantor | Satu posting per grup dengan izin, ditambah flyer | 10 | Rp60 rb | dari H-1 |
| Google Maps | Pencarian "kopi" pada malam hari | 5 | Rp0 | setelah verifikasi |
| IG/TikTok organik | — | 5 | alat Rp120 rb | dari H-14 |
| Siaran WA | Ke yang sudah setuju | 5 | Rp0 | H-2, H+12 |
| **Total** | | **100** | **Rp1,5 jt untuk 30 hari, atau ±Rp15.000 per orang** | sampai ±8 Jan |

Porsi yang datang karena teman: 50 dari 100 (ambang ≥30%). Kartu cap memberi nomor dan tanggal kunjungan, jadi "≥40 pelanggan tetap" (board) bisa dihitung dari kartu yang punya dua tanggal berbeda dalam 30 hari.

---

### 7. Sepuluh hook

Satu hook untuk satu keberatan panel. Setiap hook hanya dipakai jika syarat di kolomnya sudah benar.

| # | Format | Teks | Menjawab | Bukti panel | Syarat sebelum dipakai | Cara ukur |
|---|---|---|---|---|---|---|
| H1 | Papan kecil di lapak, deskripsi Maps, sorotan IG "Info", salam otomatis WA | **"Motor parkir di [tempat persis], [tarif nyata / ada juru parkir]. Kami sudah cek sendiri."** | Parkir | P003, P004, P007, P010. P003 batal kalau ada parkir liar mahal | Dicek di lokasi (H-11) bersama pemilik dan juru parkir | Pertanyaan "parkir di mana?" di WA/DM turun |
| H2 | Video, 3 detik pertama | **"Kursi ini sengaja ada sandarannya."** (lanjut: "Duduk 2–3 jam nggak pegal. Tikar cuma buat yang mau selonjoran.") | Duduk lesehan pegal | P007, P008, P018, P019 | Sebagian besar kursi bersandaran sudah dibeli | Komentar dan DM; penilaian tuan rumah di malam latihan |
| H3 | Pesan WA siap-teruskan, status WA | **"Datang berempat atau lebih? WA dulu. Bangkunya kami tahan 15 menit."** | 15 kursi bisa penuh | P004, P007, P008, P014, P018, P020 | Aturan tahan bangku tertulis (§4.3) | Jumlah tahan bangku per minggu; grup yang batal karena penuh |
| H4 | Story IG dan status WA, Jumat–Sabtu pukul 19.30 dan 21.00 | **"Status kursi 20.15: masih ada ±6. Kalau penuh, kami tulis juga."** | Takut datang lalu penuh atau zonk | P008, P014, P018 (sinyal berhenti), P011 | Angkanya benar saat itu. Tidak pernah "tinggal sedikit" jika tidak benar | Jumlah lihat story; tamu yang bilang "lihat status" |
| H5 | Video Reels/TikTok | **"Es kopi susu. Stopwatch jalan. [3] menit."** | Slowbar pasti lama, saya capek | P008 dan P018 (alasan beli); P011, P020 | ≥9 dari 10 pesanan ≤3 menit di malam latihan dan di malam ramai. Jika gagal, hook dibuang | Simpan dan share; log waktu |
| H6 | Kartu meja, diucapkan sebelum bayar, carousel | **"V60 diseduh satu per satu, ±[8] menit. Kami bilang sebelum kamu bayar. Mau cepat? Es kopi susu."** | Menunggu V60 lama | P001 (berhenti jika >15 menit), P015, P018 (berhenti jika >10 menit) | Angka menit dari stopwatch malam latihan (board Product C3) | % tamu menunggu minuman pertama >10 menit |
| H7 | Post feed dan kartu meja | **"Kami baru. Belum ada review. Jadi janjinya begini: tegukan pertama nggak cocok, kami seduh ulang. Gratis."** | Belum ada review | P011, P013, P017, P019 | Garansi seduh ulang tetap ada di offer | Klaim garansi; DM |
| H8 | Post, papan tulis, belakang kartu cap | **"Nunggu review dulu? Santai. Kartu capnya nggak ada tanggal berakhir: 5 malam, gelas ke-6 gratis."** | Penunggu review; tidak ada alasan kembali setelah promo | P016 (minggu 3–4), P013, P017; P002, P003, P012 | Kartu Cap Yok berjalan (§5) | Kartu baru per minggu di minggu 3 dan seterusnya |
| H9 | Video 3 detik pertama, papan di lapak | **"Lapak ini nggak punya colokan. Beneran."** (lanjut: "HP boleh. Laptop istirahat dulu.") | Aturan laptop | P002, P014, P019 (HP cukup); P009, P015 (diterima hilang) | Benar dengan sendirinya | Pertanyaan atau protes soal laptop |
| H10 | Video close-up kartu beans | **"V60 Rp22.000 di lapak? Ini kartu beans-nya: roastery, proses, tanggal sangrai. Silakan cek."** | Curiga beansnya biasa | P001, P006, P016 | Kartu beans untuk setiap beans | Simpan dan DM dari akun pecinta kopi |

---

### 8. Kalender 30 hari: Rab 25 Nov sampai Jum 25 Des 2026 (H = Rab 9 Des)

**Gerbang sebelum H-14** (cek Selasa 24 Nov):
1. **Nama** lolos cek PDKI, dan handle (@lapakyok atau cadangan) aman. Jika belum, posting publik ditunda, tetapi kerja internal tetap jalan.
2. **Tempat** terkunci dengan perjanjian tertulis **paling lambat Minggu 29 Nov** (`lapak-malam.md` §7). Jika belum, H mundur ke Rabu 16 Des dan semua tanggal di bawah bergeser +7 hari. Review 8 minggu ikut mundur ke Selasa 9 Feb, yang hampir bersamaan dengan awal Ramadan (±8 Feb). Catat itu.
3. **Desain spanduk final** dengan jam dua baris (`/founder-brand`).

**Pola minggu:** Rabu–Sabtu = malam buka (setelah H) atau malam kerja lapangan (sebelum H). Minggu–Selasa = founder istirahat dari lapak. Yang keluar di hari itu hanya post yang sudah dijadwalkan.

| Tanggal | H | Malam lapak? | Kanal | Yang keluar / dikerjakan | Hook |
|---|---|---|---|---|---|
| **Rab 25 Nov** | H-14 | Tidak (kerja lapangan) | WA Business, IG/TikTok | Siapkan WA Business: nama, jam "buka 9 Des", katalog menu dan harga, salam otomatis (template E). Post pertama, jika gerbang nama lolos: video 20 detik founder menyeduh dengan kompor gas dan lampu, "Lapak ini nggak punya colokan. Buka 9 Desember, Rawamangun." Belum menyebut alamat | H9 |
| Kam 26 Nov | H-13 | Tidak | WA pribadi | Undangan malam latihan ke 30 tuan rumah (template A): teman kuliah, rekan kantor (cek dulu klausul usaha sampingan di kontrak kerja), tetangga, kenalan komunitas kopi, kontak UNJ. Target 20 yang bilang ya | — |
| Jum 27 Nov | H-12 | Tidak | Percetakan, story | Pesan 500 Kartu Cap bernomor, stempel khusus, kartu meja (tanpa QR dulu), papan tulis status. Story: proof kartu cap | H8 |
| Sab 28 Nov | H-11 | Survei di lokasi 19.00–22.00 | Offline | Cek dari dua arah lalu lintas di mana spanduk dan lampu terbaca dari ±20 m. Cek parkir motor bersama pemilik dan juru parkir, termasuk tarif nyata. Tulis teks H1. Foto teras malam | — |
| Min 29 Nov | H-10 | — | Google Maps | **Gerbang tempat.** Jika perjanjian tertulis sudah ada: buat profil Google ("Lapak Yok", kedai kopi, alamat + pin teras, jam, tanggal buka 9 Des, "Verifikasi nanti"). Jika belum: geser H | — |
| Sen 30 Nov | H-9 | — | IG (terjadwal) | Carousel "Cara pesan di Lapak Yok": cicip dulu, waktu tunggu V60 disebut sebelum bayar, es kopi susu untuk yang buru-buru, seduh ulang kalau tidak cocok | H6, H7 |
| Sel 1 Des | H-8 | — | — | Ambil cetakan. Tidak ada post | — |
| **Rab 2 Des** | H-7 | Uji solo, tanpa tamu | Offline, Google | Stopwatch pemasangan solo. Jika lewat 19.00, jam Rabu–Kamis ditulis 19.30 di **semua** materi. Rekam video verifikasi Google saat spanduk menyala, lalu kirim. Rekam 4–6 klip untuk stok konten | — |
| Kam 3 Des | H-6 | Tidak | TikTok/Reels, WA | Video di balik bar: air di kompor gas, bloom di bawah lampu, grinder tangan. Konfirmasi tuan rumah per malam. Uji alur tahan bangku lewat WA dengan 2 teman | Di balik bar |
| **Jum 4 Des** | H-5 | **Malam latihan 1** (18.00–22.00, dengan helper) | Offline | Tuan rumah dijamu satu minuman. Teman mereka bayar harga normal (uji harga nyata) dan langsung dapat kartu cap. Stopwatch: es kopi susu (gerbang H5), V60 (angka untuk H6), sapaan ≤10 detik. Tanya tuan rumah: kursi bersandaran atau tikar setelah 2 jam? Minta izin masuk daftar siaran WA. **Tidak meminta review** | (uji H2, H5, H6) |
| **Sab 5 Des** | H-4 | **Malam latihan 2** | Offline, story | Sama dengan malam latihan 1, ditambah uji Seduh Bareng pukul 20.00 (15 menit). Uji story status kursi dengan angka asli | (uji H4) |
| Min 6 Des | H-3 | — | WA pribadi | Finalkan angka: jam buka, menit V60, teks parkir, H5 lolos atau tidak, aturan tahan bangku. Ucapkan terima kasih ke tuan rumah, lalu kirim pesan siap-teruskan (template B) untuk grup mereka | H3 |
| Sen 7 Des | H-2 | — | IG (terjadwal), siaran WA | Post "Motor parkir di …". Buat sorotan IG "Info" (parkir, jam, hujan, laptop). Siaran WA #1: "Buka Rabu 9 Des" | H1 |
| Sel 8 Des | H-1 | — | IG (terjadwal), komunitas | Post kursi bersandaran, **hanya jika benar**. Pesan ke 3–5 admin komunitas UNJ dan kantor untuk izin satu posting. Flyer hanya di tempat yang mengizinkan | H2 |
| **Rab 9 Des** | **H** | **Malam pertama** (solo) | Lapak, story | Spanduk menyala, meja seduh menghadap jalan. Kartu cap mulai, untuk semua tamu. Story: "Malam pertama, buka sampai 24.00." Mulai tally: baru/kembali, tahu dari mana, waktu tunggu | H9 (papan) |
| Kam 10 Des | H+1 | Ya (solo) | Google Maps, story | Jika profil sudah terverifikasi: cetak kartu meja ber-QR (fotokopi, ±Rp20–30 rb), lalu minta review ke **semua** tamu (template D) | H7 |
| Jum 11 Des | H+2 | Ya (18.00, helper) | Story/status WA | Status kursi pukul 19.30 dan 21.00. Tahan bangku untuk grup aktif | H3, H4 |
| Sab 12 Des | H+3 | Ya | Offline, IG | **Seduh Bareng #1**, 20.00, 15 menit, gratis untuk yang sedang duduk. Ini malam ritual tetap (board). Rekam tanpa wajah kecuali ada izin. Catat 3 angka minggu 1 | — |
| Min 13 Des | H+4 | — | Internal | 20 menit membaca 3 angka minggu 1, "tahu dari mana", dan log waktu tunggu. Balas semua review. Pilih tiga klip untuk minggu depan | — |
| Sen 14 Des | H+5 | — | IG (terjadwal) | "Nunggu review dulu? Santai. Kartu capnya nggak ada tanggal berakhir." | H8 |
| Sel 15 Des | H+6 | — | WA pribadi | Terima kasih ke tuan rumah yang membawa teman. Tawarkan tahan bangku untuk Jumat–Sabtu | H3 |
| Rab 16 Des | H+7 | Ya (solo) | TikTok/Reels | Video stopwatch es kopi susu, **hanya jika gerbang H5 lolos**. Jika tidak, pakai H6 | H5 / H6 |
| Kam 17 Des | H+8 | Ya (solo) | Story | Jika tally minggu 1 menunjukkan Rabu–Kamis lebih sepi: "Rabu–Kamis biasanya lebih lega." Ini fakta dari data, bukan janji | H4 |
| Jum 18 Des | H+9 | Ya | Story/status WA | Status kursi dan tahan bangku | H3, H4 |
| Sab 19 Des | H+10 | Ya | Offline, IG | **Seduh Bareng #2.** Post "Lapak ini nggak punya colokan." Catat 3 angka minggu 2 | H9 |
| Min 20 Des | H+11 | — | Internal, Google Maps | Review minggu 2: pemicu di §13, hook yang dipertahankan atau dibuang, jumlah kartu baru dan cap kedua. Pasang jam khusus Google untuk 24–25 Des dan 31 Des–1 Jan, sesuai keputusan buka atau tutup | — |
| Sen 21 Des | H+12 | — | IG (terjadwal), siaran WA | Video kartu beans dan tanggal sangrai. Siaran WA #2: jam libur akhir tahun dan Seduh Bareng Sabtu | H10 |
| Sel 22 Des | H+13 | — | — | Di rencana lama, Ajak Teman berakhir malam ini. Di rencana ini tidak ada yang berakhir, jadi tidak ada post "hari terakhir". Siapkan post H+14 | — |
| Rab 23 Des | H+14 | Ya (solo) | IG | "Dua minggu pertama: yang kami ubah dari masukan tamu", hanya perubahan yang benar-benar dilakukan. Menjawab "tempat baru ramai sebentar lalu turun" (P013, P016, P017). Angka #3 kohort minggu 1 pertama kali terbaca | — |
| Kam 24 Des | H+15 | Ya, atau tutup (keputusan founder, sudah dipasang di Maps sejak 20 Des) | Story | Jika buka, catat sebagai **malam libur**, terpisah dari tren | H4 |
| **Jum 25 Des** | H+16 | Libur Natal. Jika buka: 18.00–24.00 dengan helper | Story | Post hanya info jam. Malam ini ditandai "libur". Rapat bulan 2 dijadwalkan Minggu 27 Des: kanal yang lolos diteruskan, kreator ya/tidak (§4.6), cetak ulang | — |

**Rencana hujan** (Desember–Januari musim hujan; syarat board Offers C4): story pukul 18.00 berisi "Buka. Tenda terpasang, ada [n] kursi kering", atau "Tutup malam ini" jika memang tutup. Malam hujan dicatat terpisah untuk review 2 Feb.

---

### 9. Kalau tidak ada yang baru untuk diposting

Isi dengan cerita di balik bar. Jangan merekayasa keramaian.

1. Memasang tenda dan lampu dari 18.00 ke 19.00 (*timelapse* 20 detik).
2. Air mendidih di kompor gas, tanpa suara selain desisnya.
3. Bloom V60 di bawah lampu baterai, dari dekat.
4. Grinder tangan: berapa putaran untuk satu gelas.
5. Membuka kantong beans baru dan membaca tanggal sangrainya (H10).
6. Kartu beans minggu ini: dari mana kopinya (syarat board C2).
7. Menyiapkan konsentrat cold brew di rumah, malam sebelumnya.
8. Pertanyaan tamu minggu ini dan jawabannya. Nama hanya disebut dengan izin.
9. Satu kesalahan minggu ini dan apa yang diubah.
10. Malam hujan: cara tenda dan kursi diatur supaya tetap kering.
11. Info praktis: parkir, rute dari halte Pemuda Rawamangun atau LRT Velodrome, jam buka.
12. Pukul 24.00: mematikan lampu terakhir, melipat kursi, mencuci alat.

---

### 10. Template

**A. Undangan tuan rumah (WA pribadi dari founder)**
> Halo [nama], ini [nama founder]. Aku buka lapak kopi kecil, Lapak Yok, di [alamat singkat], Rawamangun. Kopinya diseduh manual tanpa listrik, ada makanan angkringan. Buka mulai Rabu 9 Desember, Rabu–Sabtu malam. Sebelum buka aku latihan dua malam: Jumat 4 Des dan Sabtu 5 Des, jam 18.00–22.00. Kamu yang paling sering ngajak geng nongkrong, jadi aku mau menjamu: minuman pertamamu dari aku. Teman yang kamu bawa bayar harga biasa (sekalian uji harga). Mau datang malam yang mana, berapa orang? Kalau nggak bisa, santai.

**B. Pesan siap-teruskan** (disediakan Lapak Yok; tamu yang memutuskan mau mengirim atau tidak)
> Ada lapak kopi malam baru di Rawamangun: Lapak Yok, [alamat singkat] ([pin]). Rab–Kam [19.00]–24.00, Jum–Sab 18.00–24.00. Kopi diseduh di depan kita, ada nasi kucing dan gorengan. HP boleh, laptop istirahat. Parkir motor: [info]. Nggak usah pindah langganan, sekali aja bareng geng. Datang berempat atau lebih? Tahan bangku: wa.me/[nomor]. [Hari] jam [..], siapa ikut?

Aturan template B: isinya hanya fakta. Jangan menaruh penilaian seperti "enak banget" di mulut tamu.

**C. Kartu Cap Yok** (ukuran kartu nama, Biru Malam di atas Kertas, bernomor)
- **Depan:** "Kartu Cap Yok · No. ____ · 5 kotak cap (tanggal di tiap kotak) · 5 cap = gelas ke-6 gratis."
- **Belakang:**
  - "1 cap tiap malam kamu jajan Rp25.000 ke atas."
  - "Bawa teman yang baru pertama kali: +1 cap buat kamu."
  - "Nggak ada tanggal berakhir."
  - "Cap nggak pernah ditukar dengan review atau follow."
  - "Tahan bangku: WA [nomor] · HP boleh, laptop istirahat."

**D. Kartu meja / QR review** (untuk semua tamu, tanpa imbalan)
> Kami baru buka dan belum punya banyak review. Kalau sempat, ceritakan pengalamanmu di Google Maps, yang enak maupun yang kurang. Kami baca dan balas semuanya. Tidak ada hadiah untuk review, dan kartu capmu tidak berubah. [QR]

**E. Salam otomatis WhatsApp Business**
> Halo! Ini Lapak Yok, [alamat] ([pin]). Buka Rab–Kam [19.00]–24.00, Jum–Sab 18.00–24.00. Parkir motor: [info]. HP boleh, laptop istirahat (lapak kami memang tanpa listrik). Mau tahan bangku untuk 4 orang atau lebih? Balas: nama, jumlah orang, jam datang. Bangku ditahan 15 menit. Founder sedang menyeduh, jadi balasan bisa agak lama. Maaf ya.

**F. Brief kreator** (hanya bulan 2, jika syarat §4.6 terpenuhi)
- **Saat datang:** kreator datang sebagai tamu di Rabu atau Kamis, dan bebas berpendapat, termasuk menyampaikan yang kurang. Pembayaran tidak bergantung pada nada ulasan.
- **Wajib diungkap:** "#iklan" atau "kerja sama berbayar" di awal caption, ditambah label kemitraan berbayar dari platform, juga jika imbalannya hanya produk.
- **Fakta yang harus benar:** alamat, jam, parkir, aturan laptop, harga, dan aturan kartu cap.
- **Dilarang:**
  - klaim kesehatan;
  - "terbaik" atau "nomor 1";
  - "viral" atau "tinggal sedikit";
  - menyindir tempat lain;
  - meminta penonton menulis review.

---

### 11. Anggaran

Mengikuti model CFO: **Rp1.000.000 marketing pembukaan** (startup) dan **Rp500.000 per bulan**. Spanduk dan papan nama (Rp700 ribu) serta lampu (Rp600 ribu) sudah ada di startup dan tidak diambil dari sini. Semua harga cetak adalah **[estimasi]**. Minta dua penawaran.

**Pembukaan: Rp1.000.000** (25 Nov sampai ±8 Jan)

| Pos | Kanal | Rp |
|---|---|---:|
| 500 Kartu Cap Yok bernomor (1 warna) dan stempel khusus | WA / ajakan teman | 250.000 |
| Dua malam latihan: satu minuman dan cicip untuk ±25 tuan rumah (HPP ±Rp8.000), ditambah gorengan cicip | WA / ajakan teman | 250.000 |
| Kartu meja laminasi: laptop, cara pesan dan waktu tunggu, QR review (QR dicetak setelah verifikasi) | Lapak + Maps | 100.000 |
| Papan kecil "Parkir motor →" dan papan tulis status (kursi, menit V60, hujan) | Lapak + Maps | 150.000 |
| Tripod HP dan lampu klip baterai untuk konten | IG/TikTok | 120.000 |
| 200 flyer A6 untuk kantor dan komunitas yang mengizinkan | WA (sumber tuan rumah) | 60.000 |
| Cadangan | — | 70.000 |
| **Total** | | **1.000.000** |

**Bulanan: Rp500.000** (bulan 1 = 9 Des sampai 8 Jan)

| Pos | Kanal | Rp |
|---|---|---:|
| Seduh Bareng setiap Sabtu (4–5 × ±Rp35.000–40.000 beans dan cup cicip) | WA / komunitas | 160.000 |
| Jamuan kecil untuk kumpul perdana satu komunitas lokal (syarat board: satu komunitas yang kumpul rutin) | WA / komunitas | 100.000 |
| Cetak ulang (kartu meja QR, kartu cap) | Lapak + Maps | 60.000 |
| Cadangan. Dipakai untuk hadiah kartu cap **jika CFO belum memasukkannya sebagai biaya variabel** (model `cfo.md` lama belum, `numbers.json` v3 sudah: Rp560/tamu), atau untuk kreator di bulan 2 (§4.6) | — | 180.000 |
| **Total** | | **500.000** |

**Per kanal, 30 hari pertama (Rp1,5 juta)**

| Kanal | Rp | Porsi |
|---|---:|---:|
| Ajakan teman lewat WA dan komunitas (kanal utama) | 820.000 | ±55% |
| Lapak + Google Maps | 310.000 | ±21% |
| Instagram + TikTok | 120.000 | 8% |
| Cadangan | 250.000 | ±17% |
| Iklan berbayar | 0 | 0% |
| **Total** | **1.500.000** | |

**Biaya yang tidak tercatat:** waktu founder sekitar 3 jam per minggu di luar malam buka (konten terjadwal, balas WA, balas review), ditambah story pada malam buka. Jangan menambah anggaran di luar model sebelum mengecek batas di §12.

---

### 12. Batas biaya untuk memenangkan satu pelanggan

**Rumus:** kontribusi per kunjungan × kunjungan per pelanggan.

- **Kontribusi per kunjungan: Rp14.105** (`cfo.md`: belanja Rp28.000 dikurangi biaya variabel Rp13.895).
- **Kunjungan per pelanggan, angka lantai: 1,7 di bulan 1** (panel lapak: 17 pembelian ÷ 10 pembeli). Tanpa tiga pemburu promo, angkanya tetap 1,71 (12 ÷ 7).
- **Kartu cap tidak mengurangi angka bulan 1,** karena hampir tidak ada yang mencapai 5 cap sebelum minggu ke-4 atau ke-5.

```
Batas keras = Rp14.105 × 1,7 = Rp23.978,5  →  dibulatkan ke bawah: Rp23.900
```

Membayar Rp23.900 untuk satu pelanggan baru hanya balik modal dari kunjungan bulan pertamanya, tanpa sisa untuk sewa, helper, atau gas. Jadi ini **batas atas, bukan target.**

*Cek silang dengan offer v3 yang ditulis paralel:* `numbers.json` v3 memakai belanja Rp29.000 dan kontribusi Rp13.768, yang sudah termasuk kartu cap. Dengan angka itu, batasnya Rp13.768 × 1,7 = Rp23.405, dibulatkan menjadi **Rp23.400**. Selisihnya kecil, dan keputusan di bawah tidak berubah.

**Rentang 6 bulan.** Ini asumsi eksplisit yang belum terbukti, karena panel hanya ditanya soal bulan pertama.

| Skenario | Asumsi | Kunjungan dalam 6 bulan | Kontribusi kotor (× Rp14.105) | Kartu cap | Nilai bersih |
|---|---|---:|---:|---|---:|
| Lantai | Data panel, hanya bulan 1 | 1,7 | Rp23.979 | 0 (belum 5 cap) | **Rp23.979** |
| Rendah | 3 dari 10 datang sekali lagi di bulan 2–6 | 2,0 | Rp28.210 | 0 | **Rp28.210** |
| Tengah | 1,7 di bulan 1, lalu ±0,5 per bulan × 5 bulan | 4,2 | Rp59.241 | 0–1 gelas (HPP Rp6.890) | **Rp52.351–59.241** |
| Tinggi | Geng nongkrong rutin: 2 di bulan 1, lalu 2 per bulan | 12 | Rp169.260 | 2 gelas: HPP Rp13.780; terburuk Rp44.000 | **Rp125.260–155.480** |

- **Batasnya tetap Rp23.900** sampai angka mingguan #3 (kembali dalam 14 hari) membuktikan skenario yang lebih tinggi.
- **Cek silang:** Rp23.900 adalah ±40% dari nilai skenario tengah. Kalaupun skenario tengah benar, membayar sampai batas masih menyisakan sekitar 60% kontribusi untuk biaya tetap.
- **Rencana dibandingkan dengan batas:**
  - Rp1,5 juta ÷ 100 pelanggan baru di bulan 1 = **±Rp15.000 per orang** (63% dari batas).
  - Batas tercapai jika hanya ±63 pelanggan baru di bulan 1, atau ±15 per minggu.
  - Di bawah itu, hentikan pengeluaran yang bisa ditunda (jamuan komunitas, cetak ulang, kreator) dan jalan dengan kanal gratis saja.
- **Pemburu promo yang datang sekali hanya untuk minuman setengah harga** menyisakan ±Rp5.280. Uang berapa pun untuk menarik mereka adalah rugi. Itu sebabnya promo tidak pernah menjadi judul.

---

### 13. Tiga angka mingguan

**Cara mencatat** (tugas `/founder-ops`): lembar tally di bar, sekitar 5 detik per tamu.
- **Baru atau kembali.**
- **Tahu dari mana:** teman, lewat depan, Maps, IG/TikTok, kampus/kantor, atau lainnya.
- **Datang bersama tamu yang sudah pernah ke sini?**
- **Minuman pertama >10 menit?**
- **Grup yang batal karena penuh.**

Saat memberi cap kedua, lihat tanggal cap pertama di kartu. Jika jaraknya ≤14 hari, beri tanda "K14" di minggu kartu itu dibuat. Malam hujan dan malam libur (24–25 Des, 31 Des–1 Jan) ditandai terpisah.

Angka-angka ini terikat ke break-even: **21 tamu bayar/malam** di belanja Rp28.000, atau **omzet ±Rp588.000 per malam** (Rp609.000 dengan belanja Rp29.000 di offer v3).

| # | Angka | Cara hitung | Target | Ubah sesuatu jika | Yang diubah |
|---|---|---|---|---|---|
| 1 | **Tamu bayar per malam buka** (rata-rata minggu itu; Rabu–Kamis dan Jumat–Sabtu dipisah) | Qasir atau tally ÷ jumlah malam buka | Minggu 1–2 (9–19 Des): **≥10** (ramp CFO). Minggu 3–4 (23 Des–2 Jan, libur): ≥10, dibaca terpisah. Minggu 5 (6–9 Jan): **≥15**. Minggu 6–8 (13–30 Jan): **≥21** | **Di bawah target dua minggu non-libur berturut-turut.** **Merah: minggu 5 di bawah 15** (21 × 0,7, skenario CFO "tamu −30%"). Ambang 2 Feb hampir pasti gagal, jadi diagnosis dimulai saat itu juga, bukan 2 Feb. **Jika tamu ≥21 tetapi omzet per malam di bawah Rp588.000,** belanja per tamu yang turun, dan break-even belum tercapai | Lihat "tahu dari mana": sumber mana yang kering. Jumat–Sabtu penuh tetapi Rabu–Kamis kosong: dorong Rabu–Kamis (H4 "lebih lega", arahkan tahan bangku ke Rabu–Kamis). Semua malam sepi: cek apakah spanduk terbaca dari jalan, tambah undangan tuan rumah, dan baru setelah itu pertimbangkan pindah ke Jl. Pemuda (`lapak-malam.md`). **Jangan menambah malam buka** |
| 2 | **Tamu baru per minggu** (sekaligus biaya per pelanggan baru) | Tanda "baru" di tally. Kartu cap baru menjadi cek silang | Minggu 1–4: **≥25 per minggu** (±100 di bulan 1). Minggu 5–8: **≥40 per minggu**. Model kasar [Menebak]: pada tingkat kembali 25%, 21 tamu/malam butuh ±40 tamu baru per minggu; pada 40%, ±30 | **Di bawah 25 per minggu (minggu 1–4) atau 40 (minggu 5–8), dua minggu berturut-turut.** **Di bawah 15 per minggu:** biaya per pelanggan baru sudah di atas Rp23.900, jadi hentikan pengeluaran yang bisa ditunda | Tambah tuan rumah baru. Kirim ulang template B lewat tuan rumah yang paling aktif (lihat siapa yang paling sering mendapat cap bonus). Pakai hook dengan simpan/DM tertinggi di papan dan story. **Bukan** iklan berbayar |
| 3 | **Persentase tamu baru yang kembali dalam 14 hari** | Tanda K14 ÷ kartu baru di minggu yang sama. Pertama terbaca 23 Des untuk kohort minggu 1 | **≥25%** (ambang 2 Feb), sasaran 40% | **Di bawah 25%.** **Di bawah 15%:** tahan semua pengeluaran akuisisi, karena tamu baru akan bocor lagi | Ini masalah pengalaman, bukan iklan. Cek waktu tunggu (>20% tamu malam solo menunggu >10 menit: tambah helper Kamis atau tutup Kamis, sesuai board Product C6), kursi, penuh, parkir, dan semua review. Tanya 5 tamu yang tidak kembali kenapa |

**Cek pendukung (bukan tiga angka utama):**
- **Belanja per tamu ≥Rp28.000.** Di Rp27.000, break-even naik ke 22. Di Rp26.000, naik ke 24.
- **Persentase tamu baru yang datang karena diajak teman ≥30%** (ambang 2 Feb). Jika di bawah itu, kanal utama tidak berjalan: tanya 5 tuan rumah kenapa mereka tidak mengajak.
- **Persentase tamu yang menunggu minuman pertama >10 menit**, dan **grup yang batal karena penuh.** ≥3 grup per malam Jumat–Sabtu berarti aturan tahan bangku atau tata kursi di dalam persil perlu diubah.
- **Review Google:** jumlah, rating, dan waktu balas. Target ≥10 di 9 Jan dan ≥20 di 2 Feb.
- **Pelanggan tetap** (kartu dengan dua tanggal berbeda dalam 30 hari): target ≥40 di 2 Feb (board).
- **Hadiah kartu cap yang ditukar per bulan,** dibandingkan dengan perkiraan ±Rp595 per kunjungan. Jika jauh di atasnya, pindah ke varian 6 cap untuk kartu baru.
- **Malam hujan dan malam libur** dicatat terpisah, supaya tidak dibaca sebagai tren.

---

### 14. Aturan untuk semua materi

- **Tidak ada review palsu.**
  - Founder, keluarga, helper, kreator, dan tuan rumah yang dijamu gratis tidak menulis review Google.
  - Tidak ada imbalan apa pun untuk review, termasuk diskon, minuman, atau cap.
  - Minta review ke semua tamu, bukan hanya yang tampak puas. Jangan meminta bintang tertentu, isi tertentu, atau nama barista disebut.
- **Kutipan panel adalah riset, bukan testimoni.** P001–P020 adalah pembeli simulasi dan tidak pernah dikutip di spanduk, post, pesan WA, atau iklan. Story tamu hanya di-repost dengan izin, tanpa diubah, dan tidak dijadikan iklan.
- **Tidak ada angka follower**, "viral", "ramai dibicarakan", "as seen on", atau foto keramaian rekayasa.
- **Kerja sama berbayar wajib diungkap.** Tulis "#iklan" atau "kerja sama berbayar" di awal caption, ditambah label kemitraan berbayar dari platform, juga untuk imbalan berupa produk (Etika Pariwara Indonesia: iklan harus bisa dikenali sebagai iklan).
- **Tidak ada klaim kesehatan.**
  - Dilarang: "kopi menghilangkan stres", "kopi sehat", "bikin fokus", "detoks", "aman untuk lambung".
  - "Tempat melepas penat bareng teman" boleh, karena itu tentang tempatnya. "Kopi yang melepas penat" tidak boleh.
- **Tidak ada klaim halal atau logo halal** sebelum sertifikat (atau *self-declare* SEHATI) benar-benar terbit (`lapak-malam.md` §5).
- **Tidak ada kelangkaan palsu.**
  - Kartu cap tidak punya tanggal berakhir.
  - Status kursi hanya angka yang benar saat itu.
  - "Tinggal sedikit" hanya boleh ditulis jika memang benar.
- **Klaim yang harus dibuktikan dulu:** "3 menit" (≥9/10 di stopwatch), menit tunggu V60, info parkir, dan kursi bersandaran.
- **Jam di semua materi sama dengan jam yang lolos uji pemasangan** (19.00 atau 19.30 untuk Rabu–Kamis), termasuk di Google Maps dan jam khusus hari libur.
- **Tidak ada superlatif tanpa bukti** ("terbaik", "nomor 1", "termurah di Rawamangun"). Tidak menyebut atau menyindir Hulu, YO'KOPI, warkop, atau kafe lain.
- **Daftar siaran WA hanya untuk yang sudah setuju** (UU 27/2022 PDP). Paling banyak satu pesan per minggu, dengan "balas STOP". Wajah tamu di konten hanya dengan izin.
- **Semua materi fisik di dalam batas persil.** Tidak ada spanduk di fasilitas umum atau papan di trotoar.
- **Ini bukan nasihat hukum.** Cek aturan iklan sebelum memakai iklan berbayar dalam skala apa pun.

---

### 15. Serah-terima dan keputusan

**Tiga keputusan untuk founder:**
1. **Kartu Cap Yok menggantikan Ajak Teman** (rekomendasi), atau berjalan bersama Ajak Teman (kartu tetap dimulai malam pertama, Ajak Teman berakhir Sel 22 Des pukul 24.00).
2. **Sebagian besar tempat duduk berupa kursi bersandaran**, bukan tikar. Ini mengubah daftar belanja startup. Tanpa ini, hook H2 tidak boleh dipakai.
3. **Buka atau tutup pada 24–25 Des** (dan 31 Des–1 Jan). Putuskan sebelum Minggu 20 Des, supaya jam khusus di Google Maps benar.

**Untuk `/founder-cfo`:**
- Hadiah kartu cap ±Rp595 per kunjungan [Menebak]. Di `numbers.json` v3 garisnya Rp560, jadi selisihnya +Rp35. Di `cfo.md`, kartu ini belum dihitung, dan break-even menjadi 21,0 (22 jika dibulatkan ke atas) kecuali belanja naik ≥Rp100.
- Diskon Ajak Teman tidak pernah ada di model. Jika founder tetap memakainya, catat ±Rp200–250 ribu.

**Untuk `/founder-ops`:**
- Lembar tally dan tanda K14.
- SOP kartu cap: nomor, stempel, dan tanggal.
- Aturan tahan bangku (maksimal 2 meja Jumat–Sabtu pukul 19.00–22.00).
- Info parkir yang diverifikasi.
- Kursi bersandaran.
- Izin alamat untuk Google di perjanjian tempat.
- Balas review paling lambat 24 jam.

**Untuk `/founder-brand`:**
- Spanduk dengan jam dua baris, terbaca dari ±20 m dan disinari lampu.
- Desain Kartu Cap Yok, kartu meja, dan papan tulis status.
- Ikon 32px untuk WA, IG, dan TikTok.

**Untuk `/founder-launch`:**
- Gerbang nama (24 Nov) dan gerbang tempat (29 Nov).
- Uji solo Rab 2 Des.
- Malam latihan Jum 4 dan Sab 5 Des, dengan stopwatch.
- Seduh Bareng setiap Sabtu pukul 20.00.
- Rapat bulan 2 Minggu 27 Des.

**Untuk `/founder-consumer --quick`:** uji ulang pitch dengan Kartu Cap Yok menggantikan Ajak Teman, sebelum 9 Des jika sempat.

**Berikutnya:** `/founder-brand` untuk touchpoint lapak, lalu `/founder-launch`.

## Brand

> **Sumber:** `brand-kafe.md` (brief brand kafe: suara, palet, huruf, kartu "HP boleh, laptop tidak"), `research/nama-yok.md` (riset nama "Yok …"), `lapak-malam.md` (rencana v3), `pitch.md`, `panel/results.md` dan `panel/answers/` (panel pembeli simulasi untuk pitch lapak), `numbers-lapak.json`, `marketing-kafe.md` §10 (template). Ditulis 8 November 2026.
>
> **Cara baca label:** [Pasti] = bukti kuat atau hasil hitungan · [Kemungkinan Besar] = inferensi kuat · [Menebak] = estimasi saya, harus diuji.
>
> - **Hanya pencarian publik.** Lima pencarian cepat hari ini, khusus "Lapak Yok" dan "Yok Leyeh" (bagian 1.5). PDKI, Instagram, TikTok, domain, GoFood/Grab, dan Google Maps tidak dibuka langsung. **Tidak ditemukan bukan berarti tersedia.**
> - **Ini bukan nasihat hukum.** Yang bisa memastikan sebuah nama aman dan bisa didaftarkan adalah **Konsultan KI terdaftar** di DJKI. Indonesia memakai sistem *first-to-file*: nama baru terlindungi setelah diajukan, dan yang lebih dulu mengajukan yang didahulukan.
> - Riset merek "Kopiyo" tidak diulang di sini. Lihat `brand-kafe.md` §3.

### Ringkasan

- **Nama: Lapak Yok** (cadangan: Yok Leyeh). Untuk format ini Lapak Yok menang di tiga uji yang paling penting selama delapan minggu pertama: terbaca di spanduk malam dari 20 m, alami sebagai ajakan WA ("Yok, ke Lapak Yok."), dan langsung memberi tahu orang yang lewat bahwa ini tempat jualan. Yok Leyeh lebih kuat sebagai merek dan lebih netral kalau nanti pindah format, tetapi bertabrakan dengan LL Coffee (@leyehleyehcoffee) justru di Jogja. **Syaratnya:** Konsultan KI menilai "Lapak Yok" bisa didaftarkan sebagai **kata + logo** di kelas 43, dan uji 10 orang lolos.
- **Janji:** *Rabu sampai Sabtu malam, lampu Lapak Yok nyala sampai 24.00: kursi buat duduk lama, kopi yang diseduh di depanmu, dan nggak ada yang nyuruh buru-buru.*
- **Tagline utama:** *Pulang kerja, yok nongkrong dulu.* Dua lainnya: *Lampu udah nyala. Yok.* dan *Bawa gengmu, yok. Kursinya kami siapin.*
- **Suara tetap hangat, jujur, tenang** (dari `brand-kafe.md`).
- **Palet tetap:** Biru Malam `#232647`, Lampu `#F0A83C`, Kertas `#F7EFE1`. Yang berubah adalah porsinya: tanpa listrik, papan tidak bisa menyala sendiri, jadi **bidang spanduk memakai Kertas** (memantulkan cahaya ±40× Biru Malam) dengan huruf Biru Malam. Semua pasangan teks yang dipakai lulus WCAG AA, dan malah naik kontrasnya di bawah lampu hangat: 7,20–12,77:1 standar, ±9,19–13,62:1 di 2700K (perkiraan).
- **Spanduk:** "LAPAK YOK" + gelembung "yok", di bawahnya "KOPI SEDUH · ANGKRINGAN". Ukuran 300 × 75 cm, tinggi huruf nama 27 cm, bahan doff, diterangi dua lampu batang LED hangat.
- **Menjawab keraguan panel:** semua 15 kursi bersandaran, bukan tikar (P007, P008, P018). Satu sudut foto yang jujur: seduhan V60 di bawah satu lampu, dengan panel gelap di belakangnya supaya uapnya terlihat (P005, P010, P011). Papan antrean V60 ditulis tangan (P001, P018, P020). Kartu reservasi WA untuk rombongan (P004, P007, P014). Info parkir hanya setelah lokasi pasti (P003, P004, P010).
- **Minggu ini (9–15 Nov):** cek PDKI, amankan @lapakyok, uji nama ke 10 orang, temui Konsultan KI. **Ajukan merek kelas 43 paling lambat Selasa 24 Nov 2026**, sebelum post publik pertama (H-14, Rabu 25 Nov).

#### Yang dipakai ulang dari `brand-kafe.md` dan yang berubah

| Hal | Status untuk lapak | Kenapa |
|---|---|---|
| Suara hangat, jujur, tenang | **Dipakai** | Cocok dengan angkringan malam yang tidak terburu-buru |
| Palet tiga warna | **Dipakai, porsinya diubah** | Papan kafe menyala dari dalam. Spanduk lapak hanya disinari lampu baterai, jadi bidang terangnya harus Kertas |
| Fraunces + Plus Jakarta Sans (OFL) | **Dipakai** | Gratis untuk pemakaian komersial. Fraunces tebal terasa seperti huruf cat gerobak |
| Kartu "HP boleh, laptop tidak" | **Dipakai, teksnya disesuaikan** | Di lapak memang tidak ada colokan, jadi aturannya jadi fakta, bukan larangan |
| Kartu beans | **Dipakai** | Ukuran huruf dinaikkan karena dibaca di bawah lampu redup |
| Nama Meja Pelan, tagline "Ngobrol sampai larut" | **Tidak dipakai** | Founder memilih nama dari ajakan "yok". Meja Pelan tetap jadi jalan keluar kalau kedua nama "yok" gagal (`research/nama-yok.md` §4 langkah 9) |
| "Harga belum termasuk PBJT 10%" | **Tidak ditulis** | PBJT belum berlaku di omzet lapak (`lapak-malam.md` §4). Harga yang ditulis adalah harga final. Konfirmasi ke akuntan atau KPP; tulis ulang kalau omzet naik |
| Jam 16.00–24.00 setiap hari | **Diganti** | Rabu–Kamis 19.00–24.00, Jumat–Sabtu 18.00–24.00 |

---

### 1. Memo keputusan nama: Lapak Yok atau Yok Leyeh

**Pertanyaannya:** nama mana yang paling bekerja untuk lapak tenda malam tanpa listrik, ±15 kursi, di teras ruko Rawamangun, yang tamunya datang karena diajak teman lewat WhatsApp, dan yang mungkin pindah ke kios atau ke Jogja nanti.

#### 1.1 Empat uji

| Uji | Lapak Yok | Yok Leyeh | Unggul |
|---|---|---|---|
| **Spanduk tenda malam, dibaca dari 10–20 m** | Dua kata yang sangat dikenal (5 + 3 huruf). Bentuk hurufnya beragam: L, A, P, K, Y, O punya diagonal dan lubang terbuka yang tetap berbeda saat buram. Kata yang dikenal terbaca dari jarak lebih jauh daripada kata asing, karena mata melengkapi sisanya [Kemungkinan Besar] | "LEYEH" berisi E-Y-E-H. Huruf E dan H sama-sama dari batang tegak dan garis datar, jadi di cahaya redup mudah menyatu ("LEVEH", "LEYEN"). Kata ini juga kurang dikenal di Jakarta, jadi mata tidak bisa menebak | **Lapak Yok** |
| **Ajakan WA "Yok, ke ___"** | "Yok, ke Lapak Yok." Gema "yok" terasa alami, dan "lapak" langsung terbaca sebagai nama tempat. Teman yang diajak bisa mengetik "lapak yok rawamangun" | "Yok, ke Yok Leyeh." tersandung di "yok, ke yok". Orang cenderung menyingkat jadi "ke Leyeh", lalu mencari "leyeh" dan bisa menemukan LL Coffee (@leyehleyehcoffee) atau Leha Leha Cafe di Jatiwaringin. Ejaan yang didengar juga bisa salah ("leye", "leyé") (`research/nama-yok.md` §3.2) | **Lapak Yok** |
| **Ikon 32 px** | Gelembung chat berisi "yok" | Gelembung chat berisi "yok" | **Seri.** Ikon tidak menentukan |
| **Pindah ke kios kecil** | Kios tetap sebuah lapak, jadi nama tetap jujur | Netral terhadap format | Seri |
| **Pindah ke ruko atau kafe** | Terasa kecil, tapi bisa menjadi cerita asal ("dulu lapak") | Netral terhadap format, lebih mudah naik kelas | **Yok Leyeh** |
| **Pindah ke Jogja** | "Lapak" dan "yok" dipahami. Tidak ditemukan usaha bernama sama | Rasanya paling Jawa dan paling pas, **tetapi** LL Coffee (@leyehleyehcoffee) ada di Jl. Kaliurang km 15, wilayah Jogja | **Lapak Yok** (risiko lebih kecil) |
| **Kekuatan sebagai merek** | **Sedang.** "Lapak" kata umum seperti "warung". Hari ini juga terlihat "Lapak Awak Cafe" di Facebook (bagian 1.5), jadi pola "Lapak ___" memang dipakai orang lain. Perlu **kata + logo** | **Lebih kuat.** "Leyeh" tidak menerangkan kopi | **Yok Leyeh** |
| **Apa yang ditangkap orang yang lewat** | "Ada tempat jualan kecil di sini, dan ini ajakan." Format langsung jelas | Suasana santai, tapi tidak bilang ada jualan apa. Bergantung pada baris kedua | **Lapak Yok** |

#### 1.2 Risiko yang jujur soal "lapak"

Panel memakai kata yang sama dengan nada meremehkan: *"Lapak tikar di teras ruko kedengarannya biasa aja"* (P011). Kata "lapak" menurunkan harapan. Itu bisa jadi keuntungan, karena tamu datang tanpa harapan kafe lalu menemukan kursi bersandaran, lampu hangat, dan V60 diseduh di depannya. Tapi itu juga berarti **tampilan lapak harus bekerja keras** (bagian 4). Nama yang jujur tidak boleh dipasangkan dengan tikar, lampu putih, dan spanduk asal cetak.

#### 1.3 Keputusan

**Pakai Lapak Yok** untuk lapak malam ini, dengan dua syarat:

1. **Konsultan KI** menilai "Lapak Yok" bisa didaftarkan di kelas 43 sebagai **kata + logo**.
2. **Uji 10 orang** (`research/nama-yok.md` §4 langkah 7) lolos: kurang dari 3 dari 10 orang yang salah eja, mengira "lapak online", atau menyebutnya "murahan".

**Pindah ke Yok Leyeh** jika salah satu syarat gagal. Sebelum pindah, cek dulu apakah LL Coffee sudah mendaftarkan "Leyeh" di PDKI. **Jika keduanya gagal**, pakai nama tanpa "yok" (misalnya Meja Pelan dari `brand-kafe.md`) dan pindahkan ajakan "yok" ke tagline. Keputusan akhir tetap di tangan founder.

**Kenapa uji spanduk dan WA lebih berat daripada kekuatan merek di sini:** delapan minggu pertama adalah ujinya (`lapak-malam.md` §7), dan kanal utamanya ajakan teman lewat WA (`marketing-kafe.md` §4). Nama yang lebih kuat di atas kertas tapi tersandung di setiap pesan WA akan merugikan tepat di masa uji itu.

#### 1.4 Uji murah sebelum mencetak apa pun

| Uji | Caranya | Lolos jika |
|---|---|---|
| Spanduk 20 m | Cetak huruf "Y", "O", "K" setinggi 27 cm, satu huruf per lembar A3, dalam dua varian: Biru Malam di atas Kertas, dan Kertas di atas Biru Malam. Tempel di tembok malam hari, terangi dengan lampu LED yang akan dipakai, lihat dari 10 m dan 20 m bersama 3 orang | Ketiganya membaca dengan benar dari 20 m. Pilih varian yang terbaca lebih dulu |
| Ajakan WA | Kirim "Yok, ke Lapak Yok jam 8?" ke 10 orang tanpa penjelasan | ≥8 dari 10 langsung paham itu nama tempat |
| Ejaan | Ucapkan nama, minta 10 orang mengetiknya di HP | ≥8 dari 10 benar |
| Ikon | Ekspor ikon 32 px dan 16 px, lihat di daftar chat WA dan lingkaran avatar IG | "yok" terbaca di 32 px |

#### 1.5 Cek cepat hari ini (5 pencarian, 8 Nov 2026)

| Pencarian | Hasil |
|---|---|
| "yokleyeh" / "yok.leyeh" / "yok_leyeh" | Tidak ada halaman yang memuat kata ini |
| "Yok Leyeh" + kopi/angkringan/cafe/kedai | Tidak ditemukan usaha bernama "Yok Leyeh" |
| "lapakyok" / "lapak.yok" / "lapak_yok" | Tidak ada hasil yang terkait |
| "Lapak Yok" + kopi/angkringan/nongkrong | Tidak ditemukan usaha bernama "Lapak Yok" |
| Keempat nama, dibatasi ke instagram.com, tiktok.com, x.com, facebook.com, gofood.co.id, food.grab.com | Tidak ada akun @lapakyok atau @yokleyeh yang terindeks. Muncul satu video Facebook **"Lapak Awak Cafe"** (ruko di Jl. Sultan Hasanuddin / Jl. Ombak, kotanya tidak jelas dari cuplikan) yang memakai "yok" sebagai ajakan. Namanya berbeda, tapi menunjukkan pola "Lapak ___ Cafe" sudah dipakai |

**Artinya:** celah di `research/nama-yok.md` (handle @yokleyeh belum dicek) sekarang sebagian tertutup. Di indeks mesin pencari tidak ada apa-apa.

**Yang tetap belum bisa saya verifikasi:**
- apakah handle @lapakyok dan @yokleyeh benar-benar kosong di Instagram, TikTok, X, dan YouTube (aplikasinya tidak bisa dibuka dari sesi ini);
- status merek di PDKI;
- domain lapakyok.id dan lapakyok.com;
- merchant di aplikasi GoFood dan GrabFood;
- usaha bernama mirip di Google Maps Rawamangun dan Jogja.

#### 1.6 Langkah merek di PDKI (bukan nasihat hukum)

| Langkah | Kapan | Isi |
|---|---|---|
| 1. Cari di PDKI | Hari 1–2 (9–10 Nov) | Buka [pdki-indonesia.dgip.go.id](https://pdki-indonesia.dgip.go.id), pilih **Merek**. Ketik "lapak yok", "lapakyok", "lapak yuk", "lapak" (untuk melihat seberapa ramai unsur ini di kelas 43 dan 30), "yok", "yuk". Untuk cadangan: "yok leyeh", "leyeh", "leyeh leyeh". Simpan tangkapan layar bertanggal |
| 2. Amankan handle | Hari 1–2 | Buat @lapakyok di Instagram, TikTok, X, YouTube, boleh dikunci dulu. Varian kalau terpakai: @lapak.yok, @lapakyok.rwm, @lapakyok_rwm (X). Nama WhatsApp Business dan profil Google Bisnis: persis "Lapak Yok", tanpa tambahan kata kunci |
| 3. Konsultan KI | Minggu ini | Pilih yang terdaftar di DJKI. Tanyakan: (a) apakah "Lapak Yok" punya daya pembeda yang cukup di kelas 43; (b) **kata saja, kata + logo dalam satu permohonan, atau dua permohonan terpisah**; (c) kelas 30 perlu atau belum; (d) apakah tagline "Pulang kerja, yok nongkrong dulu." aman dipakai sebagai kalimat iklan; (e) risiko Yok Leyeh terhadap LL Coffee |
| 4. Logo final dan hak cipta | Paling lambat ±20 Nov | Permohonan kata + logo butuh logo final. Desainer **mengalihkan hak cipta logo secara tertulis** ke founder. Kalau logo belum siap, tanyakan konsultan apakah kata saja boleh diajukan dulu |
| 5. Ajukan | **Paling lambat Selasa 24 Nov 2026** | Online di [merek.dgip.go.id](https://merek.dgip.go.id). Sehari sebelum post publik pertama (H-14, Rabu 25 Nov) |

**Kelas yang dicek dan diajukan:**

| Kelas | Isi yang relevan | Kapan perlu |
|---|---|---|
| **43** | Jasa penyediaan makanan dan minuman, kedai kopi, warung, kafe. Ini mencakup kopi dan angkringan yang disajikan di lapak | **Wajib, ajukan pertama** |
| **30** | Kopi, biji kopi sangrai, kopi bubuk, minuman berbahan kopi sebagai **barang** | Jika nanti menjual biji kopi, cold brew botolan, atau kemasan ber-merek |

**Soal biaya:** `numbers-lapak.json` menganggarkan Rp2,8 juta untuk satu permohonan di satu kelas (tarif umum PP 30/2026 menurut ringkasan firma hukum di `brand-kafe.md` §4.1; tarif usaha mikro lebih rendah, cek di situs DJKI). Kalau konsultan menyarankan dua permohonan (kata dan logo terpisah) atau dua kelas, biayanya berlipat. Honor konsultan terpisah. Kabari CFO.

**Yang tidak melindungi nama:** NIB atau nama usaha di OSS, profil Google Maps, dan handle Instagram. **Jangan memakai simbol ® sebelum sertifikat terbit.**

---

### 2. Janji dan tiga tagline

#### Janji (yang bisa diandalkan tamu setiap kali datang)

> **Rabu sampai Sabtu malam, lampu Lapak Yok nyala sampai 24.00: kursi buat duduk lama, kopi yang diseduh di depanmu, dan nggak ada yang nyuruh buru-buru.**

Janji ini hanya boleh dipakai jika operasionalnya menepati (`/founder-ops`):
- semua kursi yang dihitung punya sandaran (bagian 4.6);
- tamu yang sudah duduk tidak disuruh pulang sebelum 24.00;
- kalau V60 akan lebih dari 10 menit, perkiraannya disampaikan **sebelum tamu bayar** (P018 berhenti datang di atas 10 menit, P001 di atas 15 menit);
- kalau penuh, bilang jujur dan tawarkan dikabari lewat WA;
- kalau tutup lebih awal karena hujan, umumkan di story IG secepatnya.

#### Tiga tagline, semua dari "yok"

| # | Tagline | Dipakai di mana | Catatan |
|---|---|---|---|
| 1 | **Pulang kerja, yok nongkrong dulu.** | **Utama**: di bawah logo, papan berdiri, bio IG, kartu | Kalimat founder sendiri (`idea.md`). Tetap kalimat iklan, bukan merek |
| 2 | **Lampu udah nyala. Yok.** | Story pembukaan setiap malam, papan berdiri, caption | Jujur secara harfiah: lampu nyala berarti lapak buka. Mengikat warna Lampu dan lampu baterai jadi ritual |
| 3 | **Bawa gengmu, yok. Kursinya kami siapin.** | Kartu reservasi rombongan, pesan WA | Menjawab "takut penuh" (P004, P007, P014). **Hanya dipakai kalau reservasi WA sudah berjalan** |

Hindari "yok ngopi" sebagai tagline utama. Frasa itu sudah menjadi nama beberapa merchant GoFood dan Grab (`research/nama-yok.md` §2a).

---

### 3. Suara: hangat, jujur, tenang

Tiga sifatnya sama dengan `brand-kafe.md` §5. Di lapak, ketiganya diuji di saat yang lebih sulit: kursi penuh, antrean seduh, dan hujan.

#### 3.1 Tiga contoh khusus lapak

| Sifat | Situasi | Lakukan | Jangan |
|---|---|---|---|
| **Hangat** | Rombongan berempat datang Jumat 20.00, semua kursi terisi | "Wah, lagi penuh, Kak, maaf ya. Tulis nama sama nomor WA di sini, nanti kami kabari begitu ada kursi. Sambil nunggu, tubruk atau es kopi susu bisa duluan." | "Penuh, Kak." lalu kembali menyeduh. Atau meminta tamu yang sudah duduk pindah supaya rombongan kebagian |
| **Jujur** | Empat V60 sudah antre, tamu baru memesan V60 | "V60 lagi antre empat gelas, kira-kira 15 menit. Es kopi susu lebih cepat. Mau yang mana?" Diucapkan **sebelum** tamu bayar | "Bentar ya, Kak." lalu 25 menit tanpa kabar. Atau menulis "selalu cepat" di story |
| **Tenang** | Hujan deras, lapak tutup lebih awal (story IG) | "Hujan deras di Rawamangun. Malam ini lampu kami matikan jam 21.00. Maaf buat yang sudah di jalan. [Hari berikutnya] kami buka lagi jam 19.00." | "TUTUP!!! HUJAN" dengan huruf kapital semua. Atau hitung mundur "tinggal 3 kursi lagi!!!" |

#### 3.2 Kata yang dipakai dan dihindari

- **Dipakai:** "lapak", "kursi", "seduh", "nongkrong", "lampu nyala", "geng", "tamu", "laptop istirahat dulu", "kami baru buka".
- **Dihindari:** "hidden gem", "viral", "aesthetic", "instagramable", "healing", "WFC", "termurah", "terbaik", "kopi penghilang stres", dan "lesehan" sebagai janji utama.

#### 3.3 Sebelum dan sesudah: kalimat pertama `pitch.md`

**Sebelum:**
> Lapak Yok, lapak kopi malam bergaya angkringan di teras ruko di Rawamangun, Jakarta Timur. Buka Rabu–Sabtu 19.00–24.00 (Jumat–Sabtu mulai 18.00).

**Sesudah:**
> Pulang kerja, yok nongkrong dulu di Lapak Yok: angkringan kopi malam di teras ruko Rawamangun. Lampunya nyala Rabu–Sabtu sampai 24.00 (Rabu–Kamis dari 19.00, Jumat–Sabtu dari 18.00).

**Kenapa lebih baik:**
- Dibuka dengan momen yang dikenali tamu dan ajakan "yok", bukan dengan kategori.
- "Lapak … lapak" yang berulang dibuang.
- "Lampunya nyala" adalah isyarat malam yang khas brand ini, dan memang benar terjadi.
- "Jakarta Timur" dibuang karena "Rawamangun" sudah cukup untuk orang lokal.
- Jam ditulis per kelompok hari, jadi tidak perlu tanda kurung "mulai 18.00" yang membingungkan.

**Bonus, baris tempat duduk** (setelah kursinya benar-benar dibeli):
- Sebelum: "Duduk di bangku dan tikar, sekitar 15 tempat duduk, …"
- Sesudah: "Sekitar 15 kursi bersandaran, bukan lesehan, jadi duduk 2–3 jam nggak pegal. Rombongan bisa pesan kursi lewat WA."

`pitch.md` tidak saya ubah. Jika founder setuju, pitch baru ini layak diuji ulang di panel, karena empat penolak menyebut tikar dan pegal.

---

### 4. Tampilan lapak malam tanpa listrik

**Rasa yang dituju:** dari seberang jalan, satu kotak krem yang menyala hangat di bawah atap gelap, dengan beberapa lampu kecil di meja dan uap kopi di bawah satu lampu. Seperti angkringan yang dirawat, **bukan** lapak berlampu neon putih, **bukan** kafe yang dipindah ke tenda.

#### 4.1 Warna di bawah lampu LED baterai

**Keputusan: palet `brand-kafe.md` tetap, porsinya diubah.** Di kafe, papan Biru Malam menyala dari dalam. Di lapak, satu-satunya cahaya adalah lampu baterai yang menyinari dari depan, jadi yang terlihat dari jalan adalah bidang yang paling banyak memantulkan cahaya.

| Nama | Hex | Tugas di lapak malam | Di bawah lampu hangat |
|---|---|---|---|
| **Kertas** | `#F7EFE1` | Bidang utama spanduk, papan menu, semua kartu, mug enamel | Warna paling terang. Luminans relatifnya 0,869, ±40× Biru Malam (0,022) [Pasti, hitungan]. Inilah yang terlihat dari jalan |
| **Biru Malam** | `#232647` | Semua teks di atas Kertas, atap tenda (warna stok terdekat: "biru dongker"), badan gerobak, pita bawah spanduk, panel latar sudut seduh, latar ikon | Tampak hampir hitam, kecokelatan di foto HP. Ia menyatu dengan malam, dan memang itu tugasnya. Jangan memaksa biru yang lebih terang |
| **Lampu** | `#F0A83C` | Gelembung "yok", teks di atas Biru Malam, dan warna cahaya itu sendiri | Makin oranye. Kontrasnya dengan Biru Malam naik |

**Cek kontras WCAG 2.x** (rumus luminans relatif WCAG, dihitung dengan skrip). AA teks normal ≥4,5:1, AA teks besar ≥3:1, AAA ≥7:1.

| Teks | Latar | Standar WCAG | ±3000K | ±2700K | AA normal | Keputusan |
|---|---|---:|---:|---:|:-:|---|
| Biru Malam `#232647` | Kertas `#F7EFE1` | **12,77:1** | 13,51:1 | 13,62:1 | lulus | **Teks utama:** nama di spanduk, menu, semua kartu |
| Kertas `#F7EFE1` | Biru Malam `#232647` | **12,77:1** | 13,51:1 | 13,62:1 | lulus | Teks di gerobak dan panel gelap |
| Lampu `#F0A83C` | Biru Malam `#232647` | **7,20:1** | 8,88:1 | 9,19:1 | lulus | Baris kedua spanduk, aksen di gerobak |
| Biru Malam `#232647` | Lampu `#F0A83C` | **7,20:1** | 8,88:1 | 9,19:1 | lulus | Huruf "yok" di dalam gelembung |
| Putih `#FFFFFF` | Biru Malam `#232647` | 14,59:1 | 15,16:1 | 15,23:1 | lulus | Boleh di layar (IG, WA) |
| Lampu `#F0A83C` | Kertas `#F7EFE1` | **1,77:1** | 1,52:1 | 1,48:1 | **gagal** | **Dilarang untuk teks.** Makin buruk di lampu hangat |
| Putih `#FFFFFF` | Lampu `#F0A83C` | **2,02:1** | 1,71:1 | 1,66:1 | **gagal** | **Dilarang** |

**Cara menghitung kolom ±3000K dan ±2700K** [perkiraan, bukan ukuran]: nilai RGB linear tiap warna dikalikan dengan warna cahaya *blackbody* 3000K dan 2700K (dinormalkan ke luminans 1), tanpa adaptasi warna mata. Ini kasus terburuk, mirip kamera HP dengan *white balance* siang. Mata manusia beradaptasi sebagian, jadi nilai sebenarnya ada di antara kolom standar dan kolom ini. **Kesimpulannya tetap:** pasangan yang dipakai makin kontras di lampu hangat, dan pasangan yang dilarang makin buruk.

**Aturan warna khusus malam:**
- **Teks papan dan menu minimal 7:1, bukan hanya 4,5:1.** Di cahaya redup, kepekaan mata terhadap kontras turun. Semua pasangan yang dipakai di atas sudah ≥7,20:1.
- **Lampu tidak pernah menjadi teks di atas Kertas**, dan putih tidak pernah di atas Lampu.
- **Bahan cetak doff (matte)**, bukan glossy. Bahan glossy memantulkan titik silau dari lampu LED di depannya.
- **Proof cetak dilihat malam hari di bawah lampu LED yang akan dipakai**, dari 10 m dan 20 m. Kuning-oranye di flexi murah bisa tercetak kecokelatan.
- **Warna kompetitor belum saya verifikasi.** Sebelum mencetak, bandingkan dengan akun IG Kopi Yor (Jl. Pemuda) dan YO'KOPI (@yo_kopi), supaya tidak mirip.

#### 4.2 Huruf (gratis, lisensi SIL Open Font License)

| Peran | Huruf | Dipakai di | Tautan |
|---|---|---|---|
| **Nama dan judul besar** | **Fraunces**, Black (900), sumbu SOFT 100, WONK 0 | "LAPAK YOK" di spanduk dan gerobak, huruf "yok" di logo, judul kartu | [fonts.google.com/specimen/Fraunces](https://fonts.google.com/specimen/Fraunces) |
| **Semua info** | **Plus Jakarta Sans**, 500/700/800 | Baris kedua spanduk (ExtraBold, kapital), jam, menu, harga, kartu, caption | [fonts.google.com/specimen/Plus+Jakarta+Sans](https://fonts.google.com/specimen/Plus+Jakarta+Sans) |
| Papan antrean dan "Malam ini" | **Tulisan tangan founder** dengan kapur atau spidol | Papan kecil di gerobak | Tidak butuh lisensi |

- **Kenapa Fraunces tetap:** di ketebalan Black dengan SOFT tinggi, ujung hurufnya membulat seperti huruf cat tangan di gerobak lama. Di ukuran besar (27 cm) tetap jelas.
- **Cadangan:** jika uji 20 m (bagian 1.4) menunjukkan Fraunces terbaca lebih lambat, ganti nama di spanduk ke **Plus Jakarta Sans ExtraBold**. Logo tetap memakai Fraunces.
- **Lisensi:** OFL ([openfontlicense.org](https://openfontlicense.org)) membolehkan pemakaian komersial: spanduk, cetak, logo, media sosial. Yang dilarang adalah menjual file hurufnya. **Jangan memakai huruf dari situs "download font gratis"** yang lisensinya tidak jelas.
- **Ukuran minimum, karena dibaca di bawah lampu redup:**
  - teks kartu ≥10 pt (naik dari 8–9 pt di `brand-kafe.md`), judul kartu ≥14 pt;
  - harga di papan menu tinggi huruf kapital ≥2,5 cm (dibaca dari ±3 m);
  - papan berdiri: judul ≥6 cm, info ≥4 cm (dibaca dari ±5–8 m).

#### 4.3 Spanduk dan papan

**Patokan ukuran huruf:** patokan umum industri papan adalah ±2,5 cm tinggi huruf untuk setiap ±3 m jarak baca dengan dampak terbaik (`brand-kafe.md` §7.1) [Kemungkinan Besar; bukan standar resmi tunggal]. Untuk malam dengan cahaya lemah saya tambah 50% [Menebak]:

| Jarak | Patokan siang | Malam (×1,5) |
|---|---:|---:|
| 5 m | 4,2 cm | 6,2 cm |
| 10 m | 8,3 cm | 12,5 cm |
| 20 m | 16,7 cm | **25,0 cm** |

**Spanduk utama (depan tenda):**

| Hal | Spesifikasi |
|---|---|
| Ukuran | **300 × 75 cm**, untuk tenda 3 × 3 m. Ukur lebar rangka tenda dulu |
| Bahan | Flexi/MMT **doff**, mata ayam tiap ±50 cm, diikat kencang ke rangka (angin) |
| Posisi | Tepi atas depan tenda. Tepi bawah ±1,9 m atau lebih dari lantai, supaya tidak menutupi bar dan kepala tamu. **Orang yang lewat harus tetap bisa melihat lampu dan orang di dalam** |
| Bidang atas (49 cm, Kertas) | Gelembung "yok" (tinggi ±38 cm) di kiri, lalu **"LAPAK YOK"** dalam Fraunces Black, Biru Malam, **tinggi huruf kapital 27 cm**. Lebar perkiraan ±250 cm termasuk gelembung [Menebak; desainer menyesuaikan] |
| Pita bawah (26 cm, Biru Malam) | **"KOPI SEDUH · ANGKRINGAN"** dalam Plus Jakarta Sans ExtraBold, warna Lampu, tinggi huruf kapital 12 cm |
| Jarak baca | Nama: ±20 m di malam hari. Baris kedua: ±10 m |
| Yang tidak ditulis | Harga, promo, nomor HP, "viral". Semua itu ada di papan berdiri dan kartu |
| Cahaya | Dua lampu batang LED USB hangat (2700–3000K), dijepit di rangka depan ±50 cm di depan spanduk, diarahkan supaya rata dari ujung ke ujung. Masing-masing dengan power bank 20.000 mAh (±74 Wh, ±63 Wh terpakai, kira-kira 12 jam pada 5 W [Menebak; uji di malam latihan]) |

**Papan berdiri (A-board) ±60 × 90 cm**, di tepi teras pribadi, **tidak di trotoar** (Perda DKI 8/2007, `lapak-malam.md`). Bidang Kertas, teks Biru Malam:

> **Lampu udah nyala. Yok.**
> Kopi seduh · angkringan
> Rabu–Kamis 19.00–24.00
> Jumat–Sabtu 18.00–24.00
> ±15 kursi bersandaran · rombongan pesan via WA [nomor]
> Parkir motor: [lokasi] →

Baris parkir **hanya ditulis setelah lokasi pasti** (P003, P004, P007, P010 menyebut parkir).

#### 4.4 Tenda, gerobak, dan muka bar

- **Tenda:** tenda lipat 3 × 3 m (`numbers-lapak.json`), atap warna stok "biru dongker" yang paling dekat dengan Biru Malam (tidak harus persis). Dinding samping digulung. Satu sisi yang menghadap angin atau hujan bisa diturunkan. Rumbai depan boleh polos.
- **Gerobak atau meja bar:** badan Biru Malam. **Bar menghadap tamu dan jalan, supaya seduhan V60 terlihat** (itu pertunjukannya). Di panel depannya, logo bertumpuk (gelembung di atas "LAPAK / YOK") dan satu baris dalam Kertas: **"Kopi diseduh di depan kamu."**
- **Papan menu** digantung di bar, bidang Kertas, teks Biru Malam, disinari lampu seduh:

> **V60 single origin** · Rp22.000 · dengan kartu beans
> **Es kopi susu** · Rp17.000
> **Kopi tubruk** · Rp8.000
> **Angkringan** · nasi kucing, sate, gorengan, roti bakar · Rp3.000–12.000
> Bingung pilih? **Cicip dulu, gratis.**
> Tegukan pertama nggak cocok? Bilang aja, kami seduh ulang.
> Bayar: tunai / QRIS

"Siap 3 menit" untuk es kopi susu **baru ditulis setelah lolos uji** di malam latihan (≥9 dari 10 gelas selesai ≤3 menit di jam sibuk, aturan `brand-kafe.md` §5).

- **Papan kecil "Malam ini"** (tulisan tangan, di samping bar):

> Malam ini: [nama beans], disangrai [tanggal]
> Diseduh oleh: [nama]
> Antrean V60: __ gelas · ±__ menit

Baris antrean diisi setiap ada pesanan V60. Papan ini menjawab "nunggu lama" sebelum tamu mengeluh (P001, P011, P015, P018, P020).

#### 4.5 Kursi: menjawab "pegal duduk di tikar"

**Yang dikatakan panel:**
- *"Duduk di tikar 2-3 jam juga pegal buat umur segini"* (P007).
- *"Duduk lesehan di tikar atau bangku 2–3 jam itu pegal di punggung"* (P008).
- *"Pegal duduk lesehan 2-3 jam, mending balik ke warkop langganan"* (P018).
- *"Duduk di tikar atau bangku setelah kerja belum tentu nyaman"* (P019).

**Keputusan brand:** janji "kursi buat duduk lama" tidak bisa ditepati dengan tikar dan bangku tanpa sandaran.

| Tempat | Jumlah | Jenis | Untuk siapa |
|---|---:|---|---|
| Kursi meja | 12 | **Kursi lipat bersandaran** (kayu lipat atau kursi camping kain bersandaran), 4 meja rendah × 3 kursi | Geng 2–6 orang yang duduk 2–3 jam |
| Kursi bar | 3 | Bangku tinggi di depan gerobak, sebaiknya dengan sandaran rendah | Tamu sendiri yang mau menonton seduhan dan ngobrol dengan barista |
| Tikar + bantal | Opsional | Hanya kalau ada rombongan yang minta | **Tidak dihitung dalam 15 kursi dan tidak dipromosikan** |

- **Syarat kursi:** sandaran sampai punggung tengah, bisa dilipat dan diangkut setiap malam, tahan lembap, warna kayu alami atau biru tua. Tinggi dudukan cocok dengan tinggi meja.
- **Uji di malam latihan (30 Nov–8 Des):** dua jenis kursi, teman duduk 2 jam di masing-masing, beri nilai "pegal" 1–5. Pilih yang lebih rendah nilainya.
- **Biaya:** `numbers-lapak.json` menganggarkan Rp2,3 juta untuk "bangku dan meja lipat ±15 kursi + tikar [estimasi]". Kursi bersandaran kemungkinan lebih mahal [Menebak]. Harga belum saya cek. `/founder-ops` mencari harga, CFO menghitung ulang.
- **Komunikasi:** tulis "kursi bersandaran" di WA dan IG **hanya setelah kursinya dibeli**.

#### 4.6 Lampu dan satu sudut foto yang jujur

**Yang dikatakan panel:** *"Nggak tahu apa yang bikin yang ini beda atau worth difoto"* (P005). *"Lebih pilih kafe yang lagi hits buat foto, bukan bangku dan tikar"* (P010). *"Nggak ada yang seru buat difoto"* (P011).

**Jawabannya bukan dinding neon atau properti palsu**, tapi menyinari hal yang memang istimewa di sini: kopi yang diseduh di depan tamu.

| Lampu | Jumlah | Spesifikasi | Tugas |
|---|---:|---|---|
| **Lampu seduh** | 1 | LED isi ulang yang bisa diarahkan, 2700–3000K, **CRI ≥90** jika ada (warna makanan dan wajah tetap wajar), digantung ±60–80 cm di atas titik seduh | Pertunjukan V60 dan sudut foto |
| **Lampu spanduk** | 2 | Lampu batang LED USB hangat (bagian 4.3) | Spanduk terbaca dari jalan |
| **Lampu meja** | 4–5 | Lentera LED isi ulang, cahaya hangat, bisa diredupkan. Mengingatkan pada lampu teplok angkringan **tanpa api** (sudah ada kompor gas di bawah tenda) | Wajah dan gelas kena cahaya, cahaya setinggi meja |
| Lampu untai | Opsional, 1 | Bohlam kecil hangat (2200–2700K), redup, di tepi depan tenda | Lapak terlihat menyala dari jauh |

**Dilarang:** lampu tabung putih dingin (6500K, membuat makanan abu-abu dan wajah pucat), lampu RGB berganti warna, lampu berkedip, dan neon berisi kutipan.

**Sudut foto: "Meja Seduh".**
- Panel Biru Malam (kain atau papan) di belakang titik seduh, dengan gelembung "yok" kecil warna Lampu. Hanya itu yang ber-merek di dalam bingkai.
- Lampu seduh menyinari dari samping atau sedikit dari belakang. **Uap terlihat paling jelas jika disinari dari samping atau belakang dengan latar gelap** [Kemungkinan Besar].
- Kartu beans berdiri di samping server kaca, ikut masuk bingkai.
- Kartu kecil di bar: *"Boleh foto seduhannya. Wajah orang lain, izin dulu ya."* (aturan privasi `marketing-kafe.md` §14).

**Yang tidak dilakukan:** menyewa orang supaya terlihat ramai, menulis "spot foto aesthetic", atau memasang properti yang tidak ada hubungannya dengan kopi.

**Daya:** semua lampu memakai baterai. Isi ulang di rumah siang hari, beri label pada setiap lampu dan power bank, dan bawa satu power bank cadangan. Anggaran `numbers-lapak.json` untuk lampu dan power bank adalah Rp600 ribu [estimasi]. Daftar di atas kemungkinan melebihinya [Menebak]. Kalau anggaran terbatas, urutan belinya: (1) lampu seduh, (2) lampu spanduk, (3) lampu meja.

#### 4.7 Gelas, cangkir, dan kartu beans

| Minuman | Wadah di tempat | Bawa pulang |
|---|---|---|
| V60 | Server kaca bening + **mug enamel krem atau putih dengan list biru tua** (barang stok, warna tidak harus persis). Enamel tahan banting dan terasa angkringan | Gelas kertas polos + stiker bulat 5 cm |
| Es kopi susu | Gelas kaca bening tinggi, tanpa cetakan | Gelas plastik bening + stiker bulat 5 cm |
| Kopi tubruk | Gelas belimbing dengan lepek | – |
| Makanan | Bungkus daun pisang atau kertas nasi. Tanpa styrofoam | – |

- **Stiker bawa pulang** (satu warna Biru Malam di atas kertas stiker krem): gelembung "yok", "Lapak Yok", "Pesan kursi: WA [nomor]". Stiker lebih murah daripada gelas bercetak untuk jumlah kecil [Kemungkinan Besar]. Tanpa promo.
- **Kartu beans** (syarat board C2): sama dengan `brand-kafe.md` §7.2, ukuran 9 × 5,5 cm, kertas tebal Kertas, teks Biru Malam **≥10 pt**.

> **Depan**
> **[Nama beans]**
> Asal: [desa/kebun], [daerah] · Proses: [natural/washed/honey]
> Roastery: [nama] · **Disangrai: [tanggal]**
> Rasa: [tiga kata, mis. jeruk, gula aren, cokelat]
>
> **Belakang**
> Diseduh di Lapak Yok oleh: __________, malam __________
> Mau seduh di rumah? Rasio kami: [1:16], [92]°C, ±[3] menit.
> Lapak Yok · Pulang kerja, yok nongkrong dulu. · WA [nomor]

#### 4.8 Kartu "HP boleh, laptop tidak"

Kartu tenda di setiap meja rendah, ±10 × 7 cm per sisi, Kertas dengan teks Biru Malam, **dilaminasi** (embun, tumpahan) dan diberi **dudukan berat** atau penjepit kayu supaya tidak terbang ditiup angin.

> **Sisi 1 (menghadap tamu)**
> **HP boleh. Laptop istirahat dulu.**
> Di sini memang nggak ada colokan: lapak ini buat ngobrol. Balas chat sebentar, silakan.
> Pesan kursi rombongan: WA [nomor]
>
> **Sisi 2 (dibalik menghadap bar jika mau)**
> **Cerita kopinya, dong.**
> Balik kartu ini ke arah bar, nanti barista mampir sebentar. Kalau tidak dibalik, kami nggak ganggu obrolan kalian.

**Kalau ada laptop terbuka** (naskah dari `brand-kafe.md`, disesuaikan; diucapkan pelan, sekali, langsung ke pemiliknya):

> "Kak, maaf ganggu sebentar. Di lapak ini laptopnya kami minta istirahat dulu ya, kursinya buat ngobrol. HP tetap boleh. Kalau malam ini memang harus kerja, kami ngerti banget. Minumannya bisa kami pindah ke gelas bawa pulang."

#### 4.9 Kartu reservasi WA untuk rombongan

Panel takut 15 kursi sudah penuh saat datang berempat (P004, P007, P008, P014, P020). Kartu ini dibagikan ke setiap tamu yang datang bersama teman. Ukurannya kartu nama, Kertas, teks Biru Malam, dengan gelembung Lampu.

> **Depan**
> **Bawa gengmu, yok. Kursinya kami siapin.**
> Rombongan 4–8 orang? Pesan kursi lewat WA: [nomor] [QR wa.me]
> Tulis: nama · jumlah orang · hari · jam datang
>
> **Belakang**
> Kursi kami tahan 15 menit dari jam yang kamu tulis. Telat atau batal? Balas WA aja, nggak apa-apa.
> Rabu–Kamis 19.00–24.00 · Jumat–Sabtu 18.00–24.00
> HP boleh, laptop istirahat dulu.
> Lapak Yok · [patokan alamat], Rawamangun

**Balasan konfirmasi WA** (dikirim founder atau helper):

> Halo [nama], kursinya sudah kami catat.
>
> [Hari], [tanggal] · jam [20.00] · [jumlah] orang
> Lapak Yok, [patokan alamat]
> Peta: [tautan Google Maps]
> Parkir motor: [info parkir]
>
> Kursinya kami tahan sampai jam [20.15]. Kalau telat atau batal, balas pesan ini saja.
> Info kecil: di sini HP boleh, laptop istirahat dulu.
>
> Sampai ketemu.
> [Nama], Lapak Yok

**Usulan untuk `/founder-ops`:** pada Jumat–Sabtu, kursi yang bisa dipesan paling banyak 8 dari 15, supaya tamu tanpa reservasi tetap kebagian. Lama kursi ditahan (15 menit) juga usulan. Pesan ini tanpa promo, dan tamu tidak dimasukkan ke daftar siaran tanpa izin (UU PDP, `marketing-kafe.md` §14).

---

### 5. Brief logo

**Yang harus dikatakan logo:** "ada yang ngajak, dan lampunya udah nyala."

- **Simbol:** gelembung chat berbentuk **persegi membulat** (bukan lingkaran), ekornya di kiri bawah. Warna Lampu. Di dalamnya **"yok"** huruf kecil, Fraunces Black SOFT, warna Biru Malam (7,20:1). Gelembung adalah ajakan teman lewat WA, dan warnanya adalah lampu di malam hari.
- **Wordmark:** **"LAPAK YOK"** dalam Fraunces Black SOFT, kapital, jarak antarhuruf sedikit longgar (+5%). Huruf kapital memberi tinggi huruf terbesar di spanduk. Huruf kecil "yok" di gelembung menjadi penyeimbang yang ramah.
- **Versi yang harus ada:**
  - horizontal (gelembung + LAPAK YOK) untuk spanduk;
  - bertumpuk (gelembung di atas LAPAK / YOK) untuk panel gerobak dan post IG persegi;
  - simbol saja untuk ikon, stiker gelas, dan cap kartu;
  - satu warna Biru Malam untuk cap karet dan stiker;
  - versi terbalik: Kertas di atas Biru Malam.
- **Harus bekerja di tiga tempat:**
  1. **Spanduk** 300 × 75 cm, terbaca dari 20 m di malam hari (bagian 4.3).
  2. **Gelas:** stiker bulat 5 cm atau cap karet ±3 cm, satu warna. Hanya simbol dan nama kecil.
  3. **Ikon 32 px** (avatar IG/TikTok/WA, favicon): gelembung Lampu di atas kotak Biru Malam. Gelembung ±24 × 18 px, "yok" setinggi x ±8 px. Simpan di tengah 80% kanvas supaya tidak terpotong lingkaran avatar IG. **Di 16 px**, pakai gelembung tanpa huruf atau hanya "y". Uji di daftar chat WA.
- **Hindari:**
  - warna hijau, gagang telepon, atau gelembung bulat yang bisa disangka logo WhatsApp;
  - tanda petik seperti "YO'" (gaya YO'KOPI) dan kata "KOPI" di logo (menjauh dari YO'KOPI dan Kopi Yor);
  - biji kopi, uap meliuk, cangkir berhati;
  - motif blirik enamel sebagai logo (terlalu umum);
  - gambar gerobak *clipart*, neon, laptop dicoret;
  - warna dan bentuk logo kompetitor mana pun.
- **Konsep dengan alat gambar:** sesi ini tersambung ke alat gambar (Canva, Figma, Higgsfield). Jika founder mau, saya bisa membuat 3–4 **konsep** gelembung "yok" dan spanduk. Setiap gambar akan diberi label **"KONSEP, bukan logo final"**. Konsep perlu digambar ulang oleh desainer, dicek kemiripannya dengan logo lain, dan hak ciptanya dialihkan tertulis sebelum didaftarkan ke DJKI.

---

### 6. Lima touchpoint pertama

#### 6.1 Spanduk

**Bidang atas (Kertas):** [gelembung "yok"] **LAPAK YOK**
**Pita bawah (Biru Malam):** **KOPI SEDUH · ANGKRINGAN**

Spesifikasi lengkap di bagian 4.3. Hanya dua baris, tanpa harga, promo, atau nomor HP. Jam, kursi, dan parkir ada di papan berdiri.

#### 6.2 Post Instagram pertama (H-14, Rabu 25 November 2026)

**Syarat:** merek kelas 43 sudah diajukan (24 Nov), dan tempat sudah pasti. Tanggal buka 9 Desember **hanya ditulis jika tempat dan status halal sudah jelas** (`lapak-malam.md` §7). Kalau belum, ganti dengan "Tanggal bukanya kami kabari di sini."

- **Format:** video vertikal 9:16, ±25 detik, direkam malam hari di lokasi sebenarnya. Tanpa musik keras.
- **Isi:** teras gelap → founder menyalakan lampu satu per satu (spanduk, lampu seduh, lentera meja) → close-up V60 dituang di bawah lampu seduh, uapnya terlihat → kursi bersandaran yang masih kosong → spanduk menyala.

**Naskah suara:**
> "Lampu ini nanti nyala tiap Rabu sampai Sabtu malam. Kopinya diseduh di depan kamu, kursinya ada sandarannya, dan nggak ada yang nyuruh buru-buru sampai jam dua belas. Di sini nggak ada colokan, jadi laptop istirahat dulu. Namanya Lapak Yok."

Opsi kalimat pembuka, **hanya jika founder nyaman dan kontrak kerjanya membolehkan usaha sampingan** (`lapak-malam.md`): "Saya juga pulang kantor jam setengah enam, dan saya tahu rasanya pengin duduk dulu sebelum pulang."

**Caption:**
> Lampunya mulai nyala Rabu, 9 Desember.
>
> Lapak Yok: angkringan kopi malam di teras [patokan], Rawamangun.
> Rabu–Kamis 19.00–24.00 · Jumat–Sabtu 18.00–24.00
>
> Kopi diseduh di depan kamu. V60 Rp22.000, es kopi susu Rp17.000, tubruk Rp8.000. Ada nasi kucing, sate, gorengan.
> Sekitar 15 kursi bersandaran. Rombongan bisa pesan lewat WA.
> HP boleh, laptop istirahat dulu. Memang nggak ada colokan.
>
> Kami belum buka, jadi belum ada review. Mau dikabari? Balas "yok" di DM.
>
> #Rawamangun #angkringan #kopimalam

**Bio IG** (≤150 karakter):
> Angkringan kopi malam di Rawamangun. Rabu–Sabtu sampai 24.00. Kopi diseduh di depanmu. HP boleh, laptop istirahat. Pesan kursi rombongan ↓

**Aturan:** tanpa angka follower, tanpa "viral", tanpa testimoni. Wajah orang lain hanya dengan izin.

#### 6.3 Pesan WA yang diteruskan pelanggan ke temannya

Lapak Yok menyediakan pesan ini (dikirim ke tamu yang setuju masuk daftar WA). **Tamu yang memutuskan mau meneruskan atau tidak.** Isinya hanya fakta. Jangan menaruh pujian seperti "enak banget" di mulut tamu (`marketing-kafe.md` §10 B).

> Yok, ke Lapak Yok [hari] jam [20.00]?
> Angkringan kopi malam di teras [patokan], Rawamangun: [tautan Google Maps]
> Kopinya diseduh di depan kita: V60 22 rb, es kopi susu 17 rb, tubruk 8 rb. Ada nasi kucing sama sate.
> Kursinya bersandaran, sekitar 15. Rombongan bisa pesan dulu: wa.me/62[nomor]
> Parkir motor: [lokasi]
> Sampai Sabtu 19 Des, minuman kedua buat teman yang diajak setengah harga.
> Siapa ikut?

**Catatan:**
- Baris parkir hanya setelah lokasi pasti.
- Baris promo dihapus setelah promo berakhir. **Sabtu 19 Desember 2026 pukul 24.00** adalah malam buka terakhir dalam 14 hari jika lapak buka Rabu 9 Desember [hitungan kalender]. Tanggal ini ditulis sejak hari pertama dan tidak diperpanjang.
- "Kursinya bersandaran" hanya setelah kursinya dibeli.

#### 6.4 Kartu cap

Kartu nama 9 × 5,5 cm, Kertas, teks Biru Malam. Capnya cap karet simbol gelembung "yok" (tinta biru), ditambah paraf barista dengan pulpen.

> **Depan**
> **Kartu Yok**
> Nongkrong 6 malam, V60 berikutnya dari kami.
> ( ) ( ) ( ) ( ) ( ) ( )
> 1 cap per malam per orang, dengan minimal satu minuman.
>
> **Belakang**
> Nama: __________
> Cap ke-6 bisa ditukar satu V60 atau es kopi susu di kunjungan berikutnya. Bilang di awal, sebelum bayar.
> Rabu–Kamis biasanya lebih lega buat seduhan V60.
> Kartu hilang? Maaf, mulai dari awal lagi ya.
> Berlaku selama Lapak Yok buka, termasuk kalau nanti pindah ke kios di Rawamangun.
> Lapak Yok · Pulang kerja, yok nongkrong dulu. · WA [nomor]

- **Kenapa 6 malam:** tamu mingguan menyelesaikan kartu dalam ±6 minggu, sebelum review 8 minggu (Selasa 2 Feb 2027). Jumlah cap per kartu bisa dipakai untuk mengukur target "≥25% tamu kembali dalam 14 hari" (`lapak-malam.md` §7).
- **Kenapa hadiahnya V60:** harga jualnya paling tinggi dibanding biaya bahannya. V60 Rp22.000 dengan bahan Rp7.050 (`numbers-lapak.json`).
- **Biaya:** satu kartu penuh ±Rp7.050–7.900, atau ±Rp1.200–1.300 per kunjungan selama 6 kunjungan. Itu ±8–9% dari kontribusi per tamu (Rp14.105) [Pasti, hitungan], dan hanya untuk tamu yang menyelesaikan kartu. **Belum ada di model CFO**, jadi tambahkan sebagai satu baris.

#### 6.5 Balasan untuk keluhan pertama: "nunggu V60 lama"

**Skenario paling mungkin:** Jumat malam, helper baru belajar, enam V60 antre. Ulasan Google Maps bintang 2: *"Tempatnya enak, tapi V60 saya baru datang 25 menit. Nggak ada yang ngabarin."*

**Saat itu juga, di lapak** (kalau tamu mengeluh langsung):
> "Maaf banget, Kak, nunggunya kelamaan. Masih ada dua gelas di depan, kira-kira 8 menit lagi. Sambil nunggu, tubruknya dari kami ya."

Memberi tubruk gratis (bahan ±Rp3.400) saat waktu tunggu melewati perkiraan yang disebut adalah **usulan**. `/founder-ops` yang memutuskan aturannya.

**Balasan di Google Maps** (paling lambat 24 jam):
> Halo [nama], terima kasih sudah menulis ini, dan maaf. 25 menit untuk satu V60 itu terlalu lama, apalagi tanpa kabar dari kami. Malam itu sekitar jam [20.00] ada [enam] seduhan manual antre dan kami seduh satu per satu. Itu masalah kami, bukan alasan.
>
> Yang kami ubah mulai [tanggal]: di gerobak sekarang ada papan "Antrean V60: __ gelas, ±__ menit" yang kami isi setiap ada pesanan, dan perkiraannya kami sebut sebelum kamu bayar. Jadi kamu bisa pilih menunggu, atau ambil es kopi susu atau tubruk dulu. [Tulis hanya perubahan yang benar-benar sudah dijalankan.]
>
> Kalau suatu malam mampir lagi, sebut nama kamu ke kami. Seduhan V60 berikutnya dari kami. Tawaran ini tidak bergantung pada ulasanmu, jadi biarkan ulasannya apa adanya.
>
> [Nama founder], Lapak Yok

**Aturan membalas:**
- Balas semua ulasan dalam 24 jam, yang baik maupun yang buruk.
- Jangan pernah menawarkan imbalan supaya ulasan diubah atau dihapus.
- Jangan menyebut atau menyindir lapak atau kafe lain.

---

### 7. Aturan brand lapak

- **Tidak meniru nama, logo, warna, atau tagline kompetitor.** Menjauh dari pola "yo/yok + kopi" (YO'KOPI), bunyi "kopi yor", unsur "ngaso" (Ngaso Dulu Ah), dan "Yok Ngopi" (merchant GoFood/Grab).
- **Huruf, gambar, dan ikon hanya yang boleh dipakai:** Fraunces dan Plus Jakarta Sans (OFL), foto milik sendiri, ikon gambar sendiri.
- **Klaim hanya yang terbukti:**
  - "3 menit" hanya setelah uji di malam latihan lolos;
  - "kursi bersandaran" hanya setelah kursinya dibeli;
  - info parkir hanya setelah lokasi pasti;
  - tanggal buka hanya setelah tempat dan status halal jelas.
- **Tanpa review palsu, angka follower, "viral", superlatif, klaim kesehatan, atau keramaian yang dipentaskan.**
- **Harga ditulis final.** PBJT belum berlaku di omzet lapak; tulis ulang semua materi jika status ini berubah.
- **Status merek:** sampai DJKI mengeluarkan sertifikat, "Lapak Yok" hanya nama yang dipakai. Jangan menulis ®.
- **Bukan nasihat hukum.**

**Syarat board yang tersentuh:**
- **C2** (Coffee Story tanpa AI): kartu beans dan papan "Malam ini".
- **C9** (cara menolak laptop dengan sopan, cahaya, suasana): kartu meja, naskah barista, dan rencana lampu.

---

### 8. Dampak ke dokumen lain dan langkah berikutnya

Saya hanya menulis file ini. Yang perlu diperbarui oleh pemiliknya:

| Dokumen | Yang perlu diubah |
|---|---|
| `pitch.md` | Kalimat pertama dan baris tempat duduk (bagian 3.3), lalu uji ulang di panel |
| `numbers-lapak.json` (CFO) | Kursi bersandaran (baris Rp2,3 jt), lampu (baris Rp600 rb), biaya kartu cap, dan biaya merek jika lebih dari satu permohonan atau kelas |
| `/founder-ops` | Aturan "V60 >10 menit disampaikan sebelum bayar", papan antrean, batas kursi yang bisa dipesan, lama kursi ditahan, tubruk gratis saat telat, SOP lampu dan isi ulang baterai, kursi dan kartu yang dilaminasi |
| `/founder-launch` | Merek kelas 43 diajukan paling lambat Selasa 24 Nov; logo final ±20 Nov; uji 20 m dan uji 10 orang minggu ini; post H-14 Rabu 25 Nov; cetak setelah nama final |
| `competitors.md` | Tambahkan YO'KOPI (Rawamangun dan Jogja) dan Kopi Yor (Jl. Pemuda) |

**Urutan kerja founder minggu ini (9–15 Nov 2026):**
1. PDKI dan amankan handle @lapakyok (hari 1–2).
2. Uji 20 m dan uji 10 orang (bagian 1.4).
3. Temui Konsultan KI dengan hasilnya (bagian 1.6).
4. Putuskan nama. Jika setuju, saya bisa membuat konsep logo dengan alat gambar yang tersambung.

---

### Sumber

- Dokumen internal: `brand-kafe.md` §3–§7, `research/nama-yok.md` §1–§4, `lapak-malam.md` §1–§7, `pitch.md`, `panel/results.md`, `panel/answers/P001–P020.json`, `numbers-lapak.json`, `marketing-kafe.md` §4, §10, §14, `idea.md`.
- Pencarian 8 Nov 2026 (bagian 1.5): empat pencarian tanpa hasil yang relevan untuk "Lapak Yok", "lapakyok", "Yok Leyeh", dan "yokleyeh". Satu hasil terkait: [video Facebook "Lapak Awak Cafe"](https://www.facebook.com/sepdumclub/videos/wakjesss-ikut-kami-ke-lapak-awak-cafe-yok-lokasinya-di-jl-sultan-hasanuddin-jl-o/849406959569604/) (dari cuplikan, halaman tidak dibuka).
- Akun yang disebut dari riset sebelumnya: [@leyehleyehcoffee](https://www.instagram.com/leyehleyehcoffee/) · [@yo_kopi](https://www.instagram.com/yo_kopi/) · [@ngasoduluah](https://www.instagram.com/ngasoduluah/).
- Merek: [PDKI](https://pdki-indonesia.dgip.go.id) · [Permohonan merek online](https://merek.dgip.go.id) · tarif PP 30/2026: lihat `brand-kafe.md` §4.1.
- Huruf: [Fraunces](https://fonts.google.com/specimen/Fraunces) · [Plus Jakarta Sans](https://fonts.google.com/specimen/Plus+Jakarta+Sans) · [SIL Open Font License](https://openfontlicense.org).
- Kontras: rumus luminans relatif dan rasio kontras WCAG 2.x, dihitung dengan skrip. Kolom 3000K/2700K memakai aproksimasi kromatisitas *blackbody* (Kim dkk.) ke sRGB linear, tanpa adaptasi warna.

**Berikutnya:** `/founder-ops` (kursi, lampu, antrean, reservasi), lalu `/founder-launch` (tanggal merek dan post H-14).

## Operations

> **Cara membaca dokumen ini**
> - Disusun 8 Nov 2026 untuk founder, CFO, dan `/founder-launch`. Format: **lapak malam** di teras ruko/rumah yang tutup sore (`lapak-malam.md`). Dokumen ini **menggantikan `ops-kafe.md` untuk format lapak**. `ops-kafe.md` tetap berlaku untuk rencana kafe/ruko.
> - Dipakai: `numbers.json` versi **offer v3** (diperbarui 06.12: belanja Rp29.000/tamu, gelas kedua Rp12.000, kartu cap), `offer.md` v3, `pricing.md` v3, syarat board rapat kedua di `board.md`. Syarat **D2, D3, dan D4** ditujukan ke dokumen ini dan dijawab di bagian 2, 7, dan 9.
> - Fakta baru berasal dari **cuplikan hasil pencarian (WebSearch) 8 Nov 2026**. Halaman sumbernya **tidak dibuka**: sesi riset sebelumnya mencatat WebFetch diblokir, jadi saya tidak mencobanya lagi. Harga marketplace adalah harga tayang yang bisa sudah berubah, dan beberapa cuplikan tidak menunjukkan halaman persisnya (ditandai "cuplikan"). **Cek ulang tautan sebelum membeli.**
> - **[estimasi]** = perkiraan saya, bukan fakta. *(hitungan)* = hitungan saya dari angka bersumber. **[aturan internal]** = aturan yang saya usulkan, bukan regulasi.
> - **Bukan nasihat hukum, pajak, atau ketenagakerjaan.** Aturan berbeda per tempat dan bisa berubah. Konfirmasi ke instansinya (OSS/PTSP Kec. Pulo Gadung, kelurahan Rawamangun, BPJPH, Bapenda DKI, BPJS) atau ke profesional.
> - Saya **tidak mengubah** `numbers.json`. Semua angka yang perlu diubah ada di bagian terakhir.

---

### 1. Ringkasan

1. **Bisa dijalankan, tetapi break-even naik.** Kalau biaya nyata malam lapak dimasukkan (jam helper yang benar, es untuk cooler, air galon, gas dua kompor), biaya tetap naik dari Rp4,83 juta ke **±Rp5,98 juta/bulan**. Menurut alat CFO (dijalankan pada salinan, bukan file asli), **break-even naik dari 21 ke ±26 tamu/malam** dan tahun 1 menjadi **−Rp11,6 juta**. Ada jalan kembali ke ±21: helper 18.00–23.30, air cuci dari keran tuan rumah, dan es dibeli sendiri di jalan (bagian 11).
2. **Kapasitas 37 tamu/malam terlalu optimistis.** Angka itu hanya tercapai kalau ada ≥16 kursi, tamu duduk ≤2,5 jam, dan 20% pesanan dibawa pulang. Kalau tamu duduk 3 jam, kapasitas rata-rata turun ke ±29. **Saya sarankan CFO memakai 30** [estimasi]. Rencana 28 tamu/malam masih muat, tetapi hampir tanpa ruang cadangan.
3. **Throughput tanpa listrik** (giling tangan, kompor gas) [estimasi, ukur di malam latihan]:
   - **V60:** 5–7 gelas/jam kalau founder sendirian dan juga mengurus kasir, makanan, dan sapa. 10–12 gelas/jam kalau helper memegang semua tugas lain.
   - **Es kopi susu:** 20–30 detik per gelas dari *base* yang sudah dicampur. Realistisnya 15–25 gelas/jam sendirian dan 30–40 gelas/jam dengan helper.
   - **Janji "es kopi susu ≤3 menit" bisa dipegang**, asal *base* dicampur sebelum buka dan es kopi susu selalu menyalip antrean V60. **V60 tidak masuk janji 3 menit.** Waktu tunggunya disebut sebelum bayar (syarat D3): sekitar 5 menit, ditambah ±3 menit untuk setiap V60 yang sudah antre.
4. **Alat yang dibeli:**
   - **±Rp12,6 juta** untuk teras beratap dengan gerobak. Rentangnya Rp8,8–13,3 juta tergantung listing.
   - `numbers.json` mencatat Rp11,75 juta, jadi selisihnya +Rp0,86 juta.
   - Tenda Rp2,25 juta bisa dihapus kalau terasnya beratap, sesuai syarat board "satu titik beratap". Tikar diganti kursi bersandaran (offer v3).
   - Tanpa gerobak (pakai meja koper): ±Rp10,3 juta.
5. **Cold brew tanpa listrik:** rendam **di kulkas rumah** 13–24 jam dua kali seminggu (Selasa dan Kamis), lalu bawa ke lapak dalam cooler bag dengan es gel. Di lapak, semua yang dingin disimpan di cooler dengan es. *Base* yang berisi susu dan susu yang sudah dibuka **dibuang saat tutup**.
6. **Jumat 18.00 adalah titik lemah.** Helper membuka lapak sebelum founder tiba, padahal konsentrat masih di tas founder. Ada tiga solusi di bagian 2d. Yang terbaik: titip konsentrat di kulkas toko tuan rumah pada pagi hari.
7. **Jam kerja founder sekitar 85–90 jam/minggu** [estimasi], lebih tinggi dari "±75 jam" di `lapak-malam.md`, karena perjalanan, bongkar-pasang, belanja, dan konsentrat ikut dihitung. Studi WHO/ILO mengaitkan kerja ≥55 jam/minggu dengan risiko stroke 35% lebih tinggi. Aturan pengaman ada di bagian 6.
8. **Tiga risiko teratas:**
   1. hujan dan tempat ditarik tuan rumah;
   2. founder sakit atau lembur di kantor (tidak ada pengganti);
   3. bulan pertama sepi di musim hujan.

**Apa yang berubah dibanding `ops-kafe.md` (kafe):**

| Topik | `ops-kafe.md` (kafe) | `ops.md` (lapak) |
|---|---|---|
| Listrik | Kettle listrik, chiller, RO, grinder Latina | **Tidak ada.** Giling tangan, kompor LPG + kompor gas kaleng, cooler + es, lampu baterai |
| Konsentrat | Direndam di chiller kafe setiap malam | Direndam di kulkas rumah 2×/minggu dan dibawa ke lapak |
| Orang | 3 staf penuh waktu (UMP + BPJS) | Founder sendiri Rabu–Kamis; helper per jam Jumat–Sabtu (UMP ÷ 126) |
| Jam | Setiap hari 16.00–24.00 | Rabu–Kamis 19.00 (atau 19.30), Jumat–Sabtu 18.00, tutup 24.00 |
| Makanan | Dapur sendiri (roti bakar, pisang, mie), rice bowl titip | Rabu–Kamis **hanya siap saji** (titip/beli putus). Jumat–Sabtu ditambah roti bakar dan sate di kompor kedua |
| Izin utama | NIB, SLHS, halal reguler, PBJT, LMKN | NIB (KBLI 56304/56306), **halal SEHATI**, SKU RT/RW, **perjanjian tertulis tuan rumah**, larangan trotoar (Perda 8/2007) |
| Air | PAM + RO | Galon untuk seduh, keran tuan rumah atau jerigen untuk cuci, sistem 3 baskom |
| Musik | Royalti LMKN | **Tanpa musik dari speaker**: tidak ada royalti, dan keluhan bising lebih kecil |

**Yang tetap dipakai dari `ops-kafe.md`:**
- resep V60 (SOP-04);
- rasio konsentrat dan resep es kopi susu (SOP-03);
- garansi seduh ulang (SOP-05);
- kalimat menolak laptop (SOP-06);
- cara menangani keluhan (SOP-07);
- pemasok beans, susu, filter, dan cup (bagian 2a–2c);
- template Google Sheets HPP/stok (bagian 5).

---

### 2. Siklus harian

#### 2a. Di mana alat disimpan

**Prinsip:** barang besar menginap di tempat tuan rumah, di dalam gerobak yang dikunci atau di dalam toko sesuai perjanjian tertulis (syarat D4). Barang mahal dan yang mudah basi dibawa founder.

| Menginap di tempat tuan rumah (gerobak terkunci / dalam toko) | Dibawa founder setiap malam |
|---|---|
| Gerobak (bar), 16 kursi bertumpuk, 4 meja plastik | Grinder tangan, timbangan, 2 dripper V60, server, kettle leher angsa (kalau tidak mau ditinggal) |
| Kompor LPG 1 tungku + regulator, tabung Bright Gas 5,5 kg (**hanya jika tuan rumah setuju tertulis**), kompor gas kaleng | Toples dosis beans (15 g per toples, ditimbang di rumah), kartu beans |
| 2 cooler box (kosong dan kering), ceret 3 L, termos 2 L, wajan roti bakar | Konsentrat cold brew dalam cooler bag + es gel |
| 24 cangkir blirik, 24 gelas kaca, 3 baskom cuci, 2 jerigen, jerigen keran cuci tangan | Uang kas awal dan HP (Qasir) + powerbank |
| APAR (selalu bersama kompor), X-banner, kartu meja, standee QRIS | 2 lampu dan powerbank untuk diisi ulang di rumah atau kantor (2 lampu cadangan tetap di gerobak) [estimasi durasi baterai; cek spesifikasi] |
| Stok kering: susu UHT karton (tahan suhu ruang sebelum dibuka), gula aren tertutup, filter, cup take-away, kantong sampah | – |

Kalau tuan rumah **tidak** mengizinkan barang menginap, biaya angkut di `numbers.json` (Rp400 rb/bulan) tetap diperlukan, dan pemasangan hampir pasti lewat 30 menit. **Jadikan ini syarat tempat, bukan nego belakangan.**

#### 2b. Rutinitas mingguan di rumah (konsentrat dan dosis)

| Kapan | Apa | Waktu |
|---|---|---|
| **Selasa 06.00** (sebelum kantor) | Rendam konsentrat batch 1 di kulkas rumah (resep di 2e) | 10 menit |
| **Selasa 19.00–20.00** (malam libur) | Saring batch 1 (±13–14 jam), botolkan 1 L, beri label tanggal dan jam. Timbang **dosis V60 15 g** ke toples kecil untuk Rabu–Kamis (±20 toples). Isi kartu beans | 60 menit |
| **Kamis 06.00** | Rendam batch 2 | 10 menit |
| **Jumat 01.00–06.00** | Saring batch 2 (19–24 jam), botolkan. Timbang dosis untuk Jumat–Sabtu | 30–45 menit |
| **Rabu, Kamis, Jumat 06.00** | Pindahkan botol malam itu ke cooler bag dengan es gel beku. Bawa ke kantor dan simpan di kulkas kantor kalau ada (pertanyaan terbuka) | 5 menit |
| **Sabtu siang** | Belanja roti dan bahan sate untuk Jumat–Sabtu berikutnya; cek stok | 1–2 jam |

#### 2c. Rabu–Kamis menit per menit (founder sendiri)

Asumsi perjalanan kantor → lapak **45 menit** [estimasi; founder isi angka nyata]. Kolom **Tamu lihat?** menandai langkah yang dilihat tamu atau tetangga.

| Jam | Langkah | Tamu lihat? |
|---|---|:-:|
| 17.30 | Keluar kantor. Ambil cooler bag konsentrat dari kulkas kantor | – |
| 17.30–18.15 | Perjalanan. Di jalan: pesan **es kristal 10 kg** lewat kurir instan, tiba 18.30 (bagian 2f). WhatsApp pemasok makanan titip: antar 18.30. Posting story IG/WA: "Buka 19.00 di [titik]" | – |
| 18.15 | Tiba. Sapa tuan rumah atau tetangga, cek lantai (genangan, hujan), cuci tangan | ✓ (tetangga) |
| 18.15–18.20 | Buka kunci gerobak dan dorong ke tanda lakban di lantai, **di dalam batas persil, tidak menyentuh trotoar** ([Perda DKI 8/2007 Pasal 25(2)](https://www.hukumonline.com/klinik/a/sanksi-berjualan-di-fasilitas-umum-perumahan-lt51c11b74eca70/)). Taruh APAR di sebelah titik kompor | ✓ |
| 18.20–18.25 | Pasang regulator, **tes bocor dengan air sabun**, nyalakan kompor LPG, ceret 3 L di atas api | – |
| 18.25–18.32 | Turunkan 16 kursi dan 4 meja (4 kursi per meja), nyalakan 4 lampu | ✓ |
| 18.30 | Es datang. Cooler besar: **es minum dalam kantong bersih tersendiri** + es pendingin + botol susu/konsentrat. Cooler kecil: *base* dan susu terbuka | – |
| 18.32–18.37 | Stasiun cuci (3 baskom), jerigen keran + sabun untuk cuci tangan, 2 ember sampah. Makanan titip datang: hitung, **cek label halal dan jam produksi di nota**, tanda tangan. Tata di bawah tudung saji dengan kartu harga | ✓ |
| 18.37–18.43 | Bar: grinder, timbangan, 2 dripper + filter, toples dosis, 2 kartu beans, 2 toples cium bubuk. Air mendidih masuk termos dan kettle leher angsa; cek suhu dengan termometer | ✓ |
| 18.43–18.47 | X-banner, kartu meja "HP boleh, laptop tidak", standee QRIS, papan menu dengan baris "**V60 ±5 menit per gelas**". Buka shift di Qasir dan hitung kas awal | ✓ |
| 18.47–18.52 | Campur **base kopi susu 1 L** (SOP-L4), cicip konsentrat. Makan malam singkat (nasi kucing) dan minum air | – |
| 18.52–19.00 | Cadangan waktu. **Syarat D2: jangan menerima tamu sebelum lampu, kursi, dan air panas siap.** | – |
| **19.00** | **Buka** (atau **19.30** sesuai aturan D2 di bawah) | **✓** |
| 19.00–23.30 | Layanan. Jam ramai biasanya 19.30–21.30 [estimasi]. Prioritas: (1) sapa ≤10 detik, (2) es kopi susu ≤3 menit, (3) V60, (4) makanan, (5) cuci gelas saat sepi | ✓ |
| 21.00 | Cek jam produksi makanan (aturan 4 jam, bagian 5c), isi ulang termos, cuci satu gelombang gelas | ✓ |
| 23.30 | **Last order**, disampaikan pelan ke setiap meja | ✓ |
| 23.45 | Mulai beres-beres yang tidak mengganggu tamu (stasiun makanan, kursi kosong) | ✓ |
| **24.00** | **Tutup.** Tamu dipersilakan menghabiskan minuman | ✓ |
| 24.00–00.35 | Bongkar (SOP-L9) | ✓ (tetangga) |
| 00.35–00.45 | Hitung kas, tutup shift Qasir, foto laporan ke Sheets | – |
| 00.45–01.05 | Pulang (ojek online lebih aman dari motor sendiri saat lelah [aturan internal]) | – |
| 01.05–01.30 | Botol konsentrat sisa masuk kulkas (kalau masih memenuhi aturan 2e), isi daya lampu dan powerbank, tidur | – |

**Aturan D2 untuk jam buka:** ukur waktu pemasangan di 4 malam latihan (30 Nov–8 Des). **Kalau satu saja lewat 19.00, jam resmi Rabu–Kamis menjadi 19.30** dan jam itu yang ditulis di Google Maps, IG, dan papan. Lebih baik buka tepat 19.30 daripada "19.00" yang sering telat.

#### 2d. Jumat–Sabtu (dengan helper)

| Jam | Helper | Founder | Tamu lihat? |
|---|---|---|:-:|
| 17.30 | Datang, buka gerobak (kunci atau akses dari tuan rumah, tertulis di perjanjian). Jalankan SOP-L1 | Jumat: masih di jalan. Sabtu: datang 17.00 membawa roti dan bahan sate | ✓ |
| 17.45 | Terima es (**15 kg**) dan makanan titip | Jumat: pesan es dari jalan | – |
| **18.00** | **Buka.** Menu sementara: tubruk, makanan siap saji, air putih | – | ✓ |
| ±18.15–18.30 | – | Jumat: tiba dengan konsentrat. Mulai V60 dan es kopi susu | ✓ |
| 18.30–23.30 | Kasir/host, es kopi susu, tubruk, makanan, roti bakar dan sate di kompor kedua, cuci | Bar V60, Sesi Bareng, cicip, cerita beans, reservasi grup | ✓ |
| ±21.00 | Istirahat 30 menit (setelah 4 jam kerja terus-menerus, lihat `ops-kafe.md` §3c) | Pegang semua | – |
| 23.30 | Last order | | ✓ |
| 24.00–00.15 | Cuci, susun kursi, sampah | Kas, gas, gerobak | ✓ |
| **00.15** | **Pulang** (6,75 jam: di bawah batas 7 jam/hari untuk upah per jam). Kalau helper perempuan: antar-jemput disediakan (bagian 6) | Selesai ±00.40 | – |

**Masalah Jumat 18.00: konsentrat masih di tas founder.** Pilihan, urut dari yang terbaik:

1. **Titip di kulkas toko tuan rumah pada pagi hari.** Toko tuan rumah buka di siang hari. Founder mampir pagi sebelum kantor, kalau rutenya masuk akal. Tulis di perjanjian (bagian 9).
2. **Rendam batch Jumat di cooler lapak.** Kamis 24.00, konsentrat tertutup masuk cooler dengan es baru 10 kg dan termometer. Jumat 17.30, helper cek suhunya. Pakai hanya kalau **≤5°C** [aturan internal]; kalau lebih, buang. **Uji dulu 2 kali di malam latihan** sebelum dipakai.
3. **Jumat 18.00–18.30 menu tanpa es kopi susu dan V60.** Tulis di papan: "Es kopi susu & V60 mulai 18.30". Paling jujur, tetapi Paket Pulang Kerja belum bisa dijual 30 menit pertama.

#### 2e. Cold brew tanpa listrik dan keamanan pangannya

**Pilihan tempat merendam:**
- **Kulkas rumah (dipilih).** Panduan kopi menyebut kulkas sebagai pilihan utama. Suhu ruang hanya "boleh" sekitar 12 jam di dapur yang sejuk 18–24°C ([Complete Home Barista: suhu ruang vs kulkas](https://completehomebarista.com/faqs/brewing-methods/cold-brew/room-temp-vs-fridge-brew-time/)). Suhu ruang Jakarta lebih panas dari itu, jadi **jangan merendam di suhu ruang** [aturan internal].
- **Risikonya:** cold brew tidak pernah dipanaskan. Penelitian University of Georgia menemukan bakteri patogen yang sengaja dimasukkan **tidak tumbuh** di cold brew, tetapi **tetap hidup 9–12 hari** ([UGA Field Report](https://fieldreport.caes.uga.edu/can-cold-brew-coffee-make-you-sick/)). Jadi kebersihan wadah dan suhu dingin tetap penting.
- **Lama rendam:** 12–24 jam di kulkas masih dalam rentang yang umum dipakai ([Complete Home Barista: 12, 24, atau 48 jam](https://completehomebarista.com/faqs/brewing-methods/cold-brew/steep-time-12-24-48-hours/)). Jadwal 2b memakai 13–24 jam.

**Resep (dari `ops-kafe.md` SOP-03):** perbandingan 1 : 5 (kopi house blend digiling kasar : air), hasil ±60% dari berat air.

| | Per malam pada 28 tamu | Per batch (2 malam, dengan cadangan) |
|---|---:|---:|
| Gelas es kopi susu | ±19 *(hitungan: 45% minuman pertama + ±2/3 dari gelas kedua 35% [estimasi])* | ±42 (kapasitas 35 tamu) |
| Konsentrat (50 ml/gelas) | ±0,95 L | ±2,1–2,4 L |
| Kopi + air | – | **±700–800 g kopi + 3,5–4 L air**, muat di toples kaca 5,3 L |

**Aturan simpan** [aturan internal, lebih ketat dari blog kopi; `ops-kafe.md` SOP-03]:
- Konsentrat murni: maksimal 7 hari di kulkas, rasa terbaik hari 1–3. Di lapak selalu di atas es.
- Sisa konsentrat murni yang **tetap di atas es** sepanjang malam boleh kembali ke kulkas rumah dan dipakai malam berikutnya kalau umurnya ≤3 hari. Kalau esnya habis atau botol hangat, buang.
- *Base* yang berisi susu dan susu UHT yang sudah dibuka: **dibuang saat tutup**, berapa pun sisanya.
- Perjalanan ke kantor: cooler bag + 4 es gel beku. Panduan menyebut es gel di cooler mobil bertahan sekitar 4–7 jam ([my-best: ice pack](https://id.my-best.com/186)), sedangkan founder pergi ±11 jam. **Tanpa kulkas kantor, bekukan satu botol konsentrat semalam** supaya berfungsi sebagai es, dan ukur suhunya saat tiba di lapak [estimasi; uji di malam latihan].

#### 2f. Es

- **Kebutuhan** [estimasi]:
  - es minum ±150 g per es kopi susu, sekitar 3 kg/malam;
  - es pendingin cooler ±6–8 kg/malam;
  - pesan **10 kg** Rabu–Kamis dan **15 kg** Jumat–Sabtu.
- **Pemasok:** CoolFresh, Pulogadung (satu kecamatan dengan Rawamangun). Es kristal Rp9.950/5 kg, kurir instan, **maksimal 20 kg per pesanan** ([Tokopedia CoolFresh](https://www.tokopedia.com/espugautama/es-batu-kristal-jakarta-timur-100-halal-5kg)). Ongkir kurir belum dicari, jadi biayanya masuk [estimasi].
- **Cadangan:** penjual lain Rp11.999–16.000/5 kg ([Tokopedia](https://www.tokopedia.com/find/es-kristal-5-kg), dari `research/cost-inputs.md`). Saat survei, cari juga agen es dekat titik.
- **Hanya es kristal kemasan pabrik yang terdaftar** (contoh es kristal dengan nomor izin edar MD di [productlist.id](https://productlist.id/products/es-kristal-md-221622000100046)). **Jangan memakai es balok untuk minuman.** Di Jakarta pernah ada kasus es balok tercemar ([Jakarta Post, 2015](https://www.thejakartapost.com/news/2015/03/30/city-bpom-play-blame-game-over-tainted-ice)).
- **Es minum dan es pendingin dipisah** [aturan internal]. Es minum tetap di kantongnya dan diambil dengan sekop, tidak pernah dengan tangan atau gelas. Es yang menyentuh botol tidak masuk minuman.
- **Kalau es habis:** stop es kopi susu. Tawarkan V60, tubruk, atau es kopi susu "tanpa es tambahan" dari *base* yang masih dingin. Catat di log. Penyebab biasanya pesanan terlalu kecil di malam ramai, jadi naikkan pesanan malam serupa minggu depan.

#### 2g. Air dan mencuci gelas tanpa air mengalir

- **Air seduh dan air minum:** galon air mineral 19 L. Harga Aqua isi ulang Rp17.000–20.000 (Juni 2025), Rp24.000 di Indomaret/Alfamart ([harga.web.id](https://harga.web.id/harga-produk-aqua-galon-19-liter-dan-refill.info)). Harga galon isi ulang di Jakarta naik Rp1.000 pada April 2026 ([CNBC Indonesia](https://www.cnbcindonesia.com/news/20260428151251-4-730609/jangan-kaget-harga-air-galon-tiba-tiba-naik-rp1000-ada-apa/amp)).
  - Pemakaian ±10–12 L/malam [estimasi: V60 ±340 ml termasuk bilas filter, tubruk ±150 ml, cicip, air minum].
  - Satu galon cukup untuk ±1,5 malam. Galon kosong Aqua Rp34.900–37.290 ([harga.web.id, Jun 2025](https://harga.web.id/harga-galon-kosong-aqua-dan-vit.info)).
  - Rasa air galon berbeda dengan RO di `ops-kafe.md`. **Dial-in ulang resep V60 dengan air galon.**
- **Air cuci:** ±30–40 L/malam [estimasi]. **Pilihan 1:** keran tuan rumah (wajib ditanyakan, syarat D4). **Pilihan 2:** 2 jerigen 20 L diisi di keran tuan rumah atau depo air setempat.
- **Sistem 3 baskom.** Pedagang makanan sebaiknya mencuci dengan minimal tiga bak: guyur, sabun, bilas. Air diganti begitu kotor ([Jurnal Poltekkes Palu](https://jurnal.poltekkespalu.ac.id/index.php/bjkl/article/download/2922/816/12672)). Survei yang sama menemukan 70% pedagang tidak memakai sabun.
  1. Buang sisa makanan dan minuman ke ember sampah cair.
  2. **Baskom 1:** guyur.
  3. **Baskom 2:** sabun.
  4. **Baskom 3:** bilas.
  5. Tiriskan terbalik di nampan bersih.
  6. Ganti air baskom 3 paling sering.
- **Supaya cuci tidak mengganggu layanan:** punya **24 cangkir dan 24 gelas**, lalu cuci di jeda sepi, bukan saat jam ramai. Ini salah satu kunci throughput solo (bagian 3).
- **Air limbah** dibuang ke saluran milik tuan rumah (dengan izin), **tidak ke trotoar atau got depan** [aturan internal]. Genangan dan bau adalah bahan keluhan tetangga.

#### 2h. Sampah

- Pisahkan [aturan internal]:
  1. **organik basah** (ampas kopi, sisa makanan) di kantong yang diikat;
  2. **kemasan** (cup, plastik, nota).
- Buang ke tempat sampah tuan rumah atau TPS sesuai kesepakatan dengan RT. Ada pos "Iuran kebersihan/warga Rp150 rb, dengan kuitansi" di `numbers.json`.
- **Jangan meninggalkan kantong sampah di trotoar semalaman.**
- Ampas kopi boleh ditawarkan ke warga untuk tanaman. Ini gestur baik dengan tetangga, bukan kewajiban.

#### 2i. Kas

Ringkasnya di SOP-L9:
- kas awal ±Rp200–300 rb pecahan kecil [estimasi];
- tutup shift Qasir, hitung tunai, cocokkan mutasi QRIS di aplikasi bank, foto ke Sheets "Kas Harian";
- **uang tidak pernah ditinggal di lapak**, disetor atau ditransfer setiap minggu.

---

### 3. Uji kenyataan throughput tanpa listrik

#### 3a. Patokan yang bersumber

| Hal | Angka | Sumber |
|---|---|---|
| Giling 15 g di Timemore C2, setelan pour-over | ±25–30 detik (estimasi panduan, bukan uji); lebih lama di gilingan halus dan roast terang | [Complete Home Barista: setelan Timemore C2](https://completehomebarista.com/guides/timemore-c2-grind-settings/) |
| Waktu seduh V60 satu gelas | 2:30–3:30 (Blue Bottle); resep rumah 2:45–3:15 (`ops-kafe.md` SOP-04) | [Blue Bottle](https://bluebottlecoffee.com/us/eng/brew-guides/pour-over) |
| Pour-over di kedai ramai | Waktu persiapan adalah hambatan terbesar | [Perfect Daily Grind](https://perfectdailygrind.com/2025/01/overcoming-challenges-with-pour-over-coffee-wait-times/) |
| Es kopi susu dari *base* | ±20 detik; tanpa *base* ±45–60 detik | `ops-kafe.md` SOP-03 [estimasi] |
| Aroma bubuk setelah digiling | Turun nyata dalam 15–60 menit. Angka populer "60% dalam 15 menit" tidak jelas sumbernya | [Ratio Coffee](https://ratiocoffee.com/blogs/coffee-guides/the-flavor-difference-between-a-fresh-grind-and-a-fresh-brew) · [Crema](https://crema-coffee.com/blogs/coffee-101/coffee-myths-is-grinding-fresh-really-that-much-better) |

**Grinder founder belum diketahui modelnya.** Ukur sendiri: giling 15 g beans yang akan dijual, dengan setelan V60, 5 kali, lalu catat rata-ratanya.

#### 3b. Beban kerja per item (menit kerja tangan) [estimasi, ukur di malam latihan]

| Tugas | Menit | Catatan |
|---|---:|---|
| Sapa + catat pesanan + sebut waktu tunggu V60 + bayar (per grup ±2,5 orang) | 1,5 | QRIS statis lebih cepat dari kembalian tunai |
| **V60** (dosis sudah ditimbang): giling 0,5–0,75 + bilas filter 0,5 + tuang 1,5 + sajikan dan cerita 0,5 | **±3,25** | Waktu tunggu tamu ±5 menit kalau bar kosong. Jeda antar-tuangan dipakai untuk es kopi susu |
| **Es kopi susu** dari *base* | **±0,4** | Es, tuang 185 ml, aduk, sajikan |
| Tubruk (bubuk sudah jadi) | 0,5 | Air dari termos |
| Makanan siap saji | 0,2 | Ala angkringan: tamu ambil sendiri, disebut saat bayar |
| Roti bakar / sate (Jumat–Sabtu) | 1–1,5 | Di kompor kedua, oleh helper |
| Cicip malam solo (cium bubuk 2 beans) | 0,3 | Jumat–Sabtu: tegukan kecil dari teko cicip |
| Cuci per gelas | 0,5 | **Bisa ditunda ke jeda sepi** |
| Isi ulang ceret/termos | 1 per ±4 V60 | – |

**Contoh jam ramai solo:**
- 12 tamu datang dalam satu jam (5 grup), memesan 5 V60, 7 es kopi susu, 3 tubruk, dan 9 makanan siap saji.
- Beban kerja: 7,5 (sapa) + 16,3 (V60) + 2,8 (es kopi susu) + 1,5 (tubruk) + 1,8 (makanan) + 0,9 (cicip) + 1,5 (air) + 3,8 (separuh cuci) = **±36 menit/jam (60%)** *(hitungan)*.
- **Di 15 tamu/jam bebannya ±45 menit (75%).** Di atas itu janji tidak bisa dipegang.

#### 3c. Hasil

| | Founder sendiri (Rabu–Kamis) | Founder + helper (Jumat–Sabtu) |
|---|---|---|
| **V60/jam** | **5–7** realistis, karena founder juga memegang kasir, sapa, dan makanan. Batas ±8 sebelum waktu tunggu lewat 10 menit | **10–12** (founder hanya menyeduh; helper memegang sisanya). Teoretis ±15–18 kalau hanya V60, tetapi giling tangan 20+ dosis per malam melelahkan [estimasi] |
| **Es kopi susu/jam** | **15–25** (dibatasi kasir dan sapa, bukan pembuatannya) | **30–40** |
| **Tamu/jam di jam ramai** | **±12–15** | **±18–22** |

**Kebijakan giling (pre-grinding):**
1. **Es kopi susu:** tidak ada gilingan di lapak, karena konsentrat dibuat di rumah.
2. **Tubruk:** pakai **bubuk jadi** dari roaster, dibeli mingguan dan disimpan rapat. Contoh beans bubuk dijual roaster: Javanegra Flores Bajawa *grounds* 200 g Rp110.000 ([Tokopedia](https://www.tokopedia.com/javanegra/javanegra-flores-bajawa-grounds-200gr)). Untuk tubruk Rp8.000 pakai house blend yang lebih murah. Menggiling halus dengan tangan terlalu lama.
3. **V60:**
   - **Giling per gelas** (standar).
   - Yang disiapkan sebelumnya hanya **timbangan dosis beans utuh** di toples 15 g, sehingga timbang ulang tidak perlu.
   - **Pengecualian Jumat–Sabtu:** kalau antre ≥3 V60, helper boleh menggiling **paling banyak 2 dosis di depan** ke toples tertutup, dipakai **≤15 menit** [aturan internal, mengikuti sumber aroma di 3a].
   - **Tidak pernah menggiling sebelum buka.**
4. **Grinder kedua** (Timemore Chestnut S3, tercantum Rp1,4 juta di toko Timemore Indonesia, model dan tanggal belum pasti; [Tokopedia](https://www.tokopedia.com/timemore-coffee-indonesia/timemore-manual-coffee-grinder-chesnut-s3-grinder-kopi-manual-1732373490369856534)) **tidak dibeli sekarang**. Pertimbangkan setelah 4 minggu kalau Jumat–Sabtu rutin ≥10 V60/jam.

**Janji 3 menit:**
- **Es kopi susu ≤3 menit: bisa dipegang**, dengan tiga syarat:
  1. *base* dicampur sebelum buka;
  2. es kopi susu selalu menyalip V60;
  3. founder membuatnya di jeda antar-tuangan V60.
- **V60 tidak dijanjikan 3 menit.** Sebut sebelum bayar (D3): "V60 sekitar 5 menit. Kalau ada 2 V60 di depan, sekitar 10–12 menit. Mau es kopi susu dulu sambil nunggu?"
- **Ambang board D9:** kalau >20% tamu malam solo menunggu minuman pertama >10 menit, tambah helper Kamis atau tutup Kamis. Catat waktu pesanan dan waktu minuman pertama di log malam (bagian 8).

#### 3d. Apakah kapasitas 37 tamu/malam bertahan?

**Rumus** [estimasi]: kursi × jam buka × okupansi 80% ÷ lama duduk, lalu dibagi 0,8 karena 20% tamu membawa pulang (pos cup di `numbers.json`).

| 16 kursi bersandaran (4 meja × 4) | Duduk 2,5 jam | Duduk 3 jam |
|---|---:|---:|
| Rabu–Kamis 19.00–24.00 (5 jam) | 32 | 27 |
| Rabu–Kamis 19.30–24.00 (4,5 jam) | 29 | 24 |
| Jumat–Sabtu 18.00–24.00 (6 jam) | 38 | 32 |
| **Rata-rata 4 malam (buka 19.00)** | **35** | **29** |
| Rata-rata dengan 15 kursi | 33 | 27,5 |

*(hitungan)* Panel lapak menyebut tamu duduk 2–3 jam (`offer.md`). `launch-kafe.md` memakai 2,5 jam untuk kafe.

**Kesimpulan:**
- **37 hanya tercapai di ujung optimistis.**
- **Kursi dan lama duduk** membatasi lebih dulu daripada bar, kecuali saat tiga grup datang bersamaan di malam solo.
- Pakai **30** untuk perencanaan [estimasi]. Rencana 28 masih di bawahnya, tetapi itu berarti meja penuh hampir sepanjang malam.
- **Kalau lama duduk ternyata 3 jam, tambah 2–4 kursi** (selama masih di dalam batas persil) sebelum menambah malam.

---

### 4. Daftar alat

#### 4a. Sudah dimiliki founder (konfirmasi, jangan beli dobel)

| Barang | Yang perlu dicek |
|---|---|
| Grinder tangan | Model? Waktu giling 15 g (bagian 3a) |
| Dripper V60 (perlu 2) dan server | Jumlah |
| Timbangan dengan timer | Baterai cadangan |
| **Kettle leher angsa** | **Kettle listrik tidak bisa dipakai.** Kalau milik founder listrik, beli versi kompor: Rp130.000–522.500 ([Tokopedia: ketel leher angsa](https://www.tokopedia.com/find/ketel-leher-angsa) · [vivcoffee Rp185.000](https://www.tokopedia.com/vivcoffee/teko-leher-angsa-550ml-gooseneck-coffee-kettle)). Belum masuk total di bawah |
| HP untuk Qasir, powerbank | – |

#### 4b. Yang dibeli

Harga dari cuplikan hasil pencarian 8 Nov 2026. "Anggaran" memakai pilihan tengah atau atas supaya konservatif.

| # | Barang | Jumlah | Harga tayang | Anggaran | Sumber | Catatan |
|---|---|---:|---|---:|---|---|
| 1 | **Tenda lipat 3×3** | 0 | Rp480.150–741.000; dengan dinding mika 3 sisi Rp1.620.000 | **Rp0** | [Tokopedia: tenda 3x3](https://www.tokopedia.com/find/tenda-3x3) · [tenda jualan 3x3](https://www.tokopedia.com/find/tenda-jualan-3x3-full-set) | **Pilih teras beratap** (board). Kalau tidak beratap: +Rp741 rb s.d. Rp1,62 jt, dan pemasangan solo jadi lebih lama |
| 2 | **Gerobak angkringan** (bar + lemari terkunci) | 1 | Rp2.000.000 (mahoni, Klaten), Rp2.450.000 (jati), sampai Rp3.500.000 | **Rp3.000.000** | [Tokopedia: gerobak angkringan](https://www.tokopedia.com/find/gerobak-angkringan) · [IDN Times: Rp3–5 jt](https://www.idntimes.com/business/economy/segini-modal-usaha-angkringan-serta-tips-dan-peralatannya-00-qftxr-gn4q17) | Ongkir dari Klaten belum diketahui, jadi minta penawaran. Anggaran memberi ruang ±Rp0,5–1 jt untuk ongkir [estimasi]. Alternatif: 2 meja lipat koper 120×60 @Rp363.690 ([Tokopedia, cuplikan](https://www.tokopedia.com/find/meja-lipat-jualan)) kalau tuan rumah punya ruang simpan tertutup |
| 3 | **Kursi plastik bersandaran** (bisa ditumpuk) | 16 | Napolly BIG 209 Rp60.735–113.000; NG 100 Rp95.000 | Rp1.520.000 | [Tokopedia: kursi napolly](https://www.tokopedia.com/find/kursi-plastik-napoli-original) · [kursi plastik sandaran](https://www.tokopedia.com/find/kursi-plastik-sandaran) | Menggantikan tikar (offer v3: duduk di tikar 2–3 jam pegal) |
| 4 | Meja plastik | 4 | Napolly BIG 7550 Rp153.500; motif rotan Rp179.999 | Rp614.000 | [Tokopedia: meja plastik napolly](https://www.tokopedia.com/find/meja-plastik-napolly) | – |
| 5 | Cooler box besar | 1 | Soleil 45 L Rp749.900–899.900 | Rp899.900 | [Ruparupa](https://www.ruparupa.com/soleil-45-ltr-cooler-box-biru-muda.html) | Es minum + botol. Marina tidak ada ukuran 45 L di hasil pencarian |
| 6 | Cooler box kecil | 1 | Marina 18S 16 L Rp473.005–538.110 | Rp538.110 | [Tokopedia Lion Star Marina 18S](https://www.tokopedia.com/lionstarindonesia/lion-star-kotak-pendingin-marina-cooler-box-18s-16-liter-i-17-1730862486830941300) | *Base* + susu terbuka |
| 7 | Cooler bag + 4 es gel | 1 set | Tas Rp39.541–280.600; gel 400 ml Rp1.342–6.000 | Rp304.600 | [Tokopedia: ice pack gel](https://www.tokopedia.com/find/ice-pack-gel-tahan-lama) · [GabaG](https://www.tokopedia.com/gabag/etalase/tmt_24552) | Untuk membawa konsentrat dari rumah |
| 8 | Kompor gas 1 tungku | 1 | Rinnai RI-301S Rp155.000–245.000 | Rp245.000 | [Tokopedia: rinnai 1 tungku](https://www.tokopedia.com/find/rinnai-1-tungku) · [Pricebook](https://pricebook.co.id/article/market_issue/11889/kompor-gas-1-tungku-murah) | Untuk ceret/kettle |
| 9 | Regulator + selang SNI | 1 paket | Rp136.803–208.000 | Rp208.000 | [Tokopedia: selang regulator](https://www.tokopedia.com/find/selang-regulator-gas-3kg) · [Winn Gas W900](https://www.tokopedia.com/find/regulator-gas-winn-w900) | Pastikan label SNI |
| 10 | Tabung Bright Gas 5,5 kg + isi (perdana) | 1 | Rp326.000 (harga promo saat peluncuran, tanggal tidak jelas); isi ulang Rp102.000 (agen Jawa, sejak 15 Agu 2026) | Rp326.000 | [ESDM Migas](https://migas.esdm.go.id/post/dirjen-migas-hadiri-peluncuran-bright-gas-5,5-kg) · [Bisnis.com](https://ekonomi.bisnis.com/read/20260815/44/1996598/pertamina-turunkan-harga-bright-gas-ini-rinciannya) | **Bukan LPG 3 kg.** Pembelian LPG 3 kg untuk usaha mikro mensyaratkan NIB dan pendaftaran di pangkalan ([Bisnis.com](https://ekonomi.bisnis.com/read/20250203/44/1836261/beli-lpg-3-kg-di-pangkalan-ada-kuotanya-simak-ketentuannya)), dan mulai 2026 direncanakan memakai NIK ([Kompas TV](https://www.kompas.tv/info-publik/613813/mulai-2026-beli-lpg-3-kg-wajib-pakai-ktp-ini-kelompok-yang-berhak-dan-dilarang)) |
| 11 | Kompor portabel gas kaleng (kompor kedua) + 2 kaleng | 1 + 2 | Hi-Cook Rp100.000–120.000 (artikel 2025); kaleng 230 g Rp23.500–25.300 | Rp170.600 | [Viva](https://techno.viva.co.id/elektronik/14809-suka-camping-ini-5-pilihan-kompor-portable-murah-terbaik-2025) · [Tokopedia: gas kaleng](https://www.tokopedia.com/find/gas-kaleng-portable) | Roti bakar dan sate Jumat–Sabtu, sekaligus cadangan |
| 12 | Ceret stainless 3 L | 1 | Rp46.800–249.900 | Rp249.900 | [Ruparupa Krischef 3 L](https://www.ruparupa.com/krischef-ketel-air-3-ltr.html) · [Lazada](https://www.lazada.co.id/trending/Stove-Kettles-Top-AddToCart/514068533) | Rebus air banyak, lalu pindah ke kettle leher angsa |
| 13 | Termos 2 L | 1 | Lion Star 2 L (plastik) Rp124.000–134.000; stainless Thermos 2 L Rp559.440 | Rp134.000 | [Tokopedia: termos air panas](https://www.tokopedia.com/find/termos-air-panas) | Air panas untuk tubruk dan bilas filter |
| 14 | Termometer digital | 1 | TP300 Rp29.900–59.000 | Rp59.000 | [Tokopedia TP300](https://www.tokopedia.com/emarket-id/termometer-digital-tp300-thermometer-makanan-kopi-bbq-minyak-dapur) | Suhu air seduh **dan** suhu cooler |
| 15 | Wajan roti bakar | 1 | Rp50.000–250.000 | Rp250.000 | [Tokopedia: panggangan roti bakar](https://www.tokopedia.com/find/panggangan-roti-bakar) · [wajan roti bakar](https://www.tokopedia.com/find/wajan-roti-bakar-alat) | Jumat–Sabtu |
| 16 | Tudung saji | 2 | Rp19.000–69.900 | Rp139.800 | [Tokopedia: tudung saji](https://www.tokopedia.com/find/tudung-saji) | Makanan siap saji tidak terbuka |
| 17 | Lampu LED baterai | 4 | TaffLED 10 W Rp39.900; AOKI 18650 Rp145.306; AOKI + powerbank Rp198.000 | Rp581.200 | [Tokopedia AOKI](https://www.tokopedia.com/aoki-official/etalase/lampu-camping) · [lampu tenda camping](https://www.tokopedia.com/find/lampu-tenda-camping) | 2 di bar, 2 di area duduk. Warna hangat |
| 18 | Cangkir enamel blirik 8 cm | 24 | Rp21.052–35.000 | Rp840.000 | [Tokopedia: cangkir enamel lurik](https://www.tokopedia.com/find/cangkir-enamel-lurik-8cm) | V60, tubruk |
| 19 | Gelas kaca (set 6) | 4 set | ±Rp23.419/set | Rp93.700 | Cuplikan pencarian Tokopedia, halaman persis tidak pasti ([contoh toko](https://www.tokopedia.com/gelas5saudara/etalase/sold)) | Es kopi susu dine-in |
| 20 | **APAR powder 3 kg** | 1 | Rp299.000–390.000 | Rp390.000 | [Tokopedia: APAR 3 kg dry powder](https://www.tokopedia.com/find/apar-3kg-dry-powder) | **Wajib**, selalu di samping kompor |
| 21 | X-banner 60×160 + tiang | 1 | Rp45.000–65.000 | Rp65.000 | [Tokopedia](https://www.tokopedia.com/gamblangmediapromo/x-banner-60x160-korcin-440-free-desain-murah-dan-berkualitas-flexi-280) | Papan ≤1 m² yang menempel di bangunan dikecualikan pajak reklame (bagian 9) |
| 22 | Spanduk flexi ±3 m² | 1 | Rp28.000/m² | Rp84.000 | [Tokopedia](https://www.tokopedia.com/gamblangmediapromo/cetak-spanduk-print-banner-baliho-online-murah-flexy-korcin-440) | – |
| 23 | Jerigen HDPE 20 L food grade | 2 | Rp75.000 | Rp150.000 | [Tokopedia: jerigen 20 liter](https://www.tokopedia.com/find/jerigen-air-20-liter) | Air cuci kalau tidak ada keran |
| 24 | Jerigen dengan keran 10 L | 1 | Rp206.800 | Rp206.800 | Sama | Cuci tangan |
| 25 | Baskom 52 cm | 3 | Rp34.000 | Rp102.000 | [Tokopedia](https://www.tokopedia.com/tokoanekaplastikspj/product) | Sistem 3 baskom |
| 26 | Galon kosong 19 L | 1 | Rp34.900–47.000 | Rp47.000 | [harga.web.id](https://harga.web.id/harga-galon-kosong-aqua-dan-vit.info) · [Tokopedia](https://www.tokopedia.com/find/galon-air-kosong) | Pompa galon manual: harga belum dicari |
| 27 | Container box 100 L beroda | 2 | Rp188.000–200.800 | Rp401.600 | Cuplikan pencarian Tokopedia ([Shinpo](https://www.tokopedia.com/miraclestar/etalase/shinpo)) | Stok kering, gelas |
| 28 | Kantong sampah 60×100 + ember bertutup 20 L | 2 pak + 2 | Rp12.083/pak isi 16; ember Rp40.000–59.000 | Rp142.200 | [Tokopedia: kresek hitam besar](https://www.tokopedia.com/find/kresek-hitam-besar) · [ember plastik](https://www.tokopedia.com/find/ember-plastik-besar) | Sampah dan sampah cair |
| 29 | Toples kaca 5,3 L (rendam cold brew) | 1 | Rp99.900 | Rp99.900 | [Ruparupa Picas 5,3 L](https://www.ruparupa.com/p/toples-makanan-kaca-bulat-5-3-ltr.html) | Di rumah |
| 30 | Barang kecil: gembok + rantai, nampan, saringan cold brew, 4 botol 1 L, toples dosis, lap, sabun, sanitizer food grade, P3K | – | **Belum dicari** | **Rp500.000 [estimasi]** | – | Cari harga saat belanja |
| | **Total anggaran** | | | **±Rp12.606.000** *(hitungan, dibulatkan per pos di bagian 11)* | | Termurah (listing paling murah): ±Rp8,8 jt. Termahal: ±Rp13,3 jt |

#### 4c. Dibanding pos startup di `numbers.json`

| Pos `numbers.json` | Lama | Usulan | Alasan |
|---|---:|---:|---|
| Tenda lipat 3×3 | Rp2.250.000 | **Rp0** (Rp741 rb–1,62 jt kalau tidak beratap) | Teras beratap; harga nyata lebih murah dari estimasi |
| Gerobak/meja bar | Rp3.000.000 | Rp3.000.000 | Harga Rp2,0–3,5 jt + ongkir |
| Bangku, meja, tikar | Rp2.300.000 | Rp2.134.000 | 16 kursi bersandaran + 4 meja; tikar dihapus |
| Cooler 2 unit | Rp1.000.000 | **Rp1.745.000** | Cooler 45 L + 16 L + cooler bag dan gel |
| Kompor + tabung | Rp600.000 | **Rp950.000** | Dua kompor (air dan makanan), tabung 5,5 kg perdana, regulator SNI |
| Lampu + powerbank | Rp600.000 | Rp600.000 | 4 lampu Rp581 rb |
| Gelas, cangkir, nampan | Rp1.000.000 | Rp1.000.000 | Rp934 rb + nampan |
| APAR | Rp300.000 | Rp390.000 | Powder 3 kg |
| Banner, papan nama | Rp700.000 | **Rp300.000** | X-banner + spanduk Rp149 rb + kartu meja |
| *Baru:* air & cuci, ceret/termos/termometer, wajan + tudung, container box, sampah, toples, barang kecil | – | Rp2.487.000 | Rincian di 4b |
| **Total alat** | **Rp11.750.000** | **±Rp12.606.000** (+Rp856 rb) | Tanpa gerobak: ±Rp10,3 jt. Tanpa atap: +Rp0,74–1,62 jt |

**Pemasok bahan** tetap dari `ops-kafe.md` §2a–2c: beans Otten/Murrell/Sakha, house blend Otten Rp246.000/kg, susu UHT Diamond 1 L Rp22.500, gula aren Mahorahora Rp60.000/L, filter Hario Rp85.000/100, cup PET BBC Rp730/set. Ada dua perubahan:
- **susu harus UHT karton** (tahan suhu ruang sebelum dibuka), bukan susu segar;
- **tubruk memakai bubuk jadi**.

---

### 5. Makanan

#### 5a. Menu menurut malam (dari `offer.md` v3, syarat D2)

| | Rabu–Kamis (solo) | Jumat–Sabtu (dengan helper) |
|---|---|---|
| Makanan | **Hanya siap saji:** nasi kucing, gorengan, kue/roti | Ditambah **roti bakar dan sate** di kompor kedua |
| Paket | Pulang Kerja Rp25.000 (es kopi susu + nasi kucing + gorengan) | Ditambah Sesi Bareng Rp75.000 |

#### 5b. Buat sendiri atau titip, dan dampaknya ke margin

**Kenyataan jadwal:** founder bekerja kantor Senin–Jumat dan tidak punya waktu memasak di rumah pada hari lapak. **Semua yang dibuat sendiri harus dirakit di lapak** (roti bakar, sate dibakar) **atau disiapkan Sabtu siang.**

| Item | Cara | Harga pembanding | HPP | Catatan |
|---|---|---|---|---|
| Nasi kucing | **Titip atau beli putus** dari pembuat lokal | Jakarta Selatan Rp5.000–7.500/porsi ([IDN Times](https://www.idntimes.com/food/dining-guide/angkringan-di-jakarta-selatan-c1c2-01-3ln1w-68kmbj)); BSD Rp4.000 ([Prasetiya Mulya, 2026](https://elib.prasetiyamulya.ac.id/1583/)); Jogja Rp2.000–2.500 ([detik, 2023](https://www.detik.com/jogja/kuliner/d-7088744/20-menu-angkringan-favorit-dan-sejarahnya-sebagai-ikon-jogja/amp)) | ±70–80% [estimasi] | Komisi titip jual umum 20–60% dari harga jual ([Gramedia](https://www.gramedia.com/best-seller/?p=26130)). Tarif khusus angkringan tidak ditemukan |
| Gorengan, kue/roti | Titip atau beli putus | Gorengan Jogja Rp500–1.000 (detik, 2023). Harga Jakarta tidak ditemukan | ±70–80% [estimasi] | Survei 3 penjual di sekitar titik |
| Sate (usus, telur puyuh, ati ampela) | Beli matang/bumbu dari pemasok, **bakar di lapak** (Jumat–Sabtu) | Sate mulai Rp1.500 di Jakarta Selatan ([IDN Times](https://www.idntimes.com/food/dining-guide/angkringan-di-jakarta-selatan-c1c2-01-3ln1w-68kmbj)) | ±55–65% [estimasi] | Panaskan sampai panas sebelum disajikan |
| Roti bakar | **Buat sendiri di lapak** (Jumat–Sabtu) | Bahan ±Rp5.300/porsi (`ops-kafe.md` §2d) | ±44–53% pada harga Rp10.000–12.000 *(hitungan)* | Margin terbaik di menu makanan |

**Dampak ke margin:**
- `numbers.json` memakai **HPP makanan ±62%**: malam solo ±72% (siap saji/titip), Jumat–Sabtu ±55%. Itu konsisten dengan tabel di atas, jadi **tidak perlu diubah sekarang.**
- **Risikonya:** kalau semua makanan dititip (±72%), kontribusi turun ±Rp1.040/tamu dan break-even naik ±2 tamu/malam (`offer.md` mencatat skenario ini).
- **Ganti ke beli putus** begitu satu item laku stabil (misalnya >15 porsi/malam selama 4 minggu). Pola "titip dulu, jual putus kalau laku" dari `ops-kafe.md` §2d.
- **Perjanjian titip tertulis** ([kontrakhukum.com](https://kontrakhukum.com/article/skema-titip-jual-dalam-draft-perjanjian-konsinyasi-surabaya-bagi-umkm/)) memuat:
  - harga mitra;
  - siapa menanggung sisa;
  - **jam antar (18.30 atau 17.45) dan jam masak tertulis di nota**;
  - sertifikat halal mitra;
  - pengganti kalau mitra tidak datang.

#### 5c. Keamanan pangan tanpa kulkas

- **Nasi matang dan Bacillus cereus.** Bakteri ini bertahan dalam bentuk spora saat nasi dimasak, dan racunnya tahan panas, sehingga dipanaskan ulang pun tidak selalu aman ([detikHealth](https://health.detik.com/diet/d-8278034/salah-kaprah-memanaskan-nasi-sisa-tidak-bau-bukan-jaminan-masih-aman) · [FSANZ](https://www.foodstandards.gov.au/consumer/safety/foodborne-illness/bacillus-cereus)).
- **Berapa lama boleh di suhu ruang?** Sumber berbeda:
  - FDA/CDC (dikutip [Halodoc](https://www.halodoc.com/artikel/waspada-suhu-zona-bahaya-makanan-agar-tetap-aman-dikonsumsi) dan [Popmama](https://www.popmama.com/life/health/berapa-lama-makanan-boleh-disimpan-di-suhu-ruang-00-h1fg6-tx69rd)): makanan matang ≤2 jam di suhu ruang, **≤1 jam di atas 32°C**.
  - BPOM memakai batas **4 jam setelah dimasak** untuk makanan siap saji program MBG ([detikHealth](https://health.detik.com/berita-detikhealth/d-8662789/kepala-bpom-sebut-mbg-lewat-4-jam-basi-sppg-nakal-siap-siap-ditutup)).
  - Kemenkes (menurut detikHealth): sajian panas ≥60°C, simpan dingin ≤4°C.
- **Aturan internal Lapak Yok:**
  1. Makanan titip **diantar paling lama 1 jam sebelum buka**, dengan **jam masak tertulis di nota**. Tanpa jam masak, tolak.
  2. **Dijual paling lama 4 jam setelah dimasak** (patokan BPOM). Pesan dalam 2 gelombang di malam ramai (18.30 dan ±21.00) supaya tidak ada nasi yang dipajang lebih dari 4 jam.
  3. Sisa yang lewat batas **dibuang dan dicatat** di Sheets "Waste". **Tidak pernah dijual besok, tidak pernah dipanaskan ulang untuk dijual.**
  4. Pajang di bawah tudung saji, di tempat teduh, **tidak di dekat kompor atau lampu panas**.
  5. Sate dan roti bakar dipanaskan sampai panas saat dipesan.
  6. Susu UHT yang sudah dibuka dan *base* kopi susu: di atas es, dibuang saat tutup.
  7. Cuci tangan di jerigen keran sebelum memegang makanan. Penjamah tidak memegang uang dan makanan bergantian tanpa cuci tangan (QRIS membantu).
- **Penelitian di Malioboro** menemukan pedagang angkringan yang ikut kursus higiene sanitasi punya angka kuman alat makan lebih rendah (cuplikan pencarian riset Poltekkes Yogyakarta). **Founder dan helper sebaiknya ikut pelatihan penjamah pangan** kalau tersedia murah atau gratis di Sudinkes/puskesmas (pertanyaan terbuka).

**Halal untuk makanan titip.** Kewajiban halal berlaku untuk makanan dan minuman termasuk di lapak PKL sejak 18 Okt 2026 (bagian 9). **Setiap pemasok titip harus punya sertifikat halal sendiri.** Banyak pembuat nasi kucing rumahan mungkin belum punya. Tanyakan sejak survei, dan bantu arahkan mereka ke SEHATI (gratis).

---

### 6. Orang

#### 6a. Helper Jumat–Sabtu

| Hal | Isi |
|---|---|
| **Tugas** | Pasang lapak (SOP-L1), kasir/host, es kopi susu, tubruk, makanan, roti bakar dan sate, cuci, bongkar. Dilatih V60 dasar sebagai cadangan mulai bulan 2 |
| **Jam** | **17.30–00.15 (6,75 jam)**, istirahat 30 menit ±21.00. Di bawah 7 jam/hari dan 35 jam/minggu, syarat upah per jam |
| **Upah minimal** | UMP DKI 2026 **Rp5.729.876** ([Katadata](https://katadata.co.id/amp/berita/industri/694bb57d97fa5/ump-jakarta-2026-resmi-naik-jadi-rp-5-72-juta/)) ÷ 126 = **Rp45.475/jam**. Upah per jam hanya untuk pekerja <7 jam/hari dan <35 jam/minggu (PP 36/2021 Pasal 16; [Bisnis.com/Kemenaker](https://ekonomi.bisnis.com/read/20210302/12/1362701/kemenaker-tegaskan-upah-per-jam-hanya-untuk-pekerja-paruh-waktu) · [Gadjian](https://www.gadjian.com/blog/2023/02/23/cara-menghitung-gaji-karyawan-part-time/)) |
| **Per malam** | 6,75 × Rp45.475 = **Rp306.958** *(hitungan)* |
| **Per bulan** | × 8,67 malam (2 × 52 ÷ 12) = **Rp2.660.300** *(hitungan)*. `numbers.json` mencatat Rp1,97 jt untuk 5 jam (18.00–23.00), tetapi rencana `lapak-malam.md` sendiri menyuruh helper memasang dari 17.30 |
| **BPJS** | Usaha mikro wajib minimal JKK dan JKM ([Hukumonline, Perpres 109/2013](https://www.hukumonline.com/berita/a/3-regulasi-ini-perlu-dibenahi-agar-selaras-sjsn-lt582fda8100641/)). Besarnya ±0,54% upah [estimasi: JKK kelompok risiko terendah 0,24% + JKM 0,30%; cek di [BPJS TK](https://www.bpjsketenagakerjaan.go.id/artikel/18913/artikel-berapa-besaran-iuran-jht,-jkk,-jkm,-jp-dan-jkp)] ≈ Rp14.400/bulan |
| **Kalau helper perempuan** | Bekerja antara 23.00 dan 07.00: wajib diberi makan-minum bergizi dan dijaga keamanannya. Pulang antara 23.00 dan 05.00: **wajib antar-jemput** (UU 13/2003 Pasal 76; [Hukumonline](https://www.hukumonline.com/klinik/a/aturan-lembur-untuk-pekerja-perempuan-lt50eb906629072) · [Talenta](https://www.talenta.co/blog/aturan-shift-malam-perempuan/)). Perempuan di bawah 18 tahun dilarang bekerja di jam itu. Biaya: ojek ±Rp20–30 rb + makan ±Rp15 rb per malam [estimasi] ≈ **+Rp0,3–0,39 jt/bulan** |
| **Usia** | Minimal 18 tahun [aturan internal; wajib untuk perempuan di jam malam] |
| **Kontrak** | Tertulis: jam, upah per jam, cara bayar (mingguan), tugas, masa coba 2 malam berbayar, pemberitahuan 1 minggu sebelum berhenti. Status setelah UU Cipta Kerja: tanya konsultan |

**Cara mencari:**
1. **Mahasiswa UNJ.** Kampus UNJ ada di Rawamangun ([Antara](https://kupang.antaranews.com/berita/82489/tingkatkan-keahlian-mahasiswa-unj-resmi-miliki-sangsang-univ-zone)). Jalur yang realistis: grup info loker mahasiswa dan akun kemahasiswaan. Lowongan khusus UNJ tidak ditemukan dalam pencarian.
2. Portal lowongan (Glints, KitaLulus, Indeed) dengan filter Jakarta Timur.
3. Tulisan "Dicari helper Jumat–Sabtu" di lapak saat malam latihan, dan rekomendasi warga lewat RT.
4. **Siapkan 2 cadangan** yang sudah ikut 1 malam latihan berbayar.

**Pelatihan sebelum 9 Des:**
- 2 malam latihan berbayar (±Rp614 rb *(hitungan)*);
- SOP-L1, L4, L7, L9;
- keselamatan gas dan cara memakai APAR;
- aturan makanan 4 jam;
- naskah sapa.

#### 6b. Rota mingguan

| | Sen | Sel | Rab | Kam | Jum | Sab | Min |
|---|---|---|---|---|---|---|---|
| Founder: kantor | 07.30–17.30 | 07.30–17.30 | 07.30–17.30 | 07.30–17.30 | 07.30–17.30 | – | – |
| Founder: lapak | – | Konsentrat + dosis 19.00–20.00 | 17.30–01.00 | 17.30–01.00 | 17.30–01.00 | 16.00–01.00 | **Libur penuh** |
| Helper | – | – | – | – | 17.30–00.15 | 17.30–00.15 | – |
| Orang di jam ramai | – | – | 1 | 1 | 2 | 2 | – |

**Bulan pertama (sepi):** rota tetap sama. Jangan memotong helper Jumat–Sabtu untuk berhemat. Alasan board untuk helper adalah keamanan (gas, kas, 20+ tamu), bukan volume.

#### 6c. Jam kerja founder dan peringatan kelelahan

| Kegiatan | Jam/minggu |
|---|---:|
| Kantor Senin–Jumat 07.30–17.30 | 50 |
| Lapak Rabu, Kamis, Jumat (17.30–01.00, termasuk perjalanan) | 22,5 |
| Lapak Sabtu (16.00–01.00, termasuk belanja dan persiapan) | 9 |
| Konsentrat, dosis, kartu beans (Selasa, Kamis pagi, Jumat dini hari) | ±2 |
| Belanja mingguan, Sheets, media sosial, pesan pemasok | ±4 [estimasi] |
| **Total** | **±87** (belum termasuk perjalanan pagi ke kantor) |

**Tidur pada malam Rabu→Kamis dan Kamis→Jumat sekitar 4,5 jam** (01.30–06.00).

**Peringatan:**
- WHO dan ILO memperkirakan kerja **≥55 jam/minggu** dikaitkan dengan **risiko stroke ±35% lebih tinggi** dan **risiko meninggal karena penyakit jantung iskemik ±17% lebih tinggi**, dibanding 35–40 jam ([WHO, 17 Mei 2021](https://www.who.int/news/item/17-05-2021-long-working-hours-increasing-deaths-from-heart-disease-and-stroke-who-ilo)).
- Rencana ini sekitar 1,6× ambang itu.
- Ini bukan diagnosis, tetapi alasan kuat untuk membuat aturan pengaman sejak awal.

**Aturan pengaman** [aturan internal]:
1. **Minggu libur penuh, Senin–Selasa tanpa lapak.** Tidak ada "tambah malam" sebelum review 2 Feb 2027 (board D10, D11).
2. **Tidak memasak di rumah pada hari kantor.** Menu solo siap saji (D2) sekaligus melindungi jam tidur.
3. **Aturan sakit:** demam, pusing, atau kurang tidur 2 malam berturut-turut → **tutup**, umumkan sebelum 16.00 di IG/WA dan Google Maps. Satu malam tutup lebih murah dari satu minggu sakit.
4. **Pulang dengan ojek online, bukan menyetir motor sendiri**, pada malam ketika merasa sangat lelah.
5. **Satu minggu libur setiap 8 minggu.** Misalnya setelah review 2 Feb, dan saat Idul Fitri (sudah direncanakan di `lapak-malam.md`).
6. **Pemicu helper Kamis:** syarat D9 (>20% tamu solo menunggu minuman pertama >10 menit), **atau** founder tidur <5 jam lebih dari 2 malam per minggu selama 3 minggu.
7. **Cek kontrak kerja kantor** soal usaha sampingan dan konflik kepentingan (`lapak-malam.md`).

---

### 7. SOP (satu halaman per SOP; cetak, laminasi, simpan di gerobak)

#### SOP-L1 Pasang lapak (target ≤30 menit)

1. **Cek tempat:** genangan, hujan, ada barang tetangga? Cuci tangan.
2. **Gerobak** ke tanda lakban. **Semua barang di dalam batas persil.** Tidak ada kursi, ember, atau kabel di trotoar.
3. **APAR** di samping titik kompor, pin terpasang, jarum di hijau.
4. **Gas:**
   - pasang regulator;
   - **tes bocor**: oleskan air sabun di sambungan; muncul gelembung = bocor, jangan dinyalakan;
   - nyalakan, ceret di atas api.
5. **Kursi, meja, lampu.** Lorong antar-meja cukup untuk jalan.
6. **Es datang:** es minum di kantong tersendiri, es pendingin di sekitar botol. Termometer di cooler.
7. **Stasiun cuci** 3 baskom + jerigen keran + sabun. Ember sampah dan ember sampah cair.
8. **Makanan:** cek halal dan jam masak di nota, hitung, tanda tangan, tata di bawah tudung saji, kartu harga.
9. **Bar:** grinder, timbangan, 2 dripper, filter, toples dosis, 2 kartu beans, 2 toples cium bubuk. Air mendidih masuk termos dan kettle leher angsa; cek 92–94°C.
10. **Tanda:** X-banner, kartu meja "HP boleh, laptop tidak", standee QRIS, papan menu dengan waktu V60.
11. **Qasir:** buka shift, hitung kas awal.
12. **Base kopi susu 1 L** (SOP-L4).
13. **Sebelum menerima tamu (D2):** lampu menyala, kursi tertata, air panas siap. Kalau belum, jangan buka. **Catat jam selesai pasang** di log.

#### SOP-L2 Lima menit pertama: grup bertiga datang pukul 19.30, Kamis, founder sendiri

Tujuan (syarat D3, diuji dengan stopwatch): **disapa ≤10 detik**, **minuman atau tegukan di tangan ≤5 menit**, **waktu tunggu V60 disebut sebelum bayar**. Founder sedang menuang V60 tamu lain.

| Menit | Yang dilakukan | Kalimat (contoh, sesuaikan gaya sendiri) |
|---|---|---|
| 0:00–0:10 | Angkat kepala dan senyum, **tanpa menghentikan tuangan**. Tunjuk meja kosong | "Malam, Kak! Yok, duduk dulu di sana. Sebentar ya, saya selesaikan seduhan ini, satu menit." |
| 0:10–1:00 | Selesaikan tuangan. Ambil 3 gelas kecil **air putih gratis** dari galon dan antar | "Ini air dulu, Kak. Pulang kerja ya?" |
| 1:00–1:30 | Beri menu. Sampaikan aturan **sekali, dengan senyum** | "Satu info kecil: di sini **HP boleh, laptop kami minta disimpan**, biar semua meja enak buat ngobrol." |
| 1:30–2:15 | Tawarkan jalan tercepat dulu. **Sebut waktu V60 sebelum bayar** | "Kalau mau cepat, **es kopi susu keluar 3 menit**, atau **Paket Pulang Kerja** Rp25 ribu: es kopi susu, nasi kucing, gorengan. Kalau mau kopi seduh, **V60 sekitar 5 menit, tapi ada satu di depan, jadi kira-kira 8–10 menit**. Mau cium dulu dua beans-nya?" |
| 2:15–2:45 | Kalau ada yang ragu memilih V60: sodorkan **2 toples cium bubuk** (cicip malam solo) dan tanya 1 hal | "Yang ini segar kayak buah, yang ini manis cokelat. Kakak suka yang mana?" |
| 2:45–3:15 | Ulangi pesanan, catat di Qasir, **bayar di depan** (QRIS atau tunai). Mulai hitung 3 menit | "Dua Paket Pulang Kerja, satu V60 yang manis cokelat ya, Kak." |
| 3:15–4:30 | Buat 2 es kopi susu dari *base* (±40 detik) dan antar. Ambil makanan atau tunjukkan tudung saji: "silakan ambil sendiri, nanti disebut" | "Ini es kopi susunya. Nasi kucing dan gorengan silakan pilih di sini." |
| 4:30–5:00 | Mulai giling V60 ketiga. Cek singkat lalu **tinggalkan mereka ngobrol** | "V60-nya saya antar sekitar 6 menit lagi ya." |
| 9:00–11:00 | Antar V60 dengan kartu beans. Cerita **satu kalimat** saja, kecuali ditanya | "Ini Gayo, manis kayak gula merah. Kalau nggak cocok di tegukan pertama, bilang ya, saya seduh ulang." |

- **Kalau 3 grup datang bersamaan:** sapa semua dalam 10 detik ("Sebentar ya, Kak, saya ke sana satu-satu"), antar air putih ke semua meja, lalu layani **urut kedatangan**. **Es kopi susu dulu, V60 terakhir.**
- **Kalau meja penuh:** "Lagi penuh, Kak, kira-kira 20 menit. Boleh saya catat nomor WA, nanti saya kabari?"
- **Ukur:** selama 4 malam latihan dan minggu pertama, catat waktu sapa, waktu minuman pertama, dan apakah waktu V60 disebut. **Target: ≥90% memenuhi D3.**

#### SOP-L3 V60 di lapak

**Resep** (dari `ops-kafe.md` SOP-04, ditimbang setiap gelas). Dial-in ulang dengan **air galon**.

| Parameter | Nilai |
|---|---|
| Dosis | 15 g (sudah di toples dosis) |
| Air | 240 g (1 : 16) |
| Suhu | 92–94°C. Air mendidih dari ceret dituang ke kettle leher angsa, lalu cek termometer |
| Gilingan | Medium-fine; setelan per beans ditulis di kartu kecil di gerobak |
| Waktu total | 2:45–3:15 |

**Langkah:**
1. Tunjukkan toples dosis dan kartu beans ke tamu.
2. **Giling di depan tamu** (bagian dari pertunjukan, bukan hambatan).
3. Bilas filter dengan air termos, buang airnya. Panaskan server dan cangkir.
4. Bloom 40 g (0:00–0:35), sampai 150 g pada 1:00, sampai 240 g pada 1:45.
   - Turun lebih cepat dari 2:30 dan rasanya asam/tipis: haluskan gilingan.
   - Lebih lama dari 3:30 dan rasanya pahit: kasarkan.
5. **Di jeda antar-tuangan:** buat es kopi susu yang sedang antre (SOP-L4). **Jangan meninggalkan dripper lebih dari 30 detik.**
6. Sajikan di cangkir blirik dengan kartu beans (roastery + tanggal sangrai; offer v3).
7. **Sesi Bareng (Jumat–Sabtu):** dua V60 20 g : 320 g dari dua beans, di dua server, 4 cangkir.
8. **Teko cicip Jumat–Sabtu:** 2 beans × 10 g : 160 g pukul 18.30. Buang setelah 60 menit (`ops-kafe.md` SOP-04).

#### SOP-L4 Es kopi susu ≤3 menit

**Resep 1 gelas** (`ops-kafe.md` SOP-03): es 150 g · gula aren cair 15 ml · susu UHT full cream 120 ml · konsentrat 50 ml.

1. **Sebelum buka:** campur **base 1 L** di botol bersih berlabel jam (konsentrat 50 : susu 120 : gula aren 15). Simpan di cooler kecil di atas es.
2. **Satu gelas:** gelas + 150 g es minum (sekop) + 185 ml base → aduk → sajikan. **±20–30 detik.**
3. **Es kopi susu selalu menyalip antrean V60.**
4. **Base habis** → campur 1 L lagi. Jangan mencampur lebih dari 1 L sekaligus kecuali Jumat–Sabtu pukul 19.00–21.00 [aturan internal].
5. **Saat tutup:** **semua base dan susu yang sudah dibuka dibuang.** Konsentrat murni mengikuti aturan 2e.
6. **Catat waktu** (pesanan masuk Qasir → gelas di meja) untuk 10 gelas pertama setiap malam. **Target ≥90% ≤3 menit.** Kalau lewat, katakan terus terang ("Maaf Kak, tadi agak antre") dan catat.
7. **Gelas kedua Rp12.000** (es kopi susu atau tubruk). Tawarkan saat gelas pertama tinggal seperempat, **sekali saja**.

#### SOP-L5 Garansi seduh ulang

Janji (offer v3): *tidak cocok di tegukan pertama, diseduh ulang dengan beans lain, gratis* (sekali per gelas).

1. Berlaku kalau tamu bilang di awal (gelas masih hampir penuh). **Jangan berdebat.**
2. Tanya satu hal: "Kurang cocoknya di mana, Kak: terlalu asam, terlalu pahit, atau terlalu ringan?"
3. Pilih beans arah sebaliknya. **Malam solo hanya ada 2 beans**, jadi pilihannya beans yang satu lagi.
4. **Sebut waktunya** ("sekitar 5 menit ya, Kak"). Kalau antrean panjang, tawarkan es kopi susu sebagai ganti, tanpa biaya.
5. Seduh ulang dengan SOP-L3. Ambil gelas lama.
6. Catat di Qasir (item "Garansi" Rp0) dan di Sheets "Waste" (beans, gram, alasan). Satu beans sering diklaim → keluarkan dari menu.
7. Yang kedua masih tidak cocok: minta maaf, tukar ke es kopi susu atau tubruk tanpa biaya. Catat.

#### SOP-L6 Tamu membuka laptop

**Pencegahan:**
- Kartu "HP boleh, laptop tidak" ada di setiap meja, papan menu, Google Maps, IG, dan pesan reservasi.
- **Lapak tidak punya colokan listrik**, dan itu sudah mencegah sebagian besar kasus.

**Kalau tetap terjadi:** kalimat dari `ops-kafe.md` SOP-06, nama diganti.
1. Tunggu jeda. Datangi sendiri, bicara pelan, jangan dari gerobak dan jangan di depan meja lain.
   > "Kak, maaf ganggu sebentar ya. Di Lapak Yok semua meja kami jaga buat ngobrol, jadi laptopnya kami minta disimpan dulu. HP aman kok, kalau perlu balas kerjaan sebentar."
2. Kalau harus bekerja:
   > "Paham banget, Kak. Kalau memang perlu kerja pakai laptop, minumannya bisa saya pindah ke cup take-away, tanpa biaya cup."
3. Terima kasih begitu laptop disimpan. Jangan diungkit lagi.
4. Menolak setelah teguran kedua: tawarkan **pengembalian uang untuk minuman yang belum diminum** dan cup take-away. **Jangan mempermalukan, memotret, atau menyentuh laptopnya.**
5. Catat di log keluhan.

Pengecualian yang boleh: laptop atau tablet untuk menunjukkan foto ke teman beberapa menit.

#### SOP-L7 Rencana hujan (musim hujan Desember–Februari)

**Konteks:**
- BMKG memperkirakan musim hujan 2026/2027 mulai bertahap November–Desember, dengan **puncak Desember 2026 sampai Februari 2027**. Waktunya berbeda per daerah ([InfoPublik](https://infopublik.id/kategori/nasional-sosial-budaya/990317/bmkg-ungkap-prediksi-musim-hujan-2026-2027-mulai-november-puncak-desember) · [Metro TV](https://www.metrotvnews.com/read/b3JC54vB-bmkg-ingatkan-pemda-waspada-ancaman-bencana-di-akhir-2026)). Prakiraan khusus Jakarta tidak ditemukan.
- **Uji 9 Des–2 Feb jatuh tepat di puncak hujan.**

**Pencegahan:**
- **Teras beratap** adalah syarat tempat (D4). Cek di malam hujan saat survei: dari arah mana tampias masuk, dan di mana air menggenang.
- Kalau atap pendek: tirai plastik/terpal samping [harga belum dicari], atau tenda dengan dinding mika 3 sisi (Rp1.620.000, [Tokopedia](https://www.tokopedia.com/find/tenda-jualan-3x3-full-set)).

**Prosedur:**

| Kapan | Langkah |
|---|---|
| Pukul 16.00 | Cek prakiraan dan peringatan dini di [BMKG](https://www.bmkg.go.id) atau aplikasinya |
| Hujan ringan | Buka seperti biasa. Kursi digeser ke area paling dalam. Kapasitas berkurang, jadi **kurangi pesanan makanan titip ±30%** [estimasi] |
| Hujan deras tanpa angin | Buka. Kurangi kursi ke area yang benar-benar kering. Matikan kompor kalau percikan air sampai ke api |
| **Angin kencang, petir, atau genangan masuk teras** | **Tutup atau tunda buka.** Umumkan di IG/WA story dan Google Maps ("Malam ini hujan badai, kita libur dulu. Ketemu besok ya"). Jangan memasang tenda di angin kencang |
| Hujan mulai saat buka | Pindahkan kompor dan bar menjauh dari tampias, tutup makanan, tawarkan take-away |
| Setelah hujan | Lap kursi dan meja sebelum tamu duduk, keringkan lantai, cek sambungan gas |

**Catat malam hujan terpisah** di log (syarat D9), supaya angka 8 minggu tidak salah dibaca.

#### SOP-L8 Satpol PP atau keluhan tetangga

**Pencegahan (lebih penting dari reaksi):**
- Semua barang di **dalam batas persil**. Perda DKI 8/2007 Pasal 25(2) melarang berdagang di jalan dan trotoar, dengan ancaman kurungan 10–60 hari atau denda ([Hukumonline](https://www.hukumonline.com/klinik/a/sanksi-berjualan-di-fasilitas-umum-perumahan-lt51c11b74eca70/)). Penertiban diperketat pada 2026 ([Republika](https://ekonomi.republika.co.id/berita/t9viee416/pramono-tertibkan-pkl-di-trotoar-jakarta)), dan barang sitaan dibawa ke gudang Satpol PP Cakung ([iNews](https://www.inews.id/playlists/peringatan-tak-digubris-satpol-pp-tertibkan-lapak-pkl-dan-pos-ojol-di-senen-jakpus)).
- **Map dokumen di gerobak** (fotokopi + foto di HP): NIB, perjanjian tertulis tuan rumah, pengantar RT/RW dan SKU, surat pernyataan tidak berjualan di trotoar, bukti pendaftaran halal.
- Tidak ada speaker musik. Baku tingkat kebisingan kawasan permukiman adalah **55 dB(A)** menurut Kepmen LH 48/1996 ([CNBC Indonesia](https://www.cnbcindonesia.com/tech/20240815165651-37-563372/viral-ibu-ibu-siram-speaker-begini-aturan-batas-kebisingan-di-ri)). Ukur dengan aplikasi desibel di batas persil pukul 22.00 saat malam latihan [cara ukur kasar].
- **Motor tamu** tidak menutup jalan atau pintu tetangga. Tunjukkan tempat parkir yang disepakati.
- Perkenalkan diri ke tetangga kiri-kanan sebelum malam pertama, dan beri nomor WA untuk keluhan.

**Kalau Satpol PP datang:**
1. Tenang dan sopan. Sapa, perkenalkan diri, **jangan berdebat di depan tamu**.
2. Tunjukkan map dokumen dan batas persil.
3. Kalau petugas menunjuk barang yang melewati batas: **langsung pindahkan.**
4. Kalau diminta tutup: **tutup malam itu.** Catat nama, satuan, jam, dasar aturan yang disebut, dan minta arahan tertulis kalau bisa.
5. Besoknya: lapor ke tuan rumah dan RT/RW, lalu datangi kelurahan atau PTSP Kecamatan Pulo Gadung untuk klarifikasi.
6. **Jangan membayar "uang damai" atau "uang keamanan"** ke siapa pun tanpa dasar dan kuitansi. Pungli Rp250 rb pernah terjadi di Jaktim ([iNews](https://www.inews.id/playlists/2-preman-di-bkt-jaktim-palak-pkl-rp250000-modus-uang-kebersihan)). Laporkan ke Polsek atau kelurahan.

**Kalau tetangga mengeluh** (bising, parkir, sampah, bau):
1. Dengarkan sampai selesai dan minta maaf atas gangguannya (`ops-kafe.md` SOP-07). Tetangga bisa menempuh jalur hukum atas gangguan bising usaha sebelah ([Hukumonline](https://www.hukumonline.com/klinik/a/terganggu-suara-bising-usaha-tetangga-tempuh-langkah-ini-lt50746c4ceafdb/)). **Lebih baik selesai di teras.**
2. Perbaiki malam itu juga: pelankan suara (minta tamu dengan sopan), pindahkan motor, atau bereskan sampah.
3. Datangi lagi besok sore dengan satu kopi gratis dan tanya apakah sudah lebih baik.
4. Catat di log keluhan. **Keluhan yang sama 2 kali dalam sebulan** → bahas dengan tuan rumah dan RT. Pilihannya last order lebih awal (23.00) atau pindah titik.

#### SOP-L9 Bongkar, sampah, dan kas

1. **23.30** last order. **23.45** bereskan stasiun makanan dan kursi kosong.
2. **24.00** tutup. Tamu yang masih ada dipersilakan menghabiskan minuman (maksimal 15 menit).
3. **Gas:** tutup **katup tabung dulu**, biarkan api habis, lalu matikan kompor. Lepas regulator kalau tabung disimpan terpisah.
4. Sambil kompor dan ceret mendingin: **cuci semua gelas** dengan 3 baskom, tiriskan, dan keringkan dengan lap bersih.
5. **Buang:** *base* kopi susu, susu yang sudah dibuka, teko cicip, dan makanan yang lewat 4 jam. Catat di Sheets "Waste".
6. **Konsentrat murni** yang masih dingin masuk cooler bag (aturan 2e).
7. **Sampah:** pisahkan organik dan kemasan, ikat, buang sesuai kesepakatan. Air limbah ke saluran tuan rumah. **Tidak ada kantong sampah di trotoar.**
8. Lap meja dan kursi, tumpuk, masukkan ke gerobak/box, kunci. **Cek batas persil bersih**, dan foto tempat yang sudah bersih ke WA tuan rumah (opsional, membangun kepercayaan).
9. APAR disimpan bersama gerobak. Cek katup tabung sekali lagi.
10. **Kas:**
    - tutup shift di Qasir;
    - hitung tunai dan cocokkan dengan laporan;
    - buka aplikasi bank, cocokkan mutasi QRIS malam ini;
    - isi Sheets "Kas Harian" (tunai, QRIS, selisih, jumlah tamu, malam hujan ya/tidak) dan foto laporan;
    - uang tunai **dibawa pulang**, tidak pernah ditinggal di lapak.
11. Selisih kas >Rp20.000 [aturan internal]: catat penyebabnya (salah kembalian, item tidak tercatat), bahas dengan helper esok harinya, tanpa menyalahkan.
12. Pulang. Isi ulang lampu dan powerbank. Konsentrat ke kulkas.

---

### 8. Alat kerja (stack terkecil)

**MoodBrew tetap dibekukan** (board C1). Tidak ada aplikasi pelanggan; memesan dilakukan lewat percakapan.

| Kebutuhan | Alat | Harga | Mengapa |
|---|---|---|---|
| Kasir | **Qasir**: mulai dengan versi dasar gratis, naik ke **Pro Rp699.000/12 bulan** (≈Rp58.250/bulan) kalau perlu resep/bahan baku | [qasir.id/pricing](https://www.qasir.id/en/pricing) · versi dasar gratis (`research/cost-inputs.md` §5) | Ringan di HP, tanpa kontrak 12 bulan. **Fitur QRIS bawaan Qasir tidak terverifikasi**, jadi QRIS dicatat manual sebagai metode bayar |
| Pembayaran | **QRIS statis** dari bank (contoh [Livin' Merchant Mandiri](https://www.bankmandiri.co.id/livin-merchant/terima-pembayaran-qris-statis)), dicetak di standee + tunai | MDR **0% untuk transaksi ≤Rp100.000** di semua kategori merchant; usaha mikro 0% sampai Rp500.000, berlaku 1 Okt 2026 ([BI](https://www.bi.go.id/id/publikasi/ruang-media/cerita-bi/Pages/mdr-qris.aspx)) | Tanpa listrik dan tanpa mesin EDC. Cek mutasi di aplikasi bank saat tutup |
| HPP, stok, kas | **Google Sheets**, template dari `ops-kafe.md` §5 | Gratis | Sesuai board C1 |
| Reservasi grup Jumat–Sabtu, pemasok, helper | WhatsApp Business | Gratis | Reservasi meja grup (offer v3) |

**Tab Google Sheets:**
- **Dipakai dari `ops-kafe.md`:** Bahan, Resep, HPP & Harga, Penjualan, Stok Mingguan, Waste, Pembelian, Titip jual.
- **Baru:**
  - **Log Malam:** tanggal, jam selesai pasang, jam buka, tamu bayar, belanja per tamu, % paket, lama duduk (sampel 5 meja), waktu minuman pertama malam solo (untuk D9), es kopi susu ≤3 menit, malam hujan ya/tidak, sisa es saat tutup, galon dan gas terpakai.
  - **Kas Harian:** tunai, QRIS, selisih, foto laporan.
  - **Jam Makanan:** pemasok, item, jam masak di nota, jam tiba, jumlah, sisa, dibuang.
  - **Jam Helper:** datang, pulang, istirahat, upah, transport.
  - **Suhu Cooler:** pukul 18.30, 21.00, 24.00 (bulan pertama).
- **Perbarui harga bahan** di tab Bahan setiap kali nota berubah. HPP dan harga minimum ikut berubah otomatis.

---

### 9. Izin dan perjanjian (daftar periksa; bukan nasihat hukum)

| # | Apa | Yang diketahui | Halaman untuk konfirmasi | Kapan |
|---|---|---|---|---|
| 1 | **NIB lewat OSS** (gratis) | **KBLI 56304 Kedai Minuman** (titik tetap) atau **56306 Penyediaan Minuman Keliling/Tempat Tidak Tetap**. 56306 disebut tidak untuk bentuk tetap seperti kafe. Lapak ini **satu titik tetap tetapi dibongkar setiap malam**, jadi tergolong abu-abu. Tingkat risiko 56304 berbeda antarsumber. OSS memakai **KBLI 2025** untuk pendaftaran baru sejak 16 Jun 2026. Kalau menjual makanan, tambahkan KBLI makanan | [oss.go.id](https://oss.go.id) · [Unpad KBLI 2025: 56304](https://dpb.unpad.ac.id/kbli2025/56304/) · [Unpad: 56306](https://dpb.unpad.ac.id/kbli2025/56306/) · [kbli.co.id (KBLI 2025)](https://kbli.co.id/56303) · [UKM Indonesia](https://ukmindonesia.id/baca-deskripsi-posts/izin-usaha-cafe-kecil-untuk-umkm-melalui-oss-begini-ketentuannya) | Minggu ini. **Tanyakan KBLI ke PTSP Kec. Pulo Gadung.** NIB skala mikro juga dibutuhkan untuk SEHATI |
| 2 | **Sertifikat halal (SEHATI, gratis)** | **Wajib sejak 18 Okt 2026, tanpa penundaan** ([RCTI+/iNews](https://www.rctiplus.com/news/detail/inews/5490438/wajib-halal-mulai-18-oktober-2026--pemerintah-pastikan-tak-ada-penundaan)), **termasuk lapak PKL**, dan SEHATI ditujukan antara lain untuk penjual minuman ([JawaPos](https://www.jawapos.com/nasional/2510220191/wajib-halal-berlaku-pada-17-oktober-2026-pedagang-kaki-lima-tak-perlu-takut-karena-ada-layanan-sertifikasi-gratis)). Kuota SEHATI 2026: 1,35 juta. Kriteria menurut [BPJPH](https://bpjph.halal.go.id/read/ini-kriteria-pelaku-umk-yang-dapat-mengajukan-sertifikat-halal-gratis-program-sehati-2026) dan ringkasan [UKM Indonesia (15 kriteria)](https://ukmindonesia.id/baca-deskripsi-posts/15-kriteria-umk-yang-bisa-ajukan-sertifikasi-halal-gratis-di-program-sehati-2026): NIB skala mikro/kecil, bahan yang sudah dipastikan halal, satu fasilitas produksi dan satu outlet, verifikasi oleh pendamping PPH. Kategori non-warteg **maksimal 10 nama produk** ([Suara Surabaya](https://www.suarasurabaya.net/?p=836933)) | [SIHALAL ptsp.halal.go.id](https://ptsp.halal.go.id) · [BPJPH](https://bpjph.halal.go.id/read/kabar-gembira-bpjph-buka-kuota-1-35-juta-sertifikasi-halal-gratis-2026-bagi-umk) | **Segera setelah NIB.** Tanyakan ke BPJPH apakah boleh berjualan selama proses (`lapak-malam.md`) |
| 3 | **Pengantar RT/RW dan Surat Keterangan Usaha (SKU)** | Diawali pengantar RT, disahkan RW, **resminya gratis**. Dokumen yang sering diminta: **surat pernyataan tidak berjualan di badan jalan/trotoar**, pernyataan tidak mengganggu, foto lokasi, perjanjian tempat (`research/lokasi-rawamangun.md` §2d) | [Popbela](https://www.popbela.com/career/working-life/contoh-surat-keterangan-usaha-dari-desa-00-xbhyx-sgq0qz) · [Klikpajak](https://klikpajak.id/blog/cara-membuat-surat-keterangan-usaha-dari-desa/) | Setelah perjanjian tempat, sebelum malam latihan |
| 4 | **Perjanjian tertulis dengan tuan rumah** (syarat D4) | Isi minimal di bawah tabel ini | Ditandatangani pemilik sah (kalau penyewa, persetujuan pemilik) | Sebelum membeli gerobak |
| 5 | **Larangan trotoar** | Perda DKI 8/2007 Pasal 25(2); penegakan 2026 diperketat | [Hukumonline](https://www.hukumonline.com/klinik/a/sanksi-berjualan-di-fasilitas-umum-perumahan-lt51c11b74eca70/) · [Republika](https://ekonomi.republika.co.id/berita/t9viee416/pramono-tertibkan-pkl-di-trotoar-jakarta) | Setiap malam (SOP-L1) |
| 6 | **PBJT 10%** | Belum wajib selama omzet ≤Rp42 jt/bulan. Rencana 28 tamu × Rp29.000 × 17 malam ≈ Rp13,8 jt *(hitungan)*. Pengecualian ini tidak berlaku untuk penjualan insidental (bazar) | [Bapenda DKI](https://bapenda.jakarta.go.id/jenis/pajak-restoran) · [DDTC](https://news.ddtc.co.id/berita/daerah/1799846/threshold-pajak-restoran-di-dki-jakarta-naik-jadi-rp42-juta-per-bulan) | Pantau bulanan. Tanyakan apakah PBJT tuan rumah ikut menghitung omzet lapak (`research/lokasi-rawamangun.md` §5b) |
| 7 | **PPh Final 0,5%** | Orang pribadi: omzet Rp500 jt pertama per tahun tidak kena PPh (PP 20/2026) | [DJP](https://www.pajak.go.id/en/node/119950) | Tanya akuntan atau KPP |
| 8 | **Papan nama** | Papan ≤1 m² yang menempel di bangunan/area usaha dikecualikan dari pajak reklame (dengan syarat lain) | [DDTC](https://news.ddtc.co.id/berita/daerah/1820178/pasang-reklame-pengenal-usaha-tak-kena-pajak-perhatikan-aturan-ini) | Sebelum mencetak spanduk. Spanduk 3 m² mungkin kena pajak; tanya Bapenda |
| 9 | **Musik** | Usaha yang memutar musik membayar royalti LMKN (`ops-kafe.md` §6) | [izin.co.id](https://izin.co.id/blog/cara-bayar-royalti-lagu/) | **Tidak memutar musik** dari speaker. Tidak ada royalti, keluhan bising lebih kecil |
| 10 | **Keselamatan gas** | Loksem JT 23 Rawamangun terbakar karena bocor gas. Kaleng gas rusak atau terlalu panas dan pemasangan miring adalah penyebab umum ledakan kompor portabel | [Berita Jakarta: JT 23](https://m.beritajakarta.id/en/read/55212/four-loksem-jt-23-kiosks-burned-in-fire-caused-by-gas-leak) · [Popmama](https://www.popmama.com/life/home-and-living/penyebab-kompor-portable-meledak-00-8jnbb-6wqvzc) · [Berita Jakarta: tips LPG](https://m.beritajakarta.id/en/read/21588/here-are-tips-how-to-use-lpg-gas-stoves-safely) | Setiap malam: tes sabun, APAR, kaleng tidak di bawah sinar panas, satu kaleng satu kompor |
| 11 | **Ketenagakerjaan helper** | Upah ≥UMP ÷ 126 per jam; aturan kerja malam perempuan; BPJS minimal JKK + JKM | Bagian 6a | Sebelum malam latihan |

**Isi perjanjian tertulis dengan tuan rumah** (syarat D4, ditambah `research/lokasi-rawamangun.md` §5b):
1. Para pihak; **pemilik sah** (atau persetujuan tertulis pemilik kalau tuan rumah penyewa).
2. **Batas area** yang boleh dipakai (sketsa + foto). Semua di dalam persil, tidak di trotoar atau di atas saluran.
3. **Hari dan jam:** Rabu–Sabtu 17.30–00.45. Siapa membuka pagar; akses untuk helper Jumat–Sabtu.
4. **Jangka minimal 6 bulan**, dengan masa coba 1 bulan dan **pemberitahuan berhenti minimal 30 hari** [estimasi wajar].
5. **Atap atau rencana hujan:** area beratap mana yang boleh dipakai saat hujan.
6. **Toilet:** boleh dipakai founder, helper, dan tamu?
7. **Air:** boleh memakai keran untuk cuci gelas? Berapa kontribusinya?
8. **Titip gerobak dan barang** semalaman, termasuk **izin menyimpan tabung gas** atau tidak.
9. **Kompor gas portabel:** diizinkan; Lapak Yok membawa APAR.
10. (Opsional) **Titip 2 botol di kulkas toko** setiap pagi Jumat (bagian 2d).
11. **Klausul eksklusif kopi malam:** tuan rumah tidak menyewakan teras malam ke penjual kopi lain selama perjanjian.
12. **Biaya:** sewa tetap per bulan atau bagi hasil %, tanggal bayar, kuitansi.
13. **Kebersihan, sampah, dan air limbah:** dibuang ke mana; standar bersih setelah tutup.
14. **Kerusakan dan kehilangan:** siapa menanggung.
15. **Kebisingan dan parkir motor:** area parkir; jam tenang.
16. **PBJT:** apakah usaha tuan rumah terdaftar PBJT, dan apakah omzet lapak terpisah.

---

### 10. Daftar risiko (10 yang paling mungkin)

| # | Risiko | Kemungkinan | Dampak | Tanda awal | Rencana: cegah / saat terjadi |
|---|---|:-:|:-:|---|---|
| 1 | **Hujan** (uji jatuh di puncak hujan Des–Feb) | **Tinggi** | Sedang–Tinggi (malam sepi, alat basah) | Prakiraan BMKG, langit gelap pukul 16.00 | **Cegah:** teras beratap (D4), tirai samping, kursi plastik tahan air, makanan titip dikurangi saat hujan. **Saat terjadi:** SOP-L7; tutup kalau angin/petir; malam hujan dicatat terpisah (D9) |
| 2 | **Tuan rumah menarik izin** | Sedang | **Tinggi** (lapak berhenti, gerobak harus pindah) | Tuan rumah mengeluh soal sampah, bising, atau "ada yang mau sewa" | **Cegah:** perjanjian 6 bulan + pemberitahuan 30 hari + klausul eksklusif; foto tempat bersih setiap malam; bayar tepat waktu; jaga hubungan dengan tetangga. **Saat terjadi:** simpan 2 calon titik cadangan dari survei; gerobak beroda mudah dipindah; umumkan pindah di IG/WA |
| 3 | **Satpol PP / penertiban** | Sedang (kalau barang meluber ke trotoar); Rendah (kalau di dalam persil) | Tinggi (barang disita ke Cakung) | Spanduk larangan PKL, patroli di ruas itu | **Cegah:** batas persil ditandai lakban; map dokumen; SKU dan pernyataan tidak di trotoar. **Saat terjadi:** SOP-L8; jangan bayar "uang damai"; klarifikasi ke kelurahan besoknya |
| 4 | **Gas bocor atau kebakaran** | Rendah | **Sangat tinggi** (cedera, kerusakan, kehilangan tempat) | Bau gas, api kuning/tidak stabil, selang retak | **Cegah:** regulator dan selang SNI, tes sabun setiap malam, APAR 3 kg di samping kompor, kompor jauh dari kursi dan tudung saji, tabung tegak dan teduh, **satu orang terlatih APAR di setiap malam**. **Saat terjadi:** tutup katup tabung, jauhkan tamu, APAR (tarik pin, arahkan ke pangkal api), telepon 112 / Damkar |
| 5 | **Founder sakit atau lembur di kantor** | **Tinggi** (±87 jam/minggu) | Tinggi (malam batal; Rabu–Kamis tanpa pengganti) | Kurang tidur berturut-turut, lembur kantor diumumkan sore | **Cegah:** aturan pengaman 6c; helper cadangan belajar V60 dasar bulan 2. **Saat terjadi:** lembur → buka 19.30 atau tutup, umumkan sebelum 17.00; sakit → tutup (lebih baik dari kualitas buruk). Jumat–Sabtu, helper boleh buka dengan menu tubruk, es kopi susu, dan makanan saja kalau sudah terlatih |
| 6 | **Helper tidak datang** | Sedang | Sedang–Tinggi (Jumat–Sabtu ramai sendirian) | Telat membalas WA, sering izin | **Cegah:** konfirmasi WA Kamis malam; 2 helper cadangan yang sudah ikut malam latihan; upah dibayar tepat waktu. **Saat terjadi:** panggil cadangan; kalau tidak ada, buka 19.00 dengan menu solo (D2), tanpa roti bakar, sate, dan Sesi Bareng |
| 7 | **Barang dicuri** dari gerobak atau saat ramai | Sedang | Sedang (grinder dan kas paling mahal) | Gembok rusak, orang asing mengamati | **Cegah:** grinder, timbangan, kas, dan HP selalu dibawa pulang; gerobak dikunci dengan rantai; minta tuan rumah menyimpan di dalam toko; QRIS mengurangi tunai. **Saat terjadi:** lapor RT dan Polsek; daftar alat dengan foto dan harga di Sheets |
| 8 | **Es habis** | Sedang | Sedang (es kopi susu, produk utama, berhenti) | Es <2 kg pukul 21.00 di malam ramai | **Cegah:** pesan 15 kg Jumat–Sabtu; es minum dan es pendingin dipisah; cooler tertutup rapat dan teduh; catat sisa es di Log Malam. **Saat terjadi:** pesan ulang kurir (maks. 20 kg per pesanan), tawarkan V60 atau tubruk, jujur ke tamu |
| 9 | **Tetangga mengeluh bising, parkir, atau sampah** | Sedang | Tinggi (bisa berujung izin ditarik) | Wajah tidak ramah, teguran lisan, kabar dari RT | **Cegah:** tanpa speaker; ukur dB di batas persil; parkir motor yang disepakati; tidak ada sampah di trotoar; perkenalan ke tetangga sebelum buka. **Saat terjadi:** SOP-L8; keluhan berulang → last order 23.00 atau pindah |
| 10 | **Bulan pertama sepi** (ramp CFO mulai 10 tamu/malam, ditambah hujan) | **Tinggi** | Tinggi (kas, semangat founder) | Rata-rata 7 hari di bawah ramp 2 minggu berturut-turut | **Cegah:** malam latihan dengan teman, Ajak Teman 2 minggu (offer v3), reservasi grup, satu malam ritual (board). **Saat terjadi:** kurangi pesanan makanan titip (waste), **jangan memotong waktu seduh atau helper** (keselamatan), jangan menambah malam; perbaiki offer sebelum menurunkan harga (D10); baca hasil di review 2 Feb |

**Pertanyaan terbuka** (hanya jawaban nyata yang bisa menutupnya):
1. Waktu tempuh nyata kantor → titik pukul 17.30, dan apakah kantor punya kulkas.
2. Model grinder dan kettle founder: waktu giling 15 g; kettle bisa di kompor atau tidak?
3. Tuan rumah: atap, toilet, keran, kulkas, izin menyimpan tabung gas, akses helper, biaya.
4. Pemasok nasi kucing, gorengan, dan sate yang **punya sertifikat halal**, harga titip vs beli putus, kesanggupan antar 17.45/18.30 dengan jam masak di nota.
5. Ongkir kurir es ke titik; agen es terdekat.
6. Harga tabung Bright Gas 5,5 kg perdana saat ini (angka Rp326.000 tanggalnya tidak jelas).
7. KBLI 56304 vs 56306 (PTSP Kec. Pulo Gadung); kelayakan SEHATI untuk lapak; boleh berjualan selama sertifikat diproses (BPJPH).
8. Iuran warga atau kebersihan dan aturan jam dari RT/RW; sensitivitas tetangga terhadap obrolan sampai 24.00.
9. Pelatihan penjamah pangan gratis atau murah di Sudinkes Jakarta Timur atau puskesmas.
10. Jenis kelamin dan domisili calon helper (menentukan biaya antar-jemput).
11. Ukur di malam latihan: waktu pasang, waktu giling, V60 dan es kopi susu per jam, suhu cooler pukul 18.30/21.00/24.00, sisa es, galon dan gas per malam, dB di batas persil.

---

### 11. Perubahan angka untuk CFO

Saya **tidak** mengubah `numbers.json`. Pembanding di bawah memakai `numbers.json` versi **offer v3** (diperbarui 06.12, belanja Rp29.000/tamu, kontribusi Rp13.768). CFO perlu menjalankan ulang alat dengan perubahan ini.

#### A. Angka yang sebaiknya diubah atau ditambahkan

| # | Item | Lama | Baru | Sumber |
|---|---|---:|---:|---|
| 1 | **Helper Jumat–Sabtu** (biaya tetap) | Rp1.970.000 (5 jam, 18.00–23.00) | **Rp2.675.000** (6,75 jam 17.30–00.15 × 8,67 malam × Rp45.475 = Rp2.660.300, + BPJS JKK/JKM ±Rp14.400 [estimasi]). **+Rp0,3–0,39 jt** kalau helper perempuan (antar-jemput + makan, [estimasi]) | UMP ([Katadata](https://katadata.co.id/amp/berita/industri/694bb57d97fa5/ump-jakarta-2026-resmi-naik-jadi-rp-5-72-juta/)) ÷ 126 ([Bisnis.com](https://ekonomi.bisnis.com/read/20210302/12/1362701/kemenaker-tegaskan-upah-per-jam-hanya-untuk-pekerja-paruh-waktu)); jam dari `lapak-malam.md` ("helper menyiapkan dari 17.30"); UU 13/2003 Ps. 76 ([Hukumonline](https://www.hukumonline.com/klinik/a/aturan-lembur-untuk-pekerja-perempuan-lt50eb906629072)) |
| 2 | **Gas** (biaya tetap) | Rp250.000 (LPG kettle) | **Rp400.000** [estimasi]: LPG 5,5 kg 1–1,5 isi ulang/bulan × Rp102.000 + gas kaleng kompor kedua ±1 kaleng per malam Jumat–Sabtu × Rp23.500–25.300 | [Bisnis.com: Bright Gas Rp102.000](https://ekonomi.bisnis.com/read/20260815/44/1996598/pertamina-turunkan-harga-bright-gas-ini-rinciannya) · [Tokopedia: gas kaleng](https://www.tokopedia.com/find/gas-kaleng-portable). Jumlah pemakaian [estimasi], ganti setelah 4 minggu data |
| 3 | **Es untuk cooler + ongkir** (biaya tetap baru) | Tidak ada (es minum sudah di HPP) | **Rp450.000** [estimasi]: es pendingin ±6 kg × Rp1.990/kg × 17 malam ≈ Rp203.000 + ongkir kurir ±Rp15.000 × 17 ≈ Rp255.000 (tarif ongkir belum dicari). Turun ke ±Rp200.000 kalau es dibeli sendiri di jalan | [Tokopedia CoolFresh Rp9.950/5 kg](https://www.tokopedia.com/espugautama/es-batu-kristal-jakarta-timur-100-halal-5kg) |
| 4 | **Air galon untuk seduh dan minum** (biaya tetap baru) | Tidak ada (HPP V60 memakai air RO Rp200) | **Rp250.000** [estimasi]: ±12 L/malam ≈ 0,63 galon × Rp17.000–24.000 × 17 malam ≈ Rp183–257 rb. **Rp0 tambahan** untuk air cuci kalau keran tuan rumah masuk perjanjian | [harga.web.id](https://harga.web.id/harga-produk-aqua-galon-19-liter-dan-refill.info) · [CNBC Indonesia](https://www.cnbcindonesia.com/news/20260428151251-4-730609/jangan-kaget-harga-air-galon-tiba-tiba-naik-rp1000-ada-apa/amp) |
| 5 | **Angkut/titip alat** (biaya tetap) | Rp400.000 [estimasi] | **Rp0**, **hanya jika** titip gerobak tertulis di perjanjian (syarat D4). Kalau tidak, tetap Rp400.000 | Bagian 2a, 9 |
| 6 | **Kapasitas per malam** | 37 | **30** [estimasi]. Rentang 27–35, tergantung lama duduk 2,5–3 jam dan 15–16 kursi | Hitungan bagian 3d; lama duduk dari `offer.md` dan `launch-kafe.md` |
| 7 | **Tenda lipat 3×3** (startup) | Rp2.250.000 | **Rp0** (teras beratap). Kalau tidak beratap: Rp741.000–1.620.000 | [Tokopedia: tenda 3x3](https://www.tokopedia.com/find/tenda-3x3) · [tenda jualan 3x3](https://www.tokopedia.com/find/tenda-jualan-3x3-full-set) |
| 8 | **Bangku, meja, tikar** (startup) | Rp2.300.000 | **Rp2.134.000** (16 kursi bersandaran × Rp95.000 + 4 meja × Rp153.500; tikar dihapus) | [Tokopedia: kursi napolly](https://www.tokopedia.com/find/kursi-plastik-napoli-original) · [meja napolly](https://www.tokopedia.com/find/meja-plastik-napolly); offer v3 |
| 9 | **Cooler** (startup) | Rp1.000.000 | **Rp1.745.000** (Soleil 45 L Rp899.900 + Marina 16 L Rp538.110 + cooler bag dan gel Rp304.600) | [Ruparupa](https://www.ruparupa.com/soleil-45-ltr-cooler-box-biru-muda.html) · [Tokopedia Marina](https://www.tokopedia.com/lionstarindonesia/lion-star-kotak-pendingin-marina-cooler-box-18s-16-liter-i-17-1730862486830941300) · [ice pack](https://www.tokopedia.com/find/ice-pack-gel-tahan-lama) |
| 10 | **Kompor + tabung** (startup) | Rp600.000 | **Rp950.000** (Rinnai 1 tungku Rp245.000 + regulator SNI Rp208.000 + Bright Gas 5,5 kg perdana Rp326.000 + Hi-Cook + 2 kaleng Rp170.600) | [Tokopedia Rinnai](https://www.tokopedia.com/find/rinnai-1-tungku) · [regulator](https://www.tokopedia.com/find/selang-regulator-gas-3kg) · [ESDM Migas](https://migas.esdm.go.id/post/dirjen-migas-hadiri-peluncuran-bright-gas-5,5-kg) · [Viva](https://techno.viva.co.id/elektronik/14809-suka-camping-ini-5-pilihan-kompor-portable-murah-terbaik-2025) |
| 11 | **APAR** (startup) | Rp300.000 | **Rp390.000** (powder 3 kg, batas atas) | [Tokopedia](https://www.tokopedia.com/find/apar-3kg-dry-powder) |
| 12 | **Banner dan papan nama** (startup) | Rp700.000 | **Rp300.000** (X-banner Rp65.000 + spanduk 3 m² Rp84.000 + kartu meja/menu [estimasi]) | [Tokopedia X-banner](https://www.tokopedia.com/gamblangmediapromo/x-banner-60x160-korcin-440-free-desain-murah-dan-berkualitas-flexi-280) · [spanduk](https://www.tokopedia.com/gamblangmediapromo/cetak-spanduk-print-banner-baliho-online-murah-flexy-korcin-440) |
| 13 | **Peralatan air dan cuci** (startup baru) | Tidak ada | **Rp510.000** (2 jerigen 20 L, jerigen keran, 3 baskom, galon kosong) | Bagian 4b, #23–26 |
| 14 | **Ceret, termos, termometer** (startup baru) | Tidak ada | **Rp443.000** | Bagian 4b, #12–14 |
| 15 | **Wajan roti bakar + tudung saji** (startup baru) | Tidak ada | **Rp390.000** | Bagian 4b, #15–16 |
| 16 | **Container box 2 × 100 L** (startup baru) | Tidak ada | **Rp402.000** | Bagian 4b, #27 |
| 17 | **Sampah + wadah cold brew** (startup baru) | Tidak ada | **Rp242.000** (Rp142.000 + Rp99.900) | Bagian 4b, #28–29 |
| 18 | **Barang kecil** (startup baru) | Tidak ada | **Rp500.000 [estimasi]** (gembok, nampan, saringan, botol, lap, sabun, sanitizer, P3K; harga belum dicari) | – |
| 19 | **Gaji 2 malam latihan helper** (startup baru) | Tidak ada | **Rp614.000** (2 × 6,75 jam × Rp45.475) *(hitungan)* | Bagian 6a |
| 20 | **Kettle leher angsa versi kompor** (startup, bersyarat) | Rp0 (alat seduh dimiliki) | **Rp0–522.500**: hanya kalau kettle founder listrik | [Tokopedia: ketel leher angsa](https://www.tokopedia.com/find/ketel-leher-angsa) |

**Total:**
- Biaya tetap: **Rp4.828.250 → ±Rp5.983.250/bulan** (+Rp1,16 jt; dengan titip gerobak sehingga angkut Rp0).
- Startup alat: **Rp11,75 jt → ±Rp12,61 jt**. Total startup **Rp19,55 jt → ±Rp21,0 jt** (termasuk gaji latihan Rp614 rb).

#### B. Dampaknya (alat CFO, dijalankan pada salinan di scratchpad, bukan pada `numbers.json`)

| Skenario | Biaya tetap/bulan | Break-even/malam | Margin di 28 tamu | Tahun 1 (operasional) | Kas dibutuhkan |
|---|---:|---:|---:|---:|---:|
| `numbers.json` sekarang | Rp4,83 jt | 20,6 | +12,5% | +Rp2,2 jt | Rp25,7 jt |
| **Semua usulan A** (titip gerobak, angkut Rp0) | Rp5,98 jt | **25,6** | +4,1% | **−Rp11,6 jt** | Rp33,6 jt |
| A tanpa titip gerobak (angkut Rp400 rb) | Rp6,38 jt | 27,3 | +1,2% | −Rp16,4 jt | Rp37,2 jt |
| A + helper perempuan (antar-jemput + makan) | Rp6,37 jt | 27,2 | +1,3% | −Rp16,3 jt | Rp37,1 jt |
| A, helper hanya 18.00–23.30 (5,5 jam; founder memasang dan membongkar sendiri) | Rp5,49 jt | 23,4 | +7,7% | −Rp5,7 jt | Rp30,2 jt |
| A, air cuci dari keran tuan rumah, galon dimasukkan sewa, es dibeli sendiri | Rp5,48 jt | 23,4 | +7,8% | −Rp5,6 jt | Rp30,1 jt |
| **A + dua penghematan di atas** | Rp4,99 jt | **21,3** | +11,3% | +Rp0,3 jt | Rp27,3 jt |

Startup di semua baris skenario A: Rp20,4 jt (belum termasuk gaji latihan Rp614 rb).

**Cara membacanya:**
- Biaya menjalankan lapak tanpa listrik (es, air, gas dua kompor, jam helper yang sebenarnya) **menaikkan break-even sekitar 5 tamu/malam**, ke ±26, dari kapasitas realistis ±30.
- Dua tuas ops mengembalikannya ke ±21, **tanpa menyentuh harga** (board D10):
  1. jam helper dipendekkan ke 18.00–23.30, artinya founder memasang Jumat sendirian;
  2. air dan es diurus lewat tuan rumah dan belanja sendiri.
- Tuas ketiga ada di offer: setiap +Rp3.000 belanja per tamu menurunkan break-even 4–6 tamu (`pricing.md`).
- Hasil alat bergantung pada estimasi es, galon, dan gas. **Ganti dengan angka Log Malam setelah 4 minggu.**

#### C. Diperiksa dan tidak perlu diubah sekarang

| Item | Angka sekarang | Temuan | Keputusan |
|---|---|---|---|
| HPP makanan ±62% | Rp4.190/tamu | Konsisten dengan titip ±70–80% di malam solo dan roti bakar sendiri ±44–53% di Jumat–Sabtu (bagian 5b) | Tetap. Uji sensitivitas "semua titip" sudah ada di `offer.md` |
| Cicip + garansi | Rp250/tamu | Malam solo hanya cium bubuk (hampir tanpa biaya). Teko cicip Jumat–Sabtu 2 × (10 g × Rp400 + filter Rp850) ≈ Rp9.700/malam ≈ Rp84 rb/bulan *(hitungan)*, setara ±Rp175/tamu di 28 tamu × 17 malam | Tetap |
| Es minum di HPP es kopi susu | Termasuk di Rp7.900 | 150 g × Rp1,99 ≈ Rp299 (`ops-kafe.md` §5) | Tetap. Es pendingin ditambahkan terpisah (A3) |
| Qasir Pro | Rp58.250/bulan | Versi dasar gratis bisa dipakai 8 minggu pertama | Tetap (konservatif); boleh Rp0 sampai review |
| Lampu, gelas, gerobak | Rp600 rb, Rp1 jt, Rp3 jt | Harga nyata Rp581 rb, Rp934 rb, Rp2,0–3,5 jt + ongkir | Tetap |
| QRIS | 0% | 0% untuk ≤Rp100.000; usaha mikro 0% sampai Rp500.000 sejak 1 Okt 2026 ([BI](https://www.bi.go.id/id/publikasi/ruang-media/cerita-bi/Pages/mdr-qris.aspx)) | Tetap |
| Iuran warga | Rp150.000 | Tidak ada tarif resmi untuk lahan privat; bayar hanya dengan kuitansi (`research/lokasi-rawamangun.md` §2d) | Tetap |

**Langkah berikutnya:** CFO menjalankan ulang `numbers.json` dengan bagian A, lalu `/founder-launch` memakai malam latihan 30 Nov–8 Des untuk mengukur angka [estimasi] di dokumen ini (daftar ukur di bagian 10).

## Launch plan

> Format lapak malam. Rencana launch kafe ada di [launch-kafe.md](launch-kafe.md). Hari ini Minggu 8 November 2026. Pemilik tugas default adalah **Founder**, karena kamu menjalankan sendiri. **KP** = jalur kritis: jika terlambat, malam pertama ikut mundur. Angka dari [cfo.md](cfo.md), operasi dari [ops.md](ops.md), kalender konten dari [marketing.md](marketing.md), dan nama serta tampilan dari [brand.md](brand.md).

### Langkah 1: ujinya adalah lapak itu sendiri

Di format ruko, uji pop-up dibutuhkan sebelum mempertaruhkan Rp300 juta lebih. **Di format lapak, total kas yang dipertaruhkan sekitar Rp28–34 juta, jadi delapan minggu pertama adalah ujinya.** Panel simulasi untuk pitch lapak: 10/20 beli, sekitar 35% tanpa pemburu promo. Itu batas atas. **Jika pembeli nyata jauh di bawahnya, percayai pembeli nyata**, lalu kembali ke `offer.md` atau `pricing.md`.

#### Garis sukses, ditulis sekarang (syarat board D9, tidak boleh diturunkan)

Diukur dari rata-rata **minggu 6–8** (13–30 Jan 2027), dengan malam hujan dicatat terpisah:

| Ukuran | GO | UBAH | STOP |
|---|---|---|---|
| Tamu bayar per malam (bukan hujan) | **≥26** (break-even biaya nyata), atau ≥22 jika penghematan tuan rumah (air, galon, titip gerobak) sudah tertulis dan tercatat | 15–25 | <15 |
| Belanja per tamu | **≥Rp29.000**, target Rp32.000 | Rp25.000–28.999 | <Rp25.000 |
| Kembali dalam 14 hari | ≥25% | 15–24% | <15% |
| Datang karena diajak teman | ≥30% | 15–29% | – |
| Pelanggan tetap (≥2 kunjungan dalam 30 hari) | ≥40 orang | 20–39 | – |
| Malam solo: tamu menunggu minuman pertama >10 menit | ≤20% | >20% → tambah helper Kamis atau tutup Kamis | – |
| Komunitas | Ada satu malam ritual tetap dan satu kelompok yang kumpul rutin | – | – |

**GO** = semua baris GO. **STOP** = salah satu baris STOP, atau tuan rumah menarik izin dan tidak ada tempat pengganti dalam 2 minggu. Selain itu, **UBAH**: perbaiki offer, titik, atau jam, lalu ukur 4 minggu lagi. **Jangan pindah ke kios dan jangan membuka Jogja** sebelum GO dan 3 bulan untung berturut-turut (D11).

### Langkah 2: hitung mundur

#### Minggu 1 · Sen 9 – Min 15 Nov · Nama, titik, izin awal

| Tugas | Pemilik | Tenggat | |
|---|---|---|:-:|
| Cek "Lapak Yok" dan "Yok Leyeh" di [PDKI](https://pdki-indonesia.dgip.go.id) kelas 43 dan 30; simpan tangkapan layar. Cek handle IG/TikTok | Founder | Sel 10 Nov | **KP** |
| Survei malam Jl. Balai Pustaka dan Jl. Pemuda (Rabu–Sabtu, 19.00–22.00). Hitung orang lewat dan duduk, dan petakan pesaing malam per titik, termasuk verifikasi lokasi YO'KOPI (D5) | Founder | Sab 14 Nov | **KP** |
| Bicara dengan 4–6 calon tuan rumah: teras beratap, air dan toilet, titip gerobak dan konsentrat di kulkas, jangka minimal 6 bulan, eksklusif kopi malam (D4) | Founder | Min 15 Nov | **KP** |
| Daftar NIB di OSS (KBLI 56304 atau 56306; konfirmasi ke PTSP Kec. Pulo Gadung) | Founder | Sab 14 Nov | |
| Buat akun SIHALAL dan minta pendamping P3H untuk *self-declare*. **Tanyakan ke BPJPH apakah boleh berjualan selama sertifikat diproses** | Founder | Jum 13 Nov | **KP** |
| Cek kontrak kerja kantor: ada klausul usaha sampingan? | Founder | Jum 13 Nov | |

#### Minggu 2 · Sen 16 – Min 22 Nov · Kunci tempat dan orang

| Tugas | Pemilik | Tenggat | |
|---|---|---|:-:|
| **Tanda tangani perjanjian tertulis dengan tuan rumah** (semua butir D4) | Founder + tuan rumah | Min 22 Nov | **KP** |
| Lapor RT/RW, minta pengantar Surat Keterangan Usaha, dan surat pernyataan tidak memakai trotoar | Founder | Sab 21 Nov | |
| Pesan alat (`ops.md` §4): gerobak, 16 kursi bersandaran, 4 meja, cooler, kompor + regulator SNI, APAR, jerigen, container box | Founder | Sen 16 Nov | |
| Rekrut helper Jumat–Sabtu (mahasiswa UNJ?), upah per jam legal sekitar Rp45.475 | Founder | Min 22 Nov | **KP** |
| Pilih roaster yang mencantumkan tanggal sangrai, dan dua mitra makanan siap saji (nasi kucing, gorengan, kue) | Founder | Jum 20 Nov | |

#### Minggu 3 · Sen 23 – Min 29 Nov · Merek, uji di rumah, konten mulai

| Tugas | Pemilik | Tenggat | |
|---|---|---|:-:|
| **Ajukan merek kelas 43** lewat Konsultan KI (kata + logo jika disarankan) | Founder + Konsultan KI | Sel 24 Nov | **KP** |
| Post pertama IG (H-14, sesuai `marketing.md`) | Founder | Rab 25 Nov | |
| Uji di rumah dengan stopwatch: konsentrat cold brew, base es kopi susu (≤30 detik/gelas), V60 sendirian, pemasangan lapak ≤30 menit | Founder | Sab 28 Nov | |
| Cetak spanduk, kartu meja "HP boleh, laptop tidak", kartu beans, dan Kartu Cap Yok (`brand.md`) | Founder | Sab 28 Nov | |
| Siapkan Google Sheets "Log Malam": tamu, belanja, lama duduk, waktu tunggu, hujan, es/galon/gas terpakai | Founder | Min 29 Nov | |

#### Minggu 4 · Sen 30 Nov – Min 6 Des · Malam latihan

| Tugas | Pemilik | Tenggat | |
|---|---|---|:-:|
| **Latihan 1 (Kamis 3 Des, solo):** undang 8–10 teman. Ukur: sapa ≤10 detik, minuman di tangan ≤5 menit, waktu tunggu V60 disebut sebelum bayar (D3) | Founder | Kam 3 Des | **KP** |
| **Latihan 2 (Sabtu 5 Des, dengan helper):** undang 15–20 orang. Uji paket, Sesi Bareng, bongkar-pasang, dan cuci 3 baskom | Founder + helper | Sab 5 Des | |
| Status halal jelas, atau ada jawaban tertulis BPJPH soal berjualan selama proses | Founder | Min 6 Des | **KP** |

#### Minggu 5 · Malam pertama

- **Rabu 9 Des 2026:** malam pertama, *soft* (undangan lewat daftar WhatsApp), menu solo.
- **Jumat 11 Des:** malam publik pertama dengan helper, ditandai post "buka" di IG.

### Langkah 3: run sheet Rabu 9 Desember 2026 (malam solo)

| Jam | Apa | Catatan |
|---|---|---|
| Pagi | Konsentrat dan base dititip di kulkas tuan rumah (`ops.md` §2d) | Kalau tidak ada kulkas: bawa cooler bag + es gel |
| 17.30 | Pulang kantor, langsung ke lapak. Beli es di jalan | Kalau lembur, post di IG: "Malam ini buka 20.00." Jangan diam-diam terlambat |
| 18.45–19.15 | Pasang: kursi, lampu, gas, air panas, papan menu, Kartu Cap | **Jangan menerima tamu sebelum siap** (D2) |
| 19.00/19.30 | Buka | Jam yang ditulis di papan dan IG harus sama dengan jam nyata |
| 19.30–22.00 | Puncak. Es kopi susu didahulukan dari antrean V60, dan waktu tunggu V60 disebut sebelum bayar | Catat waktu tunggu setiap tamu ke-5 |
| 23.30 | Last order | |
| 24.00 | Tutup. Hitung kas dan QRIS, isi Log Malam, bongkar, titip gerobak | |
| Kalau ada masalah | Hujan, gas, warga mengeluh, Satpol PP: ikuti SOP di `ops.md` §7. **APAR selalu di tempat** | |

### Langkah 4: 30 hari pertama dan review

**Angka mingguan** (dari `marketing.md` dan `cfo.md`):
1. Tamu bayar per malam. Target ≥10 di minggu 1–2, naik ke ≥26 di minggu 6–8.
2. Belanja per tamu. Target ≥Rp29.000, menuju Rp32.000.
3. Tamu baru per minggu.
4. % kembali dalam 14 hari.
5. % datang karena diajak teman.

**Batas jam kerja founder:** jika dua minggu berturut-turut kamu tidur kurang dari 6 jam atau pekerjaan kantor terganggu, **tutup Rabu**. Jangan menambah malam. `ops.md` memperkirakan jam kerjamu sekitar 85–90 jam/minggu.

| Review | Tanggal | Pertanyaan |
|---|---|---|
| Hari 7 | Rab 16 Des | Pemasangan tetap ≤30 menit? Ada malam solo dengan tunggu >10 menit? Tuan rumah dan warga nyaman? |
| Hari 14 | Rab 23 Des | Belanja per tamu sudah ≥Rp29.000? Paket mana yang laku? Ada yang kembali? |
| Hari 30 | Jum 8 Jan 2027 | Angka es, galon, dan gas nyata. Jalankan ulang `cfo.md` dengan data Log Malam |
| **Review 8 minggu** | **Sel 2 Feb 2027** | Tabel GO/UBAH/STOP di atas |

**Libur:**
- **24–25 Des dan 31 Des–1 Jan:** putuskan sebelum 15 Des apakah buka. Malam libur tidak dihitung dalam rata-rata review.
- **Ramadan (±8 Feb–9 Mar 2027):** uji 2 minggu dengan jam buka setelah tarawih.
- **Idul Fitri (±10–11 Mar):** libur 1–2 minggu.

### Pertanyaan terbuka yang bisa memindahkan tanggal

1. Tuan rumah dengan teras beratap, air, dan tempat titip gerobak.
2. Status halal *self-declare*, dan apakah boleh berjualan selama proses.
3. Hasil PDKI untuk nama.
4. Helper Jumat–Sabtu.
5. Jarak kantormu ke Rawamangun, yang menentukan jam buka Rabu–Kamis.

_The panel is simulated buyers and the numbers are projections from your inputs. Confirm demand with real customers and costs with real quotes before you spend. Not financial, legal or tax advice._
