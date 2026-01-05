# ✈️ 2 Player Jet Duel - Persamaan Linear

## 📖 Deskripsi
Game **2 Player Jet Duel** adalah permainan duel pesawat tempur untuk 2 pemain lokal. Dua pesawat tempur saling berhadapan dan saling menembak! Jawab soal persamaan linear untuk mendapatkan power-up yang kuat!

## ✨ Fitur Utama

### ✈️ Pesawat Tempur Realistis
- **Player 1** (Biru): Pesawat di sisi kiri
- **Player 2** (Merah): Pesawat di sisi kanan
- Desain jet yang detail dengan:
  - Body aerodinamis
  - Wings (sayap)
  - Cockpit (kokpit)
  - Engine glow (cahaya mesin)

### 🎮 PvP Combat
- **Player vs Player**: Bukan melawan AI!
- **Saling Tembak**: Kurangi health lawan
- **Health Bar**: 100 HP untuk setiap pemain
- **Round System**: Best of 5 rounds

### 🎯 Sistem Soal untuk Power-Up
Soal muncul secara random setiap ~10 detik:
- **Easy**: 🛡️ Shield (perlindungan)
- **Medium**: ⚡ Rapid Fire (tembakan cepat)
- **Hard**: 💥 Mega Shot (triple shot)

### 📊 Scoring
- **Kill**: +100 poin
- **Jawaban Benar**: +50 poin
- **Pemenang**: Yang paling banyak kills

---

## 🎮 Kontrol

### Player 1 (Pesawat Biru - Kiri)
| Tombol | Fungsi |
|--------|--------|
| W | Gerak ke atas |
| S | Gerak ke bawah |
| A | Gerak ke kiri |
| D | Gerak ke kanan |
| **Shift** | **Tembak** |

### Player 2 (Pesawat Merah - Kanan)
| Tombol | Fungsi |
|--------|--------|
| ⬆️ Arrow Up | Gerak ke atas |
| ⬇️ Arrow Down | Gerak ke bawah |
| ⬅️ Arrow Left | Gerak ke kiri |
| ➡️ Arrow Right | Gerak ke kanan |
| **Enter** | **Tembak** |

---

## 🎯 Cara Bermain

### 1. Start Game
- Pilih "2 Player Jet Duel" dari menu Games
- Game langsung dimulai dengan Round 1

### 2. Kontrol Pesawat
- **Player 1**: Gunakan WASD untuk gerak
- **Player 2**: Gunakan Arrow Keys untuk gerak
- Pesawat bisa bergerak bebas di area masing-masing

### 3. Tembak Lawan
- **Player 1**: Tekan **Shift** untuk tembak
- **Player 2**: Tekan **Enter** untuk tembak
- Peluru bergerak horizontal
- Kena lawan = kurangi health

### 4. Soal Power-Up
- Soal muncul random untuk salah satu pemain
- Modal pause game
- Jawab benar = dapat power-up
- Jawab salah/skip = tidak dapat apa-apa

### 5. Menang Round
- Hancurkan pesawat lawan (health 0)
- Pemenang round dapat +1 kill
- Round baru dimulai otomatis

### 6. Pemenang Game
- Best of 5 rounds
- Yang paling banyak kills = pemenang
- Jika seri = draw

---

## 🛡️ Power-Ups

### Shield (🛡️)
- **Reward dari**: Soal Easy
- **Efek**: Kebal dari tembakan
- **Durasi**: 15 detik
- **Visual**: Border cyan di sekitar jet

### Rapid Fire (⚡)
- **Reward dari**: Soal Medium
- **Efek**: Cooldown tembakan lebih cepat
- **Durasi**: 15 detik
- **Visual**: Border kuning di sekitar jet

### Mega Shot (💥)
- **Reward dari**: Soal Hard
- **Efek**: Triple shot sekaligus
- **Durasi**: 15 detik
- **Visual**: Border magenta di sekitar jet

---

## 🎨 Visual & Efek

### Grafis Jet
- **Body**: Bentuk aerodinamis
- **Wings**: Sayap di atas dan bawah
- **Cockpit**: Lingkaran putih di depan
- **Engine**: Glow oranye di belakang
- **Warna**: Biru (P1) vs Merah (P2)

### Efek Visual
- ⭐ Bintang scrolling background
- 💥 Partikel saat kena tembakan
- 🔥 Ledakan besar saat pesawat hancur
- ✨ Glow effect pada peluru
- 🎯 Health bar real-time
- 🌟 Power-up indicator

### Animasi
- Jet bergerak smooth
- Peluru dengan shadow glow
- Partikel explosion
- Ring explosion effect
- Power-up border pulse

---

## 📊 HUD Display

### Player 1 (Kiri Atas)
- Nama: "Player 1 (WASD+Shift)"
- Health bar dengan warna dinamis
- Health number: 100/100
- Score

### Player 2 (Kanan Atas)
- Nama: "Player 2 (Arrows+Enter)"
- Health bar dengan warna dinamis
- Health number: 100/100
- Score

### Center Top
- Round number: "Round 1/5"

### Center Line
- Garis putih putus-putus sebagai pembatas area

---

## 💡 Strategi Bermain

### Untuk Player 1
1. **Kontrol Area Kiri**: Jangan terlalu maju ke tengah
2. **Dodge Vertical**: Gerak atas-bawah untuk hindari peluru
3. **Tembak Terus**: Shift mudah dijangkau
4. **Jawab Soal**: Jangan skip, power-up sangat membantu

