## Tugas Pendahuluan

1. ```java
    String hello = "Hello";
    String world = new String("Hello");

    System.out.println(hello == world); //false
    System.out.println(hello.equals(world)); //true
   ```

   Jelaskan apa perbedaan operator **==** dengan method **equals()** menghasilkan output yang berbeda!

2. Tuliskan dan Jelaskan fungsi 10 method pada String selain yang tersedia di modul!
3. Jelaskan apa kegunaan dari String Format pada Java, dan berikan contoh sederhana!
4. Diberikan kalimat *Java Is Fun*, tuliskan potongan program bila :
     >> contoh potongan program :
     ```java
          String s = "Tahu Kotak";
     ```
     * kalimat diubah menjadi huruf kecil,
     * kalimat diubah menjadi huruf besar,
     * spasi pada kalimat tersebut dihapus,
     * mengecek panjang dari kalimat tersebut,
     * memotong kalimat tersebut menjadi 2 bagian dan bagian pertama yang diambil,
     >> contoh : TahuKotak -> Tahu | Kotak -> Tahu *(ambil bagian pertama)*
     * mengubah String tersebut menjadi array yang bertipe data char,
     * membalikkan kalimat yang dipotong tersebut ke dalam String yang baru,
     >> contoh : TAHU -> UHAT
     * mencetak nilai _true_ jika index terakhir dari String adalah "J",
     * mencetak nilai _true_ jika String terakhir tidak kosong.
