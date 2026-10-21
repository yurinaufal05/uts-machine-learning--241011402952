# UTS Machine Learning — Linear Regression & Logistic Regression

## Identitas Mahasiswa

- **Nama:** Yuri Naufal Akhdan
- **NIM:** 241011402952
- **Kelas:** Reguler B (Reg B)
- **Mata Kuliah:** Machine Learning
- **Tugas:** Ujian Tengah Semester (UTS)

## Deskripsi

Tugas ini membahas implementasi algoritma Machine Learning, yaitu Linear Regression dan Logistic Regression, menggunakan Python dan Jupyter Notebook.

Pengerjaan meliputi proses membaca dataset, pengolahan data, implementasi algoritma, pelatihan model, prediksi, dan evaluasi hasil sesuai instruksi tugas UTS.

## Tujuan

1. Memahami konsep Linear Regression.
2. Memahami konsep Logistic Regression.
3. Mengimplementasikan algoritma menggunakan NumPy.
4. Memahami proses pembagian data latih dan data uji.
5. Mengevaluasi hasil prediksi model.

## Tools dan Library

- Python 3
- Visual Studio Code
- Jupyter Notebook
- NumPy
- Pandas
- Matplotlib

## Struktur File

Pastikan file tugas tersusun seperti berikut:

```text
tugas-uts-machine-learning/
├── README.md
├── tugas_UTS_machine_learning_Yuri_Naufal_Akhdan_Reg_B.ipynb
├── Ads_Data.csv
└── Email_Data.csv
```

**Catatan:** File CSV harus tersedia jika digunakan oleh kode dalam notebook. Letakkan dataset di folder yang sama dengan notebook agar lebih mudah dibaca.

## Algoritma yang Digunakan

### 1. Linear Regression

Linear Regression merupakan algoritma supervised learning yang digunakan untuk memprediksi nilai numerik berdasarkan hubungan antara fitur dan target.

Rumus umum:

\[
\hat{y} = Xw + b
\]

Keterangan:
- `ŷ` adalah nilai prediksi.
- `X` adalah data fitur.
- `w` adalah bobot model.
- `b` adalah bias atau intersep.

### 2. Logistic Regression

Logistic Regression merupakan algoritma supervised learning yang digunakan untuk klasifikasi.

Pada klasifikasi biner, fungsi sigmoid digunakan untuk mengubah keluaran model menjadi probabilitas.

Rumus sigmoid:

\[
\sigma(z) = \frac{1}{1+e^{-z}}
\]

Probabilitas tersebut digunakan untuk menentukan kelas prediksi berdasarkan ambang yang diterapkan pada model.

## Random State

Nilai random state yang digunakan adalah **52**, sesuai dua digit terakhir NIM `241011402952`.

Nilai ini digunakan pada proses pembagian dataset jika diminta oleh instruksi tugas.

## Cara Menjalankan Notebook

1. Buka Visual Studio Code.
2. Pilih **File → Open Folder**.
3. Pilih folder tempat file tugas disimpan.
4. Pastikan ekstensi Python dan Jupyter sudah terpasang.
5. Buka file notebook dengan ekstensi `.ipynb`.
6. Pilih Python Kernel.
7. Pastikan dataset CSV tersedia.
8. Jalankan setiap sel kode secara berurutan dari atas ke bawah.
9. Periksa hasil keluaran dan pastikan tidak ada error.

Jika library belum tersedia, buka terminal VS Code dan jalankan:

```bash
python -m pip install numpy pandas matplotlib
```

Jika perintah `python` tidak dikenali, coba:

```bash
py -m pip install numpy pandas matplotlib
```

## Ketentuan Pengerjaan

- Implementasi algoritma mengikuti instruksi UTS.
- NumPy digunakan untuk implementasi algoritma yang diwajibkan.
- Pandas digunakan untuk membaca dan mengolah dataset.
- Matplotlib digunakan untuk visualisasi apabila diperlukan.
- Penggunaan scikit-learn untuk model dan metrik harus mengikuti ketentuan dosen.
- Gunakan `RANDOM_STATE = 52` sesuai NIM.

## Pemeriksaan Sebelum Pengumpulan

- [ ] Nama mahasiswa sudah benar.
- [ ] NIM sudah benar.
- [ ] Kelas sudah tertulis Reg B.
- [ ] Random state sudah menggunakan nilai 52.
- [ ] Dataset yang dibutuhkan sudah tersedia.
- [ ] Notebook sudah dijalankan dan hasilnya diperiksa.
- [ ] Semua perubahan sudah disimpan.
- [ ] README.md dan notebook siap dimasukkan ke repositori GitHub.

## Penutup

README ini menjelaskan identitas mahasiswa, tujuan tugas, algoritma yang dipelajari, kebutuhan library, dan cara menjalankan notebook UTS Machine Learning.

**Nama:** Yuri Naufal Akhdan  
**NIM:** 241011402952  
**Kelas:** Reg B
