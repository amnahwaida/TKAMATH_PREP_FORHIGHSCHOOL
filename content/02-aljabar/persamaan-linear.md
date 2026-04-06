# Sistem Persamaan & Pertidaksamaan Linear

> **Elemen:** [Aljabar](./index.md) | **Kembali ke Home:** [🏠 README](../../README.md)

---

## 1. Kompetensi

Memahami, mengaplikasikan, dan bernalar yang lebih tinggi untuk menyelesaikan permasalahan terkait:
- Sistem persamaan linear multivariabel
- Sistem pertidaksamaan linear multivariabel
- Program linear

---

## 2. Batasan Materi (PENTING)

> ⚠️ **Catatan Ujian:** Maksimum banyaknya variabel yang digunakan adalah **tiga variabel**. Soal tidak akan melebihi batas ini.

---

## 3. Ringkasan Materi

### 3.1 Sistem Persamaan Linear Dua Variabel (SPLDV)

**Bentuk umum:**

$$\begin{cases} a_1x + b_1y = c_1 \\ a_2x + b_2y = c_2 \end{cases}$$

**Metode penyelesaian:**

| Metode | Cara |
|:-------|:-----|
| **Substitusi** | Nyatakan satu variabel dalam variabel lain, lalu substitusi |
| **Eliminasi** | Eliminasi salah satu variabel dengan menyamakan koefisien |
| **Grafik** | Cari titik potong dua garis |
| **Campuran** | Kombinasi substitusi dan eliminasi |

### 3.2 Sistem Persamaan Linear Tiga Variabel (SPLTV)

**Bentuk umum:**

$$\begin{cases} a_1x + b_1y + c_1z = d_1 \\ a_2x + b_2y + c_2z = d_2 \\ a_3x + b_3y + c_3z = d_3 \end{cases}$$

**Strategi penyelesaian:**
1. Eliminasi satu variabel dari dua pasang persamaan → dapat SPLDV
2. Selesaikan SPLDV tersebut
3. Substitusi balik untuk mencari variabel ketiga

### 3.3 Pertidaksamaan Linear Dua Variabel

**Bentuk umum:**

$$ax + by \leq c \quad \text{atau} \quad ax + by \geq c$$

**Langkah menentukan daerah penyelesaian:**
1. Gambar garis batas $ax + by = c$
2. Ambil titik uji (biasanya titik $O(0,0)$)
3. Arsir daerah yang memenuhi pertidaksamaan

### 3.4 Program Linear

**Komponen:**
- **Fungsi objektif:** $f(x, y) = ax + by$ → dimaksimumkan/diminimumkan
- **Kendala (constraints):** Sistem pertidaksamaan linear
- **Daerah fisibel:** Daerah yang memenuhi semua kendala

**Metode penyelesaian:**
1. Gambar daerah fisibel dari semua kendala
2. Tentukan titik-titik sudut (pojok) daerah fisibel
3. Substitusi titik sudut ke fungsi objektif
4. Nilai terbesar = maksimum, nilai terkecil = minimum

**Titik sudut diperoleh dari perpotongan garis-garis batas:**

$$\text{Titik sudut} = \text{perpotongan garis kendala}$$

---

## 4. Contoh Soal & Pembahasan

### Soal 1 (SPLDV — dari Juknis, Soal No. 1)

**Soal (Pilihan Ganda):**

Harga 3 buah buku dan 2 buah penggaris Rp18.000,00. Jika harga sebuah buku Rp1.000,00 lebih mahal dari sebuah penggaris, harga 2 buah buku dan 5 buah penggaris adalah ....

A. Rp19.000,00  
B. Rp23.000,00  
C. Rp25.000,00  
D. Rp27.000,00  
E. Rp30.000,00

**Pembahasan:**

Misalkan: $b$ = harga buku, $p$ = harga penggaris

$$3b + 2p = 18.000 \quad \cdots (1)$$

$$b = p + 1.000 \quad \cdots (2)$$

Substitusi (2) ke (1):

$$3(p + 1.000) + 2p = 18.000$$

$$5p + 3.000 = 18.000 \implies p = 3.000$$

