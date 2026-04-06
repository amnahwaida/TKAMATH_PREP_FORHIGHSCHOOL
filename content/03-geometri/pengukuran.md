# Pengukuran

> **Elemen:** [Geometri & Pengukuran](./index.md) | **Kembali ke Home:** [🏠 README](../../README.md)

---

## 1. Kompetensi

Memahami, mengaplikasikan, dan bernalar yang lebih tinggi untuk menyelesaikan permasalahan terkait:
- Keliling dan luas bangun datar
- Volume dan luas permukaan bangun ruang
- Jarak dua objek geometri

---

## 2. Batasan Materi (PENTING)

> ⚠️ **Catatan Ujian:** Jarak dua objek geometri meliputi:
> - Jarak dua titik
> - Jarak dua garis
> - Jarak dua bidang
> - Jarak titik dan garis
> - Jarak titik dan bidang

---

## 3. Ringkasan Materi

### 3.1 Keliling dan Luas Bangun Datar

| Bangun | Keliling | Luas |
|:-------|:---------|:-----|
| **Persegi** (sisi $s$) | $4s$ | $s^2$ |
| **Persegi Panjang** ($p, l$) | $2(p + l)$ | $p \times l$ |
| **Segitiga** (sisi $a, b, c$; tinggi $t$) | $a + b + c$ | $\frac{1}{2} \times a \times t$ |
| **Jajar Genjang** ($a, t$) | $2(a + b)$ | $a \times t$ |
| **Trapesium** ($a, b$ sejajar; $t$ tinggi) | Jumlah sisi | $\frac{1}{2}(a + b) \times t$ |
| **Belah Ketupat** ($d_1, d_2$ diagonal) | $4s$ | $\frac{1}{2} \times d_1 \times d_2$ |
| **Lingkaran** (jari-jari $r$) | $2\pi r$ | $\pi r^2$ |

**Rumus Heron** (segitiga dengan sisi $a, b, c$):

$$s = \frac{a + b + c}{2}$$

$$L = \sqrt{s(s-a)(s-b)(s-c)}$$

### 3.2 Volume dan Luas Permukaan Bangun Ruang

| Bangun | Volume | Luas Permukaan |
|:-------|:-------|:---------------|
| **Kubus** ($s$) | $s^3$ | $6s^2$ |
| **Balok** ($p, l, t$) | $plt$ | $2(pl + pt + lt)$ |
| **Prisma** | $L_{\text{alas}} \times t$ | $2L_{\text{alas}} + K_{\text{alas}} \times t$ |
| **Limas** | $\frac{1}{3} L_{\text{alas}} \times t$ | $L_{\text{alas}} + \Sigma L_{\text{sisi tegak}}$ |
| **Tabung** ($r, t$) | $\pi r^2 t$ | $2\pi r(r + t)$ |
| **Kerucut** ($r, t, s$) | $\frac{1}{3}\pi r^2 t$ | $\pi r(r + s)$ |
| **Bola** ($r$) | $\frac{4}{3}\pi r^3$ | $4\pi r^2$ |

> 💡 Garis pelukis kerucut: $s = \sqrt{r^2 + t^2}$

### 3.3 Jarak dalam Geometri

#### Jarak Dua Titik

$$d(A, B) = \sqrt{(x_2 - x_1)^2 + (y_2 - y_1)^2}$$

Dalam ruang 3D:

$$d(A, B) = \sqrt{(x_2-x_1)^2 + (y_2-y_1)^2 + (z_2-z_1)^2}$$

#### Jarak Titik ke Garis

Jarak titik $(x_0, y_0)$ ke garis $ax + by + c = 0$:

$$d = \frac{|ax_0 + by_0 + c|}{\sqrt{a^2 + b^2}}$$

#### Jarak Dua Garis Sejajar

Jarak antara garis $ax + by + c_1 = 0$ dan $ax + by + c_2 = 0$:

$$d = \frac{|c_1 - c_2|}{\sqrt{a^2 + b^2}}$$

#### Jarak dalam Bangun Ruang

Untuk menghitung jarak dalam bangun ruang (misalnya titik ke bidang diagonal):
1. Identifikasi objek-objek geometri yang terlibat
2. Buat garis tegak lurus dari objek pertama ke objek kedua
3. Hitung panjang garis tegak lurus tersebut menggunakan Pythagoras

---

## 4. Contoh Soal & Pembahasan

