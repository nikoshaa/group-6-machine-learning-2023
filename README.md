# Quiz 1 - Machine Learning Course

![screen](screen.png)

## Group 6

- [Wildan Hafidz Mauludin](https://github.com/nikoshaa)
- [Dhayu Intan Nareswari](https://github.com/DhayuIntan)
- [Farhan Dwi Pramana](https://github.com/FarhanDwiPramana)
- [Mochammad Zaky Zamroni](https://github.com/zakyzuf)
- [Ziedny Bisma Mubarok](https://github.com/Ziedny28)

## Kasus - Klasifikasi Tulisan Tangan dengan Dataset MNIST

## Overview

Anda diminta untuk melakukan klasifikasi dengan menggunakan algoritma Naive Bayes dan SVM untuk merekognisi tulisan tangan dari dataset MNIST.

## About Dataset MNIST

Dataset MNIST (Modified National Institute of Standards and Technology) merupakan dataset berupa citra grayscale dengan ukuran 28x28 yang berisi tulisan tangan dari digit angka 0-9. Jumlah data dalam dataset ini adalah 70.000 data.

## Kesimpulan dari Berbagai Metode dan Hasil yang didapat

### 1. SVM

SVM (Support Vector Machine) adalah salah satu metode klasifikasi yang paling populer dan kuat. SVM adalah metode klasifikasi biner, yang mengklasifikasikan data menjadi dua bagian.

#### 1.1 SVM RBF Kernel Hyperparameter Tuning

Dalam file [ini](./Kuis_1_SVM_RBF_Kernel.ipynb) kami melakukan percobaan dengan menggunakan SVM dengan kernel RBF, dengan berbagai nilai test size, dan dengan hyperparameter tuning. Berikut adalah hasilnya :

| Test Size | Accuracy |
| --------- | -------- |
| 0,3       | 98,54%   |
| 0,2       | 98,58%   |
| 0,1       | 98.64%   |

#### 1.2 SVM Linear Kernel Non Hyper Parameter Tunning

Dalam file [ini](./Kuis_1_SVM Linear.ipynb), dilakukan percobaan menggunakan metode linear regression, PCA juga digunakan disini, berikut adalah hasilnya

| Test Size | Accuracy |
| --------- | -------- |
| 0,3       | 83,81%   |
| 0,2       | 84,55%   |
| 0,1       | 83,77%   |

### 2. Naive Bayes

Naive Bayes adalah sebuah algoritma klasifikasi yang didasarkan pada Teorema Bayes dengan asumsi bahwa fitur-fitur yang digunakan dalam klasifikasi adalah saling independen dan memiliki pengaruh yang sama terhadap kelas yang diinginkan.

#### 2.1 Gaussian Naive Bayes dengan PCA

Dalam file [ini](./Kuis_1_PCA_Gaussian_Naive_Bayes.ipynb) kami melakukan percobaan dengan menggunakan Gaussian Naive Bayes dengan PCA untuk feature reduction, dengan berbagai nilai test size. Berikut adalah hasilnya :

| Test Size | Accuracy |
| --------- | -------- |
| 0,3       | 87,01%   |
| 0,2       | 87,17%   |
| 0,1       | 86,81%   |

#### 2.2 Multinomial Naive Bayes dengan PCA

Dalam file [ini](./Kuis_1_Naive_Bayes_Multinomial.ipynb) kami melakukan percobaan dengan menggunakan Multinomial Naive Bayes dengan PCA untuk feature reduction, dengan berbagai nilai test size. Berikut adalah hasilnya :

| Test Size | Accuracy |
| --------- | -------- |
| 0,3       | 90,34%   |
| 0,2       | 90,42%   |
| 0,1       | 90,37%   |

#### 2.3 Gaussian Naive Bayes dengan Histogram

Dalam file [ini](<./Kuis1_Gaussian_Naive_Bayes_(Histogram).ipynb>), dilakukan percobaan menggunakan metode Gaussian Naive Bayes, Histogram juga digunakan disini, berikut adalah hasilnya

| Test Size | Accuracy |
| --------- | -------- |
| 0,3       | 56,38%   |
| 0,2       | 56,25%   |
| 0,1       | 56,25%   |

## License

MIT License
