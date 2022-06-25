Nama : Nelviana Dwi Lestari

Kelas : TI.20.D.1

NIM : 312010086

Matkul: Sistem Basis Data

1. Masuk ke databse nama_nim
![1](https://user-images.githubusercontent.com/101852867/175766334-3fd80bd2-7241-4d79-a2e6-8120283014c9.png)

- Lakukan proses backup dan recovery dengan sql dari database tugas seblumnya !
Backup
![2](https://user-images.githubusercontent.com/101852867/175766348-8f6b593d-709d-47cb-908b-9f246b5c177c.png)
Jika proses backup berhasil maka akan muncul file backuppada direktori C:\xampp\mysql\data\nama database
![3](https://user-images.githubusercontent.com/101852867/175766355-49723c8b-4cc5-401a-ba09-a511bba0873c.png)

![4](https://user-images.githubusercontent.com/101852867/175766357-8f7a9858-6ed7-4e66-8dc6-46d7ce92503d.png)
Recovery

Data yang telah di-backup dapat dikembalikan kapan saja bila diperlukan. Sintaks SQL yang digunakan adalah LOAD DATA INFILE. Perintah yang dijalankan adalah

LOAD DATA INFILE ‘Nama_backup_file’ INTO TABLE nama_table ;
![5](https://user-images.githubusercontent.com/101852867/175766390-2668183b-2f31-4e3c-bbc0-fdcf850147c8.png)
![6](https://user-images.githubusercontent.com/101852867/175766406-68eddeb5-46b9-416c-bbf6-51de48e0d2a3.png)

![7](https://user-images.githubusercontent.com/101852867/175766444-1e2cb413-c345-4241-9b0d-3c9e22785ba7.png)


00**7myqldump -u root -p nelviana_312010086>nelviana_312010086_backup.sql

