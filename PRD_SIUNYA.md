# PRODUCT REQUIREMENTS DOCUMENT SIUNYA

**Platform Digital Terpadu untuk Informasi dan Layanan Mahasiswa Universitas Negeri Yogyakarta**

| Dokumen          | Product Requirements Document (PRD)                  |
| ---------------- | ---------------------------------------------------- |
| Produk           | SIUNYA                                               |
| Lingkup          | Universitas Negeri Yogyakarta                        |
| Bidang           | Software Development                                 |
| Target Pengguna  | Mahasiswa Universitas Negeri Yogyakarta              |
| Pengelola Sistem | Admin/Pengelola layanan universitas dan unit terkait |
| Status           | Draft awal untuk pengembangan proyek                 |

---

## 1. Latar Belakang

Informasi dan layanan yang dibutuhkan mahasiswa Universitas Negeri Yogyakarta dapat berasal dari berbagai fakultas, program studi, unit, organisasi mahasiswa, kegiatan, dan fasilitas. Kondisi tersebut dapat membuat mahasiswa harus mencari informasi dari berbagai sumber dan tidak selalu mengetahui saluran yang tepat ketika membutuhkan informasi atau ingin melaporkan masalah.

SIUNYA dirancang sebagai platform digital terpadu dalam lingkup Universitas Negeri Yogyakarta. Platform ini menjadi salah satu pintu akses bagi mahasiswa untuk memperoleh informasi, menemukan fasilitas, melihat kegiatan, mengakses informasi organisasi, serta menyampaikan laporan terkait fasilitas atau lingkungan kampus.

Meskipun memiliki cakupan tingkat universitas, SIUNYA tidak dimaksudkan untuk menggantikan sistem akademik maupun sistem internal yang telah digunakan UNY. Ruang lingkup produk difokuskan pada kebutuhan informasi dan layanan mahasiswa yang dapat dihimpun dalam satu platform.

---

## 2. Project Theme

**Tema 1 — Inovasi Layanan Publik Berbasis Digital untuk Meningkatkan Akses, Efisiensi, dan Transparansi.**

**Kesesuaian tema:**
SIUNYA memusatkan akses terhadap informasi dan layanan mahasiswa dalam satu platform. Akses ditingkatkan melalui penyediaan informasi, kegiatan, fasilitas, dan layanan secara terpusat; efisiensi melalui penyampaian informasi dan pelaporan secara digital; serta transparansi melalui informasi status laporan yang dapat dipantau oleh mahasiswa.

---

## 3. Tujuan Produk

* Menyediakan satu platform untuk mengakses informasi dan layanan yang relevan bagi mahasiswa UNY.
* Mempermudah mahasiswa UNY menemukan informasi mengenai kegiatan, organisasi, fasilitas, dan layanan yang tersedia.
* Mempermudah mahasiswa menyampaikan laporan terkait masalah fasilitas atau lingkungan kampus.
* Membantu pengelola mengelola informasi, kegiatan, fasilitas, dan laporan secara terpusat.
* Memberikan informasi mengenai status laporan agar tindak lanjut dapat dipantau oleh mahasiswa.
* Mengurangi kebutuhan mahasiswa untuk mencari informasi dari berbagai sumber yang terpisah.

---

## 4. Target Pengguna

### 4.1 Mahasiswa UNY

Pengguna utama SIUNYA yang dapat:

* Mengakses informasi universitas.
* Melihat event atau kegiatan.
* Melihat informasi organisasi atau UKM.
* Melihat informasi fasilitas.
* Melaporkan permasalahan fasilitas.
* Memantau status laporan yang telah dibuat.

### 4.2 Admin/Pengelola

Pengguna internal yang bertugas:

* Mengelola informasi.
* Mengelola event atau kegiatan.
* Mengelola informasi organisasi atau unit terkait.
* Mengelola data fasilitas.
* Menerima dan menindaklanjuti laporan mahasiswa.
* Memperbarui status laporan.

### 4.3 Organisasi/Unit Terkait

Pihak yang dapat berperan sebagai penyedia atau pengelola informasi kegiatan dan layanan tertentu sesuai dengan kewenangan yang diberikan dalam sistem.

