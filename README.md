# UNCOVERING HIGH-VALUE ACCOUNTS IN AWS SAAS ECOSYSTEM

Created by:
Risman Ariska Sultani
(*This notebook is an updated version of the AWS SaaS Customer Value Segmentation Project – Capstone Module 3 Purwadhika Digital Technology School, revised and reuploaded from the original source*.)

## Company Background & Business Context
Amazon Web Services (AWS) adalah divisi layanan cloud computing dari Amazon.com, Inc. yang menyediakan solusi Software as a Service (SaaS), Platform as a Service (PaaS), dan Infrastructure as a Service (IaaS) bagi individu, bisnis, dan lembaga di seluruh dunia.
Sejak diluncurkan pada tahun 2006, AWS menjadi pelopor industri cloud computing dengan lebih dari 200 layanan berbasis langganan (subscription-based) yang membantu pelanggan mengakses aplikasi, data analytics, dan infrastruktur tanpa perlu mengelola server fisik.
Sebagai pemimpin global di bidang Software as a Service (SaaS), Amazon Web Services (AWS) telah menjadi fondasi utama bagi transformasi digital di berbagai sektor industri. Dari startup teknologi hingga korporasi multinasional, pelanggan di seluruh dunia mengandalkan layanan AWS. Namun beberapa waktu terakhir dikarenakan karena fenomena **winter tech** membuat dinamika pasar SaaS menjadi tidak pasti.

## Problem Statement
Sebagai respons terhadap kondisi fenomena *winter tech*, rangkaian masalah yang akan dijawab dalam analisa ini adalah:

1. Mengidentifikasi siapa pelanggan dengan nilai tertinggi (**High-Value Customers**) berdasarkan data transaksi historis AWS.
2. Menganalisis karakteristik dan pola perilaku **High-Value Customer** potensial berdasarkan faktor Industri, wilayah dan volume penjualan(sales)
3. Merumuskan strategi retensi dan komunikasi promosi yang paling efektif untuk mempertahankan dan meningkatkan **lifetime value (LTV)** **High Value Customer** tersebut.

## Goals
Analisis ini diharapkan dapat merumuskan strategi berbasis data (data-driven strategy) yang mampu memperkuat profitabilitas AWS di tengah tantangan pasar SaaS global yang semakin kompetitif.

## Analytic Approach


### Data Preparation
- Pembersihan data *(handling missing value, outlier, dan duplikasi)*.  
- *Feature engineering* dengan menambahkan variabel:
  - **Length**
  - **Recency**
  - **Frequency**
  - **Monetary**
  - **Year**

---

### Segmentation Analysis
- Menggunakan metode **LRFM Scoring (1–4)** untuk menilai pelanggan berdasarkan empat dimensi utama.  
- Mengelompokkan pelanggan menjadi tiga segmen:
  - **High-Value Customers**
  - **Mid-Value Customers**
  - **Low-Value Customers**

---

### Customer Profiling
- Menganalisis pola **industri**, **region**, dan **volume penjualan** setiap segmen pelanggan.  
- Mengidentifikasi **pelanggan prioritas** yang berpotensi menjadi target program **retensi dan loyalitas**.

---

## 📈 Key Metrics

| **Metric** | **Description** |
|-------------|----------------|
| **Length** | Durasi hubungan pelanggan (dalam hari) sejak transaksi pertama. |
| **Recency** | Jarak waktu (dalam hari) sejak transaksi terakhir. |
| **Frequency** | Jumlah transaksi selama periode analisis. |
| **Monetary** | Nilai profit kumulatif pelanggan. |
| **LRFM Score (1–4)** | Skor agregat untuk menentukan nilai pelanggan. |

---

## Key Findings
- **High-Value Customers** menunjukkan pola transaksi **stabil dan sering**, tetapi beberapa mulai memperlihatkan peningkatan nilai **Recency** → indikasi potensi churn.  
- Industri **Healthcare, Financial, dan Manufacturing** mendominasi segmen pelanggan dengan profit tertinggi.  
- **Mid-Value Customers** memiliki peluang besar untuk ditingkatkan menjadi **High-Value** melalui **personalized marketing**.  
- Pendekatan **LRFM** memungkinkan tim AWS memfokuskan strategi **retensi berbasis profitabilitas**, bukan sekadar jumlah pelanggan.  

---

## Business Impact

Implementasi model segmentasi **LRFM** memberikan dampak signifikan bagi AWS:

- **Identifikasi High-Value Accounts** dengan kontribusi terbesar untuk prioritas retensi.  
- **Peningkatan Customer Lifetime Value (CLV)** dan stabilitas profit jangka panjang.  
- **Pengambilan keputusan lebih cepat dan terukur** melalui *data-driven insights*.  

