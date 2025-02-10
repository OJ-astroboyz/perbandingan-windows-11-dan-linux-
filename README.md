# perbandingan-windows-11-dan-linux-
## 1.Tampilan Desktop Windows 11 dan Linux Mint
## Windows
![Screenshot 2025-02-10 080501](https://github.com/user-attachments/assets/434ce411-656c-445b-8563-506beef44b18)
Menggunakan wallpaper anime dengan karakter berwarna merah dan hitam.
Banyak ikon desktop, termasuk aplikasi populer seperti Google Chrome, Discord, TikTok, dan berbagai software pengembangan (IntelliJ IDEA, Thonny, Oracle VirtualBox, dll.).
Taskbar berada di bawah dengan berbagai aplikasi yang sudah terbuka
## Linux Mint
![Screenshot 2025-02-10 080613](https://github.com/user-attachments/assets/9a0ee4c2-3b1c-46c2-a14b-5d0f1df5a666)
Menggunakan wallpaper default dengan latar belakang hitam dan logo Linux Mint.
Minimalis, hanya ada satu ikon "Install Linux Mint" di desktop.
Taskbar di bawah, tetapi lebih simpel dibandingkan dengan tampilan Windows.

## 2. Tampilan Menu Windows 11 dan Linux Mint
## Windows
![Screenshot 2025-02-10 080517](https://github.com/user-attachments/assets/da1e0a8e-15a4-40a0-8c68-deb85e7db5c5)
Start Menu berada di tengah dan memiliki tampilan modern dengan ikon besar dan rapi.
Aplikasi yang dipin (Pinned Apps) mencakup Microsoft Office (Word, Excel, PowerPoint), aplikasi multimedia (Spotify, Xbox, Solitaire), dan beberapa utilitas Lenovo.
Bagian "Recommended" menampilkan file yang baru diakses, termasuk dokumen, screenshot, dan file PDF.

## Linux Mint
![Screenshot 2025-02-10 080628](https://github.com/user-attachments/assets/7644a442-0a4f-4093-8ac9-e374bcf22327)
Tampilan menu lebih klasik, dengan daftar aplikasi di sisi kanan dan kategori aplikasi di sisi kiri.
Ikon aplikasi lebih kecil dan lebih sederhana, dengan beberapa aplikasi open-source seperti Firefox, Thunderbird Mail, Pix (image viewer), Rhythmbox (music player), dan Software Manager.
Lebih berbasis kategori, dibandingkan dengan Windows yang lebih berbasis aplikasi yang sering digunakan.

## 3. Analisis Perbandingan Performance Monitoring System : Windows 11(Performance Monitor) dan Linux Mint (HTOP).
## Penggunaan CPU dan Memori Windows dengan Linux Mint
![Screenshot 2025-02-10 083531](https://github.com/user-attachments/assets/92943fb7-fba2-4fdc-a459-6fbbac73d52d)
![Screenshot 2025-02-10 083547](https://github.com/user-attachments/assets/d82901ca-fc98-4b01-8afe-b56575ebbf49)
![Screenshot 2025-02-10 080718](https://github.com/user-attachments/assets/5383d44b-60ed-4680-9de6-d136446b3605)

## 1.Analisis CPU
## Windows
## Utilisasi CPU:
CPU Utilization: 10% (relatif rendah, menandakan sistem sedang dalam kondisi idle atau beban ringan).
CPU Speed: 1.72 GHz (di bawah base speed, menunjukkan power-saving mode atau tugas ringan).
Memory Usage: 7.4 GB dari 13.8 GB (54% penggunaan RAM, cukup tinggi tetapi masih dalam batas wajar).
Disk Usage (C: SSD NVMe): 3% (hampir tidak ada aktivitas disk yang signifikan).
GPU Utilization: 1% (menunjukkan tidak ada aktivitas grafis berat, seperti gaming atau rendering).
Network (Wi-Fi dan Ethernet): 0 Kbps (tidak ada aktivitas jaringan yang berjalan).

## Spesifikasi CPU:
Prosesor: AMD Ryzen 5 5500U dengan Radeon Graphics.
Base Speed: 2.10 GHz.
Current Speed: 1.72 GHz (menyesuaikan beban kerja saat ini).
Jumlah Socket: 1.
Jumlah Core: 6.
Logical Processors (Threads): 12.
Virtualization: Enabled (mendukung virtualisasi, bisa digunakan untuk menjalankan mesin virtual).
Cache CPU:
L1 Cache: 384 KB.
L2 Cache: 3.0 MB.
L3 Cache: 8.0 MB.
GPU: AMD Radeon Graphics.
Sistem Operasi: Windows 11 (berdasarkan UI Task Manager yang modern).

## Kesimpulan :
Performa CPU sedang dalam kondisi idle atau beban ringan, dengan penggunaan hanya 10%. Ini menunjukkan bahwa sistem tidak menjalankan tugas berat.
Penggunaan RAM mencapai 54%, yang cukup signifikan. Ini bisa disebabkan oleh aplikasi latar belakang atau browser dengan banyak tab terbuka.
Disk Usage hanya 3%, menunjukkan tidak ada aktivitas penyimpanan berat seperti transfer file besar atau instalasi program.
GPU juga dalam kondisi idle (1%), menandakan tidak ada proses rendering, gaming, atau tugas grafis berat yang sedang berjalan.
Sistem sudah berjalan selama lebih dari 14 jam, yang berarti uptime cukup lama tanpa restart.

## Linux Mint
## Utilisasi CPU:
CPU Usage: Terlihat dari bar CPU di bagian atas, penggunaan CPU saat ini cukup rendah, dengan mayoritas thread dalam kondisi idle.
Load Average:
1 menit: 0.12
5 menit: 0.21
15 menit: 0.29
→ Ini menunjukkan bahwa beban CPU sangat ringan, jauh di bawah kapasitas maksimum.
Proses yang berjalan: 80 total tasks, 204 threads, dengan hanya 1 proses yang aktif saat ini.
Proses yang paling aktif:
xfwm4 (Window Manager) menggunakan sekitar 5.1% CPU.
Xorg (X Window System) menggunakan sekitar 2.2% CPU.
xfce4-session dan xdesktop masing-masing menggunakan 3.6% dan 3.0% CPU.

## Spesifikasi CPU:
Jumlah Core: Informasi spesifik jumlah core tidak terlihat langsung di gambar, tetapi berdasarkan konteks penggunaan Linux Mint dengan Xfce, kemungkinan CPU ini memiliki 2-4 core.
Arsitektur: Tidak ada informasi langsung, tetapi dengan melihat penggunaan resource, kemungkinan besar ini adalah CPU x86_64.
Sistem Operasi: Linux Mint dengan Xfce Desktop Environment, yang dikenal ringan dan hemat resource.
Uptime: 15 menit, menunjukkan sistem baru saja dinyalakan.

## Kesimpulan :
CPU dalam kondisi sangat ringan, dengan load average yang sangat rendah (0.12, 0.21, 0.29), sehingga sistem berjalan dengan lancar tanpa hambatan.
Proses paling aktif adalah xfwm4 (window manager) dan Xorg (display server), yang merupakan bagian dari tampilan desktop.
Sistem operasi menggunakan Linux Mint dengan Xfce, yang memang dioptimalkan untuk penggunaan resource rendah, cocok untuk perangkat dengan spesifikasi rendah atau sedang.
Jika ingin lebih mengoptimalkan performa, bisa menutup aplikasi yang berjalan di latar belakang atau menggunakan tools seperti htop atau top untuk memonitor lebih lanjut.

## 2.Analisis Memori
## Windows
Total RAM: 16 GB
RAM Digunakan: 7.4 GB (54%)
RAM Tersedia: 6.5 GB
Kecepatan RAM: 3200 MT/s
Slot RAM Terpakai: 2 dari 2 slot
Memori Terkompresi: 463 MB
Swap File (Komitmen Memori): 11.4 GB digunakan dari 17.0 GB
## Kesimpulan
Menggunakan sekitar 54% dari total RAM yang tersedia.
Sistem memiliki kapasitas RAM besar (16 GB), tetapi penggunaan cukup tinggi, menunjukkan aplikasi berat mungkin sedang berjalan atau banyak layanan latar belakang aktif.
Menggunakan fitur paging dan caching untuk efisiensi.

## Linux Mint
Total RAM: 1.92 GB
RAM Digunakan: 705 MB
RAM Bebas: ~1.2 GB
Swap File: 0 KB digunakan
Proses yang Memakan Banyak RAM:
xfwm4 sekitar 100 MB per proses
xfdesktop sekitar 473 MB total
python3 beberapa proses dengan penggunaan ~550 MB

## Kesimpulan
Menggunakan jauh lebih sedikit RAM dibandingkan Windows (sekitar 705 MB dari 1.92 GB).
Tidak menggunakan swap, yang berarti sistem lebih ringan dan optimal.
Proses XFCE (lingkungan desktop) adalah yang paling banyak menggunakan RAM, tetapi tetap ringan dibandingkan dengan Windows.

## Kesimpulan akhir antara kedua nya
Windows membutuhkan lebih banyak RAM, tetapi lebih siap untuk aplikasi berat.
Linux lebih efisien dalam penggunaan memori, cocok untuk perangkat dengan spesifikasi rendah.
