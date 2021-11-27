# Jarkom-Modul-4-B01-2021

Kelompok B01

|      NRP       |                  Nama                   |
| :------------: | :-------------------------------------: |
| 05111940000120 |       Jonathan Timothy Siregar          |
| 05111940000134 |      Muhammad Fikri Sandi Pratama       |
| 05111940000150 |         Mohammad Thoriq Huda            |

# CPT - VLSM

- Pertama - tama, bagi topologi yang sudah diberikan ke dalam beberapa subnet kecil sesuai kebutuhan yang di inginkan :
- 

![VLSM-1](https://user-images.githubusercontent.com/55092974/143673754-2c313a93-1a69-407d-a6e7-0d37bb5a57f1.JPG)

- Kemudian tentukan jumlah IP yang diperlukan beserta dengan netmasknya untuk setiap subnet yang ada :

|  Subnet   | Jumlah IP | Netmask |
| :-------: | :-------: | :-----: |
|    A1     |    101    |   /25   |
|    A2     |    701    |   /22   |
|    A3     |     2     |   /30   |
|    A4     |   2021    |   /31   |
|    A5     |   1001    |   /22   |
|    A6     |    2      |   /30   |
|    A7     |   521     |   /22   |
|    A8     |    252    |   /24   |
|    A9     |     2     |   /30   |
|    A10    |     2     |   /30   |
|    A11    |    721    |   /22   |
|    A12    |    502    |   /23   |
|    A13    |    13     |   /28   |
|    A14    |    2      |   /30   |
|    A15    |    2      |   /30   |
| **Total** | **5845**  | **/19** |

- Dari data di atas, Tersusun tree subnet VLSM seperti berikut :

![WhatsApp Image 2021-11-23 at 6 18 25 PM](https://user-images.githubusercontent.com/55092974/143674968-ee631e30-83d2-4139-9e6d-9abb16fe5b63.jpeg)

- Dengan demikian, didapatkan NID untuk masing-masing subnet sebagai berikut :


|  Subnet   | Jumlah IP | Netmask |      NID       |
| :-------: | :-------: | :-----: | :-----------:  |
|    A1     |    101    |   /25   |  192.177.0.128 |
|    A2     |    701    |   /22   |  192.177.12.0  |
|    A3     |     2     |   /30   |  192.177.0.0   |
|    A4     |   2021    |   /21   |  192.177.24.0  |
|    A5     |   1001    |   /22   |  192.177.16.0  |
|    A6     |     2     |   /30   |  192.177.0.4   |
|    A7     |    521    |   /22   |  192.177.4.0   |
|    A8     |    252    |   /24   |  192.177.1.0   |
|    A9     |    2      |   /30   |  192.177.0.8   |
|    A10    |    2      |   /30   |  192.177.0.12  |
|    A11    |    721    |   /22   |  192.177.8.0   |
|    A12    |    502    |   /23   |  192.177.2.0   |
|    A13    |     13    |   /28   |  192.177.0.32  |
|    A14    |     2     |   /30   |  192.177.0.16  |
|    A15    |     2     |   /30   |  192.177.0.20  |
| **Total** | **5845**  | **/19** |


Pada CPT, buat topologi seperti berikut :

![image](https://user-images.githubusercontent.com/90582800/143684888-c26ea16b-61ec-4e70-b5c8-9412c50693e8.png)



Pada setiap router, dimasukkan IP dan netmask sesuai dengan subnet yang dituju :
<br><br>

![image](https://user-images.githubusercontent.com/90582800/143684968-6779d442-c3e5-4c64-8cce-c5e93d722681.png)


<br><br><br><br>

Pada setiap client dan server, dimasukkan IP, netmask, dan gateway pada menu IP configuration di bar desktop sesuai kebutuhan :
<br><br>

![image](https://user-images.githubusercontent.com/90582800/143685030-6d4d5fd9-2d04-4ea3-a63b-d54dbcfcc192.png)
<br><br><br><br>



Untuk setiap router, dilakukan routing sesuai dengan subnet yang dihubungkan :
<br><br>

![image](https://user-images.githubusercontent.com/90582800/143685102-c7de08e6-44db-4ac3-be30-73a3d5c7fd8a.png)

<br><br><br><br>


Dilakukan testing untuk melihat apakah routing telah benar berjalan :
<br><br>

![image](https://user-images.githubusercontent.com/90582800/143685175-dd0f8561-31e6-48f8-83ac-3883089f844a.png)

<br><br><br><br>




# GNS3 - CIDR

- Pembagian subnet di CIDR berbeda dengan VLSM dimana pembagiannya dimulai dari yang terjauh dari cloud agar mempermudah routing sehingga didapatkan subnet sebagai berikut :
![a](https://user-images.githubusercontent.com/90582800/143685451-b5737cc6-75b9-4311-a456-b1ea0d0c4a10.jpg)
![b](https://user-images.githubusercontent.com/90582800/143685456-ccffddef-4151-4a93-9f2c-04c00f150596.jpg)
![c](https://user-images.githubusercontent.com/90582800/143685458-d22d12de-4223-4995-ab7b-45b22233ce84.jpg)
![d](https://user-images.githubusercontent.com/90582800/143685460-c3e1d910-7744-4fae-93f1-f5805c62e5cd.jpg)
![e](https://user-images.githubusercontent.com/90582800/143685461-999b9cba-a44e-4e40-9070-360cc705f05c.jpg)
![f](https://user-images.githubusercontent.com/90582800/143685465-10615a56-65ff-48c1-907c-262b9afc11cb.jpg)
![g](https://user-images.githubusercontent.com/90582800/143685467-84d448d7-12e3-49ed-ac21-623dfa613387.jpg)
![h](https://user-images.githubusercontent.com/90582800/143685502-6312118c-5d22-4e93-a379-431ab470f914.jpg)


- Dari gambar diatas dapat kita buat tree subnet CIDR seperti berikut :

![Picture1](https://user-images.githubusercontent.com/90582800/143685586-ccbee67e-2ce1-47c7-87f9-8d89d06af17b.jpg)


| Subnet |  Netmask  |    IP        |  Subnet Mask  |
| :----: | :-------: | :----------: | :-----------: |
|   A1   |    /25    |   192.178.8.0    | 255.255.255.128 |
|   A2   |   /22     |   192.178.32.0   | 255.255.252.0   |
|   A3   |    /30    |   192.178.16.0   | 255.255.255.252 |
|   A4   |     /21   |   192.178.0.0    | 255.255.248.0   |
|   A5   |     /22   |   192.178.128.0  | 255.255.252.0   |
|   A6   |    /30    |   192.178.64.0   | 255.255.255.252 |
|   A7   |   /22     |   192.177.36.0   | 255.255.252.0   |
|   A8   |    /24    |   192.177.4.0    | 255.255.255.0   |
|   A9   |    /30    |   192.177.64.0   | 255.255.255.252 |
|  A10   |    /30    |   192.177.16.10  | 255.255.255.252 |
|  A11   |    /22    |   192.177.0.0    | 255.255.252.0   |
|  A12   |     /23   |   192.177.32.0   | 255.255.252.4   |
|  A13   |     /28   |   192.177.34.0   | 255.255.255.240 |
|  A14   |    /30    |   192.177.8.0    | 255.255.252.252 |
|  A15   |    /30    |   192.177.128.0  | 255.255.252.252 |

- Kemudian buat topologi pada GNS3 seperti berikut :

![image](https://user-images.githubusercontent.com/90582800/143684490-9346709f-b43f-41a0-8c4b-4ed4672cc347.png)

Pada GNS3, dimasukkan konfigurasi seperti berikut :


#### Foosha


```
auto eth0
iface eth0 inet dhcp

auto eth1
iface eth1 inet static
	address 192.177.16.1
	netmask 255.255.254.0

auto eth2
iface eth2 inet static
	address 192.177.0.5
	netmask 255.255.255.252

auto eth3
iface eth3 inet static
	address 192.177.0.9
	netmask 255.255.255.252

auto eth4
iface eth4 inet static
	address 192.177.0.21
	netmask 255.255.255.252
```



#### Guanhao

```
auto eth0
iface eth0 inet static
	address 192.177.0.10
	netmask 255.255.255.252
	

auto eth1
iface eth1 inet static
	address 192.177.4.1
	netmask 255.255.252.0
	

auto eth2
iface eth2 inet static
	address 192.177.2.1
	netmask 255.255.254.0
	gateway 192.177.2.2

auto eth3
iface eth3 inet static
	address 192.177.0.13
	netmask 255.255.255.252
```



#### Alabasta

```
auto eth0
iface eth0 inet static
	address 192.181.128.2
	netmask 255.255.254.0
	gateway 192.181.128.1

auto eth1
iface eth1 inet static
	address 192.181.130.1
	netmask 255.255.255.240
```




#### Oimo

```
auto eth0
iface eth0 inet static
	address 192.177.0.14
	netmask 255.255.255.252
	gateway 192.177.0.13

auto eth1
iface eth1 inet static
	address 192.177.0.17
	netmask 255.255.255.252

auto eth2
iface eth2 inet static
	address 192.177.1.1
	netmask 255.255.255.0
```



#### Seastone

```
auto eth0
iface eth0 inet static
	address 192.177.1.2
	netmask 255.255.255.0
	gateway 192.177.1.1

auto eth1
iface eth1 inet static
	address 192.177.8.1
	netmask 255.255.252.0
```



#### Water7


```
auto eth0
iface eth0 inet static
	address 192.177.0.6
	netmask 255.255.255.252
	gateway 192.177.0.5

auto eth1
iface eth1 inet static
	address 192.177.0.1
	netmask 255.255.252.252

auto eth2
iface eth2 inet static
	address 192.177.12.1
	netmask 255.255.255.0
```



#### Pucci

```
auto eth0
iface eth0 inet static
	address 192.177.0.2
	netmask 255.255.255.252
	gateway 192.177.0.1

auto eth1
iface eth1 inet static
	address 192.177.0.129
	netmask 255.255.255.128

auto eth2
iface eth2 inet static
	address 192.177.24.1
	netmask 255.255.248.0
```


Setelah itu dilakukan routing seperti contoh di bawah :

#### Foosha

```
#A1	
route add -net 192.177.0.128 netmask 255.255.255.128 gw 192.177.0.6

#A2
route add -net 192.177.12.0 netmask 255.255.252.0 gw 192.177.0.6
.
.
.
```

Setelah routing, dimasukkan masukan berikut :

Untuk semua Router :
```
iptables -t nat -A POSTROUTING -o eth0 -j MASQUERADE -s 192.177.0.0/16
```

Dan untuk semua node :
```
echo nameserver 192.177.122.1 > /etc/resolv.conf
```
