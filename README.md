# Nama : Ayu Salsabilla
# NIM  : 09011382429120

# DRAW-IO

![Screenshot (3)](https://github.com/user-attachments/assets/1e02f58e-0806-4e22-bab6-10e508efae02)

## penjelasan Multiprosesor Symmetric (SMP)
Gambar tersebut menampilkan arsitektur komputer multiprosesor dengan memori bersama. Sistem ini terdiri dari empat CPU yang terhubung melalui Interconnect Switch ke Shared Memory. Setiap CPU memiliki cache sendiri untuk mempercepat akses data. Advanced Cache Coherence memastikan konsistensi data di antara cache-cache tersebut, menghindari konflik saat beberapa CPU mengakses data yang sama.

System Bus menghubungkan komponen-komponen utama sistem, termasuk memori dan I/O Controller. I/O Controller mengelola komunikasi antara CPU dan perangkat eksternal seperti Peripheral Device, Storage, dan Network Interface. Arsitektur ini mengimplementasikan model Symmetric Multiprocessing (SMP) di mana semua prosesor memiliki akses setara ke memori dan sumber daya sistem.

Keunggulan utama arsitektur ini adalah kemampuan pemrosesan paralel, berbagi data antar prosesor secara efisien, dan model pemrograman yang lebih sederhana karena menggunakan memori bersama. Sistem ini umumnya digunakan pada server, workstation performa tinggi, dan aplikasi komputasi intensif.

![Screenshot (5)](https://github.com/user-attachments/assets/16d56f1e-f6a8-4d02-92f3-ce1a43bb61bd)

## penjelasan Arsitektur Multiple Prosesor (AMP)
Gambar tersebut menunjukkan arsitektur sistem multiprosesor berbasis memori bersama. Terdapat empat CPU (CPU 1 hingga CPU 4), masing-masing dilengkapi dengan cache L1 dan L2 untuk mempercepat akses data lokal. Semua CPU terhubung ke Interconnect Network atau System Bus, yang menjadi jalur utama komunikasi antar CPU, memori, dan perangkat I/O. Di bawah sistem bus, terdapat dua Memory Controller yang masing-masing mengelola satu Main Memory, memungkinkan akses paralel dan mendukung arsitektur NUMA (Non-Uniform Memory Access). Selain itu, terdapat I/O Controller yang menghubungkan CPU dengan berbagai perangkat periferal. Untuk menjaga konsistensi data antar cache di berbagai CPU, sistem ini menerapkan Cache Coherence Protocol. Arsitektur ini memungkinkan CPU bekerja secara paralel dengan efisien, mempertahankan konsistensi data, dan mempercepat proses input/output, yang sangat penting dalam aplikasi komputasi kinerja tinggi maupun server skala besar.
