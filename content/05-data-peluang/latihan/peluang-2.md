# Latihan Soal Set 2: Peluang

> **Elemen:** [Data & Peluang](../index.md) | **Materi:** [Peluang](../peluang.md) | **Set 1:** [Latihan 1](peluang.md) | **Kembali ke Home:** [🏠 README](../../../README.md)

---

## Soal 1: Pilihan Ganda (PG)
Dua buah dadu enam sisi homogen seimbang dilambungkan/dilempar berbarengan di atas meja hijau kasino secara random. Kemungkinan presentase peluang frekuensi absolut munculnya dadu dengan sisi kembar beranggotakan nomor serupa atu serempak jumlah angka dari sepasang matanya mutlak seukuran komputasi nilai $8$ adalah ...

A. $\frac{10}{36}$  
B. $\frac{5}{18}$  
C. $\frac{11}{36}$  
D. $\frac{1}{3}$  
E. $\frac{5}{36}$  

**Pembahasan:**
Total kejadian melemparkan 2 dadu sekaligus mencakup probabilitas penuh semesta $n(S) = \text{Dadu}_1 \times \text{Dadu}_2 = 6 \times 6 = 36$ titik ruang.

Kita mendamba 2 alternatif target dalam himpunan gabungan (Konjungsi "Atau").
Himpunan A (Kembar Identik):
$A = \{(1,1), (2,2), (3,3), (4,4), (5,5), (6,6)\}$. Total $n(A) = 6$ skenario.

Himpunan B (Jumlah nominalnya ekuivalen $8$):
$B = \{(2,6), (3,5), (4,4), (5,3), (6,2)\}$. Total $n(B) = 5$ skenario.

Inspeksi irisan kejadian yang menimpa sekaligus dua kriteria bertumpuk (Intersection $A \cap B$) $\implies$ Dadu bermuka kembar sekaligus menjumlah menjadi angka $8$.
Kondisi beririsan ini terjadi eksklusif pada fenomena muncul dadu $(4,4)$. Maka $n(A \cap B) = 1$.

Peluang Majemuk Gabungan (Aturan Penjumlahan kejadian Tidak Lepas):
$$ P(A \cup B) = \frac{n(A) + n(B) - n(A \cap B)}{n(S)} $$
$$ P(A \cup B) = \frac{6 + 5 - 1}{36} = \frac{10}{36} $$
$$ = \frac{5}{18} $$ (hasil pengerutan faktor pembagian).

Porsi kemungkinan teoretis ini memuaskan rumusan yang membayang pada opsi **B**.

---

## Soal 2: Pilihan Ganda Kompleks Kategori (Benar/Salah)
Tentukan Benar atau Salah tiap klaim dan pernyataan operasional perhitungan mengenai Aturan Kuasa Kaidah Pencacahan untuk mengatur rotasi huruf dan benda mati!

- A. Sandi 4 digit PIN tersusun merangkai 4 kombinasi angka sejati acak diperbolehkan mengulang-ulang. Peluang meretas (dengan susunan spesifik target sukses mutlak $1$ buah urutan doang), probabilitas kesuksesan merogohnya memuncak pada perolehan $\frac{1}{10.000}$.
- B. Jumlah kombinasi dari kata dasar **"MAKAM"** untuk disusul ulang pengacakannya adalah $24$ variasi rupa kata random beraturan.
- C. Perbedaan mutlak komparatif (Permutasi dan Kombinasi) ialah Permutasi merevitalisasi eksklusivitas unsur penataan hirarki urutan posisi susunan, sedang Kombinasi santai menggabungkan gerombolan massa komplotan sembarang tanpa menghiraukan sekat pangkat.

**Pembahasan:**
**A. Probabilitas meretas 4 pin (0-9, berulang)**
Jumlah angka eksis $0 \implies 9$ ada genap secarik 10 biji. Pin 4 digit $= 10 \times 10 \times 10 \times 10 = 10.000$ macam rupa taksir. Kesuksesan meraihnya pada peluang meretas tepat pas susunan rahasia mutlak cuma memilki $\frac{1}{10.000}$ margin kemenangan.
Kesimpulan: **Benar** ✔️

