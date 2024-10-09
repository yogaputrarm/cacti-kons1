<h2 align="center">Konfigurasi Cacti for Debian</h2>
بِسْمِ اللَّهِ الرَّحْمَنِ الرَّحِيْم

## Bahan
- VM OS Debian 

## Penggunaan 

- Masuk ke Cacti menggunakan browser dengan IP yang server kalian dapatkan
- Buat satu device untuk dilakukan monitoring 
- Pada menu Create, kemudian pilih New Device
- Masukkan Hostname dengan IP server cacti kalian
- Masukkan Nama server kalian pada kolom Description
- Pada kolom SNMP version pilih version 1
- Kemudian klik Create pada pojok kanan bawah
- Jika terdapat error pada SNMP, lakukan perubahan ip pada snmp dengan perintah:
  ```
  nano /etc/snmp/snmpd.conf
  ```
- Jika sudah ditambahkan kemudian lakukan restart SNMP, kemudian lakukan reboot pada server kalian
- Lakukan refresh pada server di cacti kalian 
