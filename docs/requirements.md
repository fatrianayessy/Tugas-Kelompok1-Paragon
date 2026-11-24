# MASTERSHEET PEMROGRAMAN - KELOMPOK 1 (MICE 3A)

## Anggota Kelompok 1
* **Nikeisha Aqilah Dhia** (2505413005)
* **Zefanya Permata Marbun** (2505413004)
* **Paramitha Nuraini Maulida** (2505413027)
* **Adam Reyhan Herlambang** (2505413065)
* **Fatriana Yessy** (2505413069)
* **Nakhwa Khalisha** (2505413038)

---

## Latar Belakang Project

ParagonCorp merupakan perusahaan induk (*holding company*) asal Indonesia yang bergerak di industri kecantikan, khususnya pengembangan dan produksi kosmetik serta produk perawatan diri. ParagonCorp menaungi berbagai merek kecantikan populer, seperti Wardah, Make Over, Emina, dan Kahf. Selain berfokus pada inovasi produk dan pengembangan industri kecantikan, ParagonCorp juga menjalankan program *Corporate Social Responsibility* (CSR) sebagai bentuk kontribusi perusahaan kepada masyarakat dan lingkungan. Program CSR tersebut mencakup empat bidang utama, yaitu pendidikan (*Education*), kesehatan (*Health*), pemberdayaan perempuan (*Women Empowerment*), dan lingkungan (*Environment*). Melalui kegiatan bisnis dan tanggung jawab sosialnya, ParagonCorp berupaya memberikan nilai tambah bagi konsumen, masyarakat, dan lingkungan secara berkelanjutan.

*Corporate Social Responsibility* (CSR) merupakan bentuk tanggung jawab perusahaan terhadap masyarakat dan lingkungan melalui berbagai program yang memberikan dampak positif secara berkelanjutan. ParagonCorp memiliki laman CSR yang menampilkan empat fokus utama, yaitu *Education*, *Health*, *Women Empowerment*, dan *Environment*. Namun, berdasarkan pengamatan awal terhadap website tersebut, ikon-ikon kategori yang ditampilkan belum dapat diakses secara optimal sehingga informasi mengenai program CSR pada setiap kategori belum dapat dijangkau melalui ikon tersebut. Selain itu, laman CSR masih memiliki peluang untuk dikembangkan agar tidak hanya menjadi media pengenalan program, tetapi juga menjadi sarana informasi yang menunjukkan hasil dan dampak nyata dari pelaksanaan CSR ParagonCorp. 

Oleh karena itu, project ini dipilih untuk mengoptimalkan fungsi dan interaktivitas laman CSR melalui pengembangan fitur navigasi pada setiap ikon kategori serta penyediaan informasi mengenai program yang telah dilaksanakan, jumlah penerima manfaat, wilayah yang terdampak, dan capaian dari masing-masing program. Dengan adanya pengembangan ini, website CSR ParagonCorp diharapkan dapat menjadi media informasi yang lebih informatif, mudah diakses, dan transparan sehingga masyarakat dapat memahami kontribusi perusahaan dalam bidang pendidikan, kesehatan, pemberdayaan perempuan, dan lingkungan secara lebih jelas.

### A. Gambaran Isi Project
1. **Pengaktifan empat ikon CSR:** Setiap ikon *Education*, *Health*, *Women Empowerment*, dan *Environment* dapat diklik dan mengarahkan pengunjung ke halaman berisi informasi program sesuai kategorinya.
2. **Penyajian data dampak CSR:** Menampilkan data capaian program, seperti jumlah penerima manfaat, jumlah kegiatan, lokasi pelaksanaan, serta hasil yang telah dicapai berdasarkan data resmi perusahaan.
3. **Pengembangan halaman informasi:** Menyediakan deskripsi program, dokumentasi kegiatan, tahun pelaksanaan, dan hasil program agar masyarakat dapat memahami kontribusi CSR secara lebih konkret.
4. **Peningkatan aksesibilitas informasi:** Membuat informasi CSR lebih mudah ditemukan dan dipahami oleh masyarakat, mahasiswa, calon mitra, serta pihak lain yang ingin mengetahui dampak sosial dan lingkungan dari kegiatan ParagonCorp.

