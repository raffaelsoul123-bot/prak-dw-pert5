# LAPORAN PRAKTIKUM DESAIN ANTARMUKA

## Identitas

| Data           | Keterangan                      |
| -------------- | ------------------------------- |
| Nama           | Mukhamad Akbar Raffael Ridho    |
| NPM            | 4525210085                      |
| Kelas          | A                               |
| Program Studi  | Teknik Informatika              |
| Mata Kuliah    | Prak. Desain Web                |
| Tema Proyek    | Portal Berita (DWNews)      |

---

## Deskripsi Proyek

Proyek ini merupakan implementasi antarmuka web responsif bertema **Portal Berita (DWNews)**. Desain ini dibuat untuk memenuhi kebutuhan penyampaian informasi yang cepat, rapi, dan mudah dibaca baik pada perangkat *desktop* maupun *mobile*.

Proyek dibangun menggunakan dua file utama:
- `index.html` — Mengatur struktur elemen, tata letak berita utama, serta bagian berita terbaru (*sidebar*).
- `style.css` — Mengatur tata letak visual, warna, serta responsivitas menggunakan *CSS Grid* dan *Flexbox*.

---

## Solusi & Alur Pengerjaan

1. **Perancangan Struktur HTML (`index.html`):**
   - Pembuatan *header* dan navigasi yang bersih.
   - Pembagian area konten menjadi dua bagian utama (*main layout*): area *headline* berita dan area *sidebar* untuk berita terbaru.
   - Penggunaan struktur semantik HTML seperti `<header>`, `<main>`, `<section>`, `<aside>`, dan `<footer>`.

2. **Styling & Responsivitas (`style.css`):**
   - Menggunakan *CSS Grid* (`2fr 1fr`) untuk tampilan *desktop* agar proporsi berita utama dan bilah samping seimbang.
   - Menerapkan `@media (max-width: 768px)` untuk mengubah tata letak menjadi satu kolom vertikal ketika diakses melalui perangkat seluler (*mobile view*).
   - Penyesuaian skema warna netral (*slate/navy*) dengan aksen biru muda (*sky blue*) untuk kenyamanan membaca.

---

## Bukti Pengerjaan

### File `index.html` & `style.css`
- **Source Code:** Tersedia pada file `index.html` dan `style.css` di repository ini.

## Kesimpulan

Proyek mandiri pembuatan antarmuka **Portal Berita (DWNews)** telah berhasil diselesaikan sesuai ketentuan. Penggunaan *CSS Grid* dan *Flexbox* terbukti efektif dalam membangun tata letak halaman berita yang responsif, terstruktur, serta memiliki tingkat keterbacaan yang tinggi pada berbagai ukuran layar.
