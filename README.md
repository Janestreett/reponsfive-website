# reponsfive-website
# Kertas & Kayu — Responsive Website

Tugas 2: "Responsive Website" — X PPLG SMT 2

Website satu halaman untuk brand fiktif studio alat tulis buatan tangan "Kertas & Kayu". Satu file HTML mandiri (`kertas-kayu-responsive.html`), dibangun dengan **Flexbox** dan **media query** sesuai instruksi.

## Cara Menjalankan

1. Unduh file `kertas-kayu-responsive.html`.
2. Buka langsung di browser (klik dua kali, atau drag ke jendela browser).
3. Tidak butuh server — murni HTML/CSS/JS statis.
4. Untuk mengecek tampilan mobile: buka DevTools browser (F12) → mode responsif, atau perkecil lebar jendela browser.

## Fitur Sesuai Instruksi

| Instruksi | Implementasi |
|---|---|
| **Navbar** | Logo, 3 link navigasi, tombol CTA, disusun dengan `display:flex; justify-content:space-between`, berubah jadi menu hamburger di layar sempit |
| **3 Card Content** | Bagian "Produk" berisi 3 kartu (Buku Catatan Linen, Pena Kayu Jati, Set Kertas Pembungkus), disusun dengan `display:flex; flex-wrap:wrap` |
| **Responsive Mobile** | `@media (max-width: 860px)` dan `@media (max-width: 560px)` mengatur ulang navbar, hero, dan kartu agar nyaman dibaca di HP |
| **Media Query** | Dipakai di 2 breakpoint utama untuk navbar, hero, grid kartu, dan strip nilai |
| **Flexbox** | Dipakai di navbar, hero, grid 3 kartu, dan strip "Nilai Kami" — tidak menggunakan CSS Grid sama sekali |

## Struktur Halaman

- **Header** — navbar sticky dengan logo, link, CTA, dan toggle menu mobile
- **Hero** — headline, deskripsi singkat, dua tombol aksi, ilustrasi tumpukan buku catatan (CSS, dengan hover effect)
- **Produk** (`#produk`) — 3 card content produk andalan
- **Nilai Kami** (`#nilai`) — 4 poin nilai brand dalam baris flexbox
- **Footer** (`#kontak`) — logo, link cepat, email, copyright

## Palet & Tipografi

- **Warna dasar:** krem hangat `#f1ecdc`, panel `#e4dcc3`
- **Aksen:** hijau teal tua `#1f4f45` dan kuning ochre `#c08a2e`
- **Font display:** `Fraunces` (serif berkarakter, dipakai miring untuk penekanan)
- **Font body:** `IBM Plex Sans`
- **Font utilitas:** `IBM Plex Mono` (label, harga, angka)

## Aksesibilitas

- Mendukung `prefers-reduced-motion`
- `:focus-visible` untuk navigasi keyboard
- Kontras warna teks terhadap latar sudah diperhitungkan agar tetap terbaca

## Catatan

Nama brand dan produk bersifat fiktif, dibuat khusus untuk keperluan demo tugas.
