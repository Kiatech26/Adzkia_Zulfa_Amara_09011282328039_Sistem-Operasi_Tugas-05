# Adzkia_Zulfa_Amara_09011282328039_Sistem-Operasi_Tugas-05


# Tugas05_Proses Input Output I/O

 # 1. Lihat daftar secara lengkap pada direktori aktif, belokkan tampilan standard output ke file baru. 
<img width="504" alt="Langkah 1" src="https://github.com/user-attachments/assets/1e986523-9fca-4da2-a1a9-2d7212dd1808">

## a. ls -la Menampilkan daftar file dan direktori secara lengkap, termasuk file tersembunyi.
## b. ls -la dan mengarahkan hasilnya ke file baru.txt.

# 2. Lihat daftar secara lengkap pada direktori /etc/paswd, belokkan tampilan standard outputke file baru tanpa menghapus file baru sebelumnya.

<img width="296" alt="langkah 2" src="https://github.com/user-attachments/assets/fa682a76-a133-4570-a01a-8c3aa5f4c164">

## a. ls -la /etc/passwd: Menampilkan informasi lengkap tentang file /etc/passwd.
## b. >> filebaru.txt: Mengarahkan output perintah ke file file_baru.txt, tanpa menghapus isi file jika file tersebut sudah ada. Output baru akan ditambahkan di akhir file.

# 3. Urutkan file baru dengan cara membelokkan standard input
<img width="338" alt="Langkah 3 " src="https://github.com/user-attachments/assets/4ab186fc-8c1a-43d6-aaa7-a79f136fa22b">

## a. sortPerintah untuk mengurutkan data secara alfabet.
## b. < file_baru.txt: Membelokkan standard input dari file file_baru.txt.
## c. > file_baru_sorted.txt: Mengarahkan hasil dari perintah sort ke file baru bernama file_baru_sorted.txt.


# 4 Urutkan file baru dengan cara membelokkan standard input dan standard output ke file baru.urut.

<img width="266" alt="Langkah 4" src="https://github.com/user-attachments/assets/ff5e6464-f683-408b-a3a8-8578e365cc81">

## a.sort: Perintah untuk mengurutkan isi file secara alfabetis.
## b.< file_baru.txt: Membelokkan standard input dari file file_baru.txt.
## c.> baru.urut: Mengarahkan standard output ke file baru yang bernama baru.urut.

# 5 Buatlah direktori latihan6 sebanyak 2 kali dan belokkan standard error ke file rmdirerror.txt. 

<img width="281" alt="Langkah 5" src="https://github.com/user-attachments/assets/8afae9ce-46ca-4fea-8c88-198ea661fe0e">

## a. mkdir latihan6 2> rmdirerror.txt: Membuat direktori latihan6 dan mengarahkan pesan kesalahan pertama ke rmdirerror.txt.
## b.mkdir latihan6 2>> rmdirerror.txt: Mencoba membuat direktori latihan6 lagi, menambahkan pesan kesalahan tambahan ke rmdirerror.txt.

# 6. Urutkan kalimat berikut :
## Jakarta
## Bandung
## Surabaya
## Padang
## Palembang
## Lampung
## Dengan menggunakan notasi here document (<@@@ …@@@) 

<img width="216" alt="langkah 6" src="https://github.com/user-attachments/assets/309812c3-62a8-4ced-8c14-058c9dd1717b">

## a. Tanda << digunakan untuk memberikan input langsung dalam perintah sort.
## b. Setelah <<@@@, daftar nama kota bisa dimasukkan.
## c. unruk menutup input dengan @@@.

# 7. Hitung jumlah baris, kata dan karakter dari file baru.urut dengan menggunakan filter dan tambahkan data tersebut ke file baru. 

<img width="208" alt="langkah 7" src="https://github.com/user-attachments/assets/ad44b6f6-2591-46c4-9678-62b0ee47c224">

<img width="326" alt="langkah 7_part 2" src="https://github.com/user-attachments/assets/90962085-d0f0-49b7-bae9-ae07877663d1">


## a. wc baru.urut: Menghitung jumlah baris, kata, dan karakter dari file baru.urut.
## b. Untuk menghitung jumlah baris di file baru.urut, gunakan opsi -l.
## c. Untuk menghitung jumlah kata di file, gunakan opsi -w.
## d. untuk menghitung jumlah karakter di file, gunakan opsi -c.
## e. >> filebaru.txt: Menambahkan hasil perhitungan ke file baru tanpa menimpa konten sebelumnya.


# 8. Gunakan perintah di bawah ini dan perhatikan hasilnya.
#    $ cat /etc/passwd | sort | pr –n | grep tty03
#    $ find /etc –print | head
#    $ head /etc/passwd | tail –5 | sort 

<img width="321" alt="langkah 8_part 1" src="https://github.com/user-attachments/assets/10edaefa-fc71-4f1c-8667-23ec75bff656">

<img width="281" alt="langkah 8_Part 2" src="https://github.com/user-attachments/assets/e77f045e-bfd8-4d45-8a4e-95b1408c93e8">

## a. cat /etc/passwd | sort | pr –n | grep tty03
## cat /etc/passwd: Menampilkan isi file /etc/passwd, yang berisi informasi tentang pengguna di sistem, sort: Mengurutkan baris-baris dari file tersebut.
## pr -n: Memberikan nomor baris pada output yang sudah diurutkan, grep tty03: Mencari baris yang mengandung teks "tty03" dalam output yang sudah diurutkan dan diberi nomor.**
## perintah ini akan menunjukkan baris-baris dari /etc/passwd yang berisi "tty03". Jika tidak ada baris yang mengandung "tty03", output akan kosong.
    
## find /etc –print | head 
## find /etc -print: Menemukan dan menampilkan semua file dan direktori di bawah /etc.
## head: Menampilkan 10 baris pertama dari hasil find.

# 9. Gunakan perintah $ who | cat | cat | sort | pr | head | cat | tail dan perhatikan hasilnya. 

<img width="334" alt="langkah_9" src="https://github.com/user-attachments/assets/f072fcd1-8792-4064-ac9a-aa07fdc7231c">

<img width="284" alt="langkah 9_part 2" src="https://github.com/user-attachments/assets/47913f4f-202b-45ae-8d7a-88b1d6dc2982">

<img width="240" alt="langkah 9 part 3" src="https://github.com/user-attachments/assets/582d6fbc-5356-42d8-be07-2197ec5e467d">

<img width="349" alt="latihan 9-part 4" src="https://github.com/user-attachments/assets/3b48f1b4-c598-4147-8598-d318ede35385">


# Artinya, pada tanggal 19 September 2024 pukul 03:47, ada seorang pengguna dengan nama "instalkia" yang sedang login melalui terminal "tty7".
# who | cat | cat:
# who menghasilkan daftar pengguna yang sedang login.
# cat pertama dan kedua tidak mengubah output, sehingga ini hanya menampilkan output dari who.
# sort:Mengurutkan daftar pengguna yang dihasilkan oleh who secara alfabetis.
# pr:Memformat output yang telah diurutkan. Biasanya ini akan menambahkan nomor halaman dan memformat output menjadi beberapa kolom, tergantung pada pengaturan default pr.
# head:Menampilkan 10 baris pertama dari output yang telah diformat oleh pr.
# cat:Mencetak output dari head ke standar output (tidak mengubah output).
# tail:Menampilkan 10 baris terakhir dari output yang dihasilkan oleh cat

