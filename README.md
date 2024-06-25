# Proyek Akhir: Menyelesaikan Permasalahan Perusahaan Edutech

## Business Understanding
Jaya Jaya Institut merupakan salah satu institusi pendidikan perguruan yang telah berdiri sejak tahun 2000. Hingga saat ini ia telah mencetak banyak lulusan dengan reputasi yang sangat baik. Akan tetapi, terdapat banyak juga siswa yang tidak menyelesaikan pendidikannya alias dropout. Oleh karena itu, perlu dianalisis faktor-faktor yang mempengaruhi tingginya dropout sehingga Jaya Jaya Institut dapat dengan cepat memberi bimbingan khusus ke mahasiswa tersebut.

### Permasalahan Bisnis
Jaya Jaya Institut menghadapi tantangan serius dengan tingginya tingkat dropout mahasiswa. Dropout yang tinggi tidak hanya merugikan institusi dari segi reputasi dan keuangan, tetapi juga berdampak negatif pada mahasiswa yang tidak menyelesaikan pendidikan mereka. Tingginya angka dropout dapat mengurangi kepercayaan calon mahasiswa dan orang tua terhadap kualitas pendidikan yang ditawarkan oleh Jaya Jaya Institut. Berikut adalah beberapa permasalahan bisnis utama yang dihadapi oleh institusi:

1. Reputasi Institusi
    Tingginya tingkat dropout dapat merusak citra institusi sebagai penyedia pendidikan berkualitas.
2. Kehilangan Pendapatan
    Setiap mahasiswa yang dropout berarti potensi pendapatan dari biaya kuliah dan lainnya yang hilang.
3. Pengaruh pada Akreditasi:
    Tingkat kelulusan yang rendah dapat mempengaruhi akreditasi institusi.
4. Ketidakpuasan Stakeholder
    Mahasiswa, orang tua, dan masyarakat dapat kehilangan kepercayaan terhadap kemampuan institusi dalam mendidik dan mendukung mahasiswa sampai lulus.

### Cakupan Proyek
1. Mengumpulkan dan memproses data mahasiswa.
2. Menganalisis data untuk menemukan pola dan faktor-faktor yang mempengaruhi dropoutnya mahasiswa.
3. Membangun model prediktif menggunakan algoritma Random Forest Classifier.
4. Membuat dashboard bisnis untuk memvisualisasikan temuan dan prediksi.
5. Memberikan rekomendasi tindakan berdasarkan hasil analisis.

### Persiapan
Berikut adalah tahapan untuk menyiapkannya:

sumber data: https://github.com/dicodingacademy/dicoding_dataset/blob/main/students_performance/data.csv

Setup environment:
Apabila menginstal Python melalui Anaconda ataupun miniconda, Anda dapat menggunakan conda sebagai package manager dan environment management system. Berikut merupakan tahapan dalam membuat virtual environment menggunakan conda untuk melakukan prediksi.

1. Buka terminal atau PowerShell.
2. Jalankan perintah berikut.
    ```
     conda create --name prediksi_attrition python=3.9
    ```
3. Aktifkan virtual environment dengan menjalankan perintah berikut.
    ```
    conda activate prediksi_attrition
    ```
4. Instal semua library yang dibutuhkan menggunakan perintah berikut.
    ```
    pip install numpy==1.24.4 pandas==2.1.4 matplotlib==3.7.5 seaborn==0.13.2 scikit-learn==1.4.0 SQLAlchemy==2.0.30 streamlit==1.36.0
    ```
5. Buka jupyter-notebook dengan menjalankan perintah berikut.
    ```
    jupyter-notebook
    ```
6. Buka file python prediction.py
7. Masukkan data yang ingin diprediksi pada variabel X_new
8. Tekan tombol run code
9. Hasil prediksi akan keluar
10. Bisa juga dengan mengakses link streamlit ini: 

## Business Dashboard
Dashboard bisnis dibuat untuk memvisualisasikan data karyawan, tingkat keluarnya karyawan, dan faktor-faktor yang mempengaruhi tingginya attrition rate. Dashboard ini akan menampilkan faktor demografis dan penghasilan, faktor pekerjaan dan kepuasan, faktor
keseimbangan kerja dan kehidupan, dan faktor lainnya yang mempengaruhi tingginya attrition rate.

## Conclusion
Dropout mahasiswa di Jaya Jaya Institut dipengaruhi oleh berbagai faktor yang dapat dikelompokkan ke dalam demografis mahasiswa, latar belakang pendidikan, keadaan ekonomi, keluarga dan latar belakang sosial, serta prestasi akademik. Mahasiswa yang lebih tua saat age at enrollment, berasal dari kategori "over 23 years old" atau "transfer" dalam application mode, mengambil mata kuliah manajemen pada malam hari atau teknik informatika, memiliki nilai admission grade yang rendah, dan tidak mendapatkan beasiswa cenderung lebih berisiko untuk dropout. Selain itu, mahasiswa dengan latar belakang keluarga yang kurang mendukung, terutama yang ibu dan ayahnya memiliki kualifikasi pendidikan yang tidak diketahui, juga menunjukkan kecenderungan dropout yang lebih tinggi. Mahasiswa yang dropout umumnya memiliki prestasi akademik yang lebih rendah

### Rekomendasi Action Items
Berikut adalah rekomendasi yang dapat dilakukan perusahaan Jaya Jaya Maju untuk mengurangi tingkat attrition:

1. Tawarkan bimbingan belajar tambahan dan dukungan akademik bagi mahasiswa yang mengambil mata kuliah manajemen malam hari dan teknik informatika, karena mereka memiliki tingkat dropout yang tinggi.

2. Implementasikan program remedial untuk membantu mahasiswa dengan admission grade rendah agar dapat mengejar ketinggalan dan meningkatkan prestasi akademik mereka.

3. Perluas program beasiswa untuk menjangkau lebih banyak mahasiswa yang berisiko tinggi dropout, dan berikan informasi yang lebih jelas tentang cara mendapatkan bantuan keuangan.

4. Sediakan layanan konseling tambahan dan dukungan psikologis bagi mahasiswa yang orang tuanya memiliki kualifikasi yang tidak diketahui atau rendah.

5. Buat program dukungan untuk mahasiswa yang berasal dari keluarga dengan pekerjaan orang tua yang kurang mendukung secara ekonomi atau sosial.

6. Implementasikan sistem monitoring prestasi akademik secara berkala dan lakukan intervensi dini untuk mahasiswa yang menunjukkan penurunan kinerja akademik.

7. Perbaiki fasilitas kampus seperti perpustakaan, ruang belajar, dan layanan dukungan mahasiswa untuk menciptakan lingkungan belajar yang lebih kondusif.

8. Promosikan program-program yang membantu mahasiswa mencapai keseimbangan antara kehidupan akademik dan pribadi, seperti kegiatan ekstrakurikuler dan layanan kesehatan mental.

9. Libatkan orang tua dalam proses pendidikan mahasiswa melalui komunikasi rutin dan program sosialisasi yang meningkatkan dukungan keluarga.

## Email dan password Metabase
Email: root@mail.com
Password: root123