[![Open Source Love](https://badges.frapsoft.com/os/v1/open-source.svg?style=flat)](https://github.com/ellerbrock/open-source-badges/)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg?logo=github&color=%23F7DF1E)](https://opensource.org/licenses/MIT)
![GitHub last commit](https://img.shields.io/github/last-commit/devancakra/Arduino-Pro-Mini-based-Conveyor-Motor-Speed-Control-System-using-PWM-Method)
![Project](https://img.shields.io/badge/Project-Arduino-light.svg?style=flat&logo=arduino&logoColor=white&color=%23F7DF1E)

# Arduino-Pro-Mini-based-Conveyor-Motor-Speed-Control-System-using-PWM-Method
<strong>Proyek Tunggal: Sistem Kontrol Kecepatan Motor Konveyor menggunakan Metode PWM</strong><br><br>
Konveyor adalah sebuah sistem mekanik yang digunakan untuk memindahkan barang atau material dari satu tempat ke tempat lain yang dilakukan secara terus menerus. Untuk mengatur seberapa cepat mesin konveyor dapat bergerak, anda dapat menggunakan potensiometer.

<br><br>

## Kebutuhan Proyek
| Bagian | Deskripsi |
| --- | --- |
| Papan Pengembangan | Arduino Pro Mini |
| Editor Kode | Arduino IDE |
| Bootloader | USB-Serial PL2303 |
| Bahasa Pemrograman | C/C++ |
| Aktuator | Gear Motor / Motor DC (x1) |
| Komponen Lainnya| USB-Serial TTL: PL2303 (x1), Kabel jumper (1 set), KCD11: Saklar Pengayun SPST (x1), Baterai Li-ion 18650 (x2), Tempat baterai seri 2 slot (x1), Motor driver L298N (x1), and Piringan Encoder (x1) |

<br><br>

## Unduh & Instal
1. Arduino IDE

   ```
   https://www.arduino.cc/en/software
   ```
<br>

2. USB-Serial PL2303

   ```
   https://bit.ly/PL2303_Driver
   ```
   
<br><br>

## Rancangan Proyek
<table>
<tr>
<th width="420">Diagram Blok</th>
<th width="420">Diagram Ilustrasi</th>
</tr>
<tr>
<td><img src="" alt="Block-Diagram"></td>
<td><img src="" alt="Pictorial-Diagram"></td>
</tr>
</table>
<table>
<tr>
<th width="840">Pengkabelan</th>
</tr>
<tr>
<td><img src="" alt="Wiring"></td>
</tr>
</table>

<br><br>

## Pengaturan Arduino IDE
1. Buka ``` Arduino IDE ``` terlebih dahulu, kemudian buka proyek ini dengan cara klik: ``` File ``` -> ``` Open ``` -> ``` pwm_conveyor.ino ```.<br><br>
   
2. ``` Pengaturan Board ``` di Arduino IDE<br><br>
   • Cara: klik ``` Tools ``` -> ``` Board ``` -> ``` Arduino AVR Boards ``` -> ``` Arduino Pro or Pro Mini ```.<br><br>

3. ``` Ubah Processor ``` in Arduino IDE.<br><br>
   • Cara: klik ``` Tools ``` -> ``` Processor ``` -> ``` ATmega328P (5V, 16 MHz) ```.<br><br>

4. ``` Pengaturan Port ``` di Arduino IDE<br><br>
   • Cara: klik ``` Port ``` -> Pilih sesuai dengan port perangkat Anda ``` (Anda dapat melihatnya di Device Manager) ```.<br><br>

5. Sebelum mengunggah program, silakan klik: ``` Verify ```.<br><br>

6. Jika tidak ada kesalahan dalam kode program, silakan klik: ``` Upload ```.<br><br>

7. Jika dalam proses tersebut Anda menemukan tulisan ``` Uploading ```, maka Anda harus segera menekan tombol ``` Reset ``` pada board yang digunakan, hal ini bertujuan agar program berhasil diupload. Kemudian jika ternyata masih ada masalah, maka coba cek ``` driver ``` / ``` port ``` / ``` bagian lainnya ```.
   
8. Selamat menikmati [Selesai].

<br><br>

## Penggunaan USB-Serial TTL: PL2303
Segera Hadir....

<br><br>

## Memulai
1. Unduh dan ekstrak repositori ini.<br><br>
   
2. Pastikan anda memiliki komponen elektronik yang diperlukan.<br><br>
   
3. Pastikan komponen anda telah dirancang sesuai dengan diagram.<br><br>
    
4. Konfigurasikan perangkat anda menurut pengaturan di atas.<br><br>

5. Selamat menikmati [Selesai].

<br><br>

## Sorotan
<img src="" alt="pwm_conveyor">

<br><br>

## LISENSI
LISENSI MIT - Hak Cipta (c) 2024 - Devan C. M. Wijaya, S.Kom

Dengan ini diberikan izin tanpa biaya kepada siapa pun yang mendapatkan salinan perangkat lunak ini dan file dokumentasi terkait perangkat lunak untuk menggunakannya tanpa batasan, termasuk namun tidak terbatas pada hak untuk menggunakan, menyalin, memodifikasi, menggabungkan, mempublikasikan, mendistribusikan, mensublisensikan, dan/atau menjual salinan Perangkat Lunak ini, dan mengizinkan orang yang menerima Perangkat Lunak ini untuk dilengkapi dengan persyaratan berikut:

Pemberitahuan hak cipta di atas dan pemberitahuan izin ini harus menyertai semua salinan atau bagian penting dari Perangkat Lunak.

DALAM HAL APAPUN, PENULIS ATAU PEMEGANG HAK CIPTA DI SINI TETAP MEMILIKI HAK KEPEMILIKAN PENUH. PERANGKAT LUNAK INI DISEDIAKAN SEBAGAIMANA ADANYA, TANPA JAMINAN APAPUN, BAIK TERSURAT MAUPUN TERSIRAT, OLEH KARENA ITU JIKA TERJADI KERUSAKAN, KEHILANGAN, ATAU LAINNYA YANG TIMBUL DARI PENGGUNAAN ATAU URUSAN LAIN DALAM PERANGKAT LUNAK INI, PENULIS ATAU PEMEGANG HAK CIPTA TIDAK BERTANGGUNG JAWAB, KARENA PENGGUNAAN PERANGKAT LUNAK INI TIDAK DIPAKSAKAN SAMA SEKALI, SEHINGGA RISIKO ADALAH MILIK ANDA SENDIRI.
