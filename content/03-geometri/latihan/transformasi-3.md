# Latihan Soal Set 3: Transformasi Geometri

> **Elemen:** [Geometri & Pengukuran](../index.md) | **Materi:** [Transformasi Geometri](../transformasi.md) | **Set 1:** [Latihan 1](transformasi.md) | **Set 2:** [Latihan 2](transformasi-2.md) | **Kembali ke Home:** [🏠 README](../../../README.md)

---

## Soal 1: Pilihan Ganda (PG)
Titik simpul $P(6, -2)$ dihantam pergerakan ganda dilatasi dengan parameter sentral pemusat dilatasi berasal mulanya bukan di nol, tapi ditarik di titik koordinat poros acuan $Q(-2, 4)$ berindeks faktor skala renggangan menciut terkalikan rasio fraksi merapat $k = \frac{1}{2}$. Di petak batas manakah bayangan kordinat sang titik bermukim merapat akhirnya?

A. $(2, 1)$  
B. $(2, 2)$  
C. $(4, 1)$  
D. $(-2, -3)$  
E. $(6, 4)$  

**Pembahasan:**
Rumus jaring laba-laba dilatasi teritorial titik bebas tak terkekang poros $Q(a, b)$:
$$ x' = k(x - a) + a $$
$$ y' = k(y - b) + b $$

Pusatkan pilar sentral acuan $a = -2$, $b = 4$.
Sedangkan target sorot si subjek mangsa titik adalah di $x = 6$, $y = -2$.
$k = \frac{1}{2}$.

Hitung merapat absis $x'$:
$$ x' = \frac{1}{2}(6 - (-2)) + (-2) = \frac{1}{2}(6 + 2) - 2 = \frac{1}{2}(8) - 2 = 4 - 2 = 2 $$

Hitung lebur ordinat $y'$:
$$ y' = \frac{1}{2}(-2 - 4) + 4 = \frac{1}{2}(-6) + 4 = -3 + 4 = 1 $$

Maka pelabuhan hasil sandaran letak bayangan akhir tak lain menciut tenang pada poros $(2, 1)$.
Jawaban akurat yang paling mulus berada singgasana **A**.

---

## Soal 2: Pilihan Ganda Kompleks Kategori (Benar/Salah)
Matriks pembangun perombakan transformasi 2D pada bidang miring sering disandinkan dengan pemetaan vektor baris per kolom. Teliti asersi di bawah dan tegaskan kegenapan kebenaran rasionya!

- A. Translasi sejatinya sama sekali belum bisa digambarkan oleh wujud Matriks $2 \times 2$ orisinil murni karena kodrat translasi mensyaratkan eksistensi wujud pergeseran titik pertambahan konstan, bukan perkalian vektor matriks berpusat $(0,0)$.
- B. Matriks Refleksi yang bertatap cermin murni di atas sumbu absis horizontal ($y=0$ / sumbu X), susunan pemetaannya menyodorkan blok sel deret matriks $\begin{pmatrix} -1 & 0 \\ 0 & 1 \end{pmatrix}$.
- C. Setiap kali subjek mendedikasikan perombakannya di luar batas Rotasi/Refleksi/Translasi, jika matriks dilatasi menyodorkan variabel perbesaran $(3,3)$ di diagonal sumbu pilar kiri ke kanan miringnya maka bayangan determinasi lonjakan determinan terhitung melebar jadi 3 kali lipat area luasnya.

