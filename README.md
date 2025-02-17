# **Data Driven Inventory Management Optimization for Retail Efficiency and Profitability**


## Deskripsi Proyek
Proyek ini bertujuan untuk mengoptimalkan manajemen inventaris di sektor ritel dengan menggunakan teknik berbasis data, termasuk **Just In Time (JIT)**, **Safety Stock**, dan **Reorder Point (ROP)**. Tujuannya adalah untuk mengurangi biaya penyimpanan, mencegah kekurangan stok (stockout), dan meningkatkan efisiensi pengadaan produk. Dengan menggunakan data untuk membuat keputusan yang lebih baik, proyek ini membantu bisnis ritel dalam meningkatkan profitabilitas dan operasional mereka.

## Tujuan
- 🎯 **Mengoptimalkan manajemen inventaris** untuk menekan biaya penyimpanan dan mencegah kekurangan stok.
- 📈 **Meningkatkan efisiensi pengadaan** melalui analisis cost-benefit yang berbasis data.

## Latar Belakang
Manajemen inventaris yang efisien sangat penting dalam ritel untuk menekan biaya penyimpanan dan mencegah kekurangan stok. Pengelolaan yang buruk dapat menyebabkan kelebihan stok atau kehilangan pendapatan akibat stockout. Oleh karena itu, pendekatan berbasis data diperlukan untuk meningkatkan efisiensi dan profitabilitas.

## Metrik Bisnis
- 📊 **Profit Growth**: Mengukur pertumbuhan keuntungan sebelum dan setelah optimasi inventaris.
- 💸 **Cost Savings**: Mengidentifikasi pengurangan biaya dari inventaris berlebih dan stockout.
- 📉 **Stockout Rate**: Mengevaluasi frekuensi terjadinya kekurangan persediaan.
- 🔄 **Inventory Turnover**: Mengukur seberapa cepat barang terjual dan diganti.

## Dampak Bisnis
- 🚀 **Efisiensi Operasional Meningkat**: Penghematan biaya hingga 44,7% dengan implementasi JIT.
- 💵 **Peningkatan Profitabilitas**: JIT meningkatkan profit antara 7,5% hingga 17,1% setiap bulan.
- ⚖️ **Pengurangan Risiko Stockout dan Overstock**: JIT berhasil menjaga stockout rate di 0%, memastikan ketersediaan stok yang optimal.

## Dataset
Dataset yang digunakan dalam proyek ini mencakup informasi transaksi dan produk yang membantu dalam memodelkan optimasi inventaris. Berikut adalah penjelasan untuk setiap kolom dalam dataset:

| **Kolom**                | **Deskripsi**                                                                                   | **Ikon**  |
|--------------------------|-------------------------------------------------------------------------------------------------|----------|
| **Date**                 | Tanggal tercatatnya transaksi atau data.                                                         | 📅        |
| **Store ID**             | ID unik yang mengidentifikasi setiap toko.                                                      | 🏬        |
| **Product ID**           | ID unik yang mengidentifikasi produk yang terjual.                                               | 📦        |
| **Category**             | Kategori produk (pakaian, elektronik, makanan, dll.).                                           | 🏷️       |
| **Region**               | Wilayah atau lokasi geografis tempat produk dijual.                                              | 🌍        |
| **Inventory Level**      | Jumlah persediaan (stok) yang tersedia di toko pada suatu titik waktu tertentu.                  | 📊        |
| **Safety Stock**         | Jumlah stok pengaman untuk menghindari kehabisan stok.                                           | 🛡️       |
| **Units Sold**           | Jumlah unit produk yang terjual pada tanggal tersebut.                                          | 💰        |
| **Units Ordered**        | Jumlah unit produk yang dipesan untuk restock atau pengisian ulang stok.                         | 🛒        |
| **Demand Forecast**      | Perkiraan jumlah permintaan untuk produk pada periode tertentu.                                 | 🔮        |
| **Price**                | Harga jual produk pada tanggal tersebut.                                                        | 💵        |
| **Order Cost**           | Biaya yang dikeluarkan untuk melakukan pemesanan produk.                                         | 💳        |
| **Daily Unit Holding Cost** | Biaya penyimpanan unit produk per hari, mencakup biaya penyimpanan barang di gudang.            | 🏷️       |
| **Estimated Lead Time**  | Waktu yang diperkirakan dibutuhkan untuk memperoleh barang yang dipesan.                         | ⏳        |
| **Discount**             | Diskon yang diberikan untuk produk pada tanggal tersebut.                                       | 💸        |
| **Competitor Pricing**   | Harga yang ditawarkan oleh pesaing untuk produk yang sama pada tanggal tersebut.                 | 💹        |
| **Weather Condition**    | Kondisi cuaca pada hari tertentu (misalnya, cerah, hujan, dll.).                                | 🌦️       |
| **Holiday/Promotion**    | Menandakan apakah hari tersebut adalah hari libur atau ada promosi yang berlangsung (1 = ya, 0 = tidak). | 🎉        |
| **Seasonality**          | Menunjukkan apakah produk terpengaruh oleh faktor musiman (misalnya, produk lebih laku saat musim liburan atau saat cuaca tertentu). | 🍂🌸❄️🌞 |

## Penggunaan
1. Clone repository ini:  
   ```bash
   git clone https://github.com/username/repository-name.git
   ```
2. Install dependencies yang diperlukan:  
   ```bash
   pip install -r requirements.txt
   ```
3. Jalankan script atau notebook untuk memulai analisis.

## Link Portfolio
Lihat lebih banyak karya saya di portfolio: [Portfolio Saya](https://nanasalpukat.github.io/portfolio_new)

## Lisensi
Proyek ini dilisensikan di bawah [MIT License](LICENSE).

Terima kasih atas perhatian Anda! ✨
