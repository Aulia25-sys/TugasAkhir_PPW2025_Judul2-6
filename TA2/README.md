# Website Portofolio – Aulia Rahmi Shakira

Proyek ini merupakan **website portofolio pribadi** yang dirancang untuk menampilkan profil, keahlian, proyek, dan informasi kontak saya secara interaktif dan modern.  
Website ini menampilkan beberapa bagian seperti **Beranda**, **Tentang Saya**, **Keahlian**, **Proyek**, dan **Kontak**, dengan desain elegan berwarna gelap (dark mode) dan efek neon biru.  
Tujuan utama proyek ini adalah untuk **mendokumentasikan perjalanan belajar dan penerapan Git & GitHub** dalam mengelola versi proyek web.

---

## Deskripsi Website
Website ini terdiri dari dua file utama:
- **index.html** → berisi struktur utama tampilan portofolio seperti profil, keahlian, proyek, dan kontak.
- **style.css** → mengatur tampilan visual website dengan tema futuristik bernuansa cyan, lengkap dengan efek hover, animasi, dan layout responsif.

Secara garis besar, portofolio ini memuat:
- Informasi pribadi dan tujuan karier di bidang **AI & Machine Learning**
- Daftar **keahlian teknis** (Python, TensorFlow, OpenCV, dan lain-lain)
- Beberapa **proyek unggulan**, seperti *I-Beauty*, *Watchwise*, dan *Sistem Deteksi Penyakit Mata*
- Formulir kontak dan tautan ke akun sosial media profesional (LinkedIn, GitHub, Instagram)

---

## Tujuan
Proyek ini dibuat sebagai bagian dari **Tugas Akhir Percobaan Git & Version Control** untuk mempraktikkan penggunaan Git secara lengkap, mulai dari inisialisasi repository, commit bertahap, pembuatan branch, hingga push ke GitHub dengan dokumentasi README.

---

## Langkah-Langkah Pengerjaan

### Langkah 1 : Mengecek Konfigurasi Git
Langkah pertama adalah memastikan Git sudah dikonfigurasi dengan benar menggunakan perintah:
<img width="411" height="293" alt="image" src="https://github.com/user-attachments/assets/792f92cf-055e-4e6a-aafb-f1018d8e106b" />
Perintah ini digunakan untuk menampilkan daftar konfigurasi nama pengguna (`user.name`) dan email (`user.email`) untuk memastikan commit nantinya tercatat atas nama yang sesuai. Dan berdasarkan gambar menunjukan bahwa konfigurasi sudah aktif.

### Langkah 2 : Inisialisasi Repository Baru
Setelah konfigurasi benar, akan dilakukan inisialisasi repository lokal. Namun, sebelum itu dilakukan cd untuk ke  file tempat menyimpan file index.html dan style.css yang akan dilakukan commit nantinya.
<img width="421" height="41" alt="image" src="https://github.com/user-attachments/assets/6a3bbda1-6008-4a47-a22e-0d836eafc62c" />

<img width="410" height="40" alt="image" src="https://github.com/user-attachments/assets/d193bed5-c7fc-49b1-bfe3-63a7024bfded" />
Dapat dilihat bahwa inisialisasi  sudah berhasil dilakukan.

### Langkah 3 : Menambahkan File HTML Awal
Selanjutnya dibuat file `index.html` berisi struktur dasar halaman portofolio (header, navigasi, hero section, dan footer).  
File ini ditambahkan ke Git dan dilakukan commit pertama:
<img width="422" height="66" alt="image" src="https://github.com/user-attachments/assets/b593a430-e7d9-4c75-afde-5b496fcb1db6" />
<img width="421" height="117" alt="image" src="https://github.com/user-attachments/assets/35fc9e3b-f4fa-4fde-a051-449912d1d067" />
Disini  digunakan perintah 'git status' untuk memastikan repository sudah siap digunakan dan dapat dilihat bahwa status repository masih kosong
<img width="422" height="72" alt="image" src="https://github.com/user-attachments/assets/2c196a0d-8351-4a33-b672-6c067b1a7710" />
Commit ini menjadi titik awal versi pertama proyek. Kemudian dapat dilihat bahwa commit pertama berhasil  dibuat.

<img width="377" height="32" alt="image" src="https://github.com/user-attachments/assets/53381db0-e907-48f9-bf82-c96ff496bb3b" />
<img width="378" height="84" alt="image" src="https://github.com/user-attachments/assets/41ff672b-5208-4a55-8744-5677625d56e5" />
Disini terjadi commit kedua dan ketiga yang sudah berhasil dilakukan berdasarkan gambar.

