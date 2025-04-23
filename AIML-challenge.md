# AI/ML Challengen

## Deskripsi

Pada kegiatan ini peserta diminta untuk menyelesaikan soal yang diberikan oleh panitia secara berkelompok. Peserta diminta untuk menyelesaikan permasalahan (Use-case) sesuai dengan instruksi yang diberikan di dalam soal challenge dengan membuat model pada Azure Machine Learning.

## Ketentuan AI/ML Challenge

- AI/ML Challenge dikerjakan secara berkelompok.
- Peserta diberikan waktu untuk mengerjakan challenge selama 4 hari.
- Tanggal dan Jam Pengumpulan pada: **Minggu, 27 April 2025 pukul 23.59.**
- Hasil pekerjaan disubmit melalui GitHub Repo yang sudah disiapkan sesuai dengan tim masing-masing.
- File yang **harus** disubmit melalui GitHub Repo ialah `Notebook` dan `ML Canvas.`
- Pastikan solusi yang diberikan bisa berjalan tanpa mengalami error atau kegagalan.
- Keberhasilan dari case ini menjadi syarat untuk lanjut ke tahap selanjutnya.
- **Kriteria Penilaian:**
    - Pemahaman peserta tim terhadap use-case challenge
    - Relevansi code pada notebook
    - Metode dan model yang digunakan
    - Fungsionalitas code pada notebook
    - Submission Time berdasarkan last commit **sebelum waktu yang sudah ditentukan.**

## Membuat dan Menjalankan Azure Machine Learning

- **Preparation**
    1. Pastikan Anda memiliki akses ke Azure Machine Learning workspace.
    2. Clone repositori ke komputer lokal atau langsung ke dalam Azure workspace.
- **Lingkungan (Environment)**
    1. Siapkan environment Python dengan semua package yang dibutuhkan.
    2. Simpan konfigurasi tersebut dalam file `requirements.txt` untuk setiap use case, atau dimungkinkan juga install library secara langsung melalui notebook.
- **Notebook**
    1. Buka atau buat **Notebook** di Azure Machine Learning Studio.
    2. Jaga agar notebook tetap terorganisir dan terdokumentasi dengan baik menggunakan markdown untuk menjelaskan kode dan hasil.
    3. Kembangkan model Anda di dalam notebook tersebut dengan penjelasan yang jelas dan runtut.
- **Eksekusi**
    1. Jalankan notebook secara berurutan untuk menjaga alur pemrosesan data dan pelatihan model yang benar.
    2. Validasi hasil dan dokumentasikan secara rinci jika ada isu atau keanehan yang muncul.

## Kriteria Pembuatan Model

- **Feature Engineering:**
Lakukan *pre-processing* data yang diperlukan, seperti normalisasi, seleksi fitur, dan penanganan data yang hilang (missing values).
- **Pemilihan Model:**
Eksperimen dengan berbagai model machine learning dan deep learning seperti Linear Regression, Random Forest, dan Neural Network.
- **Pelatihan (Training):**
    - Bagi data Anda menjadi set pelatihan dan pengujian.
    - Latih model Anda menggunakan teknik dan hyperparameter yang sesuai.
- **Evaluasi**:
    - Nilai performa model menggunakan metrik seperti RMSE, MAE, atau metrik lain yang relevan.
    - Dokumentasikan dan bandingkan hasil antar model untuk menentukan yang terbaik.
    

# **📌 Langkah-langkah Submission pada GitHub Repo**

**1. Buat Struktur Repository GitHub dengan standar:**

1. Kategorisasi direktori berdasarkan masing-masing use-case
2. Pastikan menambahkan deskripsi use case pada direktori `main` dan dapat juga menambahkan detail deskripsi pada direktori masing-masing use-case
3. Peserta dipersilahkan untuk install langsung library melalui notebook atau dapat membuat list library dalam file `requirements.txt`

**2. Commit Perubahan**

```bash
git add .
git commit -m "Menambahkan notebook model prediksi"
```

**3. Push ke GitHub**

```bash
git push origin main
```