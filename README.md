# Optimalisasi Website CSR ParagonCorp

**Optimalisasi Website CSR ParagonCorp sebagai Media Informasi Dampak dan Transparansi Program CSR** merupakan proyek **Ujian Akhir Semester (UAS)** mata kuliah Pemrograman yang dikembangkan oleh **Kelompok 1 – Kelas MICE 3A** (Program Studi D4 MICE, Jurusan Administrasi Niaga, Politeknik Negeri Jakarta)

Proyek ini berfokus pada pengembangan antarmuka dan pengaktifan navigasi empat pilar utama *Corporate Social Responsibility* (CSR) ParagonCorp (*Education*, *Health*, *Women Empowerment*, dan *Environment*) serta penyajian data dampak program secara transparan, interaktif, dan mudah diakses.

> **Batasan Ruang Lingkup:** Proyek ini hanya mengerjakan laman khusus CSR ParagonCorp (halaman utama CSR, halaman kategori program, dan galeri dokumentasi) dan tidak mencakup tampilan utama maupun halaman korporat ParagonCorp lainnya.

---

## Usage

Ikuti panduan berikut untuk menjalankan serta meninjau struktur desain dan fitur website:

* **Menjalankan Website Secara Lokal:** Unduh atau *clone* repositori ini, lalu buka berkas `index.html` menggunakan browser (**Google Chrome** atau **Mozilla Firefox**), atau jalankan melalui ekstensi **Live Server** pada Visual Studio Code.
* **Struktur Halaman & Fitur Utama:**
  * `index.html`: Menampilkan *Hero Banner*, bagian *Our Goals*, empat ikon navigasi kategori CSR, ringkasan *Pencapaian Kami*, *Annual Reports on CSR* (tautan unduh PDF per tahun), dan kontak resmi.
  * `education.html`, `health.html`, `women-empowerment.html`, `environment.html`: Halaman detail setiap pilar yang memuat daftar program, tahun pelaksanaan, wilayah terdampak, dan jumlah penerima manfaat.
  * `gallery.html`: Galeri dokumentasi kegiatan CSR beserta tanggal dan narasi capaian program.
* **Referensi Desain & Sitemap:** Tata letak antarmuka (Desktop 1440px, Tablet, dan Mobile) dapat ditinjau melalui [Sitemap & Wireframe Whimsical](https://whimsical.com/csr-sociola/PeWEKuteqpszpTXXVU1rwS).

---

## Requirements

Website ini dibangun dan diuji berdasarkan standar teknis berikut:

* **HTML5 & CSS3 Terpisah:** Struktur markup HTML dan stylesheet CSS dipisahkan untuk memudahkan pemeliharaan kode.
* **Browser:** Google Chrome dan Mozilla Firefox.
* **Responsivitas Viewport (CSS Pixel):** Tidak terdapat *horizontal scroll* pada ukuran layar:
  * Ponsel kecil: `360px`
  * Ponsel: `390px`
  * Tablet: `768px`
  * Desktop: `1366px`
* **Validasi & Performa:**
  * Lolos validasi **W3C Markup Validation Service** (bebas error HTML).
  * Skor audit **Lighthouse** minimal **90** pada kategori *Accessibility* dan *Best Practices*.
  * Waktu muat halaman (*page load*) $\le 3$ detik pada koneksi normal.
  * Mendukung navigasi keyboard menggunakan tombol `Tab` dan `Enter` dengan indikator *focus visible* yang jelas.

---

## Bugs / Feature Requests

Proyek UAS ini berangkat dari temuan kendala pada laman CSR sebelumnya (`paragon-innovation.com/csr`), di mana ikon pilar belum terhubung optimal dan tombol *Learn More* pada kategori *Education* mengarah ke `inspiringmovement.wardahbeauty.com/pilarpage/index/pilar-pendidikan` yang menghasilkan error `DNS_PROBE_FINISHED_NXDOMAIN`.

Apabila ditemukan *bug*, tautan rusak (*broken link*), atau kendala tampilan responsif selama pengujian, silakan ajukan laporan melalui tab **Issues** pada repositori ini dengan mencantumkan ukuran *viewport* dan tangkapan layar atau melalui gruo diskusi grup wa.

---

## Community Code of Conduct

Repositori ini dikelola sebagai ruang kolaborasi akademik **Kelompok 1 – Kelas MICE 3A** Politeknik Negeri Jakarta untuk memenuhi tugas Ujian Akhir Semester (UAS) mata kuliah Pemrograman. Seluruh anggota kelompok diharapkan menjaga etika kolaborasi, konsistensi penulisan kode, serta akurasi data yang bersumber dari publikasi resmi perusahaan.

---

## Contributions

Kontribusi pengembangan kode, penyusunan aset visual, serta pengujian fungsional dilakukan oleh anggota **Kelompok 1 (MICE 3A)**:

* **Nikeisha Aqilah Dhia** (`2505413005`)
* **Zefanya Permata Marbun** (`2505413004`)     `
* **Paramitha Nuraini Maulida** (`2505413027`)
* **Adam Reyhan Herlambang** (`2505413065`)
* **Fatriana Yessy** (`2505413069`)
* **Nakhwa Khalisha** (`2505413038`)

---

## License

Proyek ini disusun dan dipublikasikan untuk keperluan tugas **Ujian Akhir Semester (UAS)** mata kuliah Pemrograman di Politeknik Negeri Jakarta. Seluruh identitas merek, logo, dan informasi program CSR yang dicantumkan merupakan hak milik **ParagonCorp** dan digunakan semata-mata untuk tujuan pembelajaran.