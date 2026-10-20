# Analisis Komparatif Platform (Web, Desktop, Mobile)

## Tabel Komparatif Platform

| Aspek | Web | Desktop | Mobile |
| --- | --- | --- | --- |
| **Bahasa Utama** | HTML, CSS, JavaScript, TypeScript (Front-end); Python, Node.js, PHP, Java (Back-end) | C++, C#, Java (Swing/JavaFX), Python (PyQt), JavaScript/TypeScript (Electron) | Kotlin, Java (Android Native); Swift (iOS Native); Dart (Flutter); JS/TS (React Native) |
| **Arsitektur** | Client-Server, Single Page Application (SPA), Multi-Page Application (MPA) | Monolithic, Standalone Architecture, Client-Server Desktop | Mobile Client-Server, Microservices Architecture via REST API / GraphQL |
| **Cara Distribusi** | Hosting di Web Server, diakses pengguna melalui Browser via URL/Domain | Installer Executable (`.exe`, `.msi` di Windows; `.dmg` di macOS; `.deb` di Linux) | Official App Store (Google Play Store, Apple App Store) atau *sideloading* (`.apk`, `.ipa`) |
| **Keunggulan** | Multiplatform secara instan tanpa instalasi, pembaruan aplikasi terpusat secara real-time, hemat penyimpanan lokal | Performa komputasi sangat tinggi, akses penuh ke hardware (CPU, GPU, Storage), dapat berjalan penuh secara *offline* | Portabilitas tinggi, memanfaatkan sensor fisik perangkat (GPS, Kamera, Biometrik, Gyroscope), fitur *Push Notification* |
| **Keterbatasan** | Ketergantungan penuh pada koneksi internet dan browser, akses ke komponen hardware lokal dibatasi oleh browser | Proses instalasi dan *update* dilakukan per perangkat, perbedaan kompilasi untuk tiap sistem operating system (Windows/Mac/Linux) | Resource perangkat terbatas (kapasitas baterai & RAM), batasan ukuran layar, masalah fragmentasi perangkat |
| **Contoh Aplikasi** | Figma Web, Google Docs, Canva, Spotify Web | Visual Studio Code, NetBeans IDE, Adobe Photoshop, AutoCAD | WhatsApp, Instagram, Gojek, Tokopedia |

---

## Kesimpulan Analisis

Berdasarkan hasil analisis komparatif di atas, ketiga platform memiliki karakteristik, keunggulan, serta batasan yang saling melengkapi sesuai skenario penggunaannya:

1. **Platform Web** sangat unggul dalam hal akseabilitas dan fleksibilitas *cross-platform* tanpa hambatan instalasi, menjadikannya pilihan utama untuk sistem informasi, media sosial, dan layanan berbasis portal.
2. **Platform Desktop** menjadi pilihan mutlak apabila aplikasi membutuhkan komputasi berat, pemrosesan grafis tinggi, serta integrasi mendalam dengan perangkat keras lokal yang dapat beroperasi tanpa jaringan internet.
3. **Platform Mobile** mendominasi dari segi mobilitas dan interaksi personal pengguna melalui pemanfaatan sensor fisik (*location-aware*, kamera, biometrik) serta *real-time engagement* via notifikasi.

Pemilihan platform pengembangan aplikasi harus disesuaikan dengan **kebutuhan performa, ketersediaan akses keras (hardware), perilaku pengguna (*user behavior*), serta strategi distribusi** yang ingin dicapai oleh pengembang.

---

## Daftar Referensi
1. **Pressman, R. S., & Maxim, B. R.** (2019). *Software Engineering: A Practitioner's Approach* (9th ed.). McGraw-Hill Education.
2. **Oracle Documentation.** *Java Desktop Application Architecture & Swing/JavaFX Guide*. Diakses dari https://docs.oracle.com/
3. **Google Developers.** *Guide to Android Application Architecture*. Diakses dari https://developer.android.com/topic/architecture
4. **MDN Web Docs.** *Web Architecture and Core Web Technologies*. Diakses dari https://developer.mozilla.org/

---
## REFLEKSI

1. Platform yang Paling Menarik untuk Dipelajari
Dari ketiga platform yang dianalisis, platform Web adalah yang paling menarik bagi saya. Platform web memiliki keunggulan utama dalam hal fleksibilitas cross-platform tanpa mewajibkan pengguna melakukan instalasi aplikasi secara manual. Selain itu, perkembangan ekosistem JavaScript/TypeScript dan framework modern saat ini memungkinkan pengembangan antarmuka yang sangat interaktif, responsif, serta dapat diakses secara instan dari perangkat apa pun melalui browser.

2. Tantangan Terbesar Saat Setup Environment
Tantangan terbesar yang saya hadapi selama proses setup environment adalah melakukan navigasi direktori melalui terminal/CMD pada sistem Windows. Terutama ketika lokasi folder berada di dalam penyimpanan cloud (OneDrive) dan memiliki spasi pada nama foldernya, perintah cd sempat gagal menemukan path jika tidak dibungkus tanda petik ganda (" "). Selain itu, proses instalasi Android Studio memerlukan kapasitas penyimpanan serta kuota yang cukup besar untuk mengunduh komponen SDK pendukung.

3. Rencana Mengatasi Tantangan
Untuk mengatasi tantangan navigasi terminal, saya membiasakan diri menggunakan tanda petik ganda pada path ber-spasi atau memanfaatkan trik drag-and-drop folder langsung ke jendela terminal. Ke depannya, saya berencana memperdalam pemahaman perintah dasar CLI (Command Line Interface) dan mengelola kapasitas penyimpanan laptop secara berkala agar pengoperasian emulator serta SDK Android Studio dapat berjalan lancar.