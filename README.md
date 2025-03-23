_saya Natasha Adinda Cantika dengan NIM 2312120 mengerjakan TP4 dalam mata kuliah DPBO untuk keberkahanNya maka saya tidak melakukan kecurangan seperti yang telah dispesifikasikan. Aamiin_

## Penjelasan Program
Program ini merupakan program CRUD sederhana dengan java swing GUI dan memanfaatkan fitur UI form untuk menciptakan interface interaktif untuk user. Struktur program ini terdiri dari satu kelas utama, yaitu Menu, yang merupakan subclass dari JFrame (kelas bawaan Java untuk membuat jendela GUI).
**Komponen utama yang digunakan:**
1. **JTextField**: Input teks untuk NIM dan Nama mahasiswa.
2. **JComboBox**: Dropdown untuk memilih jenis kelamin.
3. **JRadioButton**: Pilihan status mahasiswa (Aktif/Cuti/Lulus).
4. **JScrollPane & JTable**: Menampilkan daftar mahasiswa dalam bentuk tabel yang dapat di scroll.
5. **JButton**: Tombol untuk Add/Update, Delete, dan Cancel.
6. **JPanel**: Panel utama untuk menampung komponen GUI.
7. **DefaultTableModel**: Model data untuk tabel.

Selain itu, terdapat pula kelas Mahasiswa yang merupakan kelas untuk objek mahasiswa.
**Komponen/Atribut dari kelas Mahasiswa:**
1. **NIM**, yang menampung string NIM mahasiswa.
2. **Nama**, menampung string nama mahasiswa.
3. **Jenis kelamin**, menampung string jenis kelamin mahasiswa (laki-laki/perempuan).
4. **Status**, menampung status perkuliahan mahasiswa (Aktif/Cuti/Lulus).

**Method utama dalam program:**
1. Konstruktor Menu(), berfungsi untuk mengatur tampilan GUI.
2. populatelist(), berfungsi untuk mengisi array/table mahasiswa.
3. setTable(), untuk mengatur tampilan table mahasiswa, metode ini memanfaatkan metode getter dari kelas mahasiswa.
4. insertData(), untuk menangani penambahan data mahasiswa dengan mengambil value dari JTextField, JComboBox, dan JRadioButton.
5. updateData(), untuk menangani perubahan data, cara kerjanya mirip dengan insert data.
6. deleteData(), untuk menangani penghapusan data mahasiswa, metode ini bekerja dengan menghapus salah satu elemen listmahasiswa berdasarkan selected index.
7. clearForm(), bertugas untuk mengosongkan form setelah melakukan input, update, hapus, atau menekan cancel.
8. selectRadioButton(string Status), metode ini digunakan untuk mengatur tampilan dari radio button ketika salah satu index pada tabel mahasiswa diklik, cara kerjanya adalah dengan mengambil dan mengecek string status mahasiswa, setelah melalui pengecekan if else akan menentukan radio button mana yang akan menyala atau dalam kondisi true.

**Cara Kerja Program:**
1. Saat aplikasi dijalankan, jendela GUI akan ditampilkan dengan tabel berisi data mahasiswa.
2. Pengguna dapat menambahkan data baru dengan mengisi NIM, Nama, Jenis Kelamin, dan memilih Status, lalu menekan tombol Add.
3. Pengguna dapat mengedit data dengan mengklik salah satu baris tabel, mengubah nilai pada form, lalu menekan tombol Update.
4. Pengguna dapat menghapus data dengan menekan tombol Delete setelah memilih salah satu baris.
5. Tombol Cancel digunakan untuk mengosongkan form input tanpa melakukan perubahan data.

## Sreenrecord output
<p align="left">
    <img src="screenshot/TP4_run_23_03_2025.mp4" width=500>
</p>
