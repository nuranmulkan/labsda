# labsda
anggota kelompok : 1. Rahmatul Ulya 
                   2. Nayla Nabila Syahel
                   3. Hazairin
                   4. Raisa Salsabila Nabila 
                   5. Dara Ramadhani
                   6. Habib Nuran Mulkan
                   
Struktur Umum Program
Kode ini merupakan implementasi evaluasi ekspresi postfix menggunakan stack. Stack diimplementasikan dengan array dan linked list.

Bagian-Bagian Program :

1. Struct Stack (Menggunakan Array)

top: Menunjukkan indeks elemen teratas dalam stack.
capacity: Kapasitas maksimum stack.
array: Array untuk menyimpan elemen stack.

2. Fungsi untuk Stack dengan Array

createStack(capacity): Membuat stack dengan kapasitas tertentu.
isEmpty(stack): Mengecek apakah stack kosong.
push(stack, item): Menambahkan elemen ke dalam stack.
pop(stack): Menghapus dan mengembalikan elemen teratas stack.

3. Struct Node & StackList (Menggunakan Linked List)

Node: Struktur simpul dengan data dan next.
StackList: Struktur stack dengan top sebagai pointer ke elemen teratas.

4. Fungsi untuk Stack dengan Linked List

pushList(stack, data): Menambahkan elemen ke stack (linked list).
popList(stack): Menghapus elemen teratas dari stack.
isEmptyList(stack): Mengecek apakah stack kosong.

5. Fungsi Evaluasi Postfix

evaluatePostfixArray(expression): Evaluasi ekspresi postfix menggunakan stack berbasis array.
evaluatePostfixList(expression): Evaluasi ekspresi postfix menggunakan stack berbasis linked list.
Kedua fungsi membaca ekspresi postfix dan melakukan operasi berdasarkan operand dan operator.

6. Fungsi main()

Meminta input ekspresi postfix.
Memproses evaluasi menggunakan stack array dan linked list.
Menampilkan hasil evaluasi ekspresi.

Implementasi struktur data dalam program ini menggunakan Stack, yang diimplementasikan dengan dua cara:

1. Stack berbasis Array

Menggunakan array statis atau dinamis untuk menyimpan elemen.
Operasi push, pop, dan isEmpty dilakukan dengan indeks array.
Keuntungan: Akses lebih cepat karena indeks langsung digunakan.
Kekurangan: Ukuran stack terbatas dan perlu didefinisikan sebelumnya.

2. Stack berbasis Linked List

Menggunakan pointer untuk menyimpan elemen dalam node terhubung.
Operasi push, pop, dan isEmpty dilakukan dengan manipulasi pointer.
Keuntungan: Ukuran stack fleksibel karena bisa bertambah sesuai kebutuhan.
Kekurangan: Akses lebih lambat karena membutuhkan alokasi memori dinamis.



                   
