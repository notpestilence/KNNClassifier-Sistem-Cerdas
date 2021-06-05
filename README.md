# K-Nearest Neighbors Classifier 
## Pengantar Sistem Cerdas
Tugas Classifier Pengantar Sistem Cerdas, Departemen Teknik Informatika ITS Surabaya

Anggota kelompok:
1. Charis Chrisna (04311840000006)
2. Farhan Triofani (02411840000141)

Dikerjakan untuk memenuhi tugas minggu ke-12 semester genap 2020/2021, mata kuliah Pengantar Sistem Cerdas, Departemen Teknik Informatika ITS Surabaya. Mata kuliah ini diampu oleh ibu Dini Adni Navastara, S.Kom., M.Sc.

Pada pengerjaan ini, digunakan algoritma K-Nearest Neighbors untuk melatih model agar dapat mengklasifikasikan segmentasi pelanggan atau *customer segmentation* sebuah perusahaan mobil.
Data sebagai basis pengerjaan diambil dari [laman Kaggle berikut](https://www.kaggle.com/kaushiksuresh147/customer-segmentation).

Performa *classifier* yang belum sepenuhnya akurat, dapat diperkirakan muncul dari beberapa faktor, yakni:
1. Penggunaan `euclidean` sebagai pengukuran jarak utama antar *datapoint*. Implementasi umumnya menggunakan `minkowski`;
2. Tidak melaksanakan *hyperparameter tuning* melalui `GridSearchCV` dalam rangka mencari kombinasi parameter yang pas untuk `KNeighborsClassifier()` sebelum proses *learning*.

---

### Catatan kaki:
Mohon maaf sebelumnya ibu Dini, untuk dokumentasi *code* dan penulisan narasi *markdown* kami menggunakan bahasa Inggris, karena belum terbiasa mendokumentasikan kode dalam bahasa Indonesia.
