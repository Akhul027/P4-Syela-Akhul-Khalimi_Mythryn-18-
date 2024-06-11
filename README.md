# P4-Syela-Akhul-Khalimi_Mythryn-18-
Buat dua objek Rectangle (p1 dan p2). Gabungkan p1 dan p2 menjadi p3 dan cetak hasilnya. Ambil perpotongan p1 dan p2 di p4 dan cetak hasilnya. Gandakan luas p1 dan cetak hasilnya. Kurangi luas p2 menjadi setengahnya dan cetak hasilnya. Periksa apakah p1 dan p2 berpotongan dan cetak hasilnya.

operatorRectangle+(const Rectangle &other) Menggabungkan dua persegi panjang yang berpotongan dan mengembalikan persegi panjang baru yang mencakup luas gabungan dua persegi panjang.

Operator persegi panjang- (const Rectangle &other) Mengambil perpotongan dua persegi panjang yang berpotongan dan mengembalikan persegi panjang baru yang merupakan perpotongan kedua persegi panjang. >
Rectangle &operator++() Gandakan luas persegi panjang dengan menggandakan luas​ ​panjang dan lebar persegi panjang menggunakan akar persegi(2).

Persegi Panjang &operator--() Mengurangi luas persegi panjang menjadi dua dengan membagi panjang dan lebarnya dengan akar persegi(2).
> void print() const Cetak koordinat batas persegi panjang (xmin, ymin, xmax, ymax ) ke konsol.

bool Operator==(const Rectangle &other) const Memeriksa apakah dua persegi panjang berpotongan atau tidak. Mengembalikan nilai benar jika keduanya berpotongan dan salah jika sebaliknya.
