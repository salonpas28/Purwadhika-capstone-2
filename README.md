# Purwadhika capstone 2
## Analisis Kerugian penjualan SaaS AWS (Amazon Web Services)

## Latar belakang
AWS atau Amazone Web Services merupakan sebuah perusahaaan SaaS (Software as a service) yang melayani dalam bentuk *Cloud Computing* atau Komputisi awan. AWS sering digunakan untuk analitik, penyimpanan data, layanan aplikasi, jaringan, dan berbagai produk lainnya. Dalam kasus ini, AWS ingin mencari tahu bagaimana meningkatan *revenue* mereka. Utamanya ingin mengurangi kerugian-kerugian yang dialami. Untuk itu kita akan menganalisa bagaimana kerugian ini dapat terjadi, dan apa solusi secara bisnis untuk meningkatkan keuntungan mereka.

## Masalah utama
Perusahaan ingin meningkatkan keuntungan bersih dari perusahaan sehingga ingin mengurangi kerugian. Sehingga ada keperluan mengidentifikasi penyebab kerugian terbesar, dan solusi terhadap penyebab itu.

## Deskripsi Data
Dataset Saas Sales ini memiliki data penjualan software sales dan marketing yang dijual ke bisnis atau yang biasa disebut *Business-to-business*(B2B). dengan total 19 Kolom yaitu:
1. Row ID: ID Transaksi unik.
2. Order ID: ID Order unik.
3. Order Date: tanggal pesanan.
4. Date Key: Tanggal dirubah ke kode (10 januari 2023 -> 01/12/2023 -> 20230112).
5. Contact Name: Nama yang melakukan pesanan.
6. Country: Negara sumber pesanan.
7. City: Kota sumber pesanan.
8. Region: Wilayah sumber pesanan.
9. Subregion: Bagian wilayah sumber pesanan.
10. Customer: Nama perusahaan pemesan.
11. Customer ID: ID customer unik.
12. Industry: Industri dari perusahaan pemesan.
13. Segment: segmen perusahaan.
14. Product: produk yang di pesan.
15. License: nomor lisensi produk yang dipesan.
16. Sales: total nominal transaksi.
17. Quantity: Jumlah pesanan di transaksi.
18. Discount: Diskon yang diberikan ke transaksinya.
19. Profit: Keuntungan yang didapatkan dari transaksi.

## Pembersihan/Perubahan data yang dilakukan
1. Pengecekan Outlier
2. Pengecekan konsistensi data kategorikal
3. Pengecekan duplikasi data
4. Mengganti data string/object menjadi datetime

## Kesimpulan harap lihat presentasi/deck dan notebook
Deck: https://docs.google.com/presentation/d/1RaEKf7LEy4T-hETUZnkyR0dO6a-3YWJz0__dDaZBpDo/edit?usp=sharing
Dashboard: https://public.tableau.com/app/profile/leon2007/viz/AWSlossdashboard/Dashboard1