### B. Nama Project
**"Optimalisasi Website CSR ParagonCorp sebagai Media Informasi Dampak dan Transparansi Program CSR"**

### C. Link yang Menjadi Pertimbangan Masalah
* https://www.paragon-innovation.com/csr
* *(Catatan temuan masalah dari tangkapan layar: Tautan tombol "Learn More" pada kategori Education mengarah ke `inspiringmovement.wardahbeauty.com/pilarpage/index/pilar-pendidikan` yang menghasilkan error `This site can't be reached / DNS_PROBE_FINISHED_NXDOMAIN`).*

### D. Batasan Ruang Lingkup
**Ruang lingkup yang tidak termasuk adalah:**
* Website ParagonCorp tampilan utama dan tampilan lainnya.
* Hanya mengerjakan website khusus CSR ParagonCorp.

---

## Kebutuhan Fungsional & Nonfungsional

### Kebutuhan Fungsional

| ID | Jenis | Kebutuhan | Kriteria Penerimaan |
| :--- | :--- | :--- | :--- |
| **F-01** | Fungsional | Pengguna dapat melihat bagian *Our Goals* (tujuan dan target program CSR) | Pernyataan tujuan CSR dan target capaian (misalnya jumlah penerima manfaat) tampil beserta batas waktunya |
| **F-02** | Fungsional | Pengguna dapat melihat empat fokus utama CSR ParagonCorp | Ikon dan nama kategori *Education*, *Health*, *Women Empowerment*, dan *Environment* tampil beserta deskripsi singkat |
| **F-03** | Fungsional | Pengguna dapat melihat ringkasan pencapaian program CSR (*Pencapaian Kami*) | Angka total penerima manfaat, jumlah program, dan wilayah jangkauan tampil di satu bagian ringkas |
| **F-04** | Fungsional | Pengguna dapat mengklik ikon kategori untuk membuka halaman program | Setiap ikon mengarah ke halaman kategori yang sesuai tanpa *broken link* |
| **F-05** | Fungsional | Pengguna dapat melihat daftar dan deskripsi program pada setiap kategori | Nama program, deskripsi, tahun pelaksanaan, target, dan publikasi terkait |
| **F-06** | Fungsional | Pengguna dapat melihat data dampak program | Jumlah penerima manfaat, jumlah kegiatan, lokasi atau wilayah, dan capaian tampil per kategori |
| **F-07** | Fungsional | Pengguna dapat melihat dokumentasi kegiatan CSR | Galeri foto, tanggal pelaksanaan, dan narasi hasil program tampil |
| **F-08** | Fungsional | Pengguna dapat berpindah cepat ke bagian halaman | Semua menu dan *anchor* menuju ID yang benar tanpa *broken link* |
| **F-09** | Fungsional | Pengguna dapat melihat bagian *Annual Reports on CSR* yang tersusun per tahun | Kartu laporan keberlanjutan per tahun tampil berurutan, memuat ukuran file dan tautan unduh PDF |
| **F-10** | Fungsional | Kontak resmi CSR mudah ditemukan | Email, telepon, alamat kantor, dan tautan media sosial tersedia |

### Kebutuhan Nonfungsional

