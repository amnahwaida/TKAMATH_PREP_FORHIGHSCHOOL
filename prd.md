Berikut adalah **PRD.md** yang telah diperbarui sesuai dengan **Matriks Asesmen TKA Matematika SMA** yang Anda berikan. Dokumen ini dirancang khusus untuk proyek berbasis Markdown yang di-deploy ke GitHub.

Silakan salin konten di bawah ini ke dalam file `PRD.md` di repository GitHub Anda.

```markdown
# PRD: Rangkuman Materi Ujian TKA Matematika SMA (Based on Kisi-Kisi)

| Informasi Proyek | Detail |
| :--- | :--- |
| **Nama Proyek** | TKA Math Summary (GitHub Edition) |
| **Versi Dokumen** | 1.1.0 (Updated per Kisi-Kisi) |
| **Status** | Planning |
| **Framework** | Antigrafity (Markdown-Based) |
| **Target Deploy** | GitHub Pages / Repository |
| **Sumber Materi** | Matriks Asesmen TKA Matematika SMA (5 Elemen Utama) |

---

## 1. Pendahuluan

### 1.1 Latar Belakang
Berdasarkan matriks asesmen terbaru, materi TKA Matematika SMA mencakup 5 elemen utama dengan batasan kompetensi yang spesifik. Siswa membutuhkan rangkuman yang tidak hanya menjelaskan teori, tetapi juga menyesuaikan dengan **batasan soal** (contoh: maksimal 3 variabel pada sistem persamaan) agar belajar lebih efektif.

### 1.2 Tujuan Proyek
Membangun repositori GitHub statis yang berisi rangkuman materi lengkap sesuai 5 elemen asesmen, menggunakan format Markdown murni untuk kemudahan navigasi dan maintenance tanpa database.

### 1.3 Target Pengguna
- Siswa SMA peserta ujian TKA.
- Tutor/Guru yang membutuhkan panduan sesuai kisi-kisi resmi.

---

## 2. Persyaratan Fungsional (Functional Requirements)

### 2.1 Struktur Konten & Navigasi
- [ ] **Navigasi Markdown:** Semua link harus relatif (`[Link](./folder/file.md)`).
- [ ] **Struktur 5 Elemen:** Folder utama harus mencerminkan 5 Elemen Materi (Bilangan, Aljabar, Geometri, Trigonometri, Data).
- [ ] **Indeks Bab:** Setiap folder elemen wajib memiliki `index.md` sebagai daftar isi sub-bab.
- [ ] **Breadcrumbs:** Setiap halaman materi harus memiliki navigasi kembali ke Indeks Elemen dan Home.

### 2.2 Kepatuhan Terhadap Kisi-Kisi (Compliance)
- [ ] **Batasan Materi:** Setiap halaman materi harus mencantumkan bagian **"Batasan/Catatan"** sesuai matriks (Contoh: "Maksimum 3 variabel").
- [ ] **Cakupan Kompetensi:** Materi harus mencakup aspek Memahami, Mengaplikasikan, dan Bernalar (HOTS).
- [ ] **Contoh Soal:** Wajib menyertakan contoh soal yang tidak melanggar batasan kisi-kisi.

### 2.3 Fitur Teknis
- [ ] **Render Matematika:** Mendukung sintaks LaTeX (`$ ... $`) untuk rumus.
- [ ] **Responsif:** Tampilan readable di mobile via GitHub Pages.
- [ ] **Tanpa JavaScript Berat:** Mengandalkan fitur static site generator Antigrafity.

---

## 3. Struktur Folder & Sitemap

Struktur ini disusun berdasarkan 5 Elemen dalam Matriks Asesmen.

```text
/
├── README.md                 # Home: Overview & Link ke 5 Elemen
├── PRD.md                    # Dokumen ini
├── assets/                   # Gambar diagram/rumus
│   └── images/
├── content/                  # Root Materi
│   ├── 01-bilangan/
│   │   ├── index.md          # Daftar Isi Bilangan
│   │   └── bilangan-real.md  # Sub-elemen Bilangan Real
│   ├── 02-aljabar/
│   │   ├── index.md
│   │   ├── persamaan-linear.md
│   │   ├── fungsi.md
│   │   └── barisan-deret.md
│   ├── 03-geometri/
│   │   ├── index.md
│   │   ├── objek-geometri.md
│   │   ├── transformasi.md
│   │   └── pengukuran.md
│   ├── 04-trigonometri/
│   │   ├── index.md
│   │   └── perbandingan-trig.md
│   └── 05-data-peluang/
│       ├── index.md
│       ├── statistika.md
│       └── peluang.md
└── resources/
    └── kisi-kisi-reference.md # Salinan teks matriks asesmen
