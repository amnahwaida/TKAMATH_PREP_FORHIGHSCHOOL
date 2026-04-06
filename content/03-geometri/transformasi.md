# Transformasi Geometri

> **Elemen:** [Geometri & Pengukuran](./index.md) | **Kembali ke Home:** [🏠 README](../../README.md)

---

## 1. Kompetensi

Memahami, mengaplikasikan, dan bernalar yang lebih tinggi untuk menyelesaikan permasalahan terkait:
- Transformasi geometri (translasi, refleksi, rotasi, dan dilatasi, serta komposisinya) dari titik

---

## 2. Batasan Materi (PENTING)

> ⚠️ **Catatan Ujian:** Transformasi mencakup **translasi, refleksi, rotasi, dilatasi**, dan **komposisi** transformasi dari titik.

---

## 3. Ringkasan Materi

### 3.1 Translasi (Pergeseran)

Translasi oleh vektor $\vec{t} = \begin{pmatrix} a \\ b \end{pmatrix}$:

$$T : (x, y) \to (x + a, y + b)$$

**Sifat translasi:**
- Mempertahankan bentuk, ukuran, dan orientasi
- Hanya mengubah posisi

### 3.2 Refleksi (Pencerminan)

| Cermin terhadap | Bayangan $(x, y)$ |
|:----------------|:-------------------|
| Sumbu $x$ | $(x, -y)$ |
| Sumbu $y$ | $(-x, y)$ |
| Garis $y = x$ | $(y, x)$ |
| Garis $y = -x$ | $(-y, -x)$ |
| Titik asal $O(0,0)$ | $(-x, -y)$ |
| Garis $x = h$ | $(2h - x, y)$ |
| Garis $y = k$ | $(x, 2k - y)$ |

**Sifat refleksi:**
- Mempertahankan bentuk dan ukuran
- Mengubah orientasi (bayangan cermin)

### 3.3 Rotasi (Perputaran)

Rotasi sebesar $\theta$ terhadap titik pusat $O(0, 0)$:

$$R_\theta : \begin{pmatrix} x \\ y \end{pmatrix} \to \begin{pmatrix} x\cos\theta - y\sin\theta \\ x\sin\theta + y\cos\theta \end{pmatrix}$$

Rotasi terhadap titik pusat $P(a, b)$:

$$\begin{pmatrix} x' \\ y' \end{pmatrix} = \begin{pmatrix} \cos\theta & -\sin\theta \\ \sin\theta & \cos\theta \end{pmatrix} \begin{pmatrix} x - a \\ y - b \end{pmatrix} + \begin{pmatrix} a \\ b \end{pmatrix}$$

**Rotasi khusus terhadap $O$:**

| Sudut | $(x, y) \to$ |
|:------|:--------------|
| $90°$ | $(-y, x)$ |
| $180°$ | $(-x, -y)$ |
| $270°$ atau $-90°$ | $(y, -x)$ |

### 3.4 Dilatasi (Perbesaran/Perkecilan)

Dilatasi dengan pusat $O(0, 0)$ dan faktor skala $k$:

$$D_{[O, k]} : (x, y) \to (kx, ky)$$

Dilatasi dengan pusat $P(a, b)$ dan faktor skala $k$:

$$D_{[P, k]} : (x, y) \to (k(x - a) + a, \; k(y - b) + b)$$

**Sifat dilatasi:**
- $|k| > 1$: pembesaran
- $0 < |k| < 1$: pengecilan
- $k < 0$: bayangan terbalik

### 3.5 Komposisi Transformasi

Komposisi dua transformasi $T_1$ dan $T_2$ diterapkan secara berurutan:

$$(T_2 \circ T_1)(P) = T_2(T_1(P))$$

> ⚠️ **Perhatikan urutan!** $T_1$ diterapkan lebih dulu, kemudian $T_2$.

---

## 4. Contoh Soal & Pembahasan

### Soal 1 (Dilatasi & Proporsional — dari Juknis, Soal No. 19)

**Soal:**

Pak Andi memproyeksikan desain gedung berukuran 60 cm × 60 cm ke layar 2,4 m × 1,8 m (horizontal). Skala pembesaran proporsional.

Tentukan Benar/Salah:
- A. Perbandingan ukuran tampilan desain di layar adalah 1 : 1
- B. Ukuran panjang dan lebar tampilan desain pada layar lebih dari 1 meter
- C. Terdapat bagian gambar asli yang terpotong dalam tampilan pada layar

**Pembahasan:**

Desain: $60 \times 60$ cm (rasio 1:1, bujur sangkar)

Layar: $240 \times 180$ cm (rasio 4:3, horizontal)

Agar proporsional, faktor skala dibatasi oleh dimensi **terkecil** layar:

$$k = \frac{180}{60} = 3$$

Tampilan desain: $60 \times 3 = 180$ cm × $60 \times 3 = 180$ cm

**A: Perbandingan 1:1** → Karena desain asli bujur sangkar dan dibesarkan proporsional, tampilannya tetap $180 \times 180$ → rasio **1:1** → **Benar** ✅

**B: Lebih dari 1 meter** → $180$ cm $= 1.8$ m $> 1$ m → **Benar** ✅

**C: Ada bagian terpotong** → Tampilan $180 \times 180$ masuk dalam layar $240 \times 180$ (tidak melebihi) → **Salah** ✅

---

### Soal 2 (Refleksi — Level 1)

**Soal:**

Tentukan bayangan titik $A(3, -2)$ jika dicerminkan terhadap sumbu $y$.

**Pembahasan:**

Refleksi terhadap sumbu $y$: $(x, y) \to (-x, y)$

$$A(3, -2) \to A'(-3, -2)$$

**Jawaban:** $A'(-3, -2)$

---

### Soal 3 (Rotasi — Level 2)

**Soal:**

Tentukan bayangan titik $B(4, 1)$ jika dirotasi $90°$ berlawanan arah jarum jam terhadap titik asal.

**Pembahasan:**

Rotasi $90°$: $(x, y) \to (-y, x)$

$$B(4, 1) \to B'(-1, 4)$$

**Jawaban:** $B'(-1, 4)$

---

### Soal 4 (Komposisi Transformasi — Level 3)

**Soal:**

Titik $C(2, 3)$ ditranslasi oleh $\vec{t} = \begin{pmatrix} 1 \\ -2 \end{pmatrix}$ kemudian dicerminkan terhadap sumbu $x$. Tentukan bayangan akhir.

**Pembahasan:**

Langkah 1 (Translasi):

$$C(2, 3) \to C'(2+1, 3+(-2)) = C'(3, 1)$$

Langkah 2 (Refleksi terhadap sumbu $x$):

$$C'(3, 1) \to C''(3, -1)$$

**Jawaban:** $C''(3, -1)$

## 5. Latihan Soal
Uji pemahaman terperinci Anda dengan mencoba [Set 1](./latihan/transformasi.md) dan [Set 2](./latihan/transformasi-2.md).

---

**Navigasi:**
- [⬅️ Objek Geometri](./objek-geometri.md)
- [➡️ Pengukuran](./pengukuran.md)
