# Antena
Project Pembuatan Antena

>Antena Mikrostrip
   
Proyek ini merupakan perancangan dan simulasi antena mikrostrip yang bekerja pada frekuensi 614 MHz dengan nilai Voltage Standing Wave Ratio (VSWR) mendekati 1. Antena ini dirancang untuk bekerja pada frekuensi 614 MHz, yang termasuk dalam pita Ultra High Frequency (UHF). Rentang frekuensi UHF banyak dimanfaatkan pada sistem komunikasi modern karena memiliki kemampuan propagasi yang baik dan mendukung pengiriman data maupun informasi dengan kualitas yang tinggi.

cara kerja :

Antena mikrostrip bekerja dengan mengubah sinyal listrik berfrekuensi tinggi (Radio Frequency/RF) yang berasal dari pemancar menjadi gelombang elektromagnetik yang          dipancarkan ke ruang bebas. Ketika sinyal RF diberikan pada saluran pencatu (feed line), arus listrik akan mengalir menuju patch antena dan menghasilkan medan listrik (Electric Field) serta medan magnet (Magnetic Field). Perubahan kedua medan tersebut secara terus-menerus membentuk gelombang elektromagnetik yang kemudian dipancarkan ke udara.

Sebaliknya, ketika antena menerima gelombang elektromagnetik dari udara, proses tersebut berlangsung secara terbalik. Gelombang elektromagnetik yang diterima akan diubah menjadi sinyal listrik dan diteruskan menuju rangkaian penerima (receiver).

Cara realisasi antena :
- Buka file CST yang berisi project antena mikrostrip yang sudah siap
- atur parameter antena agar mendapatkan frekuensi dan vswr sesuai
- export desain patch untuk dijadikan stiker untuk proses pembuatan PCB
- Pembuatan PCB Antena


>Antena Dipole

Proyek ini merupakan perancangan dan simulasi antena dipole setengah gelombang (Half-Wave Dipole) menggunakan software CST Studio Suite. Antena dipole merupakan salah satu jenis antena paling sederhana dan paling banyak digunakan dalam bidang telekomunikasi karena memiliki konstruksi yang sederhana, mudah dibuat, serta memiliki karakteristik radiasi yang stabil.

Antena dipole terdiri dari dua buah konduktor dengan panjang yang sama dan dipisahkan oleh titik pencatu (feed point) di bagian tengah. Ketika diberikan sinyal listrik berfrekuensi tinggi (Radio Frequency/RF), antena akan mengubah energi listrik menjadi gelombang elektromagnetik yang dipancarkan ke ruang bebas. Sebaliknya, saat menerima gelombang elektromagnetik, antena akan mengubahnya kembali menjadi sinyal listrik yang kemudian diproses oleh perangkat penerima.

cara kerja :
Prinsip kerja antena dipole didasarkan pada perubahan arus listrik bolak-balik berfrekuensi tinggi yang mengalir pada kedua elemen antena. Ketika arus RF mengalir dari titik pencatu menuju ujung kedua elemen, elektron di dalam konduktor akan bergerak bolak-balik sehingga menghasilkan medan listrik (Electric Field) dan medan magnet (Magnetic Field) yang berubah terhadap waktu. Perubahan kedua medan tersebut membentuk gelombang elektromagnetik yang kemudian dipancarkan ke ruang bebas.

Pada saat antena digunakan sebagai penerima, proses yang terjadi adalah kebalikannya. Gelombang elektromagnetik yang datang akan menginduksi arus listrik pada kedua elemen antena sehingga menghasilkan sinyal listrik yang dapat diteruskan menuju rangkaian penerima.

