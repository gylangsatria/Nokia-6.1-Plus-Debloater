# Nokia 6.1 Plus - Debloater
This Script is fork from https://github.com/thanuj10/Nokia-Debloater, 
A simple noob-friendly script that debloats your phone from the evenwell apps and soon, Google Apps.

## Mengenai Script Ini
Script ini adalah Fork dari https://github.com/thanuj10/Nokia-Debloater, saya coba kembangkan kembali dengan menambahkan beberapa aplikasi Bloatware yang hadir secara default di Nokia 6.1 Plus Region Indonesia (Model: TA-1116). 

##### Catatan Author (Di alih bahasa-kan dari bahasa Inggris). 
Author asli dari script ini mencoba untuk menghapus aplikasi bloatware dari ROM China, namun sayangnya aplikasi yang telah dihapus kembali ke posisi semula, tidak ada langkah pasti untuk menghapus aplikasi bloatware kecuali dengan melakukan Root dan menghapus dari Directory asalnya, sebelum menjalankan script ini, ada baiknya pengguna mengetahui bahwa menggunakan script ini bisa saja merusak salah satu fungsi pada perangkat yang pengguna gunakan. 

Jika perangkat mengalami kerusakan, fungsi tidak bekerja, atau ada masalah lainnya, pengguna bisa melakukan Factory Reset atau kembali ke pengaturan awal melalui Recovery Mode. 



##### Script untuk Linux dan Mac dapat dilihat pada halaman github berikut https://github.com/Sid127/Nokia-Debloater/releases


## Apa itu Evenwell dan kenapa pengguna harus memperhatikannya?
Evenwell/FiH adalah perusahaan yang berbasis di China. Secara khusus, mereka adalah anak perusahaan dari Grup Besar bernama Foxxconn yang memproduksi peralatan elektronik untuk dijual ke seluruh dunia. Grup Evenwell ini bisa dibilang merupakan mitra bisnis Nokia / HMD Global, dan mereka bertanggung jawab untuk membuat perangkat lunak pada ponsel Nokia (dalam kasus ini Nokia 6.1 Plus adalah salah satunya). Secara umum, perangkat Nokia generasi pertama dan kedua tidak memiliki bloatware, namun jika kamu perhatikan dan lihat kembali lebih dalam pada pengaturan (System App), kamu pasti akan menemukan aplikasi Evenwell ini.


## Apa yang aplikasi Evenwell ini kerjakan?

Aplikasi pada dasarnya, berfungsi untuk menjaga stabilitas sistem dan memperkuat daya tahan baterai di antara berbagai layanan / fitur lainnya. Namun setelah diperhatikan, aplikasi ini juga memiliki telemetri yang mengirim data ke perusahaan mereka.

Saya sudah membahas mengenai hal ini dihalaman blog saya https://www.blogsayugi.com/2020/11/cara-mengatasi-internet-lambat-di.html

**Dan karena itulah script ini dibuat, untuk meningkatkan privasi pengguna dan membuat system lebih baik dibandingkan sebelumnya.**


## Nokia seharusnya sudah berhenti untuk menggunakan Evenwell services/apps, dan berikut alasan kenapa kita harus menghapus aplikasi ini. 

1. Saya tidak ingin ada aplikasi yang telah dihentikan Nokia melakukan pengintaian history di sistem saya.
2. Aplikasi tersebut tidak seharusnya ada di perangkat saya sejak awal.

