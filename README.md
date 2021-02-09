# Intent

Intent adalah sebuah kelas dalam programming Android yang berfungsi untuk perpindahan halaman. Intent juga merupakan suatu objek yang terdapat dalam suatu activity dimana 
objek tersebut dapat komunikasi dengan activity yang lain, baik activity pada fungsi internal android misal seperti memanggil activity dalam satu package atau beda package 
yang masih berada dalam satu project.

Dengan kata lain Intent merupakan mekanisme untuk melakukan sebuah action dan komunikasi antar komponen aplikasi. Contoh, sebuah halaman Activity yang terdapat tombol di dalamnya. 
Lalu jika ditekan tombol tersebut akan membuka kamera, atau halaman lainnya. Nah, perpindahan inilah yang dinamakan Intent. 

Ada tiga penggunaan umum intent :
1. Memindahkan satu activity ke activity lain dengan atau tidak membawa data.
2. Menjalankan background service, misalnya melakukan sinkronisasi ke server dan menjalankan proses berulang (periodic/scheduler task).
3. Mengirimkan obyek broadcast ke aplikasi yang membutuhkan. Misal, ketika aplikasi membutuhkan proses menjalankan sebuah background service setiap kali aplikasi selesai melakukan booting. Aplikasi harus bisa menerima obyek broadcast yang dikirimkan oleh sistem Android untuk event booting tersebut.

Intent dibagi menjadi 2, yaitu :

1. Explicit Intent berfungsi untuk mengaktifkan komponen-komponen dalam satu aplikasi yang sama. Misalnya seperti : Berpindah Activity.
2. Implicit Intent berfungsi untuk memanggil fungsi activity yang sudah ada di fungsi internal android seperti Dial Number, Open Browser dan lainnya.

# Penereapan Intent

Contoh penerapan Explicit Intent dimana program tersebut melakukan perpindahan halaman dalam satu aplikasi menggunakan media button dengan membawa data.

![WhatsApp Image 2021-02-09 at 20 37 21](https://user-images.githubusercontent.com/60412314/107372592-263f4580-6b18-11eb-92cf-0dcb518e0cc5.jpeg)

Ini hasilnyaa ...

![WhatsApp Image 2021-02-09 at 20 49 32](https://user-images.githubusercontent.com/60412314/107372777-5f77b580-6b18-11eb-9ede-cd194f39ffae.jpeg)

# Terimakasi :)
