# Project-Module-3-Machine-Learning
Machine Learning Development for Travel Insurance Claim case
## Business Overview
Perusahaan asuransi memiliki business model risk-pooling, dimana perusahaan menjual sebuah produk jaminan akan suatu hal kepada seseorang dengan mewajibkan pembayaran premi sesuai kesepakatan yang telah ditentukan. Perusahaan asuransi harus mencari nasabah sebanyak-banyak nya untuk menyebarkan resiko atas pembayaran kompensasi terhadap jaminan konsumennya. Berikut ini adalah Line 0f Business (LOB) perusahaan asuransi
1. Asuransi Umum (General insurance) - Asuransi untuk melindungi aset fisik dan tanggung jawab hukum dari kerugian finansial **ex: kendaraan motor, perjalanan, rekayasa engineering, etc**
2. Asuransi Jiwa - Asuransi untuk melindungi individu atas keselamatan/kecelakaan
3. Asuransi Kesehatan - Asuransi untuk memfasilitasi individu untuk mendapatkan manfaat kesehatan

## Problem Understanding
1. Sumber **pendapatan** utama perusahaan asuransi adalah pada premi yang wajib dibayarkan nasabah. Sementara klaim merupakan pertanggungan perusahaan kepada nasabah yang menjadi **pengeluaran**. Setiap periode, perusahaan asuransi perlu menetapkan premi kepada masing-masing nasabah nya berdasarkan profil resikonya. Salah satu bentuk untuk melihat profil resiko nasabah adalah meninjau karakteristik calon nasabah apakah berpotensi tinggi untuk melakukan claim atau tidak. Ketika memiliki potensi klaim, maka premi yang dibebankan harus bernilai lebih tinggi dari nasabah yang tidak berpotensi klaim
2. Selain itu proses assessment claim yang diterima juga perlu di perhatikan juga untuk menurunkan biaya assessment tersebut

> **Features Insight**
1. **Agency**: Nama agency - Badan yang menjual produk asuransi kepada nasabah (Frontliner).
2. **Agency Type**: Jenis asuransi - Tipe proteksi perjalanan.
3. **Distribution Channel**: Metode distribusi penjualan - Metode yang digunakan untuk berjualan.
4. **Product Name**: Nama Produk asuransi - Paket asuransi yang memiliki kemanfaatan tersendiri.
5. **Gender**: Jenis kelamin nasabah.
6. **Duration**: Lama nya waktu perjalanan.
7. **Destination**: Destinasi tujuan.
8. **Net Sales**: Netto pendapatan penjualan - Jumlah netto penjualan produk oleh agen asuransi.
9. **Commission (in value)**: Komisi yang didapatkan agen asuransi saat berhasil menjual produk.
10. **Age**: Umur nasabah yang diasuransikan.
11. **Claim**: Status klaim.
