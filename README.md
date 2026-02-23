# Tugas_PAB-SEM4

## 1. Halaman Produk

<img width="325" height="700" alt="image" src="https://github.com/user-attachments/assets/407ff877-d9ae-44dd-bfb9-10523fd4912f" />

Ini halaman awal yang isinya daftar barang yang dijual.

Barangnya ditampilkan dalam bentuk kotak-kotak (grid).
Setiap kotak ada:

- Gambar produk
- Nama produk
- Harga
- Tombol “Add”

Kalau tombol Add ditekan, barang itu langsung masuk ke keranjang.

Produk yang ada:

- Laptop Gaming
- Smartphone Pro
- Wireless Headphones
- Smart Watch
- Camera DSLR
- Tablet Pro

---------------------------------------------------------------------------------------------------------------------------------------

## 2. Halaman Keranjang (1 Produk)

<img width="325" height="699" alt="image" src="https://github.com/user-attachments/assets/ff5c7205-7a24-442b-a185-f5fcc0bde5ce" />

Ini halaman keranjang setelah kita nambah barang.

Di sini cuma ada Laptop Gaming dan jumlahnya 3 buah.

Karena satu laptop harganya 15 juta, dan kita ambil 3, jadi totalnya:

15 juta × 3 = 45 juta

Di samping jumlah ada:

- Tombol - buat ngurangin
- Tombol + buat nambahin
- Ikon tempat sampah buat hapus barang

Di bawah ada total belanja dan tombol Checkout.

Artinya di tahap ini user baru beli satu jenis barang, tapi jumlahnya banyak.

---------------------------------------------------------------------------------------------------------------------------------------

## 3. Halaman Keranjang (2 Produk)


<img width="325" height="697" alt="image" src="https://github.com/user-attachments/assets/4787fcec-4ad6-4610-a525-ea83370e5844" />

Ini masih halaman keranjang, tapi sekarang ada 2 jenis barang:

- Laptop Gaming (3 buah)
- Smartphone Pro (1 buah)

Totalnya jadi:

- Laptop: 45 juta
- Smartphone: 800 ribu
- Jadi total semua: 53 juta

Di bagian bawah totalnya otomatis berubah jadi 53 juta.

Artinya sistemnya sudah bisa:

- Menyimpan lebih dari satu barang
- Menghitung total otomatis
- Update total kalau ada perubahan

---------------------------------------------------------------------------------------------------------------------------------------

## 4. Halaman Keranjang dengan Banyak jumlah di masing"itemnya


<img width="319" height="698" alt="image" src="https://github.com/user-attachments/assets/66b78559-55c1-49bf-87bc-5fcfaaf7cb41" />

Di sini ada 2 produk dalam keranjang:

1. Laptop Gaming
- Jumlah: 3
- Total: Rp 45.000.000

2. Smartphone Pro

- Jumlah: 5
- Total: Rp 40.000.000

Jadi total keseluruhan di bawah:
Rp 85.000.000

Karena:
- 45 juta (laptop)
- 40 juta (smartphone)
- = 85 juta

Di setiap produk ada:
- Tombol - buat ngurangin jumlah
- Tombol + buat nambahin jumlah
- Ikon tempat sampah buat hapus satu produk

---------------------------------------------------------------------------------------------------------------------------------------

## 5. Halaman kuantitas item Dikurangi

<img width="323" height="696" alt="image" src="https://github.com/user-attachments/assets/c35d9849-c369-41cc-9c84-512ec78716b2" />

Di gambar ini jumlahnya sudah berubah:
- Laptop Gaming → jadi 1
- Smartphone Pro → jadi 1

Totalnya sekarang:
Rp 23.000.000

Karena:
- 15 juta (1 laptop)
- 8 juta (1 smartphone)
- = 23 juta

Artinya tombol -  berfungsi dan total otomatis ikut berubah.

---------------------------------------------------------------------------------------------------------------------------------------

## 6. Halaman hapus semua produk?

<img width="323" height="699" alt="image" src="https://github.com/user-attachments/assets/06543e7f-5d02-46e5-bf01-3374bd89002e" />

Di halaman ini muncul pop-up:

“Clear Cart?”
“Remove all items from cart?”

Ada 2 pilihan:
- Cancel → batal hapus
- Clear → hapus semua barang

---------------------------------------------------------------------------------------------------------------------------------------

## 7. Halaman dengan keranjang kosong


<img width="322" height="702" alt="image" src="https://github.com/user-attachments/assets/89aa7b2a-2aae-4b94-991f-5b2d6867eabf" />

Setelah tekan Clear, semua item hilang.

Muncul tampilan:

  “Your cart is empty”

Ada tombol:

  Continue Shopping

Artinya sistem berhasil mengosongkan keranjang dan menampilkan empty state.

---------------------------------------------------------------------------------------------------------------------------------------

## 8. Halaman utama

<img width="324" height="702" alt="image" src="https://github.com/user-attachments/assets/ac8bffcc-f545-4cf1-883c-075fda9ac69e" />

User tekan Continue Shopping dan balik ke halaman produk.

Siklus belanja bisa dimulai lagi dari awal.

---------------------------------------------------------------------------------------------------------------------------------------

