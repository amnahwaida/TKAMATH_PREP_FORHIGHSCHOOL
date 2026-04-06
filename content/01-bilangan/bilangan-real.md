# Bilangan Real

> **Elemen:** [Bilangan](./index.md) | **Kembali ke Home:** [🏠 README](../../README.md)

---

## 1. Kompetensi

Memahami, mengaplikasikan, dan bernalar yang lebih tinggi untuk menyelesaikan permasalahan terkait:
- Jenis dan sifat bilangan
- Operasi bilangan (penjumlahan, pengurangan, perkalian, pembagian, dan gabungannya) beserta sifat-sifatnya

---

## 2. Batasan Materi (PENTING)

> ⚠️ **Catatan Ujian:** Bilangan meliputi **bilangan real**, termasuk bilangan asli berpangkat bilangan bulat atau berpangkat bilangan pecahan. Sifat operasi yang diuji: **komutatif, asosiatif, dan distributif**.

---

## 3. Ringkasan Materi

### 3.1 Jenis-Jenis Bilangan

Bilangan real ( $\mathbb{R}$ ) terdiri dari:

| Jenis | Simbol | Contoh | Keterangan |
|:------|:------:|:-------|:-----------|
| Bilangan Asli | $\mathbb{N}$ | $1, 2, 3, \ldots$ | Bilangan bulat positif |
| Bilangan Cacah | $\mathbb{W}$ | $0, 1, 2, 3, \ldots$ | Bilangan asli + nol |
| Bilangan Bulat | $\mathbb{Z}$ | $\ldots, -2, -1, 0, 1, 2, \ldots$ | Positif, negatif, dan nol |
| Bilangan Rasional | $\mathbb{Q}$ | $\frac{1}{2}, 0.75, -3$ | Dapat dinyatakan sebagai $\frac{p}{q}$, $q \neq 0$ |
| Bilangan Irasional | $\mathbb{Q}'$ | $\sqrt{2}, \pi, e$ | Tidak dapat dinyatakan sebagai pecahan |

**Hubungan:**

$$\mathbb{N} \subset \mathbb{W} \subset \mathbb{Z} \subset \mathbb{Q} \subset \mathbb{R}$$

### 3.2 Sifat-Sifat Operasi Bilangan

Untuk semua $a, b, c \in \mathbb{R}$:

| Sifat | Penjumlahan | Perkalian |
|:------|:------------|:----------|
| **Komutatif** | $a + b = b + a$ | $a \times b = b \times a$ |
| **Asosiatif** | $(a + b) + c = a + (b + c)$ | $(a \times b) \times c = a \times (b \times c)$ |
| **Distributif** | — | $a \times (b + c) = a \times b + a \times c$ |
| **Elemen Identitas** | $a + 0 = a$ | $a \times 1 = a$ |
| **Invers** | $a + (-a) = 0$ | $a \times \frac{1}{a} = 1$ (untuk $a \neq 0$) |

### 3.3 Bilangan Berpangkat

#### Pangkat Bilangan Bulat

Untuk $a \in \mathbb{R}$ dan $n \in \mathbb{Z}$:

| Aturan | Rumus |
|:-------|:------|
| Pangkat positif | $a^n = \underbrace{a \times a \times \cdots \times a}_{n \text{ kali}}$ |
| Pangkat nol | $a^0 = 1$ (untuk $a \neq 0$) |
| Pangkat negatif | $a^{-n} = \frac{1}{a^n}$ (untuk $a \neq 0$) |

#### Pangkat Bilangan Pecahan (Bentuk Akar)

$$a^{\frac{m}{n}} = \sqrt[n]{a^m} = \left(\sqrt[n]{a}\right)^m$$

**Contoh:**
- $8^{\frac{1}{3}} = \sqrt[3]{8} = 2$
- $4^{\frac{3}{2}} = (\sqrt{4})^3 = 2^3 = 8$
- $27^{\frac{2}{3}} = (\sqrt[3]{27})^2 = 3^2 = 9$

### 3.4 Sifat-Sifat Operasi Pangkat

Untuk $a, b \in \mathbb{R}$ dan $m, n \in \mathbb{Q}$:

| No | Sifat | Rumus |
|:--:|:------|:------|
| 1 | Perkalian basis sama | $a^m \times a^n = a^{m+n}$ |
| 2 | Pembagian basis sama | $\frac{a^m}{a^n} = a^{m-n}$ |
| 3 | Pangkat dari pangkat | $(a^m)^n = a^{m \cdot n}$ |
| 4 | Pangkat perkalian | $(a \times b)^n = a^n \times b^n$ |
| 5 | Pangkat pembagian | $\left(\frac{a}{b}\right)^n = \frac{a^n}{b^n}$ |

