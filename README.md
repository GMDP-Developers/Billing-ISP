<p align="center">
    <h1 align="center">Billing ISP</h1>
</p>


# Apa ini?  <img src="https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Febilling.gmdp.net.id&count_bg=%231C7BE3&title_bg=%23555555&icon=&icon_color=%23E7E7E7&title=Repository&edge_flat=false"/>

<h4 align="center">
GMDP eBilling adalah sistem berbasis Website yang dirancang untuk mendukung operasional Internal GMDP dan Mitra GMDP dengan fitur Pembayaran Tagihan, Pengelola Pelanggan, hingga Pelaporan pajak PPN, BHP / USO dan KSO yang sesuai dengan regulasi Indonesia
</h4>
<br>

# Informasi Penting
Ebilling 1.0 akan kami buka untuk umum (Public), tentu dengan fitur yang kami Batasi, nantikan informasi lebih lanjut di Github GMDP Developers
- [E-Billing 1.0](https://github.com/GMDP-Developers/Billing-ISP/tree/main/Ebilling%201.0)
- [E-Billing 2.0](https://github.com/GMDP-Developers/Billing-ISP/tree/main/Ebilling%202.0)

# FAQ
### 1. Siapa yang dapat menggunakan GMDP eBilling?
GMDP eBilling dirancang untuk admin/tim keuagan, tim teknisi, dan pelanggan GMDP dan mitra GMDP yang ingin mengelola pembayaran mereka dengan mudah.

### 2. Apakah GMDP eBilling mematuhi regulasi pajak di Indonesia?
Ya, GMDP eBilling mendukung pelaporan pajak sesuai regulasi Indonesia, termasuk pelaporan PPN, BHP/USO, dan KSO secara otomatis.

### 3. Bagaimana cara mengakses GMDP eBilling?
GMDP eBilling dapat diakses melalui www.ebilling.gmdp.net.id. Selain itu, aplikasi mobile tersedia untuk diunduh melalui Play Store (Android) dan App Store (iOS).

### 4. Bagaimana jika saya mengalami masalah teknis?
Anda dapat menghubungi tim dukungan kami yang tercantum pada bagian Contact.

### 5. Apakah ada panduan penggunaan GMDP eBilling?
Ya, panduan penggunaan dan dokumentasi lengkap dapat diakses melalui menu "Help" di aplikasi atau dengan menghubungi tim dukungan kami.

### 6. Apakah data pelanggan aman di GMDP eBilling?
Keamanan data adalah hal yang kami utamakan. GMDP eBilling menggunakan enkripsi data, sistem autentikasi pengguna, dan standar keamanan tinggi untuk melindungi informasi pelanggan. Kami juga telah memperoleh sertifikasi ISO 27001 (Sistem Manajemen Keamanan Informasi) dan bekerja sama dengan payment gateway bersertifikasi dari lembaga terpercaya untuk memastikan perlindungan maksimal terhadap data pengguna.

### 7. Apakah GMDP eBilling menyediakan laporan keuangan?
Ya, GMDP eBilling menyediakan laporan keuangan real-time, termasuk statistik pemasukan, riwayat pembayaran, dan laporan pajak untuk mempermudah audit dan analisis.

<hr>

# User Roles
- Admin, Teknisi (GMDP)
- Pemilik, Admin, Teknisi (Mitra)
- Pelanggan

<hr>

# Arsitektur Sistem
Backend : Laravel, Node.Js <br>
Frontend : Livewire, Tailwind CSS, Alpine JS <br>
Database : PostgreSQL 17 <br>
Integrasi : Flip, Duitku, BRIVA API, Mikrotik API, WhatsApp API <br>
Backups : 2 Server Private Lokal untuk Backup Database

<hr>

# Lisensi:
- ISO 270001

<hr>

# Fitur Utama:
### 1. Pembayaran Tagihan: Mendukung berbagai metode pembayaran melalui beberapa payment gateway, termasuk:
    * Flip for Business
    * Duitku
    * BRIVA API
### 2. Monitoring Statistik: Laporan statistik dan detail pemasukan serta pelanggan secara real-time.
### 3. Database Pelanggan: Penyimpanan dan pengelolaan informasi pelanggan yang terorganisir.
### 4. Automated Invoice dan PKS Generator: Pembuatan faktur dan perjanjian kerjasama (PKS) secara otomatis.
### 5. Pelaporan Pajak: Mendukung laporan otomatis untuk:
    * PPN (Pajak Pertambahan Nilai)
    * BHP/USO (Biaya Hak Penggunaan/Universal Service Obligation)
    * KSO (Kerjasama Operasional)
### 6. Manajemen Jaringan Otomatis: Pemutusan dan penyambungan jaringan internet secara otomatis melalui integrasi dengan Mikrotik/Winbox.
### 7. Pengingat Tagihan Otomatis: Pengiriman pesan pengingat pembayaran melalui integrasi dengan WhatsApp.
### 8. Akses Multi-Platform: Pembayaran tagihan dapat dilakukan melalui aplikasi yang tersedia di Play Store dan App Store maupun langsung melalui website GMDP eBilling.

  
<table>
    <tr>
        <td><img src='https://piclod.com/i/1699121049/141.jpg' width='450px'></td>
        <td></td>
        <td><img src='https://piclod.com/i/1690276721/139.jpg' width='400px'></td>
        <td></td>
        <td><img src='https://i.pinimg.com/736x/83/31/25/8331258e543977d6614d4f0f849b3131.jpg' width='400px'></td>
    </tr>
</table>

<!-- https://piclod.com/i/1703558312/Addicts_before_and_after_.png -->

# Contact
Jika pertanyaan Anda belum terjawab di sini, silakan hubungi kami melalui kontak yang tersedia!
#### Email `info@gmdp.net.id` atau `developer@gmdp.net.id`.
