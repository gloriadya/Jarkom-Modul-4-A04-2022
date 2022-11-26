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
   | ------ | --------- | ------- |
   | A1     | 1001      | /22     |
   | A2     | 251       | /24     |
   | A3     | 2         | /30     |
   | A4     | 2         | /30     |
   | A5     | 51        | /26     |
   | A6     | 121       | /25     |
   | A7     | 211       | /24     |
   | A8     | 2         | /30     |
   | A9     | 2         | /30     |
   | A10    | 2         | /30     |
   | A11    | 2         | /30     |
   | A12    | 501       | /23     |
   | A13    | 2         | /30     |
   | A14    | 2         | /30     |
   | A15    | 2         | /30     |
   | A16    | 271       | /23     |
   | A17    | 121       | /25     |
   | A18    | 71        | /25     |
   | Total  | 2617      | /20     |

3. Hitung pembagian IP subnetting dengan root netmask nya adalah /20 menggunakan pohon sebagai berikut.

4. Didapatkan table network id, netmask, broadcass address sebagai berikut

   | Subnet | Network ID  | Netmask         | Broadcass Address |
   | ------ | ----------- | --------------- | ----------------- |
   | A1     | 10.1.0.0    | 255.255.252.0   | 10.1.3.255        |
   | A2     | 10.1.8.0    | 255.255.255.0   | 10.1.8.255        |
   | A3     | 10.1.11.192 | 255.255.255.252 | 10.1.11.195       |
   | A4     | 10.1.11.196 | 255.255.255.252 | 10.1.11.199       |
   | A5     | 10.1.11.128 | 255.255.255.192 | 10.1.11.191       |
   | A6     | 10.1.10.0   | 255.255.255.128 | 10.1.10.127       |
   | A7     | 10.1.9.0    | 255.255.255.0   | 10.1.9.255        |
   | A8     | 10.1.11.200 | 255.255.255.252 | 10.1.11.203       |
   | A9     | 10.1.11.204 | 255.255.255.252 | 10.1.11.207       |
   | A10    | 10.1.11.208 | 255.255.255.252 | 10.1.11.211       |
   | A11    | 10.1.11.212 | 255.255.255.252 | 10.1.11.215       |
   | A12    | 10.1.4.0    | 255.255.254.0   | 10.1.5.255        |
   | A13    | 10.1.11.216 | 255.255.255.252 | 10.1.11.219       |
   | A14    | 10.1.11.220 | 255.255.255.252 | 10.1.11.223       |
   | A15    | 10.1.11.224 | 255.255.255.252 | 10.1.11.227       |
   | A16    | 10.1.6.0    | 255.255.254.0   | 10.1.7.255        |
   | A17    | 10.1.10.128 | 255.255.255.128 | 10.1.10.255       |
   | A18    | 10.1.11.0   | 255.255.255.128 | 10.1.11.127       |
