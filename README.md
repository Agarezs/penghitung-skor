# ⚡ Scoreboard Pro - Liquid Glass Edition

Aplikasi penghitung skor modern dengan desain glassmorphism yang elegan dan sistem audio canggih untuk berbagai jenis pertandingan atau kompetisi.

## 🌟 **Fitur Utama**

### 🎨 **Desain Premium**
- **Glassmorphism UI** dengan efek blur dan transparansi modern
- **Animated gradient background** yang bergerak dinamis
- **Floating particles** untuk efek visual yang memukau
- **Responsive design** - sempurna di desktop, tablet, dan mobile
- **Smooth animations** dan transisi yang halus

### 🎤 **Sistem Audio Canggih**
- **Voice selector** dengan kategorisasi suara:
  - 🇮🇩 Indonesian Voices
  - 🤖 Natural/Premium Voices  
  - 🇺🇸 English Voices
  - 🌍 Other Languages
- **Test voice function** untuk preview suara
- **Sound effects** yang berbeda untuk setiap aksi
- **Audio toggle** on/off

### 🎮 **Kontrol Lengkap**
- **Touch/Click controls** - tap area tim untuk +1 skor
- **Dedicated buttons** untuk mengurangi skor (-1)
- **Keyboard shortcuts** untuk kontrol cepat
- **Reset function** untuk mengulang pertandingan
- **New game** untuk setup baru

## ⌨️ **Keyboard Shortcuts**

| Tombol | Fungsi |
|--------|--------|
| `A` | +1 untuk Team A |
| `B` | +1 untuk Team B |
| `Q` | -1 untuk Team A |
| `W` | -1 untuk Team B |
| `R` | Reset skor ke 0-0 |
| `M` | Toggle audio on/off |

## 🚀 **Cara Penggunaan**

### 1. **Setup Pertandingan**
- Masukkan **nama Team A** dan **Team B**
- Pilih **suara yang diinginkan** dari dropdown
- Klik **"Test Suara"** untuk mencoba audio
- Klik **"Mulai"** untuk memulai pertandingan

### 2. **Menjalankan Pertandingan**
- **Tap/Click** area tim untuk menambah skor (+1)
- Gunakan tombol **"➖"** untuk mengurangi skor
- **Audio otomatis** mengumumkan skor setiap perubahan
- Monitor skor real-time di layar penuh

### 3. **Kontrol Pertandingan**
- **Reset**: Kembali ke 0-0 tanpa mengubah nama tim
- **Game Baru**: Kembali ke setup untuk tim baru
- **Toggle Audio**: Nyalakan/matikan suara

## 🛠️ **Teknologi yang Digunakan**

- **HTML5** - Struktur aplikasi
- **CSS3** - Styling dengan glassmorphism dan animasi
- **Vanilla JavaScript** - Logika aplikasi dan interaktivitas
- **Tailwind CSS** - Framework utility-first
- **Web Speech API** - Text-to-speech functionality
- **Web Audio API** - Sound effects generation

## 📱 **Kompatibilitas**

### ✅ **Didukung Penuh**
- Chrome 80+ (Desktop & Mobile)
- Firefox 75+ (Desktop & Mobile)
- Safari 13+ (Desktop & Mobile)
- Edge 80+ (Desktop & Mobile)

### ⚠️ **Keterbatasan**
- Speech synthesis memerlukan koneksi internet pada beberapa browser
- Kualitas suara bervariasi tergantung perangkat dan OS
- Audio mungkin tidak bekerja di mode private/incognito

## 🎯 **Use Cases**

### 🏆 **Olahraga**
- Pertandingan futsal/sepak bola
- Turnamen badminton/tenis meja
- Kompetisi basket mini
- Pertandingan voli

### 🎮 **Gaming & E-Sports**
- Tournament game mobile
- Kompetisi quiz/trivia
- Board game competitions
- Stream overlay scoring

### 🏫 **Pendidikan**
- Kuis kelas interaktif
- Kompetisi akademik
- Lomba antar kelompok
- Presentasi dengan scoring

### 🎪 **Event & Entertainment**
- Game show sederhana
- Ice breaker activities
- Team building events
- Family game night

## 🚀 **Instalasi & Setup**

### **Cara 1: Download & Run**
1. Download file `scoreboard-pro.html`
2. Buka file dengan browser modern
3. Siap digunakan! 🎉

### **Cara 2: Clone Repository**
```bash
git clone https://github.com/username/scoreboard-pro.git
cd scoreboard-pro
# Buka index.html di browser
```

### **Cara 3: Host Online**
- Upload ke GitHub Pages
- Deploy ke Netlify/Vercel
- Host di web server apapun

## ⚙️ **Kustomisasi**

### 🎨 **Mengubah Tema Warna**
```css
/* Edit bagian CSS untuk Team A */
.team-a {
  background: linear-gradient(135deg, #your-color 0%, #your-color2 100%);
}

/* Edit bagian CSS untuk Team B */
.team-b {
  background: linear-gradient(135deg, #your-color 0%, #your-color2 100%);
}
```

### 🔊 **Kustomisasi Audio**
```javascript
// Edit teks announcement di function announceScore()
let text = "Your custom announcement text";
```

### ✨ **Menambah Efek Visual**
```css
/* Tambahkan animasi custom */
@keyframes yourAnimation {
  /* Your keyframes */
}
```

## 🐛 **Troubleshooting**

### **Audio Tidak Bekerja**
- ✅ Pastikan browser mendukung Web Speech API
- ✅ Cek koneksi internet (diperlukan untuk beberapa suara)
- ✅ Reload halaman dan pilih suara lain
- ✅ Coba di browser berbeda

### **UI Tidak Responsive** 
- ✅ Update browser ke versi terbaru
- ✅ Clear cache browser
- ✅ Pastikan JavaScript enabled

### **Suara Tidak Natural**
- ✅ Pilih "Natural/Premium Voices" dari dropdown
- ✅ Test berbagai pilihan suara
- ✅ Gunakan Chrome untuk kualitas terbaik

## 📈 **Roadmap & Future Updates**

### 🔜 **Coming Soon**
- [ ] **Timer functionality** untuk pertandingan berdasarkan waktu
- [ ] **Score history** dan replay
- [ ] **Multiple team support** (3+ tim)
- [ ] **Custom sound upload** untuk efek suara
- [ ] **Theme customizer** UI
- [ ] **Export score results** ke PDF/CSV

### 💡 **Ideas & Suggestions**
- Tournament bracket system
- Live streaming integration
- Mobile app version
- Multiplayer online mode

### **Guidelines Kontribusi**
- Gunakan komentar yang jelas dalam kode
- Test di multiple browser sebelum submit
- Ikuti style guide yang sudah ada
- Dokumentasikan fitur baru


## 👨‍💻 **Author**

**Created By EkiZR**

- 🌟 **Star this repo** jika bermanfaat!
- 🐛 **Report bugs** via Issues
- 💡 **Suggest features** via Discussions

## 🙏 **Acknowledgments**

- [Tailwind CSS](https://tailwindcss.com/) - Utility-first CSS framework
- [Google Fonts](https://fonts.google.com/) - Inter & Orbitron fonts
- [Web APIs](https://developer.mozilla.org/en-US/docs/Web/API) - Speech & Audio APIs
- Community feedback and suggestions

---



**⭐ Don't forget to star this repository if you found it helpful!**# penghitung-skor