### 3.5 Operasi Bentuk Akar

**Penyederhanaan:**

$$\sqrt{a \times b} = \sqrt{a} \times \sqrt{b}$$

$$\sqrt{\frac{a}{b}} = \frac{\sqrt{a}}{\sqrt{b}}$$

**Merasionalkan penyebut:**

$$\frac{a}{\sqrt{b}} = \frac{a}{\sqrt{b}} \times \frac{\sqrt{b}}{\sqrt{b}} = \frac{a\sqrt{b}}{b}$$

$$\frac{a}{\sqrt{b} + \sqrt{c}} = \frac{a(\sqrt{b} - \sqrt{c})}{b - c}$$

---

## 4. Contoh Soal & Pembahasan

### Soal 1 (Level 1 — Pengetahuan)

**Soal:**

Tentukan nilai dari:

$$\frac{\sqrt{18} + \sqrt{32}}{\sqrt{2}}$$

**Pembahasan:**

Langkah 1: Sederhanakan bentuk akar

$$\sqrt{18} = \sqrt{9 \times 2} = 3\sqrt{2}$$

$$\sqrt{32} = \sqrt{16 \times 2} = 4\sqrt{2}$$

Langkah 2: Substitusi dan hitung

$$\frac{3\sqrt{2} + 4\sqrt{2}}{\sqrt{2}} = \frac{7\sqrt{2}}{\sqrt{2}} = 7$$

**Jawaban:** $7$

---

### Soal 2 (Level 2 — Aplikasi)

**Soal:**

Sederhanakan:

$$\frac{2^3 \times 4^2}{8^2}$$

**Pembahasan:**

Langkah 1: Ubah semua ke basis 2

$$4^2 = (2^2)^2 = 2^4$$

$$8^2 = (2^3)^2 = 2^6$$

Langkah 2: Hitung

$$\frac{2^3 \times 2^4}{2^6} = \frac{2^{3+4}}{2^6} = \frac{2^7}{2^6} = 2^{7-6} = 2^1 = 2$$

**Jawaban:** $2$

---

### Soal 3 (Level 3 — Penalaran)

**Soal:**

Jika $x = \sqrt{5} + \sqrt{3}$ dan $y = \sqrt{5} - \sqrt{3}$, tentukan nilai dari $x^2 + y^2$.

**Pembahasan:**

Langkah 1: Hitung $x^2$

$$x^2 = (\sqrt{5} + \sqrt{3})^2 = 5 + 2\sqrt{15} + 3 = 8 + 2\sqrt{15}$$

Langkah 2: Hitung $y^2$

$$y^2 = (\sqrt{5} - \sqrt{3})^2 = 5 - 2\sqrt{15} + 3 = 8 - 2\sqrt{15}$$

Langkah 3: Jumlahkan

$$x^2 + y^2 = (8 + 2\sqrt{15}) + (8 - 2\sqrt{15}) = 16$$

**Jawaban:** $16$

---

### Soal 4 (Tipe Soal Ujian — dari Juknis)

**Soal (Pilihan Ganda):**

Harga 3 buah buku dan 2 buah penggaris Rp18.000,00. Jika harga sebuah buku Rp1.000,00 lebih mahal dari sebuah penggaris, harga 2 buah buku dan 5 buah penggaris adalah ....

A. Rp19.000,00  
B. Rp23.000,00  
C. Rp25.000,00  
D. Rp27.000,00  
E. Rp30.000,00

**Pembahasan:**

Misalkan:
- Harga buku = $b$
- Harga penggaris = $p$

Dari soal:
- $3b + 2p = 18.000$ ... (1)
- $b = p + 1.000$ ... (2)

Substitusi (2) ke (1):

$$3(p + 1.000) + 2p = 18.000$$

$$3p + 3.000 + 2p = 18.000$$

$$5p = 15.000$$

$$p = 3.000$$

Maka $b = 3.000 + 1.000 = 4.000$

Harga 2 buku dan 5 penggaris:

$$2(4.000) + 5(3.000) = 8.000 + 15.000 = 23.000$$

**Jawaban: B. Rp23.000,00** ✅

## 5. Latihan Soal
Uji pemahaman terperinci Anda dengan mencoba [Set 1](./latihan/bilangan-real.md) dan [Set 2](./latihan/bilangan-real-2.md).

---

**Navigasi:**
- [⬅️ Kembali ke Indeks Bilangan](./index.md)
- [➡️ Elemen 2: Aljabar](../02-aljabar/index.md)
