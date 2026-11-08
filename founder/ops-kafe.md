# Operasional: Kopiyo (Rawamangun, Jakarta Timur)

> **Cara membaca dokumen ini**
> - Disusun 8 Nov 2026 untuk founder, CFO, dan `/founder-launch`. Semua angka dalam Rupiah.
> - Harga sewa, UMP, BPJS, beans, susu, cup, filter, peralatan, QRIS, POS, listrik, PBJT, PPh, dan izin dasar diambil dari [research/cost-inputs.md](research/cost-inputs.md). Riset itu tidak saya ulang.
> - Fakta baru (roaster, titip jual, SLHS, halal, BPJS, royalti musik, kerja malam, paruh waktu, pop-up, asuransi) dari **cuplikan hasil pencarian (WebSearch) tanggal 8 Nov 2026**. Halaman sumbernya tidak saya buka langsung (WebFetch sudah diblokir di sesi riset biaya, jadi tidak saya coba lagi). Harga dan aturan bisa sudah berubah. **Cek ulang tautannya sebelum dipakai untuk keputusan.**
> - **[estimasi]** = perkiraan saya, bukan fakta. *(hitungan)* = hitungan saya dari angka bersumber.
> - **Bukan nasihat hukum atau pajak.** Aturan berbeda per tempat dan sering berubah. Setiap izin, pajak, dan aturan ketenagakerjaan di bawah harus dikonfirmasi founder ke instansinya (OSS, Bapenda DKI, Sudinkes Jakarta Timur, BPJPH, BPJS, PLN, LMKN) atau ke konsultan/akuntan.
> - Saya tidak mengubah `numbers.json`. Angka yang perlu diubah ada di bagian terakhir, **"Perubahan angka untuk CFO"**.

## Ringkasan

- **Orang di jam 19.00–22.00: 3 orang pada volume rencana (60 tamu/hari).** Dua orang cukup selama rata-rata harian di bawah sekitar 40 tamu, yaitu bulan 1–4 menurut ramp CFO. Hitungannya ada di bagian 3.
- **Rencana dasar 3 staf hanya cukup sampai bulan 4.** Tiga staf bekerja 5 hari × 8 jam, sehingga hanya ada 2 orang per hari ditambah 1 shift ekstra per minggu. Mulai bulan 5, perlu tenaga paruh waktu di jam ramai (±Rp2,4 juta/bulan) atau founder ikut di bar.
- **Biaya baru yang belum ada di `numbers.json`:**
  - royalti musik LMKN (±Rp300 ribu/bulan);
  - paruh waktu jam ramai (bulan 5 dst.);
  - gaji pelatihan sebelum buka (±Rp10,2 juta, sekali);
  - makan staf dan antar-jemput untuk pekerja perempuan yang pulang lewat pukul 23.00 (wajib menurut UU Ketenagakerjaan, besarannya [estimasi]).
  - Cicip Dulu lebih tepat dimodelkan sebagai biaya harian tetap (±Rp0,87 juta/bulan).
- **Risiko margin terbesar yang ditemukan ops: makanan titip jual.** Kalau semua makanan dititip UMKM dan Kopiyo hanya mengambil sekitar 30%, HPP makanan menjadi ±70%, bukan 38%. Break-even kasar naik dari 56 ke ±67 tamu/hari. **Saran:** roti bakar, pisang goreng, dan mie dibuat sendiri. Rice bowl saja yang dititip.
- **Tiga izin paling penting:**
  1. NIB lewat OSS (KBLI rumah minum/kafe), lalu SLHS dari Dinas Kesehatan;
  2. sertifikat halal, yang **sudah wajib sejak 18 Okt 2026**; jalur gratis *self-declare* kemungkinan tidak berlaku untuk kedai;
  3. pendaftaran PBJT 10% di Bapenda DKI begitu omzet mendekati Rp42 juta/bulan.
- **Tiga risiko teratas:**
  1. janji "3 menit" gagal di jam 19.00;
  2. barista utama keluar;
  3. bulan sepi lebih lama dari ramp.
- **Syarat board yang dijawab di sini:**
  - C1: MoodBrew dibekukan; pakai POS siap pakai dan Google Sheets HPP (bagian 5).
  - C9: naskah "lima menit pertama" (SOP-02) dan cara menolak laptop (SOP-06).
  - C10: peran dan rekrutmen tim (bagian 3). Nama barista dan pengalaman F&B founder masih harus diisi founder.

---

## 1. Siklus harian

Buka setiap hari **16.00–24.00**. Persiapan mulai ±15.00 (bisa 14.00 di hari terima barang besar). Tutup selesai ±00.45.

Kolom "Tamu lihat?" menandai langkah yang dilihat atau dirasakan tamu.

| Jam | Langkah | Siapa | Tamu lihat? |
|---|---|---|:-:|
| 14.00–15.00 | *(Hanya Selasa & Jumat, hari terima barang besar.)* Terima biji kopi, susu karton, gula aren, filter. Cek tanggal sangrai, jumlah, label halal, dan kedaluwarsa. Lihat SOP-09. | Founder, atau shift P maju 1 jam (lembur) | Tidak |
| 15.00 | Shift P datang. Buka kunci, nyalakan listrik bar, cek suhu chiller dan catat di log. Saring konsentrat cold brew yang diseduh semalam, timbang hasilnya, beri label tanggal dan jam. | P | Tidak |
| 15.00–15.40 | *Dial-in* 3 beans aktif: seduh V60 sesuai resep (SOP-04), cicipi, sesuaikan gilingan. Isi kartu beans di meja. | P (barista) | Tidak |
| 15.30 | Es batu datang (10 kg/hari). Rice bowl titip datang: hitung, cek suhu, label halal, dan tanggal produksi, lalu tanda tangani nota titip. | P | Tidak |
| 15.45 | Shift T datang. Atur meja dan kartu "Dipesan" sesuai reservasi WhatsApp. Pasang papan "HP boleh, laptop tidak". Atur musik setara suara ngobrol dan lampu. | T | Ya (suasana) |
| 15.55 | Seduh "teko cicip" pertama (3 beans, SOP-04). Briefing 5 menit: menu yang habis, beans aktif, reservasi malam ini, target malam. | P + T | Tidak |
| **16.00** | **Buka pintu.** | – | **Ya** |
| 16.00–18.30 | Layanan sore, biasanya sepi. Sambil melayani: iris roti, siapkan pisang, isi ulang botol susu dan gula aren, cuci server. | P + T | Ya |
| 18.00–19.00 | Istirahat bergiliran: P 18.00–18.30, T 18.30–19.00. | – | Tidak |
| 18.30 | **Siapkan jalur cepat untuk jam ramai:** campur "base kopi susu" (konsentrat + susu + gula aren) di botol 1 L berlabel jam. Seduh teko cicip kedua pukul 19.00. | P | Tidak |
| **19.00–22.00** | **Jam ramai.** Tidak ada istirahat kecuali bergilir. Prioritas: (1) sapa tamu baru dalam 10 detik, (2) es kopi susu ≤3 menit, (3) V60, (4) makanan, (5) bereskan meja. | Semua | **Ya** |
| Kamis 19.30–20.00 | "Kamis Seduh Bareng": acara gratis 30 menit, dipandu barista. | Barista utama/founder | Ya |
| 22.00–23.00 | Layanan malam. Istirahat P 22.00–22.30, T 22.30–23.00. **Dapur last order 23.00.** | P + T | Ya |
| 23.30 | **Last order minuman**, diumumkan dengan sopan ke setiap meja. | T | Ya |
| 23.45 | Musik diturunkan, lampu sedikit lebih terang. Mulai beres-beres yang tidak mengganggu tamu. | P + T | Ya |
| **24.00** | **Pintu ditutup.** Hitung kas berdua, cetak laporan Z dari POS, foto ke grup WhatsApp founder. | P + T | Ya (pintu) |
| 24.00–00.45 | Bersih-bersih (SOP-08). Seduh konsentrat cold brew untuk besok (rendam 14–16 jam di chiller). Buang base kopi susu yang tersisa. Catat suhu chiller, buang sampah, kunci. P pulang 24.00, T pulang 00.45. | T (P sampai 24.00) | Tidak |

**Siklus mingguan dan bulanan**

