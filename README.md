# Mini Compiler - Teknik Kompilasi

## Nama
Sheril Lestari

## NIM
231011400502

---

# Hasil Program

Input:
a ^ 2 + b * c

Output:
t1 = a ^ 2
t2 = b * c
t3 = t1 + t2

---

# Jawaban Refleksi

## 1. Mengapa power() dipanggil di dalam term()?

Karena operator pangkat (^) memiliki prioritas lebih tinggi dibanding perkalian (*) dan pembagian (/), sehingga harus diproses terlebih dahulu.

## 2. Apa yang terjadi jika variabel z tidak ada di symbol_table?

Compiler akan menghasilkan Semantic Error karena variabel belum didefinisikan.

## 3. Mengapa TAC a ^ 2 muncul sebelum + ?

Karena compiler mengikuti operator precedence, sehingga operasi pangkat diproses lebih dahulu sebelum penjumlahan.
