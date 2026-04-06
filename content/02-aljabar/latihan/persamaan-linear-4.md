# Latihan Soal Set 4: Sistem Persamaan Linear & Pertidaksamaan

> **Elemen:** [Aljabar](../index.md) | **Materi:** [Persamaan Linear](../persamaan-linear.md) | **Set 1:** [Latihan 1](persamaan-linear.md) | **Set 2:** [Latihan 2](persamaan-linear-2.md) | **Set 3:** [Latihan 3](persamaan-linear-3.md) | **Kembali ke Home:** [🏠 README](../../../README.md)

---

## Soal 1: Pilihan Ganda (PG)
Diberikan sistem pertidaksamaan yang menyatakan irisan daerah penyelesaian pada bidang Kartesius:
$y \ge x^2 - 4x - 5$
$y \le -x + 5$
Berdasarkan sistem pertidaksamaan tersebut, koordinat titik manakah di bawah ini yang berada di dalam daerah penyelesaian?

A. $(0, 6)$  
B. $(3, 1)$  
C. $(-2, 4)$  
D. $(6, -3)$  
E. $(4, 8)$  

**Pembahasan:**
Uji masing-masing titik koordinat dengan cara mensubstitusikan nilainya ke dalam kedua pertidaksamaan. Sebuah titik berada dalam daerah penyelesaian jika memenuhi kedua syarat sekaligus:
Syarat 1: $y \ge x^2 - 4x - 5$
Syarat 2: $y \le -x + 5$

**A (0,6):**
Persamaan 1: $6 \ge (0)^2 - 0 - 5 \implies 6 \ge -5$ (Benar).
Persamaan 2: $6 \le -0 + 5 \implies 6 \le 5$ (Salah).

**B (3,1):**
Persamaan 1: $1 \ge (3)^2 - 4(3) - 5 \implies 1 \ge 9 - 12 - 5 \implies 1 \ge -8$ (Benar).
Persamaan 2: $1 \le -(3) + 5 \implies 1 \le 2$ (Benar). Titik B memenuhi.

**C (-2,4):**
Persamaan 1: $4 \ge (-2)^2 - 4(-2) - 5 \implies 4 \ge 4 + 8 - 5 \implies 4 \ge 7$ (Salah).

**D (6,-3):**
Persamaan 1: $-3 \ge 6^2 - 4(6) - 5 \implies -3 \ge 36 - 24 - 5 \implies -3 \ge 7$ (Salah).

**E (4,8):**
Persamaan 2: $8 \le -(4) + 5 \implies 8 \le 1$ (Salah).

Titik koordinat yang memenuhi kedua kondisi ada pada posisi $(3,1)$. Pilihan yang tepat adalah **B**.

---

## Soal 2: Pilihan Ganda Kompleks Kategori (Benar/Salah)
Penyelesaian dan pemodelan dalam program linear membutuhkan pemahaman konsep yang mendalam terkait fungsi objektif dan titik perpotongan daerah penyelesaian. Analisis kebenaran dari pernyataan-pernyataan berikut!

- A. Sistem pertidaksamaan $x + y \le 8$ dan $x + y \ge 12$ tidak memiliki daerah penyelesaian, dan irisannya merupakan himpunan kosong.
- B. Nilai fungsi objektif $Z = 3x - 2y$ akan semakin besar jika nilai absis $x$ diperbesar dan nilai ordinat $y$ diperkecil pada daerah penyelesaian yang relevan.
- C. Jika suatu pertidaksamaan linear, seperti $ax + by \le c$, dibagi atau dikali dengan suatu bilangan negatif pada kedua ruas kepersamaannya, maka tanda ketidaksamaan tidak perlu dibalik.

**Pembahasan:**
**A. Irisan pertidaksamaan linear kontradiktif**
Pertidaksamaan $x+y \le 8$ membentuk arsiran kurang dari 8, sementara $x+y \ge 12$ menuntut penjumlahannya lebih besar dari 12. Karena tidak ada bilangan mutlak yang penjumlahannya lebih kecil dari 8 namun sekaligus melebihi 12, sistem ini membentuk himpunan kosong.
Kesimpulan: **Benar** ✔️

