# Eduwash
---
+ [Gambar Dataset](https://github.com/rahmipea/hand-wash-edu/blob/main/README.md#gambar-dataset) 
+ [Dataset](https://github.com/rahmipea/hand-wash-edu/blob/main/README.md#dataset)
+ [Data test](https://github.com/rahmipea/hand-wash-edu/blob/main/README.md#data-test)

---
This repository contains documentation of our Capstone Project Bangkit 2021. Our project called Eduwash, which is an android application. We build this app in terms to educate children to washing hand correctly based on WHO standard. Our app is containing two features, excercise and practice. In the exercise feature there is a gif along with a handwash motion guideline that shows the correct hand washing steps from steps 1 until 7. Meanwhile, in practice feature the app will be asses the user's handwashing movement whether correct or not. The mechanism is the app will be activate mobile camera and utilize it as input that will be feeded to machine learning. Thus, our machine learning model will be classify the handwash motions. 
 
We were using video contains WHO recomendation handwash movements as our dataset.  

## Dataset Picture
![Sample-HandWashDataset](https://user-images.githubusercontent.com/66559322/120105814-c03d0380-c184-11eb-8d80-eaf7f0074c04.png)
This is an example of dataset that we were utilize as our training model. Each frame on video were extracted into numpy array and labeled, then training process obtained.  

## Dataset
Dataset source [Handwash Dataset](https://www.kaggle.com/realtimear/hand-wash-dataset) <br>
Extracted dataset [Features Extraction](https://drive.google.com/file/d/1emgnWE6IROcyji5VjkMGgK7oh8l6w2cs/view?usp=sharing) <br>
Label [Labels Extraction](https://drive.google.com/file/d/1Oam4rmRaIoWIImoK4y6zfNB0sbbgWKBN/view?usp=sharing) <br>

## Data test
Example video to asses model [Data Test](https://drive.google.com/drive/folders/1IfogNspR7Iz3sOIP67Acst3D5PA7k_nz?usp=sharing) <br>
Result of test model using data/video test [Hasil Predict](https://drive.google.com/drive/folders/13BanwmlDZBBc9TsLwTT8jxaQ8hETZDXJ?usp=sharing)

---
## Eduwash

Repo ini berisikan Capstone Project Bangkit 2021 yakni tentang Hand wash edu berupa Aplikasi Android.
Hand wash edu, merupakan aplikasi android yang digunakan untuk mengedukasi anak-anak dalam mencuci tangan secara benar menurut standar WHO dengan cara memberikan informasi dan fakta menarik tentang mencuci tangan. Selain itu dalam aplikasi ini juga terdapat exercise untuk mendeteksi apakah mereka telah mempraktikan nya dengan benar atau tidak. Dengan cara aplikasi akan mendeteksi gerakan tangan mereka melalui kamera hp, lalu oleh Machine Learning akan dideteksi termasuk langkah-langkah yang dianjurkan ataukan tidak. 

Dataset yang digunakan dalam pelatihan Machine Learning tersebut berupa video dari masing masing langkah yang mempresentasikan langkah yang benar dan dianjurkan oleh WHO.

## Gambar Dataset
![Sample-HandWashDataset](https://user-images.githubusercontent.com/66559322/120105814-c03d0380-c184-11eb-8d80-eaf7f0074c04.png)
Berikut adalah contoh dataset yang digunakan untuk melakukan training model, setiap frame pada video tersebut di ekstrak kedalam numpy array dan diberikan label. Setelah itu dilakukan training. 

## Dataset
Dataset yang digunakan [Handwash Dataset](https://www.kaggle.com/realtimear/hand-wash-dataset) <br>
Dataset yang sudah di lakukan ekstraksi [Features Extraction](https://drive.google.com/file/d/1emgnWE6IROcyji5VjkMGgK7oh8l6w2cs/view?usp=sharing) <br>
Label [Labels Extraction](https://drive.google.com/file/d/1Oam4rmRaIoWIImoK4y6zfNB0sbbgWKBN/view?usp=sharing) <br>

## Data test
Video example yang digunakan untuk menguji model [Data Test](https://drive.google.com/drive/folders/1IfogNspR7Iz3sOIP67Acst3D5PA7k_nz?usp=sharing) <br>
Hasil uji model menggunakan data/video test [Hasil Predict](https://drive.google.com/drive/folders/13BanwmlDZBBc9TsLwTT8jxaQ8hETZDXJ?usp=sharing)
