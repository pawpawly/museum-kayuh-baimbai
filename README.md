[![Contributors](https://img.shields.io/github/contributors/pawpawly/museum-kayuh-baimbai)](https://github.com/pawpawly/museum-kayuh-baimbai/graphs/contributors)
[![Forks](https://img.shields.io/github/forks/pawpawly/museum-kayuh-baimbai)](https://github.com/pawpawly/museum-kayuh-baimbai/network/members)
[![Stars](https://img.shields.io/github/stars/pawpawly/museum-kayuh-baimbai)](https://github.com/pawpawly/museum-kayuh-baimbai/stargazers)
[![Issues](https://img.shields.io/github/issues/pawpawly/museum-kayuh-baimbai)](https://github.com/pawpawly/museum-kayuh-baimbai/issues)
[![License](https://img.shields.io/github/license/pawpawly/museum-kayuh-baimbai)](LICENSE)

# Project Magang - CodeIgniter 4

Proyek ini dikembangkan selama masa magang di **DISBUDPORAPAR bidang kebudayaan**. Website ini dibuat menggunakan **CodeIgniter 4** sebagai framework backend dan **Tailwind CSS** untuk desain antarmuka.

---

## 📋 Fitur Utama
- Struktur kode bersih dan modular menggunakan **CodeIgniter 4**.
- Desain antarmuka responsif menggunakan **Tailwind CSS**.


---

## 🚀 Instalasi

Ikuti langkah-langkah di bawah ini untuk menjalankan proyek secara lokal:

### Prasyarat
- **PHP** >= 7.4
- **Composer**
- **Web Server** 

### Langkah Instalasi
1. **Clone repositori**:
   ```bash
   git clone https://github.com/pawpawly/museum-kayuh-baimbai.git
   ```

2. **Masuk ke direktori proyek**:
   ```bash
   cd museum-kayuh-baimbai
   ```

3. **Install dependencies** menggunakan Composer:
   ```bash
   composer install
   ```

4. **Update dependencies**:
   ```bash
   composer update
   ```

5. **Generate application key**:
   ```bash
   php spark key:generate
   ```

6. **Buat database baru**:
   ```bash
   php spark db:create museum_db
   ```

7. **Edit konfigurasi database** di file `.env`:
   ```plaintext
   #--------------------------------------------------------------------
   # DATABASE
   #--------------------------------------------------------------------
   database.default.hostname = localhost
   database.default.database = museum_db
   database.default.username = root
   database.default.password = 
   database.default.DBDriver = MySQLi
   database.default.DBPrefix =
   database.default.port = 3306
   ```

8. **Jalankan migrasi database**:
   ```bash
   php spark migrate
   ```

9. **Tambahkan data awal dengan seeder**:
   ```bash
   php spark db:seed UserSeeder
   ```
   **Username**: `superadminn`  
   **Password**: `1`

10. **Sistem informasi siap digunakan**.
    
    Akses halaman login di:
    ```
    http://localhost:8080/login
    ```

---

## 📂 Struktur Direktori
Berikut adalah struktur utama proyek:

```
museum-kayuh-baimbai/
├── app/                   # Direktori utama aplikasi
│   ├── Controllers/       # Controller utama
│   ├── Models/            # Model untuk database
│   ├── Views/             # Template dan view frontend
│   └── Config/            # Konfigurasi aplikasi
├── public/                # Aset publik (CSS, JS, dll)
├── writable/              # Direktori writable (cache, logs, dll)
├── .env                   # File konfigurasi environment
├── composer.json          # Dependencies composer
└── README.md              # Dokumentasi proyek
```

---

## 🎨 Teknologi yang Digunakan
- **Backend**: CodeIgniter 4
- **Frontend**: Tailwind CSS
- **Database**: MySQL
- **Tools**: Composer, Git

---

## 🛠 Pengembangan Selanjutnya
Berikut adalah beberapa fitur yang akan dikembangkan di masa mendatang:
- [ ] Flipbook
- [ ] 3D Virtual Tour
- [ ] Tampilan Untuk Mobile Device

---

# 👥 Tim Pengembang
| Nama | Role | Sosial Media |
|------|------|--------------|
| Muhammad Ganang Ramadhan | Frontend | [![Instagram](https://img.shields.io/badge/Instagram-%23E4405F.svg?logo=Instagram&logoColor=white)](https://instagram.com/username) [![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/username) [![GitHub](https://img.shields.io/badge/GitHub-%23121011.svg?logo=github&logoColor=white)](https://github.com/pawpawly) |
| Muhammad Mashaan Navarin | Backend | [![Instagram](https://img.shields.io/badge/Instagram-%23E4405F.svg?logo=Instagram&logoColor=white)](https://instagram.com/username) [![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/username) [![GitHub](https://img.shields.io/badge/GitHub-%23121011.svg?logo=github&logoColor=white)](https://github.com/RinnHehe) |

---

## 📧 Kontak
Jika ada pertanyaan atau masukan terkait proyek ini, silakan hubungi:

- **Nama**: Muhammad Ganang Ramadhan
- **Email**: - 

---

## ⭐ Dukungan
Jika proyek ini membantu Anda, silakan berikan **Star** ⭐ di repositori ini. Terima kasih atas dukungan Anda!

---

**Lisensi**: Proyek ini dilisensikan di bawah [MIT License](LICENSE).
