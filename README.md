# Klasifikasi-DecisionTree-di-dataset-wine
Klasifikasi decision tree dengan dataset wine menggunakan Google colab dan mengimport beberapa library python seperti matplotlib, pandas dan sklearn.
# Menggunakan pandas untuk membuka dataset
untuk memproses dataset kita bisa mengimport library pandas dan membuat variable path untuk membaca file dataset yang kita inginkan. dengan mengubah direktori dari file tempat dataset berada seperti : "/content/drive/MyDrive/Dataset/namadataset" bisa diubah sesuai dengan direktori yang kalian tempatkan file tersebut
# Memisahkan data menjadi x dan y
kita bisa memisahkan dataset menjadi x dan y dengan menggunakan library "from sklearn.model_selection import train_test_split" untuk training dan testing dataset untuk model pembelajaran mesin
# Menggunakan confusion matrix untuk menghitung keakuratan data
untuk menggunakan confusion matrix bisa dengan menggunakan library sklearn "from sklearn.metrics import confusion_matrix"
# Menghitung akurasi kinerja model pada data train dan testing
kita bisa menggunakan rumus Akurasi = Total Jumlah Prediksi / Jumlah Prediksi Benar untuk menghitung akurasi dari model yang kita latih
# Visualisasi Data
untuk memvisualisasikan data yang telah kita latih tadi bisa menggunakan library matplotlib "import matplotlib.pyplot as plt" agar kita bisa melihat decision tree nya
