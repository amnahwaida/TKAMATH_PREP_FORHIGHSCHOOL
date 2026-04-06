# Latihan Soal Set 2: Statistika

> **Elemen:** [Data & Peluang](../index.md) | **Materi:** [Statistika](../statistika.md) | **Set 1:** [Latihan 1](statistika.md) | **Kembali ke Home:** [🏠 README](../../../README.md)

---

## Soal 1: Pilihan Ganda (PG)
Data survei tentang tingkat kepuasan pelanggan terdiri atas rentang nilai 1-10. Diberikan rangkaian himpunan datum sebagai berikut:
$$6, 7, 7, 8, 8, 8, 9, 9, 10, 10$$
Tentukan besaran Varians (Ragam) dari sekelompok kumpulan himpunan populasi sederhana di atas!

A. $1,2$  
B. $1,4$  
C. $1,44$  
D. $1,56$  
E. $2,0$  

**Pembahasan:**
Rumus Varians sampel data berjumlah n ($n=10$):
$S^2 = \frac{\sum (x_i - \bar{x})^2}{n}$

Tahap 1: Merajut kalkulasi Rata-rata (Mean)
$\bar{x} = \frac{6 + 7(2) + 8(3) + 9(2) + 10(2)}{10} = \frac{6 + 14 + 24 + 18 + 20}{10}$
$\bar{x} = \frac{82}{10} = 8,2$

Tahap 2: Serapan Jarak kuadrat
- $(6 - 8,2)^2 = (-2,2)^2 = 4,84$ (frek: 1) $\implies 4,84 \times 1 = 4,84$
- $(7 - 8,2)^2 = (-1,2)^2 = 1,44$ (frek: 2) $\implies 1,44 \times 2 = 2,88$
- $(8 - 8,2)^2 = (-0,2)^2 = 0,04$ (frek: 3) $\implies 0,04 \times 3 = 0,12$
- $(9 - 8,2)^2 = (0,8)^2 = 0,64$ (frek: 2) $\implies 0,64 \times 2 = 1,28$
- $(10 - 8,2)^2 = (1,8)^2 = 3,24$ (frek: 2) $\implies 3,24 \times 2 = 6,48$

Tahap 3: Total Sum / $n$
$\Sigma = 4,84 + 2,88 + 0,12 + 1,28 + 6,48 = 15,6$
$S^2 = \frac{15,6}{10} = 1,56$

Tingkat simpangan penyebaran keragaman kuadratnya melebarkan nilai **1,56**. Hal ini mengerucut kuat di pilihan **D**.

---

## Soal 2: Pilihan Ganda Kompleks Kategori (Benar/Salah)
Pemetaan diagram Lingkaran tentang proporsi hobi mendamba persentase ideal penuh ($100\%$ / $360^\circ$). Jika ditarik data 120 orang populasi: Musik ($90^\circ$), Renang ($30^\circ$), Membaca ($x^\circ$), dan Esport selebihnya. Tentukan Benar Salah pada klaim perbandingan data survei tersebut!

- A. Peminat mendengarkan Musik terhitung berjumlah 30 individual subjek.
- B. Sektor porsi presentase penggemar espor tidak akan mungkin bisa dipastikan karena irisan irisan derajat persekusi batas irisan Membaca ($x$) ikut-ikutan remang gaib tak terungkap.
- C. Jika diketahui Peminat membaca ada 40 orang responden survei, maka derajat penyapu wilayah lingkarannya termanifestasi merenggang melingkar berjejari memutar hingga sejauh $120^\circ$.

**Pembahasan:**
**A. Peminat musik ada 30 orang**
Derajat musik $= 90^\circ$. Proporsi keseluruhannya adalah $\frac{90^\circ}{360^\circ} = \frac{1}{4}$.
Jumlah aktual $= \frac{1}{4} \times \text{Total Populasi } 120 = 30$ orang. Tepat.
Kesimpulan: **Benar** ✔️

**B. Penggemar E-Sport tak terkuak tebakan logisnya**
Ya, di dalam rumus matematika pasti proporsi utuh harus $360^\circ$. Apabila dua buah elemen/variabel saling bergantungan silang terselubung tak menampakkan porsi nominal derajat maupun persentasenya (Esport & Membaca tak diketahui nilainya), sistem tertutup semacam persamaan linear dua variabel tak bisa tuntas jika hanya dikerjakan sebagai 1 buah formula persamaan linear tunggal $E + x = 360 - 90 - 30$. Konon tak mungkin diketahui nilai ekuilibrium pastinya secara gamblang.
Kesimpulan: **Benar** ✔️

**C. Jika 40 orang, maka $120^\circ$**
Proporsi $40$ orang membaca dari total $120$ populasi.
Fraksinya adalah $\frac{40}{120} = \frac{1}{3}$.
Sebaran porsi pada keping derajat lingkaran seutuhnya adalah $\frac{1}{3} \times 360^\circ = 120^\circ$.
Kesimpulan: **Benar** ✔️

---

## Soal 3: Pilihan Ganda Kompleks MCMA (Lebih dari 1 Jawaban Benar)
Jika diketahui bahwa median himpunan data bilangan genap yang disusun seragam dari terkecil $X_1$ hinggga $X_{10}$ terletak proporsional sebanding dengan rumusannya, pilihlah implikasi-implikasi pernyataan di bawah ini yang mengawal parameter ukuran pemusatan datanya menembus kelogisan (Asumsikan seluruh data terurut positif).

- [ ] Memenggal data berkelompok untuk pemetaan kuartil akan melahirkan median sebagai nama rahasia lain untuk $Q_2$.
- [ ] Jangkauan antar kuartil secara harfiah terkuak formulanya melalui penghempasan $(Q_3 - Q_1)$.
- [ ] Titik sebaran median pada $n=10$ (genap) direnggut menengahi nilai persis secara utuh datum $x_5$.
- [ ] Menambahkan sebuah datum bernilai ekstrem tinggi pencilan (outlier), tak pelak bakal jauh lebih dahsyat menyeret Mean dibandingkan goyangannya pada Median.
- [ ] Histogram mutlak diharamkan memetakan interval berfrekuensi karena dominasi tabulasinya berwujud titik-titik bersambung layaknya diagram garis.

**Pembahasan:**
Uji konsep teoretis ukuran pusat / penyebaran:
1. $Q_2$ adalah poros sentral yang dihormati secara abadi menduduki tahta alias untuk kata Medium / Median. ✅
2. Hampiran (Jangkauan/Rentang) antar-kuartil memetakan ketimpangan atas ke bawah melalui pencabutan $Q_3$ dikurangi perbatasan bawah $Q_1$. Hal ini merepresentasikan simpangan inter-kuartil (Hamparan). ✅
3. Median data genap ($n=10$) wajib memadukan (merata-rata) gerbong datum ke-5 dan ke-6. Dia bukan wujud murni menduduki sepihak tubuh individual ke-5 itu sendiri. ❌
4. Rata-rata (Mean) amatlah peka, meresap secara mutlak setiap angka pencelupan datum besar outliner dari populasi tak terduga. Semantara median amat cuek (Resistant) karena terisolasi aman memunggungi ekstremitas tumpuan ekor kanan maupun palung dasar ekor kiri di titik tengah. ✅
5. Histogram lahir untuk bersinergi mewadahi visual berbalok menyambung rengket memfasilitasi tabulasi interval kumpulan data kelompok. Ia bukan titik diagram garis (Poligon / ogive). ❌

Jawaban kebenaran koheren mengait pada parameter valid opsi **1, 2, dan 4**.

---
**Navigasi:**
- [⬅️ Kembali ke Materi](../statistika.md)
