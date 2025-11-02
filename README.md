# Codelabs AR Foundation

Repo ini berisi **hasil build aplikasi AR Mobile berbasis Unity**.
Aplikasi dkembangkan menggunakan **Unity + AR Foundation**, dengan dukungan **Google ARCore (Android)**.

---

## Tentang Aplikasi

Aplikasi ini memanfaatkan fitur **Augmented Reality (AR)** untuk menampilkan objek 3D di dunia nyata melalui kamera perangkat Android.
Fitur utama meliputi:
- Deteksi bidang datar (plane detection)
- Interaksi objek 3D dengan lingkungan nyata
- Tracking posisi real-time

---

## Cara Instalasi

1. **Download file APK** dari repository ini
   > Klik file `.apk` di atas --> pilih **Download**

2. **Pindahkan ke HP Android**

3. Aktifkan izin instalasi dari sumber tidak dikenal:
   > Pengaturan --> Keamanan --> Aktifkan *Install from Unknown Sources*

4. Jalankan file APK untuk menginstal aplikasi.

---

## Catatan

- File `.apk` disimpan menggunakan **Git LFS (Large File Storage)** karena ukuran apk melebihi 100MB.
  Jika ingin meng-clone repo ini, pastikan Git LFS sudah aktif di perangkatmu:
  ```bash
  git lfs install
  git clone https://github.com/drgnov-305/Codelabs-AR-Foundation.git
