# UTS_Prog3_24183207015
UTS Pemrograman 3

# Aplikasi Pemesanan Makanan
https://github.com/user-attachments/assets/4648f9f1-aa9e-45bd-8b21-346abe509f1e

# 🍽️ Keyan's Vite Cuisine
Sudut Temu Ruang Rasa

## 📖 Deskripsi Proyek
**Keyan's Vite Cuisine** 
  Keyan Vite Cuisine adalah aplikasi pemesanan makanan berbasis Java GUI (Swing) yang dirancang untuk mempermudah operasional pemesanan di sebuah restoran. Aplikasi ini memiliki antarmuka yang ramah pengguna, memungkinkan kasir atau pelayan untuk mencatat pesanan pelanggan, menyesuaikan catatan khusus, dan menghitung total pembayaran secara *real-time* dengan berbagai metode pembayaran.

Proyek ini dibangun menggunakan **Apache NetBeans** dengan memanfaatkan pustaka **Java Swing** untuk menyusun antarmuka visual yang terstruktur.

## ✨ Fitur Utama
* **Manajemen Data Pemesan:** Mendata nomor meja, nama pelanggan, dan catatan khusus (misal: "Nasi goreng tidak pedas") yang akan direkam dan ditampilkan kembali pada struk akhir..
* **Kategori Menu Dinamis:** Menu dikelompokkan secara rapi ke dalam tiga kategori:
    * Makanan
    * Minuman
    * Snack.

      List menu akan otomatis menyesuaikan berdasarkan kategori yang dipilih beserta masing-masing daftar harga yang sudah tertera.
* **Sistem Keranjang Belanja (Cart):**
    * Kalkulasi otomatis (Harga Satuan × Jumlah Porsi = Total Harga).
    * Tombol "Tambah Keranjang" akan memvalidasi *input* dan memindahkan data pesanan sementara ke dalam **Daftar Pesanan**
    * Dilengkapi dengan fitur pembatalan (*error handling* operasional) melalui tombol "Hapus Item Terpilih", yang memungkinkan kasir menghapus pesanan tertentu dari daftar tanpa harus mereset seluruh transaksi.
* **Kalkulasi *Grand Total*:** Setiap kali ada penambahan atau penghapusan item di keranjang, sistem secara dinamis memperbarui label **GRAND TOTAL**. Sistem juga secara otomatis menghitung dan menampilkan total keseluruhan biaya pesanan dari semua item yang ada di keranjang pesanan.
* **Metode Pembayaran Fleksibel:** Mendukung pencatatan pembayaran menggunakan:
    * Tunai
    * QRIS
    * Transfer Bank/Debit.
* **Cetak Struk Digital:** Menghasilkan ringkasan pesanan (*pop-up dialog*) yang mencetak detail pemesan, daftar item, total bayar, catatan pesanan, dan metode pembayaran.
Struk digital ini merangkum:
  * Nama Pelanggan & No. Meja
  * Detail setiap item yang dipesan (Nama, Porsi, Harga Subtotal)
  * Catatan tambahan pelanggan
  * Total akhir yang harus dibayar
  * Metode pembayaran yang dipilih


## 🛠️ Teknologi yang Digunakan
* **Bahasa Pemrograman:** Java
* **GUI Framework:** Java Swing (`JFrame`, `JComboBox`, `JTable`, `JList`, `JTextField`, dll.)
* **IDE:** Apache NetBeans



