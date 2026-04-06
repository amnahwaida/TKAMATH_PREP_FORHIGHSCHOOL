# Latihan Soal: Barisan dan Deret

> **Elemen:** [Aljabar](../index.md) | **Materi:** [Barisan & Deret](../barisan-deret.md) | **Kembali ke Home:** [🏠 README](../../../README.md)

---

## Soal 1: Pilihan Ganda (PG)
Sebuah barisan aritmetika memiliki suku ke-3 sama dengan 11 dan suku ke-7 sama dengan 27. Suku ke-10 dari barisan tersebut adalah ....

A. 30  
B. 35  
C. 39  
D. 42  
E. 45  

**Pembahasan:**
Rumus suku ke-n barisan aritmetika: $U_n = a + (n-1)b$.
$U_3 = a + 2b = 11$
$U_7 = a + 6b = 27$

Kurangi persamaan 2 dengan persamaan 1 (eliminasi):
$(a + 6b) - (a + 2b) = 27 - 11$
$4b = 16 \implies b = 4$

Substitusi nilai $b$ untuk mencari $a$:
$a + 2(4) = 11 \implies a + 8 = 11 \implies a = 3$

Mencari suku ke-10:
$U_{10} = a + 9b = 3 + 9(4) = 3 + 36 = 39$.

Jawaban yang tepat adalah **C**.

---

## Soal 2: Pilihan Ganda Kompleks Kategori (Benar/Salah)
Pada seutas tali rotan, tali tersebut dipotong menjadi 5 bagian yang membentuk barisan geometri. Jika tali terpendek adalah 2 cm dan potongan terpanjang adalah 162 cm. Tentukan Benar/Salah untuk pernyataan di bawah ini!

- A. Rasio dari barisan geometri tersebut adalah 3.
- B. Panjang tali pada potongan ketiga adalah 18 cm.
- C. Panjang tali keseluruhan sebelum dipotong adalah 242 cm.

**Pembahasan:**
Diketahui barisan geometri dengan $n = 5$.
Suku pertama (tali terpendek) $a = 2$.
Suku kelima (tali terpanjang) $U_5 = a \cdot r^4 = 162$.

Mari kita hitung:
$2 \cdot r^4 = 162 \implies r^4 = 81$.
Mengingat panjang tali bernilai positif, maka $r = 3$.

**A. Rasio dari barisan geometri tersebut adalah 3**
Terbukti dari perhitungan kita.
Kesimpulan: **Benar** ✔️

**B. Panjang tali potongan ketiga adalah 18 cm**
$U_3 = a \cdot r^2 = 2 \cdot 3^2 = 2 \cdot 9 = 18$ cm.
Kesimpulan: **Benar** ✔️

**C. Panjang tali keseluruhan adalah 242 cm**
Panjang total = Deret geometri jumlah 5 suku ($S_5$).
$$ S_n = \frac{a(r^n - 1)}{r - 1} $$
$$ S_5 = \frac{2(3^5 - 1)}{3 - 1} = \frac{2(243 - 1)}{2} = 242 $$
Kesimpulan: **Benar** ✔️

---

## Soal 3: Pilihan Ganda Kompleks MCMA (Lebih dari 1 Jawaban Benar)
Pak Rian menabung uang di bank sebesar Rp 10.000.000,00 dengan suku bunga majemuk 5% per tahun. Pilihlah perhitungan yang menunjukkan nominal yang tepat di setiap akhir tahun berjalan! (Asumsikan tidak ada biaya admin).

- [ ] Akhir tahun ke-1: Rp 10.500.000,00
- [ ] Akhir tahun ke-2: Rp 11.000.000,00
- [ ] Akhir tahun ke-2: Rp 11.025.000,00
- [ ] Bunga yang didapat murni selama tahun ke-1 adalah Rp 500.000,00
- [ ] Pertumbuhan saldo membentuk barisan aritmetika

**Pembahasan:**
Bunga majemuk menggunakan rumus $M = M_0 (1 + \frac{p}{100})^t$.
Di sini $M_0 = 10.000.000$, bunga 5% ($0,05$).

- Akhir tahun 1 ($t=1$):
  $M_1 = 10.000.000(1 + 0,05)^1 = 10.000.000 \times 1,05 = 10.500.000$. (Benar, bunga tahun pertama = 500.000).
- Akhir tahun 2 ($t=2$):
  $M_2 = M_1 \times 1,05 = 10.500.000 \times 1,05 = 11.025.000$.

Evaluasi Opsi:
1. Akhir tahun ke-1: Rp10.500.000. (Benar) ✅
2. Akhir tahun ke-2: Rp11.000.000. (Salah, ini bunga tunggal) ❌
3. Akhir tahun ke-2: Rp11.025.000. (Benar) ✅
4. Bunga 1 tahun pertama: Rp10.500.000 - Rp10.000.000 = Rp500.000. (Benar) ✅
5. Berbentuk barisan aritmetika. Salah, bunga majemuk itu barisan geometri (eksponensial). ❌

Jawaban yang tepat adalah opsi **1, 3, dan 4**.

---
**Navigasi:**
- [⬅️ Kembali ke Materi](../barisan-deret.md)
