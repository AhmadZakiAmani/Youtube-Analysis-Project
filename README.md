<a id="top"></a>

<details>
  <summary>🇬🇧 Read In English (Click to open)</summary>
  <br>

---
</details>

<details>
  <summary>🇮🇩 Baca dalam Bahasa Indonesia (Klik untuk membuka)</summary>
  <br>

# Dashboard Analisis Saluran YouTube

## 🚀 Ringkasan Proyek

Proyek ini adalah sebuah dasbor analitik kustom yang dirancang untuk memantau dan membandingkan kinerja saluran YouTube. Solusi ini mengatasi keterbatasan antarmuka asli YouTube dengan menyediakan tampilan terkonsolidasi dan fitur perbandingan berdampingan antar kreator, yang didukung oleh data langsung dari YouTube Data API.

**✨ Untuk studi kasus lengkap, visualisasi akhir, dan penjelasan mendalam, silakan kunjungi [Portofolio Notion Saya](https://www.notion.so/YouTube-Channel-Analysis-Dashboard-Project-2876e9f3bfd680a081b8cd3d105d50c3?source=copy_link).**

---

## 📝 Workflow Proyek

**YouTube Data API → Power Query (M) → Power BI (Visualisasi)**

1.  **Extract:** Data metrik saluran dan video diambil secara dinamis dari YouTube Data API.
2.  **Transform:** Power Query (M) digunakan untuk membersihkan, mentransformasi, dan menstrukturkan data JSON yang diterima dari API.
3.  **Load & Visualize:** Data yang sudah bersih dimuat ke dalam model data Power BI dan divisualisasikan menjadi dasbor interaktif dengan beberapa halaman.

---

## 🛠️ Tech Stack & Tools

* **Visualisasi & Analisis:** Power BI
* **Data Collection & ETL:** Power Query (M)
* **Sumber Data:** YouTube Data API

---

## 📂 Struktur Repositori
```
YouTube-Analysis-Project/
├── README.md                   # Penjelasan utama proyek ini
│
├── docs/                       # Berisi semua dokumentasi & screenshot
|   ├── Youtube Dashboard.png    
│   ├── Home.png                
│   ├── Video.png               
│   └── Channel_vs_Channel.png  
│
├── power bi/                   # Berisi file sumber Power BI
│   └── YouTube Dashboard.pbit  # File template Power BI (tanpa data)
│
└── power query scripts/        # Berisi logika query untuk pengambilan data
    └── youtube api calls.m     # Skrip Power Query (M) untuk panggilan API
```
## 📊 Visualisasi Dasbor

Berikut adalah cuplikan dari beberapa halaman utama dasbor:

**Halaman Utama (Home Page)**
*Menampilkan detail dari saluran yang dipilih beserta daftar videonya.*
![Home Page](docs/Home.gif)

**Halaman Perbandingan (Channel vs Channel)**
*Menyajikan perbandingan berdampingan antara dua saluran yang dipilih secara dinamis.*
![Channel vs Channel Page](https://github.com/AhmadZakiAmani/Youtube-Analysis-Project/blob/main/docs/Channel%20vs%20Channel.gif)

---

## 🙍 Tentang Saya

Halo, saya **Ahmad Zaki Amani** 👋

✨ Saya memiliki ketertarikan besar pada bidang **Data Analytics** dan **Business Intelligence**, khususnya dalam membangun dashboard, membuat visualisasi data, dan mengubah data mentah menjadi insight yang bermanfaat.

💡 Proyek ini merupakan bagian dari portofolio saya, yang menampilkan keterampilan dalam:

* Visualisasi data & storytelling
* Perancangan dashboard (Power BI, Tableau)
* Transformasi & analisis data
* Solusi Business Intelligence

📫 Mari terhubung dan berkolaborasi!

[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge\&logo=gmail\&logoColor=white)](mailto:ahmadzaki27.az@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge\&logo=linkedin\&logoColor=white)](https://www.linkedin.com/in/ahmad-zaki-amani-ab091635b/)
[![Notion](https://img.shields.io/badge/Notion-000?logo=notion&logoColor=fff)](https://www.notion.so/Portofolio-Data-Analysis-1e26e9f3bfd680fb9c92f7dc6734a391?source=copy_link)
---

<p align="right"><a href="#top">Back To Top ⬆️</a></p>  
</details>