---

## 5. Ruang Lingkup Produk

SIUNYA berfokus pada penyediaan informasi dan layanan mahasiswa yang dapat dihimpun dalam satu platform.

### Fitur utama:

1. Informasi universitas.
2. Event atau kegiatan mahasiswa.
3. Informasi organisasi atau UKM.
4. Informasi fasilitas kampus.
5. Pelaporan permasalahan fasilitas.
6. Pemantauan status laporan.
7. Dashboard pengelolaan bagi admin.

### Batasan Scope

Untuk menjaga kompleksitas proyek, SIUNYA **tidak mencakup penggantian sistem akademik inti maupun sistem internal universitas yang telah tersedia**, seperti:

* KRS.
* Nilai akademik.
* Presensi.
* Pembayaran.
* Pengelolaan akademik mahasiswa.
* Sistem administrasi internal universitas lainnya.

SIUNYA berperan sebagai platform informasi dan layanan terpadu mahasiswa, bukan sebagai pengganti seluruh sistem informasi yang telah digunakan oleh UNY.

---

## 6. Metodologi Pendekatan

### Agile

Pengembangan SIUNYA menggunakan pendekatan **Agile** dengan proses pengembangan secara **iteratif dan incremental**.

Pendekatan ini dipilih karena SIUNYA memiliki beberapa karakteristik:

* Memiliki cakupan tingkat universitas dengan stakeholder yang beragam.
* Kebutuhan pengguna berpotensi berkembang setelah mendapatkan feedback.
* Sistem memiliki beberapa modul yang dapat dikembangkan secara bertahap.
* Feedback dari mahasiswa dan stakeholder diperlukan untuk mengevaluasi kesesuaian fitur.
* Sistem dapat dikembangkan melalui beberapa iterasi sehingga perubahan kebutuhan dapat diakomodasi pada iterasi berikutnya.

Setiap iterasi atau sprint mencakup:

```text
Perencanaan
     ↓
Pengembangan
     ↓
Pengujian
     ↓
Evaluasi
     ↓
Feedback
     ↓
Perbaikan / Prioritas Iterasi Berikutnya
```

Pengembangan tidak harus menyelesaikan seluruh fitur sekaligus. Fitur dapat diprioritaskan berdasarkan kebutuhan dan dikembangkan secara bertahap.

Contoh pembagian pengembangan:

```text
Sprint 1
Authentication + Dashboard dasar

Sprint 2
Informasi + Event

Sprint 3
Organisasi / UKM

Sprint 4
Fasilitas + Lost & Found

Sprint 5
Pelaporan + Status laporan

Sprint 6
Admin Dashboard + Penyempurnaan
```

Pembagian sprint tersebut bersifat contoh dan dapat disesuaikan berdasarkan prioritas serta hasil evaluasi tim.

---

## 7. Alur Penggunaan Utama

### 7.1 Alur Mahasiswa

```text
Login
  ↓
Beranda
  ↓
Memilih layanan
  ↓
Melihat / Menginput data
  ↓
Sistem memproses
  ↓
Hasil / Status ditampilkan
```

### 7.2 Contoh Alur Pelaporan Fasilitas

```text
Login
  ↓
Lost & Found / Laporan
  ↓
Pilih kategori dan lokasi
  ↓
Isi deskripsi + foto
  ↓
Kirim laporan
  ↓
Laporan tersimpan
  ↓
Admin menerima laporan
  ↓
Admin memproses laporan
  ↓
Status diperbarui
  ↓
Mahasiswa melihat status laporan
```

### 7.3 Alur Admin

```text
Login
  ↓
Admin Dashboard
  ↓
Kelola informasi / event / organisasi / fasilitas
          atau
      Membuka laporan
  ↓
Memproses perubahan
  ↓
Sistem menyimpan perubahan
  ↓
Informasi / status ditampilkan kepada mahasiswa
```

---

## 8. Functional Requirements

