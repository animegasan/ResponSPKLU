# Respon SPKLU

<p align="center"> <img src="https://raw.githubusercontent.com/animegasan/ResponSPKLU/refs/heads/master/src/icon.png" width="300"> </p>

Respon SPKLU (REStart Power ON - SPKLU) adalah solusi terintegrasi untuk aplikasi Stasiun Pengisian Kendaraan Listrik Umum (SPKLU), dirancang untuk me-restart sumber daya TR (Trafo) dari jarak jauh. Perangkat ini bertindak sebagai respons pertama terhadap gangguan akibat jaringan komunikasi yang tidak stabil.

Aplikasi ini memungkinkan operator untuk mengirim perintah restart dan memantau status SPKLU secara real-time melalui MQTT.

## 🚀 | Fitur  
✅ Mengirim perintah ke SPKLU melalui MQTT.  
✅ Menampilkan daftar SPKLU yang telah dikonfigurasi.  
✅ Menyimpan konfigurasi broker MQTT untuk komunikasi yang stabil.  
✅ Menampilkan status koneksi SPKLU secara real-time.  
✅ Menambahkan daftar SPKLU dengan input manual atau scan QR.  
✅ Melihat informasi perangkat dengan scan QR.  
✅ Download database dalam format CSV.  
✅ Upload database dalam format CSV.

## 📋 | Persyaratan  
- Android 7.0 (Nougat) atau lebih baru  
- Koneksi internet aktif  
- Konfigurasi broker MQTT yang valid  

## 📥 | Instalasi  
1. Unduh APK dari [Releases](https://github.com/username/respon-spklu/releases).  
2. Izinkan pemasangan dari sumber tidak dikenal jika diminta.  
3. Instal aplikasi seperti biasa di perangkat Android Anda.  

## ⚙️ | Pengaturan Respon SPKLU  

Untuk menggunakan Respon SPKLU, silakan masukkan konfigurasi yang diberikan oleh admin.  

### Langkah-langkah:  
1. Buka file konfigurasi yang diberikan oleh admin.  
2. Klik kanan pada file tersebut, lalu pilih Edit dengan Notepad.  
   ![image](https://github.com/user-attachments/assets/5097a3c6-6eeb-4c86-83e6-3eb7ca0ac5b4)  
3. Salin informasi berikut dari file konfigurasi:  
   - Address → Masukkan ke Broker URL  
   - Port → Masukkan ke Port  
   - Username → Masukkan ke Username  
   - Password → Masukkan ke Password  
4. Masukkan data tersebut pada pengaturan aplikasi Respon SPKLU.  
   ![image](https://github.com/user-attachments/assets/6b1b8c88-fc8e-489a-a4bf-548294c77263)  

Setelah konfigurasi selesai, aplikasi akan terhubung ke broker MQTT sesuai pengaturan yang diberikan. 🚀   

## 📜 | Lisensi  
Proyek ini menggunakan lisensi MIT. Silakan lihat file [LICENSE](LICENSE) untuk detail lebih lanjut.  
