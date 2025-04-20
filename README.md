# DigitalSkillFair38-Data-Science

## Project Data Science

### Titanic Data Investigation

Tragedi Titanic pada tahun 1912 menjadi salah satu bencana maritim paling ikonik sepanjang sejarah, dengan lebih dari 1.500 korban jiwa dari total lebih dari 2.200 penumpang dan awak kapal. Dalam proyek ini, saya menganalisis sebuah dataset kurasi dari [Frank Harrell’s Hmisc Titanic Dataset](https://hbiostat.org/data/repo/titanic.html) untuk menggali pola di balik siapa yang selamat dan siapa yang tidak. Fokus utama adalah *exploratory data analysis* (EDA), data preprocessing, serta eksperimen dengan berbagai algoritma machine learning. Dataset berukuran besar ini dapat diakses di link berikut: [Link dataset Excel](https://hbiostat.org/data/repo/titanic3.xls).

Dataset ini berisi informasi detail mengenai penumpang Titanic: nama, jenis kelamin, usia, dan status keselamatan mereka. Dari 500 baris data dan 4 kolom utama (`name`, `sex`, `age`, `survived`), hanya kolom `age` yang memiliki missing value sebesar 9.82%. Pembersihan data meliputi penghapusan duplikat dan imputasi nilai hilang menggunakan median untuk fitur numerik. Categorical features seperti `sex` diubah menjadi numerik menggunakan *Label Encoding*, dan fitur `AgeGroup` ditambahkan untuk mendukung analisis berbasis kategori umur.

EDA menunjukkan bahwa perempuan dan anak-anak memiliki peluang lebih besar untuk selamat dibanding pria dewasa. Distribusi usia penumpang didominasi oleh kelompok umur 20–40 tahun, dan survival rate lebih tinggi pada anak-anak usia 0–5. Selain itu, analisis terhadap titel sosial menunjukkan bahwa wanita dengan gelar seperti "Countess" dan "Lady" semuanya selamat, sementara pria dengan titel "Mr" memiliki tingkat kematian tertinggi.

---

## Version Libraries (opsional)
- pandas v1.5.3  
- numpy v1.22.4  
- seaborn v0.12.2  
- matplotlib v3.7.1  
- scikit-learn v1.2.2  
- plotly v5.14.1  
- missingno v0.5.2  

---

## Insight
Insight yang saya dapat dari projek ini ialah:
1. Wanita memiliki tingkat keselamatan lebih tinggi karena penerapan kebijakan "Women and Children First".
2. Anak-anak di bawah usia 10 tahun, khususnya balita, memiliki peluang hidup yang sangat tinggi.
3. Pria dewasa (dengan titel "Mr") adalah kelompok yang paling tidak diprioritaskan dalam evakuasi.
4. Faktor sosial seperti gelar kebangsawanan atau status sosial mempengaruhi peluang untuk diselamatkan.
5. Support Vector Machine (SVM) memberikan performa terbaik di antara semua model ML yang diuji, dengan akurasi, precision, recall, dan F1-Score yang tinggi.

---

## Advice
Project ini masih bisa dikembangkan ke ranah yang berkaitan dengan Machine Learning:
1. Pengembangan sistem prediksi risiko individu berbasis fitur demografi seperti umur, gender, dan titel sosial.
2. Simulasi evakuasi menggunakan output model prediktif untuk mengoptimalkan penyelamatan dalam kondisi darurat nyata.
3. Mengintegrasikan fitur tambahan dari sumber data lain seperti informasi kabin, kelas, dan embarkasi untuk meningkatkan akurasi model.

---

If you have any suggestions or feedback, please don't hesitate to contact me via LinkedIn or Email:

📧 salsabila.qonita.kaltsum@gmail.com  
🔗 [LinkedIn – Salsabila Qonita Kaltsum](https://www.linkedin.com/in/salsabilaqonitakaltsum/)  
📂 [GitHub Repository](https://github.com/salsabilaqonita/DigitalSkillFair38-Data-Science)

#DataScience #Python #MachineLearning #Titanic #DataInvestigation
