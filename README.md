# tugas3

A new Flutter project.

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.


 Penjelasan tiap bagian penting kode

 1. chat_screen.dart
Imports: Mengimpor flutter/material.dart untuk menggunakan widget dan elemen UI dari Flutter.
ChatScreen Class: adalah widget stateless yang menampilkan layar chat.
Scaffold: Menyediakan struktur dasar untuk halaman, termasuk AppBar dan body.
AppBar: Menampilkan judul "Chat Screen" dengan warna latar belakang pink.
Body: Menampilkan teks sederhana di tengah layar yang menyambut pengguna.
2. profile_screen.dart
Imports: Seperti sebelumnya, menggunakan flutter/material.dart.
ProfileScreen Class: Kelas ini juga merupakan widget stateless yang menampilkan layar profil.
Scaffold: Menyediakan layout dasar yang sama seperti di ChatScreen.
AppBar: Menampilkan judul "Profile Screen" dengan warna latar belakang yang konsisten.
Body: Menampilkan pesan sambutan di tengah layar, menginformasikan pengguna tentang profil mereka
3. settings_screen.dart
Imports: Mengimpor paket Flutter untuk penggunaan UI.
SettingsScreen Class: Kelas ini adalah widget stateless yang menampilkan layar pengaturan.
Scaffold: Struktur layout yang sama seperti yang digunakan sebelumnya.
AppBar: Judul yang mencerminkan fungsi layar, "Settings Screen".
Body: Menampilkan teks yang menyambut pengguna ke layar pengaturan.
4. login_screen.dart
Imports:Mengimpor pustaka yang diperlukan, termasuk Flutter untuk UI dan shared_preferences untuk menyimpan data lokal.
LoginScreen Class:Kelas LoginScreen adalah StatefulWidget yang memungkinkan pengelolaan input pengguna (username dan password).
_LoginScreenState Class:Menggunakan TextEditingController untuk mengelola input dari username dan password.
_saveUser Method:Menyimpan username pengguna menggunakan SharedPreferences setelah login berhasil.
_login Method:Memeriksa validitas username dan password. Jika sesuai, menyimpan username dan mengalihkan ke MainScreen. Jika tidak, memanggil dialog error.
_showErrorDialog Method:Menampilkan dialog jika login gagal, memberitahukan pengguna tentang kesalahan.
build Method:Mengatur tampilan halaman login menggunakan Scaffold dan Stack. Termasuk menambahkan form login yang berisi ikon, kolom input, dan tombol login.
_buildTextField Method:Membuat kolom input untuk username dan password dengan desain yang konsisten.

![login](login.png)
![halamanutama](main_screen.png)
![profile](profile.png)
![chat](chat.png)
![setting](settings.png)
