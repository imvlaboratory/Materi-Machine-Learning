<h1 align="center">Study Group Day 3 : Machine Learning </h1>

## A. What is Machine Learning?

<p align="center">
    <img src="https://user-images.githubusercontent.com/72246401/218114835-964ad3c9-72f5-4a3a-8d7c-e6940c9285dd.png" width="360" style="vertical-align:middle">
</p>

1.  Artificial Intelligence

    Dalam istilah sederhana, AI (Artificial Intelligence) ialah sistem atau mesin yang `meniru kecerdasan manusia` untuk melakukan tugas dan secara terus-menerus dapat meningkatkan kemampuannya berdasarkan `informasi yang telah dikumpulkan`. AI telah diwujudkan dalam beberapa bentuk. Beberapa contohnya adalah:
    
    <ol type="a">
    <li>Chatbot, menggunakan AI untuk memahami masalah pelanggan lebih cepat dan memberikan jawaban yang lebih efisien</li>
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
Klasifikasi dan regresi adalah dua jenis utama dari tugas supervised machine learning, dan masing-masing memiliki tujuan berbeda tergantung pada jenis output yang ingin diprediksi.<br>
Berikut adalah penjelasan masing-masing:<br>
<h3>Klasifikasi</h3>
Klasifikasi adalah jenis tugas pembelajaran mesin di mana tujuannya adalah memprediksi label diskrit, atau kategori. Dalam klasifikasi, data dibagi menjadi kelas-kelas yang terpisah, dan model belajar untuk menempatkan data baru ke salah satu dari kelas-kelas yang sudah ditentukan.<br>
<br>
<ul>
<li>Contoh: Tugas-tugas klasifikasi umum termasuk deteksi spam (mengklasifikasikan email sebagai "spam" atau "bukan spam"), diagnosis penyakit (memprediksi apakah seorang pasien memiliki penyakit atau tidak), dan pengenalan gambar (mengidentifikasi objek seperti "kucing," "anjing," atau "mobil" dalam gambar).</li>
    
<li>Klasifikasi Biner vs Multi-kelas:
Klasifikasi Biner: Hanya ada dua kelas yang mungkin (misalnya, "ya" atau "tidak").
Klasifikasi Multi-kelas: Lebih dari dua kelas, seperti mengkategorikan hewan menjadi "kucing," "anjing," "burung," dan sebagainya.</li>

<li>Algoritma yang Sering Digunakan: Algoritma klasifikasi umum meliputi regresi logistik, k-nearest neighbors (k-NN), support vector machines (SVM), pohon keputusan, random forests, dan jaringan saraf.
</li>
</ul>
<h3>Regresi</h3>
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

