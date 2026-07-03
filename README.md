# Hanya Teman - Interactive Confession Web App 💌

Sebuah website *single-page* interaktif yang cantik dan emosional, dibuat khusus untuk mengungkapkan perasaan kepada teman terdekat. Website ini menggunakan desain *glassmorphism*, animasi CSS yang mulus, efek *typewriter*, *real-time countdown*, dan efek *confetti* tanpa menggunakan framework tambahan (murni HTML, CSS, dan Vanilla JavaScript).

---

## 📸 Demo Project

![Demo Preview](demo.gif)

🔗 **Live Demo**: [https://dzareldeveloper.github.io/Hanya-Teman/](https://dzareldeveloper.github.io/Hanya-Teman/)

---

## 📂 Struktur Project

Project ini dibuat seringkas mungkin agar mudah dimodifikasi:

```text
/
├── index.html   # Struktur utama halaman web & konten teks
├── style.css    # Desain tampilan, warna, layout, dan animasi CSS
├── script.js    # Logika transisi, efek ketikan, musik, dan confetti
└── music.mp3    # (Tambahkan file ini) Lagu latar yang diputar di dalam web
```

---

## 🛠️ Cara Kustomisasi / Modifikasi

Website ini didesain agar sangat mudah disesuaikan dengan ceritamu. Berikut adalah panduan mengubah konten di dalamnya:

### 1. Cara Ganti Teks (HTML & JS)
- Buka file **`index.html`** menggunakan *code editor* (seperti VS Code atau Notepad).
- Cari teks yang ingin kamu ubah, misalnya pesan pengakuan, tulisan di tombol, atau judul.
- Untuk teks efek **mesin tik (typewriter)**, kamu harus membukanya di file **`script.js`**. 
- Cari bagian `const typeWriterLines = [...]` (sekitar baris 118) lalu ubah pesan di dalam tanda kutip `" "`.

### 2. Cara Ganti Gambar / Foto
- Buka file **`index.html`**.
- Cari tag `<img src="...">`. Saat ini gambar menggunakan link dari Pinterest.
- Ganti link di dalam atribut `src="..."` dengan link gambarmu sendiri.
- *Tips: Kamu juga bisa mendownload foto, menaruhnya di dalam folder yang sama, lalu ubah src menjadi `src="namagambar.jpg"`.*

### 3. Cara Ganti Tanggal Jadian / Awal Kenal
- Buka file **`script.js`**.
- Cari baris kode ini: 
  `const startDate = new Date('2025-09-16T00:00:00');`
- Ganti `2025-09-16` menjadi tanggal awal pertemuan kalian (Format: `Tahun-Bulan-Tanggal`). Waktu otomatis akan menghitung selisih dari tanggal tersebut hingga hari ini secara *real-time*.

### 4. Cara Ganti Nomor WhatsApp
- Buka file **`script.js`**.
- Gulir ke paling bawah, cari baris kode ini:
  `const chatLink = "https://wa.me/6281234567890";`
- Ganti angka `6281234567890` dengan nomor WhatsApp kamu. Pastikan menggunakan kode negara `62` sebagai pengganti `0`.

### 5. Cara Ganti Lagu / Background Music
- Siapkan file lagu favoritmu berformat `.mp3`.
- Ubah nama file lagu tersebut menjadi **`music.mp3`**.
- Pindahkan file **`music.mp3`** ke dalam folder yang sama dengan file `index.html`.
- Lagu akan otomatis berputar berulang (*loop*) pada saat masuk ke halaman pengungkapan perasaan.

---

## 🚀 Cara Hosting (Bagikan ke Orang Lain)

Agar targetmu bisa membuka website ini dari HP-nya, kamu perlu mengunggahnya ke layanan Hosting gratis. Ada 2 cara paling mudah:

### Cara 1: Menggunakan Netlify (Paling Mudah)
1. Buka [Netlify Drop](https://app.netlify.com/drop).
2. Login atau buat akun Netlify.
3. Siapkan folder project ini (pastikan sudah berisi `index.html`, `style.css`, `script.js`, dan `music.mp3`).
4. Tarik (*Drag & Drop*) seluruh folder tersebut ke area lingkaran di halaman Netlify Drop.
5. Selesai! Netlify akan memberimu link publik yang bisa langsung kamu bagikan.

### Cara 2: Menggunakan GitHub Pages
1. Buat akun di [GitHub](https://github.com/).
2. Buat repository baru, lalu *upload* semua file project ini ke dalam repository tersebut.
3. Setelah ter-upload, masuk ke menu **Settings** di repository kamu.
4. Pilih menu **Pages** di sebelah kiri.
5. Pada bagian **Source**, pilih branch `main` atau `master`, lalu klik **Save**.
6. Tunggu beberapa menit, GitHub akan menampilkan link website-mu di atas (contoh: `https://username.github.io/Hanya-Teman/`).

---

**Made with ❤️ by DzarelDeveloper**
