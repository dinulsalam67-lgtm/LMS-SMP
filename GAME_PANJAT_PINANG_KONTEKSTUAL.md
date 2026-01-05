# 🎉 Panjat Pinang Aljabar Kontekstual

## 📖 Deskripsi
Game **Panjat Pinang Aljabar Kontekstual** adalah permainan edukatif bertema lomba 17 Agustus yang menggabungkan tradisi Indonesia dengan pembelajaran aljabar melalui soal cerita dari kehidupan sehari-hari.

## ✨ Fitur Utama

### 🎯 Soal Kontekstual
- **20+ Soal Cerita** dari kehidupan nyata
- Kategori beragam:
  - 🛒 Belanja & Toko
  - 🚗 Transportasi & Perjalanan
  - 💰 Uang & Tabungan
  - 📚 Sekolah & Belajar
  - ⚽ Olahraga & Kesehatan
  - 🌾 Pertanian & Alam
  - 👨‍👩‍👧 Keluarga & Umur
  - 🏪 Bisnis & Usaha
  - 📱 Teknologi & Gadget
  - ♻️ Lingkungan & Sosial

### 🎨 Tema Indonesia
- Dekorasi bendera merah putih 🇮🇩
- Banner "Dirgahayu Indonesia"
- Suasana perayaan 17 Agustus
- Emoji dan visual yang meriah

### 🎮 Gameplay
- **2 Pemain**: Budi 👦 vs Ani 👧
- **10 Tangga**: Dari bawah ke puncak
- **Jawaban Benar**: Naik 1 tangga ⬆️
- **Jawaban Salah**: Turun 1 tangga ⬇️
- **Pemenang**: Yang mencapai puncak duluan 🏆

### 📊 Statistik Pemain
- Jumlah jawaban benar ✅
- Jumlah jawaban salah ❌
- Persentase akurasi 📊
- Progress tangga real-time

### 🖼️ Dua Mode Tampilan
1. **Vertikal**: Pohon pinang berdiri tegak
2. **Horizontal**: Pohon pinang mendatar (landscape)

## 🎓 Contoh Soal

### Mudah
> **🛒 Di Toko Kelontong**
> 
> Budi membeli x kg beras seharga Rp12.000/kg dan 3 kg gula seharga Rp15.000/kg. Total belanja Rp81.000. Berapa kg beras yang dibeli?
> 
> **Jawaban**: 3 kg

### Sedang
> **💰 Menabung**
> 
> Tabungan Budi 2x rupiah, tabungan Ani 3x rupiah. Selisih tabungan mereka Rp50.000. Berapa tabungan Ani?
> 
> **Jawaban**: 150.000 rupiah

## 🚀 Cara Menggunakan

### 1. Integrasi ke HTML
Tambahkan script dan CSS ke `index.html`:

```html
<!-- CSS -->
<link rel="stylesheet" href="styles/game-pinang-contextual.css">

<!-- JavaScript -->
<script src="scripts/game-pinang-contextual.js"></script>
```

### 2. Panggil Fungsi Game
Dari `game.js`, tambahkan case untuk game ID 9:

```javascript
function startGame(gameId) {
    const game = gameData.find(g => g.id === gameId);
    if (!game) return;

    const modalContent = document.getElementById('gameModalContent');

    switch (gameId) {
        // ... game lainnya ...
        case 9:
            initPanjatPinangContextualGame(modalContent, game);
            break;
    }

    openModal('gameModal');
}
```

### 3. Jalankan Game
- Buka halaman Games
- Pilih "Panjat Pinang Aljabar Kontekstual"
- Mulai bermain!

## 📁 File yang Dibuat

```
lms-matematika-smp/
├── scripts/
│   ├── game-pinang-contextual.js    # Logic game
│   └── data.js                       # Data game (updated)
├── styles/
│   └── game-pinang-contextual.css   # Styling game
└── docs/
    └── GAME_PANJAT_PINANG_KONTEKSTUAL.md  # Dokumentasi ini
```

## 🎨 Desain Visual

