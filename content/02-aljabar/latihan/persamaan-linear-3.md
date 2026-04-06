# Latihan Soal Set 3: Sistem Persamaan Linear & Pertidaksamaan

> **Elemen:** [Aljabar](../index.md) | **Materi:** [Persamaan Linear](../persamaan-linear.md) | **Set 1:** [Latihan 1](persamaan-linear.md) | **Set 2:** [Latihan 2](persamaan-linear-2.md) | **Kembali ke Home:** [🏠 README](../../../README.md)

---

## Soal 1: Pilihan Ganda (PG)
Dua buah bilangan jika dijumlahkan menyodorkan agregat angka total 40. Apabila seperempat dari bilangan pertama ditambah dengan setengah rata bilangan kedua membuahkan nilai eksak $16$. Manakah selisih (beda) antara kedua variabel misterius tersebut?

A. $4$  
B. $8$  
C. $12$  
D. $16$  
E. $24$  

**Pembahasan:**
Misalkan bilangan tersebut dipetakan dengan inisial variabel $a$ dan $b$.
Persamaan I (Total Penjumlahan): $a + b = 40 \implies b = 40 - a$.
Persamaan II (Sub-fraksinya): $\frac{1}{4}a + \frac{1}{2}b = 16$.

Kita setarakan penyebut Persamaan II (kalikan seluruh rusuk dengan $4$):
$a + 2b = 64$.
Sekarang kita substitusikan $b = 40 - a$ ke sana:
$$a + 2(40 - a) = 64$$
$$a + 80 - 2a = 64$$
$$-a = 64 - 80 = -16 \implies a = 16$$

Jika $a=16$, maka $b = 40 - 16 = 24$.
Minta perbandingan selisih: $|b - a| = |24 - 16| = 8$.

Selisih perbandingan rasio menyajikan angka $8$. Opsi akurat menjurus pada huruf **B**.

---

## Soal 2: Pilihan Ganda Kompleks Kategori (Benar/Salah)
Penyelesaian Sistem Linear Tiga Variabel (SPLTV) melahirkan ruang penyelesaian gabungan himpunan. Uji klaim di bawah untuk menyingkap teori irisan persinggungan garis linear pada ruang kordinat 3 Dimensi.

- A. Pada grafik grafis semesta tiga sumbu (X, Y, Z), selembar persamaan Linear Tiga Variabel ($ax+by+cz=d$) digambarkan eksis rupa sebagai bongkahan kubus tiga dimensi penuh.
- B. SPLTV mempunyai solusi himpunan tunggal $(x, y, z)$ yang spesifik, apabila manifestasi rupa dari ketiga bidang berpotongan secara sentral di satu pilar titik temu utama.
- C. Mustahil terbentuk sistem tanpa penyelesaian (Tak Punya Solusi) dari irisan tiga formula, berhubung dimensinya bebas dan saling memagut tak terikat ruang batas 2D.

**Pembahasan:**
**A. Rupa grafis persamaan adalah Kubus 3D**
Garis/relasi formula dimensi 1 di bidang datar (2D) bermuara gambar Garis. Di Ruang tiga dimensi (3D), sebuah Persamaan Tiga Variabel linear melukiskan selembar **Kertas Datar/Bidang Tipis**, BUKAN kubus volumenisasi utuh. 
Kesimpulan: **Salah** ❌

**B. Titik Tunggal Terjadi Ketika Bidang memusat di Se-titik Temu**
Konsepsi murni linear aljabar: tiga kertas yang menusuk dan ditancap melintang satu sama lain akan terbentur / dipertemukan dalam posisi persekusi di satu titik seujung jarum potong. Inilah konfirmasi titik koordinat utuh $(x, y, z)$ penyelesaian tunggalnya.
Kesimpulan: **Benar** ✔️

**C. Kemustahilan Kehampaan Solusi SPLTV**
Tiga perisai bidang datar bisa saja dipetakan sejajar identik melayang rukun tanpa pernah berciuman sekalipun di rentang alam semesta 3D (Sejajar/Paralel total). Hal ini melembagakan fenomena *Tanpa Solusi* (Tidak ada irisan himpunan tuntas sama sekali).
Kesimpulan: **Salah** ❌

---

## Soal 3: Pilihan Ganda Kompleks MCMA (Lebih dari 1 Jawaban Benar)
Sebuah perusahaan pakaian menjahit perpotongan kemeja dan celana menelan durasi spesifik. 1 kemeja menguras $2$ jam merajut, $1$ jam bordir. 1 celana ditaksir rewel melahap $1$ jam merajut, namun $2$ jam bordir. Mesin rajut dan mesin bordir secara mekanis hanya beroperasi dengan membatasi daya nyala maksimal 10 jam per harinya.
Gali pundi-pundi pertidaksamaan, putuskan rincian penyajian formula optimalisasi linear mana yang mendahului kepresisian sesuai teks di atas!

- [ ] Jika Kemeja $= x$ dan Celana $= y$, maka fungsi batas utilitas rajutnya diekspos sebagai $2x + y \le 10$.
- [ ] Area limit kemampuan utilitas mesin bordir terlukis di kurva kartesius melalui batasan relung $x + 2y \ge 10$.
- [ ] Batas alamiah sumbu produksi konvensional mutlak digembar-gemborkan oleh relasi $x \ge 0$ dan $y \ge 0$.
- [ ] Jika persahaan hendak menjual kemeja beromzet margin profit murni Rp50.000 dan Celana menembus taksiran Rp70.000, Fungsi Sasarannya termaknai sebagai $Z = 50.000x + 70.000y$.
- [ ] Perusahaan sangat diperbolehkan dan dapat mendistribusikan waktu merajut 5 kemeja bersama 5 keping celana secara simultan berbarengan dalam satu hari kalender jam kerja tanpa melanggar sumbu maksimumnya.

**Pembahasan:**
Metode dekonstruksi teks tabel sistematis:
- Tabel Merajut: Kemeja(x) menyerap 2h, Celana(y) 1h $\implies$ Total batas 10h. Mode pertidaksamaan: $2x + 1y \le 10$.
- Tabel Bordir: Kemeja(x) menyedot 1h, Celana(y) 2h $\implies$ Batas 10h. Mode pertidaksamaaan: $1x + 2y \le 10$.
- Omzet / Sasaran: Untung $= 50.000x + 70.000y$.

Filter opsional:
1. Batas rajut $2x + y \le 10$. Benar tertabulasikan presisi! ✅
2. Batas mesin bordir membatasi maskimal ($Max$), tidak bisa mesin bekerja melebih/melanggar (Lebih dari). Sehingga simbol $\ge 10$ adalah SALAH KAPRAH yang fatal (harus $\le 10$). ❌
3. Syarat fundamental produk/barang adalah Non-Negativity constraint $x, y \ge 0$. Tiada perusahaan bisa memproduksi baju berjumlah MINUS. ✅
4. Fungsi laba utilitas totalnya dipatok pada laju kumulasi $50000x+70000y$. Rasional. ✅
5. Menguji $x=5$ dan $y=5$ pada utilitas Rajut kendala pertama:
   $2(5) + 1(5) = 10 + 5 = 15$ jam. Ini menabrak fatal kuota jam rajut perhari yang cuma sedia 10 Jam. Perusahaan mendongkrak tak bisa memproduksi serempak ini. ❌

Opsi konfirmasi yang berhasil mengeksplor rasionalitas kebenaran terpadu merujuk sentimen nomor **1, 3, dan 4**.

---
**Navigasi:**
- [⬅️ Kembali ke Materi](../persamaan-linear.md)
