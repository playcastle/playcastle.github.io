
![alt text](logo.svg?v=white-contrast) 
# Playcastle Studio - Official Company Profile
# Setup Notes (Work in Progress)
Dev Note : *Nanti Dirapihin Jadi Satu Folder Asset Aja Biar Ga Belepotan, Saya Belum Mood Beres2 Heheh yang penting running sama cakep

Ini adalah repositori resmi untuk website profil perusahaan **Playcastle Studio**, sebuah *Indie Game Development Agency* yang berbasis di Indonesia. Kami berfokus pada pengembangan *game* yang menarik dan interaktif di berbagai platform modern.

## 🚀 Tentang Kami

Berdiri sejak tahun 2020, Playcastle Studio berkomitmen untuk mengubah tren media sosial menjadi pengalaman bermain *game* yang sangat menghibur. Kami telah menjangkau jutaan pemain di seluruh dunia melalui karya-karya kami.

* **Spesialisasi Platform:** Mobile, WebGL, dan Roblox.
* **Pencapaian:** 42+ Games Shipped | 2M+ Players Reached.

## 🛠️ Teknologi yang Digunakan

Website ini dibangun menggunakan arsitektur web statis yang ringan dan cepat:
* **Frontend:** HTML5, CSS3, JavaScript (Vanilla)
* **Web Server:** Nginx (Alpine Linux)
* **Deployment:** Docker Containerization

---

## 💻 Panduan Deployment Server (Untuk Tim Dev)

Website ini di- *deploy* di server Linux (Microsoft Azure) menggunakan Docker. Berikut adalah langkah-langkah untuk melakukan *setup* atau *update* di *production server*.

### 1. Prasyarat
* Server Linux (Ubuntu/Debian) dengan akses Root/Sudo.
* [Docker](https://docs.docker.com/engine/install/) sudah terinstal di server.
* Akses Git melalui *SSH Deploy Keys* sudah dikonfigurasi antara server dan GitHub.

### 2. Setup Pertama Kali (Initial Clone)
Masuk ke direktori `/var/opt/` di server dan lakukan *clone* repositori:

```bash
cd /var/opt
git clone git@github.com:username/playcastle-profile-company.git playcastle
