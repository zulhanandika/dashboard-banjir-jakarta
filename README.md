<div id="top"></div>
<br/>
<div align="center">
  <a href="https://www.jakarta.go.id/">
    <img src="images/Logo Jakarta.png" alt="Pemerintah Provinsi DKI Jakarta" width="80" height="80">
  </a>

  <h2 align="center">Dashboard Informasi Banjir Provinsi DKI Jakarta</h3>

  <p align="center">
    Waspadai bencana banjir Jakarta bersama-sama!
    <br />
    <br />
    <a href="https://public.tableau.com/app/profile/zulhan.andika.asyraf/viz/DashboardBanjirProvinsiDKIJakarta/Dashboard"><strong>Buka dashboard »</strong></a>
    <h5>Harap buka dashboard secara full screen</h5>
    <br />
    <br />
    <a href="https://www.jakarta.go.id/">Pemprov DKI Jakarta</a>
    ·
    <a href="https://data.jakarta.go.id/">Portal Data Terbuka DKI Jakarta</a>
  </p>
</div>

<details>
  <summary>Daftar Isi</summary>
  <ol>
    <li>
      <a href="#tentang-dashboard">Tentang Dashboard</a>
      <ul>
        <li><a href="#halaman-dashboard">Halaman Dashboard</a></li>
      </ul>
    </li>
    <li><a href="#panduan-penggunaan">Panduan Penggunaan</a></li>
    <li><a href="#sumber-data">Sumber Data</a></li>
    <li><a href="#metodologi">Metodologi</a></li>
    <li><a href="#tentang-pengembang">Tentang Pengembang</a></li>
    <li><a href="#informasi-selengkapnya">Informasi Selengkapnya</a></li>
  </ol>
</details>

## Tentang Dashboard

Dashboard Informasi Provinsi Banjir Provinsi DKI Jakarta adalah sebuah dashboard yang dikembangkan untuk menyajikan informasi yang dapat diakses oleh pemerintah dan juga seluruh masyarakat untuk memantau dan mengantisipasi bencana banjir di Provinsi DKI Jakarta. Dashboard ini berisi visualisasi-visualisasi data banjir Provinsi DKI Jakarta yang disajikan menggunakan berbagai jenis visualisasi seperti peta tematik, diagram batang, diagram garis, dan sebagainya sehingga dapat membantu pengguna dalam memahami data mengenai bencana banjir yang disediakan oleh Pemerintah Provinsi DKI Jakarta. Dashboard ini dibuat secara mandiri sebagai upaya untuk meningkatkan kewaspadaan dan kesiapsiagaan masyarakat DKI Jakarta terhadap risiko bencana banjir di Provinsi DKI Jakarta.

<p align="right">(<a href="#top">kembali ke atas</a>)</p>

### Halaman Dashboard

Halaman Dashboard Informasi Banjir Provinsi DKI Jakarta dapat dibuka pada situs Tableau Public yang dapat diakses dengan klik pada tautan di bawah ini.

<a href="https://public.tableau.com/app/profile/zulhan.andika.asyraf/viz/DashboardBanjirProvinsiDKIJakarta/Dashboard"><strong>Buka dashboard »</strong></a>

Dashboard ini terdiri dari beberapa bagian, yaitu sebagai berikut.\
![Tampilan Dashboard](images/Tampilan%20Dashboard.png)
* Visualisasi peta banjir DKI Jakarta per kelurahan, kecamatan, kota, dan provinsi.\
  ![Peta Banjir Jakarta](images/Peta%20Banjir%20Jakarta.png)
* Visualisasi rata-rata jumlah cakupan terdampak yang meliputi cakupan kecamatan, kelurahan, RW, dan keluarga terdampak, baik bulanan maupun tahunan.\
  ![Jumlah Cakupan Terdampak](images/Cakupan%20Terdampak.png)
* Visualisasi perbandingan antara rata-rata jumlah jiwa terdampak dengan rata-rata jumlah tempat pengungsian, baik bulanan maupun tahunan.\
  ![Jumlah Jiwa Terdampak dan Tempat Pengungsian](images/Jiwa%20Terdampak%20dan%20Tempat%20Pengungsian.png)
