# Bookshelf API with NodeJS
Submission Kelas Dicoding: Belajar Membuat Aplikasi Back End untuk Pemula. Membuat Bookshelf API. API dibuat dengan menggunakan NodeJS dan framework Hapi. API dapat mengelola seluruh buku yang akan disimpan. Testing API dilakukan dengan menggunakan Postman. Aplikasi juga menggunakan ESLint untuk menyesuaikan gaya penulisan code yang sesuai denagn standar.

## Fitur Aplikasi
- POST `{{url}}/books`: Menambah buku baru
- GET `{{url}}/books`: Menampilkan seluruh buku
- GET `{url}/books/{bookId}`: Menampilkan buku berdasarkan ID
- PUT `{url}/books/{bookId}`: Mengubah data buku
- DELETE `{url}/books/{bookId}`: Menghapus data buku

## Cara Install
1. Download repository ini
2. Buka dengan VSCode
3. Pada terminal, ketik `npm install`
4. Kemudian ketik `npm run start`
5. Server akan menyala, untuk menguji coba, gunakan postman.

## Cara Testing
1. Download kedua file pada direktori `Postman Testing`
2. Import kedua file pada aplikasi Postman
3. Pilih collection dan uji coba API sesuai dengan endpointnya
4. Jangan lupa untuk menyalakan server terlebih dahulu (づ｡◕‿‿◕｡)づ
