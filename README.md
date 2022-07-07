# UAS PEMROGRAMAN WEB KELOMPOK 2
NAMA: BAYU ALFADRYAN 
NIM: 191011400835
KELAS: 06TPLM005

## DESKRIPSI
Program ini dibuat menggunakan PHP Native tanpa Framework dan menggunakan MySQL untuk database sebagai penyimpanan data yang telah di input dengan query INSERT INTO tabel relawan,
kemudian data dipanggil kembali untuk dicetak/diprint menggunakan query SELECT * FROM tabel relawan, dan ada fungsi hapus menggunakan DELETE * FROM serta ubah data menggunakan UPDATE tabel.

Kemudian untuk mengkoneksikan ke database menggunakan fungsi:
<?php
$servername = "localhost";
$database = "uas";
$username = "root";
$password = "";
 
$db = mysqli_connect($servername, $username, $password, $database);

if (!$db) {
    die("Koneksi Gagal: " . mysqli_connect_error());
}
echo "Koneksi Berhasil";
mysqli_close($db);
?>
![WhatsApp Image 2022-07-07 at 15 35 49](https://user-images.githubusercontent.com/108208590/177730082-109d8f00-06d4-4953-b39b-e388b217df44.jpeg)
![WhatsApp Image 2022-07-07 at 15 35 51 (1)](https://user-images.githubusercontent.com/108208590/177730093-ad416396-508a-4579-80e8-3a644d8d9021.jpeg)
![WhatsApp Image 2022-07-07 at 15 35 51](https://user-images.githubusercontent.com/108208590/177730102-0ba039fd-a350-4f82-8515-8d130bf10998.jpeg)
![WhatsApp Image 2022-07-07 at 15 35 50 (1)](https://user-images.githubusercontent.com/108208590/177730107-91749c8b-f4ce-4328-a24a-ec8a8c28e45c.jpeg)
![WhatsApp Image 2022-07-07 at 15 35 50](https://user-images.githubusercontent.com/108208590/177730119-93b8c1ff-bfb3-485d-a7e6-c2fc346d51d9.jpeg)
![WhatsApp Image 2022-07-07 at 15 35 49 (1)](https://user-images.githubusercontent.com/108208590/177730122-8b53a066-5121-4c77-b711-b0e685616f61.jpeg)
