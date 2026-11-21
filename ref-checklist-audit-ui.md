# Checklist Audit UI

Dipakai untuk menilai sebuah layar, termasuk hasil generate AI.
Jawab setiap pertanyaan dengan "ya" atau "belum".
Setiap "belum" diubah menjadi arahan yang spesifik untuk AI.

-----------------------------------------------------------------
## 1. Hierarki visual
-----------------------------------------------------------------
[ ] Apakah elemen terpenting di layar paling menonjol?
[ ] Apakah ada maksimal satu tombol utama per layar?
[ ] Saat layar dilihat sambil menyipitkan mata, apakah urutan
    pentingnya masih terbaca?

Contoh arahan ke AI:
  "Jadikan total harga elemen paling menonjol: perbesar ukurannya
   dan tebalkan hurufnya. Kecilkan label kategori."

-----------------------------------------------------------------
## 2. Spacing & layout
-----------------------------------------------------------------
[ ] Apakah jarak antar elemen konsisten (misalnya kelipatan 4 atau 8)?
[ ] Apakah elemen yang berkaitan dikelompokkan berdekatan?
[ ] Apakah elemen sejajar rapi (alignment)?

Contoh arahan ke AI:
  "Beri jarak 24px antar kartu paket. Kelompokkan nama paket dan
   harganya dengan jarak 8px."

-----------------------------------------------------------------
## 3. Tipografi
-----------------------------------------------------------------
[ ] Apakah memakai maksimal 2 jenis font?
[ ] Apakah ukuran huruf membedakan judul, subjudul, dan isi?
[ ] Apakah teks isi cukup besar untuk dibaca di HP?
[ ] Apakah angka Rupiah mudah dibaca?

Contoh arahan ke AI:
  "Gunakan satu font sans-serif. Judul 24px tebal, isi 16px normal.
   Tulis harga dengan format Rp150.000 per pax."

-----------------------------------------------------------------
## 4. Warna & kontras
-----------------------------------------------------------------
[ ] Apakah setiap warna punya tugas yang jelas (utama, netral,
    sukses, peringatan, error)?
[ ] Apakah teks terbaca jelas di atas latarnya?
[ ] Apakah informasi penting tidak hanya dibedakan lewat warna?

Contoh arahan ke AI:
  "Pakai satu warna utama untuk tombol dan elemen aktif saja.
   Pastikan teks putih di atas tombol tetap kontras."

-----------------------------------------------------------------
## 5. State & feedback
-----------------------------------------------------------------
[ ] Apakah ada tampilan saat data kosong?
[ ] Apakah ada pesan saat terjadi error, dan jelas cara memperbaikinya?
[ ] Apakah tombol yang belum bisa dipakai terlihat disabled?
[ ] Apakah area yang bisa disentuh cukup besar untuk jari?

Contoh arahan ke AI:
  "Tambahkan pesan error di bawah input jumlah tamu saat nilainya
   di bawah 30: 'Minimal pemesanan 30 pax'. Tombol lanjut disabled
   sampai jumlah tamu valid."

-----------------------------------------------------------------
## 6. Konteks produk
-----------------------------------------------------------------
[ ] Apakah layar ini terasa seperti aplikasi catering prasmanan,
    bukan template aplikasi apa saja?
[ ] Apakah istilah dan contoh menu sesuai konteks Indonesia?
[ ] Apakah aturan bisnis (minimum pax, slot penuh, tanggal penuh)
    tercermin di layar?

-----------------------------------------------------------------
## Tanda-tanda "AI look"
-----------------------------------------------------------------
- Semua kartu berukuran dan berbobot sama, tidak ada yang menonjol
- Gradien ungu-biru atau warna yang tidak ada hubungannya dengan produk
- Ilustrasi atau ikon dekoratif yang tidak membantu pengguna
- Teks contoh yang generik ("Lorem ipsum", "Product name")
- Layout rapi tapi tidak ada yang mencerminkan masalah pengguna
