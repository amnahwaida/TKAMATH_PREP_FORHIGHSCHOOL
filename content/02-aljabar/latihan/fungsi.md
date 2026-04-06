# Latihan Soal: Fungsi

> **Elemen:** [Aljabar](../index.md) | **Materi:** [Fungsi](../fungsi.md) | **Kembali ke Home:** [🏠 README](../../../README.md)

---

## Soal 1: Pilihan Ganda (PG)
Diketahui fungsi $f(x) = \frac{x + 2}{3x - 1}$, $x \neq \frac{1}{3}$. Invers dari fungsi $f$ adalah $f^{-1}(x) = \dots$

A. $\frac{x + 2}{3x - 1}$  
B. $\frac{3x - 1}{x + 2}$  
C. $\frac{x + 2}{3x - 1}$  
D. $\frac{x + 2}{3x - 1}$  *(ada typo opsi di Juknis, gunakan cara cepat D: $\frac{x+2}{3x-1}$)*  
E. $\frac{x + 2}{3x - 1}$  *(mari kita buat opsi yang benar secara sistematis: C)*  

*Wait, let's reset the options to proper ones for this dummy generator:*

A. $\frac{x + 2}{3x + 1}$  
B. $\frac{x + 2}{3x - 1}$  
C. $\frac{x - 2}{3x - 1}$  
D. $\frac{x + 1}{3x - 2}$  
E. $\frac{x - 1}{3x + 2}$  

**Pembahasan:**
Cara cepat untuk fungsi bentuk pecahan $f(x) = \frac{ax+b}{cx+d}$ adalah $f^{-1}(x) = \frac{-dx+b}{cx-a}$.
Dari soal: $f(x) = \frac{1x + 2}{3x - 1}$.
Berarti: $a=1, b=2, c=3, d=-1$.

Inversnya: 
$f^{-1}(x) = \frac{-(-1)x + 2}{3x - 1} = \frac{x + 2}{3x - 1}$.

Jadi, invers fungsi itu ternyata sama dengan dirinya sendiri!
Jawaban yang tepat adalah **B**.

---

## Soal 2: Pilihan Ganda Kompleks Kategori (Benar/Salah)
Diketahui fungsi $f(x) = 2x - 3$ dan $g(x) = x^2 + 1$. Tentukan Benar atau Salah pernyataan berikut mengenai komposisi fungsi!

- A. Rumus untuk $(f \circ g)(x) = 2x^2 - 1$.
- B. Rumus untuk $(g \circ f)(x) = 4x^2 - 12x + 10$.
- C. Nilai dari $(f \circ g)(2) = 17$.

**Pembahasan:**
Kita hitung rumusnya:
**A. $(f \circ g)(x)$**
$(f \circ g)(x) = f(g(x)) = f(x^2 + 1) = 2(x^2 + 1) - 3 = 2x^2 + 2 - 3 = 2x^2 - 1$.
Kesimpulan: **Benar** ✔️

**B. $(g \circ f)(x)$**
$(g \circ f)(x) = g(f(x)) = g(2x - 3) = (2x - 3)^2 + 1 = (4x^2 - 12x + 9) + 1 = 4x^2 - 12x + 10$.
Kesimpulan: **Benar** ✔️

**C. Nilai $(f \circ g)(2)$**
Substitusi $x = 2$ ke dalam $(f \circ g)(x) = 2x^2 - 1$:
$(f \circ g)(2) = 2(2^2) - 1 = 2(4) - 1 = 8 - 1 = 7$.
Bukan 17.
Kesimpulan: **Salah** ❌

---

## Soal 3: Pilihan Ganda Kompleks MCMA (Lebih dari 1 Jawaban Benar)
Pilihlah jawaban yang benar tentang domain (daerah asal) fungsi! Jika fungsi $h(x) = \frac{\sqrt{x - 2}}{x - 5}$, manakah pernyataan yang merepresentasikan elemen domain yang valid? (Jawaban lebih dari satu).

- [ ] $x = 1$
- [ ] $x = 2$
- [ ] $x = 3$
- [ ] $x = 4$
- [ ] $x = 5$

**Pembahasan:**
Syarat domain untuk pecahan dengan akar:
1. Syarat akar (bagian dalam akar harus $\ge 0$): $x - 2 \ge 0 \implies x \ge 2$.
2. Syarat penyebut pecahan (penyebut $\neq 0$): $x - 5 \neq 0 \implies x \neq 5$.

Jadi, domain $h(x)$ adalah semua bilangan real $x \ge 2$, asalkan $x \neq 5$.

Mari kita evaluasi:
1. $x = 1$: Tidak memenuhi, karena $1 < 2$. Memicu akar negatif ($\sqrt{-1}$).
2. $x = 2$: Memenuhi, karena $2 \ge 2$ dan $2 \neq 5$. (Akar bernilai 0 diperbolehkan).
3. $x = 3$: Memenuhi.
4. $x = 4$: Memenuhi.
5. $x = 5$: Tidak memenuhi, akan menyebabkan penyebut menjadi 0.

Maka, jawaban yang benar adalah opsi **2, 3, dan 4**.

---
**Navigasi:**
- [⬅️ Kembali ke Materi](../fungsi.md)
