# RENCANA PEMBELAJARAN SEMESTER (RPS) BERBASIS OBE

**Mata Kuliah:** Jaringan Komputer dan Komunikasi Data  
**Bobot SKS:** 3 SKS (1 Teori, 2 Praktikum)  
**Semester:** Ganjil / Genap  
**Prasyarat:** Sistem Operasi, Arsitektur Komputer  

---

## 1. Deskripsi Mata Kuliah
Mata kuliah ini membahas fundamental komunikasi data, arsitektur jaringan TCP/IP, serta implementasi praktis perancangan dan manajemen jaringan komputer menggunakan perangkat MikroTik. Pembelajaran berbasis *Hands-on Lab* yang disejajarkan dengan silabus sertifikasi industri **MTCNA (MikroTik Certified Network Associate)** dan **MTCRE (MikroTik Certified Routing Engineer)**. Topik mencakup manajemen *RouterOS*, *Bridging*, DHCP, *Wireless*, *Firewall*, QoS, konfigurasi *Tunneling/VPN*, *Advanced Static Routing*, VLAN, dan *Dynamic Routing* (OSPF).

## 2. Capaian Pembelajaran Lulusan (CPL) yang Dibebankan
*   **CPL-1 (Sikap):** Memiliki etika profesional dan tanggung jawab dalam mengelola infrastruktur jaringan dan keamanan data institusi.
*   **CPL-2 (Pengetahuan):** Menguasai konsep dasar komunikasi data, topologi, protokol TCP/IP, serta teori *routing* statis dan dinamis.
*   **CPL-3 (Keterampilan Umum):** Mampu mendiagnosis (*troubleshoot*), menganalisis, dan menyelesaikan masalah konektivitas jaringan secara sistematis.
*   **CPL-4 (Keterampilan Khusus):** Mampu mengonfigurasi perangkat MikroTik untuk kebutuhan infrastruktur jaringan skala kecil hingga menengah (*Enterprise*), setara dengan kompetensi sertifikasi MTCNA dan MTCRE.

## 3. Capaian Pembelajaran Mata Kuliah (CPMK)
*   **CPMK-1:** Mahasiswa mampu menjelaskan model OSI, TCP/IP, dan melakukan perhitungan *Subnetting* IP Address.
*   **CPMK-2 (MTCNA Core):** Mahasiswa mampu mengonfigurasi fitur dasar *RouterOS* (Bridging, DHCP, DNS) untuk menyediakan akses Internet pada jaringan lokal.
*   **CPMK-3 (MTCNA Core):** Mahasiswa mampu merancang keamanan jaringan dasar menggunakan *Firewall* (Filter, NAT) dan mengelola *bandwidth* (QoS).
*   **CPMK-4 (MTCRE Core):** Mahasiswa mampu mengimplementasikan *Advanced Static Routing* (*Failover*, ECMP) dan segmentasi jaringan (VLAN, *Tunneling*).
*   **CPMK-5 (MTCRE Core):** Mahasiswa mampu mengonfigurasi, mendistribusikan, dan memecahkan masalah pada protokol *routing* dinamis OSPF (*Single* & *Multi-Area*).

---

## 4. Rencana Kegiatan Pembelajaran Mingguan (16 Pertemuan)

