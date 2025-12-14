# Proyek Menggunakan Blynk  
proyek 1 : Simulasi Monitoring Status Pintu Utama, Pintu Belakang, dan Jendela Samping.  

Sistem ini memungkinkan kontrol dan monitoring status pintu utama, pintu belakang, dan jendela samping menggunakan aplikasi Blynk melalui virtual pins. Implementasi menggunakan:  
1. ESP8266
2. relay 2 buah  
3. led 3 buah
4. micro switch 3 buah  
   Dengan format kode:   
   PU ---+  
         |  
   PB ---+--> [ESP8266 pin input]  
         |  
   JS ---+  

ESP8266 pin output --> [Relay 1 & Relay 2] --> [LED indikator]  

- ESP membaca status switch  
- Relay menyalakan LED  
- Status dikirim ke Blynk  

<img width="1360" height="688" alt="Screenshot 2025-12-13 101854" src="https://github.com/user-attachments/assets/5869d115-41be-4dee-b8db-0d390f9ad1dc" />
<img width="1360" height="691" alt="Screenshot 2025-12-13 145229" src="https://github.com/user-attachments/assets/4f5f6b96-daab-4822-8b5a-dee29bad8a5a" />


  
Proyek 2: Simulasi dan Kontrol Suhu dan Kelembaban Udara.  
Sistem ini memungkinkan untuk menampilkan suhu dan kelembaban udara melalui display LCD. Yang kemudian alarm akan berbunyi ketika suhu sudah melewati batas yang ditetapkan. Implementasi ini membutuhkan:  
1. DHT11
2. Buzzer
3. LCD I2C
4. ESP8266

<img width="1360" height="683" alt="Screenshot 2025-12-13 110623" src="https://github.com/user-attachments/assets/043f7743-26c2-44a4-bf39-27f57290bf4d" />
<img width="1360" height="686" alt="111" src="https://github.com/user-attachments/assets/be62790b-ec14-4d7d-a9ad-1bf6d9c0282a" />

