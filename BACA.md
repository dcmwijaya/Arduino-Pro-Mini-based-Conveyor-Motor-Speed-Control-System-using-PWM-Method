[![Open Source Love](https://badges.frapsoft.com/os/v1/open-source.svg?style=flat)](https://github.com/ellerbrock/open-source-badges/)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg?logo=github&color=%23F7DF1E)](https://opensource.org/licenses/MIT)
![GitHub last commit](https://img.shields.io/github/last-commit/devancakra/Arduino-Pro-Mini-based-Conveyor-Motor-Speed-Control-System-using-PWM-Method)
![Project](https://img.shields.io/badge/Project-Arduino-light.svg?style=flat&logo=arduino&logoColor=white&color=%23F7DF1E)

# Arduino-Pro-Mini-based-Conveyor-Motor-Speed-Control-System-using-PWM-Method
<strong>Proyek Tunggal: Sistem Kontrol Kecepatan Motor Konveyor menggunakan Metode PWM</strong><br><br>
Konveyor adalah sebuah sistem mekanik yang digunakan untuk memindahkan barang atau material dari satu tempat ke tempat lain yang dilakukan secara terus menerus. Untuk mengatur seberapa cepat mesin konveyor dapat bergerak, anda dapat menggunakan potensiometer. Untuk mengganti arah gerakan mesin konveyor, sekaligus menghentikannya, anda dapat menggunakan push button.

<br><br>

## Kebutuhan Proyek
| Bagian | Deskripsi |
| --- | --- |
| Papan Pengembangan | Arduino Pro Mini |
| Editor Kode | Arduino IDE |
| Alat Pemrogram | PL2303 |
| Driver | USB-Serial PL2303 |
| Bahasa Pemrograman | C/C++ |
| Aktuator | Gear Motor / Motor DC (x1) |
| Komponen Lainnya| • Kabel jumper (1 set)<br>• KCD11: Saklar Pengayun SPST (x1)<br>• Baterai Li-ion 18650 (x2)<br>• Tempat baterai seri 2 slot (x1)<br>• Motor driver L298N (x1)<br>• Breadboard (x1)<br>• Potensiometer (x1)<br>• Push button 4-pin (x2)<br>• Stiker kayu (1 set)<br>• Papan kayu (x2) |

<br><br>

## Unduh & Instal
1. Arduino IDE

   <table><tr><td width="810">
      
   ```
   https://www.arduino.cc/en/software
   ```

   </td></tr></table><br>

2. USB-Serial PL2303

   <table><tr><td width="810">

   ```
   https://bit.ly/PL2303_Driver
   ```

   </td></tr></table>
   
<br><br>

## Rancangan Proyek
<table>
<tr>
<th width="420">Diagram Blok</th>
<th width="420">Diagram Ilustrasi</th>
</tr>
<tr>
<td><img src="https://github.com/devancakra/Arduino-Pro-Mini-based-Conveyor-Motor-Speed-Control-System-using-PWM-Method/assets/54527592/2b7222cd-5ae7-4966-aaab-655e46af83bc" alt="Block-Diagram"></td>
<td><img src="https://github.com/devancakra/Arduino-Pro-Mini-based-Conveyor-Motor-Speed-Control-System-using-PWM-Method/assets/54527592/d77f0693-7a8c-4276-a612-3ff161a304b7" alt="Pictorial-Diagram"></td>
</tr>
</table>
<table>
<tr>
<th width="840">Pengkabelan</th>
</tr>
<tr>
<td><img src="https://github.com/devancakra/Arduino-Pro-Mini-based-Conveyor-Motor-Speed-Control-System-using-PWM-Method/assets/54527592/6ebe5afa-e0d9-42d1-a6db-455a67975657" alt="Wiring"></td>
</tr>
</table>

<br><br>

## Pengaturan Arduino IDE
1. Buka ``` Arduino IDE ``` terlebih dahulu, kemudian buka proyek ini dengan cara klik ``` File ``` -> ``` Open ``` : 

   <table><tr><td width="810">
   
      ``` pwm_conveyor.ino ```

   </td></tr></table><br>
   
2. ``` Pengaturan Board ``` di Arduino IDE

   <table>
      <tr><th width="810">

      Cara mengatur board ``` Arduino Pro Mini ```
            
      </th></tr>
      <tr><td>
   
      Klik ``` Tools ``` -> ``` Board ``` -> ``` Arduino AVR Boards ``` -> ``` Arduino Pro or Pro Mini ```

      </td></tr>
   </table><br>

3. ``` Ubah Processor ``` di Arduino IDE

   <table><tr><td width="810">
   
      Klik ``` Tools ``` -> ``` Processor ``` -> ``` ATmega328P (5V, 16 MHz) ```

   </td></tr></table><br>

4. ``` Pengaturan Port ``` di Arduino IDE

   <table><tr><td width="810">
   
      Klik ``` Port ``` -> Pilih sesuai dengan port perangkat anda ``` (anda dapat melihatnya di Device Manager) ```

   </td></tr></table><br>

5. Sebelum mengunggah program, silakan klik: ``` Verify ```.<br><br>

6. Jika tidak ada kesalahan dalam kode program, silakan klik: ``` Upload ```.<br><br>

7. Beberapa hal yang perlu anda lakukan saat menggunakan ``` board Arduino Pro Mini ``` dengan ``` USB PL2303 ``` :

   <table><tr><td width="810">

      • Informasi ``` Arduino IDE ```: ``` Uploading... ``` -> segera tekan tombol ``` RESET ``` dan lepaskan.
      
      • Tunggu sampai muncul pesan: ``` Done Uploading ``` -> ``` Program langsung dioperasikan ```.

   </td></tr></table><br>

8. Jika masih ada masalah saat unggah program, maka coba periksa pada bagian ``` driver ``` / ``` port ``` / ``` yang lainnya ```.

<br><br>

## Pengaturan Alat Pemrogram: PL2303
<img width="840" src="https://github.com/devancakra/Arduino-Pro-Mini-based-Conveyor-Motor-Speed-Control-System-using-PWM-Method/assets/54527592/cb033083-004b-4ee4-afb1-3dbc1590fc3f"><br><br>

<strong>Catatan :</strong>

   <table><tr><td width="840">

   • ``` Arduino Pro Mini ``` ini tidak dilengkapi dengan ``` port USB ```, sehingga anda membutuhkan perangkat tambahan berupa ``` USB to TTL Serial ``` untuk dapat terhubung ke laptop ataupun PC. ``` USB to TTL Serial ``` seperti ``` USB PL2303 ``` ini biasa digunakan untuk media perantara dalam pengunggahan suatu program.
   
   • Pemasangan kabel antara ``` USB PL2303 ``` dengan board ``` Arduino Pro Mini ``` dapat anda lihat selengkapnya pada gambar di atas.
   
   • Untuk mengunggah program, selain menggunakan ``` USB PL2303 ```, anda juga dapat menggunakan alat pemrogram lainnya seperti: ``` FTDI FT232RL ```. Berdasarkan pengalaman, saya akui bahwa menggunakan ``` FTDI FT232RL ``` jauh lebih baik daripada ``` USB PL2303 ``` karena proses upload dapat dilakukan secara otomatis tanpa harus menekan tombol ``` RESET ```.

   </td></tr></table><br><br>

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
LISENSI MIT - Hak Cipta © 2024 - Devan C. M. Wijaya, S.Kom

Dengan ini diberikan izin tanpa biaya kepada siapa pun yang mendapatkan salinan perangkat lunak ini dan file dokumentasi terkait perangkat lunak untuk menggunakannya tanpa batasan, termasuk namun tidak terbatas pada hak untuk menggunakan, menyalin, memodifikasi, menggabungkan, mempublikasikan, mendistribusikan, mensublisensikan, dan/atau menjual salinan Perangkat Lunak ini, dan mengizinkan orang yang menerima Perangkat Lunak ini untuk dilengkapi dengan persyaratan berikut:

Pemberitahuan hak cipta di atas dan pemberitahuan izin ini harus menyertai semua salinan atau bagian penting dari Perangkat Lunak.

DALAM HAL APAPUN, PENULIS ATAU PEMEGANG HAK CIPTA DI SINI TETAP MEMILIKI HAK KEPEMILIKAN PENUH. PERANGKAT LUNAK INI DISEDIAKAN SEBAGAIMANA ADANYA, TANPA JAMINAN APAPUN, BAIK TERSURAT MAUPUN TERSIRAT, OLEH KARENA ITU JIKA TERJADI KERUSAKAN, KEHILANGAN, ATAU LAINNYA YANG TIMBUL DARI PENGGUNAAN ATAU URUSAN LAIN DALAM PERANGKAT LUNAK INI, PENULIS ATAU PEMEGANG HAK CIPTA TIDAK BERTANGGUNG JAWAB, KARENA PENGGUNAAN PERANGKAT LUNAK INI TIDAK DIPAKSAKAN SAMA SEKALI, SEHINGGA RISIKO ADALAH MILIK ANDA SENDIRI.
