# GO API Native

Sebuah RESTful API sederhana yang dibangun menggunakan Go dengan pendekatan native. API ini menyediakan endpoint untuk manajemen Author dan Book.

## 🚀 Teknologi yang Digunakan

- **Docker** - Containerization platform
- **GORM** - ORM (Object Relational Mapping) untuk Go
- **Gorilla/mux** - HTTP router dan URL matcher untuk Go

## ⚙️ Setup dan Instalasi

1. Pastikan Docker sudah terinstall di sistem Anda
2. Clone repository ini
3. Jalankan perintah:
```bash
docker-compose up --build
```
4. API siap digunakan! 🎉

## 📝 Format Data

### Author
```json
{
    "name": "muksalmina",
    "gender": "M",
    "email": "muksalmina@mail.com",
    "age": 24
}
```

### Book
```json
{
    "title": "book one",
    "author_id": 1,
    "description": "tes book two"
}
```

## 🛣️ Endpoints API

### Authors
| Method | Endpoint | Deskripsi |
|--------|----------|-----------|
| GET    | `/api/authors` | Mendapatkan semua authors |
| POST   | `/api/authors` | Membuat author baru |
| GET    | `/api/authors/1/detail` | Mendapatkan detail author berdasarkan ID |
| PUT    | `/api/authors/1/update` | Mengupdate author berdasarkan ID |
| DELETE | `/api/authors/1/delete` | Menghapus author berdasarkan ID |

### Books
| Method | Endpoint | Deskripsi |
|--------|----------|-----------|
| GET    | `/api/books` | Mendapatkan semua books |
| POST   | `/api/books` | Membuat book baru |
| GET    | `/api/books/1/detail` | Mendapatkan detail book berdasarkan ID |
| PUT    | `/api/books/1/update` | Mengupdate book berdasarkan ID |
| DELETE | `/api/books/1/delete` | Menghapus book berdasarkan ID |

## 👨‍💻 Developed By
[MRTzee](https://github.com/mrtzee)

## 📄 License
MIT License

---
⭐ Jangan lupa beri bintang jika project ini membantu Anda!