## Untuk menggunakan Script ini, kamu harus memiliki beberapa hal berikut:
1. Sebuah ponsel Nokia (dalam kasus ini adalah Nokia 6.1 Plus Region Indonesia (Model: TA-1116). 
2. ADB Fastboot Portable yang dapat kamu download pada halaman berikut : https://androidfilehost.com/?fid=6006931924117923181
3. Script Debloater ini. 
4. PC/Laptop dengan system operasi Windows 7 atau yang lebih baru. 



# Tutorial Penggunaan
> Aktifkan USB Debugging - 
1. Silahkan kamu masuk ke halaman Settings >
2. Masuk ke **System > About Phone > Build number**
3. Tekan **Build Number** 7 kali sampai kamu melihat pesan *You are now a developer*.
4. Selanjutnya, silahkan masuk ke **System > Advanced > Developer options > Enable USB Debugging**
5. Setelah semuanya disiapkan dan USB Debugging diaktifkan, silahkan kamu beralih ke PC yang sudah kamu siapkan. 

> Menyiapkan Script Debloater
>	Di PC Windows
1. Silahkan kamu download ADB Fastboot pada link diatas.
2. Extract seluruh isi dari file .zip dan simpan dalam folder bernama adb (***PASTIKAN SELURUH FILE YANG DI EXTRACT SUDAH LENGKAP DAN SESUAI DENGAN APA YANG ADA DI FILE .ZIP***)
3. Silahkan kamu download Script dari bagian Release. 
4. Masukkan Script pada folder adb yang telah dibuat pada langkah 2 sebelumnya.
5. Koneksikan Nokia 6.1 Plus kamu melalui kabel USB. 
6. Double click pada Script yang telah di download sebelumnya. 
7. Kamu mungkin akan mendapati pesan di Nokia 6.1 Plus kamu, silahkan klik always allow this PC dan selanjutnya klik Ok.


*Jika kamu pertama kali menjalankan script ini, kamu mungkinkan akan mendapati pesan error - *No devices/emulators found*, jika iya, pastikan kamu sudah melakukan langkah 7 diatas.



## F.A.Q

1. Perlukan melakukan Root dan melakukan Unlock Bootloader?
> Tidak

2. Apa yang didapatkan dengan script debloater ini?
> Privasi yang lebih baik, daya tahan battery yang lebih lama, dan peningkatan performa. 

3. Bisakah mengembalikan perubahan dari script ini?
> Bisa, dan ada beberapa opsi untuk melakukan hal tersebut. 
 - Menggunakan fitur Rebloated yang ada di Script
 - Reinstall aplikasi Rebloated yang telah dihapus. 
 - Factory Reset (paling direkomendasikan).

4. Apakah dengan melakukan debloated kita akan kehilangan data?
> Tidak, saya sudah coba dan pastikan sendiri. 

5. Kemungkinan perangkat akan rusak akibat script ini?
> Sangat, sangat jarang sekali. 

6. Cara menghapus secara keseluruhan?
> Sampai saat ini, sayangnya untuk menghapus file APK, kamu harus melakukan root dan menghapus file secara manual di /system/app atau /system/priv-app. 


## To-Do List pengembangan script ini. 
> Original Script
- [x] Implement a way to re-install the debloated apps
- [x] Add options to debloat google apps
- [x] Add options to debloat specific apps
- [x] Add options for rebooting to bootloader and recovery mode
- [x] Add option to turn off Duraspeed on Mediatek chipset based devices
- [x] Port script to Linux (thanks to @Sid127)
- [x] Combine Linux scripts into one script
- [x] Port script to MacOS

> Fork by Gylang
- [x] Fork dari https://github.com/thanuj10/Nokia-Debloater
- [x] Mengalih bahasa-kan Text Readme dengan penyesuaian untuk perangkat Nokia 6.1 Plus Region Indonesia (Model: TA-1116), untuk model Nokia lain bisa mengikuti sumber https://github.com/thanuj10/Nokia-Debloater
- [x] Menambahkan aplikasi Babe dan PicMix sebagai daftar aplikasi bloated yang akan dihapus. 
- [-] Sedang mencari aplikasi bloated lainnya. 



## Informasi mengenai hal ini bisa dilihat di

- https://dontkillmyapp.com/nokia
(**Alasan utama developer pertama membuat script ini**)

- https://nokiamob.net/2019/08/18/rumor-hmd-plans-to-remove-evenwell-software-from-all-nokia-devices/

- https://medium.com/@roundedeverett/who-is-nokia-cb24ecbc52a9
- https://community.phones.nokia.com/discussion/51246/tapping-into-android-pies-adaptive-battery-for-optimum-battery-performance
(**Pengumuman resmi bahwa Nokia telah menghapus dan menonaktifkan evenwell apps, tapi apakah iya? karena nyatanya aplikasi masih tetap ada!**)

- https://www.reddit.com/r/Nokia7Plus/comments/apql58/ok_i_have_to_admit_disabling_evenwell_power_apps/

- https://www.blogsayugi.com/2020/11/cara-mengatasi-internet-lambat-di.html
(**Saya sudah membahas mengenai masalah bloatware system yang melambatkan koneksi internet saya**)

#Thanks to 
- Thanuj10 for creating this Script - https://github.com/thanuj10/Nokia-Debloater
- Sid127 for Linux/Mac Version - https://github.com/Sid127/Nokia-Debloater/releases
- And other developer and Nokia Users. 


