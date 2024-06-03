```
Judul          : Penerapan Algoritma Decision Tree dalam Prediksi Kelulusan Mahasiswa dengan Data Akademik
Kelompok 9     : - Laela Nur Rohmah      (312110425)
                 - Alvina Damayanti      (312110125)
                 - Sara Khusnul Mumtazah (312110319)
Kelas          : TI.21.A.3
Mata Kuliah    : Data Mining
Dosen Pengampu : Amali M.T., M.Sc
```

## Teori singkat
Data mining adalah proses pengumpulan dan pengolahan data yang bertujuan untuk mengekstrak informasi penting pada data.

Rapidminer adalah salah satu platform yang dapat digunakan untuk melakukan data mining, text mining, dan analisa prediksi 
serta mempermudah melakukan algoritma analisi data tanpa memerlukan pembuatan kode secara manual.

Decision Tree merupakan salah satu metode pengambilan keputusan yang dimana bentuk model yang di tampilkan akan berupa 
seperti struktur pohon yang digunakan untuk menggambarkan dan menganalisa konsekuensi dari berbagai hasil keputusan yang mungkin diambil.

## Penjelasan
Penelitian ini menggunakan Algoritma Decision Tree guna membantu menggambarkan hubungan antara atribut  untuk memudahkan 
dalam membuat keputusan faktor apa saja yang akan mempengaruhi terhadap  kelulusan mahasiswa. Penelitian ini juga menggunakan 
tools RapidMiner guna membantu membuat model dari algoritma Decision Tree. Tahapan yang dilakukan ialah pengumpulan data, pengelolaan data, 
pemodelan Decision Tree, pengujian algoritma/metode, dan evaluasi hasil. Pengelolaan data pada dataset akan dibagi menjadi data training 70% dan 
data testing 30%. Hasil penelitian dengan Algoritma Decision Tree dikatakan memiliki memiliki kinerja yang baik dengan tingkat accuracy sebesar 73.17%, 
hasil prediksi kelulusan mahasiswa dikatakan cukup baik dengan tingkat precision sebesar 74.05% dan tingkat recall sebesar 93.82%, 
hasil prediksi kegagalan (DropOut) mahasiswa dikatakan cukup baik dengan tingkat precision sebesar 73.02% dan tingkat recall sebesar 80.05%, 
dan didapatkan faktor-faktor yang dapat mempengaruhi kelulusan mahasiswa yaitu course  dan previous qualification.

## Desain RapidMiner
![Desain Rapidminer](https://github.com/laelanur21/Prediksi_Kelulusan_Mahasiswa_dengan_Decision_Tree/assets/96130416/2507df2e-f1bd-41fa-86eb-230a2d08a1b0)

note :
- read csv : untuk membaca dataset yang digunakan
- set role : membedakan baris penamaan atribut koordinat dan prediksi posisi yang akan di masukan kedalam kategori 'label'
- filter examples : melakukan penyortiran data, disini dipilih 'no_missing_attribute'
- split data : membagi dataset menjadi 2 yaitu data training 70%, data testing 30%
- apply model :  menerapkan model yang telah dilatih sebelumnya menggunakan data training pada data testing
- performance : mengevaluasi kinerja model yang memberikan daftar nilai kriteria kinerja secara otomatis sesuai dengan tugas yang diberikan

## Graphic Decision Tree
![graphic decision tree](https://github.com/laelanur21/Prediksi_Kelulusan_Mahasiswa_dengan_Decision_Tree/assets/96130416/2ed06cd0-820d-4f57-9c3f-c125fe756228)

## Description Decision Tree
![description decision tree](https://github.com/laelanur21/Prediksi_Kelulusan_Mahasiswa_dengan_Decision_Tree/assets/96130416/d756032f-523b-43eb-a5fd-0ddb72882ebb)

## Attribute Weights (Decision Tree)
![attribute weight](https://github.com/laelanur21/Prediksi_Kelulusan_Mahasiswa_dengan_Decision_Tree/assets/96130416/b727d6c3-230f-4d45-8b02-37f2b1234e8b)

## Accuracy
![accuracy](https://github.com/laelanur21/Prediksi_Kelulusan_Mahasiswa_dengan_Decision_Tree/assets/96130416/5a2f1abb-4049-4587-82fb-d5e73300a255)

## Performance Vector
![performance vector](https://github.com/laelanur21/Prediksi_Kelulusan_Mahasiswa_dengan_Decision_Tree/assets/96130416/5fdcd7a0-e108-4b3c-8d3f-b70128abc770)

## Visualization
![visualizations prediction target](https://github.com/laelanur21/Prediksi_Kelulusan_Mahasiswa_dengan_Decision_Tree/assets/96130416/ab13076a-e627-4c96-9bf6-d4c69a75ede8)
