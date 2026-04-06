# Latihan Soal: Peluang

> **Elemen:** [Data & Peluang](../index.md) | **Materi:** [Peluang](../peluang.md) | **Kembali ke Home:** [🏠 README](../../../README.md)

---

## Soal 1: Pilihan Ganda (PG)
Disediakan $6$ buah kursi yang diatur melingkar di sekeliling meja bundar. Ada berapa cara menempatkan $6$ orang sahabat akrab pada kursi-kursi tersebut dengan syarat $2$ orang tertentu selalu duduk berdampingan?

A. $24$ cara  
B. $48$ cara  
C. $120$ cara  
D. $240$ cara  
E. $720$ cara  

**Pembahasan:**
Duduk melingkar akan memakai permutasi siklis: $(n-1)!$.
Karena $2$ orang harus berdampingan, ikat mereka menjadi $1$ entitas tunggal.
Maka unsur objek yang akan disikluskan menjadi $(6 - 2) + 1 = 5$ entitas.

Banyak cara permutasi siklis dari 5 entitas: $(5-1)! = 4! = 24$.
Lalu, ingat bahwa $2$ orang yang diikat juga bisa bertukar tempat sesamanya sebanyak $2!$ cara $= 2$.

Maka formasi susunan total:
$24 \times 2! = 24 \times 2 = 48$ cara formasi.

Jawaban yang paling tepat adalah **B**.

---

## Soal 2: Pilihan Ganda Kompleks Kategori (Benar/Salah)
Tiga keping uang logam dilempar secara bersamaan, setiap uang logam memiliki sisi Angka (A) dan Gambar (G). 
Tentukan Benar atau Salah tiap pernyataan yang berkaitan dengan percobaan tersebut!

- A. Ruang Sampel (Total Seluruh kemungkinan) dari pelemparan tersebut adalah 6.
- B. Pelemparan tiga keping koin menghasilkan paling tidak peluang kejadian munculnya dua Angka sebesar $\frac{3}{8}$.
- C. Peluang ketiganya menunjukkan muka yang sama adalah $\frac{1}{4}$.

**Pembahasan:**
Tiap koin punya $n=2$ kemungkinan, dilempar 3 buah $\implies \text{Ruang Sampel } N(S) = 2^3 = 8$.

**A. Ruang Sampel adalah 6**
Seharusnya $8$. (AAA, AAG, AGA, GAA, AGG, GAG, GGA, GGG).
Kesimpulan: **Salah** ❌

**B. Peluang muncul tepat dua Angka**
Titik sampel dengan 2 angka (AAG, AGA, GAA), ada 3 kejadian.
Maka Peluangnya $P = \frac{3}{8}$.
Kesimpulan: **Benar** ✔️

**C. Peluang muncul muka yang persis sama ke-tiaknya**
Titik sampel (AAA, GGG), ada 2 kejadian.
Peluangnya $P = \frac{2}{8} = \frac{1}{4}$.
Kesimpulan: **Benar** ✔️

---

## Soal 3: Pilihan Ganda Kompleks MCMA (Lebih dari 1 Jawaban Benar)
Terdapat sebuah kotak berisi sekumpulan kelereng: $4$ kelereng merah, $3$ kelereng biru, dan $2$ kelereng hijau. Seseorang merogoh mengambil acak $3$ butir sekaligus dari kantong tersebut. Pilihlah dari kemungkinan probabilitas (peluang) kejadian berikut yang hasil perhitungannya benar! 

- [ ] Peluang terambil kelereng yang memiliki warga seragam (satu warna saja), adalah $\frac{5}{84}$.
- [ ] Peluang terambilnya kombinasi $2$ merah dan $1$ biru adalah $\frac{3}{14}$.
- [ ] Peluang terambil spesifik warna secara seimbang (masing-masing satu untuk tiap warna) adalah $\frac{2}{7}$.
- [ ] Peluang terambil minimal satu bola hijau adalah $1 - \frac{C(7,3)}{C(9,3)}$.
- [ ] Banyak seluruh cara berbeda pengambilan 3 buah bola adalah $64$ variasi kombinasi.

**Pembahasan:**
Analisis terlebih dahulu kombinasi populasinya:
Total bola $= 4 + 3 + 2 = 9$. Mengambil 3 kelereng.
Ruang sampel, $N = C(9, 3) = \frac{9 \times 8 \times 7}{3 \times 2 \times 1} = 3 \times 4 \times 7 = 84$.

Evaluasi Opsi:
1. Warna seragam: berpeluang terpilih semua 3 merah atau semua 3 biru. (Karena yang hijau hanya 2, tak mungkin mencukupi untuk seleksi 3 buah seragam).
   $n(\text{Sama}) = C(4, 3) + C(3, 3) = 4 + 1 = 5 \implies$ Peluang $= \frac{5}{84}$. (Benar) ✅
2. Terambil 2 Merah($M$) 1 Biru($B$):
   $n = C(4,2) \times C(3,1) = 6 \times 3 = 18 \implies$ Peluang $= \frac{18}{84} = \frac{3}{14}$. (Benar) ✅
3. Terambil 1 Merah, 1 Biru, 1 Hijau:
   $n = C(4,1) \times C(3,1) \times C(2,1) = 4 \times 3 \times 2 = 24 \implies$ Peluang $= \frac{24}{84} = \frac{2}{7}$. (Benar) ✅
4. Minimal terambil 1 Hijau. Pakai peluang komplemen ($1$ dikurangi tiada kejadian mendapat Hijau sama sekali).
   "Tanpa masuknya unsur kelereng hijau" $\implies$ merogoh populasi sisa $7$ (M+B). Cara $= C(7,3)$.
   Sehingga Peluang Minimal 1 Hijau $= 1 - \frac{C(7,3)}{C(9,3)}$. (Benar) ✅
5. Jumlah total cara mengambil 3 dari 9. Telah kita hitung bahwa $C(9,3) = 84$ variasi kombinasi (Bukan $64$). (Salah) ❌

Jawaban valid yang tepat adalah **Opsi 1, 2, 3, dan 4**.

---
**Navigasi:**
- [⬅️ Kembali ke Materi](../peluang.md)
