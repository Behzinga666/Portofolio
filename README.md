# Portofolio Pribadi - Rizqy Ramadhan

Website portofolio statis yang minimalis, clean, dan profesional. Didesain secara responsif untuk layar mobile, tablet, dan desktop tanpa memerlukan langkah *build* yang rumit (dapat langsung dibuka di browser atau di-deploy gratis ke GitHub Pages dan Vercel).

---

## 🚀 Fitur & Keunggulan
- **Minimalis & Modern**: Font Inter, palet warna terang dengan aksen biru kalem (*calm blue*).
- **Single Page Architecture**:
  - **Sticky Navbar**: Dilengkapi hamburger menu otomatis untuk mobile.
  - **Hero Section**: Foto profil bulat, sapaan hangat, status ketersediaan, serta tombol CTA.
  - **About Section**: Penjelasan singkat fokus keilmuan dan latar belakang di Universitas Pasundan.
  - **Skills Badges**: PHP/Laravel, Python, Supabase, Playwright (QA Automation), dan Network Troubleshooting.
  - **Project Cards**: Kartu portofolio dengan badge teknologi dan link ke repositori GitHub.
  - **Contact & Footer**: Tautan ke GitHub, LinkedIn, dan email dengan tahun otomatis.
- **Zero-Dependency Build**: Menggunakan CDN Tailwind CSS dan Lucide Icons, sehingga bisa langsung di-deploy tanpa Node.js.

---

## 🛠️ Cara Menjalankan Secara Lokal

1. Buka file `index.html` langsung di browser favorit Anda (Chrome, Edge, Firefox), **atau**
2. Gunakan ekstensi **Live Server** di VS Code:
   - Klik kanan pada `index.html`
   - Pilih **Open with Live Server**

---

## 🌐 Cara Deploy Gratis

### 1. GitHub Pages (Paling Mudah)
1. Buat repositori baru di GitHub (misal: `portofolio`).
2. Unggah file `index.html` dan `README.md` ke branch `main`.
3. Buka tab **Settings** di repositori GitHub Anda.
4. Pilih menu **Pages** di bilah kiri.
5. Pada bagian **Branch**, pilih `main` dan folder `/(root)`, lalu klik **Save**.
6. Dalam 1-2 menit, situs Anda akan aktif di `https://<username>.github.io/<repo-name>/`.

### 2. Vercel
1. Kunjungi [vercel.com](https://vercel.com) dan login dengan akun GitHub Anda.
2. Klik **Add New Project**, lalu pilih repositori portofolio Anda.
3. Karena ini adalah situs HTML murni, biarkan semua pengaturan default dan klik **Deploy**.
4. Website Anda langsung tayang dengan domain gratis `.vercel.app` dan sertifikat SSL/HTTPS aktif.

---

## ✏️ Cara Kustomisasi
- **Ganti Foto Profil**: Cari tag `<img>` di bagian `Hero Section` pada baris sekitar 124 dan ubah atribut `src` dengan path file foto Anda (misal `img/profil.jpg`).
- **Ganti Link Sosial**: Sesuaikan tautan `https://github.com`, `https://linkedin.com`, dan alamat email `mailto:rizqy.ramadhan@example.com` di bagian Hero dan Contact/Footer.
