# Latihan Soal Set 3: Peluang

> **Elemen:** [Data & Peluang](../index.md) | **Materi:** [Peluang](../peluang.md) | **Set 1:** [Latihan 1](peluang.md) | **Set 2:** [Latihan 2](peluang-2.md) | **Kembali ke Home:** [🏠 README](../../../README.md)

---

## Soal 1: Pilihan Ganda (PG)
Rombongan serangkai kantong merah kusam menyimpan deposit bola bola bergradasi rupa sebanyak $4$ buah berwarna kelereng Merah, ditambahkan cadangan $5$ butir bewarna Kuning dan diramaikan himpunan pendamping sebundar $3$ peluru bola Hijau bersanding melereng tertutup genap bercampur merata di kegelapan dalam adukannya. Diinisiasi dua kali beruntun pencabutan random acak (bola perdana yang terambil disisihkan *tanpa pengembalian balik* perputaran ke sarangnya). Menakar persentase merengkuh ambang kejadian terampasnya bola kuning di kocokan perdana merapat sekaligus ditemani bola hijau membalut perolehan di seret kocokan putaran cabutan keduanya, berapakah taksir peluang majemuk berkesinambungan bersyaratnya mengeksekusi misi mendarat sempurna tersebut?

A. $\frac{5}{44}$  
B. $\frac{1}{12}$  
C. $\frac{5}{144}$  
D. $\frac{15}{132}$  
E. $\frac{1}{8}$  

**Pembahasan:**
Total kerumunan benda sumbu bola $S_{awal} = 4M + 5K + 3H = 12$ bongkah.

Aksi Perdana (Cabut Bola Kuning):
Ketersediaan bola kuning sasaran berjejaring $5$ buah bidikan tersimpan mutlak dari kolam keseluruhan membludak $12$ massa ruang peluru.
Peluang Kuning $\implies P(K) = \frac{5}{12}$.

Aksi Mengiringi Susulan (Cabut Hijau TANPA restorasi restitusi dikembalikan lagi bolanya):
Sisa total kerumunan bola berkurang menyusut tinggal merana mendiami $11$ buah.
Cadangan bola beridentitas sasaran hijau di dalam perut karung mutlak berbekal stagnan stabil belum tersentuh terjarah satupun berjumlah $3$ sasaran peluru.
Peluang Hijau syarat tak genap (Dependen) $\implies P(H|K) = \frac{3}{11}$.

Probabilitas Majemuk runtutan saling bebas bersyarat:
$$ P(\text{Total}) = P(K) \times P(H|K) $$
$$ P(\text{Total}) = \frac{5}{12} \times \frac{3}{11} $$
Sederhanakan pemangkasan (coret fraksi bersilang 3 dan 12 bertumpu merapat membuahkan 4):
$$ P(\text{Total}) = \frac{5}{4 \times 11} = \frac{5}{44} $$

Ketelitian tingkat tebakan beralasan presisi memantul absolut terperinci di Opsi ranah **A**.

---

## Soal 2: Pilihan Ganda Kompleks Kategori (Benar/Salah)
Distribusi probabilitas merengkuh kaidah permutasi tak terkecuali membongkar tatanan serakan anagram. Jelajahi asersi mengenai formulan Kombinatorik pencacah perulangan di bawah, tegaskan Benar / Salah setiap pilar komputasinya melangkah di tatanan rasionalisasi empiris logis tersebut!

- A. Menumbangkan variasi kombinasi tatanan abjad sandi penyusun menyusun kata "STATISTIKA" murni tersuport disusupi formula $\frac{10!}{2! \cdot 2! \cdot 1! \cdot 1!}$ karena totalnya menyapu $10$ abjad rupa namun S berjumlah dobel 2, dan T dobel 2.
- B. Kombinatorika serampangan mengacaukan adegan 5 individu berebut 3 bangku kursi VIP bernomer silsilah sakral berstruktur tahta bertingkat mutlak harusnya direngkuh metode Kombinasi murni bukan campur tangan Permutasi.
- C. Perhitungan koefisien ekspansi Binomial Pascal dalam mengudarakan rasio $(x + y)^n$ hakikat murninya dikemudikan kompartemen gerbong pengali bermesin Kombinasi tak terhitung $C(n, k)$ pada penjabaran kompartemen polimialnya merambat ke ujung persamaannya.

