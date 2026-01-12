# AmbatuOps Technology (AmbaTech)
"Kecerdasan Terjamin. Operasi Tepat Guna."

## Daftar Isi
- [Tentang Proyek](#tentang-proyek)
- [Visi & Misi](#visi--misi)
- [Fitur Utama](#fitur-utama)
    - [Visual & Interaksi](#visual--interaksi)
    - [Fungsionalitas](#fungsionalitas)
- [Teknologi](#teknologi)
- [Struktur Tim](#struktur-tim)
- [Alur Deployment (CI/CD)](#alur-deployment-cicd)
- [Instalasi & Penggunaan](#instalasi--penggunaan)
- [Lisensi](#lisensi)

---

## Tentang Proyek
AmbatuOps Technology (AmbaTech) adalah profil perusahaan teknologi yang berfokus pada fusi Artificial Intelligence (AI) dan Cybersecurity tingkat tinggi. Website ini dirancang dengan antarmuka futuristik, interaktif, dan responsif untuk merepresentasikan visi masa depan yang cerdas.

Website berfungsi sebagai gerbang utama bagi klien untuk memahami layanan AmbaTech — mulai dari solusi AI dan audit keamanan siber hingga ekspansi SaaS di Asia Tenggara.

---

## Visi & Misi
**Visi**
Menjadi pemimpin keamanan untuk SME & ekspansi pasar SaaS.

**Misi**
- Menghadirkan inovasi solusi.
- Meningkatkan keunggulan operasi.
- Mengembangkan sumber daya manusia (SDM).

---

## Fitur Utama

### Visual & Interaksi
- Dual Theme System: Dark (default) dan Light dengan transisi halus.
- Interactive Particles: Latar belakang kanvas partikel bereaksi terhadap gerakan mouse.
- Text Scramble Effect: Efek dekripsi teks pada bagian hero.
- Glassmorphism UI: Kartu transparan dengan efek blur dan tilt 3D saat hover.
- Simulasi Terminal: Elemen visual menyerupai kode keamanan yang berjalan.

### Fungsionalitas
- Preloader sinematik dengan log sistem tiruan.
- Formulir kontak dengan validasi dan notifikasi sukses.
- Marquee Tech Stack menampilkan teknologi yang digunakan.

---

## Teknologi
**Frontend**
- HTML5, CSS3 (Custom Properties), Bootstrap 5.3
- JavaScript (ES6+) untuk logic dan animasi
- Libraries: AOS, Vanilla-Tilt.js, FontAwesome

**DevOps & Infrastruktur**
- Git & GitHub, GitHub Actions (CI/CD)
- VPS (Ubuntu) untuk production
- GitHub Pages untuk development preview

---

## Struktur Tim

| Foto | Nama | Posisi | Peran Utama |
|---:|---|---|---|
| ![Rois](images/ro.jpeg){width="40"} | Rois Azzam Shiddiq | CEO | Strategi & Visi |
| ![Kamil](images/ka.jpeg){width="40"} | Muhammad Kamil | CTO | Arsitektur Teknologi |
| ![Raka](images/rk.jpeg){width="40"} | Raka Dwi Randika | COO | Operasional Harian |
| ![Bilal](images/bi.jpg){width="40"} | Muhamad Bilal Fatiha | CPO | Pengembangan Produk |
| ![Zaidaan](images/za.jpeg){width="40"} | Zaidaan Salman | Head of BD | Kemitraan Strategis |
| ![Hisyam](images/sy.jfif){width="40"} | M. Hisyam Alfaris | Head of Cyber | Keamanan Siber |

> Pastikan semua file gambar tersedia di folder `images/`.

---

## Alur Deployment (CI/CD)
1. Development (branch `dev`)
     - Target: GitHub Pages
     - Trigger: Push ke branch `dev`
     - Fungsi: Preview fitur baru.

2. Production (branch `main`)
     - Target: VPS (Production)
     - Trigger: Push ke branch `main`
     - Metode: SCP atau mekanisme deployment aman lainnya.

---

## Instalasi & Penggunaan

Clone repository:
```bash
git clone https://github.com/username/ambatutech-app.git
cd ambatutech-app
```

Struktur minimal:
```
/
├── index.html
├── images/
│   ├── logo.png
│   ├── ro.jpeg
│   └── ... (foto tim lainnya)
└── .github/workflows/deploy.yml
```

Menjalankan lokal:
- Buka `index.html` di browser, atau gunakan Live Server (VS Code) untuk preview.

---

## Lisensi
© 2026 AmbatuOps Technology. All Rights Reserved.