### Langkah 4 : Menambahkan File CSS
Pada tahap ini dibuat file `style.css` yang mengatur tampilan website.  
File CSS tersebut menambahkan warna, layout, dan animasi agar website terlihat lebih menarik.  
Kemudian dilakukan commit ketiga dengan perintah:
<img width="380" height="122" alt="image" src="https://github.com/user-attachments/assets/89100cd2-1709-4d37-87cf-2699fdbb5a87" />
Dapat dilihat bahwa commit keempat untuk  style.css berhasil dilakukan.

### Langkah 5 : Membuat Branch Baru untuk Eksperimen Tampilan
Untuk mencoba desain baru tanpa mengubah branch utama, dibuat branch baru bernama `feature-styling`. Di branch ini dilakukan perubahan pada `style.css` seperti mengganti warna aksen dan menambahkan efek hover pada elemen proyek.  
Commit dilakukan dengan pesan *"update style baru dan animasi hover proyek"*.
<img width="378" height="128" alt="image" src="https://github.com/user-attachments/assets/1d0b7204-fb59-462a-9d0e-467a00d75eb4" />
<img width="415" height="49" alt="image" src="https://github.com/user-attachments/assets/8da86b17-edd3-46e1-9008-ee61d71fce78" />
Gambar menunjukkan pembuatan branch baru dan hasil commit di branch tersebut.

### Langkah 6 : Menggabungkan Branch ke Master
Setelah hasil di branch `feature-styling` dianggap sesuai, dilakukan penggabungan (merge) ke branch utama (`master`):
<img width="412" height="117" alt="image" src="https://github.com/user-attachments/assets/817e50fb-9a82-43a4-8e02-a164d31d42b4" />

Kemudian branch `feature-styling` dihapus karena sudah digabung:
<img width="414" height="43" alt="image" src="https://github.com/user-attachments/assets/ff7bb133-1c41-4e88-a9c7-e70e1579a9e3" />
Hasil merge berhasil tanpa konflik dan tampilan baru langsung diterapkan di branch utama. Gambar menunjukkan proses merge dan penghapusan branch yang sukses.

### Langkah 8 : Menambahkan Remote dan Push ke GitHub
Tahap selanjutnya yaitu menghubungkan repository lokal ke GitHub dengan perintah:
<img width="412" height="76" alt="image" src="https://github.com/user-attachments/assets/93cceeab-a8b9-4347-ae61-a965f4d4fbad" />
Perintah tersebut mengunggah seluruh commit ke repository GitHub agar proyek dapat diakses secara online.  

<img width="414" height="31" alt="image" src="https://github.com/user-attachments/assets/6d41671f-312b-40cb-914d-301b2927311c" />

<img width="415" height="49" alt="image" src="https://github.com/user-attachments/assets/661d231a-c492-4c64-b1c0-e825ad6da9f1" />

<img width="420" height="28" alt="image" src="https://github.com/user-attachments/assets/85681992-3694-4e4a-8034-94f03768f845" />

<img width="419" height="30" alt="image" src="https://github.com/user-attachments/assets/edb6d37e-1149-4622-978a-550fdaa17a83" />

<img width="420" height="50" alt="image" src="https://github.com/user-attachments/assets/13145d6e-e4f1-4805-985c-70b9cea3b7c7" />

<img width="419" height="52" alt="image" src="https://github.com/user-attachments/assets/335f7330-a3fa-4cd0-81b1-b81d3f45b2e1" />

<img width="419" height="93" alt="image" src="https://github.com/user-attachments/assets/658d4fe1-004e-4b56-ac7e-f68230a96f42" />

<img width="423" height="138" alt="image" src="https://github.com/user-attachments/assets/157cbfba-f32e-4b09-9eed-ee06d54fa835" />

<img width="419" height="45" alt="image" src="https://github.com/user-attachments/assets/a15368aa-7dcd-4eac-b289-e0a97200662b" />




<img width="440" height="43" alt="image" src="https://github.com/user-attachments/assets/540a3923-0a72-4084-a027-9d0ede216b2e" />

<img width="511" height="509" alt="image" src="https://github.com/user-attachments/assets/f1ca04ef-37b6-45df-996a-412b08975df5" />

<img width="535" height="138" alt="image" src="https://github.com/user-attachments/assets/790f144d-d153-4547-91b1-a5627ed0b217" />


