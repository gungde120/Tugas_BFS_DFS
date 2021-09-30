# Tugas DFS dan BFS
![tree](https://user-images.githubusercontent.com/86350332/135272198-8451d0a4-a689-488f-80fd-5957faf72d89.png)

# DFS
Lines 2-12: Membuat graph sesuai dengan tree dan angka yang berhubungan. Karena tidak ada tanda panah maka hubungan bisa dibolak-balik.

Line 11: membuat set visited untuk membuat nodes tetap pada track nya.

Lines 16-21: penjelasan algoritma DFS: awalnya akan memeriksa apakah node saat ini belum dikunjungi (jika sudah dikunjungi, node ditambahkan dalam set yang dikunjungi). Kemudian untuk setiap tetangga hubungan dari node saat ini, fungsi dfs akan dipanggil lagi. Kasus awal akan dipanggil lagi ketika semua node dikunjungi. Jika node sudah habis, maka algoritma telah selesai.

Line 24: function DFS dipanggil dengan menaruh set visited yaitu daftar yang dikunjungi, graph, dan '1' untuk start node nya.

# BFS

Lines 1-12: Membuat graph sesuai dengan tree dan angka yang berhubungan. Karena tidak ada tanda panah maka hubungan bisa dibolak-balik.

Line 14: membuat set visited untuk melacak nodes.

Line 15: membuat set queue digunakan untuk melacak node saat ini dalam antrian.

Lines 18-28: penjelasan algoritma BFS : Pada awalnya, algoritma akan memeriksa dan menambahkan node awal ke daftar yang dikunjungi (visited) dan antrian (queue). Kemudian, ketika  pada queue terdapat node yang terhubung, queue akan mengeluarkan node. Kemudian akan menambahkan  node yang berhubungan tersebut ke queue jika belum dikunjungi, dan menandainya sebagai "dikunjungi".Algoritma ini 
akan berlanjut sampai queue kosong.

Line 31: function BFS dipanggil dengan menaruh set visited yaitu daftar yang dikunjungi, graph, dan '1' untuk start node nya.
