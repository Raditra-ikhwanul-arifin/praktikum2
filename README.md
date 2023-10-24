# Bahasa Pemrograman
Tugas praktikum 2

# Laporan Praktikum
* Latihan 1:
> Python peka terhadap huruf besar-kecil, jadi perhatikan ukuran huruf besar-kecil yang digunakan
<p align="left">
  <img src="/ss/latihan1.jpg" width="700">  
</p>

    print("Hello!")
    print("Saya sedang belajar Python.")

perintah print berfungsi untuk perintah maupun mencetak kata pada Python.

* Latihan 2:
> a + b dapat ditulis menjadi a+b tetapi penggunaan Python mempunyai standar keteraturan.
<p align="left">
  <img src="/ss/latihan2.jpg" width="600">
</p>

    # variabel
    a = 77
    b = 777

    # cetak dan hitung variabel
    print("Nilai pertama:", a)
    print("Nilai kedua:", b)
    print("Hasil dari kedua nilai:", a + b)

a = 77 dan b = 777 yaitu variabel dan intenger.
, a + b yaitu perintah pada Python untuk menjumlahkan variabel yang tertera.

* Latihan 3:
> int bersifat opsional, gunakan jika Anda ingin kode yang lebih terstruktur. 
<p align="left">
  <img src="/ss/latihan3.jpg" width="700">  
</p>
   
    # input nilai variabel bersifat intenger
    n = int(input("Masukan nilai n: "))
    t = int(input("Masukan nilai t: "))
    
    # cetak nilai variabel
    print("Variabel n:", n)
    print("Variabel t:", t)
    
    # cetak hasil operasi kedua variabel dengan format string
    print("Hasil penggabungan {0} & {1}: %d".format(n, t) % (n + t))
    
    # konversi nilai variabel
    n = int(n)
    t = int(t)
    print("Hasil penjumlahan {0} + {1}: %d".format(n, t) % (n + t))
    print("Hasil pembagian {0} / {1}: %d".format(n, t) % (n / t))

int berfungsi untuk menentukan sifat perintah sebagai bilangan bulat. Input 
 berfungsi untuk memasukkan kata atau angka yang diinginkan. 
, n dan , t berfungsi untuk mengatur variabel yang telah ditentukan sebelumnya. 
Fungsi {0} dan {1}  untuk memanggil variabel secara berurutan. 
%d adalah hasil dengan definisi yang cocok dalam .format. 

