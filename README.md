# Jarkom Modul 4 A04 2022

**Nama Anggota Kelompok**

- Samuel ()
- Mohamad Kholid Bughowi (5025201253)
- Gloria Dyah Pramesti

## Soal

Diminta untuk membuat topologi pada CPT dan GNS3 seperti berikut
![soal shift 4 1](https://user-images.githubusercontent.com/49820990/203488778-e0acac24-3222-4ccd-9570-4cc50669c243.png)

### CPT dengan VLSM

1. Menentukan jumlah subnet
   ![soal modul 4 jarkom drawio (1)](https://user-images.githubusercontent.com/49820990/203488956-0488364a-fbb8-4bbb-b873-bac996f28311.png)
   Dari gambar tersebut diperoleh sebanyak 18 subnet dari A1 sampai A18

2. Hitung jumlah alamat IP yang dibutuhkan oleh tiap subnet beserta netmask nya
   | Subnet | Jumlah IP | Netmask |
   |--------|-----------|---------|
   |A1 |1001 | /22 |
   | A2 | 251|/24 |
   | A3|2 |/30|
   | A4|2 | /30|
   | A5| 51| /26|
   | A6|121| /25|
   | A7|211| /24|
   | A8|2| /30|
   | A9|2 | /30|
   | A10|2 | /30|
   | A11| 2| /30|
   | A12|501| /23|
   | A13|2| /30|
   | A14|2| /30|
   | A15|2| /30|
   | A16|271| /23|
   | A17|121| /25|
   | A18|71| /25|
   |Total|2617|/20|

3. Hitung pembagian IP subnetting dengan root netmask nya adalah /20 menggunakan pohon sebagai berikut.
