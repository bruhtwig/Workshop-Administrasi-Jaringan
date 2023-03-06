<!-- Cover Depan -->
<div align="center">
  <h2>LAPORAN PRAKTIKUM<br/><br/>WORKSHOP ADMINISTRASI JARINGAN</h2>
  <p align="center">
    <b>Dosen Pengampu :</b>
    <br>
    Dr. Ferry Astika Saputra ST, M.Sc
    <br><br>
    <b>Disusun Oleh :</b>
    <br>
    Emha Aji Putra Zaman <br>
    3121600042 <br>
    2 D4 IT B <br>
  </p>
</div>

<b>1. Evolusi  Sistem Operasi</b>
<p align="justify">Sistem Operasi (Operating System) telah mengalami evolusi yang sangat signifikan sejak diciptakan pertama kali. Awalnya, sistem operasi hanya berfungsi untuk mengelola perangkat keras (hardware) seperti memori dan pemrosesan data, namun seiring dengan waktu dan berkembangnya teknologi, sistem operasi juga memainkan peran penting dalam mengelola software dan menyediakan antarmuka pengguna yang lebih interaktif.</p>
<p align="justify">Berikut adalah beberapa titik penting dalam evolusi sistem operasi:</p>
<p align="justify">Sistem Operasi Batch (1950-an-1960-an): Sistem operasi pertama yang diciptakan adalah sistem operasi batch. Sistem ini memungkinkan pengguna untuk mengumpulkan pekerjaan mereka dalam satu file, dan sistem operasi akan memproses file tersebut secara otomatis. Namun, sistem ini tidak interaktif dan tidak memiliki antarmuka pengguna.</p>
<p align="justify">Sistem Operasi Time-Sharing (1960-an-1970-an): Sistem operasi Time-Sharing memungkinkan beberapa pengguna untuk menggunakan sistem secara bersamaan. Sistem ini juga memperkenalkan antarmuka pengguna interaktif dan beberapa perintah yang lebih mudah digunakan.</p>
<p align="justify">Sistem Operasi Personal Computer (1980-an): Dengan munculnya komputer pribadi, sistem operasi seperti DOS (Disk Operating System) dan MacOS mulai populer. Sistem operasi ini memungkinkan pengguna untuk mengakses komputer secara pribadi dan mudah digunakan.</p>
<p align="justify">Sistem Operasi Jaringan (1990-an-2000-an): Sistem operasi jaringan, seperti Windows NT dan Unix, memungkinkan pengguna untuk terhubung dengan jaringan komputer dan berbagi sumber daya seperti printer dan file.</p>
<p align="justify">Sistem Operasi Mobile (2000-an-sekarang): Dengan munculnya ponsel pintar dan tablet, sistem operasi mobile seperti iOS dan Android menjadi populer. Sistem operasi ini dirancang untuk mendukung perangkat yang lebih kecil dan mudah digunakan dalam perangkat mobile.</p>
<p align="justify">Ubuntu dan Debian adalah dua jenis sistem operasi Linux yang sangat populer dan sering digunakan di lingkungan komputasi. Keduanya memiliki beberapa perbedaan dan kesamaan, meskipun keduanya berasal dari keluarga distribusi Linux yang sama. Berikut adalah penjelasan singkat tentang Ubuntu dan Debian:</p>
<p align="justify">Ubuntu: Ubuntu adalah sistem operasi Linux berbasis Debian yang dikembangkan oleh Canonical Ltd. Ubuntu dirancang untuk mudah digunakan, aman, dan fleksibel. Ubuntu memiliki antarmuka desktop Unity yang intuitif dan mudah digunakan, dan menyediakan banyak perangkat lunak yang tersedia secara gratis melalui repositori bawaan Ubuntu. Ubuntu juga terkenal karena dukungan jangka panjang dan pembaruan keamanan.</p>
<p align="justify">Debian: Debian adalah sistem operasi Linux yang berfokus pada stabilitas dan keandalan. Debian adalah proyek yang bersifat komunitas dan tidak terkait dengan perusahaan tertentu. Debian menawarkan banyak pilihan lingkungan desktop dan aplikasi, dan menyediakan lebih dari 50.000 paket software yang tersedia melalui repositori Debian.</p>

<b>2. Su</b>
<p align="justify">
  "su" (singkatan dari "switch user") memungkinkan pengguna untuk beralih ke akun root (atau akun pengguna lain yang telah ditentukan) dengan memasukkan kata sandi root. Setelah masuk ke akun root, pengguna dapat menjalankan perintah dengan izin khusus yang tidak dapat dilakukan oleh pengguna biasa. Namun, pengguna harus sangat berhati-hati saat menggunakan perintah "su" karena pengguna akan memiliki akses penuh ke sistem dan dapat mengubah atau menghapus file sistem yang sangat penting.