**Pembahasan:**
**A. Anagram memecah kata STATISTIKA**
Mari audit cacah hurufnya:
Total gerbong $n = 10$.
Rincian rupa ganda bersarang: S $\implies$ 2, T $\implies$ 3, A $\implies$ 2, I $\implies$ 2. (Huruf T bukan cuma $2$, tapi seratus persen memborong 3 biji memecah).
Formulasi di naskah mendiskon mereduksi sepihak sumbu pemecah T menjadi asumsional tebakan cuma dobel 2. Formula murni dan sejati pembagi aslinya (denominator) menuntut kehadiran persinggahan angka takdir sakral $(2! \cdot 3! \cdot 2! \cdot 2!)$.
Kesimpulan: **Salah** ❌

**B. Pengisian slot bangku bernomer tahta silsilah VIP**
Silsilah bangku sakral bertingkat hirarki VIP ber-nomor secara gamblang mempertegas sentimen tatanan formasi (Posisi mendikte martabat dan keabsahan varian). Urutan Budi di VIP 1 dan Andi di VIP 2 mutlak tidak dapat disetarakan menukar kursi Andi 1 - Budi 2. Di sanalah kemerdekaan Permutasi menabuhkan genderang kejayaannya. Murni mengklaim bahwa ini diselesaikan Kombinasi adalah penipuan melanggar sumpah kodrati matematika tatanan hirarkis.
Kesimpulan: **Salah** ❌

**C. Kombinasi di Balik Tirai Koefisien Segitiga Binomial Newton Pascal**
Rumusan binomial memercik ekspansi Teorema $(x+y)^n = \sum_{k=0}^{n} C(n, k) x^{n-k} y^k$. Tiap koefisien pendampingnya dibangkitkan dari serabut pembacaan nilai tabel rahasia jalinan Kombinasional murni mencaplok $nCr$. Verifiksi faktual tersohor mengangkasa mendarat menyokong peradaban tak tersanggahkan.
Kesimpulan: **Benar** ✔️

---

## Soal 3: Pilihan Ganda Kompleks MCMA (Lebih dari 1 Jawaban Benar)
Penyelesaian pertarungan saling bebas melempar tiga sekeping perak uang logam beralamat berganda (Angka-Gambar) dilakukan berturut tergesa melambung seiring irama sentak serempak tumpang tindih. Pilihlah dari gerombolan seruan pernyataan di bawah yang probabilitas nilainya menapak mengkristalkan kepastian setara murni merengkuh angka teoretis absolut menohok tatanan fraksi seragam senilai tepat persis $\frac{3}{8}$ bulat-bulat logis eksak membidik target akurat absolut! (Tebak perlawanan yang mendiami opsinya sah lebih dari 1 validitas).

- [ ] Memunculkan taksiran probabilitas peluang mencuat meraup tepat setajam murni absolut eksak dua keping rupa Angka bersanding dalam genggaman dan satu berwajah Gambar sisanya mendominasinya.
- [ ] Tersuport luang kemungkinan kejadian mendulang presisi mendera mengelupas dua rupa Gambar berdampingan bersaing mesra bareng sang pendamping sebotak Angka sepotong sisanya memahat sejarah kombinasinya.
- [ ] Mengharapkan perolehan raupan muncul melambung setingkat serendahnya (sekurang-kurangnya) rahasia menduduki tampuk dua keping murni bermuka rupa keperakan Angka mengambang menduduki perahu takdir koin koinnya.
- [ ] Kalkulasi kejadian majemuk menumbangkan kemunculan ketiga keping logal murni absolut teridentifikasi kembar kembar tak terbantahkan seutas berwajah merangkai identikal Gambar seluruh-seluruhnya tanpa terkecuali seragam melayang.
- [ ] Permintaan peluang merekonstruksi mumpuni merebut kemunculan presisi urutan rupa mutlak di logam 1 Angka disusul merentang logam kedua Angka, memadukannya tergesa Gambar pada penutupan logam terakhir (Konjungsi urutan Absolut mengawal GGA batal melainkan mensyaratkannya A-A-G berurut kaku spesifik mematung mati).

