# UTS Web Programming 1 | Ega Sulanjana - TIF 22 CID

## Tentang repositori
Repositori ini berisikan file projek UTS dari mata kuliah web programming 1, dan dibuat untuk memenuhi UTS pada mata kuliah Web Programming 1
Projek website yang dibuat bertemakan toko online fashion. Website tersebut masih berupa website statis dan masih dalam pengembangan. Masih terdapat beberapa fungsional yang belum berjalan dan digantikan dengan tampilan "Segera datang".


## Alur kerja projek saya
Pada projek di repositori ini terdapat 3 folder di dalamnya, yaitu HTML, img dan JS. Pada folder HTML terdapat 9 file html, yaitu `index.html`, `login.html`, `register.html`, `landingpage.html`, `comingsoon.html`, `muslim-outfit.html`, `casual-outfit.html`, `vintage-outfit.html`, dan `streetwear-outfit.html`. Pada folder img hanya terdapat 1 file yaitu `arrowBack.png`, karena saya banyak menggunakan gambar dari browser. Pada folder JS hanya terdapat 1 file yaitu `script.js`, dan untuk beberapa script saya tambahkan di file .html nya. 

File `index.html` sebagai gerbang pertama bagi pengguna dan penguji untuk mengakses website ini. Konten di `index.html` terdapat 6 bagian didalamnya, yaitu promo, navbar, call to action (CTO), product collections, testimonial dan footer. Ke-6 bagian tersebut ditandai dengan tag komentar.

Pada file `register.html` hanya terdapat tag h1 sebagai header dan form sebagai media penampung data yang dimasukkan oleh pengguna dan atau penguji. Saya tambahkan tag script di bawah tag penutup body untuk logika pemrograman pada menu daftar. Singkatnya, ketika user dan atau penguji mendaftarkan akun di menu daftar, form akan di cek, ketika inputan form sesuai dengan ketentuan, maka akan muncul alert "Akun berhasil dibuat" dan diarahkan ke halaman `login.html`.  

Pada file `login.html` hanya terdapat tag h1 sebagai header dan form sebagai media penampung data yang dimasukkan oleh pengguna dan atau penguji. Saya tambahkan tag script di bawah tag penutup body untuk logika autentikasi pada menu masuk. Singkatnya, ketika user dan atau penguji memasukkan informasi akun, maka sistem akan mengecek apakah informasi yang dimasukkan oleh user dan atau penguji itu sesuai dengan informasi yang tersedia pada local storage user dan atau penguji? jika sesuai, maka user dan atau penguji diarahkan ke halaman `landingpage.html`, tetapi, jika tidak sesuai maka akan muncul alert "Maaf, ada inpoutan yang salah".

Pada file `landingpage.html` terdapat 6 bagian di dalamnya, yaitu promo, navbar, call to action (CTO), product collections, testimonial dan footer. Ke-6 bagian tersebut ditandai dengan tag komentar. Saya tambahkan tag script di bawah tag penutup body untuk menampilkan username yang user dan atau penguji masukkan ketika proses daftar akun di halaman `register.html` di bagian banner.

Pada file `comingsoon.html` hanya terdapat div yang menampung tag image sebagai object-cover, h1 dan p sebagai informasi bahwa halaman tersebut akan segera datang atau belum siap, dan tag a untuk mengarahkan user dan atau penguji ke halaman `landingpage.html`. 

Unjtuk file `muslim-outfit.html`, `casual-outfit.html`, `vintage-outfit.html`, dan `streetwear-outfit.html` memiliki kerangka yang sama, yang membedakan nya hanyalah data dan isiannya saja, seperti nama, gambar, dan harga. Untuk kerangkanya sendiri terdiri dari promo, product, dan footer.

##  Alat dan Bahan  
`Framework CSS: Tailwind`  
`Notification: SweetAlert2`   
`Storage: LocalStorage`  
`Icons: GoogleIcon` 
`tool: VSCode`
`image: browser dan unsplash.com`

## Catatan  
Gunakan koneksi internet untuk menjalankan proyek, karena proyek ini menggunakan CDN dan image dari browser!

## Pratinjau
### Halaman Pertama  
![Screenshot 2024-11-23 095031](https://github.com/user-attachments/assets/6bc4c84e-e218-478e-ad15-a8b6c04e00ec) 
  
### Tujuan ketika tombol "Belanja Sekarang!!" di klik
![Screenshot 2024-11-23 095059](https://github.com/user-attachments/assets/e7f0e362-e91e-4dd6-b7a2-3a809de4da75)

### Testimoni 
![Screenshot 2024-11-23 095111](https://github.com/user-attachments/assets/e22a8b9d-281c-469a-8112-ec9b1899e7eb)

### Daftar
![Screenshot 2024-11-23 095130](https://github.com/user-attachments/assets/9a7fe268-85e8-42e1-9f49-4f99f29c8e37)

### Tampilan ketika akun berhasil dibuat 
![Screenshot 2024-11-23 095215](https://github.com/user-attachments/assets/1662542b-2464-4906-9c9b-19f74ea9d0dc)

### Masuk  
![Screenshot 2024-11-23 121232](https://github.com/user-attachments/assets/754a0fce-7242-45b0-bbb2-c2acc8c4469d)

### Tampilan ketika terdapat kesalahan dalam input informasi akun, termasuk inputan kosong  
![Screenshot 2024-11-23 095230](https://github.com/user-attachments/assets/0202bf84-018b-49cb-9d34-83f3b5e6ae3e)

### Tampilan validasi akun berhasil
![Screenshot 2024-11-23 095254](https://github.com/user-attachments/assets/11bd1295-a491-4117-b59f-e01834a9990a)

### Halaman utama
![Screenshot 2024-11-23 095311](https://github.com/user-attachments/assets/16bf4d88-bb4e-4d01-8b95-da320ea96b26)

### Tujuan ketika tombol "Belanja Sekarang!!" di klik
![Screenshot 2024-11-23 095326](https://github.com/user-attachments/assets/90fc6ed5-5d49-402f-b04d-6b3716580593)

### Testimoni
![Screenshot 2024-11-23 095349](https://github.com/user-attachments/assets/34229b57-8f6a-451b-a834-0fd0bf169ea2)

### Segera datang
![Screenshot 2024-11-23 095407](https://github.com/user-attachments/assets/2c750068-7c7a-48d2-bf67-5507acdbf88c)

### Muslim outfit
![Screenshot 2024-11-23 095434](https://github.com/user-attachments/assets/6bd34dd1-a2be-4568-8c72-05287aea4660)

### Casual outfit
![Screenshot 2024-11-23 095449](https://github.com/user-attachments/assets/9362ae37-330b-47ab-9bc1-e6adeee94277)

### Vintage outfit
![Screenshot 2024-11-23 095500](https://github.com/user-attachments/assets/ee969afd-4dde-48aa-adab-6e36fdf9ccf9)

### Streetwear outfit
![Screenshot 2024-11-23 095515](https://github.com/user-attachments/assets/0e75bb6a-abf8-474d-9b39-ddf84f475022)

