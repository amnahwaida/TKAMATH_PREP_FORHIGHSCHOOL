# Latihan Soal Set 4: Sistem Persamaan Linear & Pertidaksamaan

> **Elemen:** [Aljabar](../index.md) | **Materi:** [Persamaan Linear](../persamaan-linear.md) | **Set 1:** [Latihan 1](persamaan-linear.md) | **Set 2:** [Latihan 2](persamaan-linear-2.md) | **Set 3:** [Latihan 3](persamaan-linear-3.md) | **Kembali ke Home:** [🏠 README](../../../README.md)

---

## Soal 1: Pilihan Ganda (PG)
Sepasang relasi pertidaksamaan memaparkan eksistensi wilayah mutlak irisan ruang daerah batasan (DP - Daerah Penyelesaian) di sepanjang kartesius 2 sumbunya:
Kondisi A: $y \ge x^2 - 4x - 5$
Kondisi B: $y \le -x + 5$
Garis melentur parabola membuka lapang ke atas sementara sabuk linear menjepit turun sebagai atasannya (himpitan tertutup).
Berdasarkan asupan pertidaksamaan tadi, koordinat manakah dari poin paku sembarang di penjuru bawah ini yang lolos bersemayam nyaman bertahta di DALAM zona arsiran penampung irisan keduanya?

A. $(0, 6)$  
B. $(3, 1)$  
C. $(-2, 4)$  
D. $(6, -3)$  
E. $(4, 8)$  

**Pembahasan:**
Akan kita uji silang subsitusikan masing opsional titik masuk menuju gawang kedua persyaratan untuk mengorek keabsahan murninya. Jika memuaskan kedua perisai batas sekaligus, berhak dia bertahta di kawasan aman irisan (Arsiran Daerahnya).
Persyaratan valid:
- Parabola Dasar (Lantai): $y \ge x^2 - 4x - 5$
- Atap Linear (Tutup Atas): $y \le -x + 5$

**A (0,6):**
Parabola: $6 \ge (0)^2 - 0 - 5 \implies 6 \ge -5$ (Valid).
Atap: $6 \le -0 + 5 \implies 6 \le 5$ (BATAL SALAH $\implies$ Tembus Plafon).

**B (3,1):**
Parabola: $1 \ge (3)^2 - 4(3) - 5 \implies 1 \ge 9 - 12 - 5 \implies 1 \ge -8$ (Valid).
Atap: $1 \le -(3) + 5 \implies 1 \le 2$ (Valid! Lolos verifikasi).

**C (-2,4):**
Parabola: $4 \ge (-2)^2 - 4(-2) - 5 \implies 4 \ge 4 + 8 - 5 \implies 4 \ge 7$ (BATAL).

**D (6,-3):**
Parabola: $-3 \ge 6^2 - 4(6) - 5 \implies -3 \ge 36 - 24 - 5 \implies -3 \ge 7$ (BATAL).

**E (4,8):**
Atap: $8 \le -(4) + 5 \implies 8 \le 1$ (BATAL).

Hanya satu kandidat pion yang terselamatkan dengan nyaman bersarang di dalam kepungan sistem mutlak wilayah irisan, yakni Opsi **B**.

---

## Soal 2: Pilihan Ganda Kompleks Kategori (Benar/Salah)
Pemodelan relasional batas ekstrem optimisasi program linear mewajibkan pemisahan tegas antrean pertidaksamaan tumpuan. Inspeksi rasionalitas pernyataan pengujian limit optimisasinya! 

- A. Rentang relasi dari $x + y \le 8$ dan $x + y \ge 12$ melukiskan ruang bentangan arsir ganda pararel membujur lurus ke kanan jauh sejauh semesta tiada akhir tapal batasnya.
- B. Fungsi objektif bernilai $Z = 3x - 2y$ akan merangkak perlahan memuncak mendulang pencapaian setinggi-tingginya jika koordinat X direntang masif ke kutub besar namun variabel Y digencet sekecil kerdil di titik bawah dasar kemungkinannya.
- C. Jikalau di dalam grafis pertidaksaman Linear tercantum parameter koefisien non statis misal dibingkai model $ax + by \le c$, lalu direngkuh manipulasi pembagian ke seisi elemennya memakai selongsong bilangan bulat negatif (minus), mulut capit tanda lebih kecil ($\le$) harus takluk diserang balik arah memutar sungsang menjadi ($\ge$).

**Pembahasan:**
**A. Himpitan Arsir $x+y \le 8$ DAN $x+y \ge 12$**
Logika semantik dasar linear! Bisakah seraut angka penjumlah total ditarik memuaskan takdir MENJADI KURANG DARI 8 rupiah TAPI sekaligus dimaksa LEBIH BESAR DARI 12 rupiah? Mustahil! Himpunan ini tidak menghasilkan irisan terbuka membentang melainkan Himpunan Kosong tak berpenduduk $\emptyset$. Kedua arsiran tumpang-tindih asimetris memalingkan membuang punggung menjauhi.
Kesimpulan: **Salah** ❌

