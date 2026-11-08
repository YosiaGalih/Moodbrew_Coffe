# Sumber angka CFO: Kopiyo

Setiap angka di `founder/numbers.json` ada di sini, dengan asalnya. Urutan kepercayaan:

1. Penawaran atau invoice founder sendiri: **belum ada satu pun.**
2. Harga publik dengan tautan, terutama dari `founder/research/cost-inputs.md` (riset 8 Nov 2026).
3. **[Estimasi]**: perkiraan saya, dengan alasannya. Bukan fakta.

Semua angka dalam Rupiah. Alat CFO mencetak `$`, artinya Rp.

## Harga dan belanja per tamu

| Input | Nilai | Asal |
|---|---:|---|
| Es kopi susu | 22.000 | `founder/pricing.md` (rekomendasi) |
| V60 single origin | 25.000 | `founder/pricing.md` |
| Rata-rata minuman pertama | 23.500 | Campuran 50/50 **[estimasi campuran]** |
| Gelas kedua | 15.000 × 30% tamu | Offer v2; porsi 30% **[estimasi]**. Panel: 1,3 gelas per tamu diasumsikan |
| Makanan | rata-rata 20.000 × 60% tamu | Menu Rp15.000–28.000 (offer v2). Porsi 60% **[estimasi]**: keberatan "lapar" sangat dominan di panel |
| **Belanja per tamu** | **40.000** | 23.500 + 4.500 + 12.000 |

## Biaya variabel

