# 🚀 Fighter Jet Battle - Persamaan Linear

## 📖 Deskripsi
**Fighter Jet Battle** adalah game shoot 'em up (tembak-tembakan) yang kompleks dan penuh warna untuk belajar Persamaan Linear. Terinspirasi dari game mobile Android populer, game ini menggabungkan aksi cepat dengan pembelajaran matematika yang menyenangkan!

## ✨ Fitur Utama

### 🎮 Gameplay
- **Kontrol Pesawat**: Gerakkan pesawat tempur dengan arrow keys
- **Tembak Musuh**: Tekan Space untuk menembak
- **Selesaikan Soal**: Jawab persamaan linear untuk mendapat poin
- **Combo System**: Jawab benar berturut-turut untuk bonus poin
- **Power-Ups**: Kumpulkan power-up untuk kemampuan spesial

### 💥 Sistem Pertempuran
1. **Musuh dengan Soal**: Setiap musuh membawa persamaan linear
2. **Tembak untuk Mengalahkan**: Kurangi health musuh dengan tembakan
3. **Jawab Soal**: Setelah musuh kalah, jawab soalnya
4. **Dapatkan Poin**: Poin berdasarkan kesulitan soal

### 🎯 Tingkat Kesulitan Soal
- **Easy (⭐)**: 100 poin - Persamaan sederhana (2x + 3 = 11)
- **Medium (⭐⭐)**: 200 poin - Persamaan dengan bilangan negatif (3x - 5 = 10)
- **Hard (⭐⭐⭐)**: 300 poin - Persamaan kompleks (5x - 2x + 4 = 19)

### 🛡️ Power-Ups
1. **Shield (🛡️)** - Perlindungan dari tembakan musuh
2. **Rapid Fire (⚡)** - Tembakan lebih cepat
3. **Multi Shot (✨)** - Tembakan triple sekaligus

### 📊 Sistem Skor
- **Base Points**: Sesuai kesulitan soal
- **Combo Bonus**: +10 poin per combo level
- **Max Combo**: Catat combo tertinggi

## 🎨 Visual & Efek

### Grafis Penuh Warna
- **Background**: Luar angkasa dengan bintang bergerak
- **Pesawat Pemain**: Hijau neon dengan efek glow
- **Musuh**: Warna berbeda per kesulitan (Hijau/Kuning/Merah)
- **Peluru**: Kuning cerah dengan shadow effect
- **Partikel**: Efek ledakan warna-warni

### Animasi
- ✨ Bintang bergerak
- 💥 Efek ledakan partikel
- 🌟 Glow effect pada power-up
- 🎯 Health bar musuh
- ⚡ Invincibility flash

## 🎮 Kontrol

| Tombol | Fungsi |
|--------|--------|
| ⬆️ Arrow Up | Gerak ke atas |
| ⬇️ Arrow Down | Gerak ke bawah |
| ⬅️ Arrow Left | Gerak ke kiri |
| ➡️ Arrow Right | Gerak ke kanan |
| Space | Tembak |

## 📈 HUD (Heads-Up Display)

Display informasi real-time:
- ❤️ **Lives**: Nyawa pemain (3 nyawa)
- ⭐ **Score**: Total skor
- 🔥 **Combo**: Combo saat ini
- 📊 **Level**: Level permainan

## 🎯 Cara Bermain

### 1. Mulai Game
- Pilih "Fighter Jet Battle" dari menu Games
- Game langsung dimulai

### 2. Kontrol Pesawat
- Gunakan arrow keys untuk bergerak
- Hindari tembakan musuh (peluru merah)
- Kumpulkan power-up yang jatuh

### 3. Tembak Musuh
- Tekan Space untuk menembak
- Kurangi health bar musuh hingga habis
- Musuh akan hancur dan muncul soal

### 4. Jawab Soal
- Modal soal akan muncul (game pause)
- Baca persamaan linear
- Masukkan nilai x
- Klik "Jawab" atau tekan Enter

### 5. Dapatkan Poin
- **Benar**: Dapat poin + combo naik
- **Salah**: Combo reset ke 0
- **Lewati**: Combo reset, tidak dapat poin

### 6. Bertahan Hidup
- Hindari tembakan musuh
- Jangan sampai nyawa habis
- Gunakan power-up shield untuk perlindungan

## 💡 Tips & Strategi

### Untuk Skor Tinggi
1. **Jaga Combo**: Jawab benar terus-menerus
2. **Prioritas Musuh**: Tembak musuh terdekat dulu
3. **Kumpulkan Power-Up**: Manfaatkan kemampuan spesial
4. **Gerak Terus**: Jangan diam di satu tempat
5. **Fokus**: Konsentrasi pada soal dan gameplay

### Strategi Bertahan
- Gerak zigzag untuk hindari peluru
- Gunakan shield saat banyak musuh
- Jangan terlalu agresif di awal
- Pelajari pola tembakan musuh

