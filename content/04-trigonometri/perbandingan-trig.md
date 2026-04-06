# Perbandingan Trigonometri

> **Elemen:** [Trigonometri](./index.md) | **Kembali ke Home:** [🏠 README](../../README.md)

---

## 1. Kompetensi

Memahami, mengaplikasikan, dan bernalar yang lebih tinggi untuk menyelesaikan permasalahan terkait:
- Perbandingan trigonometri: sinus, kosinus, tangen, kotangen, sekan, kosekan

---

## 2. Batasan Materi (PENTING)

> ⚠️ **Catatan Ujian:** Mencakup **enam** perbandingan trigonometri dasar, termasuk aplikasinya pada segitiga dan sudut-sudut khusus serta istimewa.

---

## 3. Ringkasan Materi

### 3.1 Definisi Perbandingan Trigonometri

Pada segitiga siku-siku dengan sudut $\theta$:

| Fungsi | Definisi | Singkatan |
|:-------|:---------|:----------|
| $\sin\theta$ | $\frac{\text{sisi depan}}{\text{sisi miring}}$ | $\frac{d}{m}$ |
| $\cos\theta$ | $\frac{\text{sisi samping}}{\text{sisi miring}}$ | $\frac{s}{m}$ |
| $\tan\theta$ | $\frac{\text{sisi depan}}{\text{sisi samping}}$ | $\frac{d}{s}$ |
| $\cot\theta$ | $\frac{\text{sisi samping}}{\text{sisi depan}}$ | $\frac{s}{d} = \frac{1}{\tan\theta}$ |
| $\sec\theta$ | $\frac{\text{sisi miring}}{\text{sisi samping}}$ | $\frac{m}{s} = \frac{1}{\cos\theta}$ |
| $\csc\theta$ | $\frac{\text{sisi miring}}{\text{sisi depan}}$ | $\frac{m}{d} = \frac{1}{\sin\theta}$ |

### 3.2 Nilai Trigonometri Sudut Istimewa

| $\theta$ | $0°$ | $30°$ | $45°$ | $60°$ | $90°$ |
|:---------|:----:|:-----:|:-----:|:-----:|:-----:|
| $\sin\theta$ | $0$ | $\frac{1}{2}$ | $\frac{1}{2}\sqrt{2}$ | $\frac{1}{2}\sqrt{3}$ | $1$ |
| $\cos\theta$ | $1$ | $\frac{1}{2}\sqrt{3}$ | $\frac{1}{2}\sqrt{2}$ | $\frac{1}{2}$ | $0$ |
| $\tan\theta$ | $0$ | $\frac{1}{3}\sqrt{3}$ | $1$ | $\sqrt{3}$ | $\infty$ |

### 3.3 Tanda Trigonometri di Setiap Kuadran

Gunakan aturan **"ALL STUDENTS TAKE CALCULUS"** (ASTC):

| Kuadran | Sudut | Positif |
|:--------|:------|:--------|
| **I** | $0° < \theta < 90°$ | **Semua** (+) |
| **II** | $90° < \theta < 180°$ | **Sin, Csc** (+) |
| **III** | $180° < \theta < 270°$ | **Tan, Cot** (+) |
| **IV** | $270° < \theta < 360°$ | **Cos, Sec** (+) |

### 3.4 Sudut Berelasi

| Relasi | $\sin$ | $\cos$ | $\tan$ |
|:-------|:-------|:-------|:-------|
| $(180° - \theta)$ | $\sin\theta$ | $-\cos\theta$ | $-\tan\theta$ |
| $(180° + \theta)$ | $-\sin\theta$ | $-\cos\theta$ | $\tan\theta$ |
| $(360° - \theta)$ | $-\sin\theta$ | $\cos\theta$ | $-\tan\theta$ |
| $(90° - \theta)$ | $\cos\theta$ | $\sin\theta$ | $\cot\theta$ |
| $(90° + \theta)$ | $\cos\theta$ | $-\sin\theta$ | $-\cot\theta$ |

### 3.5 Identitas Trigonometri Dasar

$$\sin^2\theta + \cos^2\theta = 1$$

$$1 + \tan^2\theta = \sec^2\theta$$

$$1 + \cot^2\theta = \csc^2\theta$$

$$\tan\theta = \frac{\sin\theta}{\cos\theta}$$