**Pembahasan:**
**A. Relational Matriks berhadap Translasi**
Transformasi linear (Rot, Ref, Dil) memiliki kaitan mutlak rumus $\vec{r'} = M \cdot \vec{r}$. Operasi dasar ini melambungkan Matriks $2 \times 2$. NAMUN hal itu tak bekerja buat sekadar Translasi! Translasi menghidangkan operasi penjumlah-gabungan ($T + \vec{r}$), tak pernah ada perkalian ordo $2 \times 2$ yang dapat mendongkrak matriks geser yang melulu beranjak merayap dari nol (0). Kita membedakannya dalam "Koordinat Homogen 3D".
Kesimpulan: **Benar** ✔️

**B. Matriks Cermin (Refleksi) Sumbu X**
Cermin absis $(y=0)$ membalik merapatkan target posisi ordinat jadi setelan ganjil minus sementara absis tetap eksis. Format $x' = x$, $y' = -y$.
Ini bertepatan formasi matrik peretak: $\begin{pmatrix} 1 & 0 \\ 0 & -1 \end{pmatrix}$. (X tak diputus, Y dikali -1). Pernyataan di soal terbalik di penempatan matriks $\begin{pmatrix} -1 \\ 1 \end{pmatrix}$. Matriks opsi sana kepunyaan rupa pencerminan poros sumbu vertikal/Ordinat Y.
Kesimpulan: **Salah** ❌

**C. Determinan Matriks Skalar Berpengaruh 3x Lipat Luas Saja?**
Suatu matriks renggangan $\begin{pmatrix} 3 & 0 \\ 0 & 3 \end{pmatrix}$ menandakan faktor $k=3$. Jika matriks merombak membesarkan 3 kali dari pinggang dan pundak serentak, maka secara harfiah determinan luasan permukaannya mengacu relasi skalar mutlak $Det = (3 \times 3) - (0 \times 0) = 9$. Area jembatan luas bayangannya memuai jadi **9 kali Lipat**, tak terhenti sebatas 3 kali lipat saja!
Kesimpulan: **Salah** ❌

---

## Soal 3: Pilihan Ganda Kompleks MCMA (Lebih dari 1 Jawaban Benar)
Seutas fungsi kuadrat bergengsi mengalun menukik mendeskripsikan persaman kurva lengkung di ranah $y = x^2 - 6x + 8$. Jikalau kelak disusup perombakan operasi pencerminan mentah terhadap alas titik dasar rotasi $(0,0)$ / atau titik pusat asal semesta, pilihlah konsekuensi-konsekuensi yang merasuk memaparkan relasi persamaan transfigurasi final grafik terbarunya secara legal nan tak terbantah! (Jawaban bernilai lebih dari satu)

- [ ] Bayangan pemetaaan baru mencetak rekat wujud persamaan $y = -x^2 - 6x - 8$.
- [ ] Posisi asali titik balik palung curam mula-mula yang dulunya terjerembab pada sumbu $(3, -1)$ mendadak meloncat beringas ke puncak singgasana bayangannya menjadi ordinat $(3, 1)$.
- [ ] Terkandung serapan translasi secara otomatis saat kita mencetak perputaran refleksi di sentral 180 derajatnya $(0,0)$. 
- [ ] Grafik terbalik itu mulus memotong perlintasan potong silang ke jalur landasan sumbu Y menjamahi titik koordinat persis letak $(0, -8)$.
- [ ] Nilai interses absis pemotongan lempeng garis horizontal (Sumbu X) bergeser murni menyatu pada dua titik poros potong di tapak semesta $(-2,0)$ dan $(-4,0)$.

**Pembahasan:**
Refleksi titik pusat / rotasi $180^\circ$:
Semua simpul kordinat ditampar keras oleh minus di semua penjuru sumbu $\to (-x, -y)$.
Ulah rumus pada aslinya $\implies$ Subtitusikan $y \to -y$ dan $x \to -x$.
$-y = (-x)^2 - 6(-x) + 8$
$-y = x^2 + 6x + 8 \implies y = -x^2 - 6x - 8$.

Evaluasi:
1. Kurva beralih rapi menyandang bentuk relasi $y = -x^2 - 6x - 8$. Sah merapat validitas (Benar). ✅
2. Uji titik ekstrim asali. Turunan $y' = 2x-6 = 0 \implies x=3$. Disubstitusi $y = 3^2 - 6(3) + 8 = 9-18+8 = -1$. (Jadi asal palungnya $(3,-1)$). Lalu di cermin memusat 0 nol $\to y \cdot (-1), x \cdot (-1)$. Maka bayangannya harusnya mutlak mencetak koordinat $(-3, 1)$. Namun narasi di tabel sesat mendikte ordinat mutlak ke $(3, 1)$. (Batal Salah). ❌
3. Refrensi di putaran Nol murni rotasi tidak bercokol mengakar ke sistem tumpangan komposit Translasi sama sekali. Salah tafsir yang diselundupkan secara ngawur. ❌
4. Cari potong Sumbu Y (mematok x=0) pada rekayasa bayangan. $y = -(0)^2 - 6(0) - 8 \implies y = -8$. Sah memotong di tapak $(0, -8)$. Terjamin presisi (Benar). ✅
5. Potong Sumbu X di mana y=0. $(-x^2 - 6x - 8 = 0) \implies (x^2 + 6x + 8 = 0) \implies (x+4)(x+2) = 0$. $x = -4$ dan $x = -2$. Tapak perakarannya persis identik dengan klaim perpotongannya $(-4,0)$ dan $(-2,0)$. Valid Absolut (Benar). ✅

Ringkasan serapan dalil paling presisi nan akurat memusat di perolehan opsi **1, 4, dan 5**.

---
**Navigasi:**
- [⬅️ Kembali ke Materi](../transformasi.md)
