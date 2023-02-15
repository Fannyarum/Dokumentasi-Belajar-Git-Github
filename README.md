# Dokumentasi-Belajar-Git-Github
Dokumentasi selama pembelajaran dasar git dan github

# Apa itu Git dan Github
 - **GIT** yakni perangkat lunak yang digunakan untuk mengelola versi source code program dengan menentukan baris serta kode yang akan ditambahkan atau diganti. 
- **GitHub** yaitu website  yang digunakan untuk menyimpan dan mengelola kode suatu project. Anda dapat membuat atau mengupload kode Anda ke server  GitHub dan kemudian melakukan coding secara online hingga kolaborasi.
- **Perbedaan Git dan Github** Git adalah alat yang digunakan untuk membuat hidup programmer lebih mudah, sementara GitHub adalah layanan yang digunakan untuk meng-host proyek Git. 

## Getting Started
Membuat akun github dan masukkan akun github ke visual studio code dan install git. Ketika install, editor default yang digunakan git sesuai dengan text editor anda yang digunakan.

## Cloning Repository to Local

Download GitHub CLI di [cli.github.com](https://cli.github.com/) dan Install GitHub CLI. Klik repo yang akan di clone, klik code dan salin clone url di GitHub CLI. Buka cmd ke direktory yang dituju, ketik git clone kemudian paste. 
-   **git clone**  
    Perintah git clone digunakan untuk checkout repositori.  Gunakan:
    ``git clone /path/to/repository``

## Commit dan Push

Buka repo yang sudah anda clone dengan text editor, edit file tersebut, klik gambar fork di sebelah kiri kemudian commit. Jangan lupa config di cmd.
-   **git config**  
    Salah satu perintah git yang paling banyak digunakan adalah  **git config**, yang bisa digunakan untuk mengatur konfigurasi tertentu sesuai keinginan pengguna, seperti email, algoritma untuk diff, username, format file, dll. Untuk username dan email gunakan: 
    
    ``git config --global user.name "Fannyarum"``
   `` git config --global user.email fannysiaplg30@gmail.com``
   
    Cek di pull request klik commit & push dan beri nama commit tersebut.

## Check 
Gunakan perintah berikut di cmd:
- **git remote**  
Perintah git remote akan membuat user terhubung ke remote repository. Perintah berikut ini akan menampilkan repository yang sedang dikonfigurasi.
``git remote -v``

-   **git push**  
    git push adalah perintah git dasar lainnya. Push akan mengirimkan perubahan ke master branch dari remote repository yang berhubungan dengan direktori kerja Anda. Misalnya:
``git push origin master``
-   **git pull**  
    Untuk menggabungkan semua perubahan yang ada di remote repository ke direktori lokal, gunakan perintah pull:
    
    ``git pull upstream master``
