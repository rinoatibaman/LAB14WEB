# LAB14WEB
- RINO ELJON ATIBAMAN
- 312010006
- TI.20.D1

#Langkah-langkah Praktikum
Membuat Pagination Pagination merupakan proses yang digunakan untuk membatasi tampilan yang panjandari data yang banyak pada sebuah website. Fungsi pagination adalah memecah tampilan menjadi beberapa halaman tergantung banyaknya data yang akan ditampilkanpada setiap halaman.
Pada Codeigniter 4, fungsi pagination sudah tersedia pada Library sehingga cukupmudah menggunakannya.Untuk membuat pagination, buka Kembali Controller Artikel, kemudian modifikasi
kode pada method admin_index seperti berikut.
Kemudian buka file views/artikel/admin_index.php dan tambahkan kode berikutdibawah deklarasi tabel data.
![Screenshot (23)](https://user-images.githubusercontent.com/101688124/176949171-7b5efb0e-ebd7-426c-a107-02a9359d21d7.png)
Selanjutnya buka kembali menu daftar artikel, tambahkan data lagi untuk melihat hasilnya.
![image](https://user-images.githubusercontent.com/101688124/176949433-29dfc94e-98c5-4788-bda2-6d4b145374c1.png)
#Membuat Pencarian
Pencarian data digunakan untuk memfilter data.Untuk membuat pencarian data, buka kembali Controller Artikel, pada method
admin_index ubah kodenya seperti berikut
![Screenshot (24)](https://user-images.githubusercontent.com/101688124/176950079-d7bcc570-294b-4385-9ccf-878b696d2026.png)
Kemudian buka kembali file views/artikel/admin_index.php dan tambahkan form
pencarian sebelum deklarasi tabel seperti berikut:
![Screenshot (25)](https://user-images.githubusercontent.com/101688124/176950984-73473ec9-8a4c-4718-b60d-0f06e9e640ce.png)
Dan pada link pager ubah seperti berikut.
![image](https://user-images.githubusercontent.com/101688124/176951543-83cc5655-3b4e-4bd6-bb46-e326fcdc0c31.png)
Selanjutnya ujicoba dengan membuka kembali halaman admin artikel, masukkan kata
kunci tertentu pada form pencarian.
![image](https://user-images.githubusercontent.com/101688124/176951666-70de9447-33f5-4a5d-a819-1c3eefd5bc7b.png)
Untuk membuat pencarian data, buka kembali Controller Artikel, pada method
admin_index ubah kodenya seperti berikut
![image](https://user-images.githubusercontent.com/101688124/176951945-7fbb0574-b857-43e3-bc8c-7d0df9800984.png)
![image](https://user-images.githubusercontent.com/101688124/176951993-6a2e9dc1-9dda-4ed8-9c2c-465b77c505f0.png)
![image](https://user-images.githubusercontent.com/101688124/176952013-3cae0d69-784f-4264-a8b6-b768c23e3904.png)
![image](https://user-images.githubusercontent.com/101688124/176952051-f96d161c-4d2b-4604-b07d-7ec536299b84.png)


