\# Perbandingan CNN From Scratch dan Transfer Learning MobileNetV2 pada Dataset Cats vs Dogs



\## Identitas Mahasiswa



\- Nama : Zahra Arayanindra Arum Samudra

\- NIM : 452024618068

\- Program Studi : Teknik Informatika



\---



\## Deskripsi Proyek



Proyek ini bertujuan untuk membandingkan performa metode Convolutional Neural Network (CNN) From Scratch dengan Transfer Learning menggunakan arsitektur MobileNetV2 pada tugas klasifikasi citra kucing dan anjing (Cats vs Dogs).



Eksperimen dilakukan menggunakan Google Colab dengan framework TensorFlow dan Keras. Evaluasi model dilakukan menggunakan metrik Accuracy, Loss, serta Confusion Matrix.



\---



\## Dataset



Dataset yang digunakan adalah \*\*Cats vs Dogs Dataset\*\* yang diperoleh dari Kaggle.



Link Dataset:

https://www.kaggle.com/datasets/tongpython/cat-and-dog



Dataset terdiri dari dua kelas:



\- Cat (Kucing)

\- Dog (Anjing)



\---



\## Tahapan Penelitian



1\. Pengumpulan Dataset

2\. Preprocessing Data

&#x20;  - Resize Image (224x224)

&#x20;  - Normalisasi Data

&#x20;  - Data Augmentation

3\. Implementasi CNN From Scratch

4\. Implementasi Transfer Learning MobileNetV2

5\. Training Model

6\. Evaluasi Model

7\. Analisis Hasil



\---



\## Hasil Eksperimen



| Model | Accuracy | Loss |

|---------|---------|---------|

| CNN From Scratch | 75.60% | 0.9814 |

| Transfer Learning MobileNetV2 | 98.67% | 0.0424 |



\---



\## Confusion Matrix



\### CNN From Scratch



| Actual | Prediksi 0 | Prediksi 1 |

|----------|----------|----------|

| 0 | 792 | 208 |

| 1 | 280 | 720 |



\### Transfer Learning MobileNetV2



| Actual | Prediksi 0 | Prediksi 1 |

|----------|----------|----------|

| 0 | 998 | 13 |

| 1 | 18 | 994 |



\---



\## Kesimpulan



Berdasarkan hasil eksperimen, Transfer Learning menggunakan MobileNetV2 memberikan performa yang lebih baik dibandingkan CNN From Scratch. MobileNetV2 memperoleh akurasi sebesar 98.67% dengan nilai loss 0.0424, sedangkan CNN From Scratch memperoleh akurasi sebesar 75.60% dengan nilai loss 0.9814.



Hasil tersebut menunjukkan bahwa Transfer Learning lebih efektif untuk klasifikasi citra pada dataset Cats vs Dogs karena mampu memanfaatkan pengetahuan yang telah dipelajari dari dataset ImageNet.



\---



\## Tools dan Library



\- Python

\- Google Colab

\- TensorFlow

\- Keras

\- NumPy

\- Matplotlib

\- Seaborn

\- Scikit-Learn



\---



\## File Repository



```text

├── CNN\_vs\_TransferLearning.ipynb

├── Laporan.pdf

├── README.md

```



\---



\## Mata Kuliah



Pembelajaran Mesin 2



Universitas Darussalam Gontor



Tahun Akademik 2025/2026