## D. Machine Learning Workflow
<p align="center">
<img src="https://miro.medium.com/v2/resize:fit:1200/1*XgcF3ayEH2Q8JEbZx8D09Q.png" width="800" style="vertical-align:middle">
</p>
Alur kerja (workflow) pembelajaran mesin adalah pendekatan terstruktur untuk membangun dan menerapkan model pembelajaran mesin, mulai dari persiapan data hingga evaluasi dan penerapan model akhir. Berikut adalah langkah-langkah umum dalam alur kerja pembelajaran mesin:
<ol>
<li>Definisi Masalah
Tujuan: Mendefinisikan masalah yang ingin diselesaikan dengan jelas. Ini melibatkan pemahaman terhadap tujuan bisnis atau penelitian dan menentukan apakah model pembelajaran mesin cocok untuk menyelesaikan masalah tersebut.
<br>Contoh: Memprediksi churn pelanggan, mengklasifikasikan email sebagai spam, atau meramalkan harga saham.
</li>
<li>Pengumpulan Data
Tujuan: Mengumpulkan semua data yang relevan yang diperlukan untuk melatih model. Data ini dapat berasal dari berbagai sumber, seperti database, API, sensor, atau web scraping.
<br>Contoh: Mengumpulkan data pelanggan untuk model prediksi churn, termasuk informasi demografis dan riwayat pembelian.
</li>
<li>Praproses Data
Tujuan: Menyiapkan data untuk pemodelan dengan membersihkan dan mentransformasikannya. Ini dapat melibatkan penanganan nilai yang hilang, menghapus duplikat, penskalaan fitur, mengonversi data kategori, dan membagi data menjadi set pelatihan, validasi, dan pengujian.
<br>Contoh: Mengisi nilai usia yang hilang dengan median, menormalkan fitur pendapatan, dan mengonversi label kategori menjadi format numerik.
</li>
<li>Analisis Data Eksploratif (EDA)
Tujuan: Memahami data lebih baik melalui visualisasi dan analisis statistik. EDA membantu mengidentifikasi pola, korelasi, dan potensi masalah dalam data.
<br>Contoh: Membuat histogram, plot pencar, atau matriks korelasi untuk melihat hubungan antar variabel.
</li>
<li>Rekayasa Fitur
Tujuan: Menciptakan dan mentransformasikan fitur untuk meningkatkan kinerja model. Ini dapat melibatkan pemilihan fitur yang relevan, menciptakan fitur baru, atau mengurangi jumlah fitur dengan teknik seperti Analisis Komponen Utama (PCA).
<br>Contoh: Mengonversi tanggal menjadi hari atau bulan, membuat fitur interaksi, atau menggunakan PCA untuk mengurangi dimensi.
</li>
<li>Pemilihan Model
Tujuan: Memilih algoritma yang sesuai berdasarkan jenis masalah, seperti klasifikasi, regresi, klasterisasi, atau rekomendasi. Anda mungkin juga mencoba beberapa algoritma untuk menemukan yang terbaik.
<br>Contoh: Mencoba algoritma seperti regresi logistik, pohon keputusan, dan random forest untuk tugas klasifikasi.
</li>
<li>Pelatihan Model
Tujuan: Melatih model yang dipilih pada data pelatihan. Selama pelatihan, model mempelajari hubungan dalam data dengan menyesuaikan parameternya.
<br>Contoh: Melatih jaringan saraf pada gambar berlabel untuk mengklasifikasikan objek.
</li>
<li>Evaluasi Model
Tujuan: Menilai kinerja model pada data validasi atau pengujian untuk melihat seberapa baik model mampu menggeneralisasi ke data baru. Metrik yang digunakan bergantung pada jenis masalah, seperti akurasi untuk klasifikasi atau mean squared error untuk regresi.
<br>Contoh: Mengevaluasi model deteksi spam menggunakan metrik seperti presisi, recall, dan skor F1.
</li>
<li>Tuning Hyperparameter
Tujuan: Meningkatkan kinerja model dengan mengoptimalkan hyperparameter, yang merupakan pengaturan model yang tidak dipelajari dari data. Teknik seperti pencarian grid (grid search) dan pencarian acak (random search) sering digunakan.
<br>Contoh: Mengatur jumlah pohon dalam model random forest atau tingkat pembelajaran pada jaringan saraf.
</li>
<li>Penerapan Model
Tujuan: Membuat model yang telah dilatih tersedia untuk digunakan di lingkungan produksi, sehingga dapat mulai membuat prediksi pada data dunia nyata. Ini bisa berupa membuat API, menyematkan model ke aplikasi perangkat lunak, atau menerapkannya di layanan cloud.
<br>Contoh: Menerapkan sistem rekomendasi pada situs e-commerce untuk merekomendasikan produk kepada pengguna secara real-time.
</li>
<li>Pemantauan dan Pemeliharaan
Tujuan: Memantau kinerja model yang telah diterapkan seiring waktu untuk memastikan model tetap akurat dan relevan. Ini melibatkan pelacakan model drift, melatih ulang dengan data baru jika diperlukan, dan memperbarui model sesuai kebutuhan.
<br>Contoh: Memantau model prediksi pemeliharaan untuk mesin industri dan melatih ulang model secara berkala saat data baru tersedia.
</li>
</ol>

