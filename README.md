# Penyelesaian-Integral-dengan-Metode-Eksak-Trapezoid-dan-Riemann
Pada praktikum ini akan dibuat sebuah program untuk menyelesiakan persoalan integral menggunakan 3 buah metode yaitu eksak, trapezoid, dan riemann pada python 3.
A. Prosedur Percobaan
1. Buka aplikasi python 3 pada PC/laptop.
2. Masukkan library numpy dan matplotlib.
3. Masukkan persamaan integral yang akan diselesaikan.
4. Cantumkan parameter untuk menghitung step size, yaitu a = 1, b = 10, dan N = 10, 100, dan 1000. 
5. Masukkan program untuk metode trapezoid dan riemann. 
6. Hitung juga persamaan integral tersebut menggunakan perhitungan eksak (manual). 
7. Bandingkan nilai dan grafik yang diperoleh dari setiap metode yang digunakan. 

B. Pembahasan
    Pada praktikum ini, akan dibuat penyelesaian persamaan integral menggunakan 3 metode, yaitu eksak, trapezoid, dan riemann. Metode eksak adalah metode yang menghasilkan penyelesaian paling optimal. Hal tersebut dapat dibuktikan karena pembuktian metodenya dilakukan secara analitis menggunakan metode matematis. Metode trapezoid adalah suatu metode pendekatan integral numerik dengan polinom orde satu. Dalam metode ini, kurva yang berbentuk lengkung di dekatkan dengan garis lurus sedemikian sehingga, bentuk dibawah kurvanya seperti trapesium. Metode Trapezoid mempartisi suatu fungsi menjadi n bagian lalu membentuk partisi-partisi tersebut sedemikian rupa sehingga menjadi bentuk trapesium. 
    Metode integral Riemann dilakukan dengan membagi interval di bawah kurva suatu fungsi matematik sebanyak  m subinterval sama besar. Pada setiap subinterval dibentuk persegi panjang setinggi kurva pada setiap titik tengah persegi panjang tersebut. Area setiap subinterval diperoleh dengan mengalikan panjang dan lebar masing-masing persegi panjang. Jumlah masing-masing area tersebut digunakan untuk menaksir interval integral suatu fungsi dengan interval tertentu. 
    Praktikum ini dilakukan menggunakan aplikasi python untuk metode trapezoid dan riemann. Sddangkan untuk metode eksak dilakukan dengan perhitungan manual. Hasil dari solusi eksak yaitu 1.83386. Untuk hasil dari metode trapezoid ketika n = 10 adalah 1.80251645951, n = 100 adalah 1.8336025179314241, dan n = 1000 adalah 1.8338559016977116. Untuk hasil dari metode riemann ketika n = 10 adalah 1.9841861836144943, n = 100 adalah 1.85011794739, dan n = 1000 adalah 1.8354925658787735. Dari semua hasil yang diperoleh, dapat diketahui bahwa semakin besar nilai n (jumlah integer), maka semakin mendekati nilai eksak. Namun, dari metode trapezoid dan riemann, yang lebih mendekati nilai eksak adalah metode trapezoid. Dapat dilihat ketika metode trapezoid dengan n = 1000, hasilnya adalah 1.8338559016977116 yang mana hampir mendekati nilai eksak yaitu 1.83386. Dapat dilihat juga pada grafik yang dihasilkan pada lampiran, semakin banyak diagram batang, maka semakin akurat nilai yang dihasilkan.