### Warna Tema
- **Header**: Gradient hijau (#11998e → #38ef7d)
- **Banner**: Merah-Putih Indonesia (#FF0000 → #FFFFFF → #FF0000)
- **Player 1**: Gradient ungu (#667eea → #764ba2)
- **Player 2**: Gradient pink (#f093fb → #f5576c)
- **Hadiah**: Emas (#ffd700)

### Animasi
- ✨ Wave animation untuk bendera
- 🎊 Banner pulse
- 🧗 Climb animation saat naik tangga
- 👑 Crown float untuk pemenang
- 🏆 Trophy spin di hasil akhir

## 🎯 Tujuan Pembelajaran

1. **Pemahaman Konsep Aljabar**
   - Variabel dan konstanta
   - Operasi aljabar dasar
   - Penyelesaian persamaan linear

2. **Aplikasi dalam Kehidupan**
   - Menghubungkan matematika dengan dunia nyata
   - Pemecahan masalah kontekstual
   - Berpikir kritis dan analitis

3. **Keterampilan Sosial**
   - Kompetisi sehat
   - Sportivitas
   - Motivasi belajar

## 💡 Tips Bermain

### Untuk Siswa
- 📖 Baca soal dengan teliti
- 💭 Pahami konteks cerita
- 🔍 Identifikasi variabel yang dicari
- ✏️ Buat persamaan matematika
- ✅ Periksa jawaban sebelum submit

### Untuk Guru
- 🎯 Gunakan sebagai ice breaker
- 📊 Pantau progress siswa
- 🏆 Beri apresiasi untuk partisipasi
- 💬 Diskusikan strategi penyelesaian
- 🔄 Ulangi untuk penguatan konsep

## 🔧 Kustomisasi

### Menambah Soal Baru
Edit array `contextualQuestions` di `game-pinang-contextual.js`:

```javascript
{
    context: "🎯 Kategori Baru",
    question: "Soal cerita Anda...",
    solution: "Langkah penyelesaian...",
    answer: 42,
    unit: "satuan",
    type: "number",
    difficulty: "mudah", // mudah, sedang, sulit
    hint: "Petunjuk untuk siswa..."
}
```

### Mengubah Jumlah Tangga
Ubah konstanta `totalSteps` di fungsi `initPanjatPinangContextualGame`:

```javascript
const totalSteps = 10; // Ubah sesuai kebutuhan
```

### Mengubah Nama Pemain
Edit objek `player1Stats` dan `player2Stats`:

```javascript
let player1Stats = { correct: 0, wrong: 0, name: 'Nama Baru 1' };
let player2Stats = { correct: 0, wrong: 0, name: 'Nama Baru 2' };
```

## 🐛 Troubleshooting

### Game tidak muncul
- ✅ Pastikan file JS dan CSS sudah di-include di HTML
- ✅ Cek console browser untuk error
- ✅ Pastikan game ID 9 ada di `gameData`

### Soal tidak muncul
- ✅ Cek array `contextualQuestions` tidak kosong
- ✅ Pastikan format soal sesuai struktur

### Styling tidak muncul
- ✅ Pastikan CSS file sudah di-load
- ✅ Cek path file CSS benar
- ✅ Clear browser cache

## 📈 Pengembangan Lebih Lanjut

### Fitur yang Bisa Ditambahkan
- 🔊 Sound effects untuk benar/salah
- 🎵 Background music tema Indonesia
- 🏅 Sistem achievement dan badge
- 💾 Simpan high score ke localStorage
- 🌐 Multiplayer online
- 📱 Responsive untuk mobile
- 🎨 Pilihan tema warna
- 👥 Mode 3-4 pemain

### Integrasi dengan LMS
- 📊 Tracking progress siswa
- 📝 Laporan ke guru
- 🎯 Rekomendasi soal adaptif
- 🏆 Leaderboard kelas

## 📞 Support

Jika ada pertanyaan atau masalah:
1. Cek dokumentasi ini terlebih dahulu
2. Review kode di file JS dan CSS
3. Cek console browser untuk error
4. Hubungi developer

## 📜 Lisensi

Game ini dibuat untuk tujuan edukasi. Silakan digunakan dan dimodifikasi sesuai kebutuhan pembelajaran.

---

**Selamat Bermain dan Belajar! 🎉🇮🇩**

*Dirgahayu Indonesia! Merdeka!* 🏆
