# Komangema UTS

Aplikasi Flutter sederhana untuk simulasi login toko kue. Aplikasi ini memiliki halaman login, lupa password, dan dashboard yang menampilkan daftar produk kue dummy.

## Fitur

- Login dengan email dan password hardcoded.
- Validasi email dan password pada halaman login.
- Toggle show/hide password.
- Loading indicator saat proses login dan reset password.
- Snackbar untuk pesan sukses dan error.
- Halaman forgot password dengan validasi email.
- Dashboard dengan daftar produk kue menggunakan `ListView.builder`.
- AppBar dan Drawer pada dashboard.
- Logout dengan `Navigator.pushAndRemoveUntil` agar user tidak bisa kembali ke dashboard lewat tombol back.

## Akun Test

Email:

```text
ema@gmail.com
```

Password:

```text
password123
```

## Cara Menjalankan Aplikasi

1. Ambil dependency Flutter:

```bash
flutter pub get
```

2. Jalankan aplikasi:

```bash
flutter run
```

## Screenshot

### Login

![Login Screen](docs/screenshots/login.svg)

### Forgot Password

![Forgot Password Screen](docs/screenshots/forgot-password.svg)

### Dashboard

![Dashboard Screen](docs/screenshots/dashboard.svg)

## Package yang Digunakan

- `flutter` dari Flutter SDK.
- `cupertino_icons`.
- `flutter_test` untuk kebutuhan testing bawaan Flutter.
- `flutter_lints` untuk aturan linting.
