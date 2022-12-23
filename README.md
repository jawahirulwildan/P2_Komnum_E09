Kelompok 9

- Muhammad Zien Zidan (5025211122)
- Ariella Firdaus Imata (5025211138)
- Jawahirul Wildan (5025211150)

Dengan bantuan scipy.integrate.romberg()metode, kita dapat memperoleh integrasi romberg dari fungsi yang dapat dipanggil dengan batas a=0 dan  b=3
Numpy sebuah library yang memberikan dukungan untuk himpunan dan matriks multidimensi yang besar di rujuk ke np 
Dilakukan pemanggilan dari scipy. Scipy digunakan untuk memanggil kumpulan algoritme dan fungsi matematika lalu di import juga dari integrate sehingga nantinya itu bisa melakukan teknik integrasi
Lalu dibuat variabel fungsi Gassiun
Gassiun = lambda x : np.exp (-x**2)
Lambda menuju ke x sama dengan np.exp(-x**2) nantinya akan di return ke np.exp(-x**2)
Setelah itu menggunakan fungsi scipy.integrate.romberg() dan dimasukan batas a dan b nya
Romberg = integrate.romberg(Gaussian, 0, 3, show = True)
Terakhir di print dari fungsi romberg
