---
title: "Form Oditur Militer"
date: 2022-05-10T10:43:44+07:00
draft: false
weight: 8
---

![Form Panitera Pengganti](images/form-oditur.png)

Form Oditur Militer adalah form untuk menambah, mengubah, atau menghapus data Oditur Militer. Form ini memiliki struktur atau tampilan yang sama dengan form Panitera Pengganti.

### Input Data Oditur

![Bagian Input Data Oditur](images/input-oditur.png)

| Input     | Keterangan    |
| ------    | -----------   |
| ID Oditur | Menu navigasi untuk berpindah antar Oditur Militer |
| Nama      | Tulis nama Oditur lengkap dengan gelar (jika ada) |
| Pangkat   | Tulis pangkat dengan `disingkat` (contoh: _Letkol Chk (K)_) |
| NRP       | `16 digit` NRP, dapat berupa simbol atau teks |

### Bagian Sub-Form Oditur Militer

![Sub-Form Oditur Militer](images/subform-oditur.png)

Bagian sub-form tidak dapat diubah, ditambah, atau dihapus karena statusnya dikunci (_locked_). Bagian ini hanya berfungsi untuk menampilkan daftar Oditur Militer yang sudah tersimpan saja. Untuk melakukan perubahan terhadap data Oditur yang bersangkutan silahkan gunakan menu navigasi yang sudah tersedia.

![Sub-Form Oditur Militer Expanded](images/subform-oditur-expand.png)

Salah satu manfaat lain dari sub-form ini adalah dapat menampilkan siapa saja nama Terdakwa yang terkorelasi dengan Oditur yang bersangkutan dengan cara klik tombol (**+**) yang ada pada sisi kiri nama Oditur. Contoh seperti pada gambar, ada 3 Terdakwa yakni Ari Andriawan, Wawan Triono, dan Mulyono yang Oditurnya adalah Mayor Sahroni Hidayat. Begitu seterusnya.

### Tombol Perintah

![Tombol Perintah](images/tombol-perintah-oditur.png)

| Tombol    | Keterangan    |
| ------    | -----------   |
| Tambah    | Menambahkan data Oditur Militer |
| Batal     | Membatalkan perubahan yang terjadi |
| Hapus     | `Menghapus data Oditur secara keseluruhan` |
| Simpan    | Menyimpan perubahan yang terjadi |
| Tutup     | Menutup form Oditur Militer |

{{% notice warning %}}
Hati-hati dalam memilih tombol yang di-klik karena segala perubahan yang terjadi tidak dapat dikembalikan
{{% /notice %}}

{{% notice tip %}}
Untuk menambahkan data Oditur Militer yang baru Anda bisa klik pada tombol navigasi _right-arrow_ atau langsung klik tombol "**Tambah**"
{{% /notice %}}
