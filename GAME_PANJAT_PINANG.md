# 🎋 Game Panjat Pinang Aljabar - Dokumentasi Lengkap

## 📋 Deskripsi Game

**Panjat Pinang Aljabar** adalah game edukatif matematika yang menggabungkan tradisi Indonesia (panjat pinang) dengan pembelajaran aljabar modern. Game ini dirancang untuk 2 pemain yang berkompetisi memanjat batang pinang dengan menjawab soal-soal aljabar.

## 🎮 Fitur Utama

### 1. **Gameplay Interaktif**
- ✅ 2 pemain berkompetisi secara bergantian
- ✅ Sistem naik-turun berdasarkan jawaban:
  - **Jawaban Benar**: Naik 10%
  - **Jawaban Salah**: Turun 5%
- ✅ Maksimal 20 soal per permainan
- ✅ Pemenang: Yang mencapai puncak (100%) duluan atau tertinggi setelah 20 soal

### 2. **Soal Aljabar Lengkap**
Game mencakup 5 jenis soal aljabar yang komprehensif:

#### a. **Penyederhanaan (Simplify)**
- Contoh: `Sederhanakan: 5x + 7x - 3x`
- Jawaban: `9x`
- Melatih kemampuan menggabungkan suku sejenis

#### b. **Evaluasi (Evaluate)**
- Contoh: `Jika x = 4, hitunglah 3x + 7`
- Jawaban: `19`
- Melatih substitusi nilai variabel

#### c. **Pemfaktoran (Factor)**
- Contoh: `Faktorkan: 12x + 18`
- Jawaban: `6(2x + 3)`
- Melatih mencari FPB dan memfaktorkan
- Dilengkapi dengan hint FPB

#### d. **Perkalian (Multiply)**
- Contoh: `3x × 4y = ?`
- Jawaban: `12xy`
- Melatih perkalian bentuk aljabar

#### e. **Ekspansi (Expand)**
- Contoh: `2(5x + 3) = ?`
- Jawaban: `10x + 6`
- Melatih sifat distributif

### 3. **Visualisasi Modern**

#### Batang Pinang (Poles)
- 🌳 Dua batang pinang dengan gradient coklat realistis
- ✨ Efek licin dengan segmen-segmen transparan
- 📏 Tinggi 450px dengan border-radius untuk efek 3D
- 💫 Shadow effects untuk kedalaman visual

