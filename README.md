# Wardrobe Sense - Flutter Mobile App (Android & iOS)

Aplikasi AI Personal Stylist & Curated Fashion buatan lokal pengrajin (UMKM).

## Persyaratan:
1. Flutter SDK (>= 3.0.0)
2. Android Studio (untuk build APK Android) atau Xcode (untuk build iOS di Mac)

## Langkah Cepat Build APK Android:
```bash
# 1. Masuk ke folder project
cd wardrobe_sense

# 2. Ambil paket dependencies
flutter pub get

# 3. Jalankan di emulator atau HP Anda:
flutter run

# 4. Buat file APK Release untuk diinstall di HP Android:
flutter build apk --release
```
File APK yang dihasilkan akan berada di:
`build/app/outputs/flutter-apk/app-release.apk`

## Langkah Build iOS:
```bash
flutter build ipa --release
```