## E. Performance Metrics
<p align="center">
<img src="https://media.licdn.com/dms/image/v2/C5112AQGM7rWklfggow/article-cover_image-shrink_600_2000/article-cover_image-shrink_600_2000/0/1578311015279?e=2147483647&v=beta&t=1akmPtn_45gpDcBLAwNKyAjSWfGJdQX8Z4npNBoym_I" width="800" style="vertical-align:middle">
<br>TP = True Positive; TN = True Negative; FP = False Positive; FN = False Negative;
</p>
Performance metrics adalah ukuran yang digunakan untuk mengevaluasi kinerja model pembelajaran mesin. Berikut adalah beberapa metrik umum beserta penjelasannya secara singkat:
<ul>
<li>Akurasi
    
Mengukur persentase prediksi benar dari total prediksi. Cocok untuk data seimbang (jumlah kelas relatif sama), tapi kurang informatif untuk data tidak seimbang.
</li>
<li>Presisi (Precision)

Mengukur seberapa banyak prediksi positif benar dibandingkan semua prediksi positif. Berguna untuk menghindari banyaknya false positives.
</li> 
<li>Recall (Sensitivitas)
    
Mengukur seberapa banyak dari total sampel positif yang berhasil diprediksi dengan benar. Berguna untuk mengurangi jumlah false negatives.
​</li>
<li>F1-Score
    
Kombinasi dari presisi dan recall yang memberikan keseimbangan antara keduanya, khususnya jika kedua metrik sama pentingnya.
</li>
</ul>

## Bonus. Hyperparameter Optimization via Grid Search Method
Grid search adalah metode pencarian hyperparameter yang umum digunakan dalam pembelajaran mesin untuk menemukan kombinasi parameter terbaik bagi model. Hyperparameter adalah parameter yang nilainya tidak dipelajari dari data, melainkan diatur sebelum pelatihan model dimulai. Contoh hyperparameter termasuk jumlah pohon dalam model random forest atau tingkat pembelajaran dalam model jaringan saraf.

Grid search bekerja dengan mencoba semua kombinasi yang mungkin dari nilai-nilai hyperparameter yang sudah ditentukan dalam rentang atau "grid" tertentu. Tujuan dari metode ini adalah untuk menemukan kombinasi hyperparameter yang memberikan kinerja terbaik berdasarkan metrik evaluasi yang dipilih (seperti akurasi, presisi, atau mean squared error) pada data validasi.

Langkah-langkah Grid Search
Berikut adalah cara kerja grid search secara umum:

Tentukan Rentang Hyperparameter: Tentukan hyperparameter yang ingin disesuaikan serta nilai-nilai yang ingin diuji. Misalnya, untuk model SVM, kita dapat mencoba berbagai nilai untuk parameter C dan gamma.

Misalnya:

C: [0.1, 1, 10, 100]
gamma: [0.001, 0.01, 0.1, 1]
Bentuk Kombinasi: Buat semua kombinasi yang mungkin dari nilai-nilai hyperparameter yang telah ditentukan. Dengan contoh di atas, grid search akan mencoba setiap pasangan dari nilai C dan gamma, yang menghasilkan 16 kombinasi.

Latih dan Evaluasi Model: Untuk setiap kombinasi, latih model menggunakan data pelatihan, kemudian evaluasi kinerjanya menggunakan data validasi atau pengujian.

Pilih Kombinasi Terbaik: Setelah menguji semua kombinasi, pilih kombinasi hyperparameter yang menghasilkan kinerja terbaik sesuai metrik yang diinginkan.

Kelebihan dan Kekurangan Grid Search
Kelebihan:

Mudah dan Komprehensif: Grid search mencoba semua kombinasi yang memungkinkan, sehingga dapat menemukan kombinasi hyperparameter optimal untuk ruang pencarian yang kecil.
Implementasi Mudah: Grid search mudah diterapkan dengan bantuan pustaka seperti Scikit-Learn di Python.
Kekurangan:

Biaya Komputasi Tinggi: Jika ruang pencarian besar (terdapat banyak hyperparameter atau nilai yang diuji), grid search bisa sangat lambat dan mahal secara komputasi.
Kurang Efisien untuk Pencarian Luas: Grid search tidak mempertimbangkan nilai hyperparameter yang diujinya, sehingga mencoba semua kombinasi bahkan jika beberapa nilai tidak relevan.
