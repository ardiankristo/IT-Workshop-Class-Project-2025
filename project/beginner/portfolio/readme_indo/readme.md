# Situs Web Portofolio Pertamaku

Selamat datang di template situs web portofolio pribadi Anda\! Proyek ini membantu Anda membuat situs web kustom menggunakan HTML, CSS (Tailwind CSS), dan JavaScript. Pamerkan keterampilan, pencapaian, dan kepribadian Anda dengan fitur-fitur seperti animasi gulir yang mulus, efek hover interaktif, dan desain responsif.

Mari jadikan ini milik Anda secara unik\!

## 🚀 Cara Memulai

1.  **Unduh Kode:** Salin seluruh kode HTML ke dalam file `index.html` di komputer Anda.
2.  **Buka di Peramban:** Klik dua kali `index.html` untuk melihat situs web Anda.
3.  **Mulai Kustomisasi\!** Ikuti komentar "TODO" di file `index.html` dan langkah-langkah di bawah ini.

## 🎨 Panduan Personalisasi (Daftar TODO)

### Kustomisasi Tingkat Pemula

  * **1. Judul Situs Web:** Ubah `<title>` di bagian `<head>` (misalnya, `Portofolio Keren [Nama Anda]`).
  * **2. Judul Utama:** Perbarui `<h1>` di bagian Hero (misalnya, `Portofolio [Nama Anda]`).
  * **3. Slogan:** Personalisasi slogan `<p>` di bawah judul utama.
  * **4. Bagian Tentang Saya:**
      * Ubah judul `About Me` jika diinginkan.
      * Tulis ulang paragraf untuk menjelaskan diri Anda, minat Anda, dan apa yang Anda sukai.
  * **5. Bagian Keterampilan Saya:**
      * Perbarui judul `My Skills`.
      * **Edit Keterampilan yang Ada:** Ubah `<h3>` untuk judul keterampilan dan `<p>` untuk deskripsi.
      * **Ganti Ikon:** Gunakan ikon dari [Font Awesome Free Icons](https://fontawesome.com/v5/search?m=free) dengan memperbarui kelas `<i>` (misalnya, `fas fa-camera`).
      * **Tambahkan Keterampilan Lain:** Salin, tempel, dan kustomisasi blok `div` keterampilan.
  * **6. Bagian Pencapaian Saya:**
      * Perbarui judul `My Achievements`.
      * **Edit Pencapaian yang Ada:**
          * **Tambahkan Gambar:** Ganti URL `src` dari tag `<img>` dengan gambar Anda sendiri (tangkapan layar, foto proyek, sertifikat, seni digital). Gunakan `https://placehold.co/600x350/YOUR_COLOR/YOUR_TEXT_COLOR?text=Your+Text` sebagai placeholder.
          * Ubah `<h3>` untuk judul pencapaian dan `<p>` untuk deskripsi.
      * **Tambahkan Pencapaian Lain:** Salin, tempel, dan kustomisasi blok `div` pencapaian.
  * **7. Bagian Mari Berhubungan\!:**
      * Ubah judul `Let's Connect!` dan paragraf deskriptif.
      * **Tautan Email:** Perbarui `href="mailto:your.email@example.com"` ke alamat email Anda yang sebenarnya.
      * **Tautan Media Sosial:** Ganti `href="#"` dengan URL profil LinkedIn, GitHub, Twitter (atau lainnya) Anda. Hapus ikon yang tidak digunakan.
  * **8. Footer:** Kustomisasi teks hak cipta di bagian `<footer>`.

### Tingkat Menengah Bonus (Tantang Diri Anda\!)

  * **1. Tambahkan Tombol untuk Menggulir ke Bagian Tertentu:**
      * Di bagian `<header>`, di bawah tombol "Explore My Work", tambahkan tag `<a>` lainnya.
      * **Contoh Kode:**
        ```html
        <a
            onclick="scrollToSection('contact')"
            class="bg-gray-600 hover:bg-gray-500 text-white font-bold py-3 px-8 rounded-full shadow-lg transform hover:scale-105 transition-all duration-300 ease-in-out cursor-pointer mt-4"
        >
            Hubungi Saya <i class="fas fa-paper-plane ml-2"></i>
        </a>
        ```
      * Sesuaikan `'contact'` menjadi `'skills'` atau `'achievements'` untuk menggulir ke bagian lain.
  * **2. Buat Favicon (Ikon Situs Web):**
      * Buat gambar kecil (`favicon.ico` atau `favicon.png`) menggunakan generator favicon online atau desain Anda sendiri.
      * Tambahkan baris ini di bagian `<head>` (sekitar baris 7):
        ```html
        <link rel="icon" href="path/to/your/favicon.ico" type="image/x-icon">
        ```
      * Perbarui `href` ke jalur relatif file favicon Anda.
  * **3. Sebarkan Situs Web Anda (Jadikan Dapat Diakses Publik\!):**
      * Cari "free website hosting service" (misalnya, GitHub Pages, Netlify, Vercel).
      * Umumnya melibatkan pembuatan akun, mengunggah `index.html` dan gambar Anda, dan mengikuti langkah-langkah penyebaran mereka.

Selamat bersenang-senang membuat portofolio Anda bersinar\! Ini adalah langkah yang fantastis ke dunia pengembangan web.