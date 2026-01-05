# 🎓 MathLearn - LMS Matematika Kelas VII SMP

Platform Learning Management System (LMS) modern dan interaktif untuk pembelajaran Matematika Kelas VII dengan Kurikulum Merdeka.

## ✨ Fitur Utama

### 🔐 1. Login & Autentikasi
- Login dengan Google OAuth2 (simulasi)
- Login demo untuk testing
- Session management dengan localStorage
- User profile dengan avatar

### 🏠 2. Beranda
- Hero banner menarik dengan statistik
- Quick access ke semua fitur
- Progress pembelajaran siswa
- Pengumuman terbaru
- Quote motivasi matematika

### 📘 3. Materi Pembelajaran
6 Bab lengkap dengan Kurikulum Merdeka:
1. **Bilangan Bulat** - Operasi hitung dan sifat-sifatnya
2. **Aljabar** - Variabel, konstanta, dan operasi bentuk aljabar
3. **Persamaan Linear** - PLSV dan penerapannya
4. **Perbandingan** - Senilai dan berbalik nilai
5. **Bangun Datar** - Keliling dan luas
6. **Statistika** - Mean, median, modus

Setiap bab memiliki:
- ✅ Ringkasan materi lengkap
- ✅ Contoh soal dengan pembahasan
- ✅ Latihan interaktif dengan scoring
- ✅ Soal HOTS (Higher Order Thinking Skills)
- ✅ Ilustrasi visual

### ▶️ 4. Video Pembelajaran
- 8+ video YouTube terintegrasi
- Thumbnail dan deskripsi
- Tracking video yang sudah ditonton
- Kategorisasi per bab

### 🎮 5. Game Battle Matematika
6 game battle interaktif:
1. **Battle Bilangan Bulat** - Operasi hitung cepat
2. **Battle Aljabar** - Menyederhanakan bentuk aljabar
3. **Battle Persamaan Linear** - Menyelesaikan PLSV
4. **Battle Perbandingan** - Perbandingan senilai vs berbalik
5. **Battle Bangun Datar** - Menghitung luas/keliling
6. **Battle Statistika** - Mean, median, modus

Fitur game:
- Real-time 2 pemain
- Timer 60 detik
- Scoring system
- Feedback langsung
- Animasi kemenangan

### 📝 6. Tugas & Kuis
- Kuis pilihan ganda otomatis
- Timer untuk setiap kuis
- Auto-grading dengan pembahasan
- Review jawaban detail
- Progress tracking
- Sistem pengumpulan tugas
- Deadline reminder

## 🎨 Desain & UI/UX

### Tema Modern
- Warna dominan: Biru-Putih
- Gradient yang menarik
- Animasi smooth
- Ikon jelas dan friendly
- Minimalis namun informatif

### Dark Mode
- Toggle tema gelap/terang
- Preference tersimpan di localStorage
- Transisi smooth

### Responsive Design
- 100% mobile responsive
- Tablet optimized
- Desktop friendly
- Breakpoints: 480px, 768px, 1024px

## 🛠️ Teknologi

### Frontend
- **HTML5** - Struktur semantik
- **CSS3** - Modern styling dengan CSS Variables
- **JavaScript (Vanilla)** - No framework, pure JS
- **Font Awesome** - Icons
- **Google Fonts** - Inter & Poppins

### Data Storage
- **localStorage** - User data, progress, results
- **JSON** - Data structure

### External Resources
- **YouTube API** - Video embedding
- **Google Fonts** - Typography
- **Font Awesome CDN** - Icons

## 📁 Struktur File

```
lms-matematika-smp/
├── index.html              # Main HTML file
├── styles/
│   └── main.css           # All CSS styles
├── scripts/
│   ├── data.js            # Materi, video, game, tugas data
│   ├── auth.js            # Authentication functions
│   ├── navigation.js      # Navigation & theme toggle
│   ├── materi.js          # Materi pembelajaran logic
│   ├── video.js           # Video player logic
│   ├── game.js            # Game battle logic
│   ├── tugas.js           # Tugas & kuis logic
│   └── main.js            # Main initialization
└── README.md              # Documentation
```

## 🚀 Cara Menggunakan

### 1. Buka Website
Buka file `index.html` di browser modern (Chrome, Firefox, Edge, Safari)

### 2. Login
- Klik "Masuk dengan Google" (simulasi)
- Atau gunakan "Masuk Demo" dengan email dan password apa saja

### 3. Jelajahi Fitur
- **Beranda**: Lihat overview dan quick access
- **Materi**: Pelajari 6 bab matematika
- **Video**: Tonton video pembelajaran
- **Game**: Main game battle dengan teman
- **Tugas**: Kerjakan kuis dan tugas

