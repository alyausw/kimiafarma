# Kimia Farma

Repository ini berisi syntax BigQuery yang dibuat untuk kebutuhan analisis data.

## Daftar File
- **query_kf_analisis_kinerja_bisnis.sql**: Menampilkan data analisis sesuai pada challange mengevaluasi kinerja bisnis Kimia Farma dari tahun 2020 hingga 2023.
1.  transaction_id : kode id transaksi, 
2.  date : tanggal transaksi dilakukan, 
3.  ranch_id : kode id cabang Kimia Farma, 
4.  ranch_name : nama cabang Kimia Farma, 
5.  kota : kota cabang Kimia Farma,
6.  provinsi : provinsi cabang Kimia Farma,
7.  rating_cabang : penilaian konsumen terhadap cabang Kimia Farma
8.  customer_name : Nama customer yang melakukan transaksi,
9.  product_id : kode product obat,
10. product_name : nama obat,
11. actual_price : harga obat,
12. discount_percentage : Persentase diskon yang diberikan pada obat,
13. persentase_gross_laba : Persentase laba yang seharusnya diterima dari obat dengan ketentuan berikut:
     a.     Harga <= Rp 50.000 -> laba 10%
     b.     Harga > Rp 50.000 - 100.000 -> laba 15%
     c.     Harga > Rp 100.000 - 300.000 -> laba 20%
     d.     Harga > Rp 300.000 - 500.000 -> laba 25%
     e.     Harga > Rp 500.000 -> laba 30%,
14.  nett_sales : harga setelah diskon,
15.  nett_profit : keuntungan yang diperoleh Kimia Farma,
16.  rating_transaksi : penilaian konsumen terhadap transaksi yang dilakukan.

## Cara Menggunakan
1. Salin syntax dari file `.sql`.
2. Tempel di editor BigQuery di Google Cloud Platform.
3. Klik **Run** untuk menjalankan query.