$$b = 4.000$$

Yang ditanya: $2b + 5p = 2(4.000) + 5(3.000) = 8.000 + 15.000 = 23.000$

**Jawaban: B. Rp23.000,00** ✅

---

### Soal 2 (Pertidaksamaan Linear — dari Juknis, Soal No. 2)

**Soal (Pilihan Ganda):**

Daerah yang memenuhi sistem pertidaksamaan linear $x + y \leq 5$, $x \geq 0$, $y \geq 0$ ditunjukkan oleh daerah ....

**Pembahasan:**

Langkah penyelesaian:
1. Gambar garis $x + y = 5$ (memotong sumbu $x$ di $(5, 0)$ dan sumbu $y$ di $(0, 5)$)
2. Uji titik $O(0, 0)$: $0 + 0 = 0 \leq 5$ ✅ → daerah yang memuat titik asal
3. Dengan $x \geq 0$ dan $y \geq 0$, daerah penyelesaian berada di **kuadran I**

**Jawaban: Daerah segitiga di kuadran I di bawah garis** $x + y = 5$

---

### Soal 3 (Program Linear — dari Juknis, Soal No. 12)

**Soal:**

Mirna akan memproduksi dua jenis kue dengan modal Rp8.000.000,00. Biaya produksi kue bolu Rp15.000 per kotak (laba 40%) dan kue brownies Rp20.000 per kotak (laba 35%). Setiap hari maksimal 500 kotak kue.

Tentukan Benar/Salah:
- A. Mirna harus memproduksi 200 kotak kue bolu
- B. Mirna harus memproduksi kue brownies lebih banyak
- C. Keuntungan maksimum Rp3.100.000,00

**Pembahasan:**

Misalkan: $x$ = kotak bolu, $y$ = kotak brownies

**Kendala:**
$$15.000x + 20.000y \leq 8.000.000 \implies 3x + 4y \leq 1.600$$

$$x + y \leq 500$$

$$x \geq 0, \quad y \geq 0$$

**Fungsi objektif (keuntungan):**

$$f(x, y) = 0.4(15.000)x + 0.35(20.000)y = 6.000x + 7.000y$$

**Titik-titik sudut:**
- $(0, 0)$: $f = 0$
- $(500, 0)$: cek kendala 1 → $3(500) = 1.500 \leq 1.600$ ✅ → $f = 3.000.000$
- Perpotongan $3x + 4y = 1.600$ dan $x + y = 500$:
  - Dari $x + y = 500$ → $x = 500 - y$
  - $3(500 - y) + 4y = 1.600$ → $1.500 + y = 1.600$ → $y = 100$, $x = 400$
  - $f(400, 100) = 6.000(400) + 7.000(100) = 2.400.000 + 700.000 = 3.100.000$
- $(0, 400)$: cek $4(400) = 1.600 \leq 1.600$ ✅ → $f = 2.800.000$

**Keuntungan maksimum:** $f(400, 100) = \text{Rp}3.100.000$

**Hasil:**
- A. **Salah** ✅ (harus 400 kotak bolu, bukan 200)
- B. **Salah** ✅ (bolu lebih banyak: 400 > 100)
- C. **Benar** ✅ (keuntungan max = Rp3.100.000)

---

### Soal 4 (SPLTV — Level 3)

**Soal:**

Tentukan nilai $x + y + z$ jika:

$$\begin{cases} x + y + z = 12 \\ 2x - y + z = 7 \\ x + 2y - z = 5 \end{cases}$$

**Pembahasan:**

Dari persamaan pertama, langsung diperoleh:

$$x + y + z = 12$$

**Jawaban:** $12$

> 💡 **Tip:** Perhatikan soal baik-baik. Terkadang jawaban sudah ada langsung pada persamaan yang diberikan!

## 5. Latihan Soal
Uji pemahaman terperinci Anda dengan mencoba [Set 1](./latihan/persamaan-linear.md) dan [Set 2](./latihan/persamaan-linear-2.md).

---

**Navigasi:**
- [⬅️ Kembali ke Indeks Aljabar](./index.md)
- [➡️ Fungsi](./fungsi.md)
