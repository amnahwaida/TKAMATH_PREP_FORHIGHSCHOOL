# Latihan Soal: Sistem Persamaan & Pertidaksamaan Linear

> **Elemen:** [Aljabar](../index.md) | **Materi:** [Persamaan Linear](../persamaan-linear.md) | **Kembali ke Home:** [🏠 README](../../../README.md)

---

## Soal 1: Pilihan Ganda (PG)
Diketahui sistem persamaan linear dua variabel sebagai berikut:
$$ \begin{cases} 2x + 3y = 12 \\ 4x - y = 10 \end{cases} $$
Nilai dari $x - y$ adalah ....

A. $1$  
B. $2$  
C. $3$  
D. $4$  
E. $5$

**Pembahasan:**
Gunakan metode eliminasi/substitusi. Dari persamaan (2):
$y = 4x - 10$

Substitusi ke persamaan (1):
$$ 2x + 3(4x - 10) = 12 $$
$$ 2x + 12x - 30 = 12 $$
$$ 14x = 42 \implies x = 3 $$

Substitusi nilai $x=3$ ke $y = 4x - 10$:
$$ y = 4(3) - 10 = 12 - 10 = 2 $$

Nilai dari $x - y = 3 - 2 = 1$.
Jawaban yang tepat adalah **A**.

---

## Soal 2: Pilihan Ganda Kompleks Kategori (Benar/Salah)
Seorang pedagang membeli 2 jenis buah. Harga 1 kg apel adalah Rp30.000 dan 1 kg jeruk adalah Rp20.000. Pedagang tersebut memiliki modal Rp600.000 dan keranjangnya hanya memuat maksimal 25 kg buah.
Misalkan $x$ = banyak apel (kg) dan $y$ = banyak jeruk (kg). Tentukan Benar atau Salah pernyataan mengenai model matematika program linear ini!

- A. $x + y \leq 25$
- B. $3x + 2y \leq 60$
- C. Jika pedagang membeli 15 kg apel, ia bisa memuat 10 kg jeruk tanpa melebihi modal.

**Pembahasan:**
Buat model matematika dari soal:
1. Kapasitas maksimum keranjang 25 kg: $x + y \leq 25$.
2. Modal Rp600.000: $30.000x + 20.000y \leq 600.000$ (disederhanakan dibagi 10.000 menjadi $3x + 2y \leq 60$).
3. Non-negatif: $x \geq 0, y \geq 0$.

Evaluasi pernyataan:
**A. $x + y \leq 25$**
Sesuai dengan kapasitas keranjang.
Kesimpulan: **Benar** ✔️

**B. $3x + 2y \leq 60$**
Sesuai dengan persamaan modal yang disederhanakan.
Kesimpulan: **Benar** ✔️

**C. Jika pedagang membeli 15 kg apel, ia bisa memuat 10 kg jeruk**
Cek kendala ke-1 (keranjang): $15 + 10 = 25 \leq 25$ (oke).
Cek kendala ke-2 (modal): $3(15) + 2(10) = 45 + 20 = 65$.
Padahal modal $65 > 60$. Ini berarti biayanya melebihi modal (Rp650.000 > Rp600.000). Jadi, pedagang tidak bisa memuat 10 kg jeruk.
Kesimpulan: **Salah** ❌

---

## Soal 3: Pilihan Ganda Kompleks MCMA (Lebih dari 1 Jawaban Benar)
Daerah penyelesaian yang memenuhi pertidaksamaan linear $2x + y \leq 8$, $x + 2y \leq 10$, $x \geq 0$, dan $y \geq 0$ memiliki beberapa titik sudut. Pilihlah titik-titik (absis, ordinat) mana saja yang merupakan titik sudut daerah fisibel tersebut!

- [ ] $(0, 0)$
- [ ] $(4, 0)$
- [ ] $(0, 5)$
- [ ] $(2, 4)$
- [ ] $(3, 2)$

**Pembahasan:**
Kita tentukan garis batas dan titik potong:
1. $2x + y = 8 \implies$ titik potong sumbu $x$ $(4,0)$ dan sumbu $y$ $(0,8)$.
2. $x + 2y = 10 \implies$ titik potong sumbu $x$ $(10,0)$ dan sumbu $y$ $(0,5)$.

Titik potong kedua garis:
Substitusi $y = 8 - 2x$ ke $x + 2y = 10$:
$$ x + 2(8 - 2x) = 10 $$
$$ x + 16 - 4x = 10 $$
$$ -3x = -6 \implies x = 2 $$
$$ y = 8 - 2(2) = 4 \implies (2, 4) $$

Titik-titik sudut dari daerah fisibel penyelesaian (di kuadran I, di bawah kedua garis):
- $(0,0)$ dari sumbu koordinat.
- $(4,0)$ dari titik terkecil di sumbu $x$ antara $(4,0)$ dan $(10,0)$.
- $(0,5)$ dari titik terkecil di sumbu $y$ antara $(0,8)$ dan $(0,5)$.
- $(2,4)$ dari titik perpotongan dua garis batas kendala.
Nilai $(3,2)$ berada DI DALAM daerah penyelesaian, bukan titik sudut (pojok).

Maka, jawaban yang benar adalah **1, 2, 3, dan 4 (titik $(0,0), (4,0), (0,5), (2,4)$)**.

---
**Navigasi:**
- [⬅️ Kembali ke Materi](../persamaan-linear.md)
