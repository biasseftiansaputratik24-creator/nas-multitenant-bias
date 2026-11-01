
# System Architecture

## Komponen Sistem

1. Router
Menghubungkan perangkat ke jaringan dan menangani komunikasi sesuai konfigurasi jaringan.

#2. PC Admin
Digunakan untuk konfigurasi sistem, monitoring, dan dokumentasi pengujian.

3. PC Server
Menjalankan layanan NAS dan menyediakan penyimpanan file.

4. Access Point
Menyediakan koneksi nirkabel bagi client apabila digunakan dalam topologi.

5. Tenant
Tenant A, Tenant B, dan Tenant C merupakan kelompok pengguna dengan hak akses yang dibedakan.

Alur Akses

1. Client terhubung ke jaringan lokal.
2. Client mengakses server NAS.
3. Server memeriksa autentikasi dan hak akses.
4. Client mengakses folder yang diizinkan.
5. Aktivitas pengujian dicatat dan dievaluasi.

 Konsep Multi Tenant

Setiap tenant direncanakan memiliki akun dan folder tersendiri.

Hak akses diterapkan melalui permission atau ACL yang tersedia pada sistem NAS.

Pengujian dilakukan untuk memastikan tenant tidak dapat mengakses data tenant lain tanpa izin.

Catatan

Topologi dan layanan tambahan harus disesuaikan dengan konfigurasi aktual. VLAN dan Nextcloud tidak dinyatakan telah diterapkan sebelum implementasi dan pengujiannya selesai.
