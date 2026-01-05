# 🎮 Quick Test Guide - Fighter Jet Battle

## ✅ Cara Menguji Game

### 1. Buka Aplikasi
Aplikasi sudah dibuka di browser. Jika belum, buka:
```
file:///c:/Users/user/.gemini/antigravity/scratch/lms-matematika-smp/index.html
```

### 2. Navigasi ke Game
1. Klik menu **"Game Battle"** di sidebar (kiri)
   - Atau klik card "Game Battle" di halaman Beranda

2. Scroll ke bawah hingga menemukan card game:
   **"Fighter Jet Battle - Persamaan Linear"**
   - Icon: ✈️ (fighter jet)
   - Warna: Gradient ungu
   - Deskripsi: "🚀 Tembak musuh dengan menyelesaikan persamaan linear..."

3. Klik card atau tombol **"Mulai Battle"**

### 3. Game Akan Terbuka
- Modal game akan muncul
- Canvas game 800x600 px
- Background hitam dengan bintang
- Pesawat hijau di bawah
- HUD di atas (Lives, Score, Combo, Level)

### 4. Kontrol Game
- **Arrow Keys** (⬆️⬇️⬅️➡️): Gerakkan pesawat
- **Space**: Tembak peluru
- Pesawat harus bisa bergerak smooth
- Peluru kuning keluar saat tekan Space

### 5. Musuh Muncul
- Musuh spawn dari atas
- Warna hijau/kuning/merah
- Ada persamaan linear di musuh
- Health bar di atas musuh

### 6. Tembak Musuh
- Tembak musuh hingga health habis
- Musuh meledak dengan partikel
- Modal soal muncul (game pause)

### 7. Jawab Soal
- Modal menampilkan persamaan
- Input nilai x
- Klik "Jawab" atau Enter
- Feedback muncul (benar/salah)

### 8. Skor & Combo
- Benar: +100/200/300 poin + combo
- Salah: Combo reset
- Cek HUD untuk skor real-time

### 9. Power-Ups (Opsional)
- Lingkaran berwarna jatuh dari musuh
- Tangkap untuk power-up:
  - 🛡️ Shield (biru)
  - ⚡ Rapid Fire (orange)
  - ✨ Multi Shot (ungu)

### 10. Game Over
- Nyawa habis (3 lives)
- Tampil hasil:
  - Total skor
  - Level tercapai
  - Max combo
- Tombol "Main Lagi"

---

## 🐛 Troubleshooting

### Game tidak muncul di list
✅ Refresh browser (F12 → Console untuk cek error)
✅ Pastikan file game-fighter-jet.js sudah di-load
✅ Cek data.js ada game ID 9

### Canvas hitam/kosong
✅ Buka Console (F12)
✅ Cek error JavaScript
✅ Pastikan initFighterJetGame() terpanggil

### Kontrol tidak jalan
✅ Klik pada canvas terlebih dahulu
✅ Pastikan tidak ada input lain yang fokus
✅ Coba reload halaman

### Musuh tidak muncul
✅ Tunggu beberapa detik
✅ Cek console untuk error
✅ Pastikan fungsi createEnemy() berjalan

### Modal soal tidak muncul
✅ Cek apakah musuh benar-benar hancur
✅ Lihat console untuk error
✅ Pastikan showQuestionModal() terpanggil

---

## 📊 Checklist Testing

### Visual
- [ ] Canvas muncul dengan border hijau
- [ ] Background hitam dengan bintang
- [ ] Pesawat hijau terlihat
- [ ] HUD menampilkan info (Lives, Score, dll)

### Kontrol
- [ ] Arrow keys menggerakkan pesawat
- [ ] Space menembakkan peluru
- [ ] Pesawat tidak keluar dari canvas
- [ ] Peluru bergerak ke atas

### Gameplay
- [ ] Musuh spawn dari atas
- [ ] Musuh bergerak ke bawah
- [ ] Peluru mengenai musuh
- [ ] Health bar berkurang
- [ ] Musuh hancur dengan partikel

### Soal
- [ ] Modal muncul setelah musuh hancur
- [ ] Persamaan ditampilkan
- [ ] Input bisa diisi
- [ ] Jawaban bisa di-submit
- [ ] Feedback muncul (benar/salah)

### Skor
- [ ] Skor bertambah saat benar
- [ ] Combo naik saat benar berturut-turut
- [ ] Combo reset saat salah
- [ ] HUD update real-time

### Power-Up
- [ ] Power-up jatuh dari musuh
- [ ] Bisa ditangkap pesawat
- [ ] Efek power-up aktif
- [ ] Visual indicator muncul

### Game Over
- [ ] Nyawa berkurang saat kena tembakan
- [ ] Game over saat nyawa habis
- [ ] Hasil ditampilkan
- [ ] Tombol "Main Lagi" berfungsi

---

## 🎯 Expected Behavior

### Saat Game Start
```
✅ Canvas rendered
✅ Stars scrolling
✅ Player jet visible at bottom
✅ HUD showing: ❤️3 ⭐0 🔥x0 📊1
✅ Controls responsive
```

### Saat Bermain
```
✅ Enemies spawn every few seconds
✅ Bullets shoot when Space pressed
✅ Collision detection working
✅ Particles on explosion
✅ Modal appears on enemy defeat
```

### Saat Jawab Soal
```
✅ Game pauses
✅ Modal shows equation
✅ Can input answer
✅ Feedback shows result
✅ Score updates
✅ Game resumes
```

---

## 📝 Test Scenarios

### Scenario 1: Basic Gameplay
1. Start game
2. Move player with arrows
3. Shoot with Space
4. Hit enemy
5. Answer question correctly
6. Check score increased

### Scenario 2: Combo System
1. Answer 3 questions correctly in a row
2. Check combo = x3
3. Answer 1 question wrong
4. Check combo reset to x0

### Scenario 3: Power-Up
1. Destroy enemy
2. Collect power-up that drops
3. Check visual indicator
4. Use power-up ability
5. Wait for duration to end

### Scenario 4: Game Over
1. Get hit by enemy bullets 3 times
2. Check lives decrease
3. Lives reach 0
4. Game over screen appears
5. Click "Main Lagi"
6. Game restarts

---

## 🎮 Performance Check

### FPS
- Game should run smooth at ~60 FPS
- No lag when moving
- No stutter when shooting

### Memory
- No memory leaks
- Particles cleaned up properly
- Enemies removed when off-screen

### Responsiveness
- Input lag < 50ms
- Collision detection accurate
- Modal appears instantly

---

## ✅ Success Criteria

Game dianggap **BERHASIL** jika:

1. ✅ Bisa dibuka dari menu Games
2. ✅ Canvas ter-render dengan benar
3. ✅ Kontrol responsif (arrow + space)
4. ✅ Musuh spawn dan bergerak
5. ✅ Tembakan berfungsi
6. ✅ Collision detection akurat
7. ✅ Modal soal muncul
8. ✅ Jawaban bisa di-input dan di-submit
9. ✅ Skor bertambah dengan benar
10. ✅ Game over berfungsi
11. ✅ Bisa restart game

---

## 🚀 Quick Start

**Cara Tercepat Test:**

1. Buka browser → aplikasi sudah terbuka
2. Klik "Game Battle" di sidebar
3. Scroll → Cari "Fighter Jet Battle"
4. Klik "Mulai Battle"
5. Gunakan Arrow + Space
6. Tembak musuh → Jawab soal
7. Lihat skor naik!

---

**Happy Testing!** 🎮✨

Jika ada masalah, cek Console (F12) untuk error messages.
