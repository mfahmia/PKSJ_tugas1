# PKSJ_tugas1

## Anggota:
* I Made Fandy Aditya Wirana    5114100026
* Muhammad Fahmi Abdurrahman    5114100028
* I Gede Putu Nobby Aswi Phala  5114100048

## Pendahuluan

  Laporan ini berisi uji penetrasi server. OS server yang digunakan yaitu Ubuntu Server 16.04.3 dan OS penyerang yang digunakan yaitu Kali Linux 2017.1. Tools yang digunakan untuk menyerang yaitu Ncrack, Hydra, dan Medusa. Dilakukan 2 kali uji penetrasi, penetrasi pertama server hanya diinstall OpenSSH, penetrasi kedua server terinstall fail2ban.
  
## Dasar Teori

  * ### Ubuntu Server
    Ubuntu Server Edition mendukung arsitektur Intel x86 dan AMD64. Edisi server menyediakan fitur seperti file/print services, web hosting, email hosting, dll. Ada beberapa perbedaan antara edisi server dan edisi desktop walaupun keduanya menggunakan repositori apt yang sama. Perbedaan utamanya adalah, pada edisi server X window environment tidak diinstall scara standar, walaupun antarmuka grafik dapat diinstall secara manual seperti Ubuntu desktop. CD Ubuntu Server Edition juga memiliki pilihan untuk menginstall Ubuntu Enterprise Cloud.
    
  * ### Kali Linux
    Kali Linux adalah distribusi Linux berbasis Debian yang ditujukan untuk uji penetrasi dan pengecekan keamanan. Kali memiliki ratusan tools yang disematkan untuk menjalankan berbagai task yang berkaitan dengan keamanan, seperti uji penetrasi, forensik digital, dan *Reverse Engineering*. Kali Linux dikembangkan oleh Offensive Security, perusahaan yang berkembang di bidang keamanan informasi.
    
  * ### Ncrack
    Ncrack adalah alat cracking otentikasi jaringan berkecepatan tinggi. Ini dibangun untuk membantu perusahaan mengamankan jaringan mereka dengan secara proaktif menguji semua host dan perangkat jaringan mereka dengan kata kunci yang buruk. Profesional keamanan juga mengandalkan Ncrack saat mengaudit klien mereka. Ncrack dirancang menggunakan pendekatan modular, sintaks baris perintah yang mirip dengan Nmap dan mesin dinamis yang dapat menyesuaikan perilakunya berdasarkan umpan balik jaringan. Ini memungkinkan dilakukannya audit berskala besar yang cepat namun dapat diandalkan dari beberapa host.
    
    Fitur Ncrack mencakup antarmuka yang sangat fleksibel yang memberi pengguna kontrol penuh atas operasi jaringan, memungkinkan serangan bruteforcing yang sangat canggih, template waktu untuk kemudahan penggunaan, interaksi runtime yang mirip dengan Nmap dan banyak lagi. Protokol yang didukung meliputi RDP, SSH, HTTP (S), SMB, POP3 (S), VNC, FTP, SIP, Redis, PostgreSQL, MySQL, dan Telnet.
   
  * ### THC Hydra
    Sebuah tools crack yang semakin unggul dalam hal exploit dan THC-Hydra salah satu yang sangat cepat meretas jaringan logon cracker yang mendukung banyak layanan yang berbeda. Lihat fitur dan layanan cakupan halaman - termasuk. perbandingan kecepatan terhadap ncrack dan medusa.
    
    Tools ini mendukung Asterisk, AFP, Cisco AAA, Cisco auth, Cisco, CVS, Firebird, FTP, HTTP-FORM-GET, HTTP-FORM-POST, HTTP GET, HTTP-KEPALA, HTTP-PROXY, HTTPS-FORM-GET, HTTPS-FORM-POST, HTTPS-GET, HTTP-Proxy, ICQ, IMAP, IRC, LDAP, MS-SQL, MYSQL, NCP, NNTP, Oracle Listener, Oracle SID, Oracle, PCNFS, POP3, POSTGRES, RDP, rexec, rlogin, rsh, S7-300, SAP/R3,  SIP, SMB, SMTP, SMTP Enum, SNMP, Socks5, SSH (v1 dan v2), Subversion,TeamSpeak (TS2), Telnet, VMware-Auth, VNC dan XMPP.
    
  * ### Medusa
    Medusa dimaksudkan untuk menjadi cepat, massal paralel, modular, Login brute-pompa kecil. Tujuannya adalah untuk mendukung banyak layanan yang memungkinkan otentikasi remote mungkin. Penulis menganggap item sebagai beberapa fitur kunci dari aplikasi ini sebagai berikut:
    
    * Thread based parallel testing
    * Flexible user input
    * Modular Design
    
    Medusa adalah alat baris perintah, sehingga kamu perlu belajar perintah sebelum menggunakan alat ini. Efisiensi dari alat tergantung pada konektivitas jaringan. Pada sistem lokal, dapat menguji 2000 password per menit.
  
## Instalasi Ubuntu Server


