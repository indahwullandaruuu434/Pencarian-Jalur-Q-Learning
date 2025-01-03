# Pencarian Jalur Q-Learning 

Implementasi algoritma Q-learning untuk menemukan jalur terpendek dalam graf.

## Kebutuhan
- Python 3.x
- NumPy 
- NetworkX
- Matplotlib/Pylab

## Fitur
- Visualisasi graf dengan NetworkX
- Implementasi dasar Q-learning 
- Pencarian jalur optimal ke tujuan
- Grafik proses pembelajaran

## Penggunaan
1. Atur koneksi node dalam `points_list`
2. Tentukan `MATRIX_SIZE` sesuai jumlah node
3. Jalankan program untuk visualisasi dan hasil jalur

## Komponen
- Inisialisasi dan visualisasi graf
- Pengaturan matriks reward
- Implementasi Q-learning
- Proses pelatihan (700 episode)
- Pengujian dan pencarian jalur

## Keluaran
- Visualisasi graf jaringan
- Matriks Q hasil pelatihan
- Jalur optimal dari awal ke tujuan
- Grafik perkembangan pembelajaran

## Fungsi
- `available_actions()`: Mendapatkan aksi yang valid dari state
- `sample_next_action()`: Memilih aksi secara acak
- `update()`: Memperbarui nilai Q dengan rumus Q-learning

## Parameter
- Node: 0-7 
- State tujuan: Node 7
- Gamma: 0.8
- Episode: 700
