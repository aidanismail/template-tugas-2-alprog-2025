# Tugas 2 Praktikum Algoritma dan Pemrograman 2025: Percabangan & Operator

**PENTING: Harap untuk membaca instruksi di [wiki](https://github.com/praktikum-tiunpad-angkatan-2022/modul-algoritma-dan-pemrograman/wiki) terlebih dahulu sampai dipahami sebelum mengerjakan soal!**

**Penting Juga: Biasakan menambah format berikut pada bagian paling atas setiap file kode!**

**Soal-soal ini dibuat oleh Aidan Ismail - 140810230075**

```cpp
/*
Nama Program :
Nama         :
NPM          :
Tanggal Buat :
Deskripsi    :
*/
```

## Daftar Isi

- [Latihan 1](#latihan-1)
- [Latihan 2](#latihan-2)
- [Latihan 3](#latihan-3)
- [Fizz Buzz](#Fizz-Buzz)
- [Max and Min](#Max-and-Min)
- [Central Park?](#Central-Park)
- [Floor and Ceiling](#Floor-and-Ceiling)

## Latihan 1

> file: `latihan_1.cpp`

### Deskripsi

Bantu Freddie Mercury membuat program yang membaca sebuah bilangan bulat, lalu menampilkan apakah bilangan tersebut Positif, Negatif, atau Nol.

### Format Input

Sebuah bilangan bulat `N`.

### Format Output

Sebuah string:
`Positif` jika `N` > 0
`Negatif` jika `N` < 0
`Nol` jika `N` = 0

### Contoh

- Sample Input 1

  ```
  19
  ```

- Sample Output 1

  ```
  Positif
  ```

- Sample Input 2

  ```
  -1
  ```

- Sample Output 2

  ```
  Negatif
  ```

- Sample Input 3

  ```
  0
  ```

- Sample Output 3

  ```
  Nol
  ```

## Latihan 2

> file: `latihan_2.cpp`

### Deskripsi

Bantu Marie Antoinette buat program yang membaca sebuah bilangan bulat dan menentukan apakah bilangan tersebut memiliki tepat 4 digit.
Bilangan negatif tetap dihitung digitnya tanpa tanda minus.

### Format Input

Sebuah bilangan bulat `N`.

### Format Output

Sebuah string:
`Ya` jika `N` 4 digit
`Tidak` jika `N` bukan 4 digit

### Contoh

- Sample Input 1

  ```
  1979
  ```

- Sample Output 1

  ```
  Ya
  ```

- Sample Input 2

  ```
  -10000
  ```

- Sample Output 2

  ```
  Tidak
  ```

## Latihan 3

> file: `latihan_3.cpp`

### Deskripsi

Sebuah Planet bernama Miller, mempunyai syarat tahun kabisat sebagai berikut:

- habis dibagi 300, atau
- habis dibagi 6 tetapi tidak habis dibagi 50.

### Format Input

Sebuah bilangan bulat `N`.

### Format Output

Sebuah string:
`Kabisat` jika `N` tahun kabisat
`Bukan Kabisat` jika `N` bukan tahun kabisat

### Contoh

- Sample Input 1

  ```
  2016
  ```

- Sample Output 1

  ```
  Kabisat
  ```

- Sample Input 2

  ```
  2023

  ```

- Sample Output 2

  ```
  Bukan Kabisat
  ```

## Fizz Buzz

> file: `tugas_1.cpp`

### Deskripsi

Seorang musisi bernama Paul McCartney ingin membuat permainan sederhana bernama FizzBuzz.

Aturannya:

- Jika bilangan habis dibagi 3, cetak Fizz
- Jika bilangan habis dibagi 5, cetak Buzz
- Jika habis dibagi 3 dan 5, cetak FizzBuzz
- Selain itu, cetak angka itu sendiri

### Format Input

Sebuah bilangan bulat `N`.

### Format Output

String sesuai aturan FizzBuzz.

### Contoh

- Sample Input 1

  ```
  15
  ```

- Sample Output 1

  ```
  FizzBuzz
  ```

- Sample Input 2

  ```
  7
  ```

- Sample Output 2

  ```
  7
  ```

- Sample Input 3

  ```
  3
  ```

- Sample Output 3

  ```
  Fizz
  ```

## Max and Min

> file: `tugas_2.cpp`

### Deskripsi

Kibutsuji Muzan ingin membuat program yang membaca tiga bilangan bulat a, b, dan c. Dan bisa menentukan bilangan maksimum dan minimum dari ketiganya.

### Format Input

Tiga bilangan bulat `a`, `b`, `c`.

### Format Output

Maksimum: `X`
Minimum: `Y`

### Contoh

- Sample Input 1

```
7 2 9
```

- Sample Output 1

```
Max: 9
Min: 2
```

- Sample Input 2

```
0 -1 -11
```

- Sample Output 2

```
Max: 0
Min: -11
```

## Central Park

> file: `tugas_3.cpp`

### Deskripsi

bantu tukang parkir biadab bernama Dominic Perluigi Ramonez membuat program untuk "gedung" di Jl. Gatot Subroto No.1, RT.1/RW.3, Senayan, Kecamatan Tanah Abang, Kota Jakarta.
Aturan tarifnya, yakni:

- Motor: Rp 2.000 per jam
- Mobil: Rp 5.000 per jam
- Bus: Rp 10.000 per jam

### Format Input

Jenis kendaraan (1 = Motor, 2 = Mobil, 3 = Bus)

Lama parkir dalam jam (bilangan bulat positif)

### Format Output

Tampilkan total biaya parkir.

### Contoh

- Sample Input 1

```
1
3

```

- Sample Output 1

```
Total biaya parkir: Rp6000

```

- Sample Input 2

```
3
2

```

- Sample Output 2

```
Total biaya parkir: Rp20000

```

## Floor and Ceiling

> file: `tugas_4_freeform.cpp`

### Deskripsi

Nilai floor dari sebuah bilangan riil adalah bilangan bulat terbesar yang masih lebih kecil daripada atau sama dengan bilangan tersebut. Sebaliknya, nilai ceiling dari sebuah bilangan riil adalah bilangan bulat terkecil yang masih lebih besar daripada atau sama dengan bilangan tersebut.

Moriarty memberikan Anda sebuah tantangan. Tanpa menggunakan library Tentukan nilai floor dan ceiling dari bilangan `real` N.

### Format Input & Output

Tidak ada format input dan output pada tugas yang bersifat freeform. Selama program kamu melakukan yang diinstruksikan, kreasikan sebebasmu!
