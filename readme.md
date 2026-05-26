# Website Development Plan: SYKA Web Portal

Proyek ini merupakan rancangan pengembangan ekosistem website SYKO, yang akan memiliki tiga landing page utama beserta sistem backend manajemen (CMS) yang saling terintegrasi.

## 1. Struktur Halaman Utama (Landing Pages)

### 1.1. SYKA GROUP
Halaman ini berfungsi sebagai Company Profile utama yang menjelaskan perusahaan secara umum.
*   **Konten & Fitur:**
    *   Company Profile (Sejarah, Visi, Misi, Tujuan perusahaan).
    *   Media Partner.
    *   Afiliasi.
    *   (Konten informasi publik lainnya akan ditambahkan secara bertahap saat konsep sudah matang).
*   **Hak Akses:** Publik (Tidak perlu login).

### 1.2. SYKA TRADING
Halaman ini ditujukan sebagai portal utama untuk layanan trading, membedakan antara pengunjung umum dan nasabah.
*   **Konten & Fitur:**
    *   **Bagi Non-Subscriber (Publik):** Akan ditampilkan halaman Company Profile terkait layanan trading (Desain dan fitur dapat berubah/ditambahkan ke depannya).
    *   **Bagi Subscriber:** Disediakan fitur **Login**. Setelah masuk, pengguna dapat mengakses **Modul Trading CMS** terbaik dan eksklusif yang disediakan oleh SYKO.

### 1.3. SYKA EVENT ORGANIZER
Halaman ini difokuskan pada layanan manajemen acara (event) dan pemesanan layanan.
*   **Konten & Fitur:**
    *   **Portfolio Event:** Halaman berisi galeri dan berita (news) mengenai event-event yang telah sukses diselenggarakan.
    *   **Detail Layanan:** Penjelasan mendetail terkait profil event organizer dan setiap jenis layanan yang ditawarkan.
    *   **Form Pemesanan / Kontak:** Form pengisian detail yang dapat diakses oleh masyarakat umum untuk melakukan booking layanan atau menghubungi tim (lebih lengkap dari sekadar form kontak biasa).
*   **Hak Akses:** Publik (Tidak perlu login).

## 2. Sistem Backend & Database (CMS / Admin Panel)

Seluruh komponen pada tiap *section* dari ketiga landing page di atas terhubung ke sebuah sistem database backend yang *dynamic*.
*   **Hak Akses Manajemen:**
    *   **Super Admin:** Memiliki kontrol penuh atas semua sistem, termasuk manajemen admin lain, akses ke database utama, perubahan konten inti, hingga pengaturan sistem trading.
    *   **Admin:** Memiliki kontrol operasional harian, seperti mengelola form pemesanan yang masuk, memperbarui portfolio/galeri, hingga mengubah teks pada landing page tertentu sesuai izin yang diberikan.

---
*Catatan: Dokumen ini adalah rancangan pengembangan awal (draft) dan masih sangat terbuka untuk perbaikan, penambahan, dan penyempurnaan fitur ke depannya.*
