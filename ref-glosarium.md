# Glosarium Agentic UI/UX Design

Istilah yang dipakai di kelas ini, dijelaskan singkat.
Kalau ada istilah yang belum ada di sini, tanyakan di tab Q&A.

-----------------------------------------------------------------
## Dasar UI/UX
-----------------------------------------------------------------

UI (User Interface)
  Tampilan yang dilihat dan disentuh pengguna: tombol, teks, warna,
  layout. Di aplikasi catering kita, UI adalah tampilan layar
  pemilihan paket, menu builder, dan ringkasan pesanan.

UX (User Experience)
  Pengalaman pengguna secara keseluruhan saat memakai produk:
  mudah atau tidak, cepat atau lambat, bikin bingung atau tidak.
  Di aplikasi kita, UX adalah seberapa mudah orang memesan catering
  dibanding chat WhatsApp bolak-balik.

Hierarki visual
  Urutan elemen yang dilihat mata pengguna lebih dulu. Diatur lewat
  ukuran, ketebalan huruf, warna, dan posisi. Elemen terpenting
  (misalnya total harga atau tombol lanjut) harus paling menonjol.

Spacing
  Jarak antar elemen. Spacing yang konsisten membuat layar terasa
  rapi. Elemen yang berkaitan diberi jarak lebih dekat, elemen yang
  tidak berkaitan diberi jarak lebih jauh.

Tipografi
  Cara memilih dan mengatur huruf: jenis font, ukuran, ketebalan,
  dan jarak antar baris. Tujuannya teks mudah dibaca dan punya
  hierarki yang jelas.

Kontras
  Perbedaan terang-gelap antara teks dan latar belakangnya.
  Kontras yang terlalu rendah membuat teks sulit dibaca.

State
  Kondisi sebuah layar atau elemen di luar keadaan normal, misalnya
  kosong (empty), memuat (loading), gagal (error), atau tidak bisa
  dipakai (disabled). Contoh di aplikasi kita: pesan error saat
  jumlah tamu di bawah minimum 30 pax.

Flow
  Urutan layar yang dilalui pengguna untuk menyelesaikan satu tugas.
  Flow utama aplikasi kita: isi jumlah tamu dan tanggal, pilih paket
  atau racik sendiri, susun menu, lihat ringkasan, bayar DP.

-----------------------------------------------------------------
## Bekerja bareng AI
-----------------------------------------------------------------

Agentic design
  Cara mendesain di mana kita berperan sebagai pengarah: merumuskan
  masalah, memberi arahan ke AI, menilai hasilnya, lalu memutuskan.
  AI membantu eksplorasi dan eksekusi, keputusan tetap di tangan kita.

Prompt
  Instruksi yang kita tulis untuk AI. Prompt yang spesifik
  menghasilkan output yang lebih terarah dibanding prompt umum
  seperti "buat lebih bagus".

Generate
  Proses AI membuat output, misalnya membuat layar aplikasi dari
  sebuah prompt.

Iterasi
  Memperbaiki hasil secara bertahap: lihat hasil, nilai, beri arahan
  baru, ulangi sampai sesuai.

AI look
  Ciri hasil AI yang terasa generik: rapi tapi mirip semua, hierarki
  lemah, tidak paham konteks produk. Kelas ini mengajarkan cara
  menghindarinya.

-----------------------------------------------------------------
## Brief & design system
-----------------------------------------------------------------

Problem statement
  Satu kalimat yang merumuskan masalah: siapa penggunanya, apa yang
  mereka butuhkan, dan apa yang menghalangi mereka.

How Might We (HMW)
  Pertanyaan yang mengubah masalah menjadi arah solusi. Contoh:
  "Bagaimana kita bisa membuat pemesan tahu total harga dalam
  hitungan menit tanpa chat bolak-balik?"

Design brief
  Dokumen ringkas berisi masalah, pengguna, tujuan, scope, dan
  batasan sebelum mulai mendesain.

Design system
  Kumpulan aturan dan komponen yang membuat semua layar konsisten:
  warna, huruf, spacing, komponen, dan cara memakainya.

design.md
  File teks berisi design system yang ditulis supaya bisa dibaca
  manusia dan AI. Dipakai sebagai konteks saat generate layar.

Token
  Nilai desain yang diberi nama, misalnya color.primary atau
  text.body. Mirip variabel di CSS.

-----------------------------------------------------------------
## Tools di kelas ini
-----------------------------------------------------------------

Gemini
  AI dari Google yang kita pakai untuk riset, sparring ide,
  menyusun brief, dan mengkritik desain. Dipakai versi gratis.

Stitch
  Tool dari Google untuk generate layar aplikasi dari prompt.
  Dipakai versi gratis di Fase 1.

Fase 1 dan Fase 2
  Fase 1 (Modul 0 sampai 5) memakai tools gratis. Fase 2 (Modul 6
  sampai 8) memakai Figma dan AI coding assistant.