#### Pemanjat (Climbers)
- 👤 Avatar bulat dengan gradient warna berbeda:
  - Pemain 1: Ungu-biru (#667eea → #764ba2)
  - Pemain 2: Pink-merah (#f093fb → #f5576c)
- 📊 Indikator tinggi real-time (%)
- 🎭 Animasi naik/turun yang smooth
- 🏷️ Label nama pemain di atas avatar

#### Hadiah di Puncak
- 🏆 Trophy icon
- 🎁 Gift icon
- 🏅 Medal icon
- ✨ Animasi bounce dan float yang bergantian
- 💛 Warna emas dengan drop-shadow

### 4. **Panel Pertanyaan**

#### Indikator Giliran
- 🎯 Badge berwarna sesuai pemain aktif
- 💓 Animasi pulse untuk menarik perhatian
- 📝 Teks "Giliran Pemain X"

#### Kotak Soal
- 📚 Background gradient abu-abu lembut
- 📏 Font besar (1.8rem) untuk keterbacaan
- 💡 Hint box kuning untuk soal pemfaktoran
- 🎨 Border kiri kuning untuk highlight hint

#### Input Jawaban
- ⌨️ Input field besar dengan border hijau saat fokus
- 🎯 Auto-focus untuk kemudahan
- ⏎ Support Enter key untuk submit
- 🔢 Dynamic type: number atau text sesuai soal

#### Tombol Panjat
- 🚀 Gradient hijau (#11998e → #38ef7d)
- ⬆️ Icon arrow-up
- ✨ Hover effect dengan transform dan shadow
- 💪 Font bold untuk emphasis

### 5. **Feedback System**

#### Feedback Visual
- ✅ **Benar**: Border hijau, icon check-circle hijau
- ❌ **Salah**: Border merah, icon times-circle merah, tampilkan jawaban benar
- 🎬 Animasi popIn yang smooth
- ⏱️ Auto-dismiss setelah 1.5 detik

#### Animasi Pemanjat
- 🧗 **Climbing Up**: Scale 1.2 saat naik
- 📉 **Sliding Down**: Scale 0.9 saat turun
- ⚡ Transition 0.8s ease-out
- 🎯 Update posisi secara real-time

### 6. **Layar Hasil (Result Screen)**

#### Tampilan Pemenang
- 🏆 Icon trophy besar dengan animasi bounce
- 🎉 Emoji celebration untuk pemenang
- 🤝 Icon handshake untuk seri
- 📊 Pesan kustom berdasarkan kondisi:
  - Mencapai puncak
  - Lebih tinggi setelah 20 soal
  - Seri

#### Kartu Ketinggian Final
- 📊 Progress bar dengan gradient warna pemain
- 🎯 Nilai persentase besar
- 👑 Border emas untuk pemenang
- 📈 Background khusus untuk pemenang

#### Statistik Game
- ❓ Total soal dijawab
- 📏 Tinggi tertinggi yang dicapai
- 🎨 Icon yang relevan untuk setiap stat

#### Tombol Main Lagi
- 🔄 Icon redo
- 🎮 Restart game dengan satu klik
- ✨ Hover effects yang menarik

## 🎨 Desain Visual

### Warna Tema
- **Background Arena**: Gradient biru langit (#87CEEB → #98D8C8)
- **Batang Pinang**: Coklat kayu (#8B4513 → #A0522D)
- **Pemain 1**: Ungu-biru (#667eea → #764ba2)
- **Pemain 2**: Pink-merah (#f093fb → #f5576c)
- **Aksen Hijau**: Tombol dan success (#11998e → #38ef7d)
- **Emas**: Hadiah dan pemenang (#FFD700)

### Animasi
1. **Float**: Hadiah melayang naik-turun
2. **Bounce**: Hadiah memantul bergantian
3. **Pulse**: Indikator giliran berdenyut
4. **PopIn**: Feedback muncul dengan scale
5. **ClimbUp**: Pemanjat membesar saat naik
6. **SlideDownPole**: Pemanjat mengecil saat turun

### Responsiveness
- 📱 Grid 2 kolom di desktop (poles + panel)
- 📱 Grid 1 kolom di mobile (< 768px)
- 📏 Tinggi pole menyesuaikan (450px → 350px)
- 📝 Font size menyesuaikan untuk mobile

## 🎯 Mekanisme Permainan

### Alur Game
1. **Start**: Pemain 1 mendapat soal pertama
2. **Answer**: Pemain menjawab soal
3. **Feedback**: Sistem cek jawaban dan beri feedback
4. **Update**: Tinggi pemain diupdate (naik/turun)
5. **Check Win**: Cek apakah ada yang menang
6. **Switch**: Ganti ke pemain berikutnya
7. **Repeat**: Ulangi sampai ada pemenang atau 20 soal

### Kondisi Menang
1. **Mencapai Puncak**: Tinggi >= 100%
2. **20 Soal Selesai**: Yang lebih tinggi menang
3. **Seri**: Kedua pemain sama tinggi

### Validasi Jawaban
- **Number Type**: Toleransi 0.01 untuk floating point
- **Text Type**: 
  - Remove whitespace
  - Case insensitive
  - Support multiple formats (dengan/tanpa spasi)
  - Fallback ke numeric answer jika applicable

## 🔧 Implementasi Teknis

### Struktur Data
```javascript
{
    id: 8,
    title: "Panjat Pinang Aljabar",
    icon: "fa-tree",
    color: "linear-gradient(135deg, #11998e 0%, #38ef7d 100%)",
    description: "Lomba panjat pinang...",
    features: ["2 Pemain", "Animasi Memanjat", "Soal Aljabar Lengkap", "Hadiah di Puncak"],
    difficulty: "Sedang - Sulit"
}
```

### State Management
- `player1Height`: 0-100 (persentase)
- `player2Height`: 0-100 (persentase)
- `currentPlayer`: 1 atau 2
- `questionCount`: 0-20
- `currentQuestion`: Object soal aktif
- `gameActive`: Boolean status game

### Generator Soal
- Random type selection dari 5 jenis
- Random numbers untuk variasi
- Validasi (misal: hindari pembagian nol)
- Support multiple answer formats
- Optional hint untuk soal kompleks

## 📚 Manfaat Edukatif

### Keterampilan yang Dilatih
1. **Penyederhanaan Aljabar**: Menggabungkan suku sejenis
2. **Substitusi**: Mengganti variabel dengan nilai
3. **Pemfaktoran**: Mencari FPB dan faktor
4. **Perkalian Aljabar**: Mengalikan variabel berbeda
5. **Distributif**: Menguraikan kurung

### Aspek Kompetitif
- 🏃 Mendorong kecepatan berpikir
- 🎯 Meningkatkan akurasi
- 💪 Membangun kepercayaan diri
- 🤝 Pembelajaran sosial (2 pemain)

### Gamifikasi
- 🎮 Visual menarik dengan tema tradisional
- 🏆 Reward system (hadiah di puncak)
- 📊 Progress tracking real-time
- ✨ Feedback instant
- 🎬 Animasi yang engaging

## 🚀 Cara Bermain

1. **Buka halaman Games** di LMS
2. **Pilih "Panjat Pinang Aljabar"**
3. **Pemain 1 mulai** dengan soal pertama
4. **Ketik jawaban** di input field
5. **Klik "Panjat!"** atau tekan Enter
6. **Lihat feedback** dan animasi
7. **Giliran berganti** ke pemain berikutnya
8. **Lanjutkan** sampai ada pemenang
9. **Klik "Main Lagi"** untuk restart

## 🎓 Tips Bermain

### Untuk Siswa
- 📝 Baca soal dengan teliti
- 💡 Perhatikan hint jika ada
- ⚡ Jawab dengan cepat tapi akurat
- 🎯 Fokus pada pemahaman, bukan hanya menang
- 📚 Pelajari dari jawaban yang salah

### Untuk Guru
- 👥 Gunakan untuk kompetisi kelas
- 📊 Monitor kesulitan siswa di jenis soal tertentu
- 🎯 Fokuskan pembelajaran pada area yang lemah
- 🏆 Buat turnamen untuk motivasi
- 📈 Track progress siswa

## 🔮 Pengembangan Masa Depan

### Fitur Potensial
- 🎚️ Level kesulitan (mudah, sedang, sulit)
- 📊 Leaderboard global
- 🎵 Sound effects dan background music
- 💾 Save progress dan history
- 🏅 Achievement system
- 👥 Multiplayer online
- 📱 Mobile app version
- 🎨 Tema visual alternatif
- 📚 Lebih banyak jenis soal aljabar
- 🔢 Integrasi dengan materi lain

## 📝 Kesimpulan

Game **Panjat Pinang Aljabar** berhasil menggabungkan:
- ✅ Budaya tradisional Indonesia (panjat pinang)
- ✅ Pembelajaran matematika modern (aljabar)
- ✅ Gamifikasi yang engaging
- ✅ Kompetisi yang sehat
- ✅ Visual yang menarik dan modern
- ✅ Mekanik game yang sederhana tapi efektif

Game ini cocok untuk:
- 🎓 Siswa SMP kelas 7-8
- 👥 Pembelajaran kelompok
- 🏆 Kompetisi kelas
- 🏠 Belajar mandiri
- 🎮 Latihan yang menyenangkan

---

**Dibuat dengan ❤️ untuk pembelajaran matematika yang lebih seru!**
