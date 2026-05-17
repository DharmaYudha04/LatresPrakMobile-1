# Flutter Space Responsi

Aplikasi Flutter untuk latihan responsi Praktikum PAM/TPM.

## Identitas Mahasiswa

- Nama: Anak Agung Ngurah Dharma Yudha
- NIM: 123230080
- Kelas: Praktikum Mobile IF-A


Fitur sesuai soal:
- Register dan login sederhana dengan `SharedPreferences`.
- Halaman utama berisi 3 menu: News, Blog, dan Report.
- AppBar halaman utama menampilkan username yang digunakan untuk login.
- Halaman list mengambil data dari Spaceflight News API.
- Halaman detail mengambil data berdasarkan id.
- Floating Action Button membuka halaman web asli dari item yang dipilih.

## Cara memakai di proyek Flutter yang sudah ada

1. Copy/timpa folder `lib/` ke proyek Flutter Anda.
2. Tambahkan dependency di `pubspec.yaml`:
   ```yaml
   http: ^1.2.2
   shared_preferences: ^2.3.2
   url_launcher: ^6.3.1
   ```
3. Tambahkan permission internet di `android/app/src/main/AndroidManifest.xml`:
   ```xml
   <uses-permission android:name="android.permission.INTERNET" />
   ```
4. Jalankan:
   ```bash
   flutter pub get
   flutter run
   ```

## Endpoint API

- News: `https://api.spaceflightnewsapi.net/v4/articles/`
- Blogs: `https://api.spaceflightnewsapi.net/v4/blogs/`
- Reports: `https://api.spaceflightnewsapi.net/v4/reports/`