| Minggu | Kemampuan Akhir yang Diharapkan (Sub-CPMK) | Materi Pembelajaran | Bentuk & Metode Pembelajaran | Penilaian (Indikator & Kriteria) | Bobot | Materi |
| :---: | :--- | :--- | :--- | :--- | :---: | :---: |
| **1** | Memahami fondasi komunikasi data, OSI, dan TCP/IP. | 1. Konsep Komunikasi Data & Topologi<br>2. Model OSI 7 Layer & DoD (TCP/IP)<br>3. Pengalamatan IP (IPv4) & *Subnetting* (VLSM) | Kuliah Interaktif, Latihan<br>*(TM: 1x50", P: 2x170")* | Kecepatan & ketepatan dalam menyelesaikan soal *subnetting*. | 2% | Link |
| **2** | **[MTCNA]** Menguasai manajemen dasar *RouterOS*. | 1. Arsitektur MikroTik (RouterBoard vs CHR)<br>2. Akses (Winbox, CLI, SSH, Mac-Telnet)<br>3. *User Management*, *Backup/Restore*, & NTP | Praktikum, *Hands-on*<br>*(TM: 1x50", P: 2x170")* | Keberhasilan *login* awal, konfigurasi identitas, dan *backup* sistem. | 5% |
| **3** | **[MTCNA]** Mengimplementasikan jaringan LAN terpusat. | 1. Konsep *Bridging* & *Switching* di MikroTik<br>2. ARP (Address Resolution Protocol)<br>3. DHCP Server, DHCP Client, & DHCP Relay | Praktikum, *Hands-on*<br>*(TM: 1x50", P: 2x170")* | PC Klien berhasil mendapatkan IP dinamis dan terhubung ke *router*. | 5% |
| **4** | **[MTCNA]** Mengonfigurasi *Wireless* dasar. | 1. Standar 802.11 (a/b/g/n/ac)<br>2. Setup AP, Station, & *Security Profiles*<br>3. *Wireless Tools* (Snooper, Scanner) | Praktikum<br>*(TM: 1x50", P: 2x170")* | Klien berhasil terhubung ke SSID dengan autentikasi WPA2. | 5% |
| **5** | **[MTCNA]** Melindungi jaringan lokal dengan *Firewall*. | 1. Struktur *Firewall* (Prinsip *Chains*: Input, Forward, Output)<br>2. *Filter Rules* (Accept, Drop, Reject)<br>3. NAT (SrcNAT / Masquerade, DstNAT / Port Forwarding) | Praktikum, *Problem-based*<br>*(TM: 1x50", P: 2x170")* | *Router* berhasil berbagi koneksi internet (NAT) & memblokir ping/situs tertentu. | 7% |
| **6** | **[MTCNA]** Memanajemen trafik data dan *Bandwidth*. | 1. Konsep *Quality of Service* (QoS)<br>2. *Simple Queue* (Target, Max-limit, Burst)<br>3. Pengenalan PCQ (*Per Connection Queue*) | Praktikum<br>*(TM: 1x50", P: 2x170")* | Keberhasilan melimitasi *bandwidth* per IP dan limitasi merata (PCQ). | 6% |
| **7** | **[MTCNA]** Membangun koneksi *Tunneling* dasar. | 1. Konsep VPN & PPP (*Point-to-Point Protocol*)<br>2. PPPoE Server & Client<br>3. PPTP (Point-to-Point Tunneling Protocol) | Praktikum<br>*(TM: 1x50", P: 2x170")* | Klien *remote* dapat mengakses LAN internal melalui *Tunnel* PPTP/PPPoE. | 5% |
| **8** | **Evaluasi Tengah Semester (UTS)** | **Ujian Praktik MTCNA (Membangun topologi dari Internet hingga LAN + Firewall/QoS)** | **Ujian Praktik Lab** | **Konektivitas *End-to-End* dan *Troubleshooting* dasar.** | **15%** |
| **9** | **[MTCRE]** Mengimplementasikan *Advanced Static Routing*. | 1. Anatomi Tabel *Routing* (FIB, RIB)<br>2. *Administrative Distance* & *Routing Mark*<br>3. *Failover* dengan *Check Gateway*<br>4. ECMP (*Equal Cost Multi-Path*) | Praktikum, *Hands-on*<br>*(TM: 1x50", P: 2x170")* | Trafik beralih otomatis (*failover*) jika jalur utama diputus (*link down*). | 7% |
| **10** | **[MTCRE]** Menerapkan *Point-to-Point Addressing* & VLAN. | 1. Pengalamatan IP *Point-to-Point* (/30, /32)<br>2. Konsep VLAN (802.1Q)<br>3. *Trunk Port* & *Access Port* (VLAN via Switch chip vs Bridge) | Praktikum<br>*(TM: 1x50", P: 2x170")* | Isolasi trafik antar departemen (VLAN berbeda) berhasil dilakukan. | 7% |
| **11** | **[MTCRE]** Membangun *Advanced Tunnel/VPN*. | 1. Perbedaan IPIP, EoIP, dan GRE<br>2. Implementasi EoIP (Ethernet over IP) untuk *Bridge* jarak jauh<br>3. Pengamanan Tunnel dengan L2TP/IPSec | Praktikum<br>*(TM: 1x50", P: 2x170")* | Dua jaringan LAN terpisah secara geografis berhasil di-*bridge* (satu segmen IP). | 6% |
| **12** | **[MTCRE]** Memahami protokol *Dynamic Routing* (OSPF). | 1. Algoritma *Link-State* (Dijkstra) & Konsep *Area*<br>2. OSPF *Neighbor*, *Hello Protocol*, *Router ID*<br>3. Konfigurasi OSPF *Single Area* (Area 0 / *Backbone*) | Praktikum, *Hands-on*<br>*(TM: 1x50", P: 2x170")* | Tabel *routing* terdistribusi otomatis, PC lintas *router* dapat saling ping. | 7% |
| **13** | **[MTCRE]** Menerapkan OSPF *Multi-Area*. | 1. Tipe *Router*: IR, ABR (Area Border Router), ASBR<br>2. Inter-Area Routing & LSA (*Link State Advertisement*) Types<br>3. Manipulasi OSPF *Cost* | Praktikum<br>*(TM: 1x50", P: 2x170")* | Konvergensi OSPF di 3 atau lebih *router* dengan pembagian area yang benar. | 7% |
| **14** | **[MTCRE]** Mengamankan & optimasi *Routing* OSPF. | 1. OSPF *Authentication* (MD5)<br>2. *Route Redistribution* (Connected, Static, Default)<br>3. *Stub Area* & NSSA (Not-So-Stubby-Area) | Praktikum, *Problem-based*<br>*(TM: 1x50", P: 2x170")* | Keberhasilan meringkas tabel *routing* & injeksi *default-route* ke area OSPF. | 6% |
| **15** | Integrasi Jaringan Kompleks (MTCNA + MTCRE). | Desain & Implementasi topologi kompleks (Gabungan VLAN, OSPF, NAT, dan Failover Static) sebagai persiapan *Final Project*. | *Project-based Learning*<br>*(TM: 1x50", P: 2x170")* | Mahasiswa mampu menyelesaikan studi kasus desain jaringan *Enterprise*. | 0% |
| **16** | **Evaluasi Akhir Semester (UAS)** | **Ujian Praktik Akhir Jaringan Skala Menengah (Topologi *Enterprise*)** | **Ujian Praktik Lab & Dokumentasi** | **Fungsionalitas jaringan total: Konektivitas, *Redundancy*, Segregrasi (VLAN), & *Dynamic Routing*.** | **20%** |

