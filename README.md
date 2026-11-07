# 🍄 Day 1 – Proyek Workshop 2026
### Building with AI, Managing Change with GitHub

Selamat datang di repository dokumentasi Day 1 Proyek Workshop 2026 HIMATIK.

Repository ini dibuat sebagai tempat dokumentasi materi, rangkuman pembelajaran, dan catatan penting dari kegiatan workshop dengan tema **Building with AI, Managing Change with GitHub**.

Melalui kegiatan ini, peserta diperkenalkan pada penggunaan Artificial Intelligence (AI), teknik penyusunan prompt, serta Git dan GitHub sebagai alat untuk mengelola perubahan dan mengembangkan proyek perangkat lunak.

---

## 👤 Identitas Peserta

| Informasi | Keterangan |
|---|---|
| Nama | Muhammad Raka Asri |
| Kelompok | 6 – Super Mario |
| Kegiatan | Day 1 Proyek Workshop 2026 |
| Penyelenggara | HIMATIK |
| Materi Workshop | Building with AI, Managing Change with GitHub |

## 🎯 Tujuan Repository

Repository ini bertujuan untuk:

- Mendokumentasikan materi yang diperoleh selama workshop.
- Menyimpan rangkuman dan poin-poin penting pembelajaran.
- Memahami dasar penggunaan AI dalam pengembangan aplikasi.
- Mengenal Git dan GitHub sebagai alat version control.
- Menjadi arsip pembelajaran yang dapat digunakan sebagai referensi untuk kegiatan dan proyek selanjutnya.

---

# 📚 MATERI WORKSHOP

## 1. Prompt Engineering

### 1.1 Pengertian Prompt

Prompt merupakan instruksi atau masukan yang diberikan kepada model AI untuk memperoleh hasil tertentu. Prompt dapat berupa pertanyaan sederhana, kata kunci, instruksi yang kompleks, maupun potongan kode.

**Prompt Engineering** adalah proses merancang instruksi agar AI dapat menghasilkan jawaban yang lebih tepat, relevan, dan sesuai dengan kebutuhan pengguna.

### 1.2 Pentingnya Context dalam Prompt

Konteks merupakan informasi tambahan yang membantu AI memahami tujuan dan kebutuhan dari instruksi yang diberikan.

Pemberian konteks yang jelas dapat membantu AI menghasilkan jawaban yang lebih terarah dibandingkan instruksi yang terlalu umum.

Sebagai contoh, instruksi untuk membuat aplikasi akan lebih mudah dipahami apabila dilengkapi dengan tujuan aplikasi, target pengguna, fitur yang dibutuhkan, serta teknologi yang harus digunakan.

### 1.3 Struktur Prompt yang Baik

Dalam materi workshop, struktur prompt dibagi menjadi empat bagian utama:

| Komponen | Penjelasan |
|---|---|
| Role | Menentukan peran yang harus dijalankan oleh AI. |
| Task | Menjelaskan tugas yang harus dikerjakan AI. |
| Context | Memberikan informasi dan latar belakang yang diperlukan. |
| Format | Menentukan bentuk atau format hasil yang diharapkan. |

### 1.4 Contoh Penerapan Prompt

Salah satu contoh yang digunakan dalam materi adalah membuat **Student Task Planner**, yaitu aplikasi web sederhana untuk membantu mahasiswa tahun pertama mengelola tugas dan tenggat waktu.

Beberapa kebutuhan aplikasi yang dijelaskan dalam contoh prompt tersebut adalah:

- Menampilkan daftar tugas atau assignment.
- Menampilkan judul tugas, tanggal tenggat, dan status penyelesaian.
- Memungkinkan pengguna menandai tugas sebagai selesai.
- Menyediakan filter All, Pending, dan Completed.
- Menggunakan tampilan yang sederhana, mudah dibaca, dan responsif.

Contoh tersebut juga menetapkan beberapa batasan teknis:

