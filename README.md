# TIU 5 CBT Web App

## Fitur
- Portal peserta tanpa akun: nama + nomor/kelas opsional.
- 30 soal visual sesuai dokumen sumber.
- Pilihan jawaban 1–5.
- Penilaian otomatis di server; kunci tidak dikirim ke browser peserta.
- Panel admin untuk guspurwatihera@gmail.com.
- Pada akses admin pertama, email tersebut membuat password sendiri (minimal 8 karakter).
- Admin melihat nilai, jumlah benar, detail benar/salah, dan dapat menghapus hasil.

## Menjalankan di komputer
1. Instal Node.js 18+.
2. Buka terminal di folder ini.
3. Jalankan: npm install
4. Jalankan: npm start
5. Buka http://localhost:3000
6. Admin: http://localhost:3000/admin.html

## Hosting
Aplikasi memerlukan hosting Node.js yang memiliki penyimpanan persisten karena hasil peserta disimpan di data.json. Untuk produksi, set environment variable SESSION_SECRET dengan nilai acak yang panjang dan gunakan HTTPS.

Catatan: kunci jawaban mengikuti dokumen MASTER + KUNCI yang diberikan. Dokumen sumber menyatakan kunci tersebut merupakan transkripsi dan belum diverifikasi terhadap buku manual/kunci resmi.
