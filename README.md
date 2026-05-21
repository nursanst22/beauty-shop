**NUVEA — Beauty & Skincare** adalah aplikasi web *e-commerce* satu halaman (*Single Page Application*) yang berfungsi sebagai katalog produk kecantikan interaktif. Program ini dibangun menggunakan teknologi web murni (**HTML5, CSS3, dan Vanilla JavaScript ES6**) tanpa bantuan *framework* eksternal, dengan fokus utama pada desain antarmuka (*UI/UX*) yang mewah, minimalis, dan responsif.

Sistem ini bekerja secara dinamis di sisi klien (*client-side*) untuk menangani siklus belanja pengguna melalui beberapa modul utama:

1. **Manajemen Katalog Dinamis**: Program otomatis merender data produk dari memori lokal ke dalam grid visual berdasarkan kategori (Skincare, Makeup, Lip Care, Eye Care) lengkap dengan status stok (*Sold Out*) dan label diskon.
2. **Sistem Filter & Pencarian Real-Time**: Pengguna dapat mencari produk secara instan lewat kolom pencarian yang otomatis menyaring data saat mengetik, atau menggunakan tombol kategori dan *trending tags* untuk mempersempit pilihan.
3. **Keranjang Belanja & Kalkulator Invoice**: Fitur yang mencatat item pilihan, menghitung subtotal biaya secara otomatis, mendeteksi validasi kode promo (`BEAUTY20`), dan memproses data formulir *checkout* melalui jendela modal.
4. **Sistem Wishlist (Favorit)**: Fitur penanda bertenaga *array state* yang memungkinkan pengguna menyimpan produk yang disukai dan meninjaunya kembali dalam satu halaman khusus melalui ikon navigasi.
5. **Arsitektur Responsif**: Layout visual menggunakan CSS Grid dan Flexbox yang adaptif, memastikan tampilan web otomatis berubah rapi saat diakses dari layar komputer maupun *smartphone*.
