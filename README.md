# Credit-Card-Fraud-Detection

## Deteksi Penipuan Kartu Kredit

Tantangannya adalah mengenali transaksi kartu kredit palsu sehingga pelanggan perusahaan kartu kredit tidak dikenakan biaya atas barang yang tidak mereka beli.
Tantangan utama yang terlibat dalam deteksi penipuan kartu kredit adalah:

- Data yang Sangat Besar diproses setiap hari dan pembuatan model harus cukup cepat untuk merespons penipuan tepat waktu.
- Data Tidak Seimbang yaitu sebagian besar transaksi (99,8%) bukan transaksi palsu sehingga sangat sulit untuk mendeteksi transaksi palsu
- Ketersediaan data karena sebagian besar data bersifat pribadi.
- Data yang salah diklasifikasikan dapat menjadi masalah besar lainnya, karena tidak semua transaksi penipuan tertangkap dan dilaporkan.
- Teknik adaptif yang digunakan terhadap model oleh scammers.

Bagaimana cara mengatasi tantangan-tantangan ini?

Model yang digunakan harus sederhana dan cukup cepat untuk mendeteksi anomali dan mengklasifikasikannya sebagai transaksi penipuan secepat mungkin.
Ketidakseimbangan dapat diatasi dengan menggunakan beberapa metode yang akan kita bahas di paragraf berikutnya
Untuk melindungi privasi pengguna, dimensi data dapat dikurangi.
Sumber yang lebih dapat dipercaya harus diambil untuk memeriksa ulang datanya, setidaknya untuk melatih model.
Kami dapat membuat modelnya sederhana dan dapat diinterpretasikan sehingga ketika penipu beradaptasi dengannya hanya dengan beberapa penyesuaian, kami dapat menyiapkan dan menjalankan model baru untuk diterapkan.
