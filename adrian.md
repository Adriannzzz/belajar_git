# Mengenai Version Control System

Version Control System adalah sistem yang mengelola suatu perubahan pada file dokumen, source code, atau kumpulan informasi lainnya. VCS mencatat setiap perubahan pada file yang dikerjakan oleh seseorang

## Apa itu Git & Github?

Git merupakan software berbasis Version Control System (VCS) yang bertugas untuk mencatat perubahan seluruh file atau repository suatu project Bukan hanya pencipta kodenya saja seperti di version control biasa.Sebenarnya, Git hanya bisa digunakan melalui command line sehingga kurang ramah untuk pemula. Namun, dengan GitHub, Anda bisa menggunakan Git melalui user interface (UI) yang mudah dipahami.
Sedangkan, GitHub adalah website yang digunakan untuk menyimpan dan mengelola kode suatu project. Anda juga dapat membuat atau mengupload kode Anda ke server GitHub dan kemudian melakukan coding secara online.Hal tersebut dimungkinkan karena GitHub dibangun atas dua sistem utama, yaitu version control dan Git.

# Membuat Akun Github

masuk ke dalam website Github menggunakan browser (safari,chrome dll) dan klik tombol **signin**
Link Github : <https://github.com/>
hasil:

3.Masukan **Username or email address and Password**
hasil:


4.jika login berhasil maka tampilan akan seperti dibawah ini
hasil:

# Buat Repository

1.masuk pada halaman github.com
hasil:


2.tekan avatar dan ketik **"New repository"**
hasil:


3.setelah menekan **"New Repository"**  silahkan masukan **"Repository name"**
hasil:

4.Lalu Klik **' Create repository'** maka repository akan dibuat
hasil:


5.Setelah membuat repository maka akan tampil seperti di gambar
hasil:

# Instalasi & Konfigurasi Git

### Intalasi
1. Unduh Git dengan membuka tautan dowload.git
2. search dan  tulis "Windows"
	hasil:

4. Setelah itu tunggu hingga muncul berkas aplikasi yang terunduh otomatis atau jika tidak
   maka pilih unduhan sesuai dengan arsitektur komputer kamu. Kalau menggunakan 64 bit, unduh yang 64 bit. Begitu juga kalau menggunakan 32bit
   hasil:

4. Setelah terunduh, lalu klik 2x berkas installer Git yang telah diunduh
	hasil:
1. Tinjau Lisensi Publik Umum GNU, dan jika kamu sudah siap untuk menginstal, klik Next.
	hasil:

2. Selanjutnya menentukan lokasi instalasi. Biarkan saja secara default, kemudian klik Next.
3. Lalu pemilihan komponen, atur saja seperti di bawah ini, lalu Next.
	hasil:
	
1.  Installer akan menawarkan untuk membuat icon start menu di layar Desktop. Cukup klik Next.
2.  Pilih editor teks yang ingin kamu gunakan ( Kita akan menggunakan Visual Studio Code ) untuk Git. Setelah itu klik Next 
3. Langkah selanjutnya memungkinkan kamu untuk memilih nama yang berbeda untuk branch awal kamu. Standarnya adalah 'master'. Kecuali kamu bekerja dalam tim yang memerlukan nama berbeda, biarkan opsi default dan klik Next 
	hasil:


1. Langkah instalasi ini memungkinkan kamu untuk mengubah lingkungan PATH instalasi. PATH
    adalah set standar direktori yang disertakan saat kamu menjalankan perintah dari CMD. Biarkan pilihannya di tengah (rekomendasi) dan klik Next .
12. Installer sekarang menanyakan klien SSH mana yang ingin kamu gunakan pada git. Git sudah hadir dengan klien SSH-nya sendiri, jadi jika Anda tidak membutuhkan yang spesifik, biarkan opsi default dan klik Next.
13. Opsi selanjutnya berkaitan dengan sertifikat server. Sebagian besar pengguna harus menggunakan default, klik Next.
14. Selanjutnya konfigurasi line ending. Biarkan saja seperti ini, kemudian klik Next.
15. Lalu pemilihan terminal emulator. Pilih saja yang paling bawah, kemudian klik Next.
16. Installer sekarang menanyakan apa yang git pull harus dilakukan oleh perintah tersebut. Opsi
    default disarankan Next untuk melanjutkan instalasi.
17. Selanjutnya kamu harus memilih alat kredensial mana yang akan digunakan. Git menggunakan alat kredensial untuk mengambil atau menyimpan kredensial. Biarkan opsi default dan klik Next.
18. Selanjutnya pemilihan opsi ekstra. Klik saja Next.
19. Instaler Git mungkin menawarkan untuk menginstal fitur eksperimental, tanpa centang
    apapun, langsung saja klik Install.
