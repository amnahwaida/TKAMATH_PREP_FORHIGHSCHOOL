# Latihan Soal Set 4: Transformasi Geometri

> **Elemen:** [Geometri & Pengukuran](../index.md) | **Materi:** [Transformasi Geometri](../transformasi.md) | **Set 1:** [Latihan 1](transformasi.md) | **Set 2:** [Latihan 2](transformasi-2.md) | **Set 3:** [Latihan 3](transformasi-3.md) | **Kembali ke Home:** [🏠 README](../../../README.md)

---

## Soal 1: Pilihan Ganda (PG)
Diberikan persamaan sebuah garis lurus $3x - 4y + 12 = 0$. Garis tersebut kemudian dirotasikan secara berlawanan arah jarum jam sejauh $90^\circ$ dengan titik pusat rotasi di pusat koordinat asal $O(0,0)$. Setelah rotasi, garis bayangan tersebut ditranslasikan (digeser) dengan matriks vektor $T = \begin{pmatrix} -2 \\ 1 \end{pmatrix}$. Manakah persamaan bayangan akhir dari garis tersebut?

A. $4x + 3y + 17 = 0$  
B. $4x + 3y + 7 = 0$  
C. $-4x + 3y - 17 = 0$  
D. $4x - 3y + 7 = 0$  
E. $3x + 4y - 12 = 0$  

**Pembahasan:**
**Langkah 1: Menyelesaikan parameter Rotasi $90^\circ$**
Pemetaan titik untuk rotasi memutar berlawanan arah jarum jam sebesar $90^\circ$ dari pusat $(0,0)$ mematuhi kaidah:
$(x' , y') = (-y , x)$.
Dari formula ini, kita mendapatkan substitusi matematis membalik: $x = y'$ dan $y = -x'$.
Substitusikan nilai ini ke dalam garis awalan:
$$ 3(y') - 4(-x') + 12 = 0 $$
$$ 3y' + 4x' + 12 = 0 \implies 4x' + 3y' + 12 = 0 $$
Ini adalah persamaan bayangan putaran rotasinya.

**Langkah 2: Melanjukan pergeseran Translasi $T(-2, 1)$**
Pemetaan translasi mendikte hukum pergeseran:
$x'' = x' + (-2) \implies x' = x'' + 2$
$y'' = y' + 1 \implies y' = y'' - 1$

Kemudian subtitusikan ke dalam fungsi persamaan garis bayangan rotasi sebelumnya:
$$ 4(x + 2) + 3(y - 1) + 12 = 0 $$
$$ 4x + 8 + 3y - 3 + 12 = 0 $$
$$ 4x + 3y + 17 = 0 $$

Hasil paripurna menghasilkan kurva lurus **$4x + 3y + 17 = 0$**. 
Jawaban tepat tertera pada opsi **A**.

---

## Soal 2: Pilihan Ganda Kompleks Kategori (Benar/Salah)
Matriks ordo 2x2 merupakan alat fundamental dalam merekayasa pembentukan bayangan objek. Tinjau setiap pernyataan transformasi di bawah ini dan tentukan kebenaran matriks pemetaannya!

- A. Pencerminan sebuah objek fungsi terhadap pusat rotasi titik origin koordinat $O(0,0)$ memberikan imbas dan hasil bayangan yang secara matematis persis sama dengan perputaran rotasi rotasi sebesar $180^\circ$ pada pusat origin yang sama.
- B. Suatu dilatasi memusat pada origin $(0,0)$ dengan faktor skala perbesaran $k=-2$ akan menghasilkan sebuah objek bayangan raksasa berskala dua kali lipat yang secara grafis akan tercetak tepat dan sejajar menduduki kuadran murni asalnya sendiri tanpa melompati sumbunya.
- C. Jika komposisi transformasi dibangun berurutan oleh Refleksi Sumbu $X$ lalu disusul Refleksi Sumbu $Y$, secara matematis, keseluruhan operasi tersebut identik dengan perumusan satu langkah yaitu Rotasi pada titik asali $O(0,0)$ dengan derajat kelengkungan mutlak di angka $180^\circ$.

**Pembahasan:**
**A. Refleksi Pusat Titik $O(0,0)$ ekuivalen Rotasi $180^\circ$**
Memantulkan titik $P(x,y)$ menembus titik nol $0(0,0)$ akan menghasilkan pantulan dengan koordinat $P'(-x, -y)$. Dan sebuah rotasi putar sebesar $180^\circ$ memiliki kaidah pemetaan persis mendarat searah di titik yang sama yaitu $P'(-x, -y)$. Keduanya merupakan transformasi setara yang ekuivalen satu sama lain.
Kesimpulan: **Benar** ✔️

**B. Dampak Dilatasi $k = -2$**
Faktor pengali yang bernilai negatif mendandakan bahwa objek tidak hanya diperbesar luas porsinya, mutlak pula diproyeksikan menembus titik pangkal dilatasi secara terbalik menyeberang (menciptakan bayangan sungsang merangkak ke sisi seberang lawannya). Objek tidak akan mempertahankan domisili kuadran asalnya melainkan terlempar mencelat ke kuadran tumpu berseberangan secara menyilang sejauh titik garis lurus menembus nol.
Kesimpulan: **Salah** ❌

