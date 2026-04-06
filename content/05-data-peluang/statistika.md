# Statistika

> **Elemen:** [Data & Peluang](./index.md) | **Kembali ke Home:** [🏠 README](../../README.md)

---

## 1. Kompetensi

Memahami, mengaplikasikan, dan bernalar yang lebih tinggi untuk menyelesaikan permasalahan terkait:
- Penyajian data dalam bentuk diagram batang, diagram garis, diagram lingkaran, grafik, tabel, dan bentuk visual
- Ukuran pemusatan dan penyebaran data tunggal dan data kelompok

---

## 2. Batasan Materi (PENTING)

> ⚠️ **Catatan Ujian:** Mencakup **data tunggal** dan **data kelompok**. Penyajian data meliputi diagram batang, garis, lingkaran, grafik, dan tabel.

---

## 3. Ringkasan Materi

### 3.1 Penyajian Data

| Jenis Diagram | Kegunaan |
|:--------------|:---------|
| **Diagram Batang** | Membandingkan frekuensi antar kategori |
| **Diagram Garis** | Menunjukkan tren/perubahan data terhadap waktu |
| **Diagram Lingkaran** | Menunjukkan proporsi/persentase bagian terhadap keseluruhan |
| **Tabel Frekuensi** | Mengelompokkan data berdasarkan kelas interval |
| **Histogram** | Diagram batang untuk data kontinu/kelompok |
| **Ogive** | Kurva frekuensi kumulatif |

### 3.2 Ukuran Pemusatan Data

#### Data Tunggal

| Ukuran | Rumus/Cara |
|:-------|:-----------|
| **Mean (Rata-rata)** | $\bar{x} = \frac{\sum x_i}{n}$ |
| **Median (Nilai Tengah)** | Data tengah setelah diurutkan |
| **Modus** | Nilai yang paling sering muncul |

**Median:**
- Jika $n$ ganjil: $Me = x_{\frac{n+1}{2}}$
- Jika $n$ genap: $Me = \frac{x_{\frac{n}{2}} + x_{\frac{n}{2}+1}}{2}$

#### Data Kelompok (Tabel Frekuensi)

**Mean:**

$$\bar{x} = \frac{\sum f_i \cdot x_i}{\sum f_i}$$

dengan $x_i$ = titik tengah kelas ke-$i$

**Median:**

$$Me = L + \left(\frac{\frac{n}{2} - F}{f_{\text{me}}}\right) \times c$$

| Simbol | Arti |
|:-------|:-----|
| $L$ | Tepi bawah kelas median |
| $n$ | Jumlah total frekuensi |
| $F$ | Frekuensi kumulatif sebelum kelas median |
| $f_{\text{me}}$ | Frekuensi kelas median |
| $c$ | Panjang kelas (lebar interval) |

**Modus:**

$$Mo = L + \left(\frac{d_1}{d_1 + d_2}\right) \times c$$

| Simbol | Arti |
|:-------|:-----|
| $L$ | Tepi bawah kelas modus |
| $d_1$ | Selisih frekuensi kelas modus dengan kelas sebelumnya |
| $d_2$ | Selisih frekuensi kelas modus dengan kelas sesudahnya |
| $c$ | Panjang kelas |

### 3.3 Ukuran Penyebaran Data

| Ukuran | Data Tunggal | Data Kelompok |
|:-------|:-------------|:--------------|
| **Jangkauan (Range)** | $R = x_{\max} - x_{\min}$ | $R = \text{batas atas tertinggi} - \text{batas bawah terendah}$ |
| **Varians** | $s^2 = \frac{\sum(x_i - \bar{x})^2}{n}$ | $s^2 = \frac{\sum f_i(x_i - \bar{x})^2}{\sum f_i}$ |
| **Simpangan Baku** | $s = \sqrt{s^2}$ | $s = \sqrt{s^2}$ |

**Kuartil (Data Tunggal):**
- $Q_1$ = Kuartil bawah (25%)
- $Q_2$ = Median (50%)
- $Q_3$ = Kuartil atas (75%)
- $\text{IQR} = Q_3 - Q_1$ (Jangkauan Interkuartil)

---

## 4. Contoh Soal & Pembahasan

### Soal 1 (Membaca Diagram — dari Juknis, Soal No. 8)

