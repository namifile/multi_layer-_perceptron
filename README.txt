Ini adalah contoh kecil dari Multi Layer Perceptron yang diimplementasikan di Java.

Ini dapat digunakan untuk tujuan pendidikan atau eksperimen semacam ini
jaringan saraf.
Dalam contoh ini, jaringan saraf akan mempelajari gerbang logika XOR.


- lapisan ke-1, yaitu lapisan masukan yang tersusun dari 2 neuron,
- lapisan ke-2, lapisan tersembunyi memiliki 6 neuron,
- lapisan ke-3, yaitu lapisan keluaran memiliki 1 neuron.

Kelas Neuron mewakili neuron dari jaringan saraf.
Kelas Layer mewakili sebuah lapisan perceptron.
Kelas Mlp mewakili perceptron.


Untuk mengkompilasi, gunakan:
$ javac -g Mlp.java

Kemudian jalankan Mlp:
$ java Mlp


File gnuplot.dat akan dibuat, berisi data plot untuk
evolusi kesalahan kuadrat.

Untuk memplotnya dengan gnuplot, misalnya:
$ gnuplot
gnuplot> plot "plot.dat" menggunakan 1: 2 dengan garis
gnuplot> keluar