- Menggunakan HTML, CSS, dan JavaScript murni (vanilla JavaScript).
- Kode harus mudah dipahami oleh pemula.
- Menghindari library dan dependensi eksternal yang tidak diperlukan.
- Struktur kode harus terorganisasi.
- AI diminta memberikan kode lengkap, cara menjalankan aplikasi, serta cara menguji fitur utamanya.

### 1.5 Keuntungan Prompt Engineering

Berdasarkan materi workshop, beberapa keuntungan Prompt Engineering adalah:

1. Meningkatkan performa model AI.
2. Mengurangi kemungkinan munculnya bias dan respons yang bersifat ofensif.
3. Meningkatkan kontrol dan prediktabilitas hasil AI.
4. Memberikan pengalaman penggunaan AI yang lebih baik.

---

## 2. Pengenalan Git dan GitHub

### 2.1 Pengertian Git

Git adalah sistem version control terdistribusi (Distributed Version Control System/DVCS) yang digunakan untuk melacak dan mengelola perubahan pada file dalam suatu proyek.

Git memungkinkan pengguna mengetahui perubahan yang terjadi pada file, termasuk siapa yang melakukan perubahan dan kapan perubahan tersebut dilakukan.

Git dikembangkan oleh Linus Torvalds pada tahun 2005.

### 2.2 Pengertian GitHub

GitHub merupakan platform berbasis web yang digunakan untuk menyimpan repository Git secara online serta mendukung kolaborasi dalam pengembangan perangkat lunak.

GitHub membantu pengembang menyimpan proyek, mengelola perubahan, dan bekerja sama dengan pengguna lain.

### 2.3 Perbedaan Git dan GitHub

| Git | GitHub |
|---|---|
| Sistem version control. | Platform berbasis web. |
| Digunakan untuk melacak perubahan proyek. | Digunakan untuk menyimpan repository Git secara online. |
| Dapat digunakan secara lokal. | Mendukung penyimpanan dan kolaborasi secara online. |
| Dijalankan melalui terminal atau aplikasi yang mendukung Git. | Diakses melalui website maupun integrasi aplikasi. |

**Kesimpulan:** Git merupakan alat untuk mengelola versi proyek, sedangkan GitHub merupakan platform yang menyediakan tempat penyimpanan repository Git dan fasilitas kolaborasi.

---

## 3. Git Workflow

Git memiliki tiga bagian utama dalam alur pengelolaan perubahan proyek.

### 3.1 Working Directory

Working Directory merupakan direktori kerja tempat pengguna melihat, membuat, dan mengubah file proyek.

Perubahan yang dilakukan pada file proyek akan terlihat di bagian ini sebelum dipilih untuk dimasukkan ke dalam commit.

### 3.2 Staging Area

Staging Area merupakan tempat untuk menyiapkan perubahan yang akan dimasukkan ke dalam commit berikutnya.

Pengguna dapat memilih perubahan tertentu sehingga tidak semua perubahan harus dimasukkan sekaligus ke dalam satu commit.

Dalam istilah teknis Git, Staging Area disebut juga sebagai Index.

### 3.3 Git Directory

Git Directory merupakan tempat Git menyimpan metadata dan object database yang diperlukan untuk mengelola repository.

Bagian ini menyimpan informasi penting mengenai riwayat dan pengelolaan perubahan proyek.

### 3.4 Alur Kerja Git

Secara sederhana, alur kerja Git dapat digambarkan sebagai berikut:

```text
Working Directory
       |
       | git add
       v
 Staging Area
       |
       | git commit
       v
 Git Repository
       |
       | git push
       v
Remote Repository (GitHub)
```

Alur tersebut menunjukkan bagaimana perubahan file dipersiapkan, disimpan dalam riwayat repository lokal, kemudian dikirim ke repository remote.

---

## 4. Perintah Dasar Git

Berikut beberapa perintah Git yang diperkenalkan dalam workshop.

### 4.1 Inisialisasi Repository

```bash
git init
```

Digunakan untuk membuat repository Git baru pada direktori proyek yang sedang digunakan.

### 4.2 Menambahkan Perubahan ke Staging Area

```bash
git add .
```

