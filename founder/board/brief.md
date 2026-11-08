# Brief untuk Board: Kopiyo

> Brief ini berdiri sendiri. Anggota board tidak melihat percakapan dengan founder.

## 1. Idea file (dari `founder/idea.md`)

- **Nama:** Kopiyo (alternatif: "Ngopi-yo").
- **Apa ini:** kedai kopi model *slowbar* yang menjual pengalaman menikmati kopi (diseduh pelan, ngobrol dengan barista dan teman), sengaja **bukan** tempat kerja: tempat untuk ngobrol, santai, dan melepas lelah.
- **Untuk siapa:** orang yang lelah setelah bekerja dan ingin tempat berkumpul dengan teman untuk ngopi dan bercerita. Usia, pendapatan, dan pekerjaan yang lebih spesifik belum ditentukan.
- **Apa yang dijual dan harganya:** kopi seduh slowbar (manual brew) plus pengalamannya. Founder ingin harga "tidak terlalu mahal" agar orang bisa merasakan pengalaman kopi secara penuh. Angka harga per cangkir belum ditentukan.
- **Lokasi dan kanal:** Rawamangun, Jakarta Timur, sebagai lokasi pertama; Yogyakarta disebut sebagai kemungkinan lokasi lain. Penjualan offline (dine-in). Cara pelanggan menemukan kedai belum ditentukan.
- **Anggaran:** belum disebutkan.
- **Sudah diputuskan:** tidak melayani orang yang datang untuk bekerja (bukan tempat WFC/coworking).

## 2. Kata-kata founder sendiri (diterjemahkan dekat dengan aslinya)

"Saya mau membuat tempat kopi bernama Kopiyo atau Ngopi-yo yang menjual experiences dan pengalaman orang untuk menikmati kopi. Tempat ini bermodel slowbar dan hanya menyediakan tempat untuk ngobrol, santai, dan berkumpul dengan teman, bukan tempat untuk bekerja. Jadi orang-orang yang sudah lelah dengan pekerjaan bisa ke tempat saya untuk ngopi, bercerita, dan melepas lelahnya. Rencana saya, saya mau membuat aplikasi berbasis AI ini. Challenge saya dan berikan rekomendasi mengenai ide bisnis yang akan saya jalankan."

Tentang harga: "Saya ingin membuat tempat kopi yang tidak terlalu mahal, jadi orang-orang bisa merasakan experiences penuh tentang kopi."

## 3. Aplikasi AI yang direncanakan (ringkasan PRD "MoodBrew AI" v1.0, 8 Nov 2026)

Founder menyatakan aplikasi ini adalah **alat internal Kopiyo**, bukan produk untuk dijual ke kedai lain. PRD-nya sendiri ditulis dengan arsitektur "multi-outlet-ready" dan menyebut "calon mitra integrasi".

Ruang lingkup PRD (P0 = wajib MVP):
- **Customer App (P0):** chat AI dalam bahasa bebas ("kopi dingin, fruity, tidak pahit, kafein rendah"), ekstraksi preferensi, rekomendasi 1 utama + 2–3 alternatif dari menu dan stok aktual, detail beans, keranjang, checkout, dan **Coffee Story**: narasi personal tentang asal beans, proses, dan resep kopi yang dipesan, lewat app/QR di struk.
- **POS (P0):** order dine-in/take-away, pembayaran tunai/QRIS, refund, antrean barista dengan snapshot resep.
- **Inventori, resep, HPP, harga jual (P0):** stock ledger, penerimaan barang, waste, HPP per porsi, simulasi harga dengan approval manusia.
- **Procurement (P0/P1), BI dashboard (P0/P1).**
- **AI Business Copilot (P1):** owner bertanya dalam bahasa natural ("kenapa margin latte turun?"), read-only.
- **Loyalty, WhatsApp opt-in, forecasting (P1/P2); voice/TTS (P2).**
- Teknologi yang direncanakan: React/TypeScript PWA, FastAPI, PostgreSQL + pgvector, Redis, LLM API.
- PRD menyatakan mood hanya preferensi eksplisit, tanpa diagnosis psikologis.
- Contoh HPP di PRD (ilustrasi, bukan data aktual): latte susu, material Rp9.340 + overhead Rp2.000 = Rp11.340; dengan target margin 60% harganya Rp29.000.
- Risiko yang dicatat PRD sendiri: "Cakupan produk terlalu luas untuk MVP" (rilis terlambat, integrasi rapuh).

Teks lengkap PRD (opsional, untuk detail): `/tmp/claude-0/-home-user-Moodbrew-Coffe/c3155549-a96c-5b30-88cd-e34b095deb4c/scratchpad/prd/prd.txt`

## 4. Yang belum diketahui (jangan diisi dengan angka karangan)

- Harga per cangkir, anggaran modal, ukuran tempat, jumlah kursi, jam buka.
- Profil pelanggan yang lebih spesifik (usia, pendapatan, pekerjaan).
- Pengalaman founder di F&B/kopi, siapa barista-nya, dan siapa yang akan membangun aplikasi.
- Kompetitor di Rawamangun (akan dipetakan oleh `/founder-competitors`).
- Permintaan pasar (akan diuji oleh `/founder-consumer`).
- Angka keuangan (akan dihitung oleh `/founder-cfo`).
