# ml-Iris
## Background problem
Proyek ini bertujuan untuk membangun model machine learning guna mengklasifikasikan jenis bunga Iris berdasarkan fitur-fitur yang tersedia dalam Iris Dataset dari Scikit-Learn.
Dataset ini terdiri dari tiga kelas bunga Iris:
1. Setosa
2. Versicolor
3. Virginica
Dua algoritma yang dibandingkan dalam proyek ini adalah:
1. Naïve Bayes – Model probabilistik yang cepat dan efisien dalam klasifikasi.
2. Random Forest – Model berbasis ensemble yang kuat dalam menangani data kompleks.
Tujuan utama dari proyek ini adalah membandingkan performa kedua algoritma dalam mengklasifikasikan spesies bunga Iris.

## Version Libraries
1. pandas v1
2. numpy v2
3. seaborn v3
4. scikit-learn vX.X.X
   
## Insight
Dari hasil eksperimen menggunakan Naïve Bayes dan Random Forest, diperoleh beberapa insight:
1. Akurasi kedua model hampir sama, menunjukkan bahwa dataset Iris cukup sederhana untuk diklasifikasikan.
2. Naïve Bayes memiliki keunggulan dalam kecepatan training dan prediksi.
3. Random Forest lebih fleksibel dan dapat menangani dataset yang lebih kompleks, meskipun pada dataset Iris keunggulannya tidak terlalu terlihat.
4. Jika dataset lebih kompleks dengan banyak fitur yang saling berkorelasi, Random Forest kemungkinan akan lebih unggul.

## Advice 
Proyek ini dapat dikembangkan lebih lanjut dengan beberapa saran berikut:
1. Menggunakan cross-validation untuk mengukur stabilitas model.
2. Menambahkan PCA atau teknik feature selection untuk melihat pengaruh reduksi dimensi terhadap performa model.
3. Menggunakan dataset yang lebih kompleks untuk melihat perbedaan performa yang lebih signifikan antara kedua model.
