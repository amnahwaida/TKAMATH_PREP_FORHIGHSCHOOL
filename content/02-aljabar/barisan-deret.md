# Barisan dan Deret

> **Elemen:** [Aljabar](./index.md) | **Kembali ke Home:** [🏠 README](../../README.md)

---

## 1. Kompetensi

Memahami, mengaplikasikan, dan bernalar yang lebih tinggi untuk menyelesaikan permasalahan terkait:
- Barisan dan deret aritmetika
- Barisan dan deret geometri

---

## 2. Batasan Materi (PENTING)

> ⚠️ **Catatan Ujian:** Penerapan barisan dan deret termasuk dalam masalah **pertumbuhan, peluruhan, bunga tunggal, dan bunga majemuk**.

---

## 3. Ringkasan Materi

### 3.1 Barisan dan Deret Aritmetika

**Barisan aritmetika** memiliki **beda** (selisih) tetap antara suku berturutan.

| Komponen | Rumus |
|:---------|:------|
| Suku ke-$n$ | $U_n = a + (n-1)b$ |
| Jumlah $n$ suku pertama | $S_n = \frac{n}{2}(2a + (n-1)b)$ |
| Jumlah $n$ suku pertama (alternatif) | $S_n = \frac{n}{2}(a + U_n)$ |

Dengan:
- $a = U_1$ = suku pertama
- $b$ = beda = $U_n - U_{n-1}$
- $n$ = banyak suku

**Sifat penting:**

$$U_n = S_n - S_{n-1} \quad \text{untuk } n \geq 2$$

### 3.2 Barisan dan Deret Geometri

**Barisan geometri** memiliki **rasio** tetap antara suku berturutan.

| Komponen | Rumus |
|:---------|:------|
| Suku ke-$n$ | $U_n = a \cdot r^{n-1}$ |
| Jumlah $n$ suku pertama | $S_n = \frac{a(r^n - 1)}{r - 1}$ untuk $r > 1$ |
| Jumlah $n$ suku pertama | $S_n = \frac{a(1 - r^n)}{1 - r}$ untuk $r < 1$ |
| Jumlah tak hingga | $S_\infty = \frac{a}{1 - r}$ untuk $|r| < 1$ |

Dengan:
- $a = U_1$ = suku pertama
- $r$ = rasio = $\frac{U_n}{U_{n-1}}$

### 3.3 Aplikasi: Pertumbuhan dan Peluruhan

**Pertumbuhan (Growth):**

$$N(t) = N_0 \cdot (1 + p)^t$$

**Peluruhan (Decay):**

$$N(t) = N_0 \cdot (1 - p)^t$$

Dengan:
- $N_0$ = nilai awal
- $p$ = persentase pertumbuhan/peluruhan per periode
- $t$ = waktu (jumlah periode)

### 3.4 Aplikasi: Bunga Tunggal dan Majemuk

#### Bunga Tunggal

$$M = M_0 \left(1 + \frac{p \cdot t}{100}\right)$$

**Bunga hanya dihitung dari modal awal.**

#### Bunga Majemuk (Compound Interest)

$$M = M_0 \left(1 + \frac{p}{100}\right)^t$$

**Bunga dihitung dari modal + bunga periode sebelumnya** → membentuk barisan geometri.

| | Bunga Tunggal | Bunga Majemuk |
|:--|:-------------|:--------------|
| Pola | Aritmetika (linear) | Geometri (eksponensial) |
| Pertumbuhan | Konstan | Semakin besar |
| Rumus | $M_0(1 + pt)$ | $M_0(1 + p)^t$ |

---

## 4. Contoh Soal & Pembahasan

### Soal 1 (Deret Geometri & Pertumbuhan — dari Juknis, Soal No. 5)

**Soal (Pilihan Ganda):**

Seorang peneliti mengamati bakteri. Setiap $\frac{1}{2}$ hari bakteri membelah diri menjadi dua. Pada awal pengamatan terdapat 2 bakteri. Jika setiap 2 hari $\frac{1}{4}$ dari jumlah bakteri mati, banyaknya bakteri setelah tiga hari adalah ....

A. 48 bakteri  
B. 64 bakteri  
C. 96 bakteri  
D. 128 bakteri  
E. 192 bakteri

**Pembahasan:**

Bakteri membelah setiap $\frac{1}{2}$ hari → dalam 1 hari: $2^2 = 4$ kali lipat.

**Hari ke-0:** 2 bakteri

**Hari ke-1:** $2 \times 4 = 8$ bakteri

**Hari ke-2:** $8 \times 4 = 32$ bakteri, lalu $\frac{1}{4}$ mati → sisa $= 32 \times \frac{3}{4} = 24$

> Catatan: Tiap 2 hari, $\frac{1}{4}$ mati di akhir hari ke-2.

**Hari ke-3:** $24 \times 4 = 96$ bakteri

**Jawaban: C. 96 bakteri** ✅

---

### Soal 2 (Barisan Aritmetika — Level 1)

**Soal:**

Suku ke-10 dari barisan $3, 7, 11, 15, \ldots$ adalah ....

**Pembahasan:**

$a = 3$, $b = 7 - 3 = 4$

$$U_{10} = a + (10-1)b = 3 + 9(4) = 3 + 36 = 39$$

**Jawaban:** $39$

---

### Soal 3 (Bunga Majemuk — Level 2)

**Soal:**

Andi menabung Rp5.000.000 di bank dengan bunga majemuk 10% per tahun. Berapakah tabungan Andi setelah 3 tahun?

**Pembahasan:**

$$M = M_0 \left(1 + \frac{p}{100}\right)^t = 5.000.000 \times (1,1)^3$$

$$M = 5.000.000 \times 1,331 = 6.655.000$$

**Jawaban:** Rp6.655.000

---

### Soal 4 (Deret Geometri Tak Hingga — Level 3)

**Soal:**

Tentukan nilai dari $\displaystyle 1 + \frac{1}{2} + \frac{1}{4} + \frac{1}{8} + \cdots$

**Pembahasan:**

Ini adalah deret geometri tak hingga dengan $a = 1$ dan $r = \frac{1}{2}$.

Karena $|r| = \frac{1}{2} < 1$:

$$S_\infty = \frac{a}{1 - r} = \frac{1}{1 - \frac{1}{2}} = \frac{1}{\frac{1}{2}} = 2$$

**Jawaban:** $2$

## 5. Latihan Soal
Uji pemahaman terperinci Anda dengan mencoba [📝 Latihan Soal Barisan dan Deret](./latihan/barisan-deret.md).

---

**Navigasi:**
- [⬅️ Fungsi](./fungsi.md)
- [⬅️ Kembali ke Indeks Aljabar](./index.md)
- [➡️ Elemen 3: Geometri](../03-geometri/index.md)
