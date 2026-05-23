<p align="center">
    <h1 align="center">eBilling 3.0</h1>
    <h2 align="center"> Tampilan Baru, Fitur Baru, dan Realtime </h2>
</p>

# Apa ini?

<h4 align="center">
GMDP eBilling adalah aplikasi berbasis web yang mendukung operasional internal, cabang, dan POP GMDP melalui fitur pembayaran tagihan, pengelolaan pelanggan, serta pelaporan PPN dan BHP USO sesuai regulasi yang berlaku di Indonesia.
</h4>
<br>

# Screenshoot

#### Data yang kami tampilkan adalah data DUMMY atau PALSU

<table>
    <tr>
        <td><img src='https://github.com/user-attachments/assets/af734b5c-1d57-4270-9f19-274538f5b5ed' width='800px'></td>
        <td></td>
        <td><img src='https://github.com/user-attachments/assets/6698e20b-4100-4aea-afec-260e9b56d925' width='800px'></td>
    </tr>
</table>
<table>
    <tr>
        <td><img src='https://github.com/user-attachments/assets/b86fd152-9927-44b7-b92e-7546b42d76a9' width='800px'></td>
        <td></td>
        <td><img src='https://github.com/user-attachments/assets/2e4448db-e693-4f55-9474-cd5564f6c730' width='800px'></td>
    </tr>
</table>
<table>
    <tr>
        <td><img src='https://github.com/user-attachments/assets/9d64cf72-5353-42f5-8002-51db86e17789' width='800px'></td>
        <td></td>
        <td><img src='https://github.com/user-attachments/assets/d584a056-332f-4dd7-94d0-16c7da51fb5e' width='800px'></td>
    </tr>
</table>
<table>
    <tr>
        <td><img src='https://github.com/user-attachments/assets/b7c1bced-14d7-411f-bd82-336fc53bf75c' width='800px'></td>
        <td></td>
        <td><img src='https://github.com/user-attachments/assets/3aecfd44-5818-401c-97e5-6e0ee503d7d6' width='800px'></td>
    </tr>
</table>
<table>
    <tr>
        <td><img src='https://github.com/user-attachments/assets/4bdc470d-44ee-4c1f-a132-0867047b306b' width='800px'></td>
        <td></td>
        <td><img src='https://github.com/user-attachments/assets/0e0240ee-5d42-421f-add1-ba9424bc921a' width='800px'></td>
    </tr>
</table>

<hr>

# FAQ

### 1. Siapa yang dapat menggunakan GMDP eBilling?

GMDP eBilling dirancang untuk digunakan oleh administrator, tim keuangan, tim teknis, pelanggan GMDP, serta cabang dan POP GMDP dalam mengelola proses pembayaran dan administrasi layanan secara lebih mudah dan efisien.

### 2. Apakah GMDP eBilling mematuhi regulasi di Indonesia?

Ya. GMDP eBilling mendukung proses administrasi dan pelaporan sesuai dengan ketentuan peraturan perundang-undangan yang berlaku di Indonesia, termasuk pelaporan Pajak Pertambahan Nilai (PPN) dan BHP USO secara otomatis.

### 3. Bagaimana cara mengakses GMDP eBilling?

GMDP eBilling dapat diakses melalui situs resmi:
www.ebilling.gmdp.net.id

Selain melalui website, aplikasi mobile GMDP eBilling juga tersedia untuk perangkat Android melalui Google Play Store dan perangkat iOS melalui App Store.

### 4. Bagaimana jika saya mengalami kendala teknis?

Apabila mengalami kendala teknis atau membutuhkan bantuan, pengguna dapat menghubungi tim dukungan GMDP melalui informasi kontak yang tersedia pada halaman “Contact”.

### 5. Apakah tersedia panduan penggunaan GMDP eBilling?

Ya. Panduan penggunaan dan dokumentasi sistem tersedia melalui menu “Help” pada aplikasi. Pengguna juga dapat menghubungi tim dukungan untuk mendapatkan bantuan lebih lanjut.

### 6. Apakah data pelanggan aman di GMDP eBilling?

Keamanan data pelanggan merupakan prioritas utama GMDP eBilling. Sistem ini menerapkan mekanisme perlindungan data seperti enkripsi, autentikasi pengguna, dan standar keamanan informasi yang memadai untuk menjaga kerahasiaan serta integritas data pengguna.

Selain itu, GMDP telah menerapkan standar Sistem Manajemen Keamanan Informasi ISO 27001 dan bekerja sama dengan penyedia payment gateway yang memiliki sertifikasi keamanan sesuai ketentuan yang berlaku.

### 7. Apakah GMDP eBilling menyediakan laporan keuangan?

Ya. GMDP eBilling menyediakan laporan keuangan dan transaksi secara real-time, termasuk riwayat pembayaran, statistik pemasukan, serta laporan perpajakan untuk mendukung kebutuhan monitoring, audit, dan analisis operasional.

<hr>

# User Roles

- Admin, Teknisi (GMDP)
- Kepala Cabang, Admin, Teknisi (Cabang dan POP GMDP)
- Pelanggan

<hr>

# Arsitektur Sistem

- Backend : Laravel, Node.js
- Frontend : Livewire, Tailwind CSS, Alpine.js
- Database : PostgreSQL 17
- Integrasi : Duitku, Tripay, Mikrotik API, WhatsApp API
- Backups : 2 Server Private Lokal untuk Backup Database

<hr>

# Sertifikasi dan Keamanan:

- ISO 270001

<hr>

# Fitur Utama:

### 1. Pembayaran Tagihan: Mendukung berbagai metode pembayaran melalui beberapa payment gateway, termasuk:

    * Duitku
    * Tripay

### 2. Monitoring Statistik: Laporan statistik dan detail pemasukan serta pelanggan secara real-time.

### 3. Database Pelanggan: Penyimpanan dan pengelolaan informasi pelanggan yang terorganisir.

### 4. Automated Invoice Generator: Pembuatan faktur secara otomatis.

### 5. Mendukung proses pelaporan otomatis sesuai regulasi yang berlaku di Indonesia, meliputi:

    * PPN (Pajak Pertambahan Nilai)
    * BHP/USO (Biaya Hak Penggunaan/Universal Service Obligation)

> GMDP tidak melakukan pemungutan biaya KSO

### 6. Manajemen Jaringan Otomatis: Pemutusan dan penyambungan jaringan internet secara otomatis melalui integrasi dengan Mikrotik Router.

### 7. Pengingat Tagihan Otomatis: Pengiriman pesan pengingat pembayaran melalui integrasi dengan WhatsApp.

### 8. Akses Multi-Platform: Pembayaran tagihan dapat dilakukan melalui aplikasi yang tersedia di Play Store dan App Store maupun langsung melalui website GMDP eBilling.

<!-- https://piclod.com/i/1703558312/Addicts_before_and_after_.png -->

# Contact

Jika pertanyaan Anda belum terjawab di sini, silakan hubungi kami melalui kontak yang tersedia!

#### Silahkan Email ke `developer@gmdp.net.id` untuk informasi lebih lengkap
