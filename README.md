# Latar Belakang
Data transaksi merupakan sumber berharga untuk mendapatkan wawasan bisnis yang mendalam bagi sebuah perusahaan. Analisis terhadap data transaksi dapat memberikan gambaran yang jelas terkait kinerja bisnis selama periode waktu tertentu, sehingga memberikan informasi penting untuk pengambilan keputusan bisnis berikutnya. Hal ini memungkinkan perusahaan untuk mengevaluasi apakah kinerja bisnis telah memuaskan atau memerlukan peninjauan lebih lanjut.

# Rumusan Masalah
1. Bagaimana performa bisnis perusahaan dalam periode yang ada?
2. Bagaimana tren penjualan produk? Produk apa yang memiliki penjualan tertinggi?
3. Bagaimana sebaran penjualan perusahaan? Negara apa yang menghasilkan revenue tertinggi?
4. Bagaimana segmentasi pelanggan berdasarkan analisis RFM? Siapa saja pelanggan yang masuk dalam kategori top customers, dan apa karakteristiknya?

# Data dan Asumsi
Dataset merupakan kumpulan data transaksi pada sebuah perusahaan retail _online_ yang berlokasi di United Kingdom. Dataset ini terdiri dari 9 kolom dan 541,908 baris, seperti yang dapat dilihat di: [`online_retail_dataset`](https://github.com/ramlanapriyansyah/Online_Retail_Analysis/blob/main/online_retail_dataset.zip)

Asumsi: </br>
Dalam perhitungan **Recency**, diasumsikan bahwa waktu saat ini (PRESENT) adalah 15 Desember 2011, hal ini didasarkan pada data terakhir yang tercatat yaitu 9 Desember 2011.

# Analisis Data
## A. Sales Analysis
### 1. Total Sales
![image](https://github.com/ramlanapriyansyah/Online_Retail_Analysis/assets/135192484/ef84078e-7917-4ed8-9e68-830fd57973a0)

Terjadi fluktuasi pada total order dan total pendapatan yang diterima perusahaan dari bulan Desember 2010 hingga bulan Agustus 2011, namun terjadi kenaikan pesat dari bulan Agustus hingga November 2011. </br>
Tidak ada keterangan lebih lanjut mengenai tren yang terjadi, namun diasumsikan bahwa tren kenaikan terjadi karena pada bulan Agustus-November merupakan musim liburan seperti _Back-to-school_, Hari Buruh, Tahun Baru, _Thanksgiving_, dan Natal. Konsumen cenderung berbelanja lebih banyak untuk kebutuhan liburan, termasuk hadiah, pakaian, dan barang-barang lainnya.

### 2. Sales by Product
![image](https://github.com/ramlanapriyansyah/Online_Retail_Analysis/assets/135192484/df6d0cd4-9ecb-42fa-a453-5a3dfd2c8a9b)


Produk yang paling banyak terjual adalah sebuah mainan bernama WORLD WAR 2 GLIDERS ASSTD DESIGNS, yaitu sebanyak 51,852 item selama periode Desember 2010 - November 2011, disusul JUMBO BAG RED RETROSPOT, ASSORED COLOUR BIRD ORNAMENT, WHITE HANGING HEART T-LIGHT HOLDER, dan PACK OF 72 RETROSPOT CAKE CASES.

### 3. Sales by Country
![image](https://github.com/ramlanapriyansyah/Online_Retail_Analysis/assets/135192484/8d374329-2d1d-4b8b-bf45-e245b7297fd7)

Dari grafik di atas dapat dilihat bahwa revenue terbesar berasal dari United Kingdom, yang mana merupakan hal yang wajar, mengingat perusahaan memang berlokasi di negara tersebut. </br>
Disamping itu, kemampuan ekspor perusahaan bisa dibilang cukup baik. Dari 4 negara teratas, perusahaan mampu memperoleh revenue dengan rata-rata sekitar USD 234,000. 

## B. Customer Analysis
Customer analysis atau analisis pelanggan dilakukan menggunakan metode RFM Analysis. </br>
RFM Analysis adalah teknik yang digunakan dalam pemasaran dan analisis pelanggan untuk memahami perilaku pembelian pelanggan dan mengelompokkan mereka berdasarkan tiga dimensi utama:

1. **Recency**: Mengukur seberapa baru pelanggan telah melakukan pembelian.
2. **Frequency**: Mengukur seberapa sering pelanggan melakukan pembelian dalam periode waktu tertentu.
3. **Monetary**: Mengukur seberapa banyak uang yang dihabiskan oleh pelanggan dalam periode waktu tertentu.

![image](https://github.com/ramlanapriyansyah/Online_Retail_Analysis/assets/135192484/e068fa75-3368-49d4-9d9a-3d04bd46685f)

Tabel di atas merupakan top customers yang diperoleh dari hasil analisis RFM. </br>
Terlihat bahwa customer dengan ID 14646 memiliki nilai monetary tertinggi, yaitu dengan total belanja sebesar USD 279,489. Customer ini telah melakukan pembelian sebanyak 2085 kali, dengan riwayat transaksi terakhir pada 6 hari yang lalu.

# Kesimpulan
1. Performa bisnis perusahaan bisa dibilang cukup baik. Hal tersebut bisa dilihat dari terjadinya tren peningkatan sales dalam 4 bulan terakhir.
2. Top products berdasarkan total item yang terjual sangat bervariasi, mulai dari aksesoris, mainan, hingga peralatan rumah tangga. Adapun produk dengan penjualan tertinggi adalah sebuah mainan bernama WORLD WAR 2 GLIDERS ASSTD DESIGNS.
3. Pendapatan terbesar yang diperoleh perusahaan berasal dari United Kingdom, yaitu dengan total pendapatan sebesar USD 6,767,873.
4. Customer atau pelanggan dengan ID 14646 merupakan top customer yang dimiliki perusahaan. Customer ini memiliki nilai monetary dan frequency yang tinggi, serta recency yang terbilang baru.

# Saran
1. Mempertahankan tren peningkatan sales yang terjadi.
2. Menyusun strategi pemasaran secara global (ekspor). Jika dilihat dari data, peluang pasar internasional sangat potensial. Sehingga perlu disusun strategi pemasaran yang tepat untuk dapat menyasar target pasar yang lebih luas.

*Seluruh proses analisis dapat dilihat pada file jupyter notebook berikut: [`jupyter_notebook_file`](https://github.com/ramlanapriyansyah/Online_Retail_Analysis/blob/main/jupyter_notebook_file.ipynb)













