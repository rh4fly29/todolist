
# ToDoList - Laravel 11

Ini adalah proyek **ToDoList** menggunakan Laravel 11. Proyek ini dibuat untuk latihan dasar CRUD menggunakan Laravel.

## 🚀 Fitur

- [x] Laravel 11
- [x] CRUD Task (Create, Read, Update, Delete)
- [x] UI sederhana dan fungsional

---

## 📦 Cara Menjalankan Proyek

Ikuti langkah-langkah berikut untuk menjalankan proyek ini di komputer lokal kamu:

### 1. Clone Repo

```bash
git clone https://github.com/rh4fly29/todolist.git
cd todolist
```

---

### 2. Install Dependency dengan Composer

```bash
composer install
```

---

### 3. Duplikat File .env

Karena tidak tersedia `.env.example`, kamu bisa buat manual atau salin dari proyek Laravel lain, lalu sesuaikan seperti ini:

```env
APP_NAME=Laravel
APP_ENV=local
APP_KEY=
APP_DEBUG=true
APP_URL=http://localhost

LOG_CHANNEL=stack

DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=latihan
DB_USERNAME=root
DB_PASSWORD=
```

Lalu generate app key:

```bash
php artisan key:generate
```

---

### 4. Buat Database

Buat database baru dengan nama: `latihan` di MySQL.
abis itu export file sql nya

---

### 5. Jalankan Migrasi

```bash
php artisan migrate
```

---

### 6. Jalankan Server

```bash
php artisan serve
```

Akses proyek kamu di browser:

```
http://127.0.0.1:8000
```

---

## 🙌 Kontribusi

Pull request dan issue sangat diterima! Jangan lupa star ⭐ jika proyek ini bermanfaat.

---

## 📄 Lisensi

Proyek ini bebas digunakan untuk keperluan pembelajaran.
