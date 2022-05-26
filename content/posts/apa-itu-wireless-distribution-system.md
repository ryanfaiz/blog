---
title: "Apa Itu Wireless Distribution System"
date: May 26, 2022
url: "/apa-itu-wireless-distribution-system"
categories:
  - Article
tags:
  - IaaS
  - WDS
draft: false
hidden: false
---

## Pengertian WDS
Wide Distibution System (WDS) adalah sistem yang memungkinkan koneksi nirkabel melalui access point dalam jaringan IEEE 802.11. 

## Mode WDS pada jaringan Wireless: 
- Bridge, adalah mode komunikasi dua arah antara Access Point Wireless Distribution System satu dengan Access Point lainnya, tetapi tidak memperbolehkan perangkat wireless clients atau Station (STA) untuk mengaksesnya. 
	- Bridge Point to point
	- Bridge Point to multi point
 
- Repeater, adalah mode komunikasi dimana Access Point saling berkomunikasi satu sama lain dan juga berkomunikasi dengan perangkat wireless clients atau Station (STA). 
	- Single Repeater
	- Multi Repeater 

## Syarat Menerapkan WDS: 
- Perangkat Wireless Network seperti Wireless Router, Acces Point, dan Access point Repeater wajib support teknologi WDS. 
- IP Address perangkat wireless network harus berbeda. 
- Perangkat Wireless Network wajib support autentikasi, seperti WEP atau WAP. 
- SSID (Service Set Identifiers) yang digunakan pada perangkat wireless network harus berbeda untuk identitas masing-masing perangkat wireless network.
- Setelan Radio Channel yang digunakan wajib sama.
- Pastikan MAC Address Access Point Utama sudah tersimpan di Access point repeater. 
- Matikan fitur DHCP server pada Access Point Repeater.  

## Kelebihan WDS 
- Lebih hemat biaya
- Lebih efisien
- Mudah dikonfigurasi
- Header MAC address dari paket traffic bersifat tetap atau tidak berubah

## Kekurangan WDS
- Troughput efektif maksimum akan terbagi menjadi dua setelah transmisi pertama dibuat
- Fitur Dynamic Encryption Key tidak didukung dalam teknologi Wide Distribution System (WDS)
- Tidak semua akses point support teknologi Wide Distribution System (WDS)