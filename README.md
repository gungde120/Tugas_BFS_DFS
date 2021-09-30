# Tugas DFS dan BFS
![tree](https://user-images.githubusercontent.com/86350332/135272198-8451d0a4-a689-488f-80fd-5957faf72d89.png)

# DFS
Lines 2-12: Membuat graph sesuai dengan tree dan angka yang berhubungan. Karena tidak ada tanda panah maka hubungan bisa dibolak-balik.

Line 11: visited untuk membuat track pada nodes

Line 24: function dfs dipanggil dengan menaruh set visited, graph, dan '1' untuk start node nya.

Lines 16-21: penjelasan algoritma DFS: awalnya akan memeriksa apakah node saat ini belum dikunjungi (jika sudah dikunjungi, node ditambahkan dalam set yang dikunjungi). Kemudian untuk setiap tetangga hubungan dari node saat ini, fungsi dfs akan dipanggil lagi. Kasus awal akan dipanggil lagi ketika semua node dikunjungi. Jika node sudah habis, maka function selesai.

# BFS