20. Setelah instalasi selesai, centang kotak untuk melihat Catatan Rilis atau Luncurkan Git Bash,
    lalu klik Selesai .
 21. Untuk meluncurkan Git Bash, kamu tinggal mencari Start Menu Windows lalu Enter pada Git Bash. 
	 hasil:
	 
 1. Kemudian ketik peintah git-version
	 hasil:
# Konfigurasi Git Bash

Ada beberapa konfigurasi yang harus dilakukan sebelum mulai menggunakan Git, seperti menentukan name dan email
Jika kamu memiliki akun Github, Gitlab, Bitbucket atau yang lainnya…
maka username dan email harus mengikuti akun tersebut agar mudah diintegrasikan.

Silahkan lakukan konfigurasi sesuai dengan perintah ini.
```sh
git config --global user.name "Adriannzzz"

git config --global user.email "ryann0310@gmail.com"
```

kemudian periksa konfigurasinya dengan perintah:
```sh
git config --list
```

apabila berhasil tampil seperti digambar berikut ini, berarti konfigurasi berhasil.
	hasil:
	




# Akses Folder Proyek di git bash
sekarang adalah menghubungkan folder kita dengan github. untuk langkah awal kita akan mengubah direktori di gitbash.
```sh
$ pwd
```
hasil:


Berdasarkan pwd kita melihat bahwa direktori yang diakses adalah /c/Users/lenovo, sedangkan folder yang akan kita gunakan untuk dihubungkan ke Github berada di D. Untuk mengubahnya ikut langkah berikut:
# Membuat project pertama
pertama, buat folder bernama "belajar-git" dan buka di visual studio code
hasil:


Klik, "open folder" lalu pilih folder yang kita buat tadi
hasil:


jika sudah maka klik folder dan saya tambahkan nama file yang bernama "git.html"
hasi;:
untuk  membuat repository secara lokal atau offline di komputer kita,ketik perintah berikut.

### git init

Perintah git init berfungsi untuk membuat Repository secara offline di komputer lokal atau para developer biasa menyebutnya sebagai “Initialisasi Repo Lokal”. Jika berhasil, maka akan terdapat output seperti gambar dibawah ini.
hasil:


sebelum kita menggugah berkas project kita, kita dapat melihat status folder/file kita dengan mengetikkan
### git status
hasil:



disini kita dapat melihat dimana status file kita bahwa terdapat file baru.
sekarang kita akan mengunggah berkas project kita ke lokal dengan perintah
### git add
Perintah tersebut mengintruksikan git untuk menambahkan ( git add ) seluruh file ( . ) yang berada di folder project kita (latihan git) ke Staging Area. Staging Area adalah zona tak terlihat dimana seluruh file project bersiap untuk melalui tahap pengecekan terlebih dahulu riwayat perubahannya. Untuk pertama kali, jika kita menjalankan perintah diatas maka tidak akan mendapatkan output apapun
hasil:



selanjutnya yang harus kita lakukan adalah menyimpan riwayat atau catatan perubahannya, sebelum kita unggah ke repository online. Untuk melakukan hal tersebut, kita akan menggunakan perintah:
```sh
git commit -m "tambah file html"
```
hasil:



 Kita mengintruksikan kepada git agar git menyimpan seluruh perubahan ( git commit ) yang terjadi
 pada berkas project kita, dan perubahan tersebut bisa kita berikan judul ( -m “ Tambah File HTML”
 ) perubahannya.
 Setelah menyimpan riwayat perubahannya, selanjutnya kita ke tahap akhir, yaitu mengunggah (
 Push ) project kita dari Repository lokal ke Repository online ( Github )
 sebelum kita mengunggah project kita, kita harus membuat repository di github nya.
 >[!istilah repository]
 > Repository adalah folder untuk menyimpan berkas-berkas project kita secara online, bahkan
 setiap perubahannya akan disimpan secara otomatis. ( Seperti membuat Folder di Google
 Drive atau Onedrive )

# Membuat repository di github
 Untuk membuatnya, kita buka dan masuk menggunakan akun github yang telah didaftarkan di
 https://www.github.com - Sekarang setelah berhasil masuk, maka kita berada di halaman
 Dashboard github

untuk membuat repository,maka klik "create repository"
hasil:



