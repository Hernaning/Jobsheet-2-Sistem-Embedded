# Jobsheet-2-Sistem-Embedded


Teori Singkat


ESP32 adalah nama dari mikrokontroler yang dirancang oleh perusahaan 
yang berbasis di Shanghai, China yakni Espressif Systems. ESP32 menawarkan 
solusi jaringan WiFi dan BLE. ESP32 menggunakan prosesor dual core yang 
berjalan di instruksi Xtensa LX16. Selain itu, ESP32 telah mendukung protokol 
komunikasi seperti I2C, UART dan SPI.


a) ESP32 Capacitive Touch Sensor


Buatlah rangkaian seperti gambar berikut ini


![Sensor touch ](https://user-images.githubusercontent.com/119298912/209354180-a6b99471-e107-41c5-9ce3-3f6a3f21cebc.jpg)




Buatlah program agar LED menyala ketika sensor disentuh, dan LED akan 
mati ketika sensor tidak disentuh


![ESP32 Touch Sensor 1](https://user-images.githubusercontent.com/119298912/209348701-e1dcca55-cc39-4d4f-b271-bdfb5126be42.jpg)



https://user-images.githubusercontent.com/119298912/209354395-966d2a3f-cf75-486e-a42a-22cae61a92a0.mp4




Buatlah program agar ketika sensor disentuh, LED menyala Blink

(belum)


Buatlah program agar ketika LED menyala, maka pada Serial Monitor akan 
menampilkan angka yang akan bertambah setiap kali sensor disentuh.


![ESP32 Touch Sensor 1](https://user-images.githubusercontent.com/119298912/209350004-b0053a02-7e0b-42ef-a286-3be57cb71db8.jpg)


![led on](https://user-images.githubusercontent.com/119298912/209350165-23a1bd4c-543b-4ee5-aec7-9765a599fa22.jpg)



![led off](https://user-images.githubusercontent.com/119298912/209350218-dba64553-d5ad-40a3-8799-6a27e78c29b7.jpg)


Tambahkan 2 LED sehingga pada rangkaian terdapat 3 LED. Buatlah 
program agar ketika sensor disentuh, LED menyala menjadi running LED. 
Nyala running LED tersebut adalah bergerak dari kiri ke kanan, kemudian 
kanan ke kiri secara kontinyu



https://user-images.githubusercontent.com/119298912/209350442-dd3a5fb0-bdc8-4f94-aacc-a5840a0b5448.mp4




b) Mengakses Sensor DHT 11 (Single Wire / BUS)



Buatlah program seperti pada script di bawah ini untuk mengakses sensor 
DHT11. Kemudian upload program tersebut pada ESP32 dan 
dokumentasikan hasilnya



![Sensor DHT 11 (Single-BUS)](https://user-images.githubusercontent.com/119298912/209351423-046e5243-0c51-4f68-a265-0beed103b91b.jpg)




https://user-images.githubusercontent.com/119298912/209355045-a2d47ee3-05ea-4992-a6e7-70d2164d313f.mp4



Buatlah program agar ketika suhu rungan mencapai 30 derajat celcius, maka 
ESP32 akan menyalakan LED Merah dan buzzer secara beep (blink). Apabila 
suhu dibawah 30 derajat, ESP32 akan mematikan buzzer dan menyalakan 
LED berbentuk running LED seperti pada Percobaan A. Kemudian 
dokumentasikan hasilnya



https://user-images.githubusercontent.com/119298912/209351734-4643d264-e101-4130-98cf-bacf29246b45.mp4



c) Mengakses Sensor RFID (SPI Communication)


Dekatkan kartu atau Tag RFID ke RFID Reader. Amati dan analisis cara kerja 
programnya



![RFID 1](https://user-images.githubusercontent.com/119298912/209353549-5b53dc57-3eb6-4f4e-b507-5c4194fafb23.jpg)



Buatlah program agar Tag RFID yang terbaca sebelumya dapat digunakan 
untuk hak akses. Apabila Tag RFID didekatkan pada Reader, maka LED 
Hijau akan menyala, servo akan bergerak ke kanan (lalu kembali ke posisi 
semula setelah 3 detik) dan di Serial Monitor akan tertampil pesan “Akses 
Diterima, Silahkan Masuk”. Apabila Tag RFID tidak dikenali, maka LED 
Merah akan menyala, servo tidak bergerak dan di Serial Monitor akan 
tertampil pesan “Akses Ditolak”. Gunakan Tag RFID lain untuk mencoba.
Amati yang terjadi, analisis dan dokumentasikan hasilnya



https://user-images.githubusercontent.com/119298912/209353731-39b7ba4a-129b-4218-9ab0-adcb9b79d4bc.mp4


