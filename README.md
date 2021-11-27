# Jarkom-Modul-4-B01-2021

Kelompok B01

|      NRP       |                  Nama                   |
| :------------: | :-------------------------------------: |
| 05111940000120 |       Jonathan Timothy Siregar          |
| 05111940000134 |      Muhammad Fikri Sandi Pratama       |
| 05111940000150 |         Mohammad Thoriq Huda            |

# CPT - VLSM

- Pertama - tama, bagi topologi yang sudah diberikan ke dalam beberapa subnet kecil sesuai kebutuhan yang di inginkan :

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