**B. Fungsi Objektif berkoefisien negatif**
Fungsi $Z = 3x - 2y$. Variabel $x$ memberikan kontribusi nilai positif, sementara $y$ memberikan pengurang yang memiliki koefisien $-2$. Untuk mendapatkan hasil $Z$ maksimum, nilai $x$ harus besar, dan nilai pengurang $y$ harus sekecil mungkin. 
Kesimpulan: **Benar** ✔️

**C. Sifat pertidaksamaan dioperasikan dengan bilangan negatif**
Di dalam konsep dasar persamaan, apabila kedua sisi pertidaksamaan digandakan atau pula dibagi dengan bilangan bernilai negatif (sebagai contoh: $-2x \le -8$ lalu dibagi oleh pembagi $-2$), arah tanda ketidaksamaan mutlak harus diubah menjadi balikannya ($x \ge 4$) agar pernyataan tersebut tetap bernilai valid.
Kesimpulan: **Salah** ❌

---

## Soal 3: Pilihan Ganda Kompleks MCMA (Lebih dari 1 Jawaban Benar)
Diketahui persamaan nilai mutlak berwujud $|2x - 3| - |x + 1| = 0$. Analisis setiap pernyataan terkait himpunan penyelesaian dari persamaan linear mutlak tersebut dan pilih pernyataan yang terbukti bernilai matematis yang tepat!

- [ ] Salah satu penyelesaian untuk persamaan tersebut adalah $x = 4$.
- [ ] Salah satu penyelesaian untuk persamaan tersebut berupa pecahan tak bulat berwujud $x = \frac{2}{3}$.
- [ ] Himpunan penyelesaian total atas permasalahan mutlak tersebut adalah himpunan $\{0, 2\}$.
- [ ] Operasi nilai mutlak untuk bentuk persamaan tersebut setara dengan mencari penyelesaian dari analisis sistem $(2x - 3) = \pm(x + 1)$.
- [ ] Hasil dari penjumlahan seluruh akar persamaan yang ditemukan tersebut ($x_1 + x_2$) bernilai sama dengan besaran $\frac{14}{3}$.

**Pembahasan:**
Selesaikan fungsi mutlak berikut: 
$|2x - 3| - |x + 1| = 0  \implies |2x - 3| = |x + 1|$
Dengan mengkuadratkan kedua ruas atau menerapkan definisi nilai mutlak, penyelesaian dapat dipecah menjadi mode $\implies (2x - 3) = +(x + 1)$ ATAU $(2x - 3) = -(x + 1)$. (Sesuai dengan logika opsi 4). ✅

Skenario 1 (Kondisi Positif):
$$ 2x - 3 = x + 1 \implies 2x - x = 1 + 3 \implies x = 4 $$  
Akar pertama adalah $X = 4$. ✅ (Kondisi Opsi 1 valid dan Opsi 3 salah telak).

Skenario 2 (Kondisi Negatif):
$$ 2x - 3 = -(x + 1) \implies 2x - 3 = -x - 1 \implies 3x = 2 \implies x = \frac{2}{3} $$  
Akar kedua adalah bentuk rasional murni di $2/3$. ✅

Hitung penjumlahan antarkedua nilai akar ($x_1 + x_2$):
$$ \Sigma x = 4 + \frac{2}{3} = \frac{12}{3} + \frac{2}{3} = \frac{14}{3} $$
Perhitungan penjumlahan di atas telah terbukti presisi valid secara akurat. ✅

Berdasarkan langkah pemecahan yang diurus, asersi yang layak disematkan indikasi benar diposisikan pada nomor opsi terperinci yaitu **1, 2, 4, dan 5**.

---
**Navigasi:**
- [⬅️ Kembali ke Materi](../persamaan-linear.md)
