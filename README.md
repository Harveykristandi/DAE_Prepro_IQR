# DAE_Prepro_IQR

IQR Outlier Cleaner
Code Python ini berfungsi untuk membersihkan data dari outlier menggunakan metode Interquartile Range (IQR). Hal ini dirancang untuk dijalankan di environment Google Colab.

## Fitur
1. Upload & Baca: Mengunggah file CSV langsung di Colab.
2. Pembersihan Otomatis: Mengidentifikasi kolom numerik, mengubah format angka (koma ke titik), dan mengonversinya.
3. Deteksi IQR: Menghitung batas bawah dan atas untuk setiap kolom numerik.
4. Visualisasi: Menghasilkan plot histogram perbandingan (sebelum vs. sesudah) untuk setiap kolom yang dibersihkan.
5. Simpan & Unduh: Menyimpan data yang sudah bersih ke dalam format .csv dan .xlsx, lalu otomatis mengunduhnya ke komputermu.

## Cara Pakai
1. Buka Google Colab: https://colab.research.google.com/.
2. Buat Notebook baru.
3. Salin dan tempel seluruh kode dari file clean_outliers.py ke dalam sel di Notebook.
4. Jalankan sel tersebut.
5. Saat diminta, klik tombol "Choose Files" dan unggah file TGM 2020-2023_eng.csv atau file CSV sejenis.
6. Tunggu proses selesai. File hasil dan
