🔗 **Official Website:** [https://haseblanteai.edgeone.app/](https://haseblanteai.edgeone.app/)

# Haseblante AI

**Haseblante AI** adalah aplikasi **Agentic AI** berbasis [Electron](https://www.electronjs.org/), dengan pengalaman penggunaan yang mirip dengan aplikasi AI desktop populer lainnya seperti *Claude Code* atau *Codex*.

Yang membedakan Haseblante AI adalah sifatnya yang **berjalan secara lokal (Local AI)** di lingkungan Haseblante itu sendiri — tanpa bergantung pada layanan cloud eksternal. Aplikasi ini dirancang agar penggunaannya **simpel, praktis, dan langsung pakai**.

Di bawah ini dijelaskan fitur-fitur unggulan serta kemampuan yang dimiliki Haseblante AI.

---

## ✨ Fitur Utama

Haseblante AI memiliki dua fitur unggulan utama: **Unggah File** dan **Thinking**.

### 📁 Unggah File

Pada versi demo saat ini, pengguna dapat mengunggah file dengan format:

- `.txt`
- `.md`
- `.html`
- dan format teks lainnya

> **Catatan:** Dukungan untuk unggah file berupa gambar dan video **belum tersedia** pada versi ini.

### 🧠 Thinking (Reasoning)

Fitur *Thinking* memungkinkan AI untuk bernalar lebih dalam menggunakan model **7B** dengan kemampuan *reasoning*. Dengan fitur ini, AI dapat:

- Memahami konteks permintaan secara lebih akurat
- Menghasilkan jawaban yang lebih tepat dan relevan
- Menangani tugas-tugas berat, termasuk **coding** dan pemecahan masalah kompleks

---

## 🤖 Kemampuan Agent

Haseblante AI sudah terintegrasi langsung dengan komputer pengguna, menjadikannya sebuah **AI Agent** yang sesungguhnya. Beberapa kemampuannya meliputi:

- 📖 Membaca isi file
- 💻 Mengeksekusi perintah **shell** dan **terminal**
- 🪟 Membuka dan menutup aplikasi di komputer

---

## ⚙️ Model & Spesifikasi Teknis

Model bawaan (*default*) dari Haseblante AI adalah:

> **Qwen2.5-7B-Instruct-Q4_K_S**

### Context Window

| Parameter | Nilai |
|---|---|
| Context window maksimum | ±28.000 token (secara arsitektur dapat mencapai hingga 131.072 token) |
| Context window minimum | 1 token |
| Maksimum output per jawaban | 8.000 token |

### Tentang Format Q4_K_S

`Q4_K_S` adalah varian **kuantisasi 4-bit**, yaitu metode kompresi model agar ukurannya lebih kecil dan lebih ringan dijalankan secara lokal, dengan tetap menjaga kualitas output pada tingkat yang baik.

### Catatan Teknis

Secara arsitektur, model Qwen2.5-7B-Instruct mampu membaca konteks hingga **128K token**. Namun, saat dijalankan secara lokal, batas konteks ini sering **dibatasi oleh software** (misalnya menjadi 2.048 atau 4.096 token) untuk menghemat penggunaan **VRAM/RAM GPU** pengguna.

---

## Cara menjalankannya

cara menjalankan aplikasinya ada pada official websitenya anda tinggal lihat dan ikuti di website resmi : https://haseblanteai.edgeone.app/

## 📌 Ringkasan

| Aspek | Keterangan |
|---|---|
| Platform | Electron (Desktop) |
| Jenis AI | Agentic, berjalan secara lokal |
| Model default | Qwen2.5-7B-Instruct-Q4_K_S |
| Fitur unggulan | Unggah File, Thinking (Reasoning) |
| Kemampuan | Membaca file, eksekusi shell/terminal, kontrol aplikasi |

---

*Dokumentasi ini akan terus diperbarui sesuai perkembangan fitur Haseblante AI.*