</p>

<b>3. Sudo</b>
<p align="justify">
  "sudo" (singkatan dari "superuser do") adalah alternatif yang lebih aman daripada perintah "su". Ketika pengguna menggunakan "sudo" untuk menjalankan perintah, ia hanya memerlukan kata sandi pengguna untuk memverifikasi identitasnya. Kemudian, pengguna dapat menjalankan perintah dengan izin khusus, seperti memperbarui sistem, menginstal program, atau menghapus file sistem. Perintah "sudo" dapat dikonfigurasi oleh administrator sistem untuk membatasi akses pengguna atau grup pengguna tertentu ke perintah atau tindakan tertentu.
</p>

<b>4. Package Maintenance</b>
<p align="justify">
  Package maintenance di linux adalah proses pemeliharaan dan manajemen paket-paket perangkat lunak yang telah terinstal pada sistem operasi. Pada Linux Debian, paket-paket perangkat lunak tersebut disimpan dalam repositori. Beberapa hal yang termasuk dalam package maintenance di Linux antara lain:
</p>

1. Memperbarui paket: Proses ini melibatkan pengunduhan dan instalasi pembaruan paket terbaru yang telah dirilis oleh pengembang perangkat lunak. Ini bertujuan untuk memastikan bahwa sistem operasi memiliki versi terbaru dari paket yang terinstal dan juga untuk memperbaiki bug dan keamanan yang teridentifikasi.
2. Memasang paket: Proses ini melibatkan penginstalan paket baru pada sistem operasi. Paket-paket tersebut bisa berupa aplikasi, driver, atau paket-paket lainnya yang dibutuhkan untuk menjalankan suatu program.
3. Menghapus paket: Proses ini melibatkan penghapusan paket yang tidak dibutuhkan atau sudah tidak diperlukan lagi dari sistem operasi. Ini membantu dalam menghemat ruang penyimpanan dan juga memastikan sistem operasi tetap bersih dan terorganisir.
4. Memperbaiki paket: Proses ini melibatkan perbaikan paket-paket yang rusak atau bermasalah pada sistem operasi.

Package maintenance sangat penting untuk menjaga sistem operasi agar tetap aman dan stabil, serta memastikan bahwa paket-paket perangkat lunak yang terinstal berjalan dengan baik dan memenuhi persyaratan sistem. Ubuntu menyediakan berbagai alat manajemen paket yang mudah digunakan, seperti apt-get, aptitude, dan synaptic, yang memudahkan pengguna dalam melakukan tugas pemeliharaan paket pada sistem operasi.

-> Setting Repository
<p align="justify">
  Mengatur repository pada linux dilakukan dengan mengubah isi file /etc/apt/sources.list. Sebagai contoh, berikut langkah-langkah mengatur repository pada Debian:
</p>
1. Buka terminal pada Debian dengan menekan tombol Ctrl + Alt + T.
2. Ketik perintah "sudo nano /etc/apt/sources.list" untuk membuka file sources.list dalam editor teks nano.
3. Pada file sources.list, Anda akan melihat daftar repository yang sudah terdaftar di Ubuntu. Setiap repository dinyatakan dengan baris yang dimulai dengan "deb" atau "deb-src".
4. Untuk menambahkan repository baru, salin dan tempelkan baris berikut di akhir file sources.list:
5. deb [sumber]://[nama server]/[direktori]/[versi] [distro] [main] Contoh: deb http://deb.debian.org/debian/ bullseye main
6. Baris di atas menunjukkan repository utama Debian yang tersedia pada versi Bullseye.
7. Simpan dan keluar dari editor teks nano dengan menekan tombol Ctrl + X, kemudian tekan Y untuk menyimpan perubahan dan tekan Enter untuk keluar dari editor.
8. Kemudian, jalankan perintah "sudo apt-get update" untuk memperbarui daftar repository Debian dengan repository baru yang telah ditambahkan.
9. Setelah itu, Anda dapat menggunakan perintah "sudo apt-get install" untuk menginstal paket atau program yang tersedia pada repository yang telah ditambahkan.

->Instalasi Package Linux
a) mc
<p align="justify">
  MC (Midnight Commander) adalah sebuah aplikasi file manager untuk sistem operasi Linux yang tersedia sebagai package (pakage) pada repositori Linux.
</p>

b) net-tools
<p align="justify">
  Paket "net-tools" adalah paket yang berisi utilitas jaringan penting seperti ifconfig, route, netstat dan lain-lain.
</p>

c) htop
<p align="justify">
  htop adalah sebuah utilitas yang digunakan untuk memonitor kinerja sistem pada sistem operasi Linux. Htop akan menampilkan antarmuka pengguna grafis yang dapat digunakan untuk memonitor kinerja sistem, melihat penggunaan CPU,memori, disk, dan lain-lain.
</p>