Setelah itu akan ada beberapa form untuk memberikan beberapa informasi mengenai Folder (Kita
 sekarang akan menyebutnya sebagai Repository) yang akan kita buat.
 1. Repository Name
 Ini adalah form untuk memberikan nama repository project kita ( Sering kita lakukan seperti
 membuat nama Folder ), disini kita akan memberi nama repositori “latihan-git”
 2. Descriptions
 Deskripsi untuk memberikan keterangan singkat tentang repository. Disini kita akan
 memberikan deskripsi “Belajar HTML”
 3. Repository Visibility
 Seperti pada umumnya, kita bisa menyetel repository kita dengan mode Privat ( Hanya bisa
 diakses oleh pemilik repository ) atau Public ( Bisa diakses semua orang, dan bisa dilakukan
 Pull, Fork, Clone dll oleh semua orang. )
 4. Additional Options
 Ada beberapa pengaturan tambahan dibawahnya, seperti:- Add Readme File ( Membuat deskripsi repository secara detail dengan file Readme )- Add .gitignore ( Jika ini diaktifkan, maka riwayat perubahan tidak akan dicatat oleh sistem
 Git )- Choose License ( Memilih jenis lisensi untuk repository project )
 Setelah semuanya diisi maka klik tombol “Create Repository” Jika berhasil maka akan
 tampil seperti ini
 ```sh
 echo "# belajar-git">> README.md
 git init
 git add README.md
 git commit -m "first commit"
 git branch -M main
 git remote add origin https://github.com/suryadiningratRPL2/belajar.git
 git push -u origin main
```

```sh
git  remote add origin https://github.com/SuryadiNingratRPL2/belajar.git
git branch -M main
git push origin main
```
kemudian copy remote url nya

 #### git remote add origin https://github.com/SuryadiNingratRPL2/belajar.git

 Kita mengintruksikan kepada git agar git menghubungkan ( remote ) dan menambahkan ( add )
 repository berasal dari ( origin ) link Repository Github kita.
#### Kesimpulannya : Kita mengintruksikan git untuk menambahkan akses repository yang berasal
 dari Github ke komputer lokal kita dengan menggunakan perintah git remote add origin linkrepo
github.
hasil:



#### git push origin main
setelah berhasil  maka akan muncul output seperti ini.
hasil:



sebelumnya:\
```sh
...or create a new repository on the command line
 echo "belajar-git">> README.md
 git init
 git add README.md
 git commit -m "first commit"
 git branch -M main
 git remote add origin https://github.com/suryadiningratRPL2/belajar.git
 git push -u origin main
```
```sh
...or push an existing repository from the command line
git  remote add origin https://github.com/SuryadiNingratRPL2/belajar.git
git branch -M main
git push origin main
```
```sh
...or import code from another repository
you can intialize this repository with code from a subversion. mercurial. or TFS project
[import code]
```
setelah di push:
hasill:



# Update File Ke Github

#### langkah 1:
inisialisasi sebuah respositori Git baru kedalam direktori saat ini dengan perintah
```sh
git.init
```
hasil:



Jika sudah muncul tulisan (master) setelah kita enter direktori kita maka kita sudah berhasil melakukan inisialisasi.

#### langkah 2:
sekarang buatkanlah remote repository dari repository di git ke repositori git lokal. copy terlebih dahulu link direstory git kita:
hasil:



Lalu kolaborasikan dengan perintah berikut:
```sh
git remote add origin "https://github.com/suryadiningratRPL2/belajar-git"
```
![[belajar_git/aset/Screenshot 2024-07-18 134725.png]]
#### langkah 3:
sekarang cek status commit/koneksi file ke github dengan perintah 
```sh
git status .
```
![[Screenshot 2024-08-01 131028 1.png]]
dengan demikian kita sudah selesai dan berhasil menghubungkan antara github dengan direktori kita.
#### langkah 4:
ketika ingin melakukan Update file ke Github silahkan masukan code ini:
```shell
git add .
```
hasil foto :
![[Screenshot 2024-08-01 112347 1.png]]
#### langkah 5:
ketika sudah berhasil melakukan lanjutkan kembali menggunakan code ini:
```shell
git commit -m "Awal Belajar 3"
```
hasil foto:
![[Screenshot 2024-08-01 112358 1.png]]

#### langkah 6:
setelah melakukan code diatas lanjutkan dengan langkah terakhir ini
```shell
git push origin master
```
hasil foto:
![[Screenshot 2024-08-01 112405 1.png]]

Dengan perintah git push origin master Maka kita sudah berhasil mengunggah
pesan commit perubahan kita ke dalam Github kita.

Berikut tampilannya:
 Sebelum:
 ![[Screenshot 2024-08-01 181306 1.png]]

Sesudah:
![[Screenshot 2024-08-01 154304 1.png]]

Dengan munculnya File kita pada repository Github maka kita telah berhasil menghubungkan file lokal kita dengan GitHub.
Jadi setiap kali kita melakukan perubahan pada file kita maka kita harus selalu membuat commit baru untuk menampung semua perubahan yang kita lakukan.
Contohnya pada commit sebelumnya bernama $ git commit -m "Awal belajar " maka jika kita telah melakukan perubahan kita harus membuat commit baru
dengan nama yang berbeda, yaitu "awal belajar 3"
```sh
git commit -m "awal belajar 3"
```
![[Screenshot 2024-08-01 130856 1.png]]
Setelah itu unggah kembali perubahan kita dengan perintah git push origin master
Untuk mengupdate perubahan pada repository kita.
![[Screenshot 2024-08-01 154304 1.png]]
