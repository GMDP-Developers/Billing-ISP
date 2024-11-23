<p align="center">
    <h1 align="center">eBilling 2.0</h1>
    <h2 align="center"> Tampilan Baru, Fitur Baru, dan Realtime </h2>
</p>

# Apa ini?  <img src="https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Febilling.gmdp.net.id&count_bg=%231C7BE3&title_bg=%23555555&icon=&icon_color=%23E7E7E7&title=Repository&edge_flat=false"/>

<h4 align="center">
GMDP eBilling adalah sistem berbasis Website yang dirancang untuk mendukung operasional Internal GMDP dan Mitra GMDP dengan fitur Pembayaran Tagihan, Pengelola Pelanggan, hingga Pelaporan pajak PPN, BHP / USO dan KSO yang sesuai dengan regulasi Indonesia
</h4>
<br>

# Screenshoot
#### Data yang kami tampilkan adalah data DUMMY atau PALSU
<table>
    <tr>
        <td><img src='https://github.com/user-attachments/assets/e7d51892-6db2-47cc-b50a-16e040004050' width='800px'></td>
        <td></td>
        <td><img src='https://github.com/user-attachments/assets/124e5dda-04f8-49b7-8305-d566224b217d' width='800px'></td>
    </tr>
</table>
<table>
    <tr>
        <td><img src='https://github.com/user-attachments/assets/552bf21b-996a-4062-94ec-e5f428615873' width='800px'></td>
        <td></td>
        <td><img src='https://github.com/user-attachments/assets/11f8d182-1357-41fb-aec6-52b68ed78b82' width='800px'></td>
    </tr>
</table>
<table>
    <tr>
        <td><img src='https://github.com/user-attachments/assets/d91fc53d-98e0-44a4-b357-a5e279557933' width='800px'></td>
        <td></td>
        <td><img src='https://github.com/user-attachments/assets/1e3c53cd-cd46-4d65-b99d-ad0c8b084a7f' width='800px'></td>
    </tr>
</table>
<table>
    <tr>
        <td><img src='https://github.com/user-attachments/assets/1e3c53cd-cd46-4d65-b99d-ad0c8b084a7f' width='800px'></td>
        <td></td>
        <td><img src='https://github.com/user-attachments/assets/8fb98924-ba5c-45af-a616-66ee0967ca10' width='800px'></td>
    </tr>
</table>
<table>
    <tr>
        <td><img src='https://github.com/user-attachments/assets/e20b6aee-3297-486c-a5ff-82886fdb8330' width='800px'></td>
        <td></td>
        <td><img src='https://github.com/user-attachments/assets/0108a0fd-629f-48c4-9311-d211f6d24849' width='800px'></td>
    </tr>
</table>
<table>
    <tr>
        <td><img src='https://github.com/user-attachments/assets/2840893c-d952-4f2e-96ef-9449a1ae39be' width='800px'></td>
        <td></td>
        <td><img src='https://github.com/user-attachments/assets/0e6b9932-eaca-401c-9025-f25c56ca4661' width='800px'></td>
    </tr>
</table>
<table>
    <tr>
        <td><img src='https://github.com/user-attachments/assets/0b500d51-f4e1-4489-a127-64fde5e91e1a' width='1000px'></td>
    </tr>
</table>

<hr>

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

<!-- https://piclod.com/i/1703558312/Addicts_before_and_after_.png -->

# Contact
Jika pertanyaan Anda belum terjawab di sini, silakan hubungi kami melalui kontak yang tersedia!
#### Silahkan Email ke `info@gmdp.net.id` atau `reno@gmdp.net.id` untuk informasi lebih lengkap