| Kapan | Apa |
|---|---|
| Senin 15.00–16.00 | Hitung stok dan pesan barang (SOP-09). Senin adalah hari paling sepi. |
| Selasa & Jumat | Biji kopi, susu karton, dan barang kering datang. |
| Setiap hari | Es batu, makanan titip, dan uang kas kecil. |
| Rabu | Bersih dalam grinder dan filter air. |
| Kamis | Kamis Seduh Bareng. |
| Minggu | Founder mengirim laporan mingguan: tamu/hari, belanja/tamu, % es kopi susu ≤3 menit, klaim garansi, keluhan, selisih stok. |
| Paling lambat tanggal 10 | Bayar dan lapor PBJT bulan sebelumnya, kalau sudah wajib ([DPP DKI](https://dpp.jakarta.go.id/berita/jangan-sampai-terlewat-ini-batas-waktu-bayar-dan-lapor-pajak-pbjt-di-jakarta)). |
| Bulanan | Gaji, iuran BPJS, PPh Final 0,5%, kunjungan pest control (kalau dikontrak), rekonsiliasi titip jual, review HPP di Sheets. |
| Tahunan | Royalti musik LMKN, perpanjangan sewa, THR. |

---

## 2. Pemasok

**Prinsip:** minimal dua pemasok untuk setiap bahan inti. Pembayaran tunai atau transfer di muka dulu; minta tempo pembayaran (TOP) setelah 2–3 bulan order rutin. Semua harga di bawah adalah **harga eceran atau tayang**. Harga grosir hanya bisa didapat lewat penawaran tertulis (masuk ke "Pertanyaan terbuka").

### 2a. Biji kopi

**Kebutuhan** *(hitungan)*:

| | Bulan 1 (23 tamu/hari) | Rencana (60 tamu/hari) |
|---|---:|---:|
| Single origin (V60 15 g, teko cicip, dial-in, garansi) | ±2,4 kg/minggu | ±5,0 kg/minggu |
| House blend untuk konsentrat (±16,7 g per es kopi susu) | ±1,8 kg/minggu | ±4,6 kg/minggu |

Asumsinya: 1,3 minuman per tamu, setengah V60 dan setengah es kopi susu, sesuai estimasi CFO.

**Aturan beans Kopiyo** (aturan internal, bukan regulasi):

- Pakai beans 7–30 hari setelah tanggal sangrai. Jangan pernah lewat 30 hari: panel menyebut roast date lebih dari sebulan membuat pecinta kopi pergi (`offer.md`).
- Tiga beans aktif sekaligus: satu "segar-asam", satu "manis-cokelat", satu "tengah".
- Pesan setiap Senin, jumlahnya untuk satu minggu ditambah cadangan 3 hari.

| Pemasok | Lokasi | Harga publik | Min. order / lead time / pembayaran | Sumber | Catatan |
|---|---|---|---|---|---|
| **Otten Coffee** | Jakarta (distributor resmi Hario dll.) | Gayo Atu Lintang Rp389.000/kg (diskon Rp361.770). House blend Gayo komersil Rp246.000/kg | **Minta penawaran.** Otten punya tim B2B (lowongan *B2B Sales Specialist*), tetapi harga partai tidak publik | [Otten SO](https://ottencoffee.co.id/coffee-beans/kopi-arabica-gayo-atu-lintang) · [Otten kategori](https://ottencoffee.co.id/categories/coffee-beans) · [Glints: tim B2B Otten](https://glints.com/id/companies/pt-otten-coffee-indonesia/85d540fa-9a58-436b-a385-caf36910122e) | Satu pintu untuk beans, filter, dan alat. Cocok sebagai pemasok utama atau cadangan. |
| **Murrell Coffee** | Jakarta Barat (roaster) | Toraja/Kintamani Rp387.639/kg; Java Preanger Rp398.619/kg | Beli lewat Tokopedia (bayar di muka; kurir 1–2 hari, atau instan dalam kota). Harga grosir: minta penawaran | [Tokopedia Murrell 1 kg](https://www.tokopedia.com/murrell-coffee/etalase/kemasan-1-kilogram) | Calon pemasok utama single origin. |
| **Sakha Roastery** | Bekasi (bersebelahan dengan Jaktim) | Gayo Natural Rp411.900–414.900/kg; Kintamani Rp409.900/kg | Tokopedia. Grosir: minta penawaran | [Tokopedia Gayo 1 kg](https://www.tokopedia.com/find/kopi-gayo-1kg) · [Kintamani 1 kg](https://www.tokopedia.com/find/kopi-kintamani-1kg) | Dekat, jadi pengiriman cepat. |
| **Kenal (Gayo Espresso)** | Tokopedia | Rp2.809.680 per 10 × 1 kg (≈Rp281/g) | Paket 10 kg | [Tokopedia Gayo 1 kg](https://www.tokopedia.com/find/kopi-arabica-aceh-gayo-1-kg) | Pembanding harga volume untuk house blend konsentrat. |
| **Viverri Specialty Coffee Roasters** | Jl. Rawamangun Muka Timur 74B, Pulo Gadung | **Tidak ditemukan** | Tidak ditemukan. **Status operasi belum terverifikasi** (data Des 2022) | [Jakarta Post, Des 2022](https://www.thejakartapost.com/paper/2022/12/15/twenties-jakartas-roasteries-for-getting-your-caffeine-jolt.html) | Roaster di Rawamangun. Kalau masih buka, kuat untuk cerita lokal di kartu beans. **Datangi langsung.** |
| **Anomali Coffee** | Jakarta | **Tidak ditemukan** | Tidak ditemukan. Sejak 2008 menjual biji ke kafe, restoran, dan hotel; pernah disebut memasok >150 klien (data lama) dan melatih barista klien | [detikFinance](https://finance.detik.com/solusiukm/d-3601280/pengalaman-bos-anomali-coffee-lawan-sistem-ijon-di-petani-kopi) · [SWA](https://swa.co.id/read/163158/diversifikasi-bisnis-memacu-laju-bisnis-anomali-coffee) | Tanyakan paket beans + pelatihan barista. |
| Kopi Bemo | Pasar Rawamangun | **Tidak ditemukan** | ±30 jenis kopi Indonesia; pemilik berencana menyangrai sendiri (Sep 2025) | [Berita Jakarta](https://www.beritajakarta.id/en/read/60328/potret-jakarta) | Catatan: Kopi Bemo juga kompetitor (`competitors.md`). Bisa jadi mitra cerita lokal, bisa juga tidak. |

Pemasok lain yang disebut menjual grosir, tanpa rincian syarat: [Expat. Roasters](https://whatsnewindonesia.com/jakarta/feature/dine-and-drink/expat-roasters-expands-indonesias-capital) dan [Tanamera](https://exquisite-taste-magazine.com/journey-tanamera-coffee-elevating-indonesias-specialty-coffee-global-acclaim/). Keduanya perlu dihubungi langsung.

### 2b. Susu, gula aren, es, air

**Kebutuhan pada volume rencana** *(hitungan)*: susu ±33 L/minggu (±3 karton isi 12 × 1 L), gula aren cair ±4 L/minggu, es ±7 kg/hari.

| Bahan | Pemasok | Harga | Min. order / lead time | Sumber | Catatan |
|---|---|---|---|---|---|
| Susu UHT full cream | Alfamart / Indomaret (ritel) | Diamond 1 L Rp22.500; Greenfields 950 ml Rp25.700 | Tanpa minimum, ambil sendiri | [Alfamart/Kontan](https://momsmoney.kontan.co.id/news/katalog-promo-alfamart-gantung-gajian-untung-periode-25-31-agustus-2026) · [Klik Indomaret](https://www.klikindomaret.com/xpress/uht-milk-5) | Batas atas harga; dipakai CFO (Rp23/ml). |
| Susu UHT karton 12 × 1 L | Penjual B2B Jakarta (Indotrading) | Greenfields Low Fat Rp239.000/karton (≈Rp19,9/ml) | Per karton. **Data Sep 2024 (lama)**, penjual menyebut harga bisa berubah | [Indotrading](https://en.indotrading.com/jayautamasantikah/greenfields-uht-low-p587935.aspx) | Indikasi bahwa harga distributor bisa lebih murah. **Minta penawaran *foodservice*** ke distributor Greenfields/Diamond. |
| Gula aren cair | Mahorahora / Verlin (Tokopedia) | Rp60.000–62.000/L | Tokopedia, 1–2 hari | [Mahorahora](https://www.tokopedia.com/find/gula-aren-mahorahora-cair) · [Verlin](https://www.tokopedia.com/find/gula-aren-cair-1-kg) | Pilih yang berlabel halal. |
| Es batu kristal | CoolFresh (Pulogadung, satu kecamatan) | Rp9.950/5 kg | Kurir instan, **maks. 20 kg per pesanan** | [Tokopedia CoolFresh](https://www.tokopedia.com/espugautama/es-batu-kristal-jakarta-timur-100-halal-5kg) | Pesan harian ±15.00. Cadangan: [penjual lain Rp12–16 rb/5 kg](https://www.tokopedia.com/find/es-kristal-5-kg). |
| Air untuk seduh | Paket RO di bar (lihat 2e) | Rp6–7,5 juta sekali beli | – | `cost-inputs.md` §4 | Ganti filter sesuai jadwal pabrik. |

### 2c. Filter, cup, kartu beans

| Bahan | Pemasok | Harga | Sumber |
|---|---|---|---|
| Filter Hario V60 02 (100 lembar) | Otten (distributor resmi) | Rp85.000 (≈Rp850/lembar) | [Otten](https://ottencoffee.co.id/filters/hario-paper-filter-vcf-02-100w) |
| Cup PET 14 oz + tutup (take-away es) | BBC (termurah) / Starindo | Rp730–1.576/set | [BBC](https://www.tokopedia.com/bbcenter/plastik-cup-pet-14-oz-oval-tutup-flat-dome-sippy-strawless-murah-50pcs-1729866484696516428) · [Starindo](https://www.tokopedia.com/find/cup-pet-14-oz-starindo) |
| Paper cup 8 oz + tutup | Tokopedia | ≈Rp565–700/set | [gelas kertas](https://www.tokopedia.com/find/gelas-kertas-kopi) · [tutup](https://www.tokopedia.com/thong88/etalase/tutup-cup) |
| Kartu beans (cetak) | Percetakan digital lokal | **Minta penawaran** (CFO memakai Rp400/kartu [estimasi]) | – |

Kebutuhan filter pada volume rencana: ±50 lembar/hari, atau ±4 pak per minggu *(hitungan)*.

### 2d. Makanan: buat sendiri atau titip jual?

Ini temuan ops yang paling penting untuk margin.

**Masalahnya.** `offer.md` dan `cfo-sources.md` memakai HPP makanan **38%**, dengan asumsi rice bowl dititip dan roti bakar, pisang goreng, serta mie dibuat sendiri. Brief ops menyebut *seluruh* menu makanan dititip dari UMKM. Dalam titip jual, pemilik barang memberi komisi kepada penjual. Tidak ada angka baku untuk kafe. Satu-satunya angka publik yang ditemukan bersifat umum: komisi **20–60% dari harga jual** ([Gramedia](https://www.gramedia.com/best-seller/?p=26130)). Kalau Kopiyo hanya mengambil sekitar 30%, HPP makanan titip menjadi sekitar **70%**.

**HPP per item** *(hitungan; bahan bersumber, sisanya [estimasi])*:

| Item | Cara | Bahan utama (bersumber) | HPP/porsi | Harga jual | HPP % |
|---|---|---|---:|---:|---:|
| Roti bakar | Buat sendiri (griddle) | Roti tawar kupas 15 lembar Rp21.000 ([Indomaret/Kontan](https://momsmoney.kontan.co.id/news/promo-indomaret-harga-spesial-16-29-juni-2026-nugget-skincare-diskon-hingga-30)), 2 lembar = Rp2.800; mentega dan topping Rp2.500 [estimasi] | ±Rp5.300 | Rp15.000 | ±35% |
| Mie | Buat sendiri (kompor) | Indomie goreng Rp16.000/5 bungkus normal ([Alfamart/Kontan](https://momsmoney.kontan.co.id/news/katalog-promo-alfamart-gantung-spesial-idul-adha-periode-26-mei-2-juni-2026-1)) = Rp3.200; telur dan pelengkap Rp3.000 [estimasi] | ±Rp6.200 | Rp18.000 | ±34% |
| Pisang goreng | Buat sendiri | Harga pisang kepok **tidak ditemukan**. Tanya Pasar Induk Kramat Jati / Pasar Rawamangun | ±Rp5.250 [estimasi] | Rp15.000 | ±35% [estimasi] |
| Rice bowl | **Titip** dari UMKM | Bagian Kopiyo 25–30% [perlu negosiasi] | ±Rp20.160 | Rp28.000 | ±72% |

- **Campuran** [estimasi porsi pesanan: roti bakar 30%, pisang 25%, mie 20%, rice bowl 25%]: **HPP makanan ±49%**. Biaya makanan per tamu menjadi ±Rp5.880 (CFO: Rp4.560).
- **Jika semua makanan dititip** (Kopiyo mengambil 30%): ±70%, atau Rp8.400 per tamu.

**Rekomendasi ops:**

1. **Roti bakar, pisang goreng, dan mie dibuat sendiri.** Alatnya sudah ada di anggaran CFO (dapur sederhana Rp8 juta), resepnya sederhana, dan HPP-nya sekitar 35%.
2. **Rice bowl saja yang dititip.** Mulai dengan titip jual untuk menguji permintaan. Begitu penjualannya stabil (misalnya >8 porsi/hari selama 4 minggu), ubah ke **jual putus** dengan harga beli tetap. Pola "titip dulu, lalu jual putus kalau laku" dipakai ritel UMKM ([detikBali](https://www.detik.com/bali/bisnis/d-7698836/dua-pola-the-keranjang-gaet-produk-umkm-di-bali)).
3. **Isi perjanjian titip jual tertulis**, bukan sekadar nota ([kontrakhukum.com](https://kontrakhukum.com/article/skema-titip-jual-dalam-draft-perjanjian-konsinyasi-surabaya-bagi-umkm/)):
   - harga mitra dan harga jual;
   - siapa menanggung sisa yang tidak laku;
   - jadwal setor dan laporan mingguan;
   - jam antar (15.30) dan standar porsi/berat;
   - **sertifikat halal mitra** (wajib, lihat bagian 6);
   - label tanggal produksi;
   - penggantian kalau mitra tidak mengantar.

   Penelitian UMKM juga mencatat masalah keterlambatan pembayaran dalam konsinyasi ([etheses IAIN Kediri](https://etheses.iainkediri.ac.id/24602/)).

**Mencari mitra UMKM:**

- **Nama mitra spesifik tidak ditemukan di pencarian.** Tidak ada daftar publik pemasok rice bowl untuk kafe di Jakarta Timur.
- **Jalur yang realistis:**
  - dapur rumahan dengan rating baik di GoFood/GrabFood sekitar Rawamangun, Utan Kayu, dan Pisangan;
  - UMKM binaan **Jakpreneur** (platform UMKM Pemprov DKI; Jakarta Timur peringkat 2 pendapatan peserta 2025): [Berita Jakarta](https://m.beritajakarta.id/en/read/150782/150-jakpreneurs-receive-support-to-strengthen-food-businesses), [GoodStats](https://data.goodstats.id/statistic/ini-jenis-umkm-terbanyak-di-jakarta-2025-kuliner-mendominasi-zkF8P);
  - pedagang Pasar Rawamangun.
- **Uji rasa minimal 3 calon mitra sebelum tanda tangan.**
- Pemasok frozen food grosir juga tidak ditemukan dengan harga publik ([IDN Times](https://www.idntimes.com/business/economy/ainal-zahra-1/mau-jadi-agen-frozen-food-ini-daftar-supplier-terbaik) hanya memuat sosis dan bakso). Pasar Induk Kramat Jati di Jakarta Timur adalah tempat yang paling masuk akal untuk bertanya langsung.

**Gas LPG.** Harga agen Bright Gas 12 kg di Jawa **Rp218.000** (15 Agu 2026, [Bisnis.com](https://ekonomi.bisnis.com/read/20260815/44/1996598/pertamina-turunkan-harga-bright-gas-ini-rinciannya)); harga di pangkalan bisa sekitar Rp245.000 ([CNBC, cek lapangan Tangsel](https://cnbcindonesia.com/news/20260803130310-4-756048/resmi-harga-lpg-3-kg-55-12-kg-di-agen-pangkalan-per-3-agustus-2026)). Anggaran CFO Rp400.000/bulan setara ±1,6–1,8 tabung, masuk akal untuk dapur sederhana.

### 2e. Peralatan

Paket A dari `cost-inputs.md` (±Rp18,5 juta, sudah dipakai CFO). Pemasoknya:

| Alat | Pemasok | Harga | Sumber |
|---|---|---|---|
| Grinder Latina 600N (flat 60 mm) | Tokopedia | Rp3.793.840–4.036.000 | [Tokopedia](https://www.tokopedia.com/find/grinder-latina-600n) |
| 2× kettle Timemore Fish Smart | Tokopedia | Rp1.220.000–1.349.000/unit | [Tokopedia](https://www.tokopedia.com/find/timemore-fish-smart-kettle) |
| 3× dripper Hario V60 02 | Tokopedia / Otten | Rp136.550–160.000/unit | [Tokopedia](https://www.tokopedia.com/find/hario-v60-dripper-02?page=2) |
| 2× timbangan Timemore Basic 2 | Tokopedia | Rp645.000–695.000/unit | [Tokopedia](https://www.tokopedia.com/find/timemore-black-mirror-basic-2) |
| Paket filter air RO | Seno Filter / Elmira | Rp6.000.000–7.500.000 (belum termasuk instalasi) | [Tokopedia](https://www.tokopedia.com/senofilter/paket-air-ro-untuk-cafe-resto-coffee-shop-bandung-dan-sekitarnya) |
| Showcase chiller / under counter 2 pintu | Indotrading (RSA) / Tokopedia (GEA) | Rp3.745.958 / Rp10.175.000 | [Indotrading](https://en.indotrading.com/hansmesingeagetrarsa/chiller/) · [Tokopedia](https://www.tokopedia.com/find/under-counter-chiller) |
| Kompor, griddle, wajan penggoreng, freezer kecil | Toko horeca lokal | **Minta penawaran** (CFO: Rp8 juta [estimasi]) | – |
| Wadah cold brew 5 L, saringan, botol 1 L berlabel | Toko horeca | **Minta penawaran** [estimasi kecil] | – |

Grinder, kettle, dripper, dan timbangan bisa dibeli **sebelum pop-up**, dipakai di pop-up, lalu dibawa ke kedai. Uangnya tidak hilang (lihat bagian 8).

### 2f. Kebersihan, hama, utilitas

| Kebutuhan | Pemasok | Harga | Sumber / catatan |
|---|---|---|---|
| Pest control (kontrak bulanan) | Rentokil Indonesia (kantor Jakarta), penyedia lokal | **Hanya lewat survei dan penawaran.** Rentokil menyatakan harga tergantung jenis hama, luas, dan jenis perawatan | [Rentokil: harga pest control](https://www.rentokil.com/id/layanan-kami/pengendalian-hama/harga-pest-control). Minta 2–3 penawaran tertulis. Bisa masuk pos "Perawatan Rp1 juta" milik CFO. |
| Sabun, sanitizer food grade, lap, kantong sampah | Grosir / Tokopedia | Masuk pos CFO "Perawatan, kebersihan Rp1 juta" [estimasi] | – |
| Listrik B-2 | PLN | Rp1.444,70/kWh | `cost-inputs.md` §7 |
| Tambah daya di atas 5.500 VA | PLN | **Tidak ditemukan.** Tambah daya online lewat PLN Mobile tampaknya hanya sampai 5.500 VA; di atasnya harus diajukan langsung ke PLN | [Metro TV](https://www.metrotvnews.com/read/KZmCQWPM-cek-lengkap-biaya-tambah-daya-listrik-pln-berdasarkan-daya-awal). **Pilih tempat yang sudah ≥6.600 VA** (bagian 7). |

---

## 3. Orang

### 3a. Berapa orang di jam 19.00–22.00?

Perkiraan beban kerja per jam pada volume rencana. **Semua waktu tugas adalah [estimasi] dan harus diukur di pop-up.**

- 60 tamu/hari, sekitar 50% datang pukul 19–22 [estimasi], jadi sekitar 10 tamu/jam.
- **Bar ±39 menit/jam:** 6–7 V60 (±2,5 menit efektif per gelas dengan 2 dripper paralel), 6–7 es kopi susu (±1 menit), 3 Cicip Dulu (±2 menit), dan menyajikan plus cerita beans.
- **Host/kasir ±42 menit/jam:** menyapa dan mengantar 4 grup, mencatat pesanan dan pembayaran 10 tamu, WhatsApp reservasi, membereskan meja.
- **Dapur ±43 menit/jam:** ±6 porsi makanan (±5 menit) dan mencuci gelas serta server.
- **Total ±124 menit kerja per jam, setara 2,1 orang pada utilisasi 100%.** Supaya janji 3 menit tahan saat lonjakan (utilisasi ±70–75%), dibutuhkan **±3 orang**.
- Dengan 2 orang, kapasitas wajar sekitar 6–7 tamu/jam di jam ramai, atau **±40 tamu/hari**.

| Situasi | Orang di 19.00–22.00 |
|---|:-:|
| Bulan 1–4 (ramp CFO 23–40 tamu/hari) | **2** |
| Bulan 5 dst. (≥45 tamu/hari) dan volume rencana 60 | **3** |
| Sabtu malam pada volume rencana | 3, mungkin 4. Ukur dari data POS bulan 3–4. |

### 3b. Peran

| Peran | Tugas | Profil |
|---|---|---|
| **Barista utama (B1)** | Pemilik resep dan *dial-in*, kualitas, pelatihan, pemesanan beans bersama founder, pemandu Kamis Seduh Bareng | ≥2 tahun manual brew di kedai specialty, bisa menjelaskan kopi dengan bahasa awam, suka ngobrol dengan tamu, bersedia kerja malam. **Ini syarat board C10. Nama belum ada.** |
| **Barista (B2)** | Bar dan host, bisa semua tugas B1 di hari B1 libur | ≥1 tahun barista, keramahan lebih penting dari teknik |
| **Helper (H)** | Kasir/host, jalur cepat es kopi susu, dapur (roti bakar, pisang goreng, mie, rice bowl), cuci, membereskan meja | Pengalaman dapur atau kasir F&B. Dilatih V60 dasar sampai bulan 3 sebagai cadangan. |
| **Paruh waktu (R)**, mulai bulan 5 | Host, jalur cepat, membereskan meja di jam ramai | Mahasiswa atau pekerja sekitar, minimal 18 tahun |
| **Founder** | Belanja, rekonsiliasi kas, marketing dan komunitas, izin, hubungan pemasok, laporan mingguan. **Bulan 1: hadir sebagai tuan rumah 19.00–22.00 minimal 4 malam/minggu**, juga di rencana dasar, untuk belajar dan mengumpulkan umpan balik | Pengalaman F&B founder **belum tercatat** (syarat board C10) |

Semua orang harus bisa membuat es kopi susu dan menjalankan kasir.

### 3c. Asumsi upah

**Per staf penuh waktu:**

| Komponen | Per bulan |
|---|---:|
| UMP DKI 2026 | Rp5.729.876 |
| BPJS pemberi kerja 10,24% | Rp586.739 |
| THR/12 | Rp477.490 |
| **Total** | **Rp6.794.105** |

Ini sama dengan angka CFO (`cfo-sources.md`; sumber UMP [Katadata](https://katadata.co.id/amp/berita/industri/694bb57d97fa5/ump-jakarta-2026-resmi-naik-jadi-rp-5-72-juta/), BPJS [TK](https://www.bpjsketenagakerjaan.go.id/artikel/18913/artikel-berapa-besaran-iuran-jht,-jkk,-jkm,-jp-dan-jkp) dan [Kesehatan](https://www.bpjs-kesehatan.go.id/bpjs/index.php/pages/detail/2014/13)).

**Hal yang harus dicek akuntan atau konsultan ketenagakerjaan:**

1. **Pengecualian UMP untuk usaha mikro dan kecil BELUM TERVERIFIKASI.** PP 36/2021 Pasal 36 pernah membolehkan upah di bawah UMP untuk usaha mikro dan kecil, berdasarkan kesepakatan dan dengan batas bawah tertentu ([DDTC](https://news.ddtc.co.id/berita/nasional/28040/usaha-mikro-kecil-boleh-bayar-upah-lebih-rendah-dari-ump), [Hukumonline](https://www.hukumonline.com/klinik/a/apakah-perusahaan-boleh-menggaji-di-bawah-ump-lt5118a676ad68c)). Sumbernya dari 2021, dan status pasal itu setelah PP 49/2025 belum dipastikan. **Jangan gaji di bawah UMP sebelum dicek.** Rencana ini tetap memakai UMP penuh.
2. **Program BPJS menurut skala usaha.** Perpres 109/2013 mewajibkan usaha **mikro** minimal JKK dan JKM, dan usaha **kecil** JKK, JHT, dan JKM. Jaminan Pensiun (2%) tidak termasuk kewajiban keduanya ([Hukumonline](https://www.hukumonline.com/berita/a/3-regulasi-ini-perlu-dibenahi-agar-selaras-sjsn-lt582fda8100641/), [kajian DJSN](https://djsn.go.id/files/dokumen/Dokumen%20Kajian/202109011058KA%20Skala%20Usaha%20Mikro.pdf)). Ada usulan revisi yang statusnya belum jelas. CFO tetap memakai 10,24%, yang konservatif.
3. **Jam kerja dan lembur.**
   - Jam kerja 8 jam × 5 hari atau 7 jam × 6 hari (40 jam/minggu).
   - Lembur maksimal 4 jam/hari dan 18 jam/minggu, dengan persetujuan tertulis.
   - Upah sejam = 1/173 × upah sebulan = **Rp33.121**. Lembur jam pertama 1,5× (Rp49.681), jam berikutnya 2× (Rp66.241) ([Hukumonline](https://www.hukumonline.com/klinik/a/cara-hitung-upah-lembur-per-jam-ini-rumusnya!-lt4b7e3965556d3/), [DDTC](https://news.ddtc.co.id/berita/nasional/1798791/begini-dasar-penghitungan-upah-lembur-yang-harus-anda-tahu)).
   - Istirahat minimal 30 menit setelah 4 jam kerja terus-menerus.
4. **Paruh waktu.** Upah per jam tidak boleh di bawah **upah sebulan ÷ 126**, yaitu **Rp45.475/jam** untuk UMP DKI. Upah per jam hanya untuk pekerja kurang dari 7 jam/hari dan kurang dari 35 jam/minggu (PP 36/2021 Pasal 16; [Bisnis.com/Kemenaker](https://ekonomi.bisnis.com/read/20210302/12/1362701/kemenaker-tegaskan-upah-per-jam-hanya-untuk-pekerja-paruh-waktu), [Gadjian](https://www.gadjian.com/blog/2023/02/23/cara-menghitung-gaji-karyawan-part-time/)).
5. **Kerja malam pekerja perempuan** (UU 13/2003 Pasal 76; [Hukumonline](https://www.hukumonline.com/klinik/a/aturan-lembur-untuk-pekerja-perempuan-lt50eb906629072), [Talenta](https://www.talenta.co/blog/aturan-shift-malam-perempuan/)):
   - Pekerja perempuan yang bekerja antara pukul 23.00 dan 07.00 wajib diberi **makanan dan minuman bergizi**, dan keamanannya dijaga.
   - Yang **berangkat atau pulang antara 23.00 dan 05.00 wajib diberi angkutan antar-jemput.**
   - Perempuan di bawah 18 tahun dilarang bekerja pada jam itu.

   Kopiyo tutup 00.45, jadi semua shift penutup kena aturan ini. Status rumusan pasal setelah UU Cipta Kerja belum dicek.

### 3d. Shift

Semua shift penuh waktu adalah 8 jam kerja dan 1 jam istirahat (2 × 30 menit), 5 hari per minggu.

| Kode | Jam | Istirahat | Jam kerja |
|---|---|---|---:|
| **P** (pembuka) | 15.00–24.00 | 18.00–18.30 dan 22.00–22.30 | 8 |
| **T** (penutup) | 15.45–00.45 | 18.30–19.00 dan 22.30–23.00 | 8 |
| **M** (tengah, hari ramai) | 16.45–00.45 | 20.45–21.15 dan 23.30–24.00 | 7 |
| **R** (paruh waktu jam ramai) | 18.30–22.30 | tanpa istirahat | 4 |

**Pada hari dengan 2 orang (P + T):**

| Jam | Orang di lantai |
|---|---|
| 15.00–15.45 | 1 (persiapan) |
| 15.45–18.00 | 2 |
| 18.00–19.00 | 1 (istirahat bergilir) |
| 19.00–22.00 | **2** |
| 22.00–23.00 | 1 (istirahat bergilir) |
| 23.00–24.00 | 2 |
| 24.00–00.45 | 1, dengan pintu terkunci |

**Kalau penutup sendirian terasa tidak aman**, P ikut sampai 00.45. Itu lembur 45 menit, sekitar Rp37.300 per malam *(hitungan)*.

### 3e. Rota (a): rencana dasar, 3 staf

**Bulan 1–4** (sepi; 2 orang di jam ramai sudah cukup):

| Staf | Sen | Sel | Rab | Kam | Jum | Sab | Min | Jam/minggu |
|---|:-:|:-:|:-:|:-:|:-:|:-:|:-:|---:|
| B1 Barista utama | P | – | – | P | P | P | T | 40 |
| B2 Barista | T | P | P | – | – | T | P | 40 |
| H Helper | – | T | T | T | T | M | – | 39 |
| **Orang di 19.00–22.00** | 2 | 2 | 2 | 2 | 2 | **3** | 2 | |

- Setiap hari selalu ada minimal satu barista.
- Di hari H libur (Minggu–Senin), satu barista memegang bar dan satu lagi memegang kasir dan dapur.
- Bulan 1: founder hadir 19.00–22.00, terutama Kamis dan Jumat.

**Bulan 5 dst.** (≥45 tamu/hari): tambah paruh waktu **R pada Kamis, Jumat, dan Minggu** (3 shift/minggu). Jam ramai menjadi 3 orang di Kamis–Minggu.

- Biaya: 3 × 4 jam × Rp45.475 × 52/12 ≈ **Rp2,36 juta/bulan**, ditambah iuran BPJS minimal *(hitungan)*.
- Kalau data POS menunjukkan Senin–Rabu rata-rata >40 tamu, tambah shift R ke-4 (Rabu): ≈Rp3,15 juta/bulan.
- **Alternatif lebih mahal:** hari ke-6 untuk staf penuh waktu dibayar sebagai lembur hari istirahat (pengali ≥2×, sekitar ≥Rp530 ribu per shift 8 jam *(hitungan)*). Paruh waktu jauh lebih murah.

### 3f. Rota (b): rencana ramping, founder di bar + 2 staf

| Orang | Sen | Sel | Rab | Kam | Jum | Sab | Min | Jam/minggu |
|---|:-:|:-:|:-:|:-:|:-:|:-:|:-:|---:|
| F Founder | – | P | P | T | M | M | T | ±52 (hadir) |
| S1 Barista | P | – | – | P | P | P | P | 40 |
| S2 Helper | T | T | T | – | T | T | – | 40 |
| **Orang di 19.00–22.00** | 2 | 2 | 2 | 2 | **3** | **3** | 2 | |

- **Founder bekerja 6 hari, sekitar 52 jam.** Ini inti penghematan versi ramping, sekaligus risiko kelelahan. Satu hari libur penuh (Senin) tidak boleh dilanggar.
- Siapkan daftar 2–3 barista lepas sebagai cadangan kalau founder sakit.
- **Bulan 5 dst.:** tambah R pada Kamis dan Minggu (2 shift/minggu), ≈**Rp1,58 juta/bulan** *(hitungan)*.

### 3g. Bulan pertama dan sebelum buka

- **Dua minggu sebelum buka: pelatihan berbayar.**
  - Minggu 1: resep, *dial-in*, SOP.
  - Minggu 2: dua sampai tiga "malam uji" untuk teman dan keluarga, dengan stopwatch untuk janji 3 menit.
  - Biaya: 3 staf × setengah bulan × Rp6,79 juta ≈ **Rp10,2 juta** (ramping: 2 staf ≈ Rp6,8 juta). **Belum ada di `numbers.json`.**
  - Daftarkan BPJS sebelum hari pertama pelatihan.
- **Rekrut barista utama 6–8 minggu sebelum buka**, dan ajak dia menjalankan pop-up (bagian 8). Kalau ia tidak cocok, lebih baik ketahuan sebelum sewa ditandatangani.
- **Bulan 1:** jam buka tetap penuh supaya kebiasaan pelanggan terbentuk, dan rota tetap 2 orang per hari. Kelebihan tenaga di sore yang sepi dipakai untuk prep, membersihkan, dan menyapa calon tamu di depan kedai.

---

## 4. SOP

Satu halaman per SOP. Cetak, laminasi, dan tempel di bar.

### SOP-01 Buka (15.00–16.00)

1. 15.00 Buka kunci. Nyalakan lampu bar, kettle, chiller, RO. Cek suhu chiller dan catat di log. Kalau suhu tidak dingin, lapor founder sebelum memakai susu.
2. Saring konsentrat cold brew semalam, timbang hasilnya, tuang ke botol berlabel "KONSENTRAT tgl/jam". Buang konsentrat yang umurnya lebih dari 7 hari (lihat SOP-03).
3. Isi botol susu dan pompa gula aren. Cek stok es; pesan es kalau kurang dari 5 kg.
4. *Dial-in* 3 beans: seduh 1 V60 per beans (resep SOP-04), cicipi, sesuaikan gilingan, catat setelan di papan bar.
5. 15.30 Terima es dan rice bowl titip (cek jumlah, suhu, label halal, tanggal; tanda tangani nota).
6. Siapkan dapur: iris roti, siapkan pisang, isi minyak, nyalakan kompor saat pesanan pertama.
7. 15.45 (T datang) Atur meja, kartu beans, kartu "Dipesan", papan "HP boleh, laptop tidak". Atur musik setara suara ngobrol. Lap toilet.
8. Buka WhatsApp Business: konfirmasi reservasi malam ini dengan template pesan.
9. 15.55 Seduh teko cicip. Briefing 5 menit: yang habis, beans aktif, reservasi, siapa memegang bar dan siapa memegang kasir/dapur.
10. 16.00 Buka pintu, nyalakan papan "BUKA". Buka shift di POS dengan kas awal yang dihitung berdua.

### SOP-02 Lima menit pertama: tiga teman datang pukul 19.30

Tujuan: dalam 5 menit mereka sudah duduk, merasa disambut, tahu aturannya tanpa merasa dimarahi, dan sudah memegang minuman atau tegukan cicip.

| Menit | Yang dilakukan | Kalimat (contoh, sesuaikan gaya sendiri) |
|---|---|---|
| 0:00 | Orang terdekat dengan pintu (host; kalau sibuk, barista dari bar) menatap dan menyapa **dalam 10 detik**, meski sedang membuat minuman. | "Malam, Kak! Selamat datang di Kopiyo. Bertiga ya? Sudah reservasi?" |
| 0:15 | Tawarkan pilihan tempat duduk. Jangan pilihkan meja dekat bar untuk grup yang mau ngobrol, kecuali mereka minta. | "Mau dekat bar biar lihat kopinya diseduh, atau di pojok yang lebih tenang buat ngobrol?" |
| 0:45 | Saat memberi menu, sampaikan aturan **sekali, dengan senyum, sebagai alasan baik**. Kalau ada tas laptop, tunjukkan tempat menaruhnya. | "Satu info kecil ya, Kak: di sini **HP boleh, laptop kami minta disimpan**, biar semua meja enak buat ngobrol. Tasnya aman di bawah meja." |
| 1:00 | Tawarkan dua jalan, mulai dari yang paling mudah. | "Kalau capek dan mau cepat, **es kopi susu kami keluar dalam 3 menit**. Kalau mau coba kopi seduh tapi bingung, ada **Cicip Dulu**: tiga tegukan kecil dari tiga beans, gratis, nanti saya bantu pilih." |
| 1:20 | Makanan dan paket, singkat. | "Lapar? Ada roti bakar, pisang goreng, mie, rice bowl. Bertiga juga pas buat **Sesi Ngobrol**: satu teko dua beans plus camilan, Rp85.000 bertiga." |
| 1:30–2:30 | Catat pesanan di POS (*open bill* per meja), **sebutkan ulang pesanannya**. Mulai hitung waktu 3 menit sejak pesanan masuk POS. | "Dua es kopi susu, satu Cicip Dulu, satu pisang goreng ya, Kak." |
| 2:30–4:00 | Es kopi susu dibuat di jalur cepat (SOP-03) dan diantar. Barista membawa 3 tegukan cicip dan kartu beans, lalu bertanya 2 hal. | "Kakak lebih suka yang segar-asam kayak buah, atau yang manis-cokelat? Mau hitam saja atau pakai susu?" |
| 5:00 | Cek singkat, lalu **tinggalkan mereka ngobrol**. Kalau kartu beans di meja dibalik, artinya tamu tidak mau diceritakan soal kopi; hormati. | "Aman, Kak? Nanti kalau mau nambah gelas kedua cuma Rp15.000." |

Kalau grup belum reservasi dan meja penuh: tawarkan waktu tunggu yang jujur ("kira-kira 20 menit"), catat nomor WhatsApp, dan kabari begitu meja kosong.

### SOP-03 Es kopi susu 3 menit (jalur cepat) dan konsentrat

**Konsentrat cold brew** (diseduh setiap malam saat tutup):

1. Giling house blend **kasar**. Perbandingan **1 : 5**, misalnya 400 g kopi + 2.000 g air RO. Takaran harian: bulan 1 ±250 g kopi, volume rencana ±650 g.
2. Aduk, tutup, rendam **14–16 jam di chiller** (00.15 → 15.00).
3. Saring (SOP-01), timbang hasilnya (±60% dari berat air karena diserap ampas), beri label tanggal dan jam.
4. **Umur simpan:** konsentrat tanpa campuran **maksimal 7 hari** di chiller tertutup; rasa terbaik 1–3 hari. Campuran yang **mengandung susu dibuang saat tutup hari itu juga**. Rujukan umum (blog kopi, bukan regulator) menyebut konsentrat murni ±7–14 hari dan campuran susu ±1–2 hari ([Breville](https://www.breville.com/us/en/blog/coffee-and-espresso/how-long-does-cold-brew-last.html), [Complete Home Barista](https://completehomebarista.com/guides/cold-brew-shelf-life/)). Aturan 7 hari dan 1 shift di sini sengaja lebih ketat.

**Resep 1 gelas** (gelas 14 oz):

| Bahan | Takaran |
|---|---|
| Es | 150 g |
| Gula aren cair | 15 ml |
| Susu UHT full cream | 120 ml |
| Konsentrat | 50 ml (≈16,7 g kopi) |

Diaduk atau dikocok. Waktu membuat ±45–60 detik.

**Jam ramai (mulai 18.30):** campur "base kopi susu" di botol 1 L (konsentrat 50 : susu 120 : gula aren 15). Satu gelas = es + 185 ml base, ±20 detik. Buang sisa base saat tutup.

**Aturan antrean:**

1. Es kopi susu **selalu menyalip** antrean V60.
2. Jalur cepat ada di sebelah kasir dan dipegang host. Barista V60 tidak perlu berhenti.
3. Kalau dalam 2 menit pesanan belum dibuat, siapa pun yang kosong langsung membuatnya.
4. Catat waktu (jam pesanan masuk POS dan jam diantar) untuk 10 gelas pertama setiap malam pukul 19–21. **Target: ≥90% ≤3 menit.**
5. Kalau sebuah gelas lewat 3 menit, katakan terus terang ("Maaf Kak, tadi agak antre, ini es kopi susunya") dan catat di log. Kalau lebih dari 2 kali dalam seminggu, bahas penambahan orang di jam ramai.

### SOP-04 Layanan V60, resep, dan Cicip Dulu

**Resep V60 Kopiyo (ditimbang setiap gelas):**

| Parameter | Nilai |
|---|---|
| Dosis | **15 g** (sama dengan asumsi CFO) |
| Air | **240 g** (rasio 1 : 16), air RO |
| Suhu | **92–94°C** |
| Gilingan | Medium-fine (seperti garam meja). Setelan per beans dicatat di papan bar. |
| Waktu total | **2:45–3:15** |

Rujukan umum: 15 g : ±250 g, 93–95°C, medium-fine, selesai sekitar 3 menit ([Hario UK](https://hario.co.uk/brew-guides/v60/intermediate), [Honest Coffee Guide](https://honestcoffeeguide.com/brew-recipes/basic-hario-v60-recipe/)). Angka di atas adalah resep rumah Kopiyo dan boleh disesuaikan barista utama per beans, **asal ditulis**.

**Langkah:**

1. Sapa tamu di bar, tunjukkan beans yang dipilih dan kartunya.
2. Bilas filter dengan air panas, buang airnya. Panaskan server dan cangkir.
3. Masukkan 15 g kopi, ratakan, *tare* timbangan, jalankan timer.
4. **Bloom** 40 g air, 0:00–0:35.
5. Tuang sampai 150 g pada 1:00, lalu sampai 240 g pada 1:45, dengan tuangan memutar pelan.
6. Air habis turun pada 2:45–3:15.
   - Lebih cepat dari 2:30 dan rasanya asam/tipis: gilingan dihaluskan.
   - Lebih lama dari 3:30 dan rasanya pahit/kering: gilingan dikasarkan.
7. Sajikan server dan cangkir bersama kartu beans. Cerita satu kalimat saja, kecuali tamu bertanya lagi ("Ini Gayo dari Aceh, rasanya manis kayak gula merah").

**Sesi Ngobrol (2–4 orang):** dua V60 terpisah, masing-masing **20 g : 320 g**, dari dua beans berbeda, disajikan di dua server, dengan 4 cangkir dan piring camilan berbagi.

**Cicip Dulu:**

1. Seduh "teko cicip" kecil **2 kali sehari** (15.55 dan 19.00): untuk tiap beans aktif, **10 g : 160 g**, dengan resep yang sama. Simpan di server tertutup. Buang setelah 60 menit.
2. Sajikan 3 gelas kecil (±15 ml) dengan tiga kartu beans. Tanya 2 hal (lihat SOP-02), lalu rekomendasikan satu beans.
3. Satu Cicip Dulu per tamu per kunjungan. Catat di POS sebagai item Rp0 supaya bisa dihitung.

### SOP-05 Garansi seduh ulang

Janji: *tidak cocok di tegukan pertama, kami seduh ulang dengan beans lain, gratis* (sekali per gelas).

1. Berlaku kalau tamu bilang tidak cocok di awal (gelas masih hampir penuh). **Jangan berdebat, jangan minta alasan panjang.**
2. Tanya satu hal: "Kurang cocoknya di mana, Kak: terlalu asam, terlalu pahit, atau terlalu ringan?"
3. Pilih beans dengan arah sebaliknya (asam → manis-cokelat; pahit → yang lebih segar). Tawarkan dulu tegukan dari teko cicip kalau masih ada.
4. Seduh ulang dengan resep SOP-04 dan antar dengan kartu beans baru. Ambil gelas lama.
5. Catat di POS (item "Garansi" Rp0) **dan** di log waste Sheets (beans, gram, alasan). Ini data penting: kalau satu beans sering diklaim, keluarkan dari menu.
6. Kalau yang kedua masih tidak cocok: minta maaf, tawarkan tukar ke es kopi susu tanpa tambahan biaya (keputusan barista yang bertugas, maksimal sekali). Catat.
7. Biaya garansi sudah di model CFO (±Rp171/tamu pada klaim 5%). Kalau klaim mingguan lebih dari 10% gelas V60, laporkan ke founder.

### SOP-06 Tamu membuka laptop

**Pencegahan (lebih penting daripada teguran):**

- Tulisan "HP boleh, laptop tidak" ada di pintu, di menu, di kartu meja, di deskripsi Google Maps dan Instagram, dan di pesan konfirmasi reservasi.
- Aturan disampaikan sekali saat menyambut (SOP-02).

**Kalau tetap ada yang membuka laptop:**

1. Tunggu sampai ada jeda; jangan memotong di tengah kalimat. Datangi sendiri, **jangan berteriak dari bar**, dan jangan di depan meja lain.
2. Bicara pelan, sambil sedikit membungkuk:
   > "Kak, maaf ganggu sebentar ya. Di Kopiyo semua meja kami jaga buat ngobrol, jadi laptopnya kami minta disimpan dulu. HP aman kok, kalau perlu balas kerjaan sebentar."
3. Kalau tamu bilang harus menyelesaikan pekerjaan:
   > "Paham banget, Kak. Kalau memang perlu kerja pakai laptop, minumannya bisa kami pindahkan ke cup take-away, tanpa biaya cup. Atau Kakak selesaikan dulu 5 menit, terus kami tunggu ngobrolnya."
4. Ucapkan terima kasih ketika laptop sudah disimpan. Jangan diungkit lagi, tetap ramah.
5. Kalau tamu menolak setelah teguran kedua: panggil barista utama atau founder. Tawarkan **pengembalian uang untuk minuman yang belum diminum** dan cup take-away. **Jangan pernah mempermalukan tamu, jangan memotret, jangan menyentuh laptopnya.**
6. Catat kejadiannya di log keluhan. Kalau kejadian di kedai lebih dari 3 kali per minggu, perjelas tulisan di pintu dan di Google Maps.

Pengecualian yang **boleh**: tablet atau laptop untuk menunjukkan foto atau video ke teman selama beberapa menit (bagian dari ngobrol), dan kurir atau tamu yang menunggu sebentar.

### SOP-07 Menangani keluhan

1. **Dengarkan sampai selesai.** Tatap tamunya, jangan memotong, jangan membela diri.
2. **Minta maaf atas pengalamannya**: "Maaf ya, Kak, harusnya tidak begitu."
3. **Tawarkan solusi saat itu juga.** Setiap staf **boleh langsung** membuat ulang item, mengganti dengan item lain, atau menggratiskan **satu item sampai Rp25.000** tanpa izin. Di atas itu, hubungi founder lewat WhatsApp.
4. **Selesaikan dan kembali** 5 menit kemudian: "Sekarang sudah pas, Kak?"
5. **Catat** di log keluhan (tanggal, jam, meja, masalah, solusi, nilai kompensasi, siapa yang menangani). Founder meninjaunya setiap Minggu.
6. Masalah keamanan pangan (rambut, benda asing, makanan basi): tarik item, ganti, simpan sisanya untuk diperiksa, dan beri tahu mitra titip jual kalau itemnya dari mitra.
7. **Ulasan online:** founder membalas dalam 24 jam. Isinya terima kasih, minta maaf atas hal spesifik, sebutkan apa yang sudah diperbaiki, dan ajak kembali. Jangan berdebat di publik, jangan membuka data tamu.

### SOP-08 Tutup (23.00–00.45)

1. 23.00 Dapur last order. Matikan kompor setelah pesanan terakhir; bersihkan griddle selagi hangat.
2. 23.30 Umumkan last order minuman dengan sopan ke setiap meja.
3. 23.45 Musik diturunkan, lampu dinaikkan sedikit. Kumpulkan gelas dari meja yang sudah selesai.
4. 24.00 Pintu dikunci; tamu yang masih ada dipersilakan menghabiskan minuman.
5. **Hitung kas berdua (P + T):** cetak laporan Z dari POS, cocokkan tunai dan QRIS, isi formulir kas, foto formulir dan laporan Z, kirim ke grup WhatsApp founder. Uang tunai masuk brankas atau setor besok.
6. Buang sisa base kopi susu dan teko cicip. Cuci server, dripper, kettle, timbangan.
7. Bersihkan grinder (sikat burr, buang sisa bubuk). Rabu: bersih dalam.
8. **Seduh konsentrat untuk besok** (SOP-03) dan beri label.
9. Simpan susu, makanan, dan bahan dengan label tanggal. Rice bowl titip yang tidak laku: catat di Sheets "Titip jual" dan ikuti perjanjian (retur atau buang).
10. Lap meja dan kursi, sapu dan pel, kosongkan semua tempat sampah, keluarkan kantong sampah.
11. Catat suhu chiller dan isi checklist tutup. Matikan semua yang tidak perlu (kettle, lampu, AC). Cek kompor dan regulator gas.
12. Kunci, pasang alarm (kalau ada). P pulang 24.00 dan T pulang 00.45 dengan transport yang sudah diatur (bagian 3c).

### SOP-09 Pesan ulang mingguan (Senin 15.00–16.00)

1. Hitung fisik semua bahan di daftar Sheets "Stok Mingguan": beans per jenis, house blend, susu, gula aren, filter, cup, roti, mie, minyak, gas, bahan kebersihan.
2. Masukkan angka ke Sheets. Sheets menghitung:
   - pemakaian aktual dan pemakaian teoretis (dari penjualan POS × resep);
   - selisih;
   - **jumlah pesan = par level − stok** (par = pemakaian harian rata-rata × (lead time + 3 hari)).
3. Selisih stok lebih dari 5% untuk satu bahan: tandai, dan tanyakan di briefing (salah takar, waste tidak dicatat, atau hilang).
4. Founder menyetujui pesanan sebelum 17.00. Kirim pesanan lewat WhatsApp atau Tokopedia ke pemasok utama. Kalau pemasok utama kosong, pakai cadangan dari bagian 2.
5. **Beans:** pastikan tanggal sangrai akan masuk jendela 7–30 hari saat dipakai. Minta roaster menyangrai sesuai jadwal pesanan.
6. Jadwal datang: Selasa/Rabu 14.00–16.00. Es dan makanan titip tetap harian.
7. **Saat barang datang:**
   - cocokkan nota dengan pesanan (jumlah, harga);
   - cek tanggal sangrai, kedaluwarsa, label halal, suhu susu;
   - tolak yang rusak dan foto;
   - simpan dengan prinsip yang pertama masuk dipakai pertama.
8. Simpan foto nota di Sheets "Pembelian". Bayar sesuai syarat (transfer di muka atau tempo kalau sudah disepakati).
9. Perbarui harga di Sheets "Bahan" kalau berubah. HPP dan harga minimum ikut berubah otomatis (bagian 5).

---

## 5. Alat (stack terkecil)

**MoodBrew AI dibekukan, sesuai syarat board C1.** Tidak ada Customer App, tidak ada POS buatan sendiri, dan tidak ada biaya pengembangan di tahun 1. Pemesanan dilakukan lewat percakapan dengan barista.

| Kebutuhan | Alat | Harga publik | Mengapa |
|---|---|---|---|
| POS + QRIS (kedai) | **Majoo Starter** (pilihan utama, setelah demo) | Rp249.000/outlet/bulan, belum PPN, **minimal langganan 12 bulan** | Halaman resmi mencantumkan pencatatan resep, stok, harga modal, dan **pembayaran QRIS** di paket Starter ([majoo.id/harga](https://majoo.id/harga), [FAQ](https://majoo.id/faq), [detail](https://majoo.id/harga/detail)). |
| POS (alternatif termurah) | Qasir Pro | Rp699.000/12 bulan (≈Rp58.250/bulan), belum pajak | Menu bahan baku dan resep ada, otomatisasinya disarankan di Pro/Pro Plus ([blog Qasir](https://blog.qasir.id/en/tips/kini-menu-bahan-baku-resep-bisa-diakses-langsung-di-aplikasi-qasir?region=id), [harga](https://www.qasir.id/en/pricing)). **Dukungan QRIS Qasir tidak terverifikasi.** |
| POS (pembanding) | Moka Basic | Rp299.000/outlet/bulan, +Rp10.000/slot karyawan ([Moka](https://www.mokapos.com/en/pricing)) | Dipakai CFO. Satu ulasan menyebut manajemen bahan baku ada di paket **Pro Rp499.000** ([HashMicro](https://www.hashmicro.com/id/blog/review-aplikasi-moka-pos/)), jadi Basic mungkin tidak cukup. Tanyakan saat demo. |
| POS untuk pop-up | Versi gratis Qasir atau majoolite + **QRIS statis** dari bank | Gratis. QRIS statis contohnya [Livin' Merchant Mandiri](https://www.bankmandiri.co.id/livin-merchant/terima-pembayaran-qris-statis). MDR 0% untuk transaksi ≤Rp100.000 ([BI](https://www.bi.go.id/id/publikasi/ruang-media/cerita-bi/Pages/mdr-qris.aspx)) | Jangan terikat kontrak 12 bulan sebelum lokasi pasti. |
| Pembukuan | Laporan POS + Google Sheets, ditambah akuntan bulanan | Mekari Jurnal punya aplikasi buku kas **gratis** ([jurnal.id](https://www.jurnal.id/id/aplikasi-buku-kas)); paket berbayar tidak ditemukan harganya | Untuk satu outlet, Sheets cukup sampai ada akuntan. |
| Stok + HPP | **Google Sheets**, template di bawah | Gratis | Sesuai board C1: spreadsheet HPP, bukan software. |
| Rota, reservasi, komunikasi tim | Google Sheets (rota, buku reservasi) + WhatsApp Business (reservasi, grup tim) | Gratis | Reservasi meja lewat WhatsApp sudah ada di offer. |

**Kriteria memilih POS saat demo:**

- QRIS terintegrasi (wajib);
- *open bill* per meja, supaya harga gelas kedua Rp15.000 bisa diterapkan di kunjungan yang sama;
- item Rp0 untuk Cicip Dulu dan Garansi;
- laporan penjualan per item yang bisa diekspor ke CSV;
- akun per staf;
- cetak struk dengan baris "PBJT 10%" begitu sudah wajib.

Resep di POS bagus kalau ada, tapi tidak wajib, karena HPP dan stok ada di Sheets.

**Biaya QRIS untuk tagihan grup.** Transaksi di atas Rp100.000 dikenai MDR 0,7% untuk usaha kecil ke atas, atau 0% sampai Rp500.000 untuk usaha mikro ([BI](https://www.bi.go.id/id/publikasi/ruang-media/cerita-bi/Pages/mdr-qris.aspx)). Meja 4 orang dengan Sesi Ngobrol dan makanan bisa lewat Rp100.000. Dampaknya kecil, tapi bukan nol.

### Template Google Sheets: stok + HPP

Mengikuti rumus PRD founder:

- **HPP = Σ(qty × biaya satuan) + kemasan + cadangan waste**
- **Harga = HPP ÷ (1 − target margin − biaya variabel)**

| Tab | Kolom | Rumus kunci (contoh baris 2) |
|---|---|---|
| **Bahan** | Kode · Nama · Satuan beli · Isi per kemasan (g/ml/pcs) · Harga per kemasan · **Harga per satuan** · Pemasok utama · Pemasok cadangan · Lead time (hari) · Min. order · Tanggal harga · Link sumber | `F2 = E2/D2` |
| **Resep** | Menu · Kode bahan · Qty · Harga per satuan · **Biaya** | `D2 = XLOOKUP(B2, Bahan!A:A, Bahan!F:F)` · `E2 = C2*D2` |
| **HPP & Harga** | Menu · Biaya bahan · Kemasan · Waste % · **HPP** · Biaya variabel % · Target margin % · **Harga minimum** · Harga jual · **Margin aktual** · Status | `B2 = SUMIF(Resep!A:A, A2, Resep!E:E)` · `E2 = B2 + C2 + B2*D2` · `H2 = E2/(1-G2-F2)` · `J2 = 1 - E2/I2 - F2` · `K2 = IF(J2<G2, "UBAH HARGA/RESEP", "OK")` |
| **Penjualan** | Tanggal · Menu · Qty (tempel ekspor POS mingguan) | – |
| **Stok Mingguan** | Kode · Stok awal · Masuk · Stok akhir (hitung fisik) · Pakai aktual · Pakai teoretis · Selisih % · Par level · **Jumlah pesan** | `E2 = B2 + C2 - D2` · `F2 = SUMPRODUCT(SUMIF(Penjualan!B:B, Resep menu, Penjualan!C:C) × qty resep)` (atau tab bantu per menu) · `G2 = (E2-F2)/F2` · `H2 = (E2/7) * (lead time + 3)` · `I2 = MAX(0, ROUNDUP((H2-D2)/isi kemasan, 0))` |
| **Waste** | Tanggal · Bahan · Qty · Alasan (kedaluwarsa / salah buat / garansi / teko cicip / dial-in) | Dijumlah per minggu ke Stok Mingguan |
| **Pembelian** | Tanggal · Pemasok · Bahan · Qty · Harga · Foto nota | – |
| **Titip jual** | Tanggal · Mitra · Item · Dititip · Terjual · Sisa · Harga mitra · Harga jual · Bagian Kopiyo · Utang ke mitra | `Utang = Terjual × Harga mitra` |

Biaya variabel % adalah PPh Final 0,5% ditambah MDR QRIS (0% untuk ≤Rp100.000). **PBJT 10% tidak dimasukkan** kalau menu menulis "harga belum termasuk PBJT 10%". Kalau harga menu sudah termasuk PBJT, tambahkan 10/110 ≈ 9,09% ke biaya variabel.

**Contoh terisi** *(hitungan dari harga di bagian 2 dan `cost-inputs.md`)*:

| Menu | Bahan | HPP | Harga | Margin aktual | Harga minimum |
|---|---|---:|---:|---:|---:|
| V60 (dine-in) | Kopi 15 g × Rp400 = Rp6.000; filter Rp850; air Rp200 → Rp7.050; waste 5% Rp353 | Rp7.403 | Rp25.000 | 1 − 7.403/25.000 − 0,5% = **69,9%** | Target 65%: 7.403 ÷ (1 − 0,65 − 0,005) = **Rp21.458** |
| Es kopi susu (dine-in) | Konsentrat 16,7 g × Rp263 = Rp4.392; susu 120 ml × Rp23 = Rp2.760; gula aren 15 ml × Rp60 = Rp900; es 150 g × Rp1,99 = Rp299 → Rp8.351; waste 5% Rp418 | Rp8.769 | Rp22.000 | **59,6%** | Target 60%: **Rp22.200**, sedikit di atas harga sekarang |
| Es kopi susu (take-away) | Sama, ditambah cup PET Rp1.576 | Rp10.345 | Rp22.000 | 52,5% | – |

Catatan: angka harga per satuan memakai harga eceran. Begitu penawaran grosir masuk, ganti di tab Bahan, dan semua HPP ikut berubah otomatis.

### Kapan bagian back-office MoodBrew boleh dibangun

Hanya **back-office** (stok dan HPP), **tidak pernah Customer App**, dan baru dipertimbangkan setelah **minimal 6 bulan data operasi nyata**. Syaratnya, minimal satu dari ini terbukti mahal **dua bulan berturut-turut** (kriteria saya, bukan aturan board):

- admin Sheets dan rekonsiliasi lebih dari 5 jam/minggu;
- selisih stok yang tidak terjelaskan lebih dari 5% dari biaya bahan;
- waste di atas target meski SOP dijalankan;
- atau Kopiyo sudah untung dan membuka outlet kedua (board C11).

**Sebelum membangun, cek dulu** apakah paket POS yang lebih tinggi (misalnya Majoo Advance Rp499.000 atau Moka Pro Rp499.000) sudah menyelesaikan masalahnya. Biaya 12 bulan langganan itu hampir pasti lebih murah daripada membangun software.

---

## 6. Izin, pajak, dan asuransi (daftar periksa)

**Bukan nasihat hukum.** Aturan berbeda per daerah dan sering berubah. Setiap baris harus dikonfirmasi ke instansinya atau ke konsultan/akuntan. Sumber yang saling bertentangan ditulis apa adanya.

| # | Apa | Yang diketahui dari sumber | Halaman untuk konfirmasi | Kapan |
|---|---|---|---|---|
| 1 | **Bentuk usaha dan NPWP** | PPh Final 0,5% (PP 20/2026) hanya untuk orang pribadi dan PT Perorangan dengan omzet ≤Rp4,8 M/tahun. CV dan PT biasa tidak lagi berhak. Skala usaha (mikro atau kecil) juga menentukan kewajiban BPJS (bagian 3c). | [DJP: PP 20/2026](https://www.pajak.go.id/en/node/119950) | Sebelum NIB. **Tanya akuntan.** |
| 2 | **NIB lewat OSS** | Gratis. KBLI rumah minum/kafe **56303**; kedai minuman **56304**. Tambah KBLI makanan kalau perlu. **Sejak 16 Jun 2026, OSS memakai KBLI 2025 untuk pendaftaran baru** (sumber komersial). Tingkat risiko antarsumber tidak konsisten: rendah (cukup NIB) vs menengah rendah (NIB + Sertifikat Standar). | [oss.go.id](https://oss.go.id) · [kbli.co.id 56303](https://kbli.co.id/56303) · [Unpad KBLI 2025: 56304](https://dpb.unpad.ac.id/kbli2025/56304/) · [Hukumonline](https://www.hukumonline.com/klinik/a/izin-usaha-untuk-kafe-lt618ca69caa623) | Sebelum pop-up. Pop-up juga butuh identitas usaha. |
| 3 | **Sertifikat halal** | **Wajib** untuk produk makanan dan minuman usaha mikro dan kecil **sejak 18 Okt 2026**, tanpa penundaan lagi. **Jalur gratis SEHATI/*self-declare*** (kuota 2026: 1,35 juta) **kemungkinan tidak berlaku untuk kedai.** Beberapa sumber menyebut produk usaha restoran, kantin, katering, dan kedai/warung makan dikecualikan, dan ada syarat sudah berproduksi minimal 1 tahun ([Republika](https://ekonomi.republika.co.id/berita/rm06a9349/begini-caranya-ukm-bisa-self-declare-halal), [NU Online](https://nu.or.id/nasional/cara-mendapatkan-sertifikasi-halal-bagi-pengusaha-makanan-dan-minuman-Mh4vY)). Sumber lain menyebut kafe UMK bisa *self-declare* ([Smartlegal](https://smartlegal.id/perizinan/2024/05/14/restoran-dkk-juga-wajib-ada-sertifikat-halal/)). **Rencanakan jalur reguler**: tarif UMK Rp650.000 (Rp300.000 pendaftaran + Rp350.000 pemeriksaan LPH), ditambah kemungkinan biaya transport auditor ([Kontan](https://nasional.kontan.co.id/news/simak-rincian-aturan-tarif-sertifikasi-halal-bagi-umk)). **Setiap makanan titip harus punya sertifikat halal mitranya sendiri.** | [BPJPH](https://bpjph.halal.go.id/read/kabar-gembira-bpjph-buka-kuota-1-35-juta-sertifikasi-halal-gratis-2026-bagi-umk) · [SIHALAL](https://ptsp.halal.go.id) · [BPJPH: wajib Okt 2026](https://bpjph.halal.go.id/read/sambut-wajib-halal-oktober-2026-kepala-bpjph-serukan-tertib-halal-sebagai-strategi-penguatan-bisnis) | Ajukan **segera setelah NIB**, sebelum buka. Untuk pop-up, jual minuman dan makanan titip bersertifikat saja. |
| 4 | **SLHS** (Sertifikat Laik Higiene Sanitasi) | Diajukan lewat OSS sebagai PB-UMKU, dengan acuan PMK 17/2024. Butuh **sertifikat pelatihan penjamah pangan**, lolos **inspeksi kesehatan lingkungan (nilai minimal 80)**, dan biasanya uji air. Untuk restoran berisiko menengah rendah, satu dokumen menyebut SLHS paling lambat **1 tahun setelah beroperasi** (mungkin aturan lama). Satu SOP daerah (Lumajang) menyebut masa berlaku 3 tahun. Prosedur khusus DKI tidak ditemukan; Dinkes DKI sedang memprioritaskan SLHS dapur MBG. | [Kemenkes: SE percepatan SLHS](https://kemkes.go.id/id/kemenkes-terbitkan-surat-edaran-percepatan-penerbitan-slhs) · [Antara: SLHS lewat OSS](https://jatim.antaranews.com/berita/981913/kemenkes-percepat-proses-penerbitan-slhs) · [BPS: nilai IKL 80](https://sirusa.bps.go.id/metadata/variabel/331268) · [Kemenparekraf KBLI 56101 (PDF)](https://sisupar.kemenparekraf.go.id/wasdal/uploads/kbli/9.%2056101RESTORAN.pdf) | Pelatihan penjamah untuk semua staf saat pelatihan pra-buka. Tanya **Sudinkes Jakarta Timur** atau PTSP Kecamatan Pulogadung. |
| 5 | **PBJT makanan & minuman 10%** (dulu pajak restoran) | Wajib kalau omzet **>Rp42 juta/bulan**. Rencana CFO Rp72 juta/bulan, jadi wajib. Bayar dan lapor paling lambat tanggal 10 bulan berikutnya. Daftar objek pajak secara online lewat pajakonline.jakarta.go.id. **Pengecualian Rp42 juta tidak berlaku untuk penjualan insidental**, sehingga penjualan di bazar atau pop-up mungkin tetap kena pajak (tafsiran, belum dikonfirmasi). | [Bapenda: PBJT](https://bapenda.jakarta.go.id/jenis/pajak-restoran) · [Manual daftar WP online (Bapenda)](https://bapenda.jakarta.go.id/peraturan-perpajakan/unduh/manual-cara-daftar-wp-pajak-online) · [DDTC: cara daftar objek](https://news.ddtc.co.id/literasi/tips-trik/1806104/cara-daftarkan-tempat-usaha-sebagai-objek-pajak-restoran-di-jakarta) · [DDTC: lapor SPTPD](https://news.ddtc.co.id/literasi/tips-trik/1819975/cara-lapor-sptpd-untuk-pbjt-makananminuman-secara-online-di-jakarta) · [DDTC: insidental](https://news.ddtc.co.id/berita/daerah/1799846/threshold-pajak-restoran-di-dki-jakarta-naik-jadi-rp42-juta-per-bulan) | Daftar begitu omzet mendekati Rp42 juta (sekitar bulan 3 menurut ramp). Tulis "harga belum termasuk PBJT 10%" sejak hari pertama. **Pisahkan 10% omzet ke rekening terpisah setiap minggu.** |
| 6 | **BPJS Ketenagakerjaan + Kesehatan** (pemberi kerja) | Daftar sebagai pemberi kerja dengan NIB/izin usaha, NPWP, dan KTP; bisa online atau di kantor cabang. Kartu peserta terbit ±7 hari setelah iuran dibayar (satu sumber). Program wajib tergantung skala usaha (bagian 3c). | [CNN Indonesia: cara daftar](https://www.cnnindonesia.com/edukasi/20260730120122-561-1386547/cara-daftar-kepesertaan-bpjs-ketenagakerjaan-simak-tahapannya) · [BPJS TK](https://www.bpjsketenagakerjaan.go.id) · [BPJS Kesehatan](https://www.bpjs-kesehatan.go.id) | Sebelum staf mulai pelatihan. |
| 7 | **Royalti musik (LMKN)** | Kafe dan restoran yang memutar musik membayar royalti. Tarif yang paling sering disebut **Rp120.000/kursi/tahun** (Rp60.000 hak cipta + Rp60.000 hak terkait). Bayar online lewat SIDRAMA. UMKM bisa mengajukan **keringanan atau pembebasan** (mekanismenya belum seragam). | [izin.co.id: panduan 2026](https://izin.co.id/blog/cara-bayar-royalti-lagu/) · [Popbela](https://www.popbela.com/career/working-life/kafe-dan-restoran-wajib-bayar-royalti-musik-00-6sk7r-g15k6h) · [Bisnis.com: lisensi online](https://ekonomi.bisnis.com/read/20251104/12/1925904/cara-dan-syarat-urus-lisensi-musik-di-lmkn-secara-online) · [DDTC: keringanan usaha mikro](https://news.ddtc.co.id/berita/nasional/29062/tarif-royalti-musik-yang-digunakan-usaha-mikro-bakal-diringankan) | Sebelum buka. Ajukan keringanan. |
| 8 | **Papan nama / reklame** | Papan nama usaha **≤1 m²** yang menempel di bangunan dikecualikan dari pajak reklame (dengan syarat lain). Di luar itu kena pajak reklame. Perlu tidaknya izin pemasangan papan kecil **tidak ditemukan**. | [Pergub DKI 29/2024 (DDTC)](https://perpajakan.ddtc.co.id/id/sumber-hukum/peraturan-daerah/peraturan-gubernur-provinsi-dki-jakarta-29-tahun-2024) · [DDTC News](https://news.ddtc.co.id/berita/daerah/1820178/pasang-reklame-pengenal-usaha-tak-kena-pajak-perhatikan-aturan-ini) | Sebelum memesan signage. Tanya Bapenda/PTSP. |
| 9 | **Proteksi kebakaran (APAR)** | Perda DKI 8/2008 dan aturan teknisnya (Pergub 72/2021, Permenaker 04/1980) mengatur APAR: mudah dilihat, mudah dijangkau, sesuai kelas kebakaran. **Jumlah dan jenis untuk kafe kecil tidak ditemukan.** | [ESDM: penempatan APAR](https://www.esdm.go.id/id/berita-unit/direktorat-jenderal-minyak-dan-gas-bumi/tingkatkan-kesiagaan-ditjen-migas-gelar-pelatihan-apar) · [Katadata: Gempar, Perda 8/2008](https://katadata.co.id/amp/info/691c13804738c/tangani-kebakaran-jakarta-punya-gempar-dan-pos-damkar-baru/) | Tanya Dinas Gulkarmat DKI saat fit-out. Dapur dengan LPG minimal 1 APAR di dekat kompor (praktik umum, belum dikonfirmasi). |
| 10 | **Bangunan dan sewa** | Pastikan fungsi bangunan ruko (PBG/IMB) membolehkan usaha makanan dan minuman, dan pemilik mengizinkan F&B, gas, exhaust, dan papan nama. | Tanya PTSP dan minta salinan dokumen dari pemilik | Sebelum tanda tangan sewa (bagian 7). |
| 11 | **Ketenagakerjaan** | Kontrak kerja tertulis, upah ≥UMP (bagian 3c), lembur dengan persetujuan tertulis, kewajiban kerja malam perempuan, THR. | Konsultan atau Sudinakertrans Jakarta Timur | Sebelum rekrut. |
| 12 | **QRIS** | Daftar merchant lewat bank atau penyedia POS. Kategori UMI vs usaha kecil menentukan MDR di atas Rp100.000. | [BI: MDR QRIS](https://www.bi.go.id/id/publikasi/ruang-media/cerita-bi/Pages/mdr-qris.aspx) | Sebelum pop-up. |
| 13 | **Asuransi** (tidak wajib, disarankan) | Tarif asuransi kebakaran menurut kelas risiko OJK: rendah 0,05–0,10%, sedang 0,10–0,20%, tinggi 0,20–0,35% dari nilai pertanggungan, ditambah PPN dan biaya admin. Contoh produk ruko (Simas Ruko): premi minimum Rp200.000; **stok bahan mudah terbakar tidak dijamin**. Asuransi mikro BRI Insurance Rp40.000/tahun dengan santunan ±Rp5 juta (terlalu kecil untuk isi kafe). | [IDX Channel: tarif OJK](https://www.idxchannel.com/milenomic/jangan-asal-punya-poperti-begini-cara-menghitung-premi-asuransi-rumah/all) · [Sinarmas: RIPLAY Simas Ruko](https://www.sinarmas.co.id/property/9622093/RIPLAY-Umum-Simas-Ruko.pdf) · [Jawa Pos: asuransi mikro](https://www.jawapos.com/ekonomi/2307200182/mulai-rp-40-ribu-per-tahun-brins-sediakan-asuransi-mikro-kerusakan-tempat-usaha-bagi-umkm) | Minta 2–3 penawaran sebelum buka, untuk isi kedai, fit-out, dan alat. |

**Urutan yang disarankan:**

1. Bentuk usaha dan NPWP (akuntan).
2. NIB.
3. QRIS dan POS gratis.
4. Pop-up.
5. Halal (reguler) diajukan.
6. Sewa ditandatangani.
7. BPJS dan kontrak staf.
8. Pelatihan penjamah dan pelatihan pra-buka.
9. LMKN.
10. Buka.
11. Daftar PBJT saat omzet mendekati Rp42 juta.
12. SLHS selesai secepatnya, paling lambat sesuai batas yang berlaku.

---

## 7. Checklist memilih tempat

Isi checklist ini untuk setiap calon tempat. Angka ambang di bawah adalah **usulan saya [estimasi]**; sesuaikan dengan data pop-up.

| # | Kriteria | Cara cek | Lulus kalau |
|---|---|---|---|
| 1 | **Parkir motor** | Hitung slot motor legal dalam 50 m pada Jumat pukul 19.00. Tanya pemilik soal juru parkir dan tarifnya. | ≥15 motor tanpa memakan trotoar atau mengganggu tetangga. Ada titik turun ojol. Parkir adalah keluhan nomor 3 di kompetitor (`competitors.md`). |
| 2 | **Keramaian malam** | Hitung orang dan motor yang lewat dan melambat selama 30 menit pada Selasa dan Jumat, pukul 18.00–21.00. Catat usaha tetangga yang buka sampai malam. | Jalan hidup sampai ±22.00 (warung, minimarket, kos). Bukan jalan gelap dan sepi. |
| 3 | **Dekat TransJakarta / koridor Jl. Pemuda** | Jalan kaki dari halte. Halte **Pemuda Rawamangun** (Koridor 4) di Jl. Pemuda terhubung dengan **LRT Velodrome** lewat jembatan ([Wikipedia](https://en.wikipedia.org/wiki/Pemuda_Rawamangun_(Transjakarta)), [Merah Putih](https://www.merahputih.com/post/read/lrt-stasiun-velodrome-resmi-terintegrasi-dengan-transjakarta-halte-pemuda)). | ≤10 menit jalan kaki dari halte atau stasiun. |
| 4 | **Kebisingan** | Duduk di dalam pukul 19.00 dan coba ngobrol dengan suara normal. Cek tetangga (karaoke, bengkel). Tanya RT/RW apakah buka sampai 24.00 akan dikeluhkan warga. | Ngobrol nyaman tanpa menaikkan suara. Tidak ada tetangga rumah tinggal yang menempel dinding. |
| 5 | **Daya listrik ≥6.600 VA** | Lihat meteran dan rekening PLN. Beban kasar [estimasi, cek ke teknisi]: 2 kettle, chiller, freezer, 2 AC, griddle, grinder, lampu, RO. | **Sudah ≥6.600 VA (golongan B-2)**, atau pemilik mengizinkan dan menanggung tambah daya. Di atas 5.500 VA harus diajukan langsung ke PLN; biaya dan waktunya belum diketahui. |
| 6 | **Air** | Cek sambungan PAM (bukan hanya sumur), tekanan air, saluran buang, dan kemungkinan memasang penangkap lemak. | Air PAM tersedia (dibutuhkan untuk RO, wastafel, uji air SLHS). Saluran tidak mampet. |
| 7 | **Pemilik mengizinkan F&B** | Tulis di kontrak: usaha kafe, kompor LPG, exhaust, papan nama di fasad, jam operasi sampai 01.00, renovasi. Minta salinan sertifikat dan PBG/IMB. | Semua tertulis. Fungsi bangunan sesuai usaha. Pemilik adalah pemilik sah. |
| 8 | **Sewa dibayar tahunan** | Hitung kas: sewa setahun di muka + deposit Rp25–75 juta (`cost-inputs.md` §1). Negosiasikan pembayaran 6 bulanan, opsi perpanjangan dengan batas kenaikan, dan syarat pengembalian deposit. | Total kas awal masuk anggaran founder (CFO: ±Rp292–376 juta dengan sewa setahun di muka). **Hindari kontrak 3 tahun dibayar di muka sebelum pop-up membuktikan permintaan.** |
| 9 | **Ukuran dan tata letak** | Ukur lantai dasar. Bar harus terlihat dari pintu. Ada toilet, gudang kecil, dan tempat dapur sederhana. | Cukup untuk 24–30 kursi di lantai dasar. Tamu bisa melihat V60 diseduh. |
| 10 | **Riwayat banjir dan keamanan** | Tanya tetangga dan RT soal banjir musim hujan (Nov–Feb) dan pencurian. | Tidak ada riwayat banjir masuk bangunan. |
| 11 | **Jarak dari pesaing** | Petakan jarak ke Hulu Coffee dan Pukul Satu Kopi (`competitors.md`). | Tidak bersebelahan dengan kafe WFC besar yang menarik orang berlaptop. |

---

## 8. Kit pop-up (untuk uji sebelum sewa, syarat board C8)

**Format yang disarankan: "ambil alih malam".** Pakai tempat di Rawamangun yang tutup sore (kafe siang, toko roti, toko buku, galeri, atau warung makan yang sepi malam) untuk menjalankan Kopiyo pukul 18.00–23.00, dengan meja tanpa laptop. Format ini menguji konsep yang persis (sepulang kerja, duduk, ngobrol) lebih baik daripada booth bazar.

**Peralatan.** Semua bisa dibawa ke kedai nanti; ini adalah paket A milik CFO.

| Barang | Jumlah | Harga | Sumber |
|---|---|---|---|
| Grinder Latina 600N | 1 | Rp3,79–4,04 juta | [Tokopedia](https://www.tokopedia.com/find/grinder-latina-600n) |
| Kettle Timemore Fish Smart | 2 | Rp1,22–1,35 juta/unit | [Tokopedia](https://www.tokopedia.com/find/timemore-fish-smart-kettle) |
| Dripper V60 02 | 3 | Rp136.550–160.000/unit | [Tokopedia](https://www.tokopedia.com/find/hario-v60-dripper-02?page=2) |
| Timbangan Timemore Basic 2 | 2 | Rp645.000–695.000/unit | [Tokopedia](https://www.tokopedia.com/find/timemore-black-mirror-basic-2) |
| **Subtotal alat** | | **±Rp7,9–8,6 juta** *(hitungan)* | |
| Filter V60 | 200 lembar | Rp170.000 | [Otten](https://ottencoffee.co.id/filters/hario-paper-filter-vcf-02-100w) |
| Konsentrat cold brew (diseduh di rumah atau dapur tuan rumah sehari sebelumnya), botol 1 L, cooler box | – | Bahan sesuai HPP | SOP-03 |
| Es kristal | 10–20 kg/sesi | Rp9.950/5 kg | [CoolFresh](https://www.tokopedia.com/espugautama/es-batu-kristal-jakarta-timur-100-halal-5kg) |
| Cup PET 14 oz / paper cup 8 oz (kalau tuan rumah tidak punya gelas) | – | Rp730–1.576/set; ±Rp565–700/set | bagian 2c |
| Meja lipat sebagai bar portabel, taplak, server, termos air panas cadangan | 1 set | **Pinjam dari tuan rumah, atau minta penawaran** | – |
| POS gratis + **QRIS statis cetak** | – | Gratis | bagian 5 |
| Papan "HP boleh, laptop tidak", papan menu, kartu beans, formulir daftar WhatsApp | – | Cetak lokal [estimasi kecil] | – |
| Higiene: jeriken air cuci tangan, sabun, sanitizer, lap, kantong sampah | – | [estimasi kecil] | – |

**Listrik:**

- Dua kettle listrik adalah beban terbesar. Daya kettle tidak saya temukan; cek label (kettle gooseneck listrik umumnya ±1.000–1.200 W [estimasi]).
- **Minta tuan rumah menyediakan 2 stopkontak di sirkuit berbeda.**
- Alternatif tanpa listrik: kompor gas portabel + kettle gooseneck kompor + termometer.
- *Power station* seperti EcoFlow Delta 2 (1.024 Wh/1.800 W, tercantum Rp10,79 juta di Tokopedia resmi, tanggal tidak jelas; [Tokopedia](https://www.tokopedia.com/ecoflow-id/ecoflow-delta-2-1024wh-1800w-power-station-solar-generator-lfp-camping-genset-baterai-pembangkit-listrik-hybrid-dan-offgrid-berdaya-besar-untuk-rumah-camping-bis-rv-van-1731625066755687659)) **tidak disarankan** untuk uji: mahal dan tidak kuat menyalakan dua kettle semalaman.
- Genset sewa berisik, butuh operator, dan biasanya minimal sewa 3 hari menurut sumber lama ([detikFinance](https://finance.detik.com/energi/d-3345073/pln-punya-i-power-bank-i-segede-mobil)). Itu bertentangan dengan suasana ngobrol.

**Pilihan kesepakatan dengan tuan rumah.** Tarif sewa booth dan persentase bagi hasil untuk pop-up **tidak ditemukan** di sumber publik; semua harus dinegosiasikan.

| Opsi | Cara | Cocok kalau |
|---|---|---|
| A. Sewa tetap per sesi | Kopiyo membayar biaya tetap per malam, semua penjualan milik Kopiyo | Tempat sudah ramai, tuan rumah mau pasti |
| B. Bagi hasil % dari penjualan Kopiyo | Tuan rumah mendapat persentase omzet Kopiyo. Usulan saya untuk membuka negosiasi 10–15% (**bukan angka pasar**) | Tempat tutup malam: tuan rumah dapat uang dari jam yang kosong |
| C. Saling jual | Tuan rumah menjual makanannya, Kopiyo menjual minuman, masing-masing menyimpan omzetnya sendiri | Tuan rumah adalah warung atau toko roti. Sekaligus menguji kombinasi kopi + makanan tanpa titip jual. |
| D. Barter | Gratis. Tuan rumah mendapat promosi dan trafik baru | Tempat baru atau komunitas (toko buku, galeri) |

**Izin dan kewajiban untuk pop-up** (konfirmasi masing-masing):

1. **Perjanjian tertulis dengan tuan rumah:** tanggal, jam, listrik dan air, bagi hasil, kebersihan, kerusakan, siapa yang menanggung royalti musik (sebaiknya tuan rumah, kalau musiknya milik mereka), parkir.
2. **NIB Kopiyo** (gratis) dan QRIS atas nama usaha.
3. **Halal:** sejak 18 Okt 2026 produk makanan dan minuman UMK wajib bersertifikat. Ajukan secepatnya. Untuk pop-up, makanan hanya dari mitra yang sudah bersertifikat (atau makanan tuan rumah, opsi C).
4. **PBJT:** pengecualian Rp42 juta/bulan tidak berlaku untuk penjualan insidental. Tanyakan ke Bapenda apakah pop-up beberapa malam termasuk insidental, dan apakah tuan rumah yang sudah terdaftar PBJT memungut pajak atas penjualan di tempatnya. Kalau ragu, tulis "harga belum termasuk PBJT 10%".
5. Kalau di ruang publik (bukan di dalam tempat usaha tuan rumah): izin dari pengelola atau kelurahan. Tidak saya teliti; **hindari di uji pertama.**

**Kriteria tuan rumah:**

- di Rawamangun, dekat Jl. Pemuda atau TransJakarta;
- 16–24 kursi;
- kosong atau tutup pukul 18.00–23.00;
- bukan tempat yang ramai orang berlaptop, dan mau aturan "tanpa laptop" selama sesi;
- 2 stopkontak, air, toilet, parkir motor.

**Yang diukur di setiap sesi** (untuk `/founder-launch`):

- tamu per sesi;
- % es kopi susu vs V60;
- **% es kopi susu ≤3 menit** (stopwatch, SOP-03);
- pengambilan Cicip Dulu dan berapa yang lanjut membeli;
- belanja per tamu;
- lama duduk;
- % gelas kedua dan % pesan makanan;
- kejadian laptop;
- jumlah nomor WhatsApp yang didapat dan **% yang kembali dalam 14 hari**;
- waktu tugas nyata, untuk mengganti estimasi beban kerja di bagian 3a;
- uji harga dari `pricing.md` (V60 Rp25.000 vs Rp28.000; Sesi Rp75.000 vs Rp95.000).

---

## 9. Daftar risiko (10 yang paling mungkin)

| # | Risiko | Kemungkinan | Dampak | Tanda awal | Rencana: cegah / saat terjadi |
|---|---|:-:|:-:|---|---|
| 1 | **Barista utama keluar** | Sedang | Tinggi | Sering telat, mengeluh jadwal, tawaran dari kafe lain | **Cegah:** resep tertulis dan ditimbang (SOP-04) supaya rasa tidak bergantung pada satu orang; minimal 2 orang bisa V60 (B2, lalu H di bulan 3); jadwal adil dan makan staf; masa pemberitahuan di kontrak. **Saat terjadi:** founder atau B2 mengambil alih bar; panggil barista lepas dari daftar cadangan; menu sementara 2 beans; rekrut dengan masa tumpang tindih 1–2 minggu. |
| 2 | **Beans habis atau tanggal sangrai terlalu tua** | Sedang | Sedang–Tinggi (pecinta kopi pergi) | Stok di bawah par, roaster telat konfirmasi | **Cegah:** par level di Sheets (SOP-09), 2 roaster (utama + cadangan), pesan setiap Senin, jendela 7–30 hari, tanggal sangrai tertulis di kartu beans. **Saat terjadi:** beli dari Otten atau Tokopedia dengan kurir instan dalam kota; kurangi ke 2 beans; jangan pernah menyajikan beans >30 hari. |
| 3 | **"3 menit" gagal saat ramai pukul 19.00** | **Tinggi** (4 pembeli panel sudah meragukannya) | Tinggi (janji pertama yang dirasakan tamu) | Log SOP-03 di bawah 90% ≤3 menit | **Cegah:** base kopi susu dicampur pukul 18.30; jalur cepat terpisah dari V60 dan dipegang host; es kopi susu menyalip antrean; orang ke-3 di jam ramai mulai bulan 5; uji di pop-up dengan stopwatch. **Saat terjadi:** jujur ke tamu; kalau lebih dari 2 kali seminggu, tambah shift R. Kalau tetap gagal, ubah janji di pitch ("cepat") sebelum review buruk menulisnya. |
| 4 | **Mitra makanan titip tidak andal** | Sedang | Sedang | Telat antar, porsi berubah, tagihan tidak sesuai | **Cegah:** hanya rice bowl yang dititip (bagian 2d); perjanjian tertulis; 2 calon mitra yang sudah lolos uji rasa; cek setiap pengiriman pukul 15.30. **Saat terjadi:** tulis "rice bowl habis hari ini"; roti bakar, pisang goreng, dan mie tetap jalan karena dibuat sendiri; aktifkan mitra cadangan. |
| 5 | **Listrik atau air mati** | Sedang (musim hujan Nov–Feb) | Sedang | Pemberitahuan PLN/PAM, hujan deras | **Cegah:** QRIS statis cetak (POS mati tetap bisa bayar), POS di HP + hotspot, lampu darurat, stok 5–10 galon air, kompor gas + kettle kompor sebagai cadangan kettle listrik. **Saat terjadi:** menu darurat (konsentrat + V60 dengan kettle kompor); susu yang lebih dari 2 jam tidak dingin dibuang [aturan internal]; catat suhu chiller; kalau lebih dari 2 jam, tutup dapur dan beri tahu tamu dengan jujur. |
| 6 | **Ulasan buruk** | **Tinggi** (tempat baru, sedikit ulasan) | Sedang (masalah reputasi adalah keberatan utama panel) | Rating Google turun, keluhan di log berulang | **Cegah:** SOP-02 dan SOP-07, log keluhan ditinjau setiap Minggu, minta tamu yang puas menulis ulasan. **Saat terjadi:** founder membalas dalam 24 jam, perbaiki akar masalahnya, undang kembali. Jangan berdebat di publik. |
| 7 | **Kejutan PBJT atau pajak** | Sedang | Tinggi (10% omzet) | Omzet bulanan mendekati Rp42 juta; surat dari Bapenda | **Cegah:** "harga belum termasuk PBJT 10%" di menu sejak hari pertama; daftar sebelum melewati ambang; sisihkan 10% omzet setiap minggu; PPh Final 0,5% bulanan; akuntan memeriksa bentuk usaha (PP 20/2026). **Saat terjadi:** bayar dan lapor sebelum tanggal 10; minta akuntan menghitung tunggakan. |
| 8 | **Konflik dengan tamu berlaptop** | **Tinggi** (budaya WFC di Rawamangun, `competitors.md`) | Rendah–Sedang (satu ulasan marah) | Orang datang membawa tas laptop dan bertanya soal colokan | **Cegah:** aturan di pintu, Google Maps, dan konfirmasi reservasi; tidak menyediakan colokan di meja. **Saat terjadi:** SOP-06: pelan, pribadi, tawarkan take-away atau pengembalian uang; jangan mempermalukan. |
| 9 | **Bulan sepi lebih lama dari ramp** | **Tinggi** (ramp CFO masih tebakan) | Tinggi (kas) | Rata-rata 7 hari di bawah ramp 2 minggu berturut-turut | **Cegah:** uji pop-up dulu; cadangan kas minimal 3 bulan biaya tetap; mulai tanpa paruh waktu. **Saat terjadi:** tunda shift R; founder mengambil lebih banyak shift; dorong Sesi Ngobrol untuk kantor sekitar dan Kamis Seduh Bareng; jangan memotong waktu seduh atau kualitas (peringatan board). Evaluasi jam buka Senin–Selasa hanya dengan data. |
| 10 | **Masalah dengan pemilik ruko** | Sedang | Tinggi | Pemilik menunda dokumen, menolak papan nama atau tambah daya | **Cegah:** checklist bagian 7; kontrak notaris yang mencantumkan izin F&B, jam buka, papan nama, tambah daya, perpanjangan dengan batas kenaikan, pengembalian deposit; cek kepemilikan sah. **Saat terjadi:** rujuk kontrak; siapkan calon tempat kedua dari hasil survei; jangan menambah renovasi sebelum masalah selesai. |

---

## 10. Pertanyaan terbuka (hanya jawaban nyata yang bisa menutupnya)

1. **Harga grosir beans:** daftar harga B2B, minimum order, jadwal sangrai, lead time, dan tempo pembayaran dari Otten (tim B2B), Murrell, Sakha, Anomali. Cek juga apakah Viverri (Rawamangun) masih beroperasi.
2. **Susu foodservice:** penawaran distributor Greenfields/Diamond per karton. Apakah bisa di bawah Rp23/ml (indikasi B2B lama ±Rp19,9/ml)?
3. **Mitra rice bowl:** 3 calon mitra, harga mitra, bagian Kopiyo, sertifikat halal, kemampuan mengantar harian pukul 15.30. Juga harga pisang kepok di Pasar Induk Kramat Jati.
4. **Demo POS:** Majoo Starter (resep, QRIS, *open bill*, ekspor), Qasir Pro (QRIS?), Moka Basic (bahan baku ada atau tidak di Basic?).
5. **Halal:** apakah kedai seperti Kopiyo bisa memakai *self-declare*/SEHATI, atau wajib reguler? Tanyakan ke PTSP Halal atau pendamping PPH. Berapa biaya total jalur reguler di Jakarta?
6. **SLHS di DKI:** langkah, penyedia pelatihan penjamah pangan dan biayanya, biaya uji air, dan batas waktu untuk kafe baru. Tanyakan ke Sudinkes Jakarta Timur atau PTSP Kecamatan Pulogadung.
7. **KBLI** yang tepat di KBLI 2025 (56303 vs 56304, dan perlu tidaknya KBLI makanan) serta tingkat risikonya di OSS.
8. **Akuntan:**
   - bentuk usaha (orang pribadi vs PT Perorangan) dan dampaknya ke PPh;
   - skala usaha (mikro atau kecil) dan program BPJS yang wajib (JP?);
   - status pengecualian UMP untuk usaha mikro/kecil setelah PP 49/2025;
   - kewajiban pelaporan ketenagakerjaan lain.
9. **LMKN:** tarif pasti untuk 24–30 kursi dan cara mengajukan keringanan UMKM.
10. **Pest control dan asuransi:** 2–3 penawaran tertulis masing-masing.
11. **Calon tempat:** daya terpasang, biaya dan waktu tambah daya PLN di atas 5.500 VA, PBG/IMB, riwayat banjir.
12. **APAR:** jumlah dan jenis untuk kafe kecil dengan LPG (Dinas Gulkarmat DKI).
13. **Pop-up:** tuan rumah, bentuk kesepakatan, dan status PBJT untuk penjualan insidental (Bapenda).
14. **Transport pulang malam:** jenis kelamin staf penutup, tarif ojek untuk rute pulang staf, atau opsi antar-jemput lain. Harga makan staf per shift.
15. **Daya kettle** untuk kebutuhan listrik pop-up (label alat).
16. **Tim (board C10):** siapa barista utamanya dan berapa gajinya (pasar Rp3,3–7,5 juta, `cost-inputs.md` §2; barista berpengalaman mungkin minta tunjangan di atas UMP). Apa pengalaman F&B founder?

---

## 11. Perubahan angka untuk CFO

Saya **tidak** mengubah `numbers.json` atau `numbers-lean.json`. CFO perlu menjalankan ulang alat dengan perubahan di bawah. Hitungan break-even di kolom catatan **kasar**, hanya untuk menunjukkan arah. Angka resminya dari alat CFO.

### A. Angka yang sebaiknya diubah atau ditambahkan

| # | Item | Angka lama (`numbers.json`) | Angka baru | Sumber | Catatan |
|---|---|---|---|---|---|
| 1 | **Royalti musik LMKN** (biaya tetap baru) | Tidak ada | **Rp300.000/bulan** (30 kursi × Rp120.000/tahun ÷ 12). Ramping (24 kursi): **Rp240.000/bulan** | [izin.co.id](https://izin.co.id/blog/cara-bayar-royalti-lagu/) · [Popbela](https://www.popbela.com/career/working-life/kafe-dan-restoran-wajib-bayar-royalti-musik-00-6sk7r-g15k6h) | Bisa turun kalau keringanan UMKM disetujui ([DDTC](https://news.ddtc.co.id/berita/nasional/29062/tarif-royalti-musik-yang-digunakan-usaha-mikro-bakal-diringankan)). |
| 2 | **Paruh waktu jam ramai** (biaya tetap baru, **mulai bulan 5**) | Tidak ada (3 staf) | Dasar: **±Rp2,38 juta/bulan** (3 shift × 4 jam × Rp45.475 × 52/12, ditambah BPJS minimal). Kalau 4 shift: ±Rp3,15 juta. Ramping: **±Rp1,58 juta/bulan** (2 shift) | PP 36/2021 Pasal 16: upah per jam ≥ upah sebulan ÷ 126 ([Bisnis.com](https://ekonomi.bisnis.com/read/20210302/12/1362701/kemenaker-tegaskan-upah-per-jam-hanya-untuk-pekerja-paruh-waktu), [Gadjian](https://www.gadjian.com/blog/2023/02/23/cara-menghitung-gaji-karyawan-part-time/)); UMP Rp5.729.876 | Tanpa ini, rencana dasar hanya punya 2 orang di jam ramai (bagian 3a, 3e). Alat CFO tidak bisa memodelkan biaya tetap yang naik di tengah tahun; pakai skenario terpisah atau tambahkan penuh agar konservatif. |
| 3 | **Gaji pelatihan sebelum buka** (startup baru) | Tidak ada | Dasar **±Rp10,2 juta** (3 staf × ½ bulan × Rp6.794.105). Ramping **±Rp6,8 juta** | *(hitungan)* dari angka gaji CFO (`cfo-sources.md`) | 2 minggu pelatihan dan malam uji (bagian 3g). |
| 4 | **Makan staf + antar-jemput pulang malam** (biaya tetap baru) | Tidak ada | **[estimasi] ±Rp2,2–2,8 juta/bulan** kalau semua staf penutup perempuan: makan ±Rp0,9 juta (±2 staf × 30 malam × Rp15.000 [estimasi]) + transport ±Rp1,3–1,9 juta (±2 staf × 30 malam × Rp20.000–30.000 [estimasi tarif ojek]). Lebih rendah kalau sebagian staf laki-laki dan pulang sendiri (makan staf tetap disarankan untuk retensi). | Kewajiban: UU 13/2003 Pasal 76 ([Hukumonline](https://www.hukumonline.com/klinik/a/aturan-lembur-untuk-pekerja-perempuan-lt50eb906629072), [Talenta](https://www.talenta.co/blog/aturan-shift-malam-perempuan/)). Besarannya **estimasi** | Status pasal setelah UU Cipta Kerja perlu dicek. |
| 5 | **Cicip Dulu**: ubah dari variabel ke tetap | Rp300/tamu (30% tamu × Rp1.000) [estimasi] | **±Rp29.100/hari ≈ Rp873.000/bulan, tetap**: 2 teko cicip/hari × 3 beans × (10 g × Rp400 + filter Rp850). Hapus Rp300 dari biaya variabel. | *(hitungan)* dari harga beans Rp400/g dan filter Rp850 (`cost-inputs.md`, [Otten](https://ottencoffee.co.id/filters/hario-paper-filter-vcf-02-100w)); resep SOP-04 | Teko cicip dibuang setelah 60 menit, berapa pun tamunya. Di 60 tamu/hari setara ±Rp485/tamu; di bulan 1 jauh lebih tinggi per tamu. |
| 6 | **HPP makanan** (uji sensitivitas wajib) | Rp7.600/porsi (38%), jadi Rp4.560/tamu [estimasi] | **±49% (±Rp5.880/tamu)** kalau hanya rice bowl dititip dan sisanya dibuat sendiri. **±70% (±Rp8.400/tamu)** kalau semua makanan dititip dengan bagian Kopiyo 30% | Roti tawar 15 lembar Rp21.000 ([Kontan](https://momsmoney.kontan.co.id/news/promo-indomaret-harga-spesial-16-29-juni-2026-nugget-skincare-diskon-hingga-30)); Indomie Rp16.000/5 ([Kontan](https://momsmoney.kontan.co.id/news/katalog-promo-alfamart-gantung-spesial-idul-adha-periode-26-mei-2-juni-2026-1)); komisi titip jual umum 20–60% ([Gramedia](https://www.gramedia.com/best-seller/?p=26130)). Porsi pesanan, topping, dan bagian titip = **[estimasi]** | Kasar: kontribusi turun ke ±Rp22.270 (break-even ±59/hari) atau ±Rp19.750 (±67/hari). Ganti dengan nota mitra nyata. |
| 7 | **POS** | Moka Basic Rp299.000/bulan | **Majoo Starter Rp249.000 + PPN/bulan** (minimal 12 bulan; resep dan QRIS termasuk), atau Qasir Pro Rp699.000/tahun (≈Rp58.250/bulan) | [majoo.id/harga](https://majoo.id/harga) · [majoo FAQ](https://majoo.id/faq) · [qasir.id](https://www.qasir.id/en/pricing) | Moka Basic mungkin tanpa bahan baku; Moka Pro Rp499.000 ([HashMicro](https://www.hashmicro.com/id/blog/review-aplikasi-moka-pos/)). Selisihnya kecil, keputusan setelah demo. |
| 8 | **Asuransi kebakaran** (biaya tetap baru, disarankan) | Tidak ada | **±Rp30.000–52.000/bulan** *(hitungan)*: isi kedai, fit-out, dan alat ±Rp160 juta × 0,20–0,35%/tahun + PPN 11% | Tarif OJK per kelas risiko ([IDX Channel](https://www.idxchannel.com/milenomic/jangan-asal-punya-poperti-begini-cara-menghitung-premi-asuransi-rumah/all)) | Minta penawaran nyata. |

### B. Angka yang diperiksa dan **tidak perlu diubah sekarang**

| Item | Angka lama | Temuan | Sumber | Keputusan |
|---|---|---|---|---|
| Gula aren + es per es kopi susu | Rp700 [estimasi] | ±Rp1.200 (15 ml × Rp60 + 150 g × Rp1,99). Tapi konsentrat cold brew memakai ±16,7 g kopi, bukan 18 g (−Rp342). **Bersih ±+Rp160 per gelas.** | [Mahorahora](https://www.tokopedia.com/find/gula-aren-mahorahora-cair) · [CoolFresh](https://www.tokopedia.com/espugautama/es-batu-kristal-jakarta-timur-100-halal-5kg) | Abaikan; ubah hanya kalau CFO ingin presisi. |
| BPJS pemberi kerja | 10,24% (termasuk JP 2%) | Bisa 8,24% (usaha kecil: JP tidak wajib) atau sekitar 4,54% (mikro: JKK + JKM + Kesehatan), hemat sampai ±Rp114.600/staf/bulan | [Hukumonline (Perpres 109/2013)](https://www.hukumonline.com/berita/a/3-regulasi-ini-perlu-dibenahi-agar-selaras-sjsn-lt582fda8100641/) | **Jangan diubah sebelum akuntan memastikan skala usaha dan aturan terbaru.** |
| Susu | Rp23/ml (ritel) | Indikasi B2B Rp19,9/ml (Greenfields 12 × 1 L Rp239.000, **data Sep 2024**) | [Indotrading](https://en.indotrading.com/jayautamasantikah/greenfields-uht-low-p587935.aspx) | Tunggu penawaran distributor. |
| Gas LPG | Rp400.000/bulan [estimasi] | Bright Gas 12 kg Rp218.000 (agen Jawa, 15 Agu 2026), sekitar Rp245.000 di pangkalan. Setara ±1,6–1,8 tabung | [Bisnis.com](https://ekonomi.bisnis.com/read/20260815/44/1996598/pertamina-turunkan-harga-bright-gas-ini-rinciannya) · [CNBC](https://cnbcindonesia.com/news/20260803130310-4-756048/resmi-harga-lpg-3-kg-55-12-kg-di-agen-pangkalan-per-3-agustus-2026) | Wajar, tetap. |
| Perizinan | Rp3.000.000 [estimasi] | Halal reguler UMK resmi Rp650.000 (+ kemungkinan biaya auditor); pelatihan penjamah dan uji air belum diketahui | [Kontan](https://nasional.kontan.co.id/news/simak-rincian-aturan-tarif-sertifikasi-halal-bagi-umk) | Kemungkinan cukup; cek setelah penawaran SLHS. |
| QRIS | 0% | 0% untuk ≤Rp100.000; 0,7% untuk transaksi >Rp100.000 kalau masuk kategori usaha kecil (tagihan meja grup) | [BI](https://www.bi.go.id/id/publikasi/ruang-media/cerita-bi/Pages/mdr-qris.aspx) | Dampak kecil, tetap 0%. |
| Lembur kalau persiapan mulai 14.00 | – | Rp49.681 per jam pertama lembur (1,5 × Rp33.121), hanya di hari terima barang | [Hukumonline](https://www.hukumonline.com/klinik/a/cara-hitung-upah-lembur-per-jam-ini-rumusnya!-lt4b7e3965556d3/) | Kecil (±Rp0,4 juta/bulan kalau 2 kali seminggu); masuk pos perawatan atau founder yang menerima barang. |

**Langkah berikutnya:** CFO menjalankan ulang `numbers.json` dan `numbers-lean.json` dengan bagian A, lalu lanjut ke `/founder-launch`, yang memakai kit pop-up di bagian 8 dan daftar ukur di akhir bagian itu.
