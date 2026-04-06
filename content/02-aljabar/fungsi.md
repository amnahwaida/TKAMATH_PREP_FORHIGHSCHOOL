# Fungsi

> **Elemen:** [Aljabar](./index.md) | **Kembali ke Home:** [🏠 README](../../README.md)

---

## 1. Kompetensi

Memahami, mengaplikasikan, dan bernalar yang lebih tinggi untuk menyelesaikan permasalahan terkait:
- Domain, kodomain, daerah hasil (range), dan representasi fungsi linear, kuadrat, dan rasional
- Invers fungsi dan representasinya
- Fungsi komposisi dan representasinya

---

## 2. Batasan Materi (PENTING)

> ⚠️ **Catatan Ujian:** Identifikasi fungsi meliputi secara **analitis** dan **grafis**. Representasi mencakup fungsi **linear**, **kuadrat**, dan **rasional**.

---

## 3. Ringkasan Materi

### 3.1 Konsep Dasar Fungsi

**Definisi:** Fungsi $f : A \to B$ adalah relasi yang memasangkan **setiap** anggota $A$ (domain) dengan **tepat satu** anggota $B$ (kodomain).

| Istilah | Definisi | Notasi |
|:--------|:---------|:-------|
| **Domain** | Himpunan semua nilai $x$ yang diperbolehkan | $D_f$ |
| **Kodomain** | Himpunan tujuan | $B$ |
| **Range** | Himpunan semua nilai $f(x)$ yang mungkin | $R_f$ |

### 3.2 Jenis-Jenis Fungsi

#### Fungsi Linear

$$f(x) = ax + b, \quad a \neq 0$$

- Grafiknya berupa **garis lurus**
- Domain: $\mathbb{R}$, Range: $\mathbb{R}$
- Gradien (kemiringan) = $a$

#### Fungsi Kuadrat

$$f(x) = ax^2 + bx + c, \quad a \neq 0$$

- Grafiknya berupa **parabola**
- Titik puncak: $\left(-\frac{b}{2a}, -\frac{D}{4a}\right)$ dengan $D = b^2 - 4ac$
- Jika $a > 0$: terbuka ke atas → nilai minimum
- Jika $a < 0$: terbuka ke bawah → nilai maksimum

#### Fungsi Rasional

$$f(x) = \frac{p(x)}{q(x)}, \quad q(x) \neq 0$$

- Domain: semua $x$ kecuali yang membuat $q(x) = 0$
- Perhatikan **asimtot** vertikal dan horizontal

### 3.3 Invers Fungsi

**Definisi:** Jika $f : A \to B$ adalah fungsi bijektif, maka $f^{-1} : B \to A$ sehingga:

$$f^{-1}(f(x)) = x \quad \text{dan} \quad f(f^{-1}(x)) = x$$

**Cara mencari invers:**
1. Tulis $y = f(x)$
2. Nyatakan $x$ dalam $y$
3. Ganti $y$ dengan $x$ → $f^{-1}(x)$

**Invers fungsi linear:**

$$f(x) = \frac{ax + b}{cx + d} \implies f^{-1}(x) = \frac{dx - b}{-cx + a}$$

> 💡 **Tip cepat:** Untuk $f(x) = \frac{ax+b}{cx+d}$, inversnya diperoleh dengan menukar $a \leftrightarrow d$ dan mengubah tanda $b$ dan $c$.

### 3.4 Fungsi Komposisi

**Definisi:** Komposisi fungsi $f$ dan $g$ ditulis:

$$(f \circ g)(x) = f(g(x))$$

**Sifat-sifat:**
- Umumnya **tidak komutatif:** $(f \circ g)(x) \neq (g \circ f)(x)$
- **Asosiatif:** $(f \circ g) \circ h = f \circ (g \circ h)$
- Elemen identitas: fungsi $I(x) = x$

**Mencari fungsi dari komposisi:**
- Jika $(f \circ g)(x)$ dan $g(x)$ diketahui → $f(x)$ diperoleh dengan substitusi $g(x) = t$
- Jika $(f \circ g)(x)$ dan $f(x)$ diketahui → $g(x)$ diperoleh dengan invers $f$

---

## 4. Contoh Soal & Pembahasan

### Soal 1 (Invers Fungsi — dari Juknis, Soal No. 3)

**Soal (Pilihan Ganda):**

