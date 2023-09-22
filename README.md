# Jarkom-Modul-1-A19-2023

# Kelompok F08 :
| Nama | NRP |
| ---------------------- | ---------- |
| Nayya Kamila Putri Y | 5025211183 |
| Javier Nararya Aqsa Setiyono | 5025211245 |

## No 1
User melakukan berbagai aktivitas dengan menggunakan protokol FTP. Salah satunya adalah mengunggah suatu file.

a. Berapakah sequence number (raw) pada packet yang menunjukkan aktivitas tersebut? 

b. Berapakah acknowledge number (raw) pada packet yang menunjukkan aktivitas tersebut? 

c. Berapakah sequence number (raw) pada packet yang menunjukkan response dari aktivitas tersebut?

d. Berapakah acknowledge number (raw) pada packet yang menunjukkan response dari aktivitas tersebut?

![AB](img/no1.png)

![AB2](img/ab.png)

Kita dapat memeriksa protokol FTP untuk melihat nomor urutan (sequence number) dan nomor akui (acknowledge number). Pada poin a, kita diminta untuk menjawab apa nomor urutan (sequence number) (raw) pada paket, dan jawabannya adalah 258040667. Kemudian pada poin b, kita diminta untuk menjawab nomor akui (acknowledge number) (raw) pada paket, dan jawabannya adalah 1044861039.

![CD](img/cd.png)

Setelah itu, kita perlu mencari respons dari aktivitas tersebut, yaitu angka setelah 147, yang adalah 149. Dengan pertanyaan yang sama seperti sebelumnya, tetapi kali ini adalah respons, pada poin c dan d, jawabannya adalah 1044861039 dan 258040696 masing-masing.

## No 2
Sebutkan web server yang digunakan pada portal praktikum Jaringan Komputer!
```
http.server
```

Kita dapat memeriksa alamat IP, kemudian kita periksa pada informasi yang memiliki (teks/html). Pada paket tersebut, kita periksa Protokol Transfer Hiperteks dan kita mendapatkan nama servernya, yaitu gunicorn.

![no2](img/no2.png)

## No 3
Dapin sedang belajar analisis jaringan. Bantulah Dapin untuk mengerjakan soal berikut:

a. Berapa banyak paket yang tercapture dengan IP source maupun destination address adalah 239.255.255.250 dengan port 3702? 
b. Protokol layer transport apa yang digunakan?

Menggunakan query
```
ip.host == 239.255.255.250 and udp.port == 3702
```

![no3](img/no3.png)

Di foto terlihat bahwa ada sebanyak 21 paket yang menggunakan protokol layer transport UDP

## No 4

## No 5

## No 6

## No 7
Berapa jumlah packet yang menuju IP 184.87.193.88?

Menggunakan query
```
ip.dst == 184.87.193.88
```
Dapat ditemukan ada 6 packet
![no7](img/no7.png)

## No 8
Berikan kueri filter sehingga wireshark hanya mengambil semua protokol paket yang menuju port 80! (Jika terdapat lebih dari 1 port, maka urutkan sesuai dengan abjad)

Menggunakan query
```
tcp.dstport == 80 || udp.dstport == 80
```
Karena kita perlu mencari port tujuan dari koneksi TCP atau UDP

![no8](img/no8.png)

## No 9

# No 10
