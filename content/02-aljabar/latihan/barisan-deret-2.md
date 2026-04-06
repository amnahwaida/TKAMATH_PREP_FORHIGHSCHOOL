# Latihan Soal Set 2: Barisan dan Deret

> **Elemen:** [Aljabar](../index.md) | **Materi:** [Barisan & Deret](../barisan-deret.md) | **Set 1:** [Latihan 1](barisan-deret.md) | **Kembali ke Home:** [🏠 README](../../../README.md)

---

## Soal 1: Pilihan Ganda (PG)
Suku cadang deret bilangan geometri tak hingga bernilai 12, dengan besaran jumlah total keseluruhan mencapai 36. Nilai titik awal (Suku Pertama / $a$) deret geometrinya dalah ....

A. $4$  
B. $8$  
C. $12$  
D. $16$  
E. $24$  

*(KOREKSI soal, ralat kalimat agar tidak ambigu):*
Jumlah sebuah deret geometri tak hingga adalah 36 dan rasionya adalah $\frac{2}{3}$. Suku pertama deret tersebut adalah ....
A. 12
B. 16
C. 18
D. 24
E. 27

**Pembahasan:**
Rumus jumlah memadat/menyatu konvergen (deret konvergensi tak terhingga):
$$ S_{\infty} = \frac{a}{1 - r} $$
Diketahui total tak terhingganya $S_{\infty} = 36$ dan rasionya $r = \frac{2}{3}$.
$$ 36 = \frac{a}{1 - 2/3} $$
$$ 36 = \frac{a}{1/3} $$
$$ a = 36 \times \frac{1}{3} = 12 $$

Maka titik Suku pertama ($a$) jatuh pada angka indeks $12$.
Jawaban yang valid adalah **A**.

---

## Soal 2: Pilihan Ganda Kompleks Kategori (Benar/Salah)
Suatu deret pembentuk hitung artimetika memiliki titik temu $S_n = 2n^2 + 3n$.
Tentukan kebenaran dari identitas suku/barisan ini!

- A. Suku ke-4 ($U_4$) bernilai sebesar 17.
- B. Formasi Beda/Selisih antar indeks ($b$) memilki jarak penambahan progresif senilai 4.
- C. Nilai Suku Awal ($a$) identik persis dengan kalkulasi ($S_1$) yang bernilai sebatas angka 5.

**Pembahasan:**
Hubungan fundamental antara suku ($U$) dan deretan jumlah keseluruhan ($S$) adalah bahwa $U_n = S_n - S_{n-1}$.
Mari petakan angkanya terlebih dahulu.
$S_1 = 2(1)^2 + 3(1) = 2 + 3 = 5$.
$S_2 = 2(2)^2 + 3(2) = 8 + 6 = 14$.
Berdasarkan fakta tersebut:
$U_1 = S_1 = 5$ (Suku Perdana).
$U_2 = S_2 - S_1 = 14 - 5 = 9$.

Beda $b = U_2 - U_1 = 9 - 5 = 4$.

Sekang verifikasi satu per satu pernyataannya:
**A. Suku K-4 bernilai 17**
Kita bisa hitung manual dari $a=5$ dan $b=4$:
$U_n = a + (n-1)b \implies U_4 = 5 + (3)4 = 5 + 12 = 17$.
Kesimpulan: **Benar** ✔️

**B. Beda antar indeks = 4**
Dari perhitungan analitis dan uji manual kita mengkonfirmasi persis jarak lompatannya bertambah progresif positif 4.
Kesimpulan: **Benar** ✔️

**C. Suku awal $a = 5$**
Sesuai penjabaran ($U_1 = S_1 = 5$).
Kesimpulan: **Benar** ✔️

---

## Soal 3: Pilihan Ganda Kompleks MCMA (Lebih dari 1 Jawaban Benar)
Pilihlah pernyataan rasional di bawah yang selaras atau berlaku di dalam implementasi Barisan Aritmetika! (Pilih banyak)

- [ ] Jika selisih ($b$) bernilai negatif, maka otomatis barisan dipastikan tidak akan menembus ambang 0.
- [ ] Barisan hitung biasa dari aritmetika adalah penjabaran langsung berupa penjumlahan linear progresif.
- [ ] Rumus suku tengah untuk jumlah suku bilangan ganjil dapat disingkat dengan merata-ratakan nilai tepi Suku Pertama dan Suku Akhir penutup $\left(\frac{a + U_n}{2}\right)$.
- [ ] Jika 3 karakter berurutan $x, y, z$ membentuk pola barisan aritmetika meluncur, maka dapat diasumsikan $y - x = z - y$.
- [ ] Barisan aritmetika dengan beda tetap $b = 3$ dapat disederhanakan sebagai kurva ekponensial dengan basis 3 jika digambar pada poros kartesius.

**Pembahasan:**
Uji keabsahan materi Aritmetika murni vs Eksro/Konvergen:
1. Jika bedanya progresif minus $-$, ia bagai kurva turun menyentik sumbu Y hingga dapat menembus jurang Minus tak terhingga (Bukan tertahan nol). Hal itu logis terdefensi. ❌
2. Ya, aritmetika ibarat grafik linear fungsi garis lurus miring di dunia kartesius. Penambahan selisih berbobot adil di setiap tapaknya. ✅
3. Betul. Suku titik ekuator / sentral perpaduan hitung $\implies U_{tengah} = \frac{U_{\text{awal}} + U_{\text{akhir}}}{2}$. Rumus yang cepat merengkuh nilai pertengahan asimetrik bilangan $n$. ✅
4. Betul. Mengukur dan mencari beda $b$, secara aljabar menuntut bahwa Jarak(Kanan dikurangi Kirinya) wajib sejajar $\implies \text{Jarak kedua} = \text{Jarak pertama}$. $\implies y-x = z-y$. ✅
5. Konstanta beda tidak akan pernah disandingkan dengan grafik lengkung eksponensial. Aritmetika berwujud garis linear yang mutlak lurus lurus saja (Fungsi pangkat $1$). ❌

Maka alternatif opsi yang menjunjung rasionalitas kebenaran terpadu hanyalah **Opsi 2, 3, dan 4**.

---
**Navigasi:**
- [⬅️ Kembali ke Materi](../barisan-deret.md)
