# Praktek React Router

> **Panduan Instalasi:**
>
> 1. Clone repository ini terlebih dahulu menggunakan perintah berikut (jangan lupa tambahkan spasi dan titik di akhir command agar ter-clone langsung ke direktori saat ini jika kamu memilih untuk membuat folder terlebih dahulu):
>    ```bash
>    git clone <url-repository-anda>
>    ```
> 2. Jalankan perintah berikut di terminal untuk menginstal dependencies:
>    ```bash
>    npm install
>    ```

## 📌 Fitur Utama

- **🏠 Home:**
  Halaman utama yang menyambut pengguna dengan selamat datang dan tampilan yang informatif.

- **👥 Santri Group (Dynamic Sidebar):**
  - **Sidebar Persisten:** Sidebar tetap muncul dan tidak ter-render ulang saat berpindah menu. Sidebar ini juga akan **tetap muncul secara konsisten** bahkan saat pengguna mengakses halaman **Santri Detail**.
  - **Menu Sidebar:**
    - **List:** Menampilkan daftar santri dalam bentuk _SantriCard_ (3 data). Klik pada _SantriCard_ untuk navigasi ke halaman `SantriDetail`.
    - **Nilai:** Halaman yang menampilkan tulisan "Daftar Nilai Santri".
    - **Absensi:** Halaman yang menampilkan tulisan "Absensi Santri".
  - **Santri Detail:** Halaman detail yang menampilkan informasi spesifik berdasarkan ID santri yang dipilih menggunakan hooks `useParams`, di mana struktur layout sidebar tetap terjaga.

- **ℹ️ About:**
  Halaman informasi tentang website beserta kontak sederhana.

- **🚫 Not Found:**
  Penanganan untuk route yang tidak terdaftar (404 Page).
