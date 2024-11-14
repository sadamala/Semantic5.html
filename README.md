# Semantic5.html
Masalah yang Terjadi dan efek setelah diperbaiki pada form HTML
 
1.Tidak ada tag <html>, <head>, dan <body>
Dokumen HTML ini tidak lengkap karena tidak menyertakan tag utama seperti <html>, <head>, dan <body>. Tanpa tag ini, browser mungkin kesulitan memahami struktur dokumen dan bisa menyebabkan masalah saat menampilkan halaman.
2.Penulisan tag <footer> yang salah
Tag <footer> ditempatkan di dalam tag <footer> lainnya, yang tidak valid menurut standar HTML. Ini bisa membingungkan browser dan menyebabkan tampilan footer tidak sesuai.

Dampak dari Perubahan:
1.Struktur Lebih Baik dan Kompatibilitas Browser
Penambahan tag inti seperti <html>, <head>, dan <body> membuat dokumen memiliki struktur yang lebih baik. Ini akan memastikan tampilan halaman lebih konsisten di berbagai browser dan perangkat.
2.SEO dan Aksesibilitas yang Lebih Baik
Dengan adanya tag <title> dan <meta>, halaman ini akan lebih ramah SEO (Search Engine Optimization) dan lebih mudah diakses oleh pengguna dengan kebutuhan khusus, seperti mereka yang menggunakan screen reader.
3.Responsif di Berbagai Perangkat
Tag <meta name="viewport"> membuat halaman dapat menyesuaikan dengan ukuran layar yang berbeda, terutama pada perangkat mobile, sehingga pengalaman pengguna lebih baik.
4.Mencegah Kesalahan Tampilan
Dengan memperbaiki masalah struktur seperti tag <footer> yang ganda, ini akan mengurangi kemungkinan terjadinya kesalahan tampilan atau bug di browser.



perbedaan dan efek setelah di perbaiki pada form CSS

Perbedaan Utama:
1.Urutan Deklarasi CSS:
-Kode Awal: Semua aturan CSS untuk masing-masing elemen (nav, header, section, footer) ditulis sebelum deklarasi aturan untuk elemen body.
-Kode Setelah Diubah: Urutan penulisan berubah, di mana deklarasi untuk elemen body dan elemen umum seperti header, nav, section, dan footer dipindahkan ke bawah.
2.Tata Letak & Struktur:
Tidak ada perubahan signifikan dalam tata letak, grid-area, atau ukuran grid di antara dua versi kode. Perubahan hanya ada pada urutan penulisan blok kode, namun tidak mengubah perilaku secara fungsional.

Efek dari Perubahan:
1. Perubahan Urutan Tidak Mempengaruhi Fungsionalitas:
Secara teknis, urutan penulisan dalam CSS tidak berpengaruh pada cara browser membaca dan menerapkan gaya, selama tidak ada konflik antar aturan. Dalam kedua versi kode, semua aturan CSS diterapkan sama, sehingga tidak ada efek signifikan dalam tampilan halaman dari segi visual.
2. Pengelompokan Kode:
Kode yang diubah mengelompokkan aturan untuk body dan padding elemen (header, nav, section, footer) ke bagian awal, sehingga mungkin lebih mudah dibaca atau dikelola karena aturan umum ditulis di awal. Ini membuat kode sedikit lebih terorganisir.
3. Efisiensi dalam Pengelolaan:
Dalam proyek besar, urutan penulisan dapat membantu menjaga konsistensi dan organisasi kode, terutama ketika ada banyak aturan CSS. Dalam kasus ini, menempatkan aturan umum di bagian awal bisa membantu membuat kode lebih bersih dan terstruktur.