**Soal (Pilihan Ganda):**

Diagram batang menunjukkan produksi pakaian Bu Rahmi selama tahun 2020 (Januari-Desember). Peningkatan tertinggi jumlah produksi pakaian terjadi pada bulan ....

A. April  
B. Juni  
C. Juli  
D. September  
E. November

**Pembahasan:**

Peningkatan tertinggi = selisih terbesar antara bulan berturutan.

Perlu membaca diagram dan menghitung selisih produksi antar bulan berturutan. Bulan dengan selisih positif terbesar adalah jawabannya.

**Jawaban: E. November** ✅ (sesuai kunci Juknis)

---

### Soal 2 (Modus Data Kelompok — dari Juknis, Soal No. 9)

**Soal (Pilihan Ganda):**

Perhatikan data nilai ulangan matematika kelas XI SMA Z (data kelompok). Modus dari data tersebut adalah ....

A. 64,0  
B. 64,5  
C. 65,0  
D. 65,5  
E. 66,0

**Pembahasan:**

Menggunakan rumus modus data kelompok:

$$Mo = L + \left(\frac{d_1}{d_1 + d_2}\right) \times c$$

Berdasarkan tabel data di Juknis:
- $L$ = tepi bawah kelas modus
- $d_1$ dan $d_2$ dihitung dari selisih frekuensi

**Jawaban: C. 65,0** ✅ (sesuai kunci Juknis)

---

### Soal 3 (Rata-rata Gabungan — dari Juknis, Soal No. 16)

**Soal:**

Rata-rata nilai ulangan 17 murid adalah 83. Ada 3 murid ujian susulan sehingga rata-rata 20 murid menjadi 82. Tentukan pernyataan benar:

1. Jumlah nilai ketiga murid susulan = 229
2. Rata-rata nilai ketiga murid > 70
3. Nilai terendah ketiga murid ≥ 29
4. Nilai tertinggi ketiga murid > 76
5. Jangkauan data ketiga murid > 72

**Pembahasan:**

Jumlah nilai 17 murid: $17 \times 83 = 1.411$

Jumlah nilai 20 murid: $20 \times 82 = 1.640$

Jumlah nilai 3 murid susulan: $1.640 - 1.411 = 229$

**1. Jumlah = 229** → **Benar** ✅

Rata-rata 3 murid: $\frac{229}{3} = 76{,}\overline{3}$

**2. Rata-rata > 70** → $76{,}3 > 70$ → **Benar** ✅

**3. Nilai terendah ≥ 29**

Jika dua murid mendapat nilai maks (100): $100 + 100 + x = 229$ → $x = 29$

Maka nilai terendah minimal $= 29$ → **Benar** ✅

**4. Nilai tertinggi > 76**

Jika nilai sama semua → masing-masing $76{,}3$. Karena nilai bulat, minimal satu $\geq 77 > 76$ → **Benar** ✅

**5. Jangkauan > 72** → Tidak harus benar. Jika nilai: 76, 77, 76 → jangkauan = 1 → **Salah** ✅

**Jawaban: Pernyataan 1, 2, 3, dan 4 benar** ✅

---

### Soal 4 (Mean & Median — Level 2)

**Soal:**

Data: 5, 7, 3, 8, 6, 7, 9, 7, 4, 8. Tentukan mean, median, dan modus.

**Pembahasan:**

Data diurutkan: $3, 4, 5, 6, 7, 7, 7, 8, 8, 9$ ($n = 10$)

**Mean:** $\bar{x} = \frac{3+4+5+6+7+7+7+8+8+9}{10} = \frac{64}{10} = 6{,}4$

**Median:** $n = 10$ (genap) → $Me = \frac{x_5 + x_6}{2} = \frac{7 + 7}{2} = 7$

**Modus:** $Mo = 7$ (muncul 3 kali)

**Jawaban:** Mean = $6{,}4$, Median = $7$, Modus = $7$

## 5. Latihan Soal
Uji pemahaman terperinci Anda dengan mencoba [📝 Latihan Soal Statistika](./latihan/statistika.md).

---

**Navigasi:**
- [⬅️ Kembali ke Indeks Data & Peluang](./index.md)
- [➡️ Peluang](./peluang.md)
