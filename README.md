# Dice Roller App

| Nama  | NRP         |
|--------|------------|
| Muhammad Hafidz Harridil Mahali | 5025221030 |

## Deskripsi
Dice Roller App adalah aplikasi Android sederhana yang dibuat menggunakan Jetpack Compose. Aplikasi ini memungkinkan user untuk me-roll dadu secara acak dengan menekan sebuah button. Hasil dari roll akan ditampilkan dalam bentuk gambar dadu yang sesuai.

## Fitur Utama
- Menampilkan gambar dadu berdasarkan hasil yang di-roll.
- Tombol interaktif untuk me-roll dadu secara acak.
- Menggunakan Jetpack Compose untuk UI yang lebih modern dan deklaratif.

## Struktur Kode
1. **MainActivity.kt**
   - Menginisialisasi aplikasi dan menampilkan `DiceRollerApp` sebagai tampilan utama.

2. **DiceRollerApp()**
   - Memanggil `DiceWithImageAndButton()` sebagai komponen utama aplikasi.

3. **DiceWithImageAndButton()**
   - Menggunakan `remember { mutableIntStateOf(1) }` untuk menyimpan hasil roll dadu.
   - Menggunakan `when` untuk menentukan gambar dadu yang sesuai dengan hasil roll.
   - Menampilkan gambar dadu dan tombol untuk melakukan roll dadu.
   - Saat tombol ditekan, angka acak antara 1 hingga 6 akan dihasilkan dan diperbarui di UI.

4. **DiceRollerAppPreview()**
   - Menyediakan preview UI di Android Studio.

## Teknologi yang Digunakan
- **Kotlin**: Bahasa pemrograman utama.
- **Jetpack Compose**: Framework untuk membangun UI deklaratif.
- **Material 3**: Untuk elemen UI seperti tombol dan tema aplikasi.

## Cara Menjalankan
1. Pastikan telah menginstal Android Studio.
2. Buka proyek ini di Android Studio.
3. Jalankan aplikasi pada emulator atau perangkat fisik.
4. Tekan tombol "Roll" untuk me-roll dadu.

