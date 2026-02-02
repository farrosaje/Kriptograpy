<h1 align="center">🔐 SISTEM KRIPTOGRAFI CAESAR CIPHER</h1> <img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">
📖 Deskripsi Proyek

Proyek ini merupakan sistem kriptografi klasik Caesar Cipher berbasis bahasa pemrograman Python yang digunakan untuk mengamankan pesan teks dengan metode pergeseran karakter (shift).

Caesar Cipher bekerja dengan cara:

Menggeser huruf alfabet sejauh nilai tertentu (0–25)

Huruf besar dan kecil diproses secara terpisah

Angka, spasi, dan simbol tidak diubah

Sistem ini dilengkapi dengan fitur:

Enkripsi (mengunci pesan)

Dekripsi brute-force (membuka pesan tanpa mengetahui kunci)

Cocok digunakan untuk:

Pembelajaran kriptografi dasar

Tugas sekolah/kuliah

Simulasi keamanan data teks

<h1 align="center">🎯 Fitur Utama</h1> <img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">
✨ Fitur Utama

📌 1. ✅ Enkripsi Caesar Cipher
└─ Menggeser huruf alfabet berdasarkan nilai shift

📌 2. ✅ Dekripsi Brute-Force (0–25)
└─ Membuka pesan tanpa mengetahui kunci awal

📌 3. ✅ Mendukung Huruf Besar & Kecil
└─ A–Z dan a–z diproses secara terpisah

📌 4. ✅ Angka Tidak Berubah
└─ Menjaga keaslian data numerik

📌 5. ✅ Spasi Tetap Dipertahankan
└─ Struktur kalimat tetap terbaca

📌 6. ✅ Simbol Aman & Tidak Rusak
└─ Karakter khusus tidak dimodifikasi

📌 7. ✅ Input Dinamis dari User
└─ Shift dan teks diinput secara manual

📌 8. ✅ Menu Interaktif
└─ Pilihan Enkripsi, Dekripsi, atau Exit

📌 9. ✅ Cocok untuk Edukasi Kriptografi
└─ Mudah dipahami untuk pemula

<h1 align="center">⚙️ Cara Kerja Sistem</h1>
🔄 Alur Enkripsi

User memilih menu Encryption

User memasukkan:

Nilai shift (0–25)

Plain text

Program membaca karakter satu per satu

Jika huruf:

Dicari indeks alfabet

Digeser sesuai nilai shift

Jika angka/spasi/simbol:

Langsung disalin

Hasil ditampilkan sebagai Cipher Text

📌 Rumus Enkripsi:

C = (P + Shift) mod 26

🔓 Alur Dekripsi (Brute Force)

User memilih menu Decryption

User memasukkan cipher text

Program mencoba semua shift dari 0–25

Setiap hasil ditampilkan

User menentukan teks yang benar

📌 Rumus Dekripsi:

P = (C - Shift) mod 26

<h1 align="center">📂 Struktur Program</h1>
Fungsi	Deskripsi
caesar_encryption()	Proses penguncian pesan
caesar_decryption()	Proses pembukaan pesan (brute-force)
caesar_cipher()	Menu utama sistem
<h1 align="center">📌 Contoh Penggunaan</h1>
🔐 Enkripsi

Input:

Shift : 3
Text  : HELLO World


Output:

KHOOR Zruog

🔓 Dekripsi
Shift 3 : HELLO World
Shift 4 : GDKKN Vnqkc
...

<h1 align="center">⚠️ Catatan & Keterbatasan</h1>

⚠️ Caesar Cipher tidak aman untuk sistem nyata
⚠️ Mudah dipecahkan dengan brute-force
⚠️ Digunakan hanya untuk edukasi dan simulasi

<h1 align="center">📚 Kesimpulan</h1>

Sistem ini merupakan implementasi kriptografi klasik Caesar Cipher yang:

Sederhana

Mudah dipahami

Cocok untuk pembelajaran dasar keamanan data

Dengan sistem ini, pengguna dapat memahami:

Konsep enkripsi & dekripsi

Pergeseran alfabet

Kelemahan kriptografi klasik
