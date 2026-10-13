# Tugas-6

Nama : Patrya Rofi

NIM : 09011282530055

Kelas : SKU3A




VI. Tugas
1. Eksekusi seluruh profile yang ada :
   
a. Edit file profile /etc/profile dan tampilkan pesan sebagai berikut :
echo “Profile dari /etc/profile”

<img width="498" height="186" alt="1a" src="https://github.com/user-attachments/assets/38f60c0d-d51d-4dfb-b525-93bd693d246b" />



b. Asumsi nama anda stD02001, maka edit semua profile yang ada yaitu :

<img width="800" height="600" alt="1b" src="https://github.com/user-attachments/assets/0be56189-94e7-4662-915b-d4598770d951" />



Ganti nama /home/mahasiswa dengan nama anda sendiri. Pada setiap
file tersebut, cantumkan instruksi echo, misalnya pada /home/
mahasiswa/.bash_profile :
echo “Profile dari .bash_profile”
Lakukan hal yang sama untuk file lainnya, sesuaikan tampilan dengan nama file
yang bersangkutan.


c. Jalankan instruksi subtitute user, kemudian keluar dengan perintah exit sebagai
berikut:

<img width="800" height="600" alt="1c" src="https://github.com/user-attachments/assets/73ff237e-eacb-49ee-94a7-2b6b3c01a72c" />


2. Prompt String (PS)
   
a. Edit file .bash_profile, ganti prompt PS1 dengan ‘>’. Instruksi export diperlukan
dengan parameter nama variable tersebut, agar perubahan variable PS1 dikenal
oleh semua shell

<img width="800" height="600" alt="2a per" src="https://github.com/user-attachments/assets/985cd7bf-3e1b-498a-ab04-421c8cb81ea1" />


b. Eksperimen hasil PS1 :

<img width="487" height="141" alt="2a" src="https://github.com/user-attachments/assets/1bd89550-9254-4e80-b04a-8d143e4c1bb5" />


3. Logout

<img width="800" height="600" alt="3 tugas 6" src="https://github.com/user-attachments/assets/cc0420a9-808c-48f7-a7d9-7c023bff80de" />


4. Bash script
a. Buat 3 buah script p1.sh, p2.sh, p3.sh dengan isi masing-masing :
p1.sh
#! /bin/bash

<img width="800" height="600" alt="4 a 1" src="https://github.com/user-attachments/assets/0f0660f7-c709-4b40-8f1b-6a5f66f8fa2a" />


p2.sh
#! /bin/bash

<img width="800" height="600" alt="4 a 2" src="https://github.com/user-attachments/assets/e7f69573-940f-48bf-bf6a-1e0b11e1cb79" />


p3.sh
#! /bin/bash

<img width="800" height="600" alt="4 a 3" src="https://github.com/user-attachments/assets/312adaad-cb48-45f1-bf6c-2e9ad48c0aeb" />


b. Jalankan script tersebut sebagai berikut :
<img width="800" height="600" alt="4b1" src="https://github.com/user-attachments/assets/daf3eb2f-009f-47ac-a6ae-654c0ef8633a" />

<img width="800" height="600" alt="4b2" src="https://github.com/user-attachments/assets/6c83d474-9807-4e48-a442-9d6616a0363c" />

<img width="800" height="600" alt="42b3" src="https://github.com/user-attachments/assets/917f964f-a8aa-445d-94ca-69f623c95ab6" />

<img width="800" height="600" alt="4b4" src="https://github.com/user-attachments/assets/f3fcecae-5dfb-440b-b707-309c2c799364" />


5. Jobs
a. Buat shell-script yang melakukan loop dengan nama pwaktu.sh, setiap 10 detik,
kemudian menyimpan tanggal dan jam pada file hasil.

<img width="800" height="600" alt="5 tugas 6" src="https://github.com/user-attachments/assets/7ff208ae-8337-4880-891f-ccbec82bd376" />


b. Jalankan sebagai background; kemudian jalankan satu program (utilitas find) di
background sebagai berikut :

<img width="800" height="600" alt="5b" src="https://github.com/user-attachments/assets/d6f69617-eaf3-4b65-99c2-dfb229e76399" />


c. Jadikan program ke 1 sebagai foreground, tekan ^Z dan kembalikan program
tersebut ke background

<img width="800" height="600" alt="5c" src="https://github.com/user-attachments/assets/7c5d89ad-4a64-47bd-b1c5-2b0c879105fc" />


d. Stop program background dengan utilitas kill

<img width="800" height="600" alt="5d" src="https://github.com/user-attachments/assets/69d289c1-175b-45a5-91e7-4e67969414f9" />



6. History
a. Ganti nilai HISTSIZE dari 1000 menjadi 20

<img width="800" height="600" alt="6a1" src="https://github.com/user-attachments/assets/2a427807-571d-438c-8ff2-fc3bcfc869e0" />


b. Gunakan fasilitas history dengan mengedit instruksi baris ke 5 dari instruksi yang
terakhir dilakukan

<img width="800" height="600" alt="6b" src="https://github.com/user-attachments/assets/9be2fa93-46ab-4b38-a178-ecacbd7dd857" />


c. Ulangi instruksi yang terakhir. Gunakan juga ^P dan ^N untuk bernavigasi pada
history bufer

<img width="800" height="600" alt="6c" src="https://github.com/user-attachments/assets/d7ec46af-e14d-4e26-b4c6-82ddbd6ecf2f" />


d. Ulangi instruksi pada history bufer nomor 150


<img width="800" height="600" alt="6d" src="https://github.com/user-attachments/assets/727dad04-33fe-49af-9672-a0ef3833bff4" />


e. Ulangi instruksi dengan prefix “ls”

<img width="800" height="600" alt="6e" src="https://github.com/user-attachments/assets/d1d302b8-9e79-482d-8d67-22300dfc1c32" />


$ !150

e. Ulangi instruksi dengan prefix "ls"

$ !ls
