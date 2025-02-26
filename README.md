# 📱 App Walisantri

**App Walisantri** adalah aplikasi mobile berbasis **Flutter** yang dirancang untuk membantu wali santri dalam memantau aktivitas dan informasi akademik santri di Pondok Pesantren Al-Maruf. Aplikasi ini terintegrasi dengan sistem backend berbasis **CodeIgniter**, serta mendukung **Midtrans** sebagai gateway pembayaran.

---

## ✨ Fitur Utama

✅ **Autentikasi Pengguna** - Login dan registrasi wali santri menggunakan akun terdaftar.  
✅ **Dashboard Wali Santri** - Tampilan informasi penting seperti data santri, pembayaran, dan notifikasi.  
✅ **Manajemen Pembayaran** - Melihat riwayat pembayaran, tagihan santri, dan melakukan pembayaran online dengan **Midtrans**.  
✅ **Riwayat Pelanggaran & Prestasi** - Memantau pelanggaran dan pencapaian santri di pondok pesantren.  
✅ **Jadwal Kegiatan** - Menampilkan jadwal harian santri, termasuk kegiatan pesantren dan akademik.  
✅ **Notifikasi Real-time** - Menggunakan **Firebase Cloud Messaging (FCM)** untuk pemberitahuan pembayaran dan pengingat.  
✅ **Absensi Santri** - Integrasi dengan **Fingerspot Premiere Series** untuk melihat kehadiran santri.  
✅ **Multi-bahasa** - Mendukung Bahasa Indonesia dan beberapa bahasa lainnya.  

---

## 🚀 Teknologi yang Digunakan

🔹 **Flutter** - Framework untuk membangun aplikasi mobile cross-platform (Android & iOS).  
🔹 **Dart** - Bahasa pemrograman utama untuk Flutter.  
🔹 **CodeIgniter (PHP 5.6)** - Backend untuk mengelola data santri dan transaksi pembayaran.  
🔹 **Midtrans** - Payment gateway untuk memproses transaksi pembayaran santri.  
🔹 **Firebase Cloud Messaging (FCM)** - Untuk mengirim notifikasi ke wali santri.  
🔹 **MySQL** - Database utama untuk menyimpan data santri dan transaksi.  
🔹 **Fingerspot Premiere Series** - Untuk integrasi sistem absensi santri.  

---

## 📦 Instalasi dan Konfigurasi

### 1️⃣ Clone Repository
```sh
git clone https://github.com/ahmadbusrooo/app_walisantri.git
cd app_walisantri
```

### 2️⃣ Install Dependencies
```sh
flutter pub get
```

### 3️⃣ Jalankan Aplikasi
```sh
flutter run
```
Pastikan emulator atau perangkat fisik terhubung sebelum menjalankan aplikasi.

### 4️⃣ Konfigurasi Backend
Backend menggunakan **CodeIgniter** yang berjalan di server dengan **PHP 5.6**. Pastikan konfigurasi berikut sudah disesuaikan:
- **Database:** Sesuaikan konfigurasi database di `application/config/database.php`.
- **Midtrans API Key:** Simpan di `application/config/payment.php`.
- **FCM Configuration:** Tambahkan server key FCM di backend untuk mengaktifkan notifikasi.

---

## 📷 Tampilan Aplikasi
> Segera ditambahkan (screenshots dan demo UI)

---

## 🤝 Kontribusi
Kami menerima kontribusi dari siapa saja yang ingin membantu pengembangan aplikasi ini. Silakan fork repository ini dan buat pull request!

1️⃣ **Fork Repository**  
2️⃣ **Buat Branch Baru** (`git checkout -b feature-nama-fitur`)  
3️⃣ **Commit Perubahan** (`git commit -m 'Menambahkan fitur baru'`)  
4️⃣ **Push ke GitHub** (`git push origin feature-nama-fitur`)  
5️⃣ **Buat Pull Request** dari GitHub

---

## 🛠️ Pengembang
👨‍💻 **Ahmad Busro Mustofa** – *Lead Developer*  
📧 **Email:** busromuz200206@gmail.com  
🔗 **GitHub:** [@ahmadbusrooo](https://github.com/ahmadbusrooo)

Jika ada pertanyaan atau masukan, jangan ragu untuk menghubungi saya! 😊

---

## 📜 Lisensi
Aplikasi ini menggunakan lisensi **MIT License**. Silakan gunakan dan kembangkan dengan bebas, tetapi tetap sertakan atribusi kepada pengembang asli.

```plaintext
MIT License
Copyright (c) 2025 Ahmad Busro
```

---

🚀 **Terima kasih telah menggunakan App Walisantri!** Semoga bermanfaat bagi wali santri dalam memantau perkembangan anak-anaknya di pesantren. 🙏
