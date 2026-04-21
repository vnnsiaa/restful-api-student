# RESTful API Student
Project ini dibuat menggunakan Laravel untuk memenuhi tugas mata kuliah Enterprise Application Integration.

## Deskripsi
RESTful API ini digunakan untuk mengelola data student dengan fitur:
- menampilkan seluruh data student
- menampilkan detail student berdasarkan ID
- menambahkan data student
- mengubah data student
- menghapus data student

## JWT Authentication
Api ini sudah dilengkapi authentication menggunakan JWT Token.

## Endpoint API
Semua endpoint student memerlukan Bearer Token:
1. **GET** /api/students
2. **GET** /api/students/{id}
3. **POST** /api/students
4. **PUT** /api/students/{id}
5. **DELETE** /api/students/{id}

### Auth Endpoints
- POST /api/register
- POST /api/login
- GET /api/me
- POST /api/logout

## Dokumentasi Postman
https://documenter.getpostman.com/view/51255759/2sBXqDuPto 

## Author
Devina Arulyantani Venensia Agustin
