
# MovieProject
## RestAPI Sederhana

![Screenshot_2021-04-29-15-55-20-074_com aaron movieproject](https://user-images.githubusercontent.com/60208227/116530525-5670d600-a908-11eb-9eb3-5f79ca92b3ca.jpg)

- API, Application Programming Interface yaitu sebuah software 
yang memungkinkan para developer untuk mengintegrasikan dan mengizinkan dua aplikasi yang berbeda secara bersamaan untuk saling terhubung satu sama lain.

- Tujuan penggunaan dari API adalah untuk saling berbagi data antar aplikasi yang berbeda
tersebut, dan juga untuk mempercepat proses pengembangan aplikasi dengan cara menyediakan sebuah function yang terpisah sehingga para developer tidak perlu lagi membuat fitur yang serupa.

- REST API merupakan salah satu dari desain arsitektur yang terdapat di dalam API itu 
sendiri. Dan cara kerja dari RESTful API yaitu REST client akan Melakukan akses pada 
data/resource pada REST server dimana masing-masing resource. Atau data/resource tersebut 
akan dibedakan oleh sebuah global ID atau URIs (Universal Resource Identifiers).
Jadi, Nantinya data yang diberikan oleh REST server itu bisa berupa format text, JSON atau 
XML,  saat ini format yang paling populer dan paling banyak digunakan adalah format 
JSON

- Analogi sederhananya adalah sebuah restoran, didalam restoran terdapat pelanggan, pelayan dan koki. Bayangkan pelanggan adalah user di halalaman frontend, pelayan adalah API dan koki adalah backendnya. Pelanggan akan memesan makanan pada pelayan dan pelayan akan daftar pesanan pada koki. Saat makanan telah siap, pelayan akan mengantar makanan pada pelanggan.

- Sama dengan Lifecycle API, frontend disini bisa jadi client yang mengakses platform web maupun mobile. API akan menerima permintaan data dari frontend lalu menyerahkannya pada backend, backend akan menyerahkan data yang sesuai lalu API menyerahkan data tersebut pada frontend(client) 
### Komponen Penting
- Butterknife, adalah library untuk menyimpan data pada backendnya
- Retrofit, adalah library untuk membantu kita membuat APInya
- Recycler, library yang bisa kita pakai untuk menampilkan list array data.
#### catatan kaki
- jika hasil running project (color) tidak sesuai, Anda bisa mematikan mode malam pada device Anda. 
Contoh: android: background = white, tapi saat dijalankan berwarna gelap
- walaupun APInya beda, data tidak akan ada kesalahan jika backendnya sama.
- Pastikan untuk melihat Android Manifest jika layout yang tertampil hanya warna putih,
- Copy paste memang mempercepat pengerjaan, tapi dengan mengetik manual Anda semakin paham atas kode yang Anda kerjakan.
