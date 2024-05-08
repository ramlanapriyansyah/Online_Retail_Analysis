# Latar Belakang
Data transaksi adalah sumber berharga untuk mendapatkan wawasan bisnis yang mendalam bagi sebuah perusahaan. Analisis terhadap data transaksi dapat memberikan gambaran yang jelas terkait kinerja bisnis selama periode waktu tertentu, sehingga memberikan informasi penting untuk pengambilan keputusan bisnis berikutnya. Hal ini memungkinkan perusahaan untuk mengevaluasi apakah kinerja bisnis telah memuaskan atau memerlukan peninjauan lebih lanjut.

# Rumusan Masalah
1. Bagaimana performa bisnis perusahaan dalam periode yang ada?
2. Bagaimana tren penjualan produk? Produk apa yang memiliki penjualan tertinggi?
3. Bagaimana sebaran penjualan perusahaan? Negara apa yang menghasilkan revenue tertinggi?
4. Bagaimana segmentasi pelanggan berdasarkan analisis RFM? Siapa saja pelanggan yang masuk dalam kategori top customers, dan apa karakteristiknya?

# Data dan Asumsi
Dataset merupakan kumpulan data transaksi pada perusahaan retail _online_ yang berlokasi di United Kingdom. Dataset ini terdiri dari 9 kolom dan 541,908 baris, seperti yang dapat dilihat di: `online_retail_dataset.csv`

Asumsi: </br>
Dalam perhitungan **Recency**, diasumsikan bahwa waktu saat ini (PRESENT) adalah 15 Desember 2011, hal ini didasarkan pada data terakhir yang tercatat yaitu 9 Desember 2011.

# Analisis Data
## A. Sales Analysis
### 1. Total Sales
![image](https://github.com/ramlanapriyansyah/Online_Retail_Analysis/assets/135192484/3ec2d86b-eb67-4817-afbc-b12a89ae26a8)

Terjadi fluktuasi pada total order dan total pendapatan yang diterima perusahaan dari bulan Desember 2010 hingga bulan Agustus 2011, namun terjadi kenaikan pesat dari bulan Agustus hingga November 2011. </br>
Tidak ada keterangan lebih lanjut mengenai tren yang terjadi, namun diasumsikan bahwa tren kenaikan terjadi karena pada bulan Agustus-November merupakan musim liburan seperti _Back-to-school_, Hari Buruh, Tahun Baru, _Thanksgiving_, dan Natal. Konsumen cenderung berbelanja lebih banyak untuk kebutuhan liburan, termasuk hadiah, pakaian, dan barang-barang lainnya.

### 2. Sales by Product
![image](https://github.com/ramlanapriyansyah/Online_Retail_Analysis/assets/135192484/df6d0cd4-9ecb-42fa-a453-5a3dfd2c8a9b)


Produk yang paling banyak terjual adalah sebuah mainan bernama WORLD WAR 2 GLIDERS ASSTD DESIGNS, yaitu sebanyak 51,852 item selama periode Desember 2010 - November 2011, disusul JUMBO BAG RED RETROSPOT, ASSORED COLOUR BIRD ORNAMENT, WHITE HANGING HEART T-LIGHT HOLDER, dan PACK OF 72 RETROSPOT CAKE CASES.








