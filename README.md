# Modul7PHP-Nisrina
#Screenshot hasil Connect.php
![alt text](https://github.com/Ardananisrina/Modul7PHP-Nisrina/blob/master/connect.png)
#Screenshot hasil Form-create
![alt text](https://github.com/Ardananisrina/Modul7PHP-Nisrina/blob/master/Form-create.png)
#Screenshot hasil create
![alt text](https://github.com/Ardananisrina/Modul7PHP-Nisrina/blob/master/Create.png)
#Screenshot hasil read setelah menambahkan data
![alt text](https://github.com/Ardananisrina/Modul7PHP-Nisrina/blob/master/Read(setelah%20ditambahkan%20data).png)
#Screenshot hasil Form-update
![alt text](https://github.com/Ardananisrina/Modul7PHP-Nisrina/blob/master/Form-update.png)
#Screenshot hasil update
![alt text](https://github.com/Ardananisrina/Modul7PHP-Nisrina/blob/master/Update.png)
#Screenshot hasil Read setelah data di edit
![alt text](https://github.com/Ardananisrina/Modul7PHP-Nisrina/blob/master/Read(setelah%20di%20edit).png)
#Screenshot hasil Delete-1
![alt text](https://github.com/Ardananisrina/Modul7PHP-Nisrina/blob/master/Delete-1.png)
#Screenshot hasil Delete-2
![alt text](https://github.com/Ardananisrina/Modul7PHP-Nisrina/blob/master/Delete-2.png)
#Screenshot hasil Read setelah data dihapus
![alt text](https://github.com/Ardananisrina/Modul7PHP-Nisrina/blob/master/Read(setelah%20data%20dihapus).png)
# 1. Berikan contoh kode keneksi untuk ke database pd php?
![alt text](https://github.com/Ardananisrina/Modul7PHP-Nisrina/blob/master/1.png)
# 2. Bagaimana cara anda membuat database pada phpMySQl!
- Buka PHPMyadmin dengan mengetikkan 'localhost/PHPMyadmin/'
- Klik New
- Mengetikkan nama database yang akan dibuat
- Klik create
# 3.  Berikan code query untuk menampilkan sebuah data yang ada pada ke database?
$query = "SELECT * FROM dosen" dimana dosen merupakan nama tabel yang ada di dalam sebuah database
# 4. Berikan code query untuk mengupdate sebuah data yang ada pada ke database?
$query = "UPDATE dosen SET nama_dosen = '$nama_dosen', telp = '$telp' WHERE id_dosen = $id_dosen";
# 5. Berikan code query untuk menghapus sebuah data yang ada pada ke database?
$query = "DELETE FROM dosen WHERE id_dosen = $id_dosen"; dimana 'dosen' adalah nama tabel yang ada di dalam sebuah database, dan 'id_dosen = $id_dosen' merupakan primary key dari data yang ada di tabel.
