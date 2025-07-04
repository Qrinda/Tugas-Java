 🛍️ TokoATK - Aplikasi Toko Alat Tulis Kantor

**TokoATK** adalah aplikasi berbasis web yang dikembangkan dalam mata kuliah **Java Lanjutan** semester 6 oleh **Rinda Tiara (L2022)**. Aplikasi ini dirancang untuk membantu pengelolaan toko alat tulis kantor, termasuk manajemen produk, stok, transaksi penjualan, dan pengguna.

## 📌 Fitur Utama

* ✅ Manajemen Produk (Tambah, Edit, Hapus)
* ✅ Kategori Jenis Produk
* ✅ Stok Masuk & Keluar
* ✅ Transaksi Penjualan
* ✅ Laporan Penjualan
* ✅ Manajemen User (Admin/Kasir)
* ✅ Otentikasi Login

## 🛠️ Teknologi yang Digunakan

* **Java** (JDK 11)
* **JSP & Servlet**
* **JDBC** untuk koneksi database
* **MySQL** sebagai database
* **HTML/CSS/JS** untuk frontend
* **NetBeans** (build tool Ant)

## 🗂️ Struktur Folder

```
TokoATK/
├── src/
│   └── model/           → Kelas Java untuk entitas (Produk, User, dll)
│   └── controller/      → Servlet untuk routing & logic
├── web/
│   ├── Login.jsp
│   ├── dashboard/
│   ├── produk/
│   ├── stok/
│   ├── transaksi/
├── database.sql         → File SQL skema dan data awal
```

## ⚙️ Cara Menjalankan

1. **Clone repository ini** atau ekstrak `.zip` project ke lokal.
2. **Import ke NetBeans** sebagai project Java Web (Ant).
3. **Atur koneksi database** di file `DB.java`:

   ```java
   String url = "jdbc:mysql://localhost:3306/tokoatk";
   String user = "root";
   String pass = "";
   ```
4. **Jalankan MySQL** dan import `database.sql`.
5. **Run project** dari NetBeans → akses via browser `http://localhost:8084/TokoATK`.

## 👩‍🎓 Tentang Pengembang

**Nama:** Rinda Tiara
**Kelas:** L2022
**Mata Kuliah:** Java Lanjutan
**Semester:** 6
**Kampus:** STMIK Mardira Indonesia


