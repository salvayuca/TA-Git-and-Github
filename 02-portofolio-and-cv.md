1. membuat sebuah folder kosong dengan namamu sendiri (__mkdir Salfa__)
2. membuat sebuah file dengan nama README.md, isi file tersebut dengan kalimat
    "Halo perkenalkan aku halaman utama"
    (__cd Salfa__
    __touch README.md__
    __nano README.md__)
3. insialisasi folder tersebut dengan Git, kemudian dokumentasikan menggunakan commit dengan pesan
    "Inisialisasi Git Repository"
    (__git config --global user.name "salvayuca"__
    __git config --global user.email salvayuca88@gmail.com__
    __git init__
    __git add .__
    __git commit -m "Inisialisasi Git Repository"__)
4. buat branch baru dengan nama cv, hal ini berguna agar histori kita tidak tercampur
    (__git branch -M cv__)
5. pindah branch kedalam cv, kemudian buat file dengan nama cv.txt dan isi file tersebut dengan kalimat:
    "Ini adalah file CV"
    (__git checkout -b cv__
    __touch cv.txt__
    __nano cv.txt__)
6. kemudian dokumentasikan menggunakan commit dengan pesan
    "Inisialisasi CV"
    (__git commit -m "Inisialisasi CV"__)
7. tambahkan 3 perusahaan yang akan kamu lamar, dan setiap menuliskan 1 nama perusahaan kamu harus melakukan dokumentasi menggunakan commit
    (__nano cv.txt__
    __git commit -m "menambahkan perusahaan pertama"__
    __nano cv.txt__
    __git commit -m "menambahkan perusahaan kedua"__
    __nano cv.txt__
    __git commit -m "menambahkan perusahaan ketiga"__)
8. kembali ke branch master
    (__git checkout -b master__)
9. ubah file README.md menjadi
    Halo perkenalkan aku halaman utama

    Ini adalah update pertama pada branch master
    (__nano README.md__)
10. jangan lupa untuk mendokumentasikannya menggunakan commit dengan pesan
    "update master pertama"
    (__git commit -m "update master pertama"__)
11. gabungkan branch cv kedalam branch master menggunakan perintah git merge
    (__git merge cv__)
12. unggah Git Repository tersebut kedalam GitHub
    (__git remote add origin https://github.com/salvayuca/portofolio-and-cv.git__
    __git push -u origin master__)
