# Project-calculating-values-query-python
This project about learning calculating values in a query (In Indonesia)

Sekarang untuk melakukan operator matematika seperti:
- Penjumlahan (+)
- Pengurangan (-)
- Perkalian (*)
- Pembagian (/)
- Modulus (%)
- Tipe data non-numeric

Calculating Difference:
Sebagai contoh, jika kita ingin mendapatkan 5 data usia teratas berdasarkan populasi di antara tahun 2000 dan 2008.
Perintah limit(5) digunakan untuk menampilkan 5 data teratas saja. Kita juga dapat menggunakan nama label yang kita buat untuk bisa digunakan dalam method desc() tersebut.
Case Statement:
Misalkan jika ingin menghitung data berdasarkan kondisi tertentu, maka kita dapat menggunakan fungsi case yang ada di SQLAlchemy. Fungsi ini akan mencocokan nilai kolom dengan kondisi yang telah kita tentukan.

Percentage Example: 
Case statement juga dapat kita gunakan untuk mengkonversi data menjadi bentuk lain. Misalnya :
- Mengkonversi integers menjadi floats sehingga memudahkan kita untuk pembagian.
- Mengkonversi strings to dates and times

Sekarang gabungkan fungsi case dan cast statement sebagai contoh selanjutnya. Misalkan kita ingin menghitung persentase total populasi yang tinggal di New York .
Kita import terlebih dahulu fungsi case, cast dan Float dari SQLAlchemy. Kemudian kita buat query SQL untuk menghitung persentase total populasi yang tinggal di New York. Jika nama state bukan New York, maka nilai dari kolom tersebut diberi angka 0. Lalu dibagi dengan total populasi di tahun 2008 kemudian dikali dengan 100.