| ID    | Functional Requirement                                                                               |
| ----- | ---------------------------------------------------------------------------------------------------- |
| FR-01 | Sistem menyediakan autentikasi pengguna sesuai role mahasiswa/admin.                                 |
| FR-02 | Mahasiswa dapat melihat daftar dan detail informasi universitas.                                     |
| FR-03 | Admin dapat menambah, mengubah, dan menghapus informasi.                                             |
| FR-04 | Mahasiswa dapat melihat daftar dan detail event/kegiatan.                                            |
| FR-05 | Admin dapat mengelola data event/kegiatan.                                                           |
| FR-06 | Mahasiswa dapat melihat informasi organisasi atau UKM yang tersedia.                                 |
| FR-07 | Admin dapat mengelola informasi organisasi atau UKM sesuai kewenangannya.                            |
| FR-08 | Mahasiswa dapat melihat fasilitas berdasarkan kategori dan lokasi.                                   |
| FR-09 | Admin dapat mengelola data fasilitas.                                                                |
| FR-10 | Mahasiswa dapat membuat laporan permasalahan fasilitas dengan kategori, lokasi, deskripsi, dan foto. |
| FR-11 | Admin dapat melihat laporan yang dibuat oleh mahasiswa.                                              |
| FR-12 | Admin dapat memperbarui status laporan.                                                              |
| FR-13 | Mahasiswa dapat melihat status laporan yang telah dibuat.                                            |

---

## 9. Non-Functional Requirements

### 9.1 Usability

Antarmuka SIUNYA harus sederhana, mudah dipahami, dan dapat digunakan oleh mahasiswa dari berbagai latar belakang program studi.

### 9.2 Security

Akses terhadap fitur dan data admin dibatasi berdasarkan role pengguna.

### 9.3 Maintainability

Data informasi, event, organisasi, fasilitas, dan laporan disimpan secara terstruktur sehingga dapat dikelola dan dikembangkan lebih lanjut.

### 9.4 Responsiveness

Antarmuka dapat digunakan pada perangkat desktop maupun mobile.

### 9.5 Performance

Halaman utama dan layanan utama dapat dimuat secara wajar pada koneksi internet kampus maupun koneksi seluler.

---

## 10. Data Utama

### User

* user_id
* nama
* email
* role

### Informasi

* informasi_id
* judul
* isi
* tanggal
* status

### Event

* event_id
* nama
* tanggal
* lokasi
* deskripsi
* link_pendaftaran

### Organisasi

* organisasi_id
* nama
* jenis
* deskripsi
* kontak
* link

### Fasilitas

* fasilitas_id
* nama
* kategori
* lokasi
* deskripsi
* status

### Laporan

* laporan_id
* user_id
* fasilitas_id
* kategori
* deskripsi
* foto
* status
* tanggal

---

## 11. User Stories

### Mahasiswa

**US-01** — Sebagai mahasiswa UNY, saya ingin melihat informasi universitas agar tidak perlu mencari informasi dari banyak sumber.

**US-02** — Sebagai mahasiswa UNY, saya ingin melihat event agar mengetahui kegiatan yang tersedia.

**US-03** — Sebagai mahasiswa UNY, saya ingin melihat informasi organisasi atau UKM agar mengetahui organisasi dan kegiatan yang tersedia.

**US-04** — Sebagai mahasiswa UNY, saya ingin mencari informasi fasilitas agar mengetahui lokasi dan informasi fasilitas yang tersedia.

**US-05** — Sebagai mahasiswa UNY, saya ingin melaporkan fasilitas yang bermasalah agar laporan dapat diteruskan kepada pengelola.

**US-06** — Sebagai mahasiswa UNY, saya ingin melihat status laporan agar mengetahui perkembangan tindak lanjut laporan saya.

### Admin/Pengelola

**US-07** — Sebagai admin/pengelola, saya ingin mengelola informasi agar informasi yang tersedia tetap relevan.

**US-08** — Sebagai admin/pengelola, saya ingin mengelola event dan kegiatan agar informasi kegiatan dapat diperbarui.

**US-09** — Sebagai admin/pengelola, saya ingin mengelola informasi organisasi atau UKM agar informasi organisasi dapat ditampilkan kepada mahasiswa.

