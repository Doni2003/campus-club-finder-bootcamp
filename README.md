# Campus Club Finder

## 📜 Deskripsi

Campus Club Finder adalah sebuah aplikasi web satu halaman (Single-Page Application) yang dibangun untuk membantu mahasiswa menemukan, mempelajari, dan bergabung dengan berbagai klub yang ada di kampus. Aplikasi ini murni berjalan di sisi klien (client-side) dan menggunakan Local Storage untuk menyimpan data klub yang telah diikuti oleh pengguna.

## 📸 Tampilan Aplikasi 

Berikut adalah beberapa tampilan dari halaman utama aplikasi:

**1. Halaman Utama (Home Page)**
*Tampilan hero section yang menyambut pengguna.*
![image](public/images/Homepage.png)


**2. Halaman Daftar Klub (Clubs Page - Grid & List View)**
*Pengguna dapat melihat semua klub, melakukan sorting, dan mengubah tampilan antara grid dan list.*
![image](public/images/ClubPage.png)
![image](public/images/ClubPage2.png)


**3. Halaman Detail Klub (Club Detail Page)**
*Menampilkan informasi lengkap tentang klub, acara, dan tombol untuk bergabung.*
![image](public/images/DetailPage.png)


**4. Halaman About & 404**
*Halaman informasi dan halaman not found yang fungsional.*
![image](public/images/AboutPage.png)
![image](public/images/NotFoundPage.png)


## ✨ Fitur-fitur

- **Menampilkan Daftar Klub:** Melihat 5 klub mahasiswa default yang tersedia.
- **Halaman Detail:** Setiap klub memiliki halaman detailnya sendiri dengan deskripsi lengkap dan daftar acara.
- **Sorting:** Mengurutkan daftar klub berdasarkan nama (A-Z atau Z-A).
- **View Toggle:** Ubah tampilan daftar klub antara mode Grid dan List.
- **Gabung Klub:** Pengguna dapat bergabung dengan klub, dan pilihan ini akan tersimpan di Local Storage browser.
- **Navigasi Mulus:** Berpindah antar halaman tanpa refresh menggunakan React Router.
- **Desain Responsif:** Tampilan yang dioptimalkan untuk perangkat mobile, tablet, dan desktop.

## 🛠️ Tech Stack

Proyek ini dibangun menggunakan teknologi modern berikut:

- **[Vite](https://vitejs.dev/):** Sebagai build tool dan development server yang sangat cepat.
- **[React](https://reactjs.org/):** Library JavaScript untuk membangun antarmuka pengguna.
- **[React Router](https://reactrouter.com/):** Untuk menangani routing di sisi klien.
- **[Tailwind CSS](https://tailwindcss.com/):** Kerangka kerja CSS utility-first untuk styling.