**C. Gabungan Komposisi Refleksi Sumbu $X$ kemudian Sumbu $Y$**
Mari menguraikan koordinat sembarang titik:
Mulai dengan $P(x, y)$.
Dicerminkan terhadap garis dasar Sumbu X: menghasilkan $P'(x, -y)$.
Lalu dieksekusi Refleksi lanjutan menempel Sumbu Y: menjadi $P''(-x, -y)$.
Hasil akhir $P \to P''$ adalah pertukaran kedua kutub angka $(x, y) \to (-x, -y)$. Ini terbukti mendemonstrasikan secara telak hasil mutlak perputaran Rotasi $180^\circ$.
Kesimpulan: **Benar** ✔️

---

## Soal 3: Pilihan Ganda Kompleks MCMA (Lebih dari 1 Jawaban Benar)
Pilihlah seluruh rincian kaidah pernyataan yang mengawal kebenaran matematis dalam memfungsikan formula Inversi terhadap sistem transformasi bentuk 2 Dimensi. Pilihlah dari rentetan identitas rasional di bawah yang mengantongi predikat penafsiran absolut yang benar secara logis!

- [ ] Matriks invers dari sebuah operasi Refleksi tehadap suatu sumbu pencerminan mana pun dipastikan selalu jatuh menjelma kembali ke wujud wujud identikal matriks refleksi asalnya semula (Identitas tunggal tanpa rubahan).
- [ ] Matriks invers untuk menetralkan sebuah proses Dilatasi pusat sentral sumbu $O(0,0)$ dengan faktor skala penyesuaian $k$, menuntut perumusan matriks pembalik dengan menyematkan faktor skalar bernilai setara fraksional sepertiganya.
- [ ] Jikalau ada sebuah sistem komposisi bertindih perputaran $T_{total} = T_2 \circ T_1$, matriks inversnya wajib disusun menggunakan hukum asosiatif bolak-balik aljabar matriks $\implies (T_2 \circ T_1)^{-1} = (T_1)^{-1} \circ (T_2)^{-1}$.
- [ ] Matriks pelebur Rotasi senilai minus, yaitu Rotasi memutar $(-90^\circ)$, dipastikan sejalan murni identik dengan formulasi Rotasi sejauh perputaran sebesar $270^\circ$.
- [ ] Matriks yang mencatatkan deretan sel kolom-baris $\begin{pmatrix} 0 & 1 \\ 1 & 0 \end{pmatrix}$ merupakan wakil absolut penyempurnaan wujud matriks putaran rotasional $90^\circ$ mendasar.

**Pembahasan:**
Menyelaraskan hukum alam ordo matriks transformasi:
1. Jika ditarik kesimpulan komprehensif, mentransformasi sebuah pencerminan hingga menyentuh "invers" kebalikannya (mengembalikannya ke keadaan normal semulajadi), maka instrumen pembatalkannya adalah melakukan pencerminan ulang dengan cermin yang sama persis sediakala itu pula. Secara teknis, Matriks $M^{-1} = M$ eksklusif pada seluruh kategori pilar matriks Refleksi. Fakta teori ini benar absolut. ✅
2. Jika objek dilebarkan dengan pengali $k$, maka proses mengecilkannya kembali merujuk pengerutan menjadi membaginya dengan fraksi rasio $1/k$. Ini ditranslasikan dalam matriks perbesaran matriks berkepribadian skala konstan $\frac{1}{k}$. Namun pernyataan menyebut sepertiganya (keterangan absurd keliru melantur, karena bukan $1/3$, melainkan wajib $\frac{1}{k}$). ❌
3. Formulasi murni Invers untuk rangkaian perkalian rantai silang aljabar matriks beruntun adalah menjungkirkembalikan urutannya mendarat dari relasi yang diproses tertinggal pamungkas menuju yang perdana: $(T_2 \cdot T_1)^{-1} = T_1^{-1} \cdot T_2^{-1}$. Ketetapan ini berlaku benar seutuhnya. ✅
4. Berputar mundur melawan gravitasi navigasi sejauh minus putaran ($-90^\circ$) artinya berbelok selaras menyatu padu seiring rotasi maju utuh sisa derajat keliling sejauh genap ($360^\circ - 90^\circ = 270^\circ$). Eksplisit dan logis murni. ✅
5. Matriks kolom baris yang disematkan susunan angka nol sejajar miring $\begin{pmatrix} 0 & 1 \\ 1 & 0 \end{pmatrix}$ merupakan entitas hukum pencipta cermin lurus Pencerminan terhadap garis asimtot sentral diagonal $\mathbf{y = x}$. Bukan dan tidak pernah menjadi Matriks rotasi murni (Rotasi $90^\circ$ adalah $\begin{pmatrix} 0 & -1 \\ 1 & 0 \end{pmatrix}$). Perbedaannya memangkas minus satu arah tegangan. ❌

Rentetan serapan kesesuaian nilai tertib matematika mengerucut mutlak membentangi Opsi susunan bernomor punggung **1, 3, dan 4**.

---
**Navigasi:**
- [⬅️ Kembali ke Materi](../transformasi.md)
