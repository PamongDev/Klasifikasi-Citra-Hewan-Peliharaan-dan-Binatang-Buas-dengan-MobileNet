# Proyek Klasifikasi Citra

## Deskripsi
Proyek ini adalah sebuah klasifikasi citra untuk mengidentifikasi hewan berdasarkan dataset **Animal Faces** dari Kaggle. Proyek ini mengklasifikasikan gambar menjadi tiga kelas: **Cat, Dog, dan Wild**. Model dilatih menggunakan teknik *data augmentation* untuk memperbaiki performa pada kelas **Cat** dan **Wild** yang lebih sedikit jumlahnya.

## Informasi Kontak
- **Nama**: Muhamad Fahmi Ammar
- **Email**: muh.fahmi.2001@gmail.com
- **ID Dicoding**: pamong_ammar

## Dataset
Dataset yang digunakan adalah [Animal Faces](https://www.kaggle.com/datasets/andrewmvd/animal-faces) dari Kaggle dengan tiga kelas utama:
- **Cat**
- **Dog**
- **Wild**

### Splitting Dataset
- **Train**: 80%
- **Test**: 20%

### Data Preprocessing
- **Data Augmentation** diterapkan pada kelas **Cat** dan **Wild** untuk menyeimbangkan jumlah data di setiap kelas.

## Model dan Performanya
Model dilatih menggunakan dataset yang telah di-*split* dan dilakukan augmentasi. Hasil dari model ini diuji pada data test set dan mendapatkan hasil yang sangat baik, dengan metrik sebagai berikut:

### Hasil Evaluasi

| **Class** | **Precision** | **Recall** | **F1-Score** | **Support** |
|-----------|---------------|------------|--------------|-------------|
| **Cat**   | 0.99          | 0.98       | 0.99         | 1157        |
| **Dog**   | 0.97          | 0.98       | 0.97         | 1102        |
| **Wild**  | 0.97          | 0.97       | 0.97         | 1087        |

### Overall Metrics
- **Accuracy**: 0.98
- **Macro Average**:
  - **Precision**: 0.98
  - **Recall**: 0.98
  - **F1-Score**: 0.98
- **Weighted Average**:
  - **Precision**: 0.98
  - **Recall**: 0.98
  - **F1-Score**: 0.98

## Kesimpulan
Model klasifikasi citra ini memberikan hasil yang sangat baik dengan akurasi sebesar **98%**. Teknik data augmentation pada kelas yang kurang seimbang terbukti efektif dalam meningkatkan performa model. 
