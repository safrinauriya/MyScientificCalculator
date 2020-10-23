# MyScientificCalculator
MyScientificCalculator adalah aplikasi android  yang menjalankan fungsi kalkulator ilmiah. Fungsi kalkulator ini menghitung trigonometri, logaritma dan faktorisasi selain fungsi dasar, mereka
penjumlahan, pengurangan, perkalian dan pembagian.  Untuk menjalankan aplikasi ini, membutuhkan beberapa function(fungsi) di dalamnya, seperti fungsi penjumlahan, pengurangan, perkalian, pembagian dan lainnya. 


Ketelitian pada hasil kalkulator ini adalah sampai sepuluh digit angka berarti. Untuk menambah ketelitian hasil dapat dilakukan dengan menambah digit tersembunyi. Digit tersembunyi berguna untuk mengurangi kesalahan akibat adanya pembulatan jika variabel penyimpan tidak cukup untuk menyimpan hasil dari fungsi.

# Penggunaan Layout Aplikasi
Pada layout aplikasi kalkulator, kita menggunakan layout LinearLayout. Linear Layout merupakan layout yang berfungsi untuk menampilkan komponen-komponen aplikasi contohnya : teks, tombol, gambar dan lainnya dengan cara vertikal ataupun horizontal. Di LinearLayout, instance View child diatur satu per satu sehingga list horizontal hanya akan memiliki satu baris dengan beberapa kolom dan list vertikal akan memiliki satu kolom yang terdiri dari beberapa baris.Untuk aplikasi yang memiliki design tidak terlalu kompleks maka linear layout sangat cocok untuk digunakan. 
- [x] Orientation -> untuk mengatur orientasi untuk ditampilkan secara horizontal atau vertikal, sehingga item muncul dalam satu kolom atau satu baris. 
- [x] Gravity -> Tag gravity digunakan untuk mengatur tata letak komponen yang ada pada linear layout.
- [x] Weight -> Weight digunakan untuk memberikan bobot pada komponen layout. Pada penggunaannya juga dapat digunakan jika salah satu layout width atau layout height bernilai 0, agar idak terjadi error. 
- [x] Button -> Button juga terdapat atribut onClick yang berisi fungsi fungsional dari kalkulator seperti hasil perhitungan, menghapus data yang telah di hitung, dan digit angka yang akan di hitung. 

# Penggunaan Pada Java
- [x] Anotasi @ SuppressLint digunakan untuk menonaktifkan pemeriksaan lint secara khusus pada class.
- [x] Method penggunaan Button 
1. Fungsi Operator. 
Menampilkan hasil dengan  method hasil operasi hitung penjumlahan, pengurangan, perkalian , pembagian dan lainnya. 
2. Method btnClick_equal. 
Sebagai fungsi utama dan sangat berpengaruh terhadap fungsionalitas aplikasi kalkulator untuk menampilkan hasil akhir perhitungan.
3. Method btnClick_delete. 
Berfungsi untuk menghapus digit angka pada kalkulator.
4. Method btnClick_Clear. 
Button clear(C) maka nilai dari text_result kembali menjadi “0”. 

# Tampilan Kalkulator

![Screenshot_20201023-201618_MyScientificCalculator (1)](https://user-images.githubusercontent.com/60589670/97011200-911c3f00-1570-11eb-8fb2-c02ecdf39899.jpg)

# Tampilan jika digit yang dimuat terlalu banyak

![Screenshot_20201023-213417_MyScientificCalculator](https://user-images.githubusercontent.com/60589670/97017996-cc227080-1578-11eb-977a-738cccae806c.jpg)

# Tampilan jika mengklik  tanda “=” dua kali

![Screenshot_20201023-213337_MyScientificCalculator](https://user-images.githubusercontent.com/60589670/97017982-c75dbc80-1578-11eb-98d4-a1c6e1cda6c0.jpg)
