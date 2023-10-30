# Week-10e
Tugas Artificial Intelligent and Aplication Week 10
1.	Pelajari class EightPuzzleSearch, EightPuzzleSpace, dan Node.
a.	EightPuzzleSearch
Merupakan kelas yang mewakili algoritma pencarian (seperti A* atau BFS) yang digunakan untuk menyelesaikan masalah teka-teki delapan angka (Eight-Puzzle). Kelas ini mengimplementasikan logika untuk menjalankan pencarian, memantau keadaan ruang masalah, dan menghasilkan solusi.
b.	EightPuzzleSpace
Merupakan kelas yang menggambarkan ruang masalah teka-teki delapan angka. Ruang masalah ini mencakup keadaan awal, tujuan, serta operator-operasi yang diperbolehkan (seperti menggeser angka-angka). Kelas ini berisi metode-metode untuk menghasilkan penerjemahan antara keadaan dan representasinya dalam ruang masalah.
c.	Node
Node adalah entitas dalam struktur data yang digunakan dalam pencarian. Dalam konteks ini, Node mewakili keadaan dalam ruang masalah teka-teki delapan angka. Node ini memiliki informasi tentang keadaan saat ini, g(n) (biaya sejauh ini untuk mencapai node ini), h(n) (fungsi heuristik yang memperkirakan biaya dari node ini ke tujuan), serta referensi ke node yang merupakan pendahulunya. Node digunakan untuk melacak jalur solusi dan melakukan perhitungan dalam algoritma pencarian, seperti A*.

2.	Ubahlah initial dan goal state dari program di atas sehingga bentuk initial dan goal state-nya Gambar 8. Kemudian tentukan langkah-langkah mana saja sehingga puzzlenya mencapai goal state. Analisa dan bedakan dengan solusi pada point 1.

Jawab:
Setelah mengubah initial dan goat state dari program yang diberikan dengan initial = 3 1 2 4 7 5 6 8 0  dan goat state = 1 2 3 4 0 8 5 6 7 , ditemukan hasil penyelesaian sebagai berikut:

 1 2 3 4 5 6 7 8 0 
 1 2 3 4 5 6 7 0 8
 1 2 3 4 0 6 7 5 8
 1 2 3 4 6 0 7 5 8
 1 2 0 4 6 3 7 5 8
 1 0 2 4 6 3 7 5 8
 0 1 2 4 6 3 7 5 8
 4 1 2 0 6 3 7 5 8
 4 1 2 6 0 3 7 5 8
 4 1 2 6 5 3 7 0 8
 4 1 2 6 5 3 0 7 8
 4 1 2 0 5 3 6 7 8
 0 1 2 4 5 3 6 7 8
 1 0 2 4 5 3 6 7 8
 1 2 0 4 5 3 6 7 8
 1 2 3 4 5 0 6 7 8
 1 2 3 4 0 8 5 6 7 

