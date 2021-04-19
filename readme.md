# Praktikum 4 - Pemrograman Web (CSS Layout)

### Rofi Ismail - 311910657

### TI.19.A.2

## Langkah 1
Membuat sebuah dokumen html dengan nama file <b>lab4_box.html</b> kemudian tambahkan kode untuk membuat box element dengan tag `<div>`.
![SS1](https://user-images.githubusercontent.com/56240078/115169111-5a6e4e00-a0e7-11eb-8e18-151cc0651a7c.jpg)

Kemudian tambahkan deklarasi CSS pada `<head>` untuk membuat float element.
![SS1-2](https://user-images.githubusercontent.com/56240078/115169115-5c381180-a0e7-11eb-880e-1bda3a756212.jpg)

## Langkah 2
Mengatur <b>clearfix</b> element menggunakan property `clear`.
![SS1-3](https://user-images.githubusercontent.com/56240078/115169119-5d693e80-a0e7-11eb-9b06-2af59b0e4d20.jpg)

Saya mencoba mengganti nilai `clear` dengan nilai lainnya (`left, both, right`), namun saat saya mencoba, yang tampak berbeda hanya nilai `right` dimana element `Div 4` menjadi sebaris dengan element div lainnya, sedangkan nilai `left dan both` element `Div 4` terletak dibawah div yang lain.
![SS1-4](https://user-images.githubusercontent.com/56240078/115169692-f056a880-a0e8-11eb-9847-4db9da47f0b2.jpg)
^ property `clear` dengan nilai `right`.

![SS1-5](https://user-images.githubusercontent.com/56240078/115169876-770b8580-a0e9-11eb-962d-8ba07052c82c.jpg)
^ property `clear` dengan nilai `left dan both`.

## Membuat Layout sederhana seperti gambar berikut
![Layout](https://user-images.githubusercontent.com/56240078/115170095-01ec8000-a0ea-11eb-9077-68ea23084067.jpg)

## Langkah 1
Membuat folder baru dengan nama <b>lab4_layout</b> kemudian buat file baru di dalam folder tersebut dengan nama `home.html` dan `style.css`.
Lalu tambahkan kode berikut untuk membuat kerangka layout dengan semantic element.
![SS2](https://user-images.githubusercontent.com/56240078/115169121-5e9a6b80-a0e7-11eb-898e-7edeca48a591.jpg)

Hasilnya:
![SS2-1](https://user-images.githubusercontent.com/56240078/115169124-5f330200-a0e7-11eb-934b-c5a91ce2551a.jpg)

## Langkah 2
### Membuat Layout
Menambahkan kode CSS berikut untuk membuat layoutnya.
![SS2-2](https://user-images.githubusercontent.com/56240078/115169125-5fcb9880-a0e7-11eb-92cd-17a45f88c7fe.jpg)

Hasilnya:
![SS2-3](https://user-images.githubusercontent.com/56240078/115169127-60fcc580-a0e7-11eb-9681-aed92c9fcf97.jpg)

## Langkah 3
### Membuat Navigasi
Mengatur navigasi sebagai berikut.
![SS2-4](https://user-images.githubusercontent.com/56240078/115169128-61955c00-a0e7-11eb-96dc-905be40dbaaf.jpg)

Hasilnya:
![SS2-5](https://user-images.githubusercontent.com/56240078/115169130-622df280-a0e7-11eb-8178-77be92c05072.jpg)

## Langkah 4
### Membuat Hero Panel
Membuat hero panel dengan menambahkan kode berikut pada HTML dan CSS.
![SS3](https://user-images.githubusercontent.com/56240078/115169133-635f1f80-a0e7-11eb-8e92-d80168067ef1.jpg)
Hijau = HTML, Kuning = CSS

Hasilnya:
![SS3-1](https://user-images.githubusercontent.com/56240078/115169136-6528e300-a0e7-11eb-85c6-cf109ddcd8f9.jpg)

## Langkah 5
### Mengatur Layout Main dan Sidebar
Mengatur main content dan sidebar dengan property `float`.
![SS4](https://user-images.githubusercontent.com/56240078/115169139-665a1000-a0e7-11eb-98e2-b3d17f3e4538.jpg)

### Membuat Sidebar Widget
Menambahkan kode berikut di dalam element `sidebar` untuk membuat widget.
![SS4-1](https://user-images.githubusercontent.com/56240078/115169140-66f2a680-a0e7-11eb-9192-f58c9a2c190a.jpg)

Kemudian tambahkan kode CSS.
![SS4-2](https://user-images.githubusercontent.com/56240078/115169142-6823d380-a0e7-11eb-82a0-0b997ce36e76.jpg)

Hasilnya:
![SS4-3](https://user-images.githubusercontent.com/56240078/115169144-68bc6a00-a0e7-11eb-81e5-b10355159db5.jpg)

## Langkah 6
### Mengatur Footer
Untuk mengatur footer, tambahkan kode CSS sebagai berikut.
![SS4-4](https://user-images.githubusercontent.com/56240078/115169145-69ed9700-a0e7-11eb-99e0-56fbd8ed3859.jpg)

Hasilnya:
![SS4-5](https://user-images.githubusercontent.com/56240078/115169147-6a862d80-a0e7-11eb-80a5-20c611f6d5e4.jpg)

## Langkah 7
### Menambahkan Element lain pada Main Content
Tambahkan kode berikut pada `element/section main` dalam dokumen HTML.
![SS5](https://user-images.githubusercontent.com/56240078/115169149-6bb75a80-a0e7-11eb-9dae-ec2f796db402.jpg)

Kemudian tambahkan CSS.
![SS5-1](https://user-images.githubusercontent.com/56240078/115169151-6c4ff100-a0e7-11eb-9e1a-9f5f44f8b9e2.jpg)

Hasilnya:
![SS5-2](https://user-images.githubusercontent.com/56240078/115169153-6e19b480-a0e7-11eb-9dca-00ef53491f6e.jpg)

## Langkah 8
### Menambah Content Artikel
Untuk membuat content artikel, tambahkan kode berikut pada `section main`.
![SS6](https://user-images.githubusercontent.com/56240078/115169159-6f4ae180-a0e7-11eb-8d72-f88e7f4430bc.jpg)

Kemudian tambahkan CSS.

![SS6-1](https://user-images.githubusercontent.com/56240078/115169163-7114a500-a0e7-11eb-970d-a2e9ead49d97.jpg)

Hasilnya:
![SS6-2](https://user-images.githubusercontent.com/56240078/115169164-71ad3b80-a0e7-11eb-9a73-8a7eb70fed78.jpg)

# Pertanyaan dan Tugas
### 1. Tambahkan Layout untuk menu About
- buat single layout yang berisi deskripsi, portofolio, dll.
### 2. Tambahkan Layout untuk menu Contact
- yang berisi form isian: Nama, Email, Message, dll.

## 1.  Menambahkan Layout pada menu About
### Membuat dokumen html dengan nama `about.html` sebagai berikut.
![SS7](https://user-images.githubusercontent.com/56240078/115169166-72de6880-a0e7-11eb-8f8c-417d12ac52f2.jpg)

### Lalu menambahkan CSS.
![SS7-1](https://user-images.githubusercontent.com/56240078/115169168-7376ff00-a0e7-11eb-9f81-3168d64f13fe.jpg)

### Hasilnya saat menekan menu About akan dialihkan ke halaman berikut:
![SS7-2](https://user-images.githubusercontent.com/56240078/115169169-74a82c00-a0e7-11eb-8ef9-80fe45c05d9c.jpg)

## 2. Menambahkan Layout pada menu Contact
### Membuat dokumen html dengan nama `kontak.html` sebagai berikut.
![SS7-3](https://user-images.githubusercontent.com/56240078/115169171-7540c280-a0e7-11eb-83cb-1685a1c9e682.jpg)

### Lalu menambahkan CSS.
![SS7-4](https://user-images.githubusercontent.com/56240078/115169172-75d95900-a0e7-11eb-9951-d09328a2d19e.jpg)

### Hasilnya saat menekan menu Contact akan dialihkan ke halaman berikut:
![SS7-5](https://user-images.githubusercontent.com/56240078/115169173-770a8600-a0e7-11eb-907a-0caa2290f156.jpg)