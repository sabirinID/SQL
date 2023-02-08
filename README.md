# SQL
Structured Query Language (SQL)

SQL adalah singkatan dari Structured Query Language, yang merupakan bahasa standar untuk mengakses dan memanipulasi database. Ini merupakan bahasa pemrograman yang digunakan pada database relasional seperti MySQL, PostgreSQL, Oracle, Microsoft SQL Server, dan lainnya.

SQL memiliki beberapa jenis:
1. Data Definition Language (DDL) - Berfungsi untuk membuat, mengubah, dan menghapus tabel, view, dan objek lain dalam database.
   - CREATE: untuk membuat tabel baru, database baru, atau objek lainnya.
   - ALTER : untuk mengubah definisi tabel yang sudah ada.
   - DROP  : untuk menghapus tabel, database, atau objek lainnya.

2. Data Manipulation Language (DML) - Berfungsi untuk memanipulasi data dalam database.
   - INSERT: untuk memasukkan data ke dalam tabel.
   - UPDATE: untuk memperbarui data yang sudah ada dalam tabel.
   - DELETE: untuk menghapus data dalam tabel.
   
3. Data Query Language (DQL) - Berfungsi untuk mengambil data dalam database tanpa mengubah data.
   - SELECT: untuk mengambil data dari tabel.
   - FROM  : untuk menentukan nama tabel dari mana data diambil.
   - WHERE : untuk menentukan kondisi untuk mengambil data.
   - GROUP BY: untuk mengelompokkan data berdasarkan kolom tertentu.
   - HAVING  : untuk memfilter hasil pengelompokan.
   - ORDER BY: untuk mengurutkan data berdasarkan kolom tertentu.

4. Data Control Language (DCL) - Berfungsi untuk mengatur hak akses pengguna pada database.
   - GRANT : untuk memberikan hak akses kepada user tertentu.
   - REVOKE: untuk mencabut hak akses yang sudah diberikan.

5. Transaction Control Language (TCL) - Berfungsi untuk mengatur transaksi dalam database.
   - COMMIT: untuk menyimpan transaksi yang sudah dilakukan.
   - ROLLBACK : untuk membatalkan transaksi yang sudah dilakukan.
   - SAVEPOINT: untuk membuat titik simpan sehingga bisa dibatalkan dengan ROLLBACK.
