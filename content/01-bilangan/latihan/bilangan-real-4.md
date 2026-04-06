# Latihan Soal Set 4: Bilangan Real

> **Elemen:** [Bilangan](../index.md) | **Materi:** [Bilangan Real](../bilangan-real.md) | **Set 1:** [Latihan 1](bilangan-real.md) | **Set 2:** [Latihan 2](bilangan-real-2.md) | **Set 3:** [Latihan 3](bilangan-real-3.md) | **Kembali ke Home:** [🏠 README](../../../README.md)

---

## Soal 1: Pilihan Ganda (PG)
Diketahui sebuah pertaksamaan eksponensial dalam bentuk akar bersarang yang mengekang sebuah variabel tidak diketahui. 
$$\sqrt{8^{x-2}} = \left( \frac{1}{4} \right)^{2-x}$$
Berdasarkan ekuivalensi absolut pada basis yang sejajar, tentukan kemana titik penyelesaian angka rasional variabel $X$ tersebut bermuara!

A. $-2$  
B. $-\frac{2}{3}$  
C. $\frac{2}{3}$  
D. $2$  
E. $4$  

**Pembahasan:**
Menyamakan frekuensi kedua sisi ke dalam basis primer ($2$).
Sisi kiri:
$\sqrt{8^{x-2}} = (8^{x-2})^{\frac{1}{2}} = ((2^3)^{x-2})^{\frac{1}{2}} = 2^{\frac{3(x-2)}{2}} = 2^{\frac{3x-6}{2}}$.

Sisi kanan:
$\left( \frac{1}{4} \right)^{2-x} = (2^{-2})^{2-x} = 2^{-4 + 2x} = 2^{2x-4}$.

Lepaskan pangkat dan sejajarkan ekuivalensinya:
$$ \frac{3x - 6}{2} = 2x - 4 $$
$$ 3x - 6 = 2(2x - 4) $$
$$ 3x - 6 = 4x - 8 $$
$$ -6 + 8 = 4x - 3x $$
$$ 2 = x $$

Titik tumpu penyelesaian variabel $X$ jatuh di angka **2**. Angka mutlak yang berjejal manunggal mendiami pilihan ganda tepat pada abjad **D**.

---

## Soal 2: Pilihan Ganda Kompleks Kategori (Benar/Salah)
Pemisahan struktur desimal menghadirkan fraksi unik berulang yang nampak mustahil dirangkum tetapi nyatanya bisa didomestikasi menjadi balutan pecahan a/b. Uji kebenaran penaksiran klasifikasi desimal murni dan pecahannya berikut:

- A. Angka desimal tak menentu yang terus membentang $0,2222...$ selamanya memiliki ikatan wujud sejati yang setara ekuivalen persis di format nominal aljabar pecahan sebagai $\frac{2}{9}$.
- B. Sifat bilangan Irasional dideklaristikan pada segala bentuk format numerik desimal yang rentetan angkanya mengalir acak di belakng koma nyaris tak bisa dibungkus menjadi kawat relasi porsi integer pecahan $\frac{a}{b}$. Contoh rahasianya adalah nilai Konstanta $\pi$ dan eksponen $e$.
- C. Akar serba tak sempurna seperti irisan belahan angka $\sqrt{2}$ bukanlah entitas Bilangan Nyata (Real) karena secara nominal tertebak gaib dan selamanya divonis menjadi kelompok murni bilangan Imajiner/Khayal semata-mata.

**Pembahasan:**
**A. Merasionalkan bilangan 0,222...**
Misalkan $x = 0,222...$
Kalikan 10 ke seluruh rusuk tubuhnya $\implies 10x = 2,222...$
Lakukan pencabutan (pengurangan selisih antar keduanya):
$(10x) - (x) = 2,222... - 0,222... \implies 9x = 2 \implies x = \frac{2}{9}$. Benar merasionalkan!
Kesimpulan: **Benar** ✔️

**B. Hakikat Penggolongan Irasional**
Ini adalah hukum kitab suci penjabaran absolut sistem matematika. Bilangan Rasional merangkut apa yg terdefinisikan fraksinya secara berulang konstan $A/B$. Sedang Irasional beringsut lepas melayang semrawut takkan berulang polanya. $\pi$ $(3,14159265...)$ dan theorema konstanta euler theorema $e$ ($2,718...$) adalah raja di kerajaan Irasional.
Kesimpulan: **Benar** ✔️

**C. Ekstremitas Akar tak Sempurna vs Imajiner**
Gagal mengenali domain realita. Bilangan khayalan imajiner murni cuma satu kaum yaitu menampuh paksa genjatan bilangan minus bersarang mencelup di jeruji tanda akar kuadrat ($contoh: \sqrt{-5}$). Sementara $\sqrt{2} = 1,4142...$ adalah sekadar rombongan suku kaum Irasional yang merupakan WARGA DAN PENDUDUK SAH benua Bilangan REAL/Nyata. 
Kesimpulan: **Salah** ❌

---

## Soal 3: Pilihan Ganda Kompleks MCMA (Lebih dari 1 Jawaban Benar)
Pilihlah wujud penjabaran dan persinggahan rasional eksponen-akar yang hasil simplifikasinya terverifikasi murni bermuara pada pencetakan bilangan bulat nol atau setara negatif (Bilangan bulat non-positif). Pilihlah dari menu yang tersedia di bawah secara teliti!

- [ ] $\dots - (\sqrt{5} - \sqrt{2})(\sqrt{5} + \sqrt{2}) + 3$
- [ ] $(2^{0}) - (\sqrt[3]{-1})$
- [ ] $(\frac{1}{2})^{-2} - 8$
- [ ] $\frac{\sqrt{80}}{\sqrt{5}} - 4$
- [ ] $4^{\frac{3}{2}} - \sqrt{49}$

**Pembahasan:**
Mari preteli kalkulasinya masing-masing, cari yang hasilnya $0, -1, -2$, dst (Intinya Bukan bilangan Asli positif $>0$):
1. $- (5 - 2) + 3 = -(3) + 3 = 0$. (Masuk kriteria target non-positif). ✅
2. $2^0 = 1$. $\sqrt[3]{-1} = -1$. Lalu: $1 - (-1) = 1 + 1 = 2$. (Hasil $2$, ini Positif / Salah Target). ❌
3. $(1/2)^{-2} = 2^2 = 4$. Lanjut: $4 - 8 = -4$. (Dihasilkan angka Minus, termasuk target kriteria non-positif!). ✅
4. $\frac{\sqrt{80}}{\sqrt{5}} = \sqrt{16} = 4$. Melaju: $4 - 4 = 0$. (Target masuk jaring nol!). ✅
5. $4^{\frac{3}{2}} = (2^2)^{\frac{3}{2}} = 2^3 = 8$. Lanjut $\sqrt{49} = 7$. Maka $8 - 7 = 1$. (Hasil Bilangan Asli Positif 1, Salah bidik gawang). ❌

Jadi rentetan pilihan himpunan rasional logis bernuansa non-positif menyasar lekat di jajaran Opsi sentral bernomor punggung **1, 3, dan 4**.

---
**Navigasi:**
- [⬅️ Kembali ke Materi](../bilangan-real.md)