### Maksimalkan Poin
- Jawab soal hard untuk poin besar
- Pertahankan combo setinggi mungkin
- Jangan skip soal kecuali terpaksa
- Gunakan multi-shot untuk efisiensi

## 🏆 Sistem Penilaian

### Hasil Akhir
- **🏆 Master** (>1000 poin): "Luar Biasa! Master Persamaan Linear!"
- **🥈 Bagus** (>500 poin): "Bagus! Terus Berlatih!"
- **🥉 Coba Lagi** (<500 poin): "Jangan Menyerah! Coba Lagi!"

### Statistik Ditampilkan
- Total Skor
- Level Tercapai
- Max Combo

## 🔧 Kustomisasi

### Mengubah Kesulitan
Edit di `game-fighter-jet.js`:

```javascript
let maxEnemies = 3; // Jumlah musuh maksimal
let lives = 3; // Nyawa awal
player.speed = 5; // Kecepatan pesawat
```

### Menambah Jenis Soal
Tambah di fungsi `generateQuestion()`:

```javascript
case 'custom':
    // Soal custom Anda
    return {
        equation: "...",
        answer: ...,
        difficulty: 'medium',
        points: 200
    };
```

### Mengubah Warna
Edit di CSS atau JS:

```javascript
player.color = '#00ff00'; // Warna pesawat
```

## 📊 Contoh Soal

### Easy
```
Soal: 2x + 5 = 13
Jawaban: x = 4
Poin: 100
```

### Medium
```
Soal: 3x - 7 = 8
Jawaban: x = 5
Poin: 200
```

### Hard
```
Soal: 5x - 2x + 3 = 18
Jawaban: x = 5
Poin: 300
```

## 🐛 Troubleshooting

### Game tidak muncul
- ✅ Cek console browser (F12)
- ✅ Pastikan file JS dan CSS sudah di-load
- ✅ Refresh browser (Ctrl+F5)

### Kontrol tidak responsif
- ✅ Klik pada canvas terlebih dahulu
- ✅ Pastikan tidak ada input lain yang fokus
- ✅ Coba reload halaman

### Soal tidak muncul
- ✅ Cek fungsi `generateQuestion()`
- ✅ Pastikan modal tidak ter-block
- ✅ Lihat error di console

### Performance lambat
- ✅ Kurangi jumlah partikel
- ✅ Reduce maxEnemies
- ✅ Gunakan browser modern

## 🎓 Tujuan Pembelajaran

### Kognitif
1. Memahami konsep persamaan linear
2. Menyelesaikan persamaan dengan berbagai tingkat kesulitan
3. Berpikir cepat dan akurat
4. Mengenali pola persamaan

### Afektif
1. Meningkatkan motivasi belajar matematika
2. Menumbuhkan rasa percaya diri
3. Belajar dari kesalahan
4. Sportivitas dalam kompetisi

### Psikomotorik
1. Koordinasi mata-tangan
2. Refleks cepat
3. Multitasking (bermain + berpikir)

## 📈 Pengembangan Selanjutnya

### Fitur yang Bisa Ditambahkan
- [ ] Boss fight dengan soal super sulit
- [ ] Multiple levels dengan kesulitan meningkat
- [ ] Leaderboard online
- [ ] Achievement system
- [ ] Sound effects & background music
- [ ] Berbagai jenis pesawat
- [ ] Upgrade system
- [ ] Multiplayer mode
- [ ] Story mode
- [ ] Daily challenges

### Peningkatan Visual
- [ ] Sprite animasi untuk pesawat
- [ ] Background parallax
- [ ] Efek ledakan lebih detail
- [ ] Cutscene intro/outro
- [ ] Weather effects

## 🎮 Untuk Guru

### Penggunaan di Kelas
1. **Warm-up**: Mulai pelajaran dengan 5 menit game
2. **Review**: Gunakan untuk mengulang materi
3. **Kompetisi**: Buat turnamen kelas
4. **Reward**: Berikan poin tambahan untuk skor tinggi

### Monitoring Siswa
- Lihat skor untuk evaluasi pemahaman
- Perhatikan jenis soal yang sering salah
- Gunakan combo sebagai indikator konsistensi
- Diskusikan strategi penyelesaian

## 📞 Support

Jika ada masalah:
1. Baca dokumentasi ini
2. Cek troubleshooting guide
3. Review source code
4. Hubungi developer

## 📜 Credits

Game ini dibuat untuk:
- Membuat pembelajaran matematika lebih menyenangkan
- Meningkatkan engagement siswa
- Menggabungkan gaming dan edukasi
- Memberikan pengalaman belajar yang berbeda

---

## 🎉 Selamat Bermain!

**Tembak, Jawab, Menang!** 🚀

*"Matematika itu seru kalau dikemas dengan cara yang tepat!"*

---

**Version**: 1.0.0  
**Last Updated**: 22 Desember 2025  
**Category**: Educational Game - Mathematics  
**Platform**: Web Browser
