# if-else-statement

#if-else statement 
adalah salah satu kontrol flow statement yang digunakan untuk membuat keputusan dalam program.
struktur dasar dari if else statement adalah sebagai berikut:/

    if kondisi:

        # kode yang akan dieksekusi jika kondisi bernilai True 

    else:

        # kode yang akan dieksekusi jika kondisi bernilai False

kondisi dapat berupa ekspresi Boolean apa saja, seperti perbandingan dua nilai, pengecekan status suatu variabel, atau hasil dari operasi logika. 
jika kondisi bernilai True, maka kode di dalam blik if akan dieksekusu. Jika kondisi bernilai False, maka kode di dalam blok else akan dieksekusi.

#contoh

# Cek apakah nilai siswa lebih besar dari atau sama dengan 90
    if nilai_siswa >= 90:
        print("Predikat A")
    elif nilai_siswa >= 80:
        print("Predikat B")
    elif nilai_siswa >= 75:
        print("Predikat C")
    else:
        print("Predikat D")
