---
title: "Form Panitera Pengganti"
date: 2022-05-10T10:43:44+07:00
draft: false
weight: 7
---

![Form Panitera Pengganti](images/form-pp.png)

Sesuai namanya, Form Panitera Pengganti adalah form untuk menambah, mengubah, atau menghapus data Panitera Pengganti. Jika dibandingkan dengan form Terdakwa, form ini terlihat lebih sederhana dengan ciri khas utama memiliki sub-form yang menampilkan daftar Panitera Pengganti yang sudah tersimpan dalam database.

### Input Panitera Pengganti

![Bagian Input Panitera Pengganti](images/bagian-pp.png)

| Input     | Keterangan    |
| ------    | -----------   |
| ID PP     | Menu navigasi untuk berpindah antar Panitera Pengganti |
| Nama PP   | Nama Panitera Pengganti lengkap dengan gelar (jika ada) |
| Pangkat   | Tulis pangkat secara lengkap (contoh: Pembantu Letnan Satu) |
| NRP       | `16 digit` NRP, dapat berupa simbol atau teks |

### Bagian Sub-Form Panitera Pengganti

![Sub-Form Panitera Pengganti](images/subform-pp.png)

Bagian sub-form tidak dapat diubah, ditambah, atau dihapus karena statusnya dikunci (_locked_). Bagian ini hanya berfungsi untuk menampilkan daftar Panitera Pengganti yang sudah tersimpan saja. Untuk melakukan perubahan terhadap data Panitera Pengganti yang bersangkutan silahkan gunakan menu navigasi yang sudah tersedia.

![Sub-Form Panitera Pengganti Expanded](images/subform-pp-expand.png)

Salah satu manfaat lain dari sub-form ini adalah dapat menampilkan siapa saja nama Terdakwa yang terkorelasi dengan Panitera Pengganti yang bersangkutan dengan cara klik tombol (**+**) yang ada pada sisi kiri nama PP. Contoh seperti pada gambar, ada 2 Terdakwa yakni Ari Andriawan dan Wawan Triono yang PP-nya adalah Peltu Rudianto. Begitu seterusnya.

### Tombol Perintah

![Tombol Perintah](images/tombol-perintah-pp.png)

| Tombol    | Keterangan    |
| ------    | -----------   |
| Tambah    | Menambahkan data Panitera Pengganti |
| Batal     | Membatalkan perubahan yang terjadi |
| Hapus     | `Menghapus data Panitera Pengganti secara keseluruhan` |
| Simpan    | Menyimpan perubahan yang terjadi |
| Tutup     | Menutup form Panitera Pengganti |

{{% notice warning %}}
Hati-hati dalam memilih tombol yang di-klik karena segala perubahan yang terjadi tidak dapat dikembalikan
{{% /notice %}}

{{% notice tip %}}
Untuk menambahkan data Panitera Pengganti yang baru Anda bisa klik pada tombol navigasi _right-arrow_ atau langsung klik tombol "**Tambah**"
{{% /notice %}}