| ID | Jenis | Kebutuhan | Kriteria Penerimaan |
| :--- | :--- | :--- | :--- |
| **NF-01** | Nonfungsional | Layout responsif | Tidak ada scroll horizontal pada viewport desktop, tablet, dan mobile |
| **NF-02** | Nonfungsional | Navigasi dapat digunakan melalui keyboard | Ikon kategori, tautan, dan tombol dapat difokuskan (*focus visible*) dan diaktifkan dengan `Tab` / `Enter` |
| **NF-03** | Nonfungsional | Informasi dampak transparan dan akurat | Setiap data capaian mencantumkan periode dan bersumber dari data resmi perusahaan |
| **NF-04** | Nonfungsional | Halaman dimuat dengan cepat | Halaman utama dan halaman kategori tampil $\le 3$ detik pada koneksi normal |
| **NF-05** | Nonfungsional | Markup valid | Tidak ada error HTML pada validator W3C |
| **NF-06** | Nonfungsional | Audit otomatis memadai | *Accessibility* dan *Best Practices* $\ge 90$ pada Lighthouse |
| **NF-07** | Nonfungsional | Proyek mudah dipelihara | CSS terpisah dan `README.md` tersedia |

---

## Kebutuhan Teknis

1. **Teknologi pengembangan website:**
   Website dikembangkan menggunakan HTML untuk menyusun struktur halaman dan CSS untuk mengatur tampilan serta tata letak website. File HTML dan CSS dipisahkan agar kode lebih terstruktur dan mudah dipelihara.
2. **Ukuran viewport untuk pengujian responsivitas:**
   Pengujian dilakukan menggunakan ukuran viewport dalam CSS pixel, bukan resolusi fisik perangkat, dengan kondisi sebagai berikut:
   * **Ponsel kecil:** lebar `360 px`
   * **Ponsel:** lebar `390 px`
   * **Tablet:** lebar `768 px`
   * **Desktop:** lebar `1366 px`
3. **Browser yang digunakan:**
   Website diuji menggunakan Google Chrome dan Mozilla Firefox untuk memastikan tampilan, navigasi, ikon kategori, dan tautan dapat berfungsi dengan baik.
4. **Navigasi dan interaktivitas:**
   Setiap ikon kategori, menu, dan tautan harus mengarah ke halaman atau bagian yang sesuai. Elemen interaktif juga harus dapat digunakan melalui keyboard menggunakan tombol `Tab` dan `Enter` serta memiliki indikator fokus yang jelas.
5. **Validasi struktur HTML:**
   Struktur HTML diperiksa menggunakan *W3C Markup Validation Service* untuk mengidentifikasi kesalahan penulisan kode HTML.
6. **Pengujian aksesibilitas dan kualitas website:**
   Website diuji menggunakan Lighthouse dengan target skor *Accessibility* dan *Best Practices* minimal 90.
7. **Kecepatan pemuatan halaman:**
   Waktu pemuatan halaman utama dan halaman kategori ditargetkan tidak lebih dari 3 detik pada kondisi koneksi normal.
8. **Penggunaan gambar dan aset visual:**
   Gambar dokumentasi, ikon, dan aset visual harus memiliki kualitas yang sesuai, dioptimalkan agar tidak memperlambat website, serta berasal dari sumber yang memiliki izin penggunaan.
9. **Sumber informasi dan data CSR:**
   Informasi program, tahun pelaksanaan, jumlah penerima manfaat, lokasi, dan capaian program harus menggunakan sumber resmi yang dapat diverifikasi. Periode dan sumber data dicantumkan agar informasi yang disajikan transparan.
10. **Dokumentasi proyek:**
    Proyek dilengkapi dengan file `README.md` yang menjelaskan struktur file, cara menjalankan website, dan informasi pendukung pengembangan.

### Link Sitemap & Wireframe
* https://whimsical.com/csr-sociola/PeWEKuteqpszpTXXVU1rwS
* *(Mencakup wireframe untuk: Paragon CSR - Desktop 1440px, Category Page - Desktop 1440px, Photos Gallery - Desktop 1440px, serta tampilan responsif Tablet dan Mobile).*

---

## Kebutuhan Konten & Aset

### 1. Daftar Teks yang Diperlukan

