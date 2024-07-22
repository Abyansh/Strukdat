# Aplikasi Penerimaan dan Pengantaran Barang

Anggota Kelompok:
* Abyan Shidqi Hidayat (140810210014)
* Dimas Falah Arianto Wibisono (140810210064)
---
## Latar Belakang
Pendataan barang adalah elemen penting dalam bisnis jasa pengiriman. Setelah data barang dikumpulkan, informasi tersebut bisa digunakan untuk statistik kinerja pekerja, efektivitas sistem pengelolaan, dan lainnya. Oleh karena itu, kemudahan dalam pencatatan barang masuk dan keluar sangat diperlukan agar proses ini dapat berjalan seefisien mungkin.

Selain itu, pencatatan barang keluar dapat memberikan informasi yang membantu kurir dalam mengantar barang. Kurir tidak perlu membawa catatan fisik dari barang yang dimuat di kendaraannya jika sudah memiliki informasi digital mengenai barang yang sedang diantar.

Aplikasi untuk mencatat barang masuk dan keluar di bisnis jasa pengiriman dapat dibuat menggunakan bahasa pemrograman C++ dengan mengimplementasikan berbagai jenis struktur data untuk menambah fungsionalitas aplikasi tersebut.

## Tujuan dan Manfaat
Tujuan dari proposal ini adalah mengimplementasikan materi struktur data dalam bentuk aplikasi serta membuat aplikasi yang dapat digunakan oleh pengusaha jasa pengiriman barang. Manfaat dari proposal ini adalah menambah pemahaman praktikan dalam mengimplementasikan struktur data serta mempermudah pendataan barang masuk dan keluar dalam bisnis jasa pengiriman barang yang menggunakan aplikasi ini.

## Penjelasan Aplikasi
Aplikasi ini dirancang khusus untuk pekerja gudang barang dan kurir pengantar barang dari gudang. Implementasi struktur data Linked List dan Queue sebagai Priority Queue digunakan untuk mengurutkan barang masuk, sedangkan struktur data Stack digunakan untuk memuat barang ke kendaraan serta informasi barang paling luar.

1. Setiap barang memiliki atribut:
   - ID barang
   - Nama barang
   - Nama pengirim
   - Nama penerima
   - Alamat penerima
   - Jenis Pengiriman
   - Status barang

2. Pekerja gudang dapat melakukan:
   - Entry barang masuk
   - Melihat daftar barang masuk yang sudah diurutkan berdasarkan jenis pengiriman
   - Melihat informasi setiap barang yang ada dalam daftar

3. Kurir barang dapat melakukan:
   - Entry barang yang dimuat ke kendaraan (barang keluar)
   - Melihat daftar barang yang dimuat ke kendaraan
   - Melihat informasi setiap barang yang ada dalam daftar
   - Melihat informasi barang yang paling luar (barang yang paling dulu diantar)