**B. Fungsi Memuncak Nilai $(-2y)$**
Perumusan $Z = 3x - 2y$. Agar nominal pamungkas nilai Z melambung raksasa meroket tinggi, tentu unsur positif penyokong ($+3x$) wajib dijejali nominal sangat bongsor masif. Di kancah sebaliknya, pengurang beban minus $(-2y)$ harus ditumpulkan sekerdil mungkin hingga sekecil ampasnya supaya tak banyak menyerap meluruhkan keuntungan uang kas total si Z tersebut. Pernyataannya tepat menyuguhkan esensi perumusan.
Kesimpulan: **Benar** ✔️

**C. Sifat Mutlak pertidaksamaan dikekang minus**
Kapanpun sebuah palang identitas kemiringan Pertidaksamaan ditabrakkan dan dihujani unsur selongsong bilangan berbasis negatif membagi/mengalikan seluruh lengannya di ruas kanan dan kiri (cth $-2x \le -8$, dibagi $-2$), rambu-rambu capit gergaji otomatis hukum wajib tertukar terbalik haluan mengamankan pilar validitas kesetaraan mutlak ($x \ge 4$). 
Kesimpulan: **Benar** ✔️

---

## Soal 3: Pilihan Ganda Kompleks MCMA (Lebih dari 1 Jawaban Benar)
Dikurung sistem pemetaan Nilai Mutlak yang mengekang jeruji absolut perataan $x$ dengan relasi sebar persamaan absolut $|2x - 3| - |x + 1| = 0$. Eksplorasi akar-akar mutlak dan telikung jangkauan yang menemuai garis kesesuaian tervalidasi benar mendiami jajaran selongsong daftar rincian opsional tabel beruntun ini! (Kalkulasi berpeluang menjawab sah menembus lebih dari selapis opsi yang hadir).

- [ ] Salah satu sumbu rentangan nilai rahasia teka-teki variabel $x$ memuaskan dirinya merebahkan diri di lempengan genap rupa koordinat absis menduduki angka bulat asali bernilai murni merapat yakni nominal mutlak 4.
- [ ] Angka basis pecahan berjejer $x = \frac{2}{3}$ adalah punggung titik koordinat serapan sejati lainnya membebaskan kurungan penyelesaian tersebut mengantarkannya pada kemerdekaan absolut titik ekuivalen rasionya.
- [ ] Hasil penampungan serapan tumpuan rentang galian tebakan penyelesaian total memiliki dua pilar jawaban valid merentang semesta di $x = 0$ dan $x = 2$.
- [ ] Persamaan Nilai Mutlak bersilang setimbang tersebut memproyeksikan rasional identitas jika dirangkai penguraiannya mencopot menumpu di jeruji alalisis $\implies (2x - 3) = \pm(x + 1)$.
- [ ] Jika dihimpun secara merata ditarik tali simpulan menjumlah agregat nilai X yang valid lulus ($x_1 + x_2$), kuota saldonya mempersebahkan jejak agregat rasio mampat total setara bilangan rasional fraksional perpaduan membelah batas di jejak bilangan seukuran sekisar bernilai $\frac{14}{3}$.

**Pembahasan:**
Pembedahan tereksekusi persamaan absolut absolut: 
$|2x - 3| - |x + 1| = 0  \implies |2x - 3| = |x + 1|$
Mengeliminasi sangkar kandang jeruji mutlak di kedua kubu (memiliki 2 sekenario pemecahan plus/minus):
Mode penyelesaian $\implies$ $2x - 3 = x + 1$ ATAU $2x - 3 = -(x + 1)$. (Opsi 4 tepat terdefinisikan). ✅

Eksekusi sekenario Puncak A (Kanan Positif):
$$ 2x - x = 1 + 3 \implies x = 4 $$  (Maka akar genap pertama mendarat mutlak mendulang X=4). ✅ (Opsi 1 tembus dan Opsi 3 otomatis gugur).

Eksekusi sekenario Puncak B (Kanan Negatif menyilang):
$$ 2x - 3 = -x - 1 \implies 3x = 2 \implies x = \frac{2}{3} $$  (Akar murni sekunder mendarat bertaut di fraksinasi 2 per 3). ✅

Lakukan rekam jejak sumasi / Agregat Pertambahan $X$ ($x_1 + x_2$):
$$ \Sigma x = 4 + \frac{2}{3} = \frac{12}{3} + \frac{2}{3} = \frac{14}{3} $$ (Diverifikasi genap selaras tuntas tepat). ✅

Jajaran rumusan analisis di Opsi-Opsi tervalidasi mengangkasa dan merajai rujukan centang kebenaran utuh pada susunan barikade opsi bernomor seri **1, 2, 4, dan 5**.

---
**Navigasi:**
- [⬅️ Kembali ke Materi](../persamaan-linear.md)