### 4. Kerjakan Kuis
- Pilih kuis dari menu Tugas & Kuis
- Klik "Mulai Kuis"
- Jawab semua soal sebelum waktu habis
- Lihat hasil dan pembahasan

### 5. Main Game
- Pilih game dari menu Game Battle
- Klik "Mulai Battle"
- Bermain dengan 2 pemain bergantian
- Siapa yang paling banyak benar menang!

## 📊 Data Materi

### Bilangan Bulat
- 8 topik pembahasan
- 3 contoh soal
- 5 latihan interaktif
- 2 soal HOTS

### Aljabar
- 6 topik pembahasan
- 3 contoh soal
- 5 latihan interaktif
- 2 soal HOTS

### Persamaan Linear
- 5 topik pembahasan
- 3 contoh soal
- 5 latihan interaktif
- 2 soal HOTS

### Perbandingan
- 4 topik pembahasan
- 3 contoh soal
- 5 latihan interaktif
- 2 soal HOTS

### Bangun Datar
- 7 topik pembahasan
- 3 contoh soal
- 5 latihan interaktif
- 2 soal HOTS

### Statistika
- 6 topik pembahasan
- 3 contoh soal
- 5 latihan interaktif
- 2 soal HOTS

## 🎯 Kuis & Tugas

### Kuis Tersedia
1. Kuis: Bilangan Bulat (10 soal, 20 menit)
2. Kuis: Aljabar (10 soal, 20 menit)
3. Kuis: Persamaan Linear (10 soal, 25 menit)
4. Kuis: Bangun Datar (10 soal, 25 menit)
5. Kuis: Statistika (10 soal, 25 menit)

### Tugas Tersedia
1. Tugas: Perbandingan dalam Kehidupan

## 🎮 Game Battle

### Game 1: Battle Bilangan Bulat ✅
- Fully functional
- Random question generator
- 4 operations: +, -, ×, ÷
- Real-time scoring
- 60 second timer

### Game 2-6: Coming Soon
- Struktur sudah siap
- Akan dikembangkan dengan pola yang sama

## 💾 Data Persistence

Semua progress disimpan di localStorage:
- User session
- Video watched status
- Quiz results
- Assignment submissions
- Theme preference

## 🌐 Browser Support

- ✅ Chrome 90+
- ✅ Firefox 88+
- ✅ Safari 14+
- ✅ Edge 90+

## 📱 Responsive Breakpoints

- **Mobile**: < 480px
- **Tablet**: 481px - 768px
- **Desktop**: 769px - 1024px
- **Large Desktop**: > 1024px

## 🎨 Color Palette

### Primary Colors
- Primary Blue: `#4F46E5`
- Primary Blue Dark: `#4338CA`
- Primary Blue Light: `#6366F1`

### Secondary Colors
- Purple: `#7C3AED`
- Pink: `#EC4899`
- Cyan: `#06B6D4`

### Semantic Colors
- Success: `#10B981`
- Warning: `#F59E0B`
- Error: `#EF4444`
- Info: `#3B82F6`

## 🔮 Future Enhancements

### Planned Features
- [ ] Real Google OAuth integration
- [ ] Backend with Firebase/Supabase
- [ ] Real-time multiplayer games
- [ ] Leaderboard system
- [ ] Achievement badges
- [ ] Parent/teacher dashboard
- [ ] PDF export for materi
- [ ] Print certificate
- [ ] Discussion forum
- [ ] Live chat support

### Game Enhancements
- [ ] Complete all 6 games
- [ ] Add difficulty levels
- [ ] Power-ups system
- [ ] Sound effects
- [ ] Background music
- [ ] Avatar customization

## 👨‍💻 Development

### Local Development
1. Clone atau download project
2. Buka `index.html` di browser
3. Edit files sesuai kebutuhan
4. Refresh browser untuk melihat perubahan

### Customization
- **Colors**: Edit CSS variables di `main.css`
- **Content**: Edit data di `data.js`
- **Features**: Tambah logic di file JS masing-masing

## 📄 License

Educational use only. Created for Indonesian SMP students.

## 🙏 Credits

- **Icons**: Font Awesome
- **Fonts**: Google Fonts (Inter, Poppins)
- **Videos**: YouTube educational content
- **Design**: Inspired by Google Classroom & Khan Academy

## 📞 Support

Untuk pertanyaan atau bantuan:
- Email: support@mathlearn.id (simulasi)
- Website: www.mathlearn.id (simulasi)

---

**Dibuat dengan ❤️ untuk siswa SMP Indonesia**

*Versi 1.0.0 - Desember 2025*
