# Chirex.1.0
> Sistem Pakar Diagnosa Penyakit Pada Ayam Menggunakan Metode Certainty Factor Berbasis Website Responsive.
>


## Berikut tampilan sistem yang di buat.

* Home

![alt text](https://github.com/januriawan/Chirex.1.0/blob/master/Home%201.png)
![alt text](https://github.com/januriawan/Chirex.1.0/blob/master/Home%202.png)
![alt text](https://github.com/januriawan/Chirex.1.0/blob/master/Home%203.png)
![alt text](https://github.com/januriawan/Chirex.1.0/blob/master/Home%205.png)

* Admin

![alt text](https://github.com/januriawan/Chirex.1.0/blob/master/Admin%201.png)
![alt text](https://github.com/januriawan/Chirex.1.0/blob/master/Admin%202.png)

## Configure

Setting nama database anda di file config.php 
```<?php
$server = "localhost";
$username = "root";
$password = "";
$database = "spkayam";

mysql_connect($server,$username,$password) or die("Koneksi gagal");
mysql_select_db($database) or die("Maaf, Database tidak bisa dibuka");
?>
```
Login dengan /chirex/formlogin 
Username : <b>admin</b> 
Password : <b>admin</b>