### Soal 1 (Volume Kotak — dari Juknis, Soal No. 6)

**Soal (Pilihan Ganda):**

Dari selembar karton persegi berukuran sisi 30 cm akan dibuat kotak tanpa tutup, dengan menggunting empat persegi di setiap pojok. Volume kotak terbesar yang dapat dibuat adalah ....

A. 2.000 cm³  
B. 3.000 cm³  
C. 4.000 cm³  
D. 5.000 cm³  
E. 6.000 cm³

**Pembahasan:**

Jika sisi persegi yang digunting = $x$ cm, maka:
- Panjang kotak = $30 - 2x$
- Lebar kotak = $30 - 2x$
- Tinggi kotak = $x$

$$V(x) = x(30 - 2x)^2$$

Untuk mencari volume maksimum, turunkan dan sama dengankan nol:

$$V(x) = x(900 - 120x + 4x^2) = 4x^3 - 120x^2 + 900x$$

$$V'(x) = 12x^2 - 240x + 900 = 0$$

$$x^2 - 20x + 75 = 0$$

$$(x - 5)(x - 15) = 0$$

$x = 5$ atau $x = 15$ (tidak valid karena $30 - 2(15) = 0$)

Maka $x = 5$:

$$V(5) = 5(30 - 10)^2 = 5 \times 400 = 2.000 \text{ cm}^3$$

**Jawaban: A. 2.000 cm³** ✅

---

### Soal 2 (Keliling & Luas Trapesium — dari Juknis, Soal No. 14)

**Soal:**

Trapesium ABCD dengan $AB \parallel CD$. Putuskan kecukupan informasi:
- (1) Luas trapesium ABCD = 24
- (2) BC = 10 dan CD = 5

A. Pernyataan (1) SAJA cukup  
B. Pernyataan (2) SAJA cukup  
C. DUA pernyataan BERSAMA-SAMA cukup  
D. Masing-masing SAJA cukup  
E. Tidak cukup

**Pembahasan:**

Luas trapesium: $L = \frac{1}{2}(AB + CD) \times t$

- Pernyataan (1): $L = 24$ — butuh informasi $AB$, $CD$, dan $t$ → **tidak cukup sendiri**
- Pernyataan (2): $BC = 10$, $CD = 5$ — memberikan ukuran sisi, tapi tanpa sisi sejajar lainnya dan tinggi → **bergantung tipe soal**

Dengan kedua informasi bersamaan bisa diperoleh keliling/informasi lebih lengkap.

**Jawaban: B** ✅ (sesuai kunci Juknis)

---

### Soal 3 (Jarak Titik ke Garis — Level 2)

**Soal:**

Tentukan jarak titik $P(3, 4)$ ke garis $3x + 4y - 5 = 0$.

**Pembahasan:**

$$d = \frac{|3(3) + 4(4) - 5|}{\sqrt{3^2 + 4^2}} = \frac{|9 + 16 - 5|}{\sqrt{25}} = \frac{20}{5} = 4$$

**Jawaban:** $4$ satuan

---

### Soal 4 (Volume Gabungan — Level 3)

**Soal:**

Sebuah bangun ruang gabungan terdiri dari balok berukuran $6 \times 4 \times 3$ cm dengan setengah tabung (diameter 4 cm, panjang 6 cm) di atasnya. Hitunglah volume total.

**Pembahasan:**

Volume balok: $V_1 = 6 \times 4 \times 3 = 72$ cm³

Volume setengah tabung: $r = 2$ cm

$$V_2 = \frac{1}{2} \times \pi r^2 \times t = \frac{1}{2} \times \pi (4) \times 6 = 12\pi \approx 37{,}7 \text{ cm}^3$$

$$V_{\text{total}} = 72 + 12\pi \approx 109{,}7 \text{ cm}^3$$

**Jawaban:** $(72 + 12\pi)$ cm³

## 5. Latihan Soal
Uji pemahaman terperinci Anda dengan mencoba [Set 1](./latihan/pengukuran.md) , [Set 2](./latihan/pengukuran-2.md), dan [Set 3](./latihan/pengukuran-3.md).

---

**Navigasi:**
- [⬅️ Transformasi Geometri](./transformasi.md)
- [⬅️ Kembali ke Indeks Geometri](./index.md)
- [➡️ Elemen 4: Trigonometri](../04-trigonometri/index.md)
