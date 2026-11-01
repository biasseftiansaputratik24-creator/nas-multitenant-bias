
# Test Scenarios

TC-01: Konektivitas Client

Tujuan:
Memastikan client dapat menjangkau server NAS.

Metode:
Memeriksa koneksi jaringan dari client.

Hasil:
Diisi berdasarkan pengujian aktual.

TC-02: Akses Shared Folder

Tujuan:
Memastikan user yang berwenang dapat membuka folder share.

Metode:
Mengakses folder NAS dari Windows client.

Hasil:
Diisi berdasarkan pengujian aktual.

TC-03: Isolasi Antar-Tenant

Tujuan:
Memastikan setiap tenant hanya dapat mengakses data yang diizinkan.

Metode:
Gunakan akun uji yang berbeda dan folder tenant terpisah.

Kriteria:
Akun tenant tidak dapat membaca atau menulis ke folder tenant lain tanpa izin.

Hasil:
Diisi berdasarkan pengujian aktual.

TC-04: Transfer File

Tujuan:
Mengukur waktu transfer file antara client dan server.

Metode:
Menyalin file uji dengan ukuran yang ditentukan.

Hasil:
Diisi berdasarkan pengujian aktual.

TC-05: Stabilitas Sistem

Tujuan:
Mengamati kestabilan server selama pengujian.

Metode:
Memantau penggunaan CPU, RAM, dan kondisi jaringan.

Hasil:
Diisi berdasarkan pengujian aktual.
