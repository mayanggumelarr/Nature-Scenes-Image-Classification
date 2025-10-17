# Nature-Scenes-Image-Classification
This repositori is made to save my project Nature Scenes Image Classification with MobileNetV2 <br>
Projek Submission Image Classification dengan topik klasifikasi citra alam yang diambil oleh satelit <br>
Dataset didapat dari sumber Kaggle.com dengan rincian: <br>

- Label: 6 label natural scene 
- Total: 17034 total gambar (before augmented)
- Resolusi citra yang berbeda-beda
Model dibangun dengan memanfaatkan Transfer Learn MobileNetV2 add layer Sequential, Conv2D, dan Pooling Layer. Selain itu, juga menggunakan Early stop sebagai callback
dan optimizer. <br>

Model disimpan dengan format .keras, .h5, SavedModel, TF-Lite, dan TFJS <br>

Inference model dilakukan dengan metode get dari inputan user. <br>
<br>

**GET DATASET :** <br>
Kamu bisa mendapatkan di URL: `https://www.kaggle.com/datasets/puneet6060/intel-image-classification` <br>

**GET FULL FILE PROJECTS :** <br>
Kamu bisa mengunduh file .zip di drive: `https://drive.google.com/file/d/1IgE7kREgqJu0equL-OXPBCOZa664_k2n/view?usp=drive_link`
