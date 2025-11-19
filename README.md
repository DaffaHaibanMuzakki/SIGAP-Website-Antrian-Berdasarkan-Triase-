# SIGAP-Website-Antrian-Berdasarkan-Triase-
Website ini merupakan prototype dimana diperuntukan untuk administrasi rumah sakit untuk mendata pasien berdasarkan kondisi triase pasien. Triase yang darurat
akan lebih diprioritaskan.

# Sistem yang digunakan
 1. Backend (Server) — Node.js + Express + Socket.IO
 2. Frontend (Client) — HTML + Bootstrap + EJS
 3. Penyimpanan Data — File JSON

# Fitur-fitur Website SIGAP:
1. Triase Otomatis
Sistem sendiri menentukan tingkat darurat pasien berdasarkan kondisi Spo2, denyut jantung, dan tekanan darah. Kondisi triase bisa diklasifikasikan sebagai berikut :
a. Triase Merah
- SpO₂ di bawah 90% → oksigen sangat rendah
- Nadi di atas 120 atau di bawah 50 → jantung bekerja tidak normal
- Tekanan darah di bawah 90 atau di atas 180 → berisiko shock/krisis tekanan
b. Triase Kuning
- SpO₂ antara 90–94% → oksigen sedikit kurang
- Nadi antara 100–120 → agak tinggi
- Tekanan darah 140–180 → tinggi tetapi belum kritis
c. Triase Hijau
- Jika pasien tidak memenuhi kondisi merah atau kuning, maka:
- Kondisi masih stabil
- Tidak menunjukkan tanda bahaya serius
2. Antrian Dinamis
Pasien yang lebih darurat langsung naik ke prioritas.
 3. Realtime Update
Tidak perlu refresh halaman setelah data terkirim ke database, data berubah otomatis setiap detik.
 4. Countdown Waktu Tunggu
Memastikan pasien tidak menunggu terlalu lama.
 5. Notifikasi Otomatis
Jika pasien sudah terlalu lama → muncul notifikasi (merah/kuning/hijau).
6. Riwayat Pasien
Semua pasien yang sudah di-acc oleh perawat dipindah otomatis ke halaman riwayat.

<img width="1333" height="597" alt="image" src="https://github.com/user-attachments/assets/1fab490b-c078-49fd-b9cb-300d0724bfee" />
<img width="1338" height="590" alt="image" src="https://github.com/user-attachments/assets/8ceda675-8609-4b03-a814-41ea1fb6f9d5" />
<img width="1351" height="597" alt="image" src="https://github.com/user-attachments/assets/22cb9a20-5b57-4db3-aa56-fb948e5e8839" />
