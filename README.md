## Catatan
1. Transformasi menggunakan tipe data _uniform_
2. _uniform_ bisa digunakan untuk _vertex_ dan/atau _fragment shader_
3. _attribute_ hanya bisa digunakan di _vertex shader_
4. _varying_ dari _vertex_ ke _fragment_ (ambil warna dari CPU, kirim ke _+_vertex shader_, lalu kirim ke _fragmen shader_)
5. Data pada _vertex shader_ tidak berpengaruh pada penampilan, hanya untuk mentransfer data
6. Setelah vertex shader selesai menyimpan lokasi vertices, saat ini belum terbentuk persegi utuh, selanjutnya rasterization yang dilakukan di GPU akan menginterpolasi (menghubungkan antar titik, mengisi area di dalam garis yang telah terhubung, mengatur warna fragment)
7. Jumlah fragment tergantung resolusi tampilan
8. _ambient color_ menyimpan informasi warna cahaya