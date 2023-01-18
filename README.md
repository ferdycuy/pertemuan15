# pertemuan15

-  PIP merupakan package manager untuk mengelola package dan
modul pada python. 
-  Dengan menggunakan PIP, kita dapat menggunakan library yang
tersedia bebas dari direktory package library python.
-  Untuk dapat menggunakan PIP, perlu diinstall terlebih dahulu, silakan
kunjungi tautan berikut untuk proses instalasinya:[https://pypi.org/project/pip]

-  pertama kalian menginstall package > "pip install nama_package"
 
![Screenshot (130)](https://user-images.githubusercontent.com/115714443/213196827-47f7792e-8123-4262-b974-f4d819b24ee2.png)

-  pip install beautifulsoup4

![Screenshot (131)](https://user-images.githubusercontent.com/115714443/213197196-82e53b1c-e6c2-4139-b6b9-c01c71d62b58.png)

- pip list > untuk menampilkan daftar package yang terinstall

![Screenshot (133)](https://user-images.githubusercontent.com/115714443/213197398-0649b935-6087-49d5-9d11-1e122efa58cf.png)

## Web Scraping Menggunakan Python

![Screenshot (122)](https://user-images.githubusercontent.com/115714443/213197716-0cd53701-88fc-496f-9bc4-98781fd1590d.png)

### Penjelasan
- pertama,!pip install pandas digunakan untuk menginstall package pandas di python. Package pandas digunakan untuk memanipulasi data dalam bentuk tabel (dataframe) dan digunakan untuk data analysis. Fungsi dari package pandas sangat luas, seperti melakukan operasi pada data, mengimport dan mengeksport data dari berbagai format, dan lainnya.

- lalu,!pip install requests digunakan untuk menginstall package requests di python. Package requests digunakan untuk melakukan HTTP request dari python.

- Kemudian,!pip install BeautifulSoup4 digunakan untuk menginstall package BeautifulSoup4 di python. Package BeautifulSoup4 digunakan untuk parsing dan mengelola data dari HTML atau XML.

- dan,import pandas as pd digunakan untuk mengimport library pandas dan menyebutnya sebagai pd. Library pandas digunakan untuk memanipulasi data dalam bentuk tabel (dataframe) dan digunakan untuk data analysis.

- serta,from bs4 import BeautifulSoup digunakan untuk mengimport class BeautifulSoup dari package BeautifulSoup4. Class BeautifulSoup digunakan untuk mengelola dan mengolah data dari HTML atau XML.

![Screenshot (126)](https://user-images.githubusercontent.com/115714443/213198362-67e36800-cace-423a-80f6-fe0d82a917ce.png)

### Penjelasan

- Mengambil data lowongan kerja dari situs web Glints. Dengan menggunakan library Python 'requests', kodingan mengirim permintaan GET ke URL "https://glints.com/id/lowongan-kerja" yang merupakan halaman web yang berisi informasi lowongan kerja. Kemudian, dengan menggunakan library 'BeautifulSoup', kodingan menganalisis konten halaman web yang didapat dari permintaan GET tersebut dengan menggunakan parser HTML.

- lalu, kodingan mencari semua elemen HTML dengan atribut 'div' dan 'id' yang sesuai, yaitu '__next'. Kemudian, dari elemen-elemen tersebut, kodingan mengekstrak informasi pekerjaan, lokasi, dan nama perusahaan dengan mencari elemen yang memiliki atribut 'class' yang sesuai. Informasi yang diambil kemudian disimpan dalam sebuah list yang sesuai.

- Kemudian, kodingan menggunakan library pandas untuk membuat dataframe dari list yang didapat dan menyimpannya dalam variabel 'df'. Kemudian kodingan mencetak dataframe tersebut, sehingga kita dapat melihat informasi lowongan kerja yang diambil dari situs web Glints.

![Screenshot (127)](https://user-images.githubusercontent.com/115714443/213199071-25eb4ce5-b621-444b-8f09-a7225031479f.png)

# TERIMAKASI
