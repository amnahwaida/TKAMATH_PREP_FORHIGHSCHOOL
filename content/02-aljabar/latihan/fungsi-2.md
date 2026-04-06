# Latihan Soal Set 2: Fungsi

> **Elemen:** [Aljabar](../index.md) | **Materi:** [Fungsi](../fungsi.md) | **Set 1:** [Latihan 1](fungsi.md) | **Kembali ke Home:** [🏠 README](../../../README.md)

---

## Soal 1: Pilihan Ganda (PG)
Diketahui $f(x) = x^2 - 4x + 6$ dan $g(x) = x - 2$. Rumus komposisi fungsi $(f \circ g)(x)$ adalah ....

A. $x^2 - 4x + 4$  
B. $x^2 - 8x + 18$  
C. $x^2 - 6x + 10$  
D. $x^2 - 2x + 6$  
E. $x^2 - 8x - 2$  

**Pembahasan:**
Hitung $(f \circ g)(x)$:
$$(f \circ g)(x) = f(g(x))$$
Substitusikan $x-2$ ke dalam susunan $f(x)$:
$$ f(x-2) = (x-2)^2 - 4(x-2) + 6 $$
$$ = (x^2 - 4x + 4) - 4x + 8 + 6 $$
$$ = x^2 - 8x + 18 $$

Ternyata hasilnya adalah sebuah fungsi kuadratik baru $x^2 - 8x + 18$.
Jawaban yang tepat adalah **B**.

---

## Soal 2: Pilihan Ganda Kompleks Kategori (Benar/Salah)
Tentukan Benar atau Salah pernyataan berkaitan dengan daerah asal (domain) dan daerah hasil (range) dari sebuah relasi matematika!

- A. Rentang Range suatu fungsi eksponensial dalam bentuk umum $y = 2^x$ adalah $y \ge 0$.
- B. Fungsi kuadratik $y = -x^2 + 4$ memiliki rentang Range berupa batas mutlak menuju $-\infty$ dengan titik tertinggi $y=4$.
- C. Sebuah fungsi dikatakan injektif bila tiap entitas pada daerah asal memetakan ke titik berbeda pada daerah kawan (kodomain).

**Pembahasan:**
**A. Range fungsi eksponensial $y = 2^x$ adalah $y \ge 0$**
Pertumbuhan berlipat-ganda pangkat eksponensial (basis positif) tak pernah dapat merengkuh angka bernilai nol seutuhnya, hanya asimtot vertikal menuju nol (mendekat namun tak sampai menyentuh/memotong), sehingga yang valid adalah $(y > 0)$, BUKAN $(y \ge 0)$.
Kesimpulan: **Salah** ❌

**B. Range dari $-x^2 + 4$ adalah puncaknya di 4**
Persamaan kuadrat dengan koefisien negatif pada $x^2$ melukiskan kurva parabola yang membuka melengkung ke arah bawah. Puncak maksimal (Y) terletak ketika turunan nol atau di saat $x=0$, yang menghasilkan nilai fungsi tertingginya yaitu $+4$. Sisanya bersemayam di kuadran di bawahnya.
Kesimpulan: **Benar** ✔️

**C. Definisi Fungsi Injektif**
Ya, fungsi satu-satu (Injektif) bermakna jika disuntik dari asal $x$ yang berbeda akan selalu sampai di titik sasaran $y$ yang berbeda pula. Tidak akan ada percabangan konvergensi $x_1$ dan $x_2$ bertabrakan di titik sasaran $y$ yang sama.
Kesimpulan: **Benar** ✔️

---

## Soal 3: Pilihan Ganda Kompleks MCMA (Lebih dari 1 Jawaban Benar)
Pilihlah pernyataan yang merupakan implikasi sah manakala suatu fungsi awal $f(x)$ ditarik garis Inversnya $\implies f^{-1}(x)$ (Pilih lebih dari satu yang benar!)

- [ ] Grafik invers suatu fungsi sesungguhnya merupakan gambar bayangan cermin jika direfleksikan menyusuri garis lurus vertikal $X=0$.
- [ ] Titik domain dari $f(x)$ akan tertukar 100% perannya menjadi titik range untuk fungsi invers $f^{-1}(x)$.
- [ ] Sembarang Fungsi Linear dipastikan memiliki fungsi invers yang juga bersifat Linear sejauh garis grafiknya tak bersumbu horizontal/vertikal sejajar.
- [ ] Semua fungsi kuadrat secara general akan senantiasa menghasilkan fungsi invers yang terdefinisi satu-satu jika ditarik dari $\infty$ ke $-\infty$.
- [ ] Susunan rumus dari komposisi invers ke dalam relasi induknya $\implies (f \circ f^{-1})(x)$ mutlak bernilai menghasilkan "$x$".

**Pembahasan:**
Mari mengevaluasi sifat definit invers relasi:
1. Bayangan dicerminkan ke garis *identitas* $y = x$, BUKAN ke poros sumbu $Y$ atau sumbu $X$. ❌
2. Karena hakikat $f^{-1}$ mengurai secara terbalik alur matematis, poros $X$ (Domain) menjadi sasaran poros $Y$ (*Range*), dan berlaku sebaliknya. ✅
3. Garis diagonal linear selalu dijamin mempunyai invers (bentuk pecahannya berpotongan presisi). ✅
4. Fungsi kuadrat memiliki bayangan berupa Parabola menyamping. Melukis garis vertikal pada bayangan itu akan menabrak 2 garis yang berulang nilai (Dual-sasaran pada 1 sumbu poros asal). Bukan fungsi (invalid). Supaya memiliki invers, kita harus "memotong" setengah dari parabolanya dengan pembatasan domain. ❌ 
5. Ya, identitas matematika mendasar dari fungsi invers adalah jika dimasukkan berturut (dirusak kemudian dibangunkan dari serpihannya) akan menghasilkan kembali nilai ke kondisi asalnya ($x$). ✅

Maka jawaban utuh yang valid dan berbobot benar dalah **opsi 2, 3, dan 5**.

---
**Navigasi:**
- [⬅️ Kembali ke Materi](../fungsi.md)
