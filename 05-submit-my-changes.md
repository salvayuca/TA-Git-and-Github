1. Fork repository GitHub https://github.com/impactbyte/tech4impact-students-bio.git menggunakan akun Github kamu
2. Clone remote repository dari hasil fork tersebut. Jangan clone dari repository originalnya.
    (__git clone https://github.com/salvayuca/tech4impact-students-bio.git__
    __cd tech4impact-students-bio__
    __git remote -v__)
3. Buatlah branch baru dengan nama lengkap kamu. Misalnya david-winalda. Jangan melakukan perubahan pada branch master.
    (__git branch Salfa-Ayu-Alecia__)
4. Checkout ke dalam branch tersebut yang telah kamu buat
    (__git checkout Salfa-Ayu-Alecia__)
5. Buatlah 1 file format .md dengan nama lengkap kamu. Contoh davidwinalda.md
    (__nano salfa.md__)
6. Isi file tersebut davidwinalda.md dengan konten di bawah ini:
    Nama Lengkap: David Winalda
    Umur: 27
    Pesan yang ingin disampaikan: Semangat untuk kamu yang disana sedang berjuang
7. Masukkan file .md tersebut ke dalam staging area
    (__git add .__)
8. Commit dengan memberikan pesan nama file .md kamu
    (__git commit . -m "add salfa.md"__)
9. Merge branch yang telah kamu buat ke dalam branch master
    (__git checkout master__
    __git merge Salfa Ayu Alecia__)
10. Push ke dalam branch master
    (__git push -u origin master__)
11. Lakukan pull request dari GitHub Repository yang telah kamu fork untuk digabungkan ke dalam branch master pada GitHub Repository aslinya.