**Pembahasan:**
Total ruang kejadian tiga pilar keping logam saling mandiri melempar $= 2 \times 2 \times 2 = 8$ sumbu tatanan kombinasi rentang. 
(AAA, AAG, AGA, GAA, AGG, GAG, GGA, GGG).

Mari audit pernyataan menembus validitas ke setara dengan angka target gawang $=\frac{3}{8}$:
1. Muncul 2 Angka, 1 Gambar sembarang acak terserah lokasinya. Kombinasi yang mendukung murni tumpuan irisan: AAG, AGA, GAA. Ada $3$ rupa pelik kejadian sah terekam. Peluang menukik senilai mutlak $\frac{3}{8}$. Terciumbenar sahih tuntas! ✅
2. Muncul 2 Gambar, 1 Angka membentang campur ruah. Formasi rentangan sekutunya menduduki kombinasi: AGG, GAG, GGA. Sama-sama terendus berjumlah tegap sebanyak $3$ elemen. Otomatis probabilitas menembus fraksional sepadan di fraksi murni merapat di nilai $\frac{3}{8}$. Mendapat stempel Sah!! ✅
3. Sekurang-kurangnya terbit dua (2) Angka (artinya boleh merestui memuat tepat mutlak 2 Angka, dan diakomodasi bebas merdeka menambah merengkuh jatah utuh sekaligus 3 Angka borongan). Formasinya: AAG, AGA, GAA + (Bonus ekstra AAA) $\implies$ berjumlah 4 serpihan unsur irisan ganda. Peluang ini mendarat mengamankan kedudukan meledak ke $\frac{4}{8} = \frac{1}{2}$. Meleset tumpuan bidik dari gerbang target pencarian $3/8$ asalnya. Batal merajai sumbu salah mutlak. ❌
4. Muncul tiga keping seutuhnya merangkap menyandang nama kebangsawanan monolitik identikal Gambar membondong serempak. Susunan kerajaannya cuman absolut 1 penguasa tunggal memonopoli semesta (GGG). Proyeksi melahirkan perintisan peluang kerdil sepihak di dasar nilai jurang membatik seharga murni $\frac{1}{8}$. Meleset tenggelam merana menjauhi 3/8. Batal disambar salah! ❌
5. Urutan tertebus sakral dan tegap absolut tak terbantahkan terikrar menuntut tatanan absolut kaku memagut rentang mutlak $\implies$ Koin I $(Angka) \to$ Koin II $(Angka) \to$ Koin III $(Gambar)$. Tak boleh tukar persinggahan (Murni urutan pakem taktis AAG saja seorang tiada keramaian komplotan varian cadangannya). Kejadian urutan mati mutlak ini bertitik cuma 1. Probabilitas merajut menelusup ke titik jurang peluang sunyi senilai takluk sebatas $\frac{1}{8}$. Bukanlah $\frac{3}{8}$ yang melahirkan sorak sorai kemeriahan. Batal bersalah tersesat logika kemiringan. ❌

Kemenangan pembuktian yang sukses mendekonstruksi pilar tebakan melilit merajut merengkuh tahta singgasana persis nilai sasaran taksiran peluang takluk murni eksak bernilai perimbangan $= 3/8$ absolut bulat bulat mengerucut pada penunjukkan rincian elemen yang termanifestasi merengkuh opsi valid bernomor poin sentral **1 dan 2**.

---
**Navigasi:**
- [⬅️ Kembali ke Materi](../peluang.md)