* Visualisasi rata-rata lama genangan banjir dan ketinggian air maksimal urut dari yang tertinggi, baik bulanan maupun tahunan.\
  ![Lama Genangan Banjir](images/Lama%20Genangan.png)
* Visualisasi jumlah korban tahunan yang meliputi korban meninggal, hilang, luka berat, dan luka ringan, baik urut dari yang tertinggi maupun urut waktu.\
  ![Jumlah Korban Urut Tertinggi](images/Jumlah%20Korban%20Urut%20Tertinggi.png)
  ![Jumlah Korban Urut Waktu](images/Jumlah%20Korban%20Urut%20Waktu.png)

<p align="right">(<a href="#top">kembali ke atas</a>)</p>

## Panduan Penggunaan

Sebelum menggunakan dashboard, terdapat beberapa hal yang perlu diperhatikan oleh pengguna, di antaranya sebagai berikut.

* Diperlukan `laptop/PC` untuk membuka dashboard
* Diperlukan `koneksi internet` untuk membuka dashboard
* Dashboard dapat diakses pada [halaman berikut](https://public.tableau.com/app/profile/zulhan.andika.asyraf/viz/DashboardBanjirProvinsiDKIJakarta/Dashboard)
* Pastikan browser sudah berada pada posisi _`zoom`_ `100%`
* Buka dashboard secara _`full screen`_ dengan klik pada bagian pojok kanan bawah
* Sesuaikan nilai parameter sesuai jenis data yang ingin divisualisasikan.
* Arahkan kursor ke grafik untuk melihat penjelasan atau nilai dari data tertentu.
* Terdapat penjelasan data berupa _mark_ yang menunjuk ke arah tertentu dan _caption_ yang ada di bawah grafik.
* Jika ingin mengurutkan dari nilai yang tertinggi, klik pada sebelah kiri sumbu Y setiap grafik.

<p align="right">(<a href="#top">kembali ke atas</a>)</p>

## Sumber Data

Seluruh data yang digunakan pada dashboard ini diambil dari [Portal Data Terbuka Pemerintah Provinsi DKI Jakarta](https://data.jakarta.go.id/) dengan dilakukan beberapa pengolahan agar siap untuk divisualisasikan. Selain itu, _Shapefile_ batas administrasi kelurahan Provinsi DKI Jakarta yang digunakan diunduh dari [Open Street Map](https://openstreetmap.id/data-dki-jakarta/).

<p align="right">(<a href="#top">kembali ke atas</a>)</p>

## Metodologi

Tahapan pengembangan Dashboard Informasi Banjir Provinsi DKI Jakarta sebagai berikut.

1. **Menentukan tujuan pembuatan dashboard dan informasi yang ingin disampaikan.**\
   Tujuan pembuatan dashboard ini yaitu untuk memberikan informasi mengenai banjir di Provinsi DKI Jakarta, baik secara spasial maupun temporal yang dapat diakses oleh seluruh masyarakat untuk memantau dan mengantisipasi banjir di Provinsi DKI Jakarta.
2. **Mengumpulkan data yang akan digunakan, yaitu data banjir di Provinsi DKI Jakarta dan _shapefile_ wilayah administrasi Provinsi DKI Jakarta.**\
   Data banjir di Provinsi DKI Jakarta didapatkan dari Portal Data Terbuka Provinsi DKI Jakarta yang terdiri dari data kejadian bencana banjir tahun 2013-2020 di DKI Jakarta dan data rekapitulasi tahunan dari 2013-2020 kejadian banjir di Provinsi DKI Jakarta. Berikut ini daftar variabel yang terdapat pada data kejadian bencana banjir di Provinsi DKI Jakarta.
   |Nama Variabel|Penjelasan|
   |:---:|---|
   |`kota_administrasi`| nama kota di Provinsi DKI Jakarta yang terkena dampak banjir|
   |`kecamatan`| nama kecamatan yang terkena dampak banjir|
   |`kelurahan`| nama kelurahan yang terkena dampak banjir|
   |`rw`| nama RW yang terkena dampak banjir|
   |`jumlah_terdampak_rw`| jumlah RW yang terkena dampak banjir|
   |`jumlah_terdampak_rt`| jumlah RT yang terkena dampak banjir|
   |`jumlah_terdampak_kk`| jumlah kepala keluarga yang terkena dampak banjir|
   |`jumlah_terdampak_jiwa`| jumlah orang yang terkena dampak banjir|
   |`ketinggian_air`| ketinggian air pada saat kejadian banjir (cm)|
   |`tanggal_kejadian`| tanggal kejadian banjir|
   |`lama_genangan`| lama genangan saat banjir (hari)|
   |`jumlah_meninggal`| jumlah korban meninggal saat kejadian banjir|
   |`jumlah_hilang`| jumlah korban hilang saat kejadian banjir|
   |`jumlah_luka_berat`| jumlah korban luka berat saat kejadian banjir|
   |`jumlah_luka_ringan`| jumlah korban luka ringan saat kejadian banjir|
   |`jumlah_pengungsi_tertinggi`| jumlah pengungsi banjir|
   |`jumlah_tempat_pengungsian`| jumlah tempat pengungsian korban banjir|
   |`nilai_kerugian`| jumlah nilai kerugian akibat kejadian banjir|
  
   Selain itu, batas administrasi yang digunakan untuk menampilkan peta banjir Jakarta didapatkan dari situs Open Street Map. Batas administrasi yang digunakan yaitu hanya batas kelurahan.
3. **Memeriksa struktur data, kelengkapan data, konsistensi nilai, dan kesesuaian format.**\
   Data banjir yang tersedia masih dipisah per per bulan. Variabel yang bertipe string yaitu kota_administrasi, kecamatan, kelurahan, rw, ketinggian_air, dan tanggal_kejadian. Sementara itu, variabel yang bertipe numerik yaitu jumlah_terdampak_rw, jumlah_terdampak_rt, jumlah_terdampak_kk, jumlah_terdampak_jiwa, lama_genangan, jumlah_meninggal, jumlah_hilang, jumlah_luka_berat, jumlah_luka_ringan, jumlah_pengungsi_tertinggi, jumlah_tempat_pengungsian, dan nilai_kerugian. Nilai yang terdapat pada variabel kota_administrasi, kecamatan, dan kelurahan masih banyak ditemui salah ketik dan penamaan daerah yang tidak konsisten. Selain itu, terdapat kelurahan yang nama kecamatannya salah atau kecamatan yang nama kotanya salah. Pada variabel RW, masih terdapat nilai ganda yang dipisahkan dengan tanda koma sehingga perlu dipisahkan dulu. Pada variabel ketinggian_air, masih terdapat nilai berupa rentang yang dipisahkan dengan tanda strip atau “s/d” dan masih terdapat satuannya semua dalam cm. Pada variabel tanggal_kejadian, masih terdapat nilai ganda yang dipisahkan dengan tanda koma dan masih terdapat karakter yang tidak perlu yaitu “tgl” karena sudah ada pada nama variabel.
4. **Melakukan _preprocessing_ untuk menyiapkan dan merapikan data.**\
   Tahapan _preprocessing_ dilakukan menggunakan _software_ RStudio untuk menyiapkan data hingga siap untuk divisualisasikan. Tahapan _preprocessing_ yang dilakukan meliputi:
   <ol type="a">
        <li>Menyatukan data banjir seluruh tahun.</li>
        Data yang tersedia masih berupa data kejadian banjir bulanan sehingga perlu seluruh data perlu digabung menjadi satu.
        <li>Menghilangkan satuan pada data.</li>
        Variabel ketinggian_air masih mengandung satuan dalam cm sehingga perlu dihilangkan.
        <li>Memisahkan data yang isinya lebih dari satu.</li>
        Variabel RW dan tanggal_kejadian masih mengandung nilai ganda atau berupa rentang sehingga perlu dipisahkan sehingga satu sel hanya mengandung tepat satu nilai. 
        <li>Memperbaiki kesalahan penulisan.</li>
        Masih terdapat sangat banyak kesalahan penulisan pada variabel kota_administrasi, kecamatan, dan kelurahan sehingga perlu diperbaiki.
        <li>Menyesuaikan nama wilayah pada data dengan nama wilayah pada shapefile wilayah administrasi Provinsi DKI Jakarta.</li>
        Nilai variabel kota_administrasi, kecamatan, dan kelurahan masih berbeda dengan nama wilayah pada shapefile batas administrasi sehingga perlu disamakan menyesuaikan pada shapefile supaya bisa dilakukan penggabungan (join).
        <li>Memisahkan variabel yang berupa rentang.</li>
        Nilai pada variabel ketinggian_air masih berupa rentang sehingga perlu dipisahkan menjadi nilai minimum dan maksimum. Pada penelitian ini, yang digunakan hanya nilai ketinggian maksimum karena lebih penting untuk mewaspadai kemungkinan terburuk dari banjir.
        <li>Menyesuaikan format data.</li>
        Format penulisan variabel kota_administrasi, kecamatan, dan kelurahan masih banyak yang berbeda ada yang kapital di awal kata dan ada yang kapital semua huruf sehingga perlu disamakan menjadi kapital di awal kata saja. 
        <li>Melakukan agregasi per bulan dan tahun.</li>
        Unit setiap baris data yang tersedia menunjukkan nilai per kejadian. Data tersebut dilakukan agregasi per bulan dan tahun untuk mendapatkan data banjir per bulan dan tahun.
        <li>Melakukan imputasi nilai yang kosong.</li>
        Setelah diagregasi, terdapat beberapa bulan di tahun tertentu yang tidak terdapat kejadian banjir sehingga perlu dilakukan imputasi nilai yang kosong dengan nilai nol.
   </ol>
5. **Menyiapkan _software_ yang akan digunakan.**\
   _Software_ yang digunakan untuk visualisasi data yaitu Tableau Desktop versi 22.1.2434. Software Tableau dipilih karena dapat digunakan untuk melakukan visualisasi data dan dashboard secara interaktif dan penggunaannya cukup mudah sebagaimana banyak digunakan pada penelitian terdahulu.
6. **Mengimpor data yang akan digunakan ke software.**\
   Data hasil _preprocessing_ dan _shapefile_ batas administrasi kelurahan di DKI Jakarta diimpor pada _software_ Tableau.
7. **Memastikan kesesuaian format dan tipe data.**\
   Memeriksa kembali kesesuaian format dan tipe data yang sudah dideteksi secara otomatis oleh Tableau untuk memastikan sudah sesuai, misalnya pada data tanggal, kemudian juga data yang awalnya bertipe string kemudian diubah menjadi numerik pada tahap _preprocessing_.
8. **Menggabungkan data dengan _shapefile_ wilayah administrasi Provinsi DKI Jakarta.**\
   Data hasil _preprocessing_ dan _shapefile_ batas administrasi kelurahan di DKI Jakarta perlu digabungkan berdasarkan nama kelurahan yang formatnya sudah disamakan pada tahap _preprocessing_.
9.  **Membuat visualisasi-visualisasi yang dibutuhkan.**\
    Visualisasi-visualisasi yang akan ditampilkan pada dashboard perlu dibuat terlebih dahulu secara terpisah sebelum digabungkan pada dashboard.
10. **Menambahkan _captions_ dan _marks_ untuk menjelaskan data.**\
    Visualisasi yang baik yaitu yang memiliki tujuan visualisasi yang spesifik dan memberikan interpretasi pada data yang divisualisasikan, bukan membiarkan pengguna menginterpretasikan masing-masing tanpa ada informasi tertentu yang ingin disampaikan oleh pembuat visualisasi. Oleh karena itu, pada penelitian ini, ditambahkan interpretasi menggunakan _marks_ untuk memberikan penjelasan data yang spesifik secara singkat dan menggunakan _captions_ untuk memberikan penjelasan data secara garis besar.
11. **Mengatur format pada visualisasi.**\
    Format huruf, perataan teks, warna, garis tepi, dan garis pada visualisasi perlu diatur dan disesuaikan sesuai kebutuhan.
12. **Membuat visualisasi menjadi interaktif dengan menambahkan parameter pada visualisasi.**\
    Parameter digunakan untuk menyediakan pilihan bagi pengguna untuk menyesuaikan visualisasi yang ditampilkan sehingga tampilan visualisasi menjadi lebih interaktif dan dinamis. Terdapat beberapa parameter yang digunakan, yaitu parameter level wilayah peta banjir (kelurahan, kecamatan, kota, dan provinsi), parameter cakupan terdampak (kecamatan, kelurahan, RW, dan keluarga), parameter jangka waktu (bulanan dan tahunan), parameter urutan grafik (urut tertinggi dan urut waktu), serta parameter jenis korban (meninggal, hilang, luka berat, dan luka ringan).
13. **Menggabungkan visualisasi-visualisasi pada dashboard dan memberikan penjelasan sesuai kebutuhan.**\
    Visualisasi yang sudah dibuat secara terpisah digabungkan menjadi satu pada dashboard beserta judul, parameter, dan legenda sesuai kebutuhan. Visualisasi-visualisasi pada dashboard tersebut disusun sedemikian rupa menurut urgensinya.
14. **Memeriksa kembali isi dashboard dan melakukan revisi jika diperlukan.**\
    Dashboard yang sudah dibuat perlu dilakukan pemeriksaan akhir untuk mengidentifikasi apakah terdapat kesalahan penulisan atau terdapat hal-hal yang masih belum sesuai untuk dapat direvisi sebelum dipublikasikan.
15. **Mempublikasikan dashboard pada Tableau Public.**\
    Dashboard dipublikasikan menggunakan Tableau Public supaya dapat digunakan oleh seluruh masyarakat.
16. **Melakukan survei System Usability Scale (SUS) untuk  mengevaluasi dashboard yang sudah dibuat.**\
    Dashboard ini dibuat untuk dapat digunakan oleh seluruh masyarakat sehingga perlu dievaluasi menggunakan pengujian SUS.
17. **Melakukan revisi atau perbaikan akhir.**\
    Dashboard yang sudah dievaluasi perlu diperbaiki kembali sesuai dengan hasil pengujian dan saran dari pengguna agar dashboard sesuai dengan harapan pengguna.

<p align="right">(<a href="#top">kembali ke atas</a>)</p>

## Tentang Pengembang

Dashboard ini dikembangkan oleh **Zulhan Andika Asyraf** (221910827 - 3SD2). **Zulhan Andika Asyraf** adalah seorang mahasiswa Politeknik Statistika STIS program studi DIV Komputasi Statistik Peminatan Sains Data. Profil selengkapnya dapat dilihat pada tautan berikut.\
[Profil Pengembang](https://id.linkedin.com/in/zulhanandika)

<p align="right">(<a href="#top">kembali ke atas</a>)</p>

## Informasi Selengkapnya

Berikut ini beberapa referensi untuk informasi lebih lanjut mengenai banjir di Provinsi DKI Jakarta.

* [Pemerintah Provinsi DKI Jakarta](https://www.jakarta.go.id/)
* [Portal Data Terbuka Provinsi DKI Jakarta](https://data.jakarta.go.id/)
* [Pantau Banjir DKI Jakarta](https://pantaubanjir.jakarta.go.id/)
* [Peta Bencana DKI Jakarta](https://petabencana.id/map/Daerah%20Khusus%20Ibukota%20Jakarta)
* [Data Penganggulangan Bencana DKI Jakarta](https://data.jakarta.go.id/group/penanggulangan-bencana)
* [Badan Penanggulangan Bencana DKI Jakarta](https://bpbd.jakarta.go.id/)
* [Badan Nasional Penanggulangan Bencana](https://bnpb.go.id/)

<p align="right">(<a href="#top">kembali ke atas</a>)</p>