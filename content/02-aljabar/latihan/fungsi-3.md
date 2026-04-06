# Latihan Soal Set 3: Fungsi & Komposisi Invers

> **Elemen:** [Aljabar](../index.md) | **Materi:** [Fungsi](../fungsi.md) | **Set 1:** [Latihan 1](fungsi.md) | **Set 2:** [Latihan 2](fungsi-2.md) | **Kembali ke Home:** [🏠 README](../../../README.md)

---

## Soal 1: Pilihan Ganda (PG)
Diberikan relasi fungsi $f(x) = \frac{2x - 3}{x + 5}$, dengan ketetapan limit domain batas agar tidak kosong $x \neq -5$. Tentukan di titik mana nilai domain rahasia $y$ jatuh, jika diketahui fungsi invers balikan $f^{-1}(y) = 3$. (Cari nilai variabel $y$).

A. $\frac{3}{8}$  
B. $-\frac{3}{8}$  
C. $\frac{5}{2}$  
D. $0$  
E. $1$  

**Pembahasan:**
Permasalahan menantang pencarian nilai dengan cara membongkar skema fungsional terbalik.
Ada dalil kesetaraan magis relasi bolak balik fungsi:
$$ f^{-1}(a) = b \iff f(b) = a $$

Ini artinya kita tidak perlu repot-repot menyusun rumus komplit mencari invers pecahan lalu mem-pluk in angka 3.
Dalil itu berpesan bahwa jikalau $f^{-1}(y) = 3$, maka ini mengonfirmasi padanan setara absolut $\implies f(3) = y$.
Maka kita cukup masukkan nilai substitusi 3 ke punggung relasi utamanya ($f$ biasa):
$$ y = f(3) = \frac{2(3) - 3}{3 + 5} $$
$$ y = \frac{6 - 3}{8} = \frac{3}{8} $$

Selesai. Alih kode merinci hasil pada fraksi murni $\frac{3}{8}$.
Jawaban yang pas memikat hati terletak di **A**.

---

## Soal 2: Pilihan Ganda Kompleks Kategori (Benar/Salah)
Suatu rentang operasi aljabar diistilahkan sebagai Fungsi asalkan ia tidak menyelisihi tatanan kesepakatan pemetaan himpunan dasar.
Tentukan Benar/Salah sifat pembagian irisan kodomain!

- A. Relasi himpunan $\{ (1,2), (2,3), (3,2), (4,5) \}$ dapat disahkan sebagai rupa Fungsi, sekalipun daerah hasil range angka 2 kejatuhan dual arah dari $X=1$ dan $X=3$.
- B. Fungsi Kuadrat $f(x) = ax^2 + bx$ merupakan representasi pemetaan korespondensi satu-satu mutlak memecah poros absis ordinat. 
- C. Jikalau dipasang aturan himpunan komposit gabungan berturut-turut, relasi $(f \circ g)^{-1}$ akan identik setara merombaknya menggunakan struktur terbalik dari jajaran independen relasinya yaitu $g^{-1} \circ f^{-1}$.

**Pembahasan:**
**A. Himpunan dan Syarat Kesahan Fungsi**
Pilar mutlak Fungsi adalah: Setiap individu subjek yang ada di domain (X) HANYA BOLEH mencoblos (memiliki pasangan sasaran) satu arah panah saja di zona lawan (Kodomain). Tiada keraguan bagi $X$ untuk mendua.
Di himpunan, baris X adalah $[1, 2, 3, 4]$. Tidak ada angka depannya yang dobel/rakus menembak 2 sumbu target. Walau di sana $1 \to 2$ dan $3 \to 2$ (semua menuju orang sama), *its OK*. Subjek $X$ tidak berpoliandri. Relasi ini valid menyandang titel mulia Fungsi Surjektif/sejenisnya.
Kesimpulan: **Benar** ✔️

**B. Relasi Kuadrat sebagai korespondensi Seragam/Satu-Satu**
Grafik lengkung lengkungan parabola (kuadrat) mutlak MENYALAHI kaidah fungsi satu-satu (Injektif), dan otomatis merubuhkan status fungsional paripurna korespondensi satu-satunya (Bijektif). Jika disorot senter mendatar (Horizontal test), 1 tinggi $y$ mutlak ditarik dari dua akar kutub poros $X$ berbeda (akar plus, akar minus). Bukan injektif.
Kesimpulan: **Salah** ❌

**C. Sifat Penguraian Invers Komposit Bersarang**
Aturan buka kurung terbalik untuk ikatan komposit menyuruh kita membalik tabung penyusunnya secara berurut merayap dari relasi paling terakhir masuk ditarik mundur:
$(f \circ g)^{-1}(x) = (g^{-1} \circ f^{-1})(x)$.
Ini adalah sifat esensi dalil silang murni identitas komposit matematis yang abadi berlaku.
Kesimpulan: **Benar** ✔️

---

## Soal 3: Pilihan Ganda Kompleks MCMA (Lebih dari 1 Jawaban Benar)
Pilihlah deret manifestasi perhitungan operasi modifikasi aljabar Fungsi $f(x) = x^2 - 1$ dan $g(x) = x - 3$ yang membuahkan luaran matematis ekuivalen pas yang dirincikan di tabulasinya (Pilih perumusan/evaluasi yang terverifikasi taksiran Benarnya!)

- [ ] $(f+g)(x) = x^2 + x - 4$
- [ ] $(f-g)(x) = x^2 - x + 2$
- [ ] $(f \cdot g)(x) = x^3 - 3x^2 - x + 3$
- [ ] $(g \circ f)(x) = x^2 - 4$
- [ ] Menjumlah titik $f(2) + g(2)$ membuahkan defisit kalkulasi seharga nominal $(-2)$.

**Pembahasan:**
Penjabaran rasional kalkulasi fungsi utuh $f={x^2-1}$  ; $g={x-3}$ :
1. Penjumlahan $f+g = (x^2 - 1) + (x - 3) = x^2 + x - 4$. (Sinkron). ✅
2. Pengurangan $f-g = (x^2 - 1) - (x - 3) = x^2 - 1 - x + 3 = x^2 - x + 2$. (Sinkron). ✅
3. Perkalian $f \cdot g = (x^2 - 1) \cdot (x - 3) = x^2(x - 3) - 1(x - 3) = x^3 - 3x^2 - x + 3$. (Sinkron). ✅
4. Komposisi $g(f) = g(x^2 - 1) = (x^2 - 1) - 3 = x^2 - 4$. (Sinkron). ✅
5. Eksekusi nominal di $X=2$:
   $f(2) = 2^2 - 1 = 4 - 1 = 3$.
   $g(2) = 2 - 3 = -1$.
   Total Kumulasi $= 3 + (-1) = 2$ bernilai Surplus plus Positif, BUKAN jeblok minus ganjil defisit $-2$. (Nihil kecocokan). ❌

Konklusi deretan kalkulasi persis sempurna memeluk akurasi adalah **Opsi 1, 2, 3, dan 4**.

---
**Navigasi:**
- [⬅️ Kembali ke Materi](../fungsi.md)