| Input | Nilai | Asal |
|---|---:|---|
| Biji kopi filter (single origin, 1 kg) | Rp400/g | [Otten](https://ottencoffee.co.id/coffee-beans/kopi-arabica-gayo-atu-lintang), [Murrell](https://www.tokopedia.com/murrell-coffee/etalase/kemasan-1-kilogram); median sekitar Rp407/g |
| Biji kopi house blend (kopi susu) | Rp263/g | Tengah rentang Rp246–281/g ([Otten](https://ottencoffee.co.id/categories/coffee-beans)) |
| Dosis | V60 15 g, kopi susu 18 g | **[Estimasi]**, dosis umum |
| Susu UHT | Rp23/ml × 120 ml | [Klik Indomaret](https://www.klikindomaret.com/xpress/uht-milk-5), [Alfamart/Kontan](https://momsmoney.kontan.co.id/news/katalog-promo-alfamart-gantung-gajian-untung-periode-25-31-agustus-2026). Harga ritel; harga grosir bisa lebih murah |
| Filter V60 | Rp850/lembar | [Otten Hario VCF-02-100W](https://ottencoffee.co.id/filters/hario-paper-filter-vcf-02-100w) |
| Cup take-away es (PET 14 oz + tutup) | Rp1.600/set × 20% gelas | [Tokopedia PET 14 oz](https://www.tokopedia.com/find/cup-pet-14-oz-starindo). Porsi 20% **[estimasi]** |
| Gula aren + es | Rp700 per gelas kopi susu | **[Estimasi]** |
| Air RO/galon | Rp200/gelas | **[Estimasi]** |
| Waste 5% dari bahan | ±Rp400 | **[Estimasi]** |
| HPP makanan | ±38% dari harga jual | **[Estimasi]**. Rice bowl titip dari UMKM lokal (margin titip ±30%); roti bakar, pisang goreng, mie dibuat sendiri. Perlu harga supplier nyata (`/founder-ops`) |
| Cicip Dulu | 30% tamu × Rp1.000 | **[Estimasi]**: 3 tegukan dari seduhan yang sudah ada |
| Garansi seduh ulang | 5% klaim × 50% V60 × Rp6.850 | Biaya seduh ulang = 15 g × Rp400 + filter Rp850. Tingkat klaim 5% **[estimasi]**. Uji sensitivitas klaim 20% ada di `founder/offer.md` |
| Kartu beans | Rp400 × 50% tamu | **[Estimasi]** cetak digital |
| PPh Final UMKM | 0,5% dari omzet | [DJP](https://www.pajak.go.id/en/node/119950). Untuk wajib pajak orang pribadi, Rp500 juta omzet pertama per tahun bebas; dimasukkan penuh agar konservatif |
| QRIS | 0% untuk transaksi ≤ Rp100.000 | [Bank Indonesia](https://www.bi.go.id/id/publikasi/ruang-media/cerita-bi/Pages/mdr-qris.aspx), berlaku sejak 1 Okt 2026 |

## Biaya tetap bulanan

| Input | Nilai | Asal |
|---|---:|---|
| Sewa ruko ±100–150 m² | 12.500.000 | Rp150 juta/tahun, tengah rentang Rp106–200 juta/tahun: [Rumah123](https://www.rumah123.com/sewa/jakarta-timur/rawamangun/tahunan/ruko/), [99.co](https://www.99.co/id/properti/ruko-disewa-180jt-rawamangun-cp-1009053429), [Lamudi](https://www.lamudi.co.id/sewa/jakarta/jakarta-timur/rawamangun/komersial/ruko/). **Biasanya dibayar setahun di muka** (lihat catatan kas di `cfo.md`) |
| 3 staf × Rp6.790.000 | 20.370.000 | UMP DKI 2026 Rp5.729.876 ([Katadata](https://katadata.co.id/amp/berita/industri/694bb57d97fa5/ump-jakarta-2026-resmi-naik-jadi-rp-5-72-juta/)) + BPJS pemberi kerja 10,24% ([BPJS TK](https://www.bpjsketenagakerjaan.go.id/artikel/18913/artikel-berapa-besaran-iuran-jht,-jkk,-jkm,-jp-dan-jkp), [BPJS Kes](https://www.bpjs-kesehatan.go.id/bpjs/index.php/pages/detail/2014/13)) + THR/12. Jumlah staf 3 **[estimasi]**: buka 8 jam + persiapan, 7 hari |
| Listrik | 1.800.000 | Tarif B-2 Rp1.444,70/kWh ([Kompas](https://money.kompas.com/read/2026/11/02/083952426/tarif-listrik-pln-november-2026-cek-daftar-lengkap-semua-golongan)) × ±1.250 kWh. Beban **[estimasi]**: 2 AC, chiller, kettle, lampu |
| Air, galon, internet | 800.000 | **[Estimasi]** |
| POS | 299.000 | [Moka Basic](https://www.mokapos.com/en/pricing). Alternatif termurah: Qasir ±Rp58.250/bulan ([Qasir](https://www.qasir.id/en/pricing)) |
| Marketing rutin | 2.000.000 | **[Estimasi]**, dipecah di `/founder-marketing` |
| Perawatan, kebersihan | 1.000.000 | **[Estimasi]** |
| Gas LPG dapur | 400.000 | **[Estimasi]** |

## Startup (sekali)

| Input | Nilai | Asal |
|---|---:|---|
| Deposit sewa | 25.000.000 | Batas bawah rentang Rp25–75 juta (riset biaya) |
| Renovasi/fit-out | 75.000.000 | **[Estimasi, perlu penawaran kontraktor]** |
| Furnitur ±30 kursi | 25.000.000 | **[Estimasi]** |
| Peralatan bar manual brew | 18.500.000 | Paket A di `research/cost-inputs.md` (Otten, Tokopedia) |
| AC 2 unit | 12.000.000 | **[Estimasi]** |
| Under-counter chiller 2 pintu | 10.175.000 | [Tokopedia](https://www.tokopedia.com/find/under-counter-chiller), batas bawah |
| Peralatan dapur sederhana | 8.000.000 | **[Estimasi]** |
| Tablet POS + printer | 5.000.000 | **[Estimasi]** |
| Gelas dan smallwares | 5.000.000 | **[Estimasi]** |
| Perizinan (SLHS, halal, dll.) | 3.000.000 | **[Estimasi]**. NIB gratis via OSS; sertifikat halal reguler/SEHATI, lihat `/founder-ops` |
| Signage | 5.000.000 | **[Estimasi]** |
| Stok awal | 10.000.000 | **[Estimasi]** |
| Marketing pembukaan | 5.000.000 | **[Estimasi]** |
| Promo Ajak Teman 14 hari | 1.200.000 | Sekitar 23 tamu/hari × 14 hari × 30% × setengah harga gelas **[estimasi]** |
| **Tidak termasuk** | | Pengembangan aplikasi MoodBrew AI (dibekukan, syarat board C1); gaji founder |

## Volume

| Input | Nilai | Asal |
|---|---:|---|
| Kapasitas | 96 tamu/hari | 30 kursi × 8 jam ÷ 2,5 jam duduk. **Semua [estimasi]**; ganti dengan denah tempat nyata |
| Rencana | 60 tamu/hari | Okupansi rata-rata ±62% **[estimasi]** |
| Ramp bulan 1–12 | 23 → 60 | **[Estimasi]**. Cek terhadap panel di `cfo.md` |

## PBJT 10% (pajak restoran DKI)

Wajib jika omzet lebih dari Rp42 juta/bulan ([Bapenda DKI](https://bapenda.jakarta.go.id/jenis/pajak-restoran)). Di rencana 60 tamu × Rp40.000 × 30 hari = Rp72 juta/bulan, sehingga **wajib**. Model ini menganggap PBJT **ditambahkan di atas harga menu**. Jika harga menu sudah termasuk pajak, lihat what-if di `cfo.md`.
