# Latihan Soal Set 4: Fungsi & Komposisi Invers

> **Elemen:** [Aljabar](../index.md) | **Materi:** [Fungsi](../fungsi.md) | **Set 1:** [Latihan 1](fungsi.md) | **Set 2:** [Latihan 2](fungsi-2.md) | **Set 3:** [Latihan 3](fungsi-3.md) | **Kembali ke Home:** [🏠 README](../../../README.md)

---

## Soal 1: Pilihan Ganda (PG)
Diketahui fungsi komposisi dua relasi matematika berbunyi $(f \circ g) (x) = 4x^2 + 8x - 3$. Pada kondisi tersebut, diketahui pula relasi salah satu fungsinya yaitu $g(x) = 2x + 4$. Berdasarkan informasi di atas, tentukan persamaan dasar dari $f(x)$!

A. $x^2 + 4x + 3$  
B. $x^2 - 4x - 3$  
C. $x^2 - 8x + 13$  
D. $4x^2 - 2x + 1$  
E. $2x^2 + 6x - 4$  

**Pembahasan:**
Konsep fungsi komposisi menjelaskan bahwa: 
$f(g(x)) = 4x^2 + 8x - 3$
Substitusi nilai fungsi $g(x)$ yang telah diketahui: $f(2x + 4) = 4x^2 + 8x - 3$.

Untuk mencari $f(x)$, lakukanlah pemisalan terikat:
Misal variabel $\alpha = 2x + 4$, maka dapat dipecahkan penjabaran atas nilai $x$:
$2x = \alpha - 4 \implies x = \frac{\alpha - 4}{2}$.

Substitusi nilai $x$ tersebut kembali ke dalam persamaan utama:
$$ f(\alpha) = 4\left(\frac{\alpha - 4}{2}\right)^2 + 8\left(\frac{\alpha - 4}{2}\right) - 3 $$
Uraikan operasi pangkat beserta perkalian distribusinya:
$$ f(\alpha) = 4\left(\frac{\alpha^2 - 8\alpha + 16}{4}\right) + 4(\alpha - 4) - 3 $$
Selesaikan penyederhanaan dengan membagi angka 4:
$$ f(\alpha) = (\alpha^2 - 8\alpha + 16) + (4\alpha - 16) - 3 $$
Kelompokkan berdasar variabel yang ekuivalen:
$$ f(\alpha) = \alpha^2 - 8\alpha + 4\alpha + 16 - 16 - 3 $$
$$ f(\alpha) = \alpha^2 - 4\alpha - 3 $$

Setelah diganti menjadi notasi yang semestinya, persamaan yang tepat adalah $f(x) = x^2 - 4x - 3$. 
Jawaban tersebut bersinggungan langsung dengan opsi **B**.

---

## Soal 2: Pilihan Ganda Kompleks Kategori (Benar/Salah)
Domain terbatas dan batas mendatar adalah fenomena asimtot di dalam pembelajaran teori Fungsi. Analisis pernyataan matematis rasional berhubung asimtot dan batas fungsi di bawah untuk menentukan mana yang valid Bernilai Benar/Salah!

- A. Fungsi berbentuk rasional pecahan bernilai $f(x) = \frac{x - 3}{x^2 - 9}$ tidak mempunyai bentuk Asimtot Vertikal, melainkan hanya mempunyai satu daerah kelowongan (hole) tepat pada ordinat rasional bernilai $x = 3$.
- B. Asimtot datar (horizontal asymtot) mendeskripsikan tren batasan kurva bernilai konstan ketika $x$ mengarah pada batas tak terhingga. Fungsi fungsional relasional $f(x) = \frac{4x^2 - 5}{1 - 2x^2}$ memiliki asimtot datar tepat pada sumbu bernilai $y = -2$.
- C. Pada relasi rasio logaritma, semisal fungsi logaritma bernilai $y = \log_2(x+5)$, nilai variabel basis fungsi (domain yang diizinkan untuk dikalkulasi) dipisahkan oleh kaidah bernilai khusus $x > -5$.

**Pembahasan:**
**A. Syarat Kemunculan Asimtot dan Lubang (Hole)**
Fungsi $f(x) = \frac{x-3}{(x-3)(x+3)}$. 
Pada titik di mana pembilang dan penyebut bernilai nol bersamaan ($x = 3$), akan terbentuk sebuah lonjakan tanpa data yang diklasifikasikan sebagai lubang (*hole*).
Namun pada nilai penyebut sama dengan nol tetapi pembilang bukan nol ($x = -3$), kondisi tersebut membentuk Asimtot Vertikal.
Hal ini berarti fungsi ini memiliki Asimtot Vertikal di sumbu $x = -3$, sehingga pernyataan bahwa fungsi tersebut tidak memilikinya sama sekali dipastikan cacat.
Kesimpulan: **Salah** ❌

