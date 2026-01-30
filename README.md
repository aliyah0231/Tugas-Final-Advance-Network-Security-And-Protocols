# Tugas-Final-Advance-Network-Security-And-Protocols
# Tugas-Final-Advance-Network-Security-And-Protocols

Repository ini berisi **laporan akhir dan dokumentasi** tugas mata kuliah **Advanced Network Security and Protocols** dengan topik **Simulasi Pola Penyerangan Double Attack pada Layanan SSH menggunakan Cowrie Honeypot**.

---

## 📄 Laporan
Klik untuk membuka laporan lengkap:
- 👉 [Laporan Final (PDF)](Laporan_Advance_Network_Security_And_Protocols.pdf)

---

## 📁 Dokumentasi Pengujian
Klik untuk melihat dokumentasi berupa screenshot instalasi, konfigurasi, dan hasil simulasi serangan:
- 👉 [Folder Dokumentasi](Documentasi)

---

## 🧪 Deskripsi Singkat
Penelitian ini melakukan simulasi serangan jaringan secara berlapis (*double attack*) terhadap layanan SSH, yaitu:
- Port Scanning
- Brute Force Attack
- DDoS Attack

Serangan dilakukan dari **Kali Linux (Attacker)** ke **Ubuntu Server (Target)** yang telah dipasang **Cowrie Honeypot** sebagai server jebakan.

---

## ⚙️ Lingkungan Pengujian
- Kali Linux → Attacker
- Ubuntu Server → Target (Cowrie Honeypot)
- SSH asli dipindahkan ke port 2222
- Honeypot Cowrie berjalan di port 22

---

## 🎯 Tujuan
Mengetahui kemampuan Cowrie Honeypot dalam mendeteksi dan mencatat pola serangan **double attack** pada layanan SSH tanpa mengganggu server asli.

---

## ⚠️ Catatan
Seluruh pengujian dilakukan pada lingkungan virtual dan hanya digunakan untuk keperluan akademik.
