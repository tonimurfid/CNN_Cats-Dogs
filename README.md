# CNN_Cats-Dogs
## Klasifikasi Gambar Kucing atau Anjing Menggunakan Convolutional Neural Network

### Deskripsi Proyek
Proyek ini merupakan bagian dari kursus Deep Learning dari Udemy dan bertujuan untuk membuat model Convolutional Neural Network (CNN) yang dapat membedakan antara gambar kucing dan anjing. Model ini dapat digunakan untuk klasifikasi gambar kucing dan anjing dengan tingkat akurasi yang tinggi.

### Instalasi
1. Pastikan Anda memiliki Python yang terinstal di komputer Anda.
2. Instalasi beberapa pustaka Python yang dibutuhkan dengan menjalankan perintah berikut di terminal atau command prompt:

   ```bash
   pip install numpy pandas tensorflow keras matplotlib opencv-python
   ```

3. Unduh dataset kucing dan anjing dari sumber dataset yang dipilih.

### Penggunaan
1. Pastikan Anda telah mengunduh dan menyiapkan dataset kucing dan anjing.
2. Jalankan script `train_cnn.py` untuk melatih model CNN menggunakan dataset yang telah disiapkan:

   ```bash
   python train_cnn.py --dataset_path path_to_dataset --output_model_path model_output_path
   ```

   Gantilah `path_to_dataset` dengan path menuju dataset kucing dan anjing, dan `model_output_path` dengan path tempat Anda ingin menyimpan model yang dilatih.

3. Setelah melatih model, Anda dapat menjalankan script `predict_image.py` untuk melakukan prediksi pada gambar kucing atau anjing:

   ```bash
   python predict_image.py --image_path path_to_image --model_path path_to_model
   ```

   Gantilah `path_to_image` dengan path menuju gambar yang ingin Anda prediksi, dan `path_to_model` dengan path menuju model yang telah dilatih.

### Kontribusi
Kontribusi terhadap proyek ini selalu dipersilakan. Jika Anda menemukan masalah atau memiliki saran perbaikan, silakan buat *pull request* di repositori proyek ini.

### Lisensi
Proyek ini dilisensikan di bawah [MIT License](LICENSE).

### Kontak
Jika Anda memiliki pertanyaan atau saran, jangan ragu untuk menghubungi saya melalui email di [email@example.com](mailto:fatonimurfids@gmail.com).

---

Dengan menggunakan README di atas sebagai panduan, Anda dapat memberikan informasi yang cukup kepada pengguna proyek Anda tentang cara menggunakan, melatih, dan berkontribusi pada proyek klasifikasi gambar kucing atau anjing menggunakan Convolutional Neural Network. Jangan lupa untuk menyertakan informasi tambahan yang relevan dengan proyek Anda sendiri!
