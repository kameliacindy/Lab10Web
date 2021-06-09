# Praktikum 10 : PHP OOP

## Pengertian PHP OOP

 - **OOP** adalah singkatan dari _**Object Oriented Programming**_. 
 - **OOP** merupakan metode pemrograman yang lebih berorientasi pada objek, maksudnya pemrograman yang lebih terpusat pada objek, sehingga akan lebih sangat memudahkan kita di dalam membuat aplikasi.

## Pengertian *Class*

 - ***Class*** di dalam OOP digunakan untuk membuat sebuah kerangka kerja atau bisa disebut sebagai *library* yang berisi *property* dan *method*. 
 - Jadi ***class*** adalah sebuah wadah yang menyimpan *property* dan *method*. Dan *object* yang dihasilkan biasanya berdasarkan isi dari *class*.

## Pengertian *Object*

 - ***Object*** adalah **output** dari ***class***. 
 - *Object* dapat menampilkan atau mengelola isi *class*, seluruh isi *class* akan kita instansiasikan menjadi *object*.

## Contoh PHP OOP

Berikut adalah **contoh syntax penulisan metode oop di php**. buat sebuah file dengan nama `mobil.php`

![enter image description here](https://github.com/kameliacindy/Lab10Web/blob/main/img/mobil.PNG)

![enter image description here](https://github.com/kameliacindy/Lab10Web/blob/main/img/mobil2.PNG)

### Penjelasan class Mobil

Kita membuat sebuah **class** dengan nama **Mobil**. Pada sebuah bahasa pemrograman berorientasi objek mengharuskan kita untuk mendeklarasikan nama objek yang akan kita buat dengan menggunakan class Mobil, maka akan tercipta sebuah objek Mobil.

### Penjelasan private $warna

 - Setelah class Mobil selanjutnya terdapat sebuah kode dengan nama `private $warna`, `private $merk`, `private $harga`
 - Dasarnya `private` dan `$warna` adalah sesuatu yang berbeda.
 - `private` adalah sifat atau tipe pada variable yang akan kita gunakan, dimana variable private untuk memberikan akses properti yang hanya dapat diakses dari dalam class tersebut. 
 - Sedangkan `$warna`, `$merk`, `$harga` adalah sebuah variable atau di dalam OOP disebut sebagai ***property***.

### Penjelasan public function __construct()

***Method Construct*** adalah *method* yang dijalankan pertama kali pada saat sebuah class dijalankan. Jadi apabila kita menjalankan atau menginstansiasi sebuah class yang terdapat *method* atau *function construct* di dalamnya maka yang pertama kali dijalankan adalah *method construct* ini.

### Penjelasan $this->warna

 - **$this** adalah sebuah *keyword* atau kata kunci yang sudah tersedia di php sehingga kita tidak boleh menggunakan *keyword* tersebut untuk variable yang akan kita buat.
 - Fungsi **$this** ini digunakan sebagai penunjuk pada sebuah objek *property* yang nantinya akan dapat diakses pada *method* lain sehingga sifatnya tidak hanya digunakan pada suatu *method* yang mendeklarasikan *property* tersebut.

### Hasil Tampilannya

![enter image description here](https://github.com/kameliacindy/Lab10Web/blob/main/img/ss_mobil.PNG)

## Syntax penulisan kode form.php

![enter image description here](https://github.com/kameliacindy/Lab10Web/blob/main/img/form.PNG)

![enter image description here](https://github.com/kameliacindy/Lab10Web/blob/main/img/form2.PNG)

## Syntax penulisan kode form_input.php

![enter image description here](https://github.com/kameliacindy/Lab10Web/blob/main/img/form_input.PNG)

### Hasil Output form_input.php

![enter image description here](https://github.com/kameliacindy/Lab10Web/blob/main/img/ss_form_input.PNG)

Kemudian kita menginput, seperti berikut ini.

![enter image description here](https://github.com/kameliacindy/Lab10Web/blob/main/img/ss_form_input2.PNG)

Terima kasih, semoga bermanfaat...

Nama	: Kamelia Cindy Astuti

NIM	: 311910104

Kelas	: TI. 19. A. 1
