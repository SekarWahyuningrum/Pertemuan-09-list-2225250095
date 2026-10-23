**Nama:** Sekar Wahyuningrum

**NIM:** 2225250095

**Kelas:** 3E

**Mata Kuliah:** Algoritma dan Pemrograman

## Tujuan

Memahami cara menggunakan list dalam Python untuk menyimpan dan mengolah banyak data dalam satu variabel. Mempelajari cara mengambil data menggunakan indeks dan slicing, menambah serta menghapus elemen list, menghitung rata-rata nilai, dan menentukan nilai yang memenuhi batas kelulusan. Selain itu, praktikum ini bertujuan melatih kemampuan menggunakan fungsi agar program lebih mudah dibuat dan dipahami.

## Struktur Folder

```text
pertemuan-09-list-2225250095/
├── README.md
├── .gitignore
├── latihan/
│   ├── 01_buat_list.py
│   ├── 02_indeks_slicing.py
│   ├── 03_manipulasi_list.py
│   ├── 04_agregasi_nilai.py
│   ├── 05_filter_kelulusan.py
│   └── 06_fungsi_statistik.py
└── praktik/
    └── analisis_nilai_mahasiswa.py
```

## Materi yang Dipelajari

1. Membuat dan membaca list menggunakan tanda kurung siku `[]`.
2. Mengakses elemen list menggunakan indeks.
3. Menggunakan slicing untuk mengambil sebagian elemen list.
4. Memanipulasi list menggunakan metode `append()`, `insert()`, dan `remove()`.
5. Menghitung total, rata-rata, nilai minimum, dan maksimum menggunakan fungsi bawaan Python.
6. Menyaring nilai berdasarkan batas kelulusan menggunakan perulangan dan percabangan.
7. Membuat fungsi untuk menghitung rata-rata dan menentukan nilai yang lulus.
8. Menjalankan program melalui terminal VS Code serta mengelola tugas menggunakan Git dan GitHub.

## Deskripsi File Latihan dan Praktik

| File                          | Keterangan                                                                                        |
| ----------------------------- | ------------------------------------------------------------------------------------------------- |
| `01_buat_list.py`             | Membuat list berisi lima nilai dan menghitung jumlah elemennya.                                   |
| `02_indeks_slicing.py`        | Menampilkan elemen pertama, elemen terakhir, tiga elemen awal, dan elemen pada indeks 1 sampai 3. |
| `03_manipulasi_list.py`       | Mengubah, menambahkan, menyisipkan, dan menghapus elemen list.                                    |
| `04_agregasi_nilai.py`        | Menghitung total, rata-rata, nilai minimum, dan maksimum.                                         |
| `05_filter_kelulusan.py`      | Menampilkan nilai yang memenuhi batas kelulusan 60 dan menghitung jumlahnya.                      |
| `06_fungsi_statistik.py`      | Membuat fungsi `rata_rata(data)` untuk menghitung rata-rata nilai.                                |
| `analisis_nilai_mahasiswa.py` | Menganalisis nilai mahasiswa menggunakan fungsi rata-rata dan penyaringan nilai kelulusan.        |

## Cara Menjalankan Program

Pastikan Python sudah terpasang di komputer. Buka terminal VS Code, kemudian arahkan terminal ke folder utama proyek.

### 1. Menjalankan File Latihan

Jalankan setiap file latihan menggunakan perintah berikut.

**Latihan 1 — Membuat List**

```bash
python latihan/01_buat_list.py
```

**Latihan 2 — Indeks dan Slicing**

```bash
python latihan/02_indeks_slicing.py
```

**Latihan 3 — Manipulasi List**

```bash
python latihan/03_manipulasi_list.py
```

**Latihan 4 — Agregasi Nilai**

```bash
python latihan/04_agregasi_nilai.py
```

**Latihan 5 — Filter Kelulusan**

```bash
python latihan/05_filter_kelulusan.py
```

**Latihan 6 — Fungsi Statistik**

```bash
python latihan/06_fungsi_statistik.py
```

### 2. Menjalankan Program Praktik

Jalankan program analisis nilai mahasiswa menggunakan perintah berikut.

```bash
python praktik/analisis_nilai_mahasiswa.py
```

Program akan menampilkan hasil pengolahan nilai mahasiswa, termasuk rata-rata, daftar nilai yang lulus, jumlah mahasiswa yang lulus, dan jumlah mahasiswa yang tidak lulus.

## Hasil Pengujian Latihan

| No. | Program                  | Hasil Pengujian                              |
| --: | ------------------------ | -------------------------------------------- |
|   1 | Membuat dan membaca list | Jumlah data = 5                              |
|   2 | Indeks dan slicing       | Elemen pertama = 75, elemen terakhir = 70    |
|   3 | Manipulasi list          | `[75, 70, 82, 90]`                           |
|   4 | Agregasi nilai           | Total = 398, rata-rata = 79.60               |
|   5 | Filter kelulusan         | Nilai lulus = `[75, 80, 60, 90]`, jumlah = 4 |
|   6 | Fungsi statistik         | Rata-rata = 79.60                            |

## Hasil Pengujian Praktik

Program praktik `analisis_nilai_mahasiswa.py` menggunakan daftar nilai mahasiswa berikut:

```python
[78, 55, 90, 67, 60, 82, 45, 71, 88, 59]
```

Hasil pengolahan data ditampilkan pada tabel berikut.

| Operasi                                 | Input                | Hasil yang Diharapkan          |
| --------------------------------------- | -------------------- | ------------------------------ |
| Menghitung rata-rata                    | 10 nilai mahasiswa   | 69.50                          |
| Menentukan nilai lulus                  | Batas kelulusan = 60 | `[78, 90, 67, 60, 82, 71, 88]` |
| Menghitung jumlah mahasiswa lulus       | Batas kelulusan = 60 | 7 mahasiswa                    |
| Menghitung jumlah mahasiswa tidak lulus | Batas kelulusan = 60 | 3 mahasiswa                    |

Berdasarkan perhitungan, jumlah seluruh nilai adalah 695 dengan rata-rata 69.50. Sebanyak 7 mahasiswa memperoleh nilai minimal 60 sehingga dinyatakan lulus, sedangkan 3 mahasiswa memperoleh nilai di bawah 60 sehingga dinyatakan tidak lulus.

## Kuis Formatif - Kuis 3

Kuis formatif membahas materi list Python, meliputi:

1. Penggunaan list untuk menyimpan banyak data dalam satu variabel.
2. Pengaksesan elemen menggunakan indeks dan slicing.
3. Manipulasi elemen list.
4. Penggunaan fungsi untuk menghitung jumlah elemen dan rata-rata.
5. Penanganan list kosong agar program tidak mengalami kesalahan saat melakukan perhitungan.
6. Penggunaan perintah Git untuk mengirim commit lokal ke GitHub.

## Refleksi

Dari praktikum ini, saya belajar bahwa list dapat memudahkan penyimpanan dan pengolahan banyak data dalam satu variabel. Saya menjadi lebih memahami cara mengambil elemen menggunakan indeks dan slicing, mengubah isi list, serta menghitung rata-rata dan menyaring nilai mahasiswa menggunakan Python.

Saya juga belajar untuk lebih teliti saat menggunakan indeks karena indeks list dimulai dari 0. Kesalahan dalam menentukan indeks dapat menyebabkan data yang diambil tidak sesuai atau menimbulkan error. Melalui latihan ini, saya semakin memahami dasar penggunaan list dan cara mengolah data dengan Python secara lebih teratur.