```

---

## 4. Detail Materi & Batasan (Berdasarkan Matriks)

Pengembang konten **WAJIB** mengikuti detail berikut saat menulis file Markdown:

### 4.1 Elemen 1: Bilangan
| File Markdown | Sub-Elemen | Batasan/Catatan Penting |
| :--- | :--- | :--- |
| `bilangan-real.md` | Jenis, sifat, operasi bilangan | Termasuk bilangan asli berpangkat bulat/pecahan. Sifat: Komutatif, Asosiatif, Distributif. |

### 4.2 Elemen 2: Aljabar
| File Markdown | Sub-Elemen | Batasan/Catatan Penting |
| :--- | :--- | :--- |
| `persamaan-linear.md` | Sistem Pers/Pertidaksamaan Linear | **Maksimum 3 variabel**. Termasuk Program Linear. |
| `fungsi.md` | Domain, Range, Invers, Komposisi | Representasi: Linear, Kuadrat, Rasional. Analitis & Grafis. |
| `barisan-deret.md` | Aritmetika & Geometri | Termasuk pertumbuhan, peluruhan, bunga tunggal & majemuk. |

### 4.3 Elemen 3: Geometri & Pengukuran
| File Markdown | Sub-Elemen | Batasan/Catatan Penting |
| :--- | :--- | :--- |
| `objek-geometri.md` | Sudut, Garis, Bidang, Bangun | Bangun datar (Segitiga, Segiempat, Lingkaran). Bangun ruang (Beraturan). Teorema Pythagoras. |
| `transformasi.md` | Translasi, Refleksi, Rotasi, Dilatasi | Termasuk komposisi transformasi dari titik. |
| `pengukuran.md` | Keliling, Luas, Volume, Jarak | Jarak antar objek geometri (Titik ke Titik, Titik ke Garis, dll). |

### 4.4 Elemen 4: Trigonometri
| File Markdown | Sub-Elemen | Batasan/Catatan Penting |
| :--- | :--- | :--- |
| `perbandingan-trig.md` | Sin, Cos, Tan, Cot, Sec, Cosec | Perbandingan trigonometri dasar. |

### 4.5 Elemen 5: Data dan Peluang
| File Markdown | Sub-Elemen | Batasan/Catatan Penting |
| :--- | :--- | :--- |
| `statistika.md` | Penyajian Data, Ukuran Pemusatan | Diagram (Batang, Garis, Lingkaran). Data Tunggal & Kelompok. |
| `peluang.md` | Aturan Peluang | (Melengkapi bagian "Aturan..." pada matriks). |

---

## 5. Template Penulisan Materi (Markdown Template)

Setiap file materi (contoh: `persamaan-linear.md`) harus mengikuti format ini agar konsisten:

```markdown
# Judul Sub Materi (Contoh: Sistem Persamaan Linear)

> **Elemen:** [Aljabar](../index.md) | **Kembali ke Home:** [../../README.md](../../README.md)

## 1. Kompetensi
Memahami, mengaplikasikan, dan bernalar untuk menyelesaikan permasalahan sistem persamaan.

## 2. Batasan Materi (PENTING)
> ⚠️ **Catatan Ujian:** Maksimum banyaknya variabel yang digunakan adalah **tiga variabel**. Soal tidak akan melebihi batas ini.

## 3. Ringkasan Materi
Penjelasan konsep...

### Rumus
$$ ax + by + cz = d $$

## 4. Contoh Soal & Pembahasan
**Soal:**
Diketahui sistem persamaan... (Pastikan variabel ≤ 3)

**Pembahasan:**
Langkah penyelesaian...

---
**Navigasi:**
- [Sebelumnya](file-sebelumnya.md)
- [Selanjutnya](file-selanjutnya.md)
```

---

## 6. Strategi Deployment (GitHub & Antigrafity)

1.  **Repository Setup:**
    - Buat repo publik `tka-math-summary`.
    - Upload file `README.md`, `PRD.md`, dan folder `content`.
2.  **Konfigurasi Antigrafity:**
    - Pastikan tool membaca folder `content` sebagai root dokumen.
    - Generate site statis.
3.  **GitHub Pages:**
    - Settings > Pages > Source: `Deploy from a branch`.
    - Pilih branch `main` dan folder root (atau `/docs` jika output Antigrafity diarahkan ke sana).
4.  **Validasi Link:**
    - Cek semua link navigasi antar folder (`../`) apakah berfungsi setelah di-deploy.
    - Pastikan gambar di `assets/` tampil dengan benar.

---

## 7. Roadmap Pengembangan

- [ ] **Minggu 1:** Setup Struktur Folder & README Utama.
- [ ] **Minggu 2:** Penulisan Elemen 1 (Bilangan) & Elemen 2 (Aljabar).
- [ ] **Minggu 3:** Penulisan Elemen 3 (Geometri) & Elemen 4 (Trigonometri).
- [ ] **Minggu 4:** Penulisan Elemen 5 (Data) & Review Batasan Materi.
- [ ] **Minggu 5:** Testing Navigasi & Deploy GitHub Pages.

---

## 8. Catatan Khusus Developer

1.  **Konsistensi Batasan:** Jangan membuat contoh soal yang melanggar batasan kisi-kisi (Misal: Jangan buat soal Sistem Persamaan 4 variabel).
2.  **Link Relatif:** Karena deploy ke GitHub Pages, pastikan link markdown relatif terhadap posisi file, bukan absolut dari root domain.
3.  **Matematika:** Gunakan `$` untuk inline math dan `$$` untuk block math. Pastikan Antigrafity mendukung render LaTeX. Jika tidak, gunakan gambar dari folder `assets`.
4.  **Versi Kisi-Kisi:** Jika ada update kisi-kisi, update file `resources/kisi-kisi-reference.md` dan sesuaikan PRD ini.

```