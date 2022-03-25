                                                   Pertanyaan dan Tugas
1. Lakukan eksperimen dengan mengubah dan menambah properti dan nilai pada kode CSS dengan mengacu pada CSS Cheat Sheet yang diberikan pada file terpisah dari modul ini.
2. Apa perbedaan pendeklarasian CSS elemen h1 {...} dengan #intro h1 {...}? berikan penjelasannya!
3. Apabila ada deklarasi CSS secara internal, lalu ditambahkan CSS eksternal dan inline CSS pada elemen yang sama. Deklarasi manakah yang akan ditampilkan pada browser? Berikan penjelasan dan contohnya!
4. Pada sebuah elemen HTML terdapat ID dan Class, apabila masing-masing selector tersebut terdapat deklarasi CSS, maka deklarasi manakah yang akan ditampilkan pada browser? Berikan penjelasan dan contohnya! ( <p id="paragraf-1" class="text-paragraf"> )
  
                                 JAWABAN
  
1.Berikut adalah perubahannya :
  sebelum di rubah
  ![v](https://user-images.githubusercontent.com/101801920/160067699-830f9551-1258-4d03-bed7-d73464485794.PNG)
  tampilan di browser
![VII](https://user-images.githubusercontent.com/101801920/160067710-d43f8229-493f-4441-84c5-ca50e0468891.PNG)

  Sesudah di rubah
  ![SATU](https://user-images.githubusercontent.com/101801920/160067227-1bed22c9-f363-4c98-bec1-a6c151ed0cd1.PNG)
  tampilan di rowser
  ![DUA](https://user-images.githubusercontent.com/101801920/160067460-ec563c7f-c771-48b1-b051-4372076a0d5a.PNG)
  
2. => Kalau h1{...} Untuk memberikan style pada semua element h1

   => Kalau #intro h1{...} Awalan simbol hash (#) memungkinkan kita untuk memberi style pada id. selector id bersifat kaku dan tidak bisa digunakan kembali pada element yang lainnya. Menurut saya lebih baik gunakan selektor class untuk mendefinisikan element yang ingin diberi nilai.
  
 3. jika ketiga CSS mengubah elemen yang sama maka deklarasi tersebut akan mengikuti aturan dimana prioritas CSSnya seperti berikut :

 => CSS sebaris
 => CSS pemilih ID
 => CSS internal
external CSS Contoh: ini adalah tampilan coding pada html testing dimana terdapat 2 kalimat yang memiliki elemen yang sama yaitu h1:
terdapat 2 CSS yang merubah warna tect h1

![tiga](https://user-images.githubusercontent.com/101801920/160069429-ded20cb6-bb4f-4db1-a57a-72890ff5556a.PNG)
    tampilan di browser
 ![empat](https://user-images.githubusercontent.com/101801920/160069418-133004e2-470c-4e54-8650-1db1f05b6ada.PNG)
  
 4. semakin spesifik css maka akan semakin tinggi prioritas css tersebut. contoh :
![lima](https://user-images.githubusercontent.com/101801920/160070309-bdf69c76-939b-4371-b75e-70fee77ce9df.PNG)

 Di situ bisa dilihat terdapat 2 css yang merujuk ke elemen yang sama tapi 1 merujuk dengan id yang birisi font 100px dan warna aqua sedangkan yang satu lagi merujuk dengan kelas yang berisi font 10px dan warna beige:
  ![SATU](https://user-images.githubusercontent.com/101801920/160070366-37fc1a5d-a0ff-4370-9968-0d00f069d465.PNG)






  
