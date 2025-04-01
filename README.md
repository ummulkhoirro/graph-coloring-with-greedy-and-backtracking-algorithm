# graph-coloring-with-greedy-and-backtracking-algorithm
Pewarnaan graf adalah proses memberikan label (atau warna) pada node dalam graf sehingga tidak ada dua node yang bertetangga memiliki warna yang sama. Proyek ini bertujuan untuk mendemonstrasikan dan membandingkan kinerja dari dua teknik pewarnaan graf yang populer.

1. Algoritma Backtracking: Pendekatan rekursif yang mengeksplorasi semua kemungkinan pewarnaan hingga menemukan solusi yang valid.
2. Algoritma Greedy: Pendekatan heuristik yang memberikan warna terkecil yang tersedia untuk setiap node secara berurutan.


# Kesimpulan
Dari hasil eksperimen pewarnaan graf menggunakan Backtracking dan Greedy Algorithm, dapat disimpulkan bahwa:

- Backtracking memberikan solusi optimal tetapi lebih lambat
  Backtracking mencoba semua kemungkinan kombinasi warna, sehingga hasilnya lebih optimal (menggunakan jumlah warna minimal).
  Namun, karena kompleksitas eksponensialnya, metode ini membutuhkan waktu eksekusi yang lebih lama, terutama untuk graf yang
  lebih besar.

- Greedy lebih cepat tetapi tidak selalu optimal
  Algoritma Greedy lebih efisien dalam waktu eksekusi karena hanya memberikan warna pertama yang tersedia untuk setiap node.
  Namun, solusi yang dihasilkan tidak selalu optimal dalam jumlah warna yang digunakan. Bergantung pada urutan input, Greedy
  bisa memberikan hasil yang lebih buruk daripada Backtracking.

- Perbandingan Kinerja
  Backtracking ideal digunakan jika graf berukuran kecil hingga sedang dan membutuhkan solusi optimal.
  Greedy lebih cocok untuk graf besar di mana efisiensi waktu lebih diutamakan dibandingkan optimalitas jumlah warna.

