# Bahasa Pemrograman
Tugas praktikum 2

# Laporan Praktikum
* Latihan 1:
> Python bersifat case-sensitive, jadi perhatikan besar kecil huruf yang digunakan.
<p align="left">
  
</p>

    print("Hello!")
    print("Saya sedang belajar Python.")

perintah print berfungsi untuk perintah maupun mencetak kata pada Python.

* Latihan 2:
> a + b bisa saja ditulis menjadi a+b tapi penggunaan Python mempunyai standar keteraturan.
<p align="left">

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
> int bersifat opsional, gunakan jika ingin kode lebih terstruktur.
<p align="left">

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

int berfungsi untuk mendefinisikan sifat perintah menjadi bilangan bulat.
input berfungsi untuk memasukan kata atau bilangan yang diinginkan.
, n dan , t berfungsi untuk meletakan variabel yang sudah didefinisikan sebelumnya.
{0} dan {1} berfungsi untuk memanggil variabel sesuai urutan.
%d merupakan hasil dengan definisi sesuai pada .format.

