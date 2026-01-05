# 🚀 Panduan Cepat - MathLearn LMS

## Cara Menjalankan Website

### Metode 1: Buka Langsung di Browser
1. Buka File Explorer
2. Navigate ke folder: `C:\Users\user\.gemini\antigravity\scratch\lms-matematika-smp`
3. Double-click file `index.html`
4. Website akan terbuka di browser default Anda

### Metode 2: Drag & Drop
1. Buka browser (Chrome/Firefox/Edge)
2. Drag file `index.html` ke jendela browser
3. Website akan langsung terbuka

### Metode 3: Menggunakan Live Server (Recommended untuk Development)
Jika Anda memiliki VS Code:
1. Install extension "Live Server"
2. Klik kanan pada `index.html`
3. Pilih "Open with Live Server"

## 📝 Cara Menggunakan

### 1️⃣ Login
**Opsi A: Login dengan Google (Simulasi)**
- Klik tombol "Masuk dengan Google"
- Akan otomatis login sebagai "Siswa Matematika"

**Opsi B: Login Demo**
- Masukkan email apa saja (contoh: `siswa@email.com`)
- Masukkan password apa saja (contoh: `123456`)
- Klik "Masuk Demo"

### 2️⃣ Jelajahi Beranda
- Lihat statistik pembelajaran
- Klik quick access untuk langsung ke fitur
- Cek progress pembelajaran Anda
- Baca pengumuman terbaru
- Dapatkan motivasi dari quote matematika

### 3️⃣ Pelajari Materi
1. Klik menu "Materi" di navigasi
2. Pilih salah satu dari 6 bab:
   - Bilangan Bulat
   - Aljabar
   - Persamaan Linear
   - Perbandingan
   - Bangun Datar
   - Statistika
3. Klik "Pelajari Sekarang"
4. Jelajahi 4 tab:
   - **Ringkasan**: Materi lengkap
   - **Contoh Soal**: Soal dengan pembahasan
   - **Latihan**: Kuis interaktif
   - **Soal HOTS**: Soal tingkat tinggi

### 4️⃣ Tonton Video
1. Klik menu "Video" di navigasi
2. Pilih video yang ingin ditonton
3. Video YouTube akan langsung diputar
4. Klik "Tonton Sekarang" untuk menandai sudah ditonton

### 5️⃣ Main Game Battle
1. Klik menu "Game Battle" di navigasi
2. Pilih salah satu game (Battle Bilangan Bulat sudah fully functional)
3. Klik "Mulai Battle"
4. Bermain dengan 2 pemain bergantian:
   - Pemain 1 menjawab soal
   - Pemain 2 menjawab soal
   - Ulangi sampai waktu habis (60 detik)
5. Lihat pemenangnya!

### 6️⃣ Kerjakan Kuis
1. Klik menu "Tugas & Kuis" di navigasi
2. Pilih kuis yang ingin dikerjakan
3. Klik "Mulai Kuis"
4. Jawab semua soal:
   - Pilih jawaban dengan klik opsi
   - Klik "Selanjutnya" untuk soal berikutnya
   - Perhatikan timer di pojok kanan atas
5. Setelah selesai, lihat hasil:
   - Nilai persentase
   - Jumlah benar/salah
   - Skor total
6. Klik "Lihat Pembahasan" untuk review detail

### 7️⃣ Fitur Tambahan

**Toggle Dark Mode**
- Klik ikon bulan/matahari di pojok kanan atas
- Website akan berubah ke mode gelap/terang

**Logout**
- Klik tombol logout (ikon sign-out) di pojok kanan atas
- Anda akan kembali ke halaman login

## 🎯 Tips & Trik

### Untuk Siswa
1. **Pelajari materi dulu** sebelum mengerjakan kuis
2. **Tonton video** untuk pemahaman lebih baik
3. **Kerjakan latihan interaktif** untuk latihan
4. **Coba game battle** untuk belajar sambil bermain
5. **Review pembahasan** jika ada jawaban salah

### Untuk Guru
1. Gunakan kuis untuk evaluasi pemahaman siswa
2. Pantau progress melalui sistem scoring
3. Manfaatkan soal HOTS untuk tantangan
4. Gunakan game untuk ice breaking
5. Tambahkan tugas custom sesuai kebutuhan

## 🐛 Troubleshooting

### Website tidak muncul dengan benar?
- Pastikan menggunakan browser modern (Chrome 90+, Firefox 88+, Edge 90+)
- Clear cache browser (Ctrl + Shift + Delete)
- Refresh halaman (F5 atau Ctrl + R)

### Video tidak muncul?
- Pastikan koneksi internet aktif
- YouTube harus bisa diakses
- Coba refresh halaman

### Data hilang setelah refresh?
- Data disimpan di localStorage browser
- Jangan clear browser data jika ingin menyimpan progress
- Gunakan browser yang sama untuk konsistensi

### Game tidak berfungsi?
- Pastikan JavaScript enabled di browser
- Coba refresh halaman
- Cek console browser (F12) untuk error

## 📊 Data yang Tersimpan

Website ini menyimpan data di browser Anda (localStorage):
- ✅ User session (email, nama)
- ✅ Video yang sudah ditonton
- ✅ Hasil kuis
- ✅ Jawaban tugas
- ✅ Preferensi tema (dark/light)

**Note**: Data akan hilang jika Anda clear browser data!

## 🎨 Kustomisasi

### Mengubah Warna
Edit file `styles/main.css`, bagian `:root`:
```css
:root {
    --primary-blue: #4F46E5;  /* Ubah warna utama */
    --secondary-purple: #7C3AED;  /* Ubah warna sekunder */
}
```

### Menambah Materi
Edit file `scripts/data.js`, tambahkan di array `materiData`:
```javascript
{
    id: 7,
    title: "Materi Baru",
    icon: "fa-icon-name",
    color: "linear-gradient(...)",
    // ... dst
}
```

### Menambah Video
Edit file `scripts/data.js`, tambahkan di array `videoData`:
```javascript
{
    id: 9,
    title: "Video Baru",
    category: "Kategori",
    youtubeId: "VIDEO_ID",
    // ... dst
}
```

### Menambah Kuis
Edit file `scripts/data.js`, tambahkan di array `tugasData`:
```javascript
{
    id: 7,
    title: "Kuis Baru",
    type: "kuis",
    soal: [
        {
            pertanyaan: "...",
            pilihan: ["A", "B", "C", "D"],
            jawaban: "A",
            pembahasan: "..."
        }
    ]
}
```

## 📞 Bantuan

Jika ada pertanyaan atau masalah:
1. Baca dokumentasi lengkap di `README.md`
2. Cek troubleshooting di atas
3. Hubungi administrator

---

**Selamat Belajar! 🎓**

*MathLearn LMS - Belajar Matematika Jadi Lebih Seru!*
