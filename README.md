# Car Management Api

Challenge Chapter 4 Full Stack Web Binar Academy 

## Start

Untuk memulai aplikasi ini lakukan perintah `npm run start` pada terminal. Jika ingin dijalankan dengan nodemon dapat dilakukan perintah `npm run dev`

## Request
Dalam aplikasi ini terdapat beberapa request sebagai berikut:

### View Halaman Awal
Untuk menampilkan halaman awal terdapat pada `http://localhost:8000/`
</br></br>
![](./views/assets/add%20new%20car.png)

### View Halaman Tambah Mobil Baru
Untuk menampilkan halaman Tambah Mobil Baru dapat menekan tombol "Add New Car" pada halaman di atas, atau dapat menuju url `http://localhost:8000/add`
</br></br>
![](./views/assets/dashboard%20new%20car.png)


### View Halaman Edit Mobil
Untuk menampilkan halaman Tambah Edit Mobil dapat menekan tombol "Edit" di halaman awal pada mobil yang ingin di-edit, atau dapat menuju url `http://localhost:8000/update/:id`
</br></br>
![](./views/assets/edit%20new%20car.png)

## Entity Relationship Diagram
Data pada aplikasi ini disimpan dalam tabel bernama `cars`. Atribut dari tabel ini terdapat primary key dengan auto fill yaitu `id` dengan tipe data integer, dan atribut lainnya yaitu `name` tipe data string, `rent` tipe data integer, `size` tipe data string, `createdAt` dan `updatedAt` dengan tipe data DATE. Berikut merupakan diagram tabel cars:
</br></br>

![](./views/assets/ss%20erd.png)



