# ScopeGlobalDanLocal__PY
Bahan Ajar Pemrograman Python Dasar - Mengenal Dan Menggunakan Variabel Dengan Scope Global dan Scope Local.<br><br>
<img src="https://github.com/RizkyKhapidsyah/ScopeGlobalDanLocal__PY/blob/master/result/001.PNG"><br><br>
# Lihat <a href="https://github.com/RizkyKhapidsyah/ScopeGlobalDanLocal__PY/blob/master/ScopeGlobalDanLocal__PY.py">Source Code.</a><br><br>


Pengertian scope global dan scope lokal dibawah ini :

Scope Global adalah suatu jenis nama fungsi yang bisa kita ubah isi data fungsi atau data functions di luar fungsi dan bisa diubah kapanpun kita mau. Scope lokal adalah jenis nama fungsi yang tidak dapat diubah datanya di luar fungsi. Scope lokal hanya dapat diubah di dalam fungsi nya itu sendiri . karena itu disebut dengan lokal. sedangkan scope global maksunya data dalam fungsinya bisa di luar fungsi dan kita bisa mesetting apapun . langsung saja Belajar Python Scope Global dan Lokal

# 1 . Scope Lokal

Scope lokal biasanya digunakan untuk privasi (private) code untuk biasanya mencegah dari serangan luar (hacker) karna hanya bersifat lokal dan tidak bisa di ubah dari luar fungsi. Contoh Program nya :

## Contoh 1 Scope Global :

      nama = ‘Phantom assasions’

      def tonyfunctions(namabaru):
      nama = namabaru
      print(‘nama Hero yang belum diubah adalah : ‘, nama) #fungsi lokal

      tonyfunctions(“sniper”)

      nama = “sinper” #diganti dengan sinper tetep nama diatas yang ada dalam fungsi tidak berubah

      print(nama) #print nama diluar fungsi


Output

>python scope lokal

# 2. Scope Global

Scope Global selalu diawali dengan tanda “global” karena sudah terdaftar dalam library python tersebut. scope global sangat banyak digunakan dalam OOP(Object Oriented Programming) yang digunakan untuk mengedit atau merubah

## contoh 1 scope global

      nama = ‘Phantom assasions’
      HP = 100

      def tonyfunctions(namabaru,darah):
      global nama,HP #global scope
      nama = namabaru
      HP = darah
      print(‘nama Hero yang belum diubah adalah : ‘, nama, “darah tersisa :”,HP) 

      nama = “sinper”
      tonyfunctions(nama,HP)


Output

>nama Hero yang belum diubah adalah : sinper darah tersisa : 60

## Contoh 2 Scope Global

      def tonyfunctions(namabaru):
      nama = namabaru
      print(‘nama Hero yang belum diubah adalah : ‘, nama) #fungsi lokal

      tonyfunctions(“sniper”)

      nama = “sinper” #diganti dengan sinper tetep nama diatas yang ada dalam fungsi tidak berubah

      print(nama) #print nama diluar fungsi


### Output

>nama Hero yang belum diubah adalah : sniper
>sinper


-----
Referensi Artikel: <a href="https://www.codezeroo.com">CodeZeroo</a>. Thanks to: <a href="https://www.codezeroo.com">CodeZeroo</a><br> 
Referensi Source Code: <a href="https://www.youtube.com/user/faqihzamukhlish"> Kelas Terbuka </a> dan <a href="https://github.com/kelasterbuka"> Kelas Terbuka (Repository)</a>. Created by <a href="https://github.com/faqihza">Faqihza Mukhlish.</a> Thanks To: <a href="https://www.youtube.com/channel/UCRGHjysoCemh4y7tCJQs30w/about">Faqihza Mukhlish.</a><br>

-----
All Source Code is Modified.