**B. Pengacakan anagram kata "MAKAM"**
Memakai permutasi anasir/unsur ganda identik rupa tak terbedakan.
Kata "MAKAM" total memikul $n=5$ slot aksara huruf.
Huruf M ada 2 buah (dobel), A ada 2 buah (dobel), dan K ada 1 mandiri.
Cara susun: $P = \frac{5!}{2! \times 2!} = \frac{120}{2 \times 2} = \frac{120}{4} = 30$ variasi himpunan anagram. BUKAN $24$.
Kesimpulan: **Salah** ❌

**C. Konsep Beda Tipis Kombinasi/Permutasi**
Secara gamblang menterjemahkan dikotominya bahwa Permutasi mutlak terbebani tatanan dan ranking (AB tidak sama dengan BA), sedari itu Kombinasi masa bodo (memilih regu campur-aduk permen bebas).
Kesimpulan: **Benar** ✔️

---

## Soal 3: Pilihan Ganda Kompleks MCMA (Lebih dari 1 Jawaban Benar)
Pilihlah kombinasi penafsiran permutasi melingkar atau deret urut di bawah ini yang memandu konklusi penjabaran kalkulasinya pada nilai setara yang tak dapat diindahkan, lebih tepatnya beresolusi total mengantongi persis hasil variasi sejumlah $120$ macam rupa tatanan berbeda! (Jawaban valid lebih dari satu).

- [ ] Membariskan jejeran 5 orang perwira secara serentak sejajar berjajar memanjang horisontal menduduki sesi foto tanpa embel-embel syarat.
- [ ] Menyusun jamuan makan formal meletakkan 6 utusan menteri kabinet negara berduduk tatanan memutar meronda di lingkaran karpet agung oval.
- [ ] Nilai perkalian fraksi pencacahan mutlak permutasi dari rasio $P(6, 3)$.
- [ ] Membentuk formasi panitia inti $3$ buah perwalian hirarki atas berstruktur (Ketua, Sekretaris, Manajer) memangkas kandidat kerumunan terpadu delegasi serombongan 6 subjek peserta calon pendaftar tunggal yang eksis mendaftar.
- [ ] Pengurutan secara silang untuk sebuah kata anagram tak seirama kembar (Misal "KASUR").

**Pembahasan:**
Kalkulasi setiap pernyataan untuk menelisik apa saja yang menghadap hasil akhir menembus $120$:
1. Berbaris linear $5$ entitas terpisah. Permutasi lurus $n! = 5! = 5 \times 4 \times 3 \times 2 \times 1 = 120$. ✅
2. Melingkar siklis melingkungi bundaran bertotal pesertanya 6 makhluk. Permutasi $= (6-1)! = 5! = 120$ gaya berurutan. ✅
3. Mutlak rasio permutasi $P(6, 3) = \frac{6!}{(6-3)!} = \frac{6!}{3!} = 6 \times 5 \times 4 = 120$. ✅
4. Merangkut hirarki susun mencomot kandidat jabatan itu wajib taat mutlak Permutasi (Ranking matters). Calon 6 diambil 3 jabatan asimetris $\implies P(6, 3) = 120$. ✅
5. Anagram kata merdeka seratus persen tiada aksara ganda rupa. $n=5$ huruf ("K, A, S, U, R"). Cara susun linear $= 5! = 120$. ✅

Segala permohonan penyelesain dari kesuluruh deretan tersebut berakumulasi sepakat absolut bermuara ke padanan keragaman himpunan merengkuh persis total variasi $120$.
Maka semua kompartemen tatanan poin **1, 2, 3, 4, dan 5** valid terkonfirmasi absolut mencetak angka setara.

---
**Navigasi:**
- [⬅️ Kembali ke Materi](../peluang.md)
