# Belajar Web dengan Golang

## Daftar Materi
- Pengenalan Web
- Client dan Server
- Golang Web
- Server
- Handler
- ServeMux
- Request
- HTTP Test
- Query Parameter
- Header
- Form Post
- Response Code
- Cookie
- FileServer
- ServeFile
- Template
- Template Data
- Template Action
- Template Layout
- Template Function
- Template Caching
- XSS Cross Site Scripting
- Redirect
- Upload File
- Download File
- Middleware
- Routing Library

---

## Ringkasan Materi

### Pengenalan Web
Dasar konsep web, bagaimana client dan server saling berkomunikasi lewat HTTP.

### Client dan Server
Penjelasan peran client (pengguna) dan server (penyedia layanan) dalam arsitektur web.

### Golang Web
Menggunakan package `net/http` untuk membangun aplikasi web sederhana.

### Server
Cara membuat HTTP server dengan `http.ListenAndServe`.

### Handler
Membuat handler function untuk menangani request dan response.

### ServeMux
Router bawaan Golang untuk mengatur path dan handler.

### Request
Struktur `http.Request` untuk membaca data dari client.

### HTTP Test
Testing handler dan server menggunakan package `net/http/httptest`.

### Query Parameter
Mengambil data dari URL query string.

### Header
Mengakses dan memanipulasi HTTP header.

### Form Post
Mengambil data dari form dengan method POST.

### Response Code
Mengatur status code response (200, 404, 500, dll).

### Cookie
Membuat, membaca, dan menghapus cookie.

### FileServer
Melayani file statis (HTML, CSS, JS, gambar).

### ServeFile
Mengirim file tertentu ke client.

### Template
Menggunakan `html/template` untuk render HTML dinamis.

### Template Data
Passing data ke template.

### Template Action
Menggunakan action seperti `{{if}}`, `{{range}}`, dll.

### Template Layout
Membuat layout dengan template inheritance.

### Template Function
Menambahkan fungsi custom ke template.

### Template Caching
Optimisasi dengan caching template.

### XSS Cross Site Scripting
Mencegah serangan XSS dengan auto-escaping di template.

### Redirect
Mengalihkan request ke URL lain.

### Upload File
Menangani upload file dari form.

### Download File
Mengirim file untuk diunduh client.

### Middleware
Membuat middleware untuk logging, autentikasi, dll.

### Routing Library
Menggunakan library pihak ketiga (misalnya Gorilla Mux) untuk routing lebih kompleks.

---

## Catatan
- Package utama: `net/http` dan `html/template`.  
- Cocok untuk bikin web server sederhana sampai aplikasi kompleks.  
- Middleware dan routing library bikin aplikasi lebih modular dan scalable.
