# Submission 1: Hate Comment Classification
Nama: Rayhan Gibrani uhum

Username dicoding: rayhan gibrani uhum

| | Deskripsi |
| ----------- | ----------- |
| Dataset | [Social Media Hate Commentst](https://www.kaggle.com/datasets/subhajeetdas/hate-comment/data) |
| Masalah | Dengan berkembangnya internet , komunikasi antar manusia menjadi tidak terbatas pada lokasi geografis. Hal ini selaras dengan berkembangnya social media sebagai wadah untuk komunikasi. semua orang memiliki hak yang sama dalam mennyatakan pendapatnya. Hal ini membuat kerap adanya kasus bullying di social media berupa hate comment atau komen kebencian. dengan adanya model machine learning ini di harapakan dapat mngurangi kasus bully online akibat hate comment |
| Solusi machine learning | solusi yang di gunakan adalah menggunakan machine learning yang berfungsi layaknya filter untuk membedakan yang mana hate comment dgn tidak |
| Metode pengolahan | Metode pengolahan data yang digunakan pada proyek ini adalah tokenisasi fitur input, di mana teks pada kolom 'comment' diubah menjadi representasi numerik menggunakan Text Vectorization. Proses ini memungkinkan teks untuk diproses dan dipahami oleh model secara efisien, sehingga model dapat belajar dari fitur yang telah diubah ini |
| Arsitektur model | Model yang dibangun menggunakan layer 'TextVectorization' untuk mengubah input string menjadi representasi angka, diikuti oleh layer 'Embedding' yang mempelajari hubungan atau kemiripan antar kata untuk memahami makna teks. Setelah itu, terdapat 2 hidden layer dengan aktivasi 'ReLU' untuk menangkap pola non-linear dalam data, dan diakhiri dengan 1 output layer dengan aktivasi 'sigmoid' untuk klasifikasi biner |
| Metrik evaluasi | Deksripsi metrik yang digunakan untuk mengevaluasi performa model |
| Performa model | Deksripsi performa model yang dibuat |
