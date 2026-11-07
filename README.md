# 🍄 Day 1 – Proyek Workshop 2026
### Building with AI, Managing Change with GitHub

**Kelompok 6 – Super Mario**

---

## 👤 Identitas Peserta

| Informasi | Keterangan |
|---|---|
| Nama | Muhammad Raka Asri |
| Kelompok | 6 – Super Mario |
| Program Studi | D4 Teknik Informatika |
| Institusi | Politeknik Negeri Jakarta |
| Kegiatan | Day 1 Proyek Workshop 2026 |

## 📌 Tentang Repository

Repository ini merupakan dokumentasi kegiatan Day 1 Proyek Workshop 2026 HIMATIK. Isinya mencakup rangkuman materi, catatan pembelajaran, dan refleksi dari tiga sesi workshop.

Selain sebagai dokumentasi kegiatan, repository ini juga menjadi arsip pembelajaran yang dapat digunakan sebagai referensi selama perkuliahan.

## 🎯 Tujuan

- Mendokumentasikan materi workshop.
- Memahami penggunaan AI, Git, dan GitHub.
- Mengenal program MBKM dan MSIB.
- Memahami Kurikulum OBE 2026 D4 Teknik Informatika.

---

## 📑 Daftar Isi

1. [Informasi Workshop](#informasi-workshop)
2. [Sesi 1 – Building with AI, Managing Change with GitHub](#1-sesi-1--building-with-ai-managing-change-with-github)
3. [Sesi 2 – Kurikulum Merdeka di Perguruan Tinggi](#2-sesi-2--kurikulum-merdeka-di-perguruan-tinggi)
4. [Sesi 3 – Kurikulum OBE 2026](#3-sesi-3--kurikulum-obe-2026-d4-teknik-informatika)
5. [Poin Pembelajaran](#-poin-pembelajaran)
6. [Refleksi Pribadi](#-refleksi-pribadi)
7. [Referensi](#-referensi)

---

## Informasi Workshop

Day 1 Proyek Workshop 2026 membahas tiga topik utama yang berkaitan dengan teknologi, pendidikan, dan persiapan mahasiswa menghadapi dunia kerja.

| Sesi | Materi | Pembahasan |
|---|---|---|
| 1 | Building with AI, Managing Change with GitHub | Prompt Engineering, Git, GitHub |
| 2 | Kurikulum Merdeka | MBKM, MSIB, metode pembelajaran |
| 3 | Kurikulum OBE 2026 | Profil lulusan, CPL, struktur mata kuliah |

---

# 1. Sesi 1 – Building with AI, Managing Change with GitHub

**Pemateri: Nugi Farhan**

Sesi pertama membahas penggunaan AI dalam pengembangan aplikasi serta pengelolaan proyek menggunakan Git dan GitHub.

### A. Prompt Engineering

Prompt adalah instruksi atau masukan yang diberikan kepada AI untuk memperoleh hasil tertentu. Prompt Engineering merupakan proses menyusun instruksi agar respons AI lebih sesuai dengan kebutuhan.

**Struktur prompt yang baik:**

| Komponen | Fungsi |
|---|---|
| Role | Menentukan peran AI |
| Task | Menjelaskan tugas yang harus dilakukan |
| Context | Memberikan informasi pendukung |
| Format | Menentukan bentuk hasil yang diinginkan |

Pemberian konteks yang jelas membantu AI memahami tujuan dan menghasilkan jawaban yang lebih relevan.

**Contoh penerapan: Student Task Planner**

Materi workshop menggunakan contoh pembuatan aplikasi web sederhana untuk membantu mahasiswa mengelola tugas kuliah.

Fitur yang direncanakan:
- Menampilkan daftar tugas.
- Menampilkan judul dan tanggal tenggat.
- Menampilkan status penyelesaian.
- Menandai tugas sebagai selesai.
- Filter All, Pending, dan Completed.

Teknologi yang digunakan dalam contoh:
- HTML
- CSS
- Vanilla JavaScript

### B. Git dan GitHub

**Git** adalah sistem version control terdistribusi yang digunakan untuk mencatat dan mengelola perubahan file dalam proyek.

**GitHub** adalah platform berbasis web untuk menyimpan repository Git secara online dan mendukung kolaborasi.

| Git | GitHub |
|---|---|
| Sistem version control | Platform berbasis web |
| Mengelola riwayat perubahan | Menyimpan repository secara online |
| Dapat digunakan secara lokal | Mendukung kolaborasi |
| Mengelola versi proyek | Menyediakan fitur Issues dan Pull Requests |

Git dikembangkan oleh Linus Torvalds pada tahun 2005.

### C. Git Workflow

Git memiliki tiga area utama dalam proses pengelolaan perubahan:

1. **Working Directory:** Tempat pengguna membuat dan mengubah file.
2. **Staging Area:** Tempat menyiapkan perubahan sebelum commit.
3. **Git Directory:** Tempat Git menyimpan database dan informasi riwayat proyek.

**Alur kerja Git:**

```text
Working Directory
       |
    git add
       |
       v
  Staging Area
       |
   git commit
       |
       v
 Local Repository
       |
    git push
       |
       v
Remote Repository
    (GitHub)
```

### D. Perintah Dasar Git

| Perintah | Fungsi |
|---|---|
| `git init` | Membuat repository Git baru |
| `git add .` | Menambahkan perubahan ke staging |
| `git add -A` | Menambahkan seluruh perubahan repository |
| `git commit -m "pesan"` | Menyimpan perubahan ke riwayat Git |
| `git status` | Memeriksa status perubahan |
| `git log` | Melihat riwayat commit |
| `git clone URL` | Menyalin repository remote |
| `git push origin main` | Mengirim commit ke GitHub |
| `git pull origin main` | Mengambil dan menggabungkan perubahan dari remote |

**Contoh alur penggunaan:**

```bash
git init
git add .
git commit -m "Initial commit"
git remote add origin <URL-REPOSITORY>
git push -u origin main
```

### E. Git Setup

Sebelum menggunakan Git, pengguna perlu menginstal Git dan mengatur identitas.

Memeriksa instalasi:

```bash
git --version
```

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

### F. SSH Key dan GitHub

SSH (Secure Shell) digunakan untuk menghubungkan komputer dengan GitHub melalui autentikasi yang aman.

SSH menggunakan dua jenis kunci:

- **Public Key:** Ditambahkan ke akun GitHub.
- **Private Key:** Disimpan secara pribadi di komputer dan tidak boleh dibagikan.

Membuat SSH Key:

```bash
ssh-keygen -t ed25519 -C "email@domain.com"
```

Setelah dibuat, public key ditambahkan melalui menu GitHub **Settings → SSH and GPG Keys → New SSH Key**.

Menguji koneksi:

```bash
ssh -T git@github.com
```

### G. Alur Pengembangan dengan AI dan GitHub

Materi workshop memperkenalkan alur pengembangan aplikasi menggunakan platform AI-assisted seperti Claude, Antigravity, dan ChatGPT.

Tahapannya:

1. Menginstal platform AI-assisted.
2. Menyusun prompt untuk membuat aplikasi.
3. Membuat repository menggunakan `git init`.
4. Menyimpan perubahan dengan commit.
5. Mengirim proyek ke GitHub menggunakan push.
6. Melakukan perubahan dan memperbarui repository.

**Catatan:** Sesi ini diikuti secara teori. Student Task Planner belum dibuat sebagai aplikasi dalam kegiatan yang saya ikuti.

---

# 2. Sesi 2 – Kurikulum Merdeka di Perguruan Tinggi

**Materi: Merdeka Belajar – Kampus Merdeka (MBKM & MSIB)**

Sesi kedua membahas kesempatan belajar di luar program studi, pengalaman industri, serta metode pembelajaran yang dapat mengembangkan kompetensi mahasiswa.

### A. Mengenal MBKM

Merdeka Belajar – Kampus Merdeka (MBKM) merupakan kebijakan pendidikan tinggi yang diperkenalkan sejak tahun 2020.

Tujuannya memberikan kesempatan kepada mahasiswa untuk mengembangkan kemampuan sesuai minat dan kebutuhan dunia kerja.

Beberapa tujuan MBKM:
- Memberikan pengalaman belajar di luar kelas.
- Menghubungkan pembelajaran kampus dengan industri.
- Mengembangkan kompetensi mahasiswa.
- Memberikan pengakuan akademik melalui konversi SKS sesuai ketentuan.

### B. MBKM dan MSIB

MBKM merupakan payung kebijakan pembelajaran, sedangkan MSIB adalah salah satu program pelaksanaannya.

| MBKM | MSIB |
|---|---|
| Kebijakan pembelajaran | Program Magang dan Studi Independen Bersertifikat |
| Memiliki delapan bentuk kegiatan | Berfokus pada magang dan studi independen |
| Memberikan kesempatan belajar di luar prodi | Melibatkan mitra industri dan organisasi |
| Konversi SKS mengikuti ketentuan prodi | Skema program dalam materi mencakup 20 SKS |

### C. Delapan Bentuk Kegiatan MBKM

| No. | Kegiatan | Penjelasan |
|---|---|---|
| 1 | Pertukaran Pelajar | Belajar di program studi atau kampus lain |
| 2 | Magang / Praktik Kerja | Mendapatkan pengalaman di dunia industri |
| 3 | Asistensi Mengajar | Membantu kegiatan pembelajaran |
| 4 | Penelitian / Riset | Melakukan penelitian bersama dosen atau lembaga |
| 5 | Proyek Kemanusiaan | Terlibat dalam kegiatan kemanusiaan |
| 6 | Kegiatan Wirausaha | Mengembangkan usaha |
| 7 | Proyek Independen | Membuat proyek atau inovasi secara mandiri |
| 8 | Membangun Desa / KKN | Melakukan pengabdian kepada masyarakat |

### D. MSIB: Magang dan Studi Independen Bersertifikat

MSIB memiliki dua bentuk kegiatan utama.

**1. Magang Bersertifikat**

Mahasiswa memperoleh pengalaman bekerja langsung di perusahaan atau organisasi mitra, mengerjakan proyek nyata, dan mendapatkan bimbingan mentor industri.

**2. Studi Independen Bersertifikat**

Mahasiswa mempelajari kompetensi tertentu melalui kegiatan terstruktur seperti:
- Short course.
- Bootcamp.
- Massive Open Online Course (MOOC).
- Proyek dan studi kasus bersama mitra.

Dalam skema yang dijelaskan pada materi, kedua program berlangsung selama satu semester dan dapat dikonversi menjadi 20 SKS.

### E. Metode Pembelajaran

Materi workshop menjelaskan tiga metode pembelajaran yang mendorong mahasiswa lebih aktif.

| Metode | Fokus | Hasil |
|---|---|---|
| Project-Based Learning (PjBL) | Mengerjakan proyek nyata | Produk, prototipe, aplikasi, atau laporan |
| Problem-Based Learning (PBL) | Menyelesaikan permasalahan | Solusi berdasarkan analisis |
| Case-Based Learning (CBL) | Menganalisis kasus | Rekomendasi dan kesimpulan |

**Tahapan Case-Based Learning:**

1. Mempelajari kasus.
2. Mengidentifikasi masalah.
3. Melakukan analisis dan diskusi.
4. Merumuskan solusi.
5. Presentasi dan refleksi.

### F. Manfaat MBKM bagi Mahasiswa

- Memperoleh pengalaman kerja sebelum lulus.
- Mengembangkan keterampilan sesuai kebutuhan industri.
- Memperluas relasi dengan mentor dan praktisi.
- Mendapatkan pengakuan akademik sesuai ketentuan program.

### G. Persiapan Mengikuti MBKM

1. Memastikan data akademik di PDDikti sesuai.
2. Membuat akun pada portal program yang tersedia.
3. Memilih program sesuai minat.
4. Menyiapkan dokumen pendaftaran dan mengikuti seleksi.
5. Berkonsultasi dengan dosen mengenai konversi SKS.

**Catatan:** Materi presentasi mencantumkan angka dua semester pada bagian utama dan tiga semester pada slide penutup terkait hak belajar di luar prodi. Karena terdapat perbedaan dalam presentasi, ketentuan yang berlaku perlu dikonfirmasi melalui pedoman akademik dan program studi.

---

# 3. Sesi 3 – Kurikulum OBE 2026 D4 Teknik Informatika

**Pemateri: Bambang Warsuta, S.Kom., M.T.I.**  
**Kepala Program Studi D4 Teknik Informatika, Politeknik Negeri Jakarta**

Sesi ketiga membahas kurikulum berbasis Outcome-Based Education (OBE), mulai dari profil lulusan hingga struktur mata kuliah.

### A. Mengenal Outcome-Based Education (OBE)

Outcome-Based Education merupakan pendekatan pendidikan yang berfokus pada capaian pembelajaran atau kompetensi yang harus dimiliki lulusan.

Kurikulum OBE 2026 D4 Teknik Informatika memiliki gambaran berikut:

| Komponen | Jumlah |
|---|---:|
| Semester | 8 |
| Mata Kuliah | 49 |
| Total SKS | 145 |
| Profil Lulusan | 4 |
| CPL | 11 |

Lulusan memperoleh gelar Sarjana Terapan Komputer (S.Tr.Kom.) dengan kualifikasi KKNI Level 6.

Penyusunan kurikulum dilakukan dengan alur:

**Profil Lulusan → Profesi → CPL → Mata Kuliah**

### B. Empat Profil Lulusan

| Kode | Profil | Gambaran Kompetensi |
|---|---|---|
| PL01 | Analis Solusi | Menganalisis masalah dan merumuskan solusi komputasi |
| PL02 | Pengembang Aplikasi | Merancang, membangun, menguji, dan mengevaluasi aplikasi |
| PL03 | Penerap Teknologi | Menerapkan data, AI, jaringan, cloud, dan keamanan siber |
| PL04 | Profesional Kolaboratif | Bekerja secara etis, komunikatif, kolaboratif, dan adaptif |

**Contoh profesi berdasarkan profil:**

- PL01: System Analyst, Business Analyst IT, IT Consultant Junior.
- PL02: Software Developer, Web Developer, Mobile Developer, UI/UX Developer.
- PL03: Data Analyst, AI/ML Engineer, Cloud Engineer, Network Administrator.
- PL04: IT Project Officer, IT Support Specialist, Technical Writer, Technopreneur.

Mitra industri juga menilai empat profesi fundamental, yaitu Data Engineer, AI Engineer, Sales Engineer, dan Consultant.

### C. Capaian Pembelajaran Lulusan (CPL)

CPL merupakan kompetensi yang harus dicapai mahasiswa setelah menyelesaikan pendidikan.

Kurikulum OBE 2026 memiliki sebelas CPL:

| Kode | Capaian Pembelajaran |
|---|---|
| CPL 01 | Ketakwaan, ketaatan hukum, disiplin, dan tanggung jawab |
| CPL 02 | Sikap profesional dan etis, termasuk keamanan informasi |
| CPL 03 | Pemahaman sistem komputer, algoritma, dan metode komputasi |
| CPL 04 | Analisis persoalan komputasi dan perancangan solusi TI |
| CPL 05 | Perancangan dan simulasi aplikasi multi-platform |
| CPL 06 | Komunikasi, presentasi, kerja sama, dan kepemimpinan tim |
| CPL 07 | Penyusunan laporan dan artikel ilmiah |
| CPL 08 | Implementasi kebutuhan komputasi dengan metode yang sesuai |
| CPL 09 | Perancangan dan evaluasi antarmuka serta UX |
| CPL 10 | Penerapan metode analitis secara sistematis dan terukur |
| CPL 11 | Pengembangan dan evaluasi solusi komputasi multi-platform |

**CPL prioritas menurut advisory board:**

- CPL 02 – Etika dan keamanan informasi.
- CPL 04 – Analisis dan rancangan solusi.
- CPL 06 – Komunikasi dan kerja tim.
- CPL 08 – Implementasi komputasi.
- CPL 11 – Solusi multi-platform.

CPL 06 menjadi kompetensi yang paling ditekankan dalam kebutuhan dunia kerja. Artinya, kemampuan komunikasi dan kerja sama sama pentingnya dengan keterampilan teknis.

### D. Struktur Kurikulum dan Beban SKS

Kurikulum terdiri dari 49 mata kuliah dengan total 145 SKS selama delapan semester.

| Semester | SKS | Fokus Pembelajaran |
|---|---:|---|
| 1 | 17 | Dasar komputer, matematika, dan pemrograman |
| 2 | 18 | Struktur data, basis data, dan front-end |
| 3 | 23 | PBO, AI, rekayasa perangkat lunak |
| 4 | 23 | Jaringan, sistem informasi, dan keamanan |
| 5 | 13 | Big Data, Machine Learning, dan penelitian |
| 6 | 19 | Pemrograman mobile, proyek, dan stream pilihan |
| 7 | 20 | Magang dan penelitian |
| 8 | 12 | Tugas akhir |

**Pendalaman pada semester 6:**

Mahasiswa memilih salah satu dari dua stream dengan total 9 SKS.

- **Stream KA (Kecerdasan Artifisial):** Data Mining, Natural Language Processing, dan Computer Vision.
- **Stream RPL (Rekayasa Perangkat Lunak):** Sistem Informasi Geografis, Sistem Informasi Kesehatan (e-health), dan Emerging Technology.

Semester 7 memiliki kegiatan magang sebesar 12 SKS, sedangkan semester 8 berfokus pada tugas akhir sebesar 8 SKS.

### E. Strategi Belajar Efektif

Materi OBE juga membahas strategi belajar berdasarkan buku *Make It Stick: The Science of Successful Learning* karya Brown, Roediger, dan McDaniel (2014).

**Empat mitos belajar:**

| Mitos | Fakta |
|---|---|
| Membaca ulang adalah cara terbaik | Menguji diri membantu mengetahui pemahaman |
| Belajar kebut semalam cukup | Belajar berjarak membantu ingatan bertahan |
| Belajar harus selalu mudah | Kesulitan yang wajar dapat memperkuat pemahaman |
| Setiap orang punya gaya belajar tetap | Tidak ada keharusan mencocokkan metode dengan label gaya belajar |

**Enam kebiasaan belajar efektif:**

1. **Retrieval Practice:** Menguji ingatan tanpa melihat catatan.
2. **Spaced Practice:** Mengulang materi dengan jeda waktu.
3. **Interleaving:** Mempelajari beberapa topik secara bergantian.
4. **Elaboration:** Menjelaskan materi menggunakan kata sendiri.
5. **Generation:** Mencoba menyelesaikan soal sebelum melihat pembahasan.
6. **Calibration:** Mengukur pemahaman melalui evaluasi secara jujur.

---

## 💡 Poin Pembelajaran

Dari ketiga sesi workshop, beberapa hal penting yang saya peroleh adalah:

1. AI dapat membantu pengembangan aplikasi, tetapi hasilnya sangat dipengaruhi oleh kualitas prompt dan konteks yang diberikan.
2. Git dan GitHub penting untuk mengelola versi proyek serta menyimpan riwayat perubahan.
3. MBKM dan MSIB memberikan kesempatan bagi mahasiswa untuk memperoleh pengalaman di luar kegiatan perkuliahan reguler.
4. PjBL, PBL, dan CBL melatih mahasiswa menerapkan pengetahuan melalui proyek, masalah, dan studi kasus.
5. Kurikulum OBE mengarahkan pembelajaran berdasarkan kompetensi yang harus dicapai lulusan.
6. Kemampuan komunikasi dan kerja sama perlu dikembangkan bersama kemampuan teknis.

---

## 📝 Refleksi Pribadi

Dari workshop ini, saya mendapatkan gambaran yang lebih luas mengenai hal-hal yang perlu dipersiapkan selama menjadi mahasiswa Teknik Informatika.

Materi pertama memberikan pemahaman tentang penggunaan AI sebagai alat bantu pengembangan aplikasi serta pentingnya Git dan GitHub dalam mengelola proyek. Saya juga memahami bahwa penggunaan AI perlu disertai instruksi yang jelas agar hasilnya sesuai kebutuhan.

Pada materi MBKM, saya mengetahui adanya kesempatan untuk memperoleh pengalaman belajar di luar kampus, khususnya melalui magang dan studi independen. Hal ini menarik karena mahasiswa dapat mengenal lingkungan industri sebelum menyelesaikan perkuliahan.

Sementara itu, materi Kurikulum OBE memberikan gambaran mengenai kompetensi yang perlu dicapai selama kuliah. Saya menyadari bahwa kemampuan teknis bukan satu-satunya hal yang penting. Komunikasi, kerja sama, dan kemampuan menyelesaikan masalah juga dibutuhkan dalam dunia kerja.

Ke depannya, saya ingin lebih aktif mengembangkan keterampilan melalui proyek, memanfaatkan teknologi dengan baik, dan menerapkan kebiasaan belajar yang lebih efektif.

---

## 📚 Referensi

**Materi Workshop**

1. Nugi Farhan. *Building with AI, Managing Change with GitHub*. Materi Day 1 Proyek Workshop 2026.
2. *Kurikulum Merdeka di Perguruan Tinggi – MBKM & MSIB*. Materi presentasi workshop.
3. Bambang Warsuta, S.Kom., M.T.I. *Kurikulum OBE 2026 – Program Studi D4 Teknik Informatika*. Politeknik Negeri Jakarta.

**Referensi Pendukung**

4. Brown, P. C., Roediger, H. L. III, & McDaniel, M. A. (2014). *Make It Stick: The Science of Successful Learning*. Harvard University Press.
5. Git Documentation: https://git-scm.com/doc
6. GitHub Documentation: https://docs.github.com/
7. Google Cloud – Prompt Engineering: https://cloud.google.com/discover/what-is-prompt-engineering

---

<p align="center">
  <b>Muhammad Raka Asri</b>
  <br>
  D4 Teknik Informatika – Politeknik Negeri Jakarta
  <br><br>
  <i>"Keep learning, keep building, and keep improving."</i> 🚀
</p>
