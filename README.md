# Model Deteksi Masker

Repository ini berisi model deep learning untuk mendeteksi apakah seseorang mengenakan masker atau tidak. Model ini dilatih menggunakan Convolutional Neural Network (CNN) dan disimpan dalam berbagai format untuk memudahkan penggunaannya di berbagai platform.

## Format Model
Model tersedia dalam format-format berikut:
- **SavedModel**: Format TensorFlow yang dapat digunakan dengan TensorFlow Serving atau alat-alat TensorFlow lainnya.
- **TensorFlow Lite (TFLite)**: Format yang dioptimalkan untuk menjalankan model di perangkat mobile.
- **TensorFlow.js**: Format yang cocok untuk menjalankan model langsung di browser.

## Struktur Folder
- **`tfjs_model/`**: Menyimpan file model yang diperlukan untuk TensorFlow.js.
- **`tflite/`**: Menyimpan file model `.tflite` dan file `label.txt` untuk label kelas.
- **`saved_model/`**: Menyimpan file format SavedModel untuk TensorFlow.
- **`notebook.ipynb`**: Notebook yang digunakan untuk pelatihan, evaluasi, dan konversi model.
- **`README.md`**: File ini, yang berisi informasi mengenai repository.
- **`requirements.txt`**: Daftar pustaka dan library yang digunakan
