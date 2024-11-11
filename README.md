# master_plan

PRAKTIKUM 1

1. ![image](https://github.com/user-attachments/assets/cc8b2b08-b5f9-40f7-aa25-5bc99a3a3b7e)
2. Maksud dari langkah 4 adalah menggambarkan sebuah rencana yang teridiri dari nama dan daftar tugas. bisa membuat objek dalam Plan dengan nama tertentu dan daftar tugas yang relevan. kode ini dirancang agar lebih fleksibel, mudah dipahami, dan aman dengan menggunakan nilai default, parameter bernama, dan immutable list.
3. variable plan dalam langkah 6 digunakan untuk menyimpan objek dari kelas plan, yang akan menjadi data utama dalam tampilan PlanScreen. Kelas plan kemungkinan menyimpan informasi terkait rencana yang ingin ditampilkan atau dikelola pada layar tersebut, seperti daftar tugas atau kegiatan.
   penggunaan const pada plan berarti objek plan tersebut adalah konstan atau immutable, yang berarti objek tersebut tidak dapat diubah setelah dibuat.
4. ![image](https://github.com/user-attachments/assets/e7b27e1e-7bbd-4355-b4bf-e6818940fc1b)
   akan menampilkan checkbox dan textfromFiled untuk mengedit atau menambah deskripsi tugas
5. iniState() untuk memeprsiapkan dan menginisialisasi berbagai hal sebelum widget dibangun
   dispose() dipanggil ketika widget sudah tidak lagi digunakan atau dihapus dari widget tree. fungsi utamanya untuk memebrsihkan dan melepas sumber dara yang digunakan oleh widget.

PRAKTIKUM 2
1. ![Screenshot 2024-11-11 111621](https://github.com/user-attachments/assets/e7b3c9ad-b8e3-43fd-b1dc-eb5127f4b29d)
2. InheritedWidget adalah kelas dasar yang digunakan untuk membuat widget yang dapat membagikan data (state) ke widget lain di bawahnya dalam pohon widget. InheritedWidget memungkinkan data untuk dibagikan ke widget anak tanpa harus melewati banyak level widget secara eksplisit melalui konstruktor. Namun, InheritedWidget hanya menyediakan cara untuk menyimpan dan mendistribusikan data, dan tidak menyediakan cara untuk memberitahu widget anak ketika data tersebut berubah. InheritedNotifier adalah turunan dari InheritedWidget yang lebih spesifik dan berfungsi untuk menangani pemberitahuan perubahan data secara otomatis. Dalam kasus ini, InheritedNotifier digunakan dengan ValueNotifier<Plan>, yang merupakan objek yang dapat memberi tahu widget terkait ketika data (dalam hal ini objek Plan) berubah.
3. pada praktikum 3 adalah contoh implementasi getter dalam Dart untuk menghitung dan menampilkan jumlah tugas yang telah diselesaikan serta memberikan pesan mengenai status tugas tersebut. hal ini dikarenakan untuk enkapsulasi, reusability dan pemisahan tanggung jawab.
4. ![image](https://github.com/user-attachments/assets/26530040-50b1-4423-a6b3-2b9549217a24)
   menampilkan ketika menambahkan tugas dan checkbox maka akan menampilkan 1 out of 2 takss


A new Flutter project.

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.
