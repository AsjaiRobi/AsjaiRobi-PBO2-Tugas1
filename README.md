# AsjaiRobi-PBO2-Tugas1

# Program CekAngka

Program CekAngka adalah aplikasi Java berbasis GUI yang dibuat menggunakan Java Swing. Aplikasi ini memungkinkan pengguna untuk memasukkan angka, kemudian memeriksa apakah angka tersebut adalah bilangan ganjil atau genap dan apakah angka tersebut adalah bilangan prima.
Fitur

    Input Angka
        Pengguna dapat memasukkan angka pada TextField yang disediakan.

    Pengecekan Ganjil/Genap
        Setelah menekan tombol "Cek", program akan mengecek apakah angka tersebut ganjil atau genap dan menampilkan hasilnya.

    Pengecekan Bilangan Prima
        Program juga akan memeriksa apakah angka tersebut adalah bilangan prima atau bukan.

    Tombol Hapus
        Tombol "Hapus" berfungsi untuk mengosongkan TextField input dan hasil yang tampil di Label.

    Validasi Input
        Program memastikan hanya angka yang dapat dimasukkan oleh pengguna di TextField.

Struktur Program

    Class CekAngka: Kelas utama yang menginisialisasi dan menampilkan antarmuka program.
    Method isPrime(int number): Memeriksa apakah angka adalah bilangan prima.
    Method isNumeric(String input): Memeriksa apakah input yang dimasukkan adalah angka.
    Event Listeners: Mengelola interaksi pengguna, seperti saat tombol "Cek" ditekan atau saat input di TextField dihapus.

Cara Menggunakan Program

    Masukkan angka pada TextField.
    Klik tombol "Cek" untuk mengetahui apakah angka tersebut ganjil/genap dan apakah prima.
    Hasil akan ditampilkan dalam dialog pesan serta Label.
    Klik tombol "Hapus" untuk membersihkan input dan hasil.

Contoh Hasil

    Input: 7
        Output: "7 adalah bilangan ganjil. Dan bilangan prima."
    Input: 10
        Output: "10 adalah bilangan genap. Dan bukan bilangan prima."
