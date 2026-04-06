# Latihan Soal Set 2: Transformasi Geometri

> **Elemen:** [Geometri & Pengukuran](../index.md) | **Materi:** [Transformasi Geometri](../transformasi.md) | **Set 1:** [Latihan 1](transformasi.md) | **Kembali ke Home:** [🏠 README](../../../README.md)

---

## Soal 1: Pilihan Ganda (PG)
Titik $A(m, n)$ ditranslasikan dengan vektor $T = \begin{pmatrix} -4 \\ 2 \end{pmatrix}$ sehingga menghasilkan titik bayangan $A'(-1, 5)$. Jika titik awal $A(m, n)$ kemudian dicerminkan terhadap garis $y = 3$, maka kordinat pantulannya adalah ....

A. $(3, 3)$  
B. $(3, 1)$  
C. $(5, 5)$  
D. $(5, 1)$  
E. $(3, 6)$ 

**Pembahasan:**
Langkah 1: Menentukan absis $m$ dan ordinat $n$ titik awal $A$.
Aturan translasi: $A + T = A'$
$$ \begin{pmatrix} m \\ n \end{pmatrix} + \begin{pmatrix} -4 \\ 2 \end{pmatrix} = \begin{pmatrix} -1 \\ 5 \end{pmatrix} $$
$m - 4 = -1 \implies m = 3$.
$n + 2 = 5 \implies n = 3$.
Titik mulanya adalah $A(3, 3)$.

Langkah 2: Melakukan Refleksi terhadap garis horizontal $y = 3$.
Aturan pantulan ke sumbu garis mendatar $y = k$:
$(x, y) \to (x, \ 2k - y)$.
Refleksi $A(3, 3)$ terhadap $y = 3$ ($k=3$):
$(3, \ 2(3) - 3) = (3, \ 6 - 3) = (3, 3)$.

Titiknya tidak berpindah letak karena memang persis sedang berada menempel pada batas tepi cermin ($y=3$). 
Jawaban yang pas adalah **A**.

---

## Soal 2: Pilihan Ganda Kompleks Kategori (Benar/Salah)
Suatu persegi panjang $KLMN$ difokuskan untuk mengalami sebuah dilatasi (perkalian skala) tersentral pada suatu titik koordinat. Misal letak bangun berada di sebelah kanan dan titik pembesaran di kiri. Tentukan Benar/Salah sifat-sifat pergeserannya di bawah ini!

- A. Rentang pelebaran luasan dilatasi memiliki kaitan nilai eksponensial kuadratis terhadap besaran faktor skala $k$. $\left(Luas_{baru} = k^2 \times Luas_{awal}\right)$.
- B. Dilatasi dengan angka skala penyusutan bernilai $k = \frac{1}{2}$ akan meluruhkan seluruh jarak dan ukuran keliling aslinya menjadi sisa setengah.
- C. Jika sentral pusat pembesaran/pengecilan bukan merupakan pusat objek (berada menjauh layaknya senter sorot), dilatasi tidak akan mengubah/mindahkan titik tempat koordinat si objek.

**Pembahasan:**
**A. Pertambahan Luas Secara Kuadratis**
Luas dari bentuk 2 Dimensi (memiliki atribut elemen $panjang \times lebar$). Jika setiap elemen memanjang dikali $k$, maka dimensi gabungan dua sumbunya akan mengalami lonjakan $k \times k = k^2$. Luas Bayangan mutlak proporsional $k^2$ kali lipat luas utamanya.
Kesimpulan: **Benar** ✔️

**B. Skala penyusutan $k = 1/2$ meluruhkan jarak dan keliling menjadi separuh**
Dimensi keliling 1 Dimensi memadat murni dipengaruhi seukur $k^1$. Otomatis panjang selisih maupun tapak rusuk menciut tepat proporsi 50% / setengah pergerakan.
Kesimpulan: **Benar** ✔️

**C. Dilatasi Tidak merombak kedudukan**
Perpindahan pasti mutlak terjadi melesat/mendekat menuju titik Senter (Pusat titik sorot). Bayangkan sebuah bayangan senter, semakin ditarik ($k>1$) sorot objeknya juga posisinya menjauh terseret dari lampunya, tak sebatas menggemuk di koordinat awal. Perubahan koordinat merupakan intisari mutlak dan utama dalam persamaan dilatasinya kecuali bangunnya dilukis tepat berpusat pelukan di titik asal $(0,0)$. 
Kesimpulan: **Salah** ❌

---

## Soal 3: Pilihan Ganda Kompleks MCMA (Lebih dari 1 Jawaban Benar)
Pilihlah seluruh komposisi dari dua atau rentetan operasi transformasi secara beruntun di bawah ini yang akan bersifat manipulatif KOMUTATIF (mendapat hasil hasil koordinat akhir bayangan yang sama entah dibolak-balik urutan urut-urutannya). Lebih dari satu jawaban.

- [ ] Melakukan rotasi sejauh $90^\circ$ lalu dilanjut rotasi lagi $180^\circ$ dari pusat asal yang sama $(0,0)$.
- [ ] Menerapkan Translasi sejauh $T_1$ disambung gerak dorong Translasi susulan sejauh $T_2$.
- [ ] Pencerminan refleksi titik $(x,y)$ terhadap sumbu X lalu langsung disambung rotasi $90^\circ$ memutar asal $(0,0)$.
- [ ] Dilatasi terpusat $(0,0)$ faktor skala $3$, disambung lagi pembesaran terpusat sama dengan faktor $2$.
- [ ] Pencerminan terhadap garis $y=x$, kemudian dilanjut pencerminan sumbu sejajar $y=x$ sekali lagi. 

**Pembahasan:**
Eksplorasi apakah komposisi $T_A \circ T_B = T_B \circ T_A$ (bersifat bolak balik Komutatif / Tukar Rute).
1. Rotasi searah pada satu poros yang sama bersifat Aditif.  $R_{180} + 90 = R_{270}$ maupun $R_{90} + 180 = R_{270}$. Jadi bisa ditukar bolak-balik urutannya. ✅
2. Penjumlahan relasi vektor Translasi selalu komutatif ($T_1 + T_2 = T_2 + T_1$). Koordinat pamungkas tak goyah. ✅
3. Matriks gabungan Refleksi dan Rotasi tidak bersifat mutlak komutatif. Matriks $(Ref \times Rot) \neq (Rot \times Ref)$ pada rotasi ganjil. ❌
4. Dilatasi pada sebuah pusat sumbu yang berhimpitan yang sama akan memiliki gabungan perbesaran skala yang bersatu padu lurus secara linear perkalalian ($k_1 \times k_2$). Karena $3 \times 2 = 2 \times 3 = 6$, komposisinya mutlak tergolong komutatif jika memiliki pusat sumbu presisi yang sama. ✅
5. Pencerminan ulang terhadap satu cermin lurus yang persis sama adalah fenomena membalik bayangan balik lagi ke realita (identitas null $1$ atau sama saja tidak mentransformasi pergerakan: posisi awal). Dilakukan duluan maupun belakangan hasilnya kembali ke posisinya berdiri. Valid komutatif bertumpu di ekuator asalnya. ✅

Rangkaian operasional rasional yang memiliki watak komutatif ditunjukkan pada nomor **1, 2, 4, dan 5**.

---
**Navigasi:**
- [⬅️ Kembali ke Materi](../transformasi.md)
