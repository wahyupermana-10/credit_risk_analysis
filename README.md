# Hacktiv8 Talent Fair Vol. 7 Challenge

## _Projek ini dibuat dengan maksud untuk mengikuti kegiatan Talent Fair Vol. 7 oleh Hactiv8 sebagai tahap akhir untuk lulus dari Hactiv8._

Nama : Risqi Wahyu Permana<br>
Batch :HCK 6

---

# Credit Risk Analysis

Projek ini akan membahas mengenai faktor - faktor penyebab seorang nasabah memiliki status peminjaman yang tidak berisiko dan tidak berisiko. Dalam projek ini juga akan dibuat sebuah model machine learning untuk memprediksi nasabah memiliki status yang beresiko dan tidak beresiko berdasarkan data historisnya.

---

# Kesimpulan

Kesimpulan pada sisi bisnis:

- Bisa lebih diperhatikan lebih lanjut kategori - kategori yang mengindikasikan seorang nasabah memiliki resiko credit risk tinggi. Agar dapat menentukan langkah yang tepat untuk meminimalkan resiko.
- Personalisasi penawaran pinjaman atau pengembangan produk khusus kepada nasabah. Karena pada data yang kita dapatkan terdapat misalnya profesi tertentu yang banyak melakukan pinjaman. Kita bisa personalisasi atau mengembangkan produk khusus untuk menarik minat nasabah baru atau membuat pinjaman dari nasabah berprofesi lain yang masih rendah bisa meningkat.

Kesimpulan pada model:

- Metrik yang digunakan adalah roc_auc karena bisa digunakan untuk data yang inbalance
- Model mengalami overfit.
- Model kurang bagus dalam memprediksi nasabah yang memiliki kredit beresiko tinggi. Hal ini disebabkan oleh data yang tidak seimbang antara data target.

Saran untuk perbaikan model:

- Bisa mencoba menggunakan model machine learning lain yang lebih tahan dengan data inbalance seperti Gradient Boosting, SVM, AdaBoost.
- Karena jumlah data yang banyak, bisa mempertimbangkan menggunakan deep learning. Selain itu, deep learning bisa menggunakan bobot untuk membantu dalam situasi data yang inbalance.
- Menggunakan Regularisasi untuk mengurangi overfitting.
