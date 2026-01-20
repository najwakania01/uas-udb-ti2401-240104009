# Clickjacking Vulnerability Checker

Aplikasi web sederhana untuk memeriksa apakah sebuah website rentan terhadap serangan **clickjacking**.

![Python](https://img.shields.io/badge/Python-3.12-blue)
![Flask](https://img.shields.io/badge/Flask-3.0-green)
![Docker](https://img.shields.io/badge/Docker-Ready-blue)

## 📋 Deskripsi

**Clickjacking** adalah teknik serangan di mana penyerang menyembunyikan elemen berbahaya di balik elemen yang terlihat aman. Aplikasi ini memeriksa apakah website target memiliki proteksi terhadap clickjacking dengan menganalisis header HTTP:

- **X-Frame-Options**: Header yang mencegah halaman dimuat dalam iframe
- **Content-Security-Policy (frame-ancestors)**: Directive CSP yang mengontrol embedding halaman

## 🚀 Cara Menjalankan

### Prasyarat

- [Docker](https://docs.docker.com/get-docker/) terinstall
- [Docker Compose](https://docs.docker.com/compose/install/) terinstall

### Langkah-langkah

1. **Clone repository**
   ```bash
   git clone <repository-url>
   cd uas-udb-ti2401