**US-10** — Sebagai admin/pengelola, saya ingin mengelola data fasilitas agar informasi fasilitas tetap akurat.

**US-11** — Sebagai admin/pengelola, saya ingin melihat dan memproses laporan mahasiswa agar permasalahan fasilitas dapat ditindaklanjuti.

**US-12** — Sebagai admin/pengelola, saya ingin memperbarui status laporan agar mahasiswa mengetahui perkembangan laporan yang dibuat.

---

## 12. Batasan dan Asumsi

* Dokumen ini merupakan PRD awal dan dapat mengalami perubahan selama proses pengembangan.
* SIUNYA memiliki cakupan tingkat Universitas Negeri Yogyakarta.
* SIUNYA tidak menggantikan sistem akademik inti maupun sistem internal universitas yang telah tersedia.
* Informasi yang ditampilkan dalam SIUNYA diasumsikan berasal dari pihak yang memiliki kewenangan untuk menyediakan informasi tersebut.
* Pengelolaan konten dan laporan dilakukan oleh admin atau pihak yang memiliki hak akses sesuai role.
* Tautan pendaftaran event dapat menggunakan layanan eksternal sehingga kelompok tidak perlu membangun modul pendaftaran yang kompleks.
* Pengembangan dilakukan secara bertahap dan dapat disesuaikan berdasarkan hasil evaluasi serta feedback pengguna.
* Fitur yang tidak termasuk dalam scope dapat dipertimbangkan untuk pengembangan di masa mendatang, tetapi tidak menjadi prioritas dalam pengembangan awal.

---

## 13. Indikator Keberhasilan

* Mahasiswa UNY dapat menemukan informasi yang relevan melalui satu platform.
* Mahasiswa dapat menemukan informasi event dan organisasi yang tersedia.
* Mahasiswa dapat menemukan informasi fasilitas berdasarkan kategori dan lokasi.
* Mahasiswa dapat membuat laporan fasilitas secara digital.
* Admin dapat mengelola informasi, event, organisasi, fasilitas, dan laporan dari satu dashboard.
* Mahasiswa dapat mengetahui status laporan yang dibuat.
* Alur utama sistem dapat direalisasikan sebagai prototype/software tanpa memperluas scope ke sistem akademik inti.
* Sistem dapat dikembangkan secara bertahap berdasarkan feedback dan evaluasi pada setiap iterasi.
* Scope pengembangan tetap terkontrol meskipun SIUNYA memiliki cakupan tingkat universitas.

---

## 14. Prioritas Pengembangan Awal

Untuk menjaga scope tetap realistis, pengembangan awal SIUNYA diprioritaskan pada fitur yang menjadi inti produk.

### Prioritas Utama

1. Authentication dan role pengguna.
2. Dashboard.
3. Informasi.
4. Event/kegiatan.
5. Informasi fasilitas.
6. Lost & Found / pelaporan.
7. Status laporan.
8. Admin dashboard.

### Prioritas Pengembangan Berikutnya

1. Informasi organisasi/UKM yang lebih lengkap.
2. Notifikasi.
3. Filter dan pencarian lanjutan.
4. Integrasi dengan layanan atau sistem eksternal jika diperlukan.

Fitur tambahan hanya dikembangkan apabila tidak mengganggu scope dan tujuan utama SIUNYA.

---

## 15. Catatan Produk

Nama produk yang digunakan adalah **SIUNYA**.

SIUNYA memiliki cakupan tingkat **Universitas Negeri Yogyakarta**, bukan hanya Fakultas Teknik. Produk difokuskan pada penyediaan informasi, kegiatan, fasilitas, organisasi, serta layanan pelaporan bagi mahasiswa.

SIUNYA tidak dimaksudkan untuk menggantikan SIAKAD, sistem pembayaran, presensi, KRS, nilai, maupun sistem akademik dan administrasi internal lainnya.

Pengembangan SIUNYA menggunakan pendekatan **Agile** dengan pengembangan secara **iteratif dan incremental**, sehingga sistem dapat dikembangkan secara bertahap serta disesuaikan berdasarkan feedback pengguna dan stakeholder.
