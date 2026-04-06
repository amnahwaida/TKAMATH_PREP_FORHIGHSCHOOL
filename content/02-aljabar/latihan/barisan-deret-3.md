# Latihan Soal Set 3: Barisan & Deret

> **Elemen:** [Aljabar](../index.md) | **Materi:** [Barisan & Deret](../barisan-deret.md) | **Set 1:** [Latihan 1](barisan-deret.md) | **Set 2:** [Latihan 2](barisan-deret-2.md) | **Kembali ke Home:** [🏠 README](../../../README.md)

---

## Soal 1: Pilihan Ganda (PG)
Aplikasi deret geometri tak berujung (tak hingga konvergen) terjadi pantulan bola kasti. 
Sebuah bola tenis pingpong terjatuh secara bebas terseret gravitasi dari ketinggian asali 10 meter. Setiap menumbuk lantai beton, ia memantul tegak kembali melayang terbang dengan rekor pencapaian puncak ketinggian sejauh rasio $\frac{3}{5}$ dari tapak tinggi lintasan jatuhnya di putaran mendahuluinya. Berapakah panjang keseluruhan jejak lintasan gerak bola di terowongan udara dari awal dilepas sampai lelah berhenti tanpa daya sentuh melompat lagi?

A. 15 meter  
B. 25 meter  
C. 40 meter  
D. 50 meter  
E. 60 meter  

**Pembahasan:**
Bola jatuh perdana $\implies h_0 = 10$.
Rasio pantul eksponensial $r = \frac{3}{5}$.

Sistem lintasan total untuk lintasan vertikal bola terjatuh bebas selalu membentuk 2 sekuens deret (deret jatuh dan deret pantul ke atas bergantian). Jalan singkat rumus jembatan keledai untuk gerak pantul abadi ($S_\infty$) adalah:
$$ \text{Lintasan Total} = \left( \frac{m + n}{m - n} \right) \times h_0 $$
Jika rasio $r = \frac{n}{m}$, dan ketinggian perdana ditarik bebas dari $h_0$.
Diketahui $r = \frac{3}{5} \implies n = 3, m = 5$.
$$ S = \left( \frac{5 + 3}{5 - 3} \right) \times 10 $$
$$ S = \left( \frac{8}{2} \right) \times 10 = 4 \times 10 = 40 \text{ meter}. $$

Jeda total lintasan gerak vertikal menduduki rasio 40.
Jawaban terkonfirmasi mantab di pilihan **C**.

---

## Soal 2: Pilihan Ganda Kompleks Kategori (Benar/Salah)
Analisis Benar Salah konklusi matematis berikatan dengan perhitungan simpanan bunga bank berganda (Bunga Majemuk / Tabungan Eksro)!

- A. Nominal saldo kumulatif akhir sebuah setoran tabungan statis modal di bank bila digulirkan lewat perhitungan Bunga Tunggal akan selalu memproduksi profit uang absolut yang bertengger persis sepadan bahkan sama kencangnya meroket dibandingkan model perhitungan Bunga Majemuk pada dekade tahun pertama.
- B. Sistem pemupukan bunga modal pada model Bunga Majemuk tak pernah peduli memecah pokok dana melainkan selalu konsisten mengais persentase dari asupan bibit awal pendanaannya tanpa menghiraukan saldo terakhir berputar.
- C. Jika modal ditanam sejuta (1 juta rupiah) berlapis margin majemuk $10\%$ rutin per tahunnya, rekor capaian di lembar akhir tahun kalender yang ke-2 akan terpampang menembus gundukan Rp1.210.000,00.

**Pembahasan:**
**A. Konklusi komparasi kemajuan tahun Pertama di antara Bunga Tunggal dan Bunga Majemuk**
Sangat masuk akal sehat mendasar! Khusus di siklus ulang tahun pertama ( $t=1$ ), belum ada bunga melimpah tumpang tindih. Entah mematok rasio *Tunggal / Flat* maupun terjerumus reksa *Majemuk beranak-pinak*, jumlah saldo hasil penuaian yang disajikan mutlak nominalnya identik sama pada persentase awalannya.
Kesimpulan: **Benar** ✔️

