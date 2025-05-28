# 📚 Book Tracker App
# 🧑‍💻 My Chosen Role

**Frontend Developer (UI/UX)**

Saya memilih peran sebagai pengemban frontend karena memiliki ketertarikan yang kuat terhadap UI/UX design. Selain itu, saya juga memiliki pengalaman menggunakan Figma untuk merancang Interface yang estetik dan fungsional. Di dalam proyek ini, saya menggunakan Vite, Tailwind CSS, dan React.

## 🛠️ How To Run My Part
### ✅ Prasyarat:
Sebelum memulai, pastikan Anda memiliki perangkat lunak berikut yang terinstal pada komputer Anda:
- Python 3.13.3
- Node.js 16.x
- Git x64

## 🚀 Steps to Run a Project 
# Clone repository (jika belum melakukannya):
git clone 
cd Book-app-/frontend

# Install semua dependensi yang dibutuhkan oleh proyek:
npm install

# Jalankan aplikasi secara lokal:
npm run dev 

Aplikasi kini dapat diakses di browser melalui http://localhost:8080/ untuk melihat dan menguji User Interface.

## ✨ Fitur

### 1. 🔐 Halaman Login (User Authentication)
Deskripsi: Halaman login ini menyediakan antarmuka yang sederhana untuk pengguna memasukkan email dan password.

Fitur:

Saat ini, halaman ini hanya berupa mock UI dan belum terhubung dengan backend.

Validasi dasar dilakukan untuk memastikan data yang dimasukkan oleh pengguna sesuai.

Desain menggunakan Tailwind CSS untuk memastikan halaman login responsif di berbagai perangkat.

Langkah Akses:

Setelah membuka aplikasi, Anda akan diarahkan ke halaman login.

Masukkan email dan password pada kolom yang disediakan (perhatikan bahwa pada tahap ini, fitur login masih bersifat mock dan tidak terhubung ke backend).

📍 Lokasi: src/pages/Login.tsx

## 2. ⚙️ Halaman Pengaturan Pengguna (User Settings)
Deskripsi: Halaman ini memungkinkan pengguna untuk memperbarui informasi pribadi mereka seperti nama, alamat email, dan password.

Fitur:

Halaman pengaturan dirancang menggunakan card UI yang responsif, sehingga mudah diakses baik di desktop maupun perangkat mobile.

Tombol "Save Changes" disediakan, namun belum terhubung dengan backend (fungsi ini hanya tersedia pada UI).

Langkah Akses:

Setelah berhasil login, pengguna dapat mengakses halaman pengaturan dari menu utama atau dengan mengklik ikon pengaturan di pojok kanan atas.

Pengguna dapat mengubah nama, email, dan password mereka, dan menekan tombol "Save Changes" untuk menyimpan perubahan tersebut (meskipun saat ini tidak terhubung ke backend).

📍 Lokasi: src/pages/Settings.tsx

## 3. 📊 Halaman Insight Pengguna (User Insights)
Deskripsi: Halaman ini menampilkan statistik terkait aktivitas membaca pengguna, termasuk total buku yang telah dibaca, buku yang sedang dibaca, dan rata-rata bacaan per bulan.

Fitur:

Statistik yang ditampilkan berupa data dummy untuk saat ini, dengan layout yang bersih dan mobile-friendly.

Tampilan yang terstruktur untuk memudahkan pengguna dalam melihat progress mereka.

Langkah Akses:

Setelah login, pengguna dapat mengakses halaman Insight langsung dari dashboard atau menu.

Statistik akan ditampilkan secara otomatis dan akan mencakup metrik seperti total buku yang telah dibaca dan rata-rata buku yang dibaca per bulan.

📍 Lokasi: src/pages/Insight.tsx

## 📝 Notes
* Halaman UI yang dibuat ini bertujuan untuk memberikan gambaran visual awal bagi aplikasi, namun belum terhubung ke backend. Semua data yang ditampilkan, seperti statistik buku atau informasi pengguna, masih berupa data palsu (dummy).
* Struktur komponen dan file diatur sedemikian rupa agar aplikasi dapat dengan mudah berkembang dan diperluas dengan penambahan fitur atau integrasi backend nanti nya.
* Penggunaan Tailwind CSS memungkinkan pengembangan antarmuka yang fleksibel, dengan desain yang konsisten dan cepat dalam penerapan perubahan
* Semua komponen UI yang telah dibuat dirancang untuk dapat diimprovisasi lebih lanjut agar sesuai dengan kebutuhan aplikasi seiring berjalannya waktu, menjadikan proyek ini siap untuk penerapan lebih lanjut dalam pengembangan fitur-fitur backend.
