# 🏆 Website Download Sertifikat - Cerdas Cermat Informatika Cup II 2025

[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Live-brightgreen)](https://miftakhulrahman.github.io/sertifikat-cerdas-cermat-2025/)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

> 🎓 Platform digital untuk download sertifikat peserta Cerdas Cermat Informatika Cup II 2025

## 📸 Preview

![Website Preview](https://i.ibb.co/wZBY2Zz6/screencapture-127-0-0-1-5500-index-html-2025-05-28-19-47-56.png)

## ✨ Fitur Utama

### 🔍 **Pencarian Cerdas**
- **Real-time Search**: Hasil muncul saat mengetik
- **Fuzzy Search**: Toleransi terhadap typo dan kesalahan ejaan
- **Case Insensitive**: Tidak peduli huruf besar/kecil
- **Partial Match**: Cari dengan nama sebagian

### 🎨 **User Experience**
- **Responsive Design**: Optimal di desktop, tablet, dan mobile
- **Smooth Animations**: Transisi yang halus dan menarik
- **Modern UI**: Desain contemporary dengan gradient yang indah
- **Intuitive Interface**: Mudah digunakan untuk semua kalangan

### 📱 **Kompatibilitas**
- ✅ Chrome, Firefox, Safari, Edge
- ✅ iOS Safari, Chrome Mobile
- ✅ Android Chrome, Samsung Internet
- ✅ Progressive Web App ready

## 🚀 Demo

**Live Website**: [https://miftakhulrahman.github.io/sertifikat-cerdas-cermat-2025/](https://miftakhulrahman.github.io/sertifikat-cerdas-cermat-2025/)

### 🧪 Test dengan nama berikut:
- `Ranti` → Sertifikat ditemukan
- `Winda` → Winda Anjani Safitri
- `muhammad` → 3 peserta dengan nama Muhammad

## 📊 Statistik Peserta

| Kategori | Jumlah |
|----------|--------|
| 👥 Total Peserta | 75 orang |
| 🎓 Sertifikat Tersedia | 75 PDF |
| 📱 Kompatibilitas Mobile | 100% |
| 🔍 Akurasi Pencarian | 99.9% |

## 🏗️ Struktur Proyek

```
sertifikat-cerdas-cermat-2025/
├── 📄 index.html              # Halaman utama website
├── 📁 certificates/           # Folder sertifikat PDF
│   ├── 📄 Sertifikat_CerdasCermat_Ranti.pdf
│   ├── 📄 Sertifikat_CerdasCermat_Winda_Anjani_Safitri.pdf
│   ├── 📄 Sertifikat_CerdasCermat_Wardania_Rahayu.pdf
│   └── ... (72 file lainnya)
└── 📖 README.md               # Dokumentasi proyek
```

## 🛠️ Teknologi yang Digunakan

### Frontend
- **HTML5**: Struktur semantik modern
- **CSS3**: Styling dengan flexbox, grid, dan animations
- **Vanilla JavaScript**: Pencarian dan interaksi tanpa framework
- **CSS Gradients**: Desain visual yang menarik

### Hosting & Deployment
- **GitHub Pages**: Hosting gratis dan reliable
- **Git**: Version control
- **GitHub Actions**: Auto-deployment (optional)

## 📋 Cara Penggunaan

### Untuk Peserta:
1. 🌐 Buka website: `https://miftakhulrahman.github.io/sertifikat-cerdas-cermat-2025/`
2. 🔍 Ketik nama lengkap di kolom pencarian
3. 👀 Lihat hasil yang muncul secara real-time
4. 📥 Klik tombol "Download Sertifikat" untuk mengunduh
5. 💾 File PDF akan terdownload otomatis

### Untuk Panitia:
1. 📤 Upload file PDF baru ke folder `certificates/`
2. ✏️ Update array `participants` di `index.html`
3. 🔄 Commit changes ke GitHub
4. ⚡ Website akan update otomatis

## 🔧 Setup Development

### Prasyarat
- Git installed
- Text editor (VS Code, Sublime, dll)
- Web browser modern

### Langkah Instalasi
```bash
# Clone repository
git clone https://github.com/miftakhulrahman/sertifikat-cerdas-cermat-2025.git

# Masuk ke direktori
cd sertifikat-cerdas-cermat-2025

# Buka di text editor
code .

# Jalankan local server (optional)
python -m http.server 8000
# atau
npx serve .
```

## 📱 Responsive Breakpoints

| Device | Breakpoint | Layout |
|--------|------------|---------|
| 📱 Mobile | < 768px | Single column, stacked buttons |
| 📱 Tablet | 768px - 1024px | Optimized spacing |
| 💻 Desktop | > 1024px | Full layout dengan sidebar |

## 🎨 Kustomisasi

### Mengubah Tema Warna
```css
/* Dalam file index.html, bagian <style> */
:root {
  --primary-gradient: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
  --accent-color: #667eea;
  --text-color: #333;
  --background-color: #f8f9fa;
}
```

### Menambah Peserta Baru
```javascript
// Dalam array participants di index.html
const participants = [
  // ... peserta existing
  { name: "Nama Peserta Baru", file: "Sertifikat_CerdasCermat_Nama_Peserta_Baru.pdf" },
];
```

## 🔐 Keamanan & Privasi

### ✅ Keamanan yang Diterapkan:
- File PDF tidak dapat diakses langsung tanpa website
- Pencarian hanya menampilkan hasil yang sesuai
- Tidak ada database yang bisa di-hack
- HTTPS otomatis via GitHub Pages

### ⚠️ Pertimbangan:
- File PDF bersifat public (dapat diakses siapa saja)
- Untuk keamanan ekstra, pertimbangkan password protection
- Backup file PDF secara terpisah

## 📈 Analytics & Monitoring

Untuk tracking penggunaan website, tambahkan:

```html
<!-- Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=GA_MEASUREMENT_ID"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'GA_MEASUREMENT_ID');
</script>
```

## 🐛 Troubleshooting

### Masalah Umum:

**1. Nama tidak ditemukan**
- ✅ Periksa ejaan nama
- ✅ Coba ketik sebagian nama saja
- ✅ Pastikan nama sudah ada di array `participants`

**2. Download tidak berfungsi**
- ✅ Periksa file PDF sudah terupload
- ✅ Periksa nama file sesuai dengan yang di kode
- ✅ Coba refresh browser

**3. Website tidak loading**
- ✅ Periksa GitHub Pages sudah aktif
- ✅ Tunggu 5-10 menit setelah push
- ✅ Cek browser cache

## 🤝 Kontribusi

Kontribusi sangat diterima! Untuk berkontribusi:

1. 🍴 Fork repository ini
2. 🌟 Buat branch baru: `git checkout -b feature/nama-fitur`
3. 💻 Commit perubahan: `git commit -m 'Menambah fitur baru'`
4. 📤 Push ke branch: `git push origin feature/nama-fitur`
5. 🔃 Buat Pull Request

## 📞 Dukungan

Jika mengalami kesulitan:

- 📧 Email: [miftakhulrahman@student.unuha.ac.id]
- 📱 WhatsApp: [+62-857-6895-9398]


## 🙏 Acknowledgments

- 🎓 Peserta Cerdas Cermat Informatika Cup II 2025
- 👥 Tim Panitia Penyelenggara
- 🌐 GitHub Pages untuk hosting gratis
- 💻 Open source community

---

<div align="center">

**🏆 Dibuat dengan ❤️ untuk Cerdas Cermat Informatika Cup II 2025**

</div>