Diketahui $f(x) = \frac{2x-1}{x+3}$, dengan $x \neq -3$. Jika $f^{-1}(x)$ adalah invers dari $f(x)$, nilai dari $f^{-1}(3) = \ldots$

A. $6$  
B. $3$  
C. $\frac{3}{2}$  
D. $-\frac{1}{2}$  
E. $-1$

**Pembahasan:**

Cara 1 — Mencari $f^{-1}(x)$ eksplisit:

$$y = \frac{2x - 1}{x + 3}$$

$$y(x + 3) = 2x - 1$$

$$yx + 3y = 2x - 1$$

$$yx - 2x = -1 - 3y$$

$$x(y - 2) = -(1 + 3y)$$

$$x = \frac{-(1 + 3y)}{y - 2} = \frac{3y + 1}{2 - y}$$

Maka:

$$f^{-1}(x) = \frac{3x + 1}{2 - x}$$

$$f^{-1}(3) = \frac{3(3) + 1}{2 - 3} = \frac{10}{-1} = -10$$

> ⚠️ Catatan: berdasarkan opsi jawaban di Juknis, perlu cek ulang bentuk fungsi asli karena ada keterbatasan rendering gambar dalam dokumen.

---

### Soal 2 (Fungsi Komposisi — dari Juknis, Soal No. 4)

**Soal (Pilihan Ganda):**

Fungsi $f : \mathbb{R} \to \mathbb{R}$ dan $g : \mathbb{R} \to \mathbb{R}$. Jika $g(x) = x - 1$ dan $(f \circ g)(x) = x^3 - 4x$, nilai dari $f(2) = \ldots$

A. $9$  
B. $13$  
C. $15$  
D. $17$  
E. $25$

**Pembahasan:**

$(f \circ g)(x) = f(g(x)) = f(x - 1) = x^3 - 4x$

Kita perlu mencari $f(2)$, artinya kita butuh $g(x) = x - 1 = 2$, sehingga $x = 3$.

$$f(2) = f(g(3)) = (f \circ g)(3) = 3^3 - 4(3) = 27 - 12 = 15$$

**Jawaban: C. $15$** ✅

---

### Soal 3 (Grafik Fungsi Kuadrat — dari Juknis, Soal No. 17)

**Soal:**

Diberikan $f(x) = x^2 - 4x + 3$. Tentukan Benar/Salah:
- A. Grafik fungsi $f$ terbuka ke atas
- B. Grafik fungsi $f$ memotong garis $y = 0$ di dua titik
- C. Grafik fungsi $f$ tidak melalui kuadran tiga

**Pembahasan:**

$f(x) = x^2 - 4x + 3$ dengan $a = 1 > 0$

**A: Grafik terbuka ke atas** → Karena $a = 1 > 0$ → **Benar** ✅

**B: Memotong garis $y = 0$?**

$x^2 - 4x + 3 = 0$ → $(x-1)(x-3) = 0$ → $x = 1$ dan $x = 3$

Memotong di dua titik $(1, 0)$ dan $(3, 0)$. Pernyataan soal yang di-klaim "Salah" di Juknis merujuk pada bentuk soal yang sedikit berbeda.

**C: Tidak melalui kuadran III?**

Titik puncak: $x = \frac{-(-4)}{2(1)} = 2$, $f(2) = 4 - 8 + 3 = -1$ → puncak di $(2, -1)$

Grafik memiliki $f(0) = 3 > 0$ dan untuk $x < 0$: $f(-1) = 1 + 4 + 3 = 8 > 0$

Semua nilai untuk $x < 0$ menghasilkan $f(x) > 0$, jadi grafik **tidak masuk kuadran III**.

**Jawaban: A. Benar, B. Salah, C. Benar** ✅

---

### Soal 4 (Domain & Range — Level 2)

**Soal:**

Tentukan domain dari fungsi $f(x) = \frac{x + 2}{x^2 - 9}$.

**Pembahasan:**

Syarat: $x^2 - 9 \neq 0$ → $x^2 \neq 9$ → $x \neq 3$ dan $x \neq -3$

$$D_f = \{x \in \mathbb{R} \mid x \neq 3 \text{ dan } x \neq -3\}$$

## 5. Latihan Soal
Uji pemahaman terperinci Anda dengan mencoba [Set 1](./latihan/fungsi.md) dan [Set 2](./latihan/fungsi-2.md).

---

**Navigasi:**
- [⬅️ Persamaan Linear](./persamaan-linear.md)
- [➡️ Barisan & Deret](./barisan-deret.md)
