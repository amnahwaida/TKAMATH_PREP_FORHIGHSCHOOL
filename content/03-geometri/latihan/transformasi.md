# Latihan Soal: Transformasi Geometri

> **Elemen:** [Geometri & Pengukuran](../index.md) | **Materi:** [Transformasi Geometri](../transformasi.md) | **Kembali ke Home:** [🏠 README](../../../README.md)

---

## Soal 1: Pilihan Ganda (PG)
Titik $P(2,-5)$ dirotasikan sebesar $90^{\circ}$ berlawanan arah jarum jam dengan pusat titik asal $O(0,0)$. Titik bayangannya kemudian ditranslasikan oleh $\begin{pmatrix} -3 \\ 4 \end{pmatrix}$. Koordinat akhir titik $P$ adalah ....

A. $(2, 6)$  
B. $(5, 2)$  
C. $(2, 2)$  
D. $(8, 2)$  
E. $(8, -2)$

**Pembahasan:**
Langkah 1: Rotasi $90^{\circ}$ berlawanan jarum jam terhadap pusat $(0,0)$.
Aturan rotasi $+90^\circ$: $R(x, y) \to (-y, x)$.
Titik awal: $P(2, -5)$.
Bayangan pertama ($P'$): $(-(-5), 2) = (5, 2)$.

Langkah 2: Translasi oleh $\vec{t} = \begin{pmatrix} -3 \\ 4 \end{pmatrix}$.
Aturan translasi: $T(x,y) \to (x+a, y+b)$.
Titik dari rotasi ($P'$): $(5, 2)$.
Koordinat akhir ($P''$): $(5 + (-3), \ 2 + 4) = (2, 6)$.

Jawaban yang tepat adalah **A**.

---

## Soal 2: Pilihan Ganda Kompleks Kategori (Benar/Salah)
Tentukan Benar atau Salah pada setiap pernyataan mengenai sifat-sifat pencerminan (refleksi) dan dilatasi di bidang koordinat!

- A. Pencerminan terhadap garis $y = -x$ akan mengubah titik $B(-2, 3)$ menjadi titik $(-3, 2)$.
- B. Dilatasi dengan faktor skala $k = -2$ dari sebuah bangun segitiga akan membalikkan orientasi arah gambar serta memperbesar ukurannya.
- C. Jika suatu titik dirotasikan $180^\circ$ terhadap titik asal $(0,0)$, hasilnya akan sama jika titik tersebut dicerminkan terhadap garis $y = x$.

**Pembahasan:**
**A. Refleksi $y = -x$ dari $B(-2, 3)$**
Aturan ke garis $y = -x$ adalah $(x, y) \implies (-y, -x)$.
Sehingga $(-2, 3) \implies (-3, -(-2)) = (-3, 2)$.
Kesimpulan: **Benar** ✔️

**B. Dilatasi dengan $k = -2$ akan memperbesar dan membalik orientasi.**
Nilai $|-2| = 2 > 1$, berakibat bangun menjadi 2 kali lebih besar.
Nilai minus ($-$), berakibat bangunnya terbalik 180 derajat ke sisi berlawanan titik pusat.
Kesimpulan: **Benar** ✔️

**C. Rotasi $180^\circ$ vs Pencerminan $y=x$**
Aturan rotasi $180^\circ$: $(x,y) \implies (-x,-y)$. (Ini identik dengan refleksi terhadap titik asal).
Aturan pencerminan $y = x$: $(x,y) \implies (y, x)$.
Jelas $(-x,-y)$ tidak selalu sama dengan $(y,x)$. (Akan sama hanya bila $x = 0$ dan $y = 0$).
Kesimpulan: **Salah** ❌

---

## Soal 3: Pilihan Ganda Kompleks MCMA (Lebih dari 1 Jawaban Benar)
Pilihlah transformasi berikut yang sifatnya berupa isometri atau mempertahankan ukuran dan bentuk asal bangunan! Jawaban bisa lebih dari satu.

- [ ] Translasi berturut-turut oleh tiga vektor berbeda
- [ ] Rotasi sebesar $270^\circ$ terhadap titik asal
- [ ] Refleksi berurutan terhadap dua sumbu tegak lurus
- [ ] Dilatasi menggunakan pusat titik asal dan skala 2
- [ ] Dilatasi menggunakan pusat $(1,1)$ dengan faktor skala -1

**Pembahasan:**
Transformasi **isometri** adalah transformasi yang sama sekali **tidak mengubah ukuran (jarak antar titik/luasan/keliling)**. Termasuk mempertahankan bentuk, sekalipun posisinya terbalik.
1. Translasi. Pergeseran selalu mempertahankan ukuran panjang. (Benar Isometri). ✅
2. Rotasi. Perputaran juga sama, bentuknya tetap persis. (Benar Isometri). ✅
3. Refleksi. Cermin menghasilkan bayangan berukuran 1:1, tidak mengubah luasan. (Benar Isometri). ✅
4. Dilatasi ($k=2$). Berakibat ukuran bayangan membesar $2$ kali lipat untuk luasan. Bukan isometri! ❌
5. Dilatasi dengan faktor $-1$. Karena $|k| = |-1| = 1$, pembesaran atau perkecilannya tidak berubah ukurannya. (Efek $k=-1$ justru sama persis seperti rotasi $180^\circ$, yaitu Isometri). ✅

Maka, jawaban yang benar adalah opsi **1, 2, 3, dan 5**.

---
**Navigasi:**
- [⬅️ Kembali ke Materi](../transformasi.md)