### 3.6 Rumus Trigonometri Tambahan

**Sudut rangkap:**

$$\sin 2\theta = 2\sin\theta\cos\theta$$

$$\cos 2\theta = \cos^2\theta - \sin^2\theta = 2\cos^2\theta - 1 = 1 - 2\sin^2\theta$$

**Jumlah dan selisih sudut:**

$$\sin(\alpha \pm \beta) = \sin\alpha\cos\beta \pm \cos\alpha\sin\beta$$

$$\cos(\alpha \pm \beta) = \cos\alpha\cos\beta \mp \sin\alpha\sin\beta$$

---

## 4. Contoh Soal & Pembahasan

### Soal 1 (Mencari cos dari sin — dari Juknis, Soal No. 7)

**Soal (Pilihan Ganda):**

Diketahui $\sin A = \frac{5}{13}$, $A$ adalah sudut tumpul. Nilai $\cos A = \ldots$

A. $\frac{12}{13}$  
B. $-\frac{12}{13}$  
C. $\frac{5}{12}$  
D. $-\frac{12}{13}$  
E. $\frac{13}{12}$

**Pembahasan:**

Gunakan identitas: $\sin^2 A + \cos^2 A = 1$

$$\cos^2 A = 1 - \sin^2 A = 1 - \frac{25}{169} = \frac{144}{169}$$

$$\cos A = \pm\frac{12}{13}$$

Karena $A$ adalah **sudut tumpul** (kuadran II), maka $\cos A < 0$:

$$\cos A = -\frac{12}{13}$$

**Jawaban: D. $-\frac{12}{13}$** ✅

---

### Soal 2 (Aplikasi Trigonometri — dari Juknis, Soal No. 15)

**Soal (Pilihan Ganda):**

Suatu tangga dengan panjang 6 meter disandarkan pada dinding vertikal. Sudut yang dibentuk tangga dengan lantai adalah $60°$. Tinggi dinding yang disentuh ujung atas tangga adalah ....

A. 3 meter  
B. $3\sqrt{2}$ meter  
C. $3\sqrt{3}$ meter  
D. $4\sqrt{2}$ meter  
E. $4\sqrt{3}$ meter

**Pembahasan:**

$$\sin 60° = \frac{\text{tinggi dinding}}{\text{panjang tangga}}$$

$$\frac{\sqrt{3}}{2} = \frac{t}{6}$$

$$t = 6 \times \frac{\sqrt{3}}{2} = 3\sqrt{3} \text{ meter}$$

**Jawaban: C. $3\sqrt{3}$ meter** ✅

---

### Soal 3 (Identitas Trigonometri — Level 2)

**Soal:**

Sederhanakan: $\frac{\sin^2\theta}{1 - \cos\theta}$

**Pembahasan:**

Gunakan: $\sin^2\theta = 1 - \cos^2\theta = (1 - \cos\theta)(1 + \cos\theta)$

$$\frac{(1 - \cos\theta)(1 + \cos\theta)}{1 - \cos\theta} = 1 + \cos\theta$$

**Jawaban:** $1 + \cos\theta$

---

### Soal 4 (Sudut Berelasi — Level 3)

**Soal:**

Tentukan nilai dari $\sin 150° + \cos 210° - \tan 315°$.

**Pembahasan:**

$$\sin 150° = \sin(180° - 30°) = \sin 30° = \frac{1}{2}$$

$$\cos 210° = \cos(180° + 30°) = -\cos 30° = -\frac{\sqrt{3}}{2}$$

$$\tan 315° = \tan(360° - 45°) = -\tan 45° = -1$$

$$= \frac{1}{2} - \frac{\sqrt{3}}{2} - (-1) = \frac{1}{2} - \frac{\sqrt{3}}{2} + 1 = \frac{3 - \sqrt{3}}{2}$$

**Jawaban:** $\frac{3 - \sqrt{3}}{2}$

## 5. Latihan Soal
Uji pemahaman terperinci Anda dengan mencoba [Set 1](./latihan/perbandingan-trig.md) dan [Set 2](./latihan/perbandingan-trig-2.md).

---

**Navigasi:**
- [⬅️ Kembali ke Indeks Trigonometri](./index.md)
- [⬅️ Elemen 3: Geometri](../03-geometri/index.md)
- [➡️ Elemen 5: Data & Peluang](../05-data-peluang/index.md)
