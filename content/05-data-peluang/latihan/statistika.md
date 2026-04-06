# Latihan Soal: Statistika

> **Elemen:** [Data & Peluang](../index.md) | **Materi:** [Statistika](../statistika.md) | **Kembali ke Home:** [🏠 README](../../../README.md)

---

## Soal 1: Pilihan Ganda (PG)
Diberikan himpunan data tunggal: $4, 5, 8, 9, 7, 5, 6, 8, 5, 7$. Kuartil atas ($Q_3$) dari kumpulan data tersebut adalah ....

A. $5$  
B. $6$  
C. $7$  
D. $7,5$  
E. $8$

**Pembahasan:**
Langkah pertama mencari kuartil atas adalah mengurutkan himpunan data dari yang paling kecil.
Urutan dari 10 data ($n=10$):
$4, 5, 5, 5, 6, 7, 7, 8, 8, 9$

Karena jumlah n = 10, data terbagi menjadi 2 blok kiri dan kanan pada membelah median.
Median ($Q_2$) berada antara datum ke-5 dan 6: $\frac{6+7}{2} = 6,5$.
Blok kiri (data 1-5): $4, 5, 5, 5, 6$.
Blok kanan (data 6-10): $7, 7, 8, 8, 9$.

Kuartil atas ($Q_3$) adalah median dari "blok kanan" yaitu data ke-8 secara keseluruhan urutan.
Nilai di tengah susunan $\{7, 7, 8, 8, 9\}$ adalah $8$. 
Jadi, $Q_3 = 8$.

Jawaban yang tepat adalah **E**.

---

## Soal 2: Pilihan Ganda Kompleks Kategori (Benar/Salah)
Dalam ulangan harian matematika, sebuah kelas beranggotakan 20 murid putra mengantongi rata-rata 75, sedangkan 10 murid putri memperoleh rata-rata 84.
Tentukan Benar atau Salah pada setiap pernyataan ukuran pemusatan berikut ini!

- A. Rata-rata gabungan keseluruhan kelas tersebut adalah 78.
- B. Rata-rata gabungan akan lebih condong (mendekati) ke nilai rata-rata murid putra karena jumlah populasinya lebih besar.
- C. Total kumulatif nilai ulangan seluruh kelas berjumlah 2.400.

**Pembahasan:**
Mari hitung total tiap sub populasi:
Total putra $= 20 \times 75 = 1.500$.
Total putri $= 10 \times 84 = 840$.
Keseluruhan Populasi ($n$) $= 20 + 10 = 30$.

Evaluasi tiap pernyataan:
**A. Rata-rata gabungan keseluruhan adalah 78**
$$ \bar{X}_{\text{gabungan}} = \frac{1.500 + 840}{30} = \frac{2.340}{30} = 78 $$
Ternyata rata -rata seluruh kelas tepat 78. 
Kesimpulan: **Benar** ✔️

**B. Rata-rata gabungan lebih condong ke rata-rata nilai murid putra**
Nilai rata-rata akan selalu tertarik ke kelompok yang populasinya lebih tinggi. Perhatikan letak $78$ lebih dekat dari $75$ (selisih $3$ poin) dibandingkan $84$ (selisih $6$ poin).
Kesimpulan: **Benar** ✔️

**C. Total kumulatif mencapai 2.400**
Telah kita hitung bahwa $1.500 + 840 = 2.340$. Nilainya kurang dari $2.400$.
Kesimpulan: **Salah** ❌

---

## Soal 3: Pilihan Ganda Kompleks MCMA (Lebih dari 1 Jawaban Benar)
Pilihlah yang termasuk sifat-sifat distribusi ukuran pemusatan jika semua himpunan data awal dijumlahkan dengan angka konstan $+5$! Jawaban lebih dari satu.

- [ ] Mean data akan bertambah 5 poin
- [ ] Median data akan bertambah 5 poin
- [ ] Jangkauan (Range) bertambah 5 poin
- [ ] Simpangan Baku data akan bertambah 5 poin
- [ ] Modus dari data tersebut ikut bertambah 5 poin

**Pembahasan:**
Konsep pergeseran himpunan data dasar:
1. Jika setiap datum ditambah/dikurang konstan $c$, **Ukuran Pusat** (Mean, Median, Modus) akan terpengaruh sama persis (tambah/kurang sebesar $c$).
2. Namun, **Ukuran Penyebaran** (Range, Jangkauan interkuartil, Simpangan rata-rata, Varians, Simpangan Baku) **TETAP/TIDAK BERUBAH** sama sekali. Karena pergeseran keseluruhan ke atas atau ke bawah tidak melebarkan/mengecilkan jarak antar datanya.

Mari periksa opsinya:
1. Mean bertambah 5. (Benar) ✅
2. Median bertambah 5. (Benar) ✅
3. Jangkauan bertambah 5. Salah, range tidak berubah. ❌
4. Simpangan baku bertambah 5. Salah, deviasi nilainya akan tetap. ❌
5. Modus bertambah 5. (Benar) ✅

Jawaban yang valid adalah **1, 2, dan 5**.

---
**Navigasi:**
- [⬅️ Kembali ke Materi](../statistika.md)