**B. Pengamatan Terhadap Limit Tuju Nilai Tak Berhingga**
Batas asimtot datar diselesaikan dengan Theorema Kalkulus Limit menuju nilai konstan tuju rentang ($\infty$).
Karena pangkat tertinggi pada nilai pembilang dan nilai penyebut selevel, yaitu sama-sama dua, koefisiennya langsung diturunkan:
Rasio limit $= \frac{4}{-2} = -2$.
Asimtot datar benar posisinya di persinggahan mendatar kurva rasional $y = -2$.
Kesimpulan: **Benar** ✔️

**C. Nilai Domain Batas Logaritma**
Aturan definisi matematika untuk fungsi algoritma menyatakan bahwa bilangan yang dilogaritmakan (numerus) wajib bernilai lebih besar dari titik angka $0$. 
Oleh sebab itu, $x+5 > 0 \implies x > -5$. Hal ini terbukti benar.
Kesimpulan: **Benar** ✔️

---

## Soal 3: Pilihan Ganda Kompleks MCMA (Lebih dari 1 Jawaban Benar)
Pillihlah fungsi-fungsi di bawah ini yang memenuhi Theorema Inversi (Sebuah fungsi dan inversinya dapat saling mengembalikan posisinya sebagai korespondensi satu-satu yang bersifat Injektif dan Bijektif)! Memiliki Fungsi Invers berarti tidak terdapat dua masukan yang bernilai domain rentang persis sama.

- [ ] Fungsi Logaritma $y = \ln(x-2)$.
- [ ] Relasi horizontal konstan bernilai $y = 8$.
- [ ] Kurva berbentuk $y = |x - 4|$.
- [ ] Fungsi pertautan eksklusif bentuk pecah $y = \frac{3x - 1}{x + 2}$.
- [ ] Garis gelombang periodik tak bertepi $y = \sin(x)$ sepanjang domain rentangan batas rasional bilangan real $(-\infty, \infty)$.

**Pembahasan:**
Verifikasi korespondensi satu-satu dengan "Uji Garis Horizontal":
Sebuah fungsi dipastikan berinjam terikat menjadi fungsi korespondensi atau Injektif jika nilai grafiknya tidak ada yang memotong satu garis datar menyilang sama dengan nilai taksiran $Y$.
1. Kurva perhitungan Logaritma natural $\ln(x)$ bersifat monoton naik terus dan grafik tersebut tak akan mencapai posisi datar. Hal ini meluluskan uji satu-satu. Ia memiliki Invers bernilai rasional. ✅
2. Fungsi konstanta mendatar $y=8$ sudah menggariskan lintasannya selalu tepat mendatar di poin nomor 8. Grafiknya ditakdirkan memotong berulang kali dengan jumlah titik angka dominan tak terbatas, sehingga batal. ❌
3. Semua grafis Nilai Mutlak berbentuk seperti huruf kapital V. Saat meletakkan seutas penggaris mendatar secara visual, garis tersebut akan menyentuh memotong pada posisi dua ruas kurvanya. Cacat sebagai fungsional ter-invers. ❌
4. Fungsi pecahan rasional hiperbola dalam kalkulus dapat diuraikan persamaan Invers secara standar umum dengan mengaplikasikan substitusi silang dan pencabutan aljabar (Inversnya adalah rupa dari $\frac{-2x - 1}{x - 3}$). ✅
5. Kurva asimetri Trigonometri Sinus berjalan meliuk konstan seperti ombak tak terbatas, yang jelas nilai Y-nya akan menyentuh batas konstan tinggi di banyak titik potong melimpah. Oleh sebab itu, fungsi ini tidak mempunyai spesialisasi eksklusif pada batas bilangan real total sehingga bukan dikategorikan sebagai fungsi 1-1 (Gagal syarat mempunyai Invers penuh, kecuali domain sinusnya didekat dan ditutupi paksa di jangkauan batas sempit $-90^\circ$ hingga $+90^\circ$). ❌

Ragam penunjukan fungsi bersilang yang tervalidasi mempunyai sifat invers adalah poin rasional merujuk **1 dan 4**.

---
**Navigasi:**
- [⬅️ Kembali ke Materi](../fungsi.md)
