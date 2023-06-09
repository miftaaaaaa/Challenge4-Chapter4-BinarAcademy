# BCR - Car Management API

Challenge Chapter 4 FullStack Web Developer Binar Academy

## Entity Relationship Diagram
Data pada aplikasi ini disimpan dalam tabel bernama `cars`. Atribut dari tabel ini terdapat primary key dengan auto fill yaitu `id` dengan tipe data Integer, dan atribut lainnya yaitu `name` tipe data String, `rent` tipe data Integer, `size` tipe data String, `createdAt` dan `updatedAt` dengan tipe data DateTime. Berikut merupakan ERD cars :
</br></br>
![](./views/assets/ERD.png)

## Instalation

Clone the repository
   ```sh
   git clone https://github.com/miftaaaaaa/Challenge4-Chapter4-BinarAcademy.git
   ```

Install packages
   ```sh
   npm install
   ```

## Start

Untuk memulai aplikasi ini lakukan perintah `npm run dev` pada terminal. 

## Request
Dalam aplikasi ini terdapat beberapa request sebagai berikut :

### View Halaman Awal
Untuk menampilkan halaman awal terdapat pada `http://localhost:8000/`
</br></br>
![](./views/assets/dashboard.png)

### View Halaman Tambah Mobil Baru
Untuk menampilkan halaman Tambah Mobil Baru dapat menekan tombol "Add New Car" pada halaman di atas, atau dapat menuju url `http://localhost:8000/add`
</br></br>
![](./views/assets/add.png)

### View Halaman Edit Mobil
Untuk menampilkan halaman Tambah Edit Mobil dapat menekan tombol "Edit" di halaman awal pada mobil yang ingin diedit, atau dapat menuju url `http://localhost:8000/update/:id`
</br></br>
![](./views/assets/update.png)

### View Delete Mobil
Untuk menghapus data Mobil dapat menekan tombol "Delete" di halaman awal pada mobil yang ingin dihapus.
</br></br>
![](./views/assets/delete.png)

## Database
![](./views/assets/database.png)