Digunakan untuk menambahkan perubahan file di direktori saat ini beserta subdirektorinya ke Staging Area.

Perintah lainnya:

```bash
git add -A
```

Menambahkan seluruh perubahan dalam repository, termasuk file baru, perubahan file, dan penghapusan file.

```bash
git add --all
```

Memiliki fungsi yang sama dengan `git add -A`.

```bash
git add *
```

Menggunakan wildcard yang diperluas oleh shell untuk memilih file. Perilakunya dapat berbeda dari `git add -A`, khususnya untuk file tersembunyi dan file yang dihapus.

### 4.3 Menyimpan Perubahan dengan Commit

```bash
git commit -m "Initial commit"
```

Digunakan untuk menyimpan perubahan yang telah berada di Staging Area ke dalam riwayat repository lokal.

Pesan commit digunakan untuk menjelaskan perubahan yang disimpan.

### 4.4 Menghubungkan Repository Remote

```bash
git remote add origin <URL-REPOSITORY>
```

Digunakan untuk menambahkan alamat repository remote dengan nama `origin`.

Perintah ini menghubungkan repository lokal dengan repository remote, misalnya repository yang berada di GitHub.

### 4.5 Mengirim Perubahan ke GitHub

```bash
git push origin main
```

Digunakan untuk mengirim commit dari branch lokal `main` ke branch `main` pada remote bernama `origin`.

### 4.6 Mengambil Perubahan dari GitHub

```bash
git pull origin main
```

Digunakan untuk mengambil perubahan dari branch `main` pada remote `origin` dan mengintegrasikannya ke branch lokal yang sedang digunakan.

Git pull pada dasarnya menjalankan proses fetch kemudian merge.

---

## 5. Persiapan Lingkungan Pengembangan

### 5.1 Instalasi Git

Git perlu diinstal terlebih dahulu agar dapat digunakan melalui terminal atau command prompt.

Untuk memeriksa apakah Git sudah terinstal, gunakan perintah:

```bash
git --version
```

Jika berhasil, terminal akan menampilkan versi Git yang terpasang.

### 5.2 Konfigurasi Identitas Git

Sebelum melakukan commit, pengguna perlu mengatur identitas yang akan digunakan Git.

Mengatur nama:

```bash
git config --global user.name "Your Name"
```

Mengatur email:

```bash
git config --global user.email "your-email@example.com"
```

Memeriksa konfigurasi:

```bash
git config --global --list
```

Konfigurasi tersebut digunakan sebagai identitas penulis pada commit yang dibuat.

### 5.3 Visual Studio Code

Visual Studio Code merupakan code editor yang dapat digunakan untuk mengembangkan dan mengelola file proyek.

Dalam materi workshop, peserta diperkenalkan pada instalasi VS Code dan penggunaan terminal untuk memeriksa versi aplikasi.

```bash
code --version
```

Perintah tersebut digunakan untuk memeriksa versi VS Code melalui terminal apabila perintah `code` sudah tersedia pada PATH sistem.

---

## 6. Menghubungkan Repository dengan GitHub

### 6.1 Membuat Repository Baru

Repository dapat dibuat melalui GitHub dengan langkah umum berikut:

1. Membuka website GitHub.
2. Membuat repository baru.
3. Menentukan nama repository.
4. Mengatur visibilitas repository.
5. Membuat repository dan memperoleh URL untuk dihubungkan dengan Git lokal.

### 6.2 Clone Repository

Selain membuat repository dari direktori lokal menggunakan `git init`, pengguna juga dapat mengambil repository yang sudah tersedia di GitHub menggunakan:

```bash
git clone <URL-REPOSITORY>
```

Perintah ini digunakan untuk menyalin repository remote ke komputer lokal, termasuk riwayat Git yang tersedia.

---

## 7. SSH Key dan Koneksi GitHub

### 7.1 Pengertian SSH Key

SSH (Secure Shell) merupakan metode komunikasi aman yang dapat digunakan untuk mengautentikasi koneksi antara komputer lokal dan GitHub.

SSH Key menggunakan pasangan kunci, yaitu:

