# Folder foto

Nama file harus **persis sama** dengan yang tertulis di `CONFIG` dalam `index.html` (huruf besar/kecil dan spasi berpengaruh di GitHub Pages dan hosting Linux). Foto yang belum ada otomatis diganti placeholder.

## Logo

`Logo Asyifa Jaya.jpeg` — header, footer, ikon tab browser, bagian ajakan penutup.

## Kode QR

`Barcode.jpg` (asli) → `Barcode-web.png` (dipotong ke area putih, isi QR sama) — tampil di bagian Harga partai dan footer, **hanya di PC/laptop**.
Jika QR diganti, potong juga margin abu-abunya atau ubah `src` di `index.html` ke file baru.

## Foto produk (sudah dipetakan di kode)

| File | Produk | Dipakai juga di |
|---|---|---|
| `Ayam ekoran.jpeg` | Ayam utuh / ekoran | Hero (besar), latar ajakan penutup |
| `Dada filet.jpeg` | Dada fillet | Hero |
| `Paha pentung.jpeg` | Paha bawah (pentung) | Hero |
| `Sayap.jpeg` | Sayap | |
| `Ceker.jpeg` | Ceker | |
| `Hati ampela.jpeg` | Hati ampela | |
| `Usus.jpeg` | Usus | |
| `Kulit.jpeg` | Kulit | |
| `Kepala.jpeg` | Kepala & leher | |
| `Paha Atas.jpeg` | Paha atas | |
| `Tulangan.jpeg` | Tulangan (rangka) | |

Semua foto produk yang ada juga tampil di strip foto berjalan di bawah hero (muncul jika minimal 4 foto tersedia).

## Belum ada foto (opsional)

| File | Dipakai di |
|---|---|
| `gerai.jpg`, `peternakan.jpg`, `pemotongan.jpg`, `penyimpanan.jpg` | Bagian "Proses kami". Setelah diunggah, isi kolom `foto` di `CONFIG.slides` (saat ini kosong agar tidak ada permintaan file yang gagal). Slider muncul jika minimal satu foto ada. |

Ukuran disarankan: produk potret (tegak) seperti foto yang ada, mis. 900×1600, tampil dipotong rasio 4:5 di katalog — letakkan objek utama di tengah; proses 1600×1280. Kompres hingga < 300 KB per file.
