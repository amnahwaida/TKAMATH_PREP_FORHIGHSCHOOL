# Latihan Soal Set 2: Sistem Persamaan Linear

> **Elemen:** [Aljabar](../index.md) | **Materi:** [Persamaan Linear](../persamaan-linear.md) | **Set 1:** [Latihan 1](persamaan-linear.md) | **Kembali ke Home:** [🏠 README](../../../README.md)

---

## Soal 1: Pilihan Ganda (PG)
Ahmad, Budi, dan Cici membeli alat tulis di toko yang sama. 
Ahmad membeli 2 buku, 1 pulpen, dan 1 pensil sebesar Rp14.000. 
Budi membeli 1 buku, 2 pulpen, dan 1 pensil sebesar Rp11.000. 
Cici membeli 3 buku, 2 pulpen, dan 2 pensil sebesar Rp24.000. 
Berapakah harga 1 buku?

A. Rp3.000  
B. Rp4.000  
C. Rp5.000  
D. Rp6.000  
E. Rp7.000  

**Pembahasan:**
Misalkan Buku = $x$, Pulpen = $y$, Pensil = $z$.
Sistem persamaan (SPLTV):
1) $2x + y + z = 14.000$
2) $x + 2y + z = 11.000$
3) $3x + 2y + 2z = 24.000$

Eliminasi $z$ dari pers (1) dan (2):
$(2x + y + z) - (x + 2y + z) = 14.000 - 11.000$
$x - y = 3.000 \implies y = x - 3.000$ ... (Pers. 4)

Eliminasi $z$ dari pers (1) kali 2 terhadap (3):
$(4x + 2y + 2z) = 28.000$
$(3x + 2y + 2z) = 24.000$
Kurangkan:
$x = 4.000$

Jadi harga 1 buah buku adalah **Rp4.000**.
Jawaban yang benar adalah **B**.

---

## Soal 2: Pilihan Ganda Kompleks Kategori (Benar/Salah)
Tentukan Benar atau Salah tiap pernyataan yang mendeskripsikan sifat penyelesaian dari suatu Sistem Persamaan Linear Dua Variabel (SPLDV) $a_1x + b_1y = c_1$ dan $a_2x + b_2y = c_2$ !

- A. Jika perbandingan $\frac{a_1}{a_2} = \frac{b_1}{b_2} = \frac{c_1}{c_2}$, maka sistem memiliki tak hingga banyak solusi.
- B. Jika grafik kedua persamaan tersebut saling sejajar dan tidak berhimpit, maka SPLDV tersebut tidak memiliki hasil selesaian sama sekali.
- C. Selesaian sebuah SPLDV selalu berupa bilangan bulat, tidak pernah berupa pecahan.

**Pembahasan:**
**A. Rasio antar koefisien persis sama**
Jika ketiga rasionya sama persis, berarti persamaan kedua hanyalah kelipatan dari persamaan pertama. Gambaran grafiknya akan berupa dua garis yang berhimpit secara sempurna. Karenanya solusinya tak terhingga.
Kesimpulan: **Benar** ✔️

**B. Garis sejajar dan tidak berhimpit**
Jika dua garis linear tidak berpotongan maupun tidak pula berhimpit, hal itu berarti rasio $x,y$ proporsional namun konstantanya tidak $\left( \frac{a_1}{a_2} = \frac{b_1}{b_2} \neq \frac{c_1}{c_2} \right)$. Hal ini memastikan mustahil ada titik temu (solusi gabungan).
Kesimpulan: **Benar** ✔️

**C. Selesaian SPLDV selalu bulat**
Tidak benar. Selesaian SPLDV bisa berupa bilangan bulat, desimal, maupun pecahan asalkan menunjuk pada titik potong yang presisi (misal pertigaan atau perdelapanan).
Kesimpulan: **Salah** ❌

---

## Soal 3: Pilihan Ganda Kompleks MCMA (Lebih dari 1 Jawaban Benar)
Pilihlah pertidaksamaan-pertidaksamaan yang titik origin $(0,0)$ dan titik $(-2, 3)$ keduanya termasuk ke dalam daerah domain penyelesaiannya (terarsir)! (Jawaban lebih dari satu).

- [ ] $2x + y \le 5$
- [ ] $x - y \ge -6$
- [ ] $x + 2y \le -1$
- [ ] $y \ge -x$
- [ ] $3y \le x + 12$

**Pembahasan:**
Gunakan metode cek substitusi ke dalam pertidaksamaan tersebut pada titik $(0,0)$ lalu ke titik $(-2,3)$. Sebuah pertidaksamaan dianggap benar bila memuaskan kedua-duanya.

1. $2x + y \le 5$:
   Cek $(0,0)$: $0 \le 5$ (Valid).
   Cek $(-2,3)$: $-4 + 3 \le 5 \implies -1 \le 5$ (Valid). ✅
2. $x - y \ge -6$:
   Cek $(0,0)$: $0 \ge -6$ (Valid).
   Cek $(-2,3)$: $-2 - 3 \ge -6 \implies -5 \ge -6$ (Valid). ✅
3. $x + 2y \le -1$:
   Cek $(0,0)$: $0 \le -1$. (SALAH). ❌
4. $y \ge -x \implies y + x \ge 0$:
   Cek $(0,0)$: $0 \ge 0$ (Valid).
   Cek $(-2,3)$: $3 - 2 \ge 0 \implies 1 \ge 0$ (Valid). ✅
5. $3y \le x + 12 \implies 3y - x \le 12$:
   Cek $(0,0)$: $0 \le 12$ (Valid).
   Cek $(-2,3)$: $3(3) - (-2) \le 12 \implies 9 + 2 \le 12 \implies 11 \le 12$ (Valid). ✅

Maka jawaban yang benar adalah **opsi 1, 2, 4, dan 5**.

---
**Navigasi:**
- [⬅️ Kembali ke Materi](../persamaan-linear.md)
