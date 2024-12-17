Latihan OOP

Buatlah package dan modul dengan struktur seperti berikut:

• data -> mahasiswa.py ➔berisi model data yang mendefinisikan class Mahasiswa dan class DataMahasiswa untuk proses pencarian data, tambah data, hapus data, dan ubah data.

• view -> input_form.py ➔berisi class untuk form input data mahasiswa

• view -> mahasiswa.py ➔berisi class untuk proses menapilkan list data dan detail data.

• Main.py ➔ program utama yang menampilkan menu utama.

Halo nama saya Faiq Zainal Ridho, kali ini saya akan membahas cara membuat class dengan file terpisah. Tanpa basa basi mari kita bahas:

1. folder data berisi file mahasiswa dengan kelas Mahasiswa dan masukkan fungsi utama dengan def __init__ yang di dalam kurungnya self, nama, nim, tugas, uts, uas dan variabel diawali dengan self

![5 1](https://github.com/user-attachments/assets/f67ae20c-4b6c-465f-966c-1524a31937fd)

2. definisi tambah untuk menyimpan data yang telah diinputkan

![5 2](https://github.com/user-attachments/assets/81ab3e2f-e55f-48d2-978a-0b6e31bb303c)

3. definisi ubah untuk mengubah data yang tersimpan

![6 2](https://github.com/user-attachments/assets/e6d0ea39-a409-4adb-b19d-7da9c34dc9e2)

4. definisi hapus untuk menghapus data yang ada

![7 1](https://github.com/user-attachments/assets/59077013-ecbe-4908-898c-cdb622b7a0dc)

5. definisi cari untuk mencari data yang tersimpan

![7](https://github.com/user-attachments/assets/4ae2b10e-e7e9-42e5-882d-f556ac3d0fe5)

6. folder view berisi file input_form dengan kelas masuk beserta definisi tambah, ubah, hapus dan cari sebagai input yang diimport dari data.mahasiswa dengan kelas Mahasiswa bersama datanya agar data input tersimpan

![3](https://github.com/user-attachments/assets/a2dc27c5-50fb-425b-9277-ac07c9a0b1dc)

![4](https://github.com/user-attachments/assets/8a3446f4-2de8-42a1-ba43-baf13b7d0f6d)

7. folder view dengan file kitamahasiswa dengan kelas Vmahasiswa beserta definisi tampilkan sebagai tabel untuk data yang ada

![2](https://github.com/user-attachments/assets/a17e0740-ae21-4c7c-97f0-894c9cd637b6)

8. diluar kedua folder ini, file Utama sebagai penjalan program yang ada di dalam folder data dan view dengan kelas main dengan definisi __init__(self) yang dijalankan dari import view.input_form dan view.kitamahasiswa

![1](https://github.com/user-attachments/assets/c4522e01-935e-4548-81ad-0ae559da889b)

9. berikut hasilnya

![its](https://github.com/user-attachments/assets/7201f04d-3bdc-4fac-9077-a058d605afc8)

![show](https://github.com/user-attachments/assets/950e2d96-d17a-4ac4-a0df-ce5a073d9b22)

![time](https://github.com/user-attachments/assets/bc445237-a71c-441a-aa24-6743ad4fec96)

![!!!](https://github.com/user-attachments/assets/a793ec16-1a3d-4459-951f-6180c6b6e837)

10. berikut flowchartnya (masih tidak ada yang diubah)

![praktikum6](https://github.com/user-attachments/assets/5720e3d6-275b-4e09-89d6-dbc6a3dc3440)

11. berikut diagramnya

![Latihan OOP](https://github.com/user-attachments/assets/f9d25c5f-2802-4c67-afcb-3be2663a1c23)

inilah tugas yang saya kerjakan dan jelaskan, mohon maaf atas keterlambatannya diakibatkan masalah pada vcs dan terima kasih
