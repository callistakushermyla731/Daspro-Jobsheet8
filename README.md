Percobaan 1
1. Output jumlah bintang yang dicetak menjadi lebih banyak satu. Karena loop dimulai dari i = 1 sampai N, sehingga total perulangan adalah N kali. Jika diubah menjadi i = 0, maka perulangannya akan dimulai dari 0, 1, 2, ..., sampai N. Berarti perulangan berjalan N + 1 kali.
2. Perulangan tidak akan berjalan, sehingga tidak ada bintang yang dicetak. Karena i = 1, sedangkan kondisi yang dicek adalah i > N, dan jika nilai N berapa pun yang positif, 1 > N adalah false. Karena kondisi awal langsung salah, blok for tidak pernah dijalankan.
3. Program akan mencetak bintang tanpa henti sampai program dihentikan secara paksa. Karena i dimulai dari 1, kondisi loop i <= N. Tetapi setiap iterasi i justru berkurang (i--), sehingga i menjadi 0, -1, -2, dan seterusnya. Nilai i menjadi tidak pernah mencapai syarat berhenti/false.4. 

Percobaan 2
1. Program tetap mencetak pola, tetapi total baris tetap N, hanya saja baris pertama kosong. Baris pertama akan kosong karena perulangan dalam akan berjalan dari i = 1 sampai i <= iOuter, sedangkan nilai iOuter = 0 menye kondisi i <= iOuter langsung false.
2. Mencetak lebih banyak satu bintang dari yang seharusnya. Semula: i berjalan dari 1 → iOuter → jumlah bintang = iOuter. Diubah: i berjalan dari 0 → iOuter → jumlah bintang = iOuter + 1
3. Perulangan luar= Mengatur jumlah baris yang akan dicetak. Perulangan dalam= Mengatur jumlah bintang di setiap baris.
4. Untuk pindah ke baris berikutnya setelah perulangan dalam selesai mencetak bintang. Jika dihilangkan, maka semua bintang dicetak dalam satu baris panjang dan pola segitiga tidak terbentuk.