**B. Tabiat Karakter Bunga Majemuk yang Statik**
Ini terbalik fatwa penipuan semata. Justru Bunga Tunggallah (Bunga *Flat* Pegadaian Biasa) yang statik mati-kutu mencomot jatah hanya murni bersandar di pangkuan modal pangkal $M_0$. Sebaliknya, Bunga Majemuk amatlah progresif rakusnya sebab ia meremas margin dari saldo menimbun terakhir berjalan di setiap siklus perputaran ($M_n = M_{t-1} + margin$).
Kesimpulan: **Salah** ❌

**C. Simulasi Bunga Majemuk Rp1 Juta**
Tahap tahun I: $1.000.000 \times 1,1 = 1.100.000$
Tahap tahun II berputar berlandaskan basis $1,1$ juta tadi $\implies 1.100.000 \times 1,1 = 1.210.000$. Kalkulasi murni akurat nan padu tanpa selisih cacat.
Kesimpulan: **Benar** ✔️

---

## Soal 3: Pilihan Ganda Kompleks MCMA (Lebih dari 1 Jawaban Benar)
Suatu deret untaian ritmis membentuk susunan formasi linear bertahap angka $4, 7, 10, 13, 16, \dots$. Berbekal formasi tapak tilas urutan tersebut, tandai seluruh rangkuman dalil penaksir matematis terapan di sekitarnya yang memuat takaran konklusi valid penuh kebenaran semisal di uji forensik aljabar!

- [ ] Pola pengundak-undakan irisan indeksnya mendeskripsikan secara sah sosok barisan Aritmetika berpola mendaki dengan nilai rasio eksaserbasi progresif $+3$ bedanya.
- [ ] Rumus rahasia (Master Key) general perangkai indeks suku ke-$n$ bisa disingkat mampatkan bervalensi fungsional linear ke bingkai $U_n = 3n + 1$.
- [ ] Angka yang bertengger nongkrong menduduki kursi jabatan ke-15 di gerbong barisan tersebut tiada lain memeluk entitas $46$.
- [ ] Apabila diringkas membundel penjumlahan $S_n$ sepuluh seri penggalan awalnya ($n=10$), jumlah agregat yang tertimbun mutlak merayap senilai 175 poin saldo utuh.
- [ ] Bentuk perulangan kumulasi (Summation) baris linear ritmis aritmetika di level apapun dijamin mencetak persamaan kuadrat sempurna menembus asimtot $(S_n \implies (\ldots)n^2 + \ldots)$ untuk relasi deret agregat pemadunya.

**Pembahasan:**
Analisis rupa Barisan ($4, 7, 10, 13, \dots$):
Terverifikasi bertata dasar: suku pijakan awal $a=4$ dan interval lompatan $b = 7-4 = 3$.

Mari kita adu nyali uji opsi-opsinya:
1. Wataknya melambing secara aritmetika stabil linear beda (+3). Validitas diakui! ✅
2. Uji konstruksi perumusan deret $U_n$: $U_n = a + (n-1)b = 4 + (n-1)3 = 4 + 3n - 3 = 3n + 1$. Seringkasan identitas $U_n$ bernyawa $3n+1$. Valid diakui! ✅
3. Menebak isi gerbong $15 \implies U_{15}$. Kita lemparkan variabel indeks masuk $\implies 3(15)+1 = 45+1 = 46$. Tepat menduduki nilai 46. Mengesankan valid. ✅
4. Kalkulasi akumulasi 10 gerbong ($n=10$) terekam pada fungsi $S_{10} = \frac{n}{2} (2a + (n-1)b) = \frac{10}{2} (2(4) + 9(3)) = 5(8 + 27) = 5(35) = 175$. Valid. ✅
5. Berdasarkan rumusan murni sumasi agregat barisan rata Aritmetika ($S_n = \frac{bn^2}{2} + (\ldots)$), polanya absolut tak pernah lari dari patron eksponensial deret kuadrat terhadap laju index $N$ ($n^2$). (Barisan konstan linear, sementara Deret penjumlahan/luasan bersimbiosis fungsi luasan Kuadrat vertikal kartesisnya). Terverifikasi sahih! ✅

Tiada cacat cacat logika sedikitpun dalam setiap derap langkah di kelima rincian, perpaduan kumpulannya bertransformasi sah mutlak membendera pilihan centang semua **1, 2, 3, 4, dan 5**.

---
**Navigasi:**
- [⬅️ Kembali ke Materi](../barisan-deret.md)
