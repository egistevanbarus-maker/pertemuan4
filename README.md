# Live Dashboard App

**Mahasiswa:** Egi Stevan Barus
**NIM:** 243303621266

## Deskripsi
Dashboard interaktif yang merespon input pengguna secara real-time. Aplikasi ini mengimplementasikan state management untuk sistem counter dan greeting form.

## Fitur
- [x] **Main Quest:** Sistem counter (+/-) dan greeting form dinamis.
- [x] **Side Quest (+25XP):** Validasi angka (tidak bisa < 0) dan fitur ganti warna background.

## Dokumentasi & Bukti
- **State Management:** Menggunakan `useState` untuk menyimpan `count`, `name`, dan `bgColor`.
- **Interaction Logic:** Input teks memiliki *two-way binding* dengan `onChangeText` untuk merespon sapaan secara langsung.
- **Screenshot:** (![alt text](<Screenshot 2026-05-02 111009.png>))

## Cara Menjalankan
1. Clone repo ini.
2. Jalankan `npm install`.
3. Jalankan `npx expo start` dan scan QR dengan Expo Go.