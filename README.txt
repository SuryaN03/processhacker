TRANSLATE INDONESIA


Process Hacker adalah penampil proses sumber terbuka dan gratis yang kuat. 

## Mulai Cukup jalankan ProcessHacker.exe untuk memulai Process Hacker. 
Ada dua versi, 32-bit (x86) dan 64-bit (x64). 
Jika Anda tidak yakin yang mana versi yang akan digunakan, buka Control Panel > System dan centang "System ketik". 
Anda tidak dapat menjalankan Peretas Proses versi 32-bit pada a sistem 64-bit dan berharap untuk bekerja dengan benar, 
tidak seperti program lain. ## Persyaratan sistem Windows 7 atau lebih tinggi, 32-bit atau 64-bit. 


## Pengaturan 
Jika Anda menjalankan Process Hacker dari drive USB, Anda mungkin ingin simpan juga pengaturan Process Hacker di sana. 
Untuk melakukan ini, buat file kosong bernama "ProcessHacker.exe.settings.xml" di tempat yang sama direktori sebagai ProcessHacker.exe. 
Anda dapat melakukan ini menggunakan Windows Explorer: 
1. Pastikan "Sembunyikan ekstensi untuk jenis file yang dikenal" 
tidak dicentang Alat > Opsi folder > Lihat. 
2. Klik kanan di folder dan pilih New > Text Document. 
3. Ganti nama file menjadi ProcessHacker.exe.settings.xml (hapus ".txt" perpanjangan). 


## Plugin Plugin dapat dikonfigurasi 
dari Hacker > Plugins. Jika Anda mengalami crash yang melibatkan plugin, 
pastikan mereka up to date. Plugin ExtendedTools hanya tersedia untuk Windows Vista dan di atas. Informasi Disk 
dan Jaringan yang disediakan oleh plugin ini adalah hanya tersedia saat menjalankan Process Hacker dengan administratif hak. 


## KProcessHacker Process Hacker 
menggunakan driver mode kernel, KProcessHacker, untuk membantu dengan fungsi tertentu. Ini termasuk: 
* Menangkap jejak tumpukan mode kernel 
* Menangani proses pencacahan lebih efisien 
* Mengambil nama untuk pegangan file 
* Mengambil nama untuk objek EtwRegistration 
* Mengatur atribut pegangan Perhatikan bahwa secara default, KProcessHacker hanya mengizinkan koneksi dari proses dengan SeDebugPrivilege. 
Untuk mengizinkan Peretas Proses menampilkan detail untuk semua proses saat tidak berjalan sebagai administrator: 
1. Di Peninjau Suntingan Registri, navigasikan ke: HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Services\KProcessHacker3 
2. Di bawah kunci ini, buat kunci bernama Parameter jika tidak ada. 
3. Buat nilai DWORD bernama SecurityLevel dan atur ke 2. 
Jika Anda tidak menggunakan build resmi, Anda mungkin perlu menyetelnya ke 0. 4. 
Mulai ulang layanan KProcessHacker3 (sc stop KProcessHacker3, sc mulai KProcessHacker3).

gudluck !



teks indonesia