| No. | Teks yang Diperlukan | Isi yang Dibutuhkan |
| :--- | :--- | :--- |
| 1 | Profil CSR ParagonCorp | Penjelasan mengenai CSR dan komitmen ParagonCorp terhadap masyarakat serta lingkungan. |
| 2 | Deskripsi kategori *Education* | Penjelasan program CSR di bidang pendidikan. |
| 3 | Deskripsi kategori *Health* | Penjelasan program CSR di bidang kesehatan. |
| 4 | Deskripsi kategori *Women Empowerment* | Penjelasan program pemberdayaan perempuan. |
| 5 | Deskripsi kategori *Environment* | Penjelasan program pelestarian lingkungan. |
| 6 | Nama program CSR | Nama setiap program yang sudah dilaksanakan. |
| 7 | Tujuan program | Tujuan dan permasalahan yang ingin diselesaikan melalui program. |
| 8 | Pelaksanaan program | Waktu, lokasi, dan bentuk kegiatan yang dilakukan. |
| 9 | Data penerima manfaat | Jumlah individu atau kelompok yang mendapatkan manfaat dari program. |
| 10 | Wilayah terdampak | Kota, kabupaten, atau daerah tempat program dilaksanakan. |
| 11 | Hasil dan dampak program | Capaian, perubahan, atau manfaat yang dihasilkan dari program CSR. |
| 12 | *Call to Action* (CTA) | Teks tombol, misalnya *Lihat Program*, *Pelajari Selengkapnya*, atau *Lihat Dampak*. |

### 2. Daftar Gambar dan Aset Visual

| No. | Gambar/Aset | Kebutuhan dan Fungsi |
| :--- | :--- | :--- |
| 1 | Logo ParagonCorp | Identitas perusahaan pada halaman CSR. |
| 2 | Ikon *Education* | Ikon navigasi menuju kategori pendidikan. |
| 3 | Ikon *Health* | Ikon navigasi menuju kategori kesehatan. |
| 4 | Ikon *Women Empowerment* | Ikon navigasi menuju kategori pemberdayaan perempuan. |
| 5 | Ikon *Environment* | Ikon navigasi menuju kategori lingkungan. |
| 6 | Foto kegiatan pendidikan | Dokumentasi pelatihan, beasiswa, atau kegiatan pembelajaran. |
| 7 | Foto kegiatan kesehatan | Dokumentasi pemeriksaan kesehatan, edukasi, atau bantuan kesehatan. |
| 8 | Foto pemberdayaan perempuan | Dokumentasi pelatihan keterampilan dan pengembangan usaha perempuan. |
| 9 | Foto kegiatan lingkungan | Dokumentasi penanaman pohon, pengelolaan sampah, atau pelestarian lingkungan. |
| 10 | Foto penerima manfaat | Menunjukkan masyarakat yang terlibat atau menerima manfaat program. |
| 11 | Infografis capaian CSR | Visualisasi jumlah program, penerima manfaat, dan wilayah jangkauan. |
| 12 | Banner atau foto utama | Memperkuat tampilan awal halaman CSR. |

### Panduan Visual Aset
* **A. Ikon navigasi kategori:** Gunakan empat ikon dengan gaya visual yang konsisten. Misalnya, buku untuk *Education*, simbol kesehatan untuk *Health*, figur perempuan untuk *Women Empowerment*, dan daun untuk *Environment*.
* **B. Banner utama (*Hero Image*):** Foto kegiatan sosial dengan komposisi lebar untuk bagian atas halaman CSR. Bisa disertai judul *"Creating Impact Together"* dan deskripsi singkat mengenai komitmen sosial perusahaan.
* **C. Infografis capaian CSR:** Visualisasi jumlah penerima manfaat, jumlah program, dan wilayah pelaksanaan. Angka yang ditampilkan harus berasal dari data resmi perusahaan *(contoh referensi metrik visual: 80+ People Trained, 495 Direct Beneficiaries, Communities Benefited, 100+ Meals Served Weekly, K-12+ Post-Secondary Pathways, Growing Systems Strengthened)*.
* **D. Foto dokumentasi program:** Foto kegiatan dan penerima manfaat untuk halaman detail masing-masing program, dilengkapi keterangan lokasi, tahun, serta hasil kegiatan.