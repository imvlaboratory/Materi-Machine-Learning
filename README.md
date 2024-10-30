<h1 align="center"> Machine Learning </h1>

## A. What is Machine Learning?

<p align="center">
    <img src="https://user-images.githubusercontent.com/72246401/218114835-964ad3c9-72f5-4a3a-8d7c-e6940c9285dd.png" width="360" style="vertical-align:middle">
</p>

1.  Artificial Intelligence

    Dalam istilah sederhana, AI (Artificial Intelligence) ialah sistem atau mesin yang `meniru kecerdasan manusia` untuk melakukan tugas dan secara terus-menerus dapat meningkatkan kemampuannya berdasarkan `informasi yang telah dikumpulkan`. AI telah diwujudkan dalam beberapa bentuk. Beberapa contohnya adalah:
    
    <ol type="a">
    Chatbot, menggunakan AI untuk memahami masalah pelanggan lebih cepat dan memberikan jawaban yang lebih efisien</li>
    <li>Smart Assistant, menggunakan AI untuk mengurai informasi penting dari kumpulan data teks dalam jumlah besar guna mengatur jadwal pengguna secara lebih baik</li>
    <li>Recommendation Engine, menggunakan AI supaya dapat memberikan rekomendasi otomatis untuk acara TV berdasarkan kebiasaan menonton pengguna, atau rekomendasi produk berdasarkan riwayat pembelian di platform ecommerce</li>
    </ol>

    Artificial Intelligence atau AI lebih banyak berkutat dengan proses mesin berpikir dan analisis data. Meskipun AI menampilkan gambar robot mirip manusia yang memiliki kemampuan berpikir cerdas, `AI tidak dimaksudkan untuk menggantikan manusia`.

    Ketika membicarakan AI, kita sebenarnya tidak jauh-jauh dari dua istilah ini yaitu `Machine Learning dan Deep Learning`. Karna keduanya merupakan sub-bidang dari Artificial Intelligence.

2.  Machine Learning

    Machine Learning yaitu istilah untuk menyebut komputer yang belajar dari data. Bidang ini merupakan irisan dari jurusan `ilmu komputer` dan `statistika` di mana algoritma digunakan untuk melakukan tugas tertentu tanpa diprogram secara eksplisit. Sebaliknya, `machine larning mengenali pola dalam data` dan membuat prediksi ketika ada data baru yang tiba.

    Secara umum, proses pembelajaran algoritma ini dapat bersifat `supervised ataupun unsupervised`, tergantung pada data yang digunakan untuk melatih algoritma. Machine Learning menggabungkan `algoritma “klasik”` untuk berbagai macam tugas seperti `pengelompokan (clustering), regresi, atau klasifikasi`. Algoritma Machine Learning harus dilatih pada data dengan memberikan label tertentu. `Semakin banyak data` yang diberikan ke dalam algoritma, maka `hasilnya akan semakin baik`.
    
    <p align="center">
    <img src="https://cdn-images-1.medium.com/max/800/1*rbaxTrB_CZCqbty_zv2bEg.png" width="432" style="vertical-align:middle">
</p>

Secara umum, proses pembelajaran algoritma ini dapat bersifat supervised ataupun unsupervised, tergantung pada data yang digunakan untuk melatih algoritma.

## B. Features and Labels
<p align="center">
    <img src="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEjmOSmpA-HUYZCCXYb2rNnaqpd9XCHzh10_id4wi6zZqYmH9DpkcKqXnjha30vKI5agUgCLPlhYamtfXyrjgdaJOrvrrUPoDMijd_K6n2eUIs16gldq6B6q_sRuEAMVVkF-xF9VK454rx0/s650/model.png" width="800" style="vertical-align:middle">
</p>

Dalam machine learning, ada dua konsep dasar yang membantu membangun model prediksi adalah `fitur` dan `label`. Bayangkan fitur sebagai karakteristik atau sifat dari setiap data. Fitur-fitur ini adalah atribut yang dapat diukur dari setiap item dalam dataset dan memberikan informasi penting yang digunakan model untuk membuat keputusan. Sebagai contoh, jika kita mencoba memprediksi harga rumah, fitur-fitur mungkin mencakup jumlah kamar tidur, luas bangunan, dan lokasi rumah. Setiap fitur ini memberikan informasi yang membantu menjelaskan apa yang membuat setiap rumah unik dan pada akhirnya memengaruhi prediksi model.