- **Public Key:** Kunci publik yang dapat ditambahkan ke akun GitHub.
- **Private Key:** Kunci privat yang disimpan secara aman pada komputer pengguna dan tidak boleh dibagikan.

### 7.2 Membuat SSH Key

Dalam materi workshop, digunakan algoritma Ed25519 untuk membuat SSH Key.

Perintah yang digunakan:

```bash
ssh-keygen -t ed25519 -C "email@domain.com"
```

Ketika diminta menentukan lokasi penyimpanan, pengguna dapat menggunakan lokasi default. Pengguna juga dapat memberikan passphrase untuk menambah perlindungan terhadap private key.

### 7.3 Menghubungkan SSH Key dengan GitHub

Secara umum, proses menghubungkan SSH Key dengan GitHub meliputi:

1. Membuat pasangan SSH Key.
2. Menyimpan private key pada komputer lokal.
3. Mengambil isi public key.
4. Membuka pengaturan SSH and GPG Keys pada GitHub.
5. Memilih New SSH Key.
6. Menambahkan public key ke akun GitHub.
7. Menguji koneksi SSH.

Salah satu perintah untuk menguji koneksi adalah:

```bash
ssh -T git@github.com
```

Jika autentikasi berhasil, GitHub akan memberikan pesan bahwa pengguna telah berhasil melakukan autentikasi.

**Catatan:** Beberapa perintah pengelolaan SSH agent dan Keychain pada slide workshop secara khusus menggunakan macOS. Langkah konfigurasi pada Windows atau Linux dapat berbeda.

---

## 8. Penerapan AI dalam Pengembangan Aplikasi

Pada bagian akhir workshop, peserta diperkenalkan pada penggunaan AI-assisted platform untuk membantu proses pengembangan aplikasi.

Contoh platform yang disebutkan dalam materi adalah:

- Claude
- Antigravity
- ChatGPT

### 8.1 Student Task Planner

Student Task Planner merupakan contoh proyek aplikasi web sederhana yang menjadi tujuan praktik dalam materi workshop.

Aplikasi ini dirancang untuk membantu mahasiswa tahun pertama mengelola tugas kuliah dan tenggat waktu.

Fitur yang direncanakan meliputi:

- Daftar tugas atau assignment.
- Informasi judul tugas.
- Tanggal tenggat.
- Status penyelesaian tugas.
- Fitur menandai tugas sebagai selesai.
- Filter tugas berdasarkan status All, Pending, dan Completed.

### 8.2 Alur Pengembangan Menggunakan AI dan GitHub

Berdasarkan panduan pada slide workshop, alur pengembangan proyek adalah:

1. Menginstal platform AI-assisted.
2. Menyusun prompt untuk membuat aplikasi atau website.
3. Membuat repository Git lokal menggunakan `git init`.
4. Menyimpan perubahan menggunakan `git commit`.
5. Mengirim perubahan ke GitHub menggunakan `git push`.
6. Melakukan perubahan atau pengembangan aplikasi.
7. Melakukan commit dan push kembali untuk menyimpan pembaruan.

Alur ini menunjukkan bagaimana AI dapat membantu proses pembuatan aplikasi, sementara Git dan GitHub digunakan untuk mengelola serta mendokumentasikan perubahan proyek.

**Status pengerjaan:** Student Task Planner belum dibuat dalam kegiatan yang saya ikuti. Bagian ini merupakan dokumentasi konsep dan alur praktik yang dijelaskan dalam materi workshop.

---

# 💡 POIN PENTING DAN PENGETAHUAN BARU

Berdasarkan materi yang dipelajari, terdapat beberapa hal penting yang dapat dirangkum:

1. **AI membutuhkan instruksi yang jelas.** Kualitas dan relevansi hasil AI dapat ditingkatkan dengan memberikan role, task, context, dan format yang sesuai.

2. **Konteks sangat berpengaruh terhadap hasil AI.** Instruksi yang dilengkapi informasi dan kebutuhan yang jelas akan membantu AI memahami tujuan pekerjaan.

3. **Git dan GitHub memiliki fungsi yang berbeda.** Git digunakan untuk mengelola versi dan perubahan proyek, sedangkan GitHub menyediakan platform untuk menyimpan repository secara online dan mendukung kolaborasi.

4. **Version control membantu mengelola perubahan.** Setiap commit menjadi bagian dari riwayat perubahan proyek sehingga perkembangan pekerjaan dapat terdokumentasi.

5. **Staging Area memiliki peran penting.** Pengguna dapat memilih perubahan yang ingin dimasukkan ke dalam commit berikutnya.

6. **AI dapat mendukung proses pengembangan aplikasi.** Dengan prompt yang terstruktur, AI dapat membantu menghasilkan kode berdasarkan kebutuhan yang diberikan.

7. **AI dan GitHub dapat digunakan secara saling melengkapi.** AI membantu proses pembuatan dan pengembangan aplikasi, sedangkan Git dan GitHub membantu mengelola serta menyimpan perubahan.

---

# 📝 REFLEKSI DAN PENDAPAT PRIBADI

Materi Day 1 Proyek Workshop memberikan pemahaman mengenai bagaimana teknologi Artificial Intelligence dapat dimanfaatkan dalam proses pengembangan aplikasi serta bagaimana perubahan pada proyek dapat dikelola menggunakan Git dan GitHub.

Salah satu hal penting yang dapat dipahami adalah bahwa penggunaan AI tidak hanya bergantung pada teknologi yang digunakan, tetapi juga pada bagaimana instruksi diberikan. Melalui Prompt Engineering, sebuah kebutuhan dapat dijelaskan secara lebih terstruktur dengan menentukan role, task, context, dan format. Hal tersebut membantu AI memahami tujuan yang ingin dicapai sehingga hasil yang diberikan menjadi lebih relevan.

Selain itu, pengenalan Git dan GitHub memberikan gambaran mengenai pentingnya version control dalam pengembangan perangkat lunak. Dengan memahami Working Directory, Staging Area, dan Git Directory, proses pengelolaan perubahan file menjadi lebih terstruktur. Penggunaan commit, push, dan pull juga membantu menjelaskan bagaimana perubahan dapat disimpan dan disinkronkan dengan repository online.

Menurut saya, kedua materi tersebut memiliki hubungan yang menarik. AI dapat membantu mempercepat proses pembuatan aplikasi, sedangkan Git dan GitHub membantu menjaga pengelolaan proyek agar tetap terorganisasi. Keduanya merupakan pengetahuan dasar yang bermanfaat untuk dipelajari dalam dunia teknologi informasi.

Melalui materi ini, saya memperoleh gambaran awal mengenai penggunaan AI dalam pengembangan aplikasi dan pentingnya pengelolaan versi proyek. Pengetahuan tersebut dapat menjadi bekal untuk mempelajari lebih lanjut proses pengembangan perangkat lunak serta menerapkannya pada tugas dan proyek berikutnya.

---

# 📌 STATUS PEMBELAJARAN

| Materi / Kegiatan | Status |
|---|---|
| Pengenalan Prompt Engineering | Dipelajari |
| Pengenalan Git dan GitHub | Dipelajari |
| Git Workflow | Dipelajari |
| Perintah Dasar Git | Dipelajari |
| Persiapan Git dan VS Code | Dipelajari |
| Pengenalan SSH Key | Dipelajari |
| Konsep Student Task Planner | Dipelajari |
| Praktik Pembuatan Student Task Planner | Belum dilakukan |

---

# 📚 REFERENSI

1. Materi presentasi workshop **Building with AI, Managing Change with GitHub** – Nugi Farhan.
2. Dokumentasi resmi Git: https://git-scm.com/doc
3. Dokumentasi resmi GitHub: https://docs.github.com/
4. Dokumentasi resmi Visual Studio Code: https://code.visualstudio.com/docs

---

**Repository Maintainer:** Muhammad Raka Asri

**GitHub:** [@rakaasri2-dev](https://github.com/rakaasri2-dev)

*Learn, understand, and build something meaningful.* 🚀
