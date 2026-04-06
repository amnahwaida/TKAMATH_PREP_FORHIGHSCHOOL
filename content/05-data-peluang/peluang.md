# Peluang

> **Elemen:** [Data & Peluang](./index.md) | **Kembali ke Home:** [🏠 README](../../README.md)

---

## 1. Kompetensi

Memahami, mengaplikasikan, dan bernalar yang lebih tinggi untuk menyelesaikan permasalahan terkait:
- Aturan pencacahan (aturan penjumlahan, aturan perkalian, permutasi, dan kombinasi)
- Peluang suatu kejadian

---

## 2. Batasan Materi (PENTING)

> ⚠️ **Catatan Ujian:** Mencakup aturan pencacahan lengkap (**penjumlahan**, **perkalian**, **permutasi**, **kombinasi**) dan **peluang kejadian majemuk**.

---

## 3. Ringkasan Materi

### 3.1 Aturan Pencacahan

#### Aturan Penjumlahan

Jika kejadian $A$ dapat terjadi dengan $m$ cara **ATAU** kejadian $B$ dengan $n$ cara, dan kedua kejadian saling lepas:

$$n(A \cup B) = m + n$$

#### Aturan Perkalian

Jika kejadian $A$ dilakukan dengan $m$ cara **DAN** kejadian $B$ dengan $n$ cara:

$$n(A \cap B) = m \times n$$

### 3.2 Faktorial

$$n! = n \times (n-1) \times (n-2) \times \cdots \times 2 \times 1$$

**Kasus khusus:** $0! = 1$ dan $1! = 1$

| $n$ | $n!$ |
|:---:|:----:|
| 3 | 6 |
| 4 | 24 |
| 5 | 120 |
| 6 | 720 |
| 7 | 5.040 |
| 8 | 40.320 |
| 9 | 362.880 |
| 10 | 3.628.800 |

### 3.3 Permutasi

Banyak cara menyusun $r$ objek dari $n$ objek (**urutan penting**):

$$P(n, r) = \frac{n!}{(n-r)!}$$

**Kasus khusus:**
- Permutasi semua objek: $P(n, n) = n!$
- Permutasi siklis (lingkaran): $(n-1)!$
- Permutasi dengan unsur sama: $\frac{n!}{n_1! \cdot n_2! \cdot \ldots \cdot n_k!}$

### 3.4 Kombinasi

Banyak cara memilih $r$ objek dari $n$ objek (**urutan tidak penting**):

$$C(n, r) = \binom{n}{r} = \frac{n!}{r!(n-r)!}$$

**Sifat penting:**

$$C(n, r) = C(n, n-r)$$

$$C(n, 0) = C(n, n) = 1$$

### 3.5 Peluang

**Definisi klasik:**

$$P(A) = \frac{n(A)}{n(S)}$$

dengan:
- $n(A)$ = banyak kejadian $A$ yang diinginkan
- $n(S)$ = banyak seluruh kejadian (ruang sampel)

**Sifat-sifat:**

$$0 \leq P(A) \leq 1$$

$$P(A) + P(A') = 1 \quad \text{(komplemen)}$$

### 3.6 Peluang Kejadian Majemuk

#### Kejadian Saling Lepas (Mutually Exclusive)

$$P(A \cup B) = P(A) + P(B)$$

#### Kejadian Tidak Saling Lepas

$$P(A \cup B) = P(A) + P(B) - P(A \cap B)$$

#### Kejadian Independen

$$P(A \cap B) = P(A) \times P(B)$$

#### Kejadian Bersyarat (Conditional)

$$P(A | B) = \frac{P(A \cap B)}{P(B)}$$

#### Peluang Berurutan Tanpa Pengembalian

Jika pengambilan dilakukan satu per satu tanpa dikembalikan:

$$P = \frac{n_1}{N} \times \frac{n_2}{N-1} \times \cdots$$

---

## 4. Contoh Soal & Pembahasan

### Soal 1 (Peluang Berurutan — dari Juknis, Soal No. 10)

**Soal (Pilihan Ganda):**

Sekolah P mengirim 2 perwakilan grup band dari 6 grup putra dan 4 grup putri. Kemampuan merata, pengambilan acak satu per satu. Peluang terambil grup band putra pertama dan putri kedua adalah ....

A. $\frac{4}{15}$  
B. $\frac{2}{15}$  
C. $\frac{4}{15}$  
D. $\frac{3}{10}$  
E. $\frac{2}{5}$

**Pembahasan:**

Total grup = $6 + 4 = 10$

Pengambilan tanpa pengembalian:

$$P = P(\text{putra pertama}) \times P(\text{putri kedua | putra sudah terambil})$$

$$P = \frac{6}{10} \times \frac{4}{9} = \frac{24}{90} = \frac{4}{15}$$

**Jawaban: C. $\frac{4}{15}$** ✅

---

### Soal 2 (Aturan Pencacahan — dari Juknis, Soal No. 20)

**Soal (Pilihan Ganda):**

Kode akses kupon bazar memiliki 5 karakter: ABC-XY, di mana A, B, C = huruf dan X, Y = angka. Tidak boleh ada huruf dan angka yang diulang. Berapa banyak kode akses berbeda?

A. 1.263.600  
B. 1.352.000  
C. 1.404.000  
D. 1.423.656  
E. 1.757.600

**Pembahasan:**

Huruf: 26 pilihan (alfabet), tidak boleh diulang

$$\text{Cara memilih 3 huruf} = P(26, 3) = 26 \times 25 \times 24 = 15.600$$

Angka: 10 pilihan (0-9), tidak boleh diulang

$$\text{Cara memilih 2 angka} = P(10, 2) = 10 \times 9 = 90$$

Total kode:

$$N = 15.600 \times 90 = 1.404.000$$

**Jawaban: C. 1.404.000** ✅

---

### Soal 3 (Kombinasi — Level 2)

**Soal:**

Dari 8 siswa, akan dipilih 3 siswa sebagai pengurus kelas. Berapa banyak cara pemilihan?

**Pembahasan:**

Urutan tidak penting (panitia = kombinasi):

$$C(8, 3) = \frac{8!}{3! \cdot 5!} = \frac{8 \times 7 \times 6}{3 \times 2 \times 1} = 56$$

**Jawaban:** 56 cara

---

### Soal 4 (Peluang Komplemen — Level 3)

**Soal:**

Dua dadu dilempar bersamaan. Berapa peluang jumlah mata dadu **tidak sama dengan 7**?

**Pembahasan:**

$n(S) = 6 \times 6 = 36$

Kejadian jumlah = 7: $(1,6), (2,5), (3,4), (4,3), (5,2), (6,1)$ → $n(A) = 6$

$$P(\text{jumlah} = 7) = \frac{6}{36} = \frac{1}{6}$$

$$P(\text{jumlah} \neq 7) = 1 - \frac{1}{6} = \frac{5}{6}$$

**Jawaban:** $\frac{5}{6}$

## 5. Latihan Soal
Uji pemahaman terperinci Anda dengan mencoba [Set 1](./latihan/peluang.md) , [Set 2](./latihan/peluang-2.md), [Set 3](./latihan/peluang-3.md), dan [Set 4](./latihan/peluang-4.md).

---

**Navigasi:**
- [⬅️ Statistika](./statistika.md)
- [⬅️ Kembali ke Indeks Data & Peluang](./index.md)
- [🏠 Home](../../README.md)