---

## 5. Sistem Penilaian (OBE Assessment)

| Komponen Penilaian | Terkait dengan CPMK | Persentase Bobot | Keterangan |
| :--- | :--- | :--- | :--- |
| **Kuis & Observasi Lab Mingguan (MTCNA)** | CPMK-1, CPMK-2, CPMK-3 | 25% | Pengecekan *progress* hasil konfigurasi lab mingguan (minggu 1-7). |
| **Kuis & Observasi Lab Mingguan (MTCRE)** | CPMK-4, CPMK-5 | 25% | Pengecekan *progress* hasil konfigurasi *routing* kompleks (minggu 9-14). |
| **Ujian Tengah Semester (UTS)** | CPMK-2, CPMK-3 | 20% | Ujian konfigurasi waktu-terbatas (Fokus pada fondasi, Gateway, & *Firewall*). |
| **Ujian Akhir Semester (UAS) / Final Lab** | CPMK-4, CPMK-5 | 30% | Penyelesaian *Troubleshooting Ticket* atau *Lab Topology* gabungan MTCNA+MTCRE. |
| **TOTAL** | | **100%** | |

## 6. Referensi & Daftar Pustaka

**Buku Utama:**
1. Towidjojo, Rendra. (2016). *MikroTik Kung Fu Kitab 1 & 2*. Jasakom.
2. Towidjojo, Rendra. (2018). *MikroTik Kung Fu: Routing* (Referensi MTCRE). Jasakom.
3. Hartpence, B. (2011). *Packet Guide to Routing and Switching*. O'Reilly Media.

**Referensi Pendukung / Praktikum:**
1. Modul Pelatihan Resmi MTCNA (*MikroTik Certified Network Associate*).
2. Modul Pelatihan Resmi MTCRE (*MikroTik Certified Routing Engineer*).
3. Dokumentasi Resmi MikroTik Wiki/Help (*help.mikrotik.com/docs/*).

**Perangkat Kebutuhan Praktikum:**
*   **Hardware (Opsi 1):** MikroTik RouterBoard seri hap lite / hap ac2 / RB750Gr3 (Minimal 1 per mahasiswa, ideal 2 per kelompok untuk OSPF).
*   **Software / Emulator (Opsi 2):** GNS3, EVE-NG, PNETLab, atau VMware/VirtualBox dengan *image* MikroTik CHR (Cloud Hosted Router).
*   Winbox (Utility manajemen MikroTik).
