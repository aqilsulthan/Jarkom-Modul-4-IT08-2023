# Praktikum Jaringan Komputer 2023

**Kelompok IT08**

Nama Anggota Kelompok | NRP
------------------- | --------------		
Aqil Sulthan Yuki Maye | 5027211007
Adimas Defatra Bimasena | 5027211040

 Kelompok | Prefix IP 
----------|-----------
 IT08      | 192.237   

## Modul 4
Soal dikerjakan pada Cisco Packet Tracer dan GNS3 menggunakan metode perhitungan CLASSLESS yang berbeda.

Keterangan: Bila di CPT menggunakan VLSM, maka di GNS3 menggunakan CIDR atau sebaliknya

> Untuk pengerjaan soal, kami menggunakan Cisco Packet Tracer untuk metode VLSM dan GNS3 untuk metode CIDR

### Topologi
![Foto](./img/topologi.png)

### VLSM
- Topologi Subnetting VLSM

![Foto](./img/topologivlsm.png)

- Konfigurasi Subnet VLSM

Menentukan subnet berdasarkan rute, jumlah IP, netmask, dan length
![Foto](./img/subnetvlsm.png)

- Konfigurasi IP VLSM

Menentukan IP Network ID dan Broadcast tiap subnet serta netmasknya
![Foto](./img/ipvlsm.png)

- Tree VLSM

Membuat tree berdasarkan urutan IP VLSM dengan mask tertinggi
![Foto](./img/treevlsm.jpeg)

- Testing
Test ping konfigurasi VLSM

![Foto](./img/testpingvlsm.png)
![Foto](./img/statuspingvlsm.png)

### CIDR
- Topologi Subnetting CIDR

![Foto](./img/topologicidr.png)

- Konfigurasi Subnet CIDR

Menentukan subnet berdasarkan rute, jumlah IP, netmask, dan length
![Foto](./img/subnetcidr.png)

- Konfigurasi IP CIDR

Menentukan IP Network ID dan Broadcast tiap subnet serta netmasknya
![Foto](./img/ipcidr.png)

- Penggabungan Subnet

> Pengabungan Pertama (B)
![Foto](./img/b_cidr.png)

> Pengabungan Kedua (C)
![Foto](./img/c_cidr.png)

> Pengabungan Ketiga (D)
![Foto](./img/d_cidr.png)

> Pengabungan Keempat (E)
![Foto](./img/e_cidr.png)

> Pengabungan Kelima (F)
![Foto](./img/f_cidr.png)

> Pengabungan Keenam (G)
![Foto](./img/g_cidr.png)

> Pengabungan Ketujuh (H)
![Foto](./img/h_cidr.png)

> Pengabungan Kedelapan (I)
![Foto](./img/i_cidr.png)

- Tree CIDR

Membuat tree berdasarkan urutan IP CIDR dengan mask tertinggi
![Foto](./img/treecidr.jpeg)

- Konfigurasi CIDR GNS3
```
test
```





