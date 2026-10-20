# Analisis Komparatif Platform (Web, Desktop, Mobile)

| Aspek | Web | Desktop | Mobile |
| --- | --- | --- | --- |
| **Bahasa Utama** | HTML, CSS, JavaScript, TypeScript, PHP | C++, C#, Java, Python, Swift | Java, Kotlin, Swift, Dart (Flutter), JavaScript (React Native) |
| **Arsitektur** | Client-Server (Browser-Server Architecture) | Standalone / Client-Server / Monolithic | Mobile Client-Server Architecture |
| **Cara Distribusi** | Diakses langsung melalui web browser via URL | Installer executable (`.exe`, `.msi`, `.dmg`, `.pkg`) | App Store (Google Play Store, Apple App Store, APK) |
| **Keunggulan** | Akses instan multiplatform tanpa instalasi, update otomatis terpusat | Performa tinggi, akses penuh ke hardware/GPU lokal, bisa berjalan offline | Portabel, akses fitur sensor hp (GPS, kamera, biometrik), notifikasi push |
| **Keterbatasan** | Sangat tergantung koneksi internet, akses hardware perangkat terbatas | Memerlukan instalasi manual, update lebih rumit, keterikatan OS | Terbatas ukuran layar, manajemen memori/baterai ketat, fragmentasi OS |
| **Contoh Aplikasi** | Figma Web, Canva, Google Docs | Visual Studio Code, NetBeans IDE, Adobe Photoshop | WhatsApp, Gojek, Instagram |

## Referensi
1. **Mozilla Developer Network (MDN).** *Web architecture and core web technologies guide*. https://developer.mozilla.org/
2. **Android Developers.** *Guide to app architecture & mobile engineering*. https://developer.android.com/topic/architecture
3. **Microsoft Learn.** *Desktop application development documentation & architectural patterns*. https://learn.microsoft.com/




---

## Bagian 3: Refleksi

### 1. Platform yang Paling Menarik untuk Dipelajari
Dari ketiga platform yang dianalisis, platform **Web** merupakan yang paling menarik bagi saya. Keunggulan utama platform web terletak pada kemudahan aksesibilitasnya yang tidak memerlukan proses instalasi oleh pengguna akhir, serta kemudahan dalam melakukan pembaruan aplikasi secara terpusat. Selain itu, perkembangan ekosistem JavaScript/TypeScript dan *framework* modern saat ini memungkinkan pembuatan antarmuka web yang sangat interaktif dan responsif di berbagai ukuran perangkat.

### 2. Tantangan Terbesar Saat Setup Environment
Tantangan terbesar yang saya hadapi saat proses *setup environment* adalah melakukan navigasi direktori melalui terminal/CMD pada sistem operasi Windows, terutama ketika direktori kerja berada di dalam folder *cloud storage* (OneDrive) dan memiliki spasi pada nama foldernya. Hal ini sempat menyebabkan perintah `cd` tidak menemukan *path* direktori yang dituju jika tidak ditangani dengan tanda petik ganda (`" "`).

### 3. Rencana Mengatasi Tantangan
Untuk mengatasi tantangan tersebut, saya belajar menggunakan kutip ganda pada setiap *path* direktori yang memiliki spasi, atau menggunakan trik *drag and drop* folder langsung ke jendela terminal. Ke depannya, saya juga berencana untuk memperdalam pemahaman mengenai perintah-perintah dasar CLI (*Command Line Interface*) serta konfigurasi *environment variables* agar proses pengembangan perangkat lunak dapat berjalan lebih efisien.