# Kimia Farma

Repository ini berisi syntax BigQuery yang dibuat untuk kebutuhan analisis data.

## Daftar File
- **query_kf_analisis_kinerja_bisnis.sql**: Menampilkan data analisis sesuai pada challange mengevaluasi kinerja bisnis Kimia Farma dari tahun 2020 hingga 2023.
1.  transaction_id : kode id transaksi, 
2.  date : tanggal transaksi dilakukan, 
  ● branch_id : kode id cabang Kimia Farma, 
  ● branch_name : nama cabang Kimia Farma, 
  ● kota : kota cabang Kimia Farma, 
  ● provinsi : provinsi cabang Kimia Farma,
  ● rating_cabang : penilaian konsumen terhadap cabang Kimia Farma
  ● customer_name : Nama customer yang melakukan transaksi,
  ● product_id : kode product obat,
  ● product_name : nama obat,
  ● actual_price : harga obat,
  ● discount_percentage : Persentase diskon yang diberikan pada obat,
  ● persentase_gross_laba : Persentase laba yang seharusnya diterima dari obat dengan ketentuan berikut:
     ■ Harga <= Rp 50.000 -> laba 10%
     ■ Harga > Rp 50.000 - 100.000 -> laba 15%
     ■ Harga > Rp 100.000 - 300.000 -> laba 20%
     ■ Harga > Rp 300.000 - 500.000 -> laba 25%
     ■ Harga > Rp 500.000 -> laba 30%,
  ● nett_sales : harga setelah diskon, 
  ● nett_profit : keuntungan yang diperoleh Kimia Farma,
  ● rating_transaksi : penilaian konsumen terhadap transaksi yang dilakukan.

## Cara Menggunakan
1. Salin syntax dari file `.sql`.
2. Tempel di editor BigQuery di Google Cloud Platform.
3. Klik **Run** untuk menjalankan query.