### Untuk Player 2
1. **Kontrol Area Kanan**: Pertahankan posisi
2. **Manfaatkan Enter**: Tembak sambil gerak
3. **Prediksi Gerakan**: Tembak ke arah lawan akan bergerak
4. **Power-Up Priority**: Jawab soal hard untuk Mega Shot

### Strategi Umum
- ✅ Jangan diam di satu tempat
- ✅ Gerak zigzag untuk hindari peluru
- ✅ Gunakan power-up dengan bijak
- ✅ Fokus saat ada soal
- ✅ Komunikasi dengan lawan (friendly competition!)

---

## 🏆 Sistem Round

### Round Flow
1. **Round Start**: Kedua jet spawn di posisi awal
2. **Combat**: Saling tembak hingga ada yang mati
3. **Round End**: Pemenang dapat +1 kill
4. **Next Round**: Auto start setelah 3 detik
5. **Repeat**: Sampai round 5

### Kondisi Menang
- **Kills**: Yang paling banyak hancurkan lawan
- **Score**: Sebagai tiebreaker jika kills sama
- **Seri**: Jika kills dan score sama

---

## 📈 Scoring System

### Poin dari Combat
- **Kill Enemy**: +100 poin
- **Damage Dealt**: Tidak ada poin (hanya kurangi health)

### Poin dari Soal
- **Jawaban Benar**: +50 poin
- **Jawaban Salah**: 0 poin
- **Skip**: 0 poin

### Total Score
- Akumulasi dari kills + jawaban benar
- Ditampilkan di health bar
- Digunakan untuk tiebreaker

---

## 🎓 Contoh Soal

### Easy (Shield)
```
Soal: 2x + 5 = 13
Jawaban: x = 4
Reward: 🛡️ Shield
```

### Medium (Rapid Fire)
```
Soal: 3x - 7 = 8
Jawaban: x = 5
Reward: ⚡ Rapid Fire
```

### Hard (Mega Shot)
```
Soal: 5x - 2x + 3 = 18
Jawaban: x = 5
Reward: 💥 Mega Shot
```

---

## 🔧 Tips & Tricks

### Combat Tips
1. **Aim Ahead**: Tembak ke depan gerakan lawan
2. **Strafe**: Gerak samping sambil tembak
3. **Cover**: Gunakan area sendiri sebagai "safe zone"
4. **Cooldown**: Tunggu cooldown sebelum tembak lagi

### Power-Up Tips
1. **Shield**: Gunakan saat health rendah
2. **Rapid Fire**: Gunakan untuk offensive push
3. **Mega Shot**: Gunakan untuk burst damage
4. **Timing**: Aktifkan power-up di saat yang tepat

### Soal Tips
1. **Cepat Jawab**: Game pause, tapi lawan bisa lihat
2. **Akurat**: Salah = tidak dapat power-up
3. **Prioritas**: Soal hard = power-up terbaik
4. **Jangan Skip**: Setiap power-up berguna

---

## 🐛 Troubleshooting

### Kontrol tidak jalan?
- ✅ Klik pada canvas terlebih dahulu
- ✅ Pastikan Caps Lock off
- ✅ Coba tekan tombol lagi

### Peluru tidak keluar?
- ✅ Tunggu cooldown selesai
- ✅ Pastikan game active (tidak pause)
- ✅ Tekan tombol tembak dengan benar

### Soal tidak muncul?
- ✅ Soal muncul random setiap ~10 detik
- ✅ Tunggu saja, akan muncul otomatis
- ✅ Tidak setiap round ada soal

### Game lag?
- ✅ Close aplikasi lain
- ✅ Gunakan browser modern
- ✅ Refresh halaman

---

## 📊 Statistik Game

### Gameplay
- **Players**: 2 (local multiplayer)
- **Rounds**: 5 rounds
- **Health**: 100 HP per player
- **Damage**: 10 per bullet (15 dengan Mega Shot)
- **Power-Up Duration**: 15 detik

### Canvas
- **Size**: 900x600 px
- **FPS**: 60 target
- **Stars**: 150 background stars
- **Particles**: Dynamic

---

## 🎯 Tujuan Pembelajaran

### Matematika
1. Menyelesaikan persamaan linear cepat
2. Berpikir di bawah tekanan
3. Aplikasi konsep dalam game

### Soft Skills
1. Kompetisi sehat
2. Sportivitas
3. Koordinasi mata-tangan
4. Decision making cepat
5. Multitasking

---

## 🎉 Kesimpulan

Game **2 Player Jet Duel** adalah:
- ✈️ **PvP Combat** yang seru
- 🎮 **2 Player Local** untuk main bareng teman
- 🎯 **Soal Matematika** untuk power-up
- 🎨 **Grafis Jet Realistis** yang keren
- 🏆 **Round System** yang kompetitif

---

## 📞 Support

Jika ada masalah:
1. Baca dokumentasi ini
2. Cek troubleshooting
3. Review source code
4. Hubungi developer

---

**Selamat Bertarung!** ✈️💥

*"May the best pilot win!"*

---

**Version**: 1.0.0  
**Game Type**: 2 Player PvP  
**Platform**: Web Browser  
**Controls**: Keyboard (WASD + Shift vs Arrows + Enter)