Di sisi lain, `label` sering juga disebut sebagai `Class` mewakili hasil atau jawaban yang ingin kita prediksi. Label-label ini memberikan model "jawaban yang benar" selama pelatihan, sehingga model belajar bagaimana fitur-fitur berkorelasi dengan hasil tertentu. Dengan kata lain, label membimbing model untuk memahami apa yang harus diprediksi berdasarkan pola yang ada di fitur-fitur.

Untuk memahami hubungan antara fitur dan label, bayangkan seperti ini: fitur adalah masukan yang mendeskripsikan setiap data atau bisa disebut sebagai `variabel independen`, sedangkan label adalah keluaran atau jawaban yang akan diprediksi oleh model atau bisa juga disebut sebagai `variabel dependen`. Dengan menganalisis `pola atau korelasi` antara `fitur` dan `label`, model dapat belajar membuat prediksi akurat untuk data baru yang belum pernah dilihat sebelumnya. Sebagai contoh, jika Anda memberikan model detail tentang sebuah rumah (`fitur`) tanpa mengungkapkan harganya (`label`), model yang telah terlatih dengan baik harus dapat memprediksi harga rumah tersebut berdasarkan apa yang telah dipelajari. Proses menggunakan `fitur` untuk memprediksi `label` ini, adalah inti dari `supervised machine learning`.

## C. Classification Vs. Regression
<p align="center">
<img src="https://cdn-images-1.medium.com/max/1600/1*xs6Jr4iAPvoqszF9JgDWOA.png" width="800" style="vertical-align:middle">
</p>
Klasifikasi dan regresi adalah dua jenis utama dari tugas pembelajaran mesin yang diawasi, dan masing-masing memiliki tujuan berbeda tergantung pada jenis output yang ingin diprediksi.<br>
Berikut adalah penjelasan masing-masing:<br>
<br>
<h2>Klasifikasi</h2>
Klasifikasi adalah jenis tugas pembelajaran mesin di mana tujuannya adalah memprediksi label diskrit, atau kategori, untuk data yang diberikan. Dalam klasifikasi, data dibagi menjadi kelas-kelas yang terpisah, dan model belajar untuk menempatkan data baru ke salah satu dari kelas-kelas yang sudah ditentukan. Hasilnya bersifat kategorikal, yang berarti jatuh ke dalam kategori tertentu alih-alih menjadi nilai kontinu.<br>
<br>
<ul>
<li>Contoh: Tugas-tugas klasifikasi umum termasuk deteksi spam (mengklasifikasikan email sebagai "spam" atau "bukan spam"), diagnosis penyakit (memprediksi apakah seorang pasien memiliki penyakit atau tidak), dan pengenalan gambar (mengidentifikasi objek seperti "kucing," "anjing," atau "mobil" dalam gambar).</li>
    
<li>Klasifikasi Biner vs Multi-kelas:
Klasifikasi Biner: Hanya ada dua kelas yang mungkin (misalnya, "ya" atau "tidak").
Klasifikasi Multi-kelas: Lebih dari dua kelas, seperti mengkategorikan hewan menjadi "kucing," "anjing," "burung," dan sebagainya.</li>

<li>Algoritma yang Sering Digunakan: Algoritma klasifikasi umum meliputi regresi logistik, k-nearest neighbors (k-NN), support vector machines (SVM), pohon keputusan, random forests, dan jaringan saraf.
</li>
</ul>
<h2>Regresi</h2>
Regresi adalah jenis tugas pembelajaran mesin di mana tujuannya adalah memprediksi nilai kontinu berdasarkan fitur-fitur input. Alih-alih mengelompokkan data ke dalam kelas diskrit, model regresi menghasilkan nilai numerik. Model ini belajar memahami hubungan antara fitur-fitur input dan variabel target, memungkinkan model untuk membuat prediksi yang terletak dalam spektrum kontinu.
<ul><br>
<li>Contoh: Tugas-tugas regresi umum termasuk prediksi harga rumah, peramalan suhu, dan estimasi harga saham.</li>
<li>Regresi Linear vs Non-linear:</li>
<ul>
<li>Regresi Linear: Mengasumsikan hubungan linear antara fitur input dan target, yang berarti prediksi dapat diwakili sebagai garis lurus melalui data.</li>
<li>Regresi Non-linear: Mengizinkan hubungan yang lebih kompleks, di mana prediksi dapat mengikuti kurva atau bentuk lain tergantung pada data.</li>
</ul>
<li>Algoritma yang Sering Digunakan: Algoritma regresi umum meliputi regresi linear, regresi polinomial, pohon keputusan, random forests, dan jaringan saraf.</li>
</ul>
