
![Python](https://img.shields.io/badge/Python-3.10%2B-blue)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Preprocessing-150458)
![PowerBI](https://img.shields.io/badge/Power%20BI-Dashboard-F2C94C)
![Status](https://img.shields.io/badge/Status-Completed-success)

# Strategic Customer Segmentation & RFM Analytics

Repositori ini berisi proyek analisis data komprehensif untuk mengelompokkan pelanggan *Superstore* menggunakan metode **RFM Analysis (Recency, Frequency, Monetary)**. Proyek ini bertujuan untuk membantu tim manajemen memahami perilaku belanja pelanggan, mengidentifikasi kelompok pelanggan paling bernilai, serta merancang strategi pemasaran berbasis data yang tepat sasaran.

---

##  Fitur & Tahapan Analisis
1. **Data Cleaning & Preprocessing:** Pembersihan tipe data tanggal, penanganan format desimal mata uang (*Sales* & *Profit*), serta validasi basis data unik pelanggan (*unique customer_id* = **793 pelanggan**).
2. **RFM Scoring (Quartile 1-5):** Pemberian skor *Recency*, *Frequency*, dan *Monetary* menggunakan metode `pd.qcut` untuk memastikan distribusi objektif tanpa bias dari nilai ekstrem (*outliers*).
3. **Segmentasi Pelanggan:** Pengelompokan basis pelanggan ke dalam 6 kategori strategis:
   - *Champions*
   - *Loyal Customers*
   - *Potential Loyalist*
   - *Recent Customers*
   - *At Risk*
   - *Lost Customers*
4. **Visualisasi Data & Dashboard:** Visualisasi interaktif menggunakan Python (`Matplotlib`, `Seaborn`) untuk memetakan hubungan antara jumlah pelanggan, resensi, dan kontribusi pendapatan (*Total Revenue*).

---

##  Ringkasan Performa Segmen Pelanggan

| Segmen Pelanggan | Jumlah Pelanggan | Proporsi (%) | Total Revenue | Avg Recency | Avg Frequency |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **Champions** | 89 | 11.22% | Rp 284.6M | 25 Hari | 9.4 Order |
| **Potential Loyalist** | 136 | 17.15% | Rp 228.5M | 78 Hari | 7.1 Order |
| **At Risk** | 145 | 18.28% | Rp 214.0M | 221 Hari | 7.5 Order |
| **Loyal Customers** | 190 | 23.96% | Rp 207.4M | 27 Hari | 6.8 Order |
| **Lost Customers** | 171 | 21.56% | Rp 160.3M | 378 Hari | 3.7 Order |
| **Recent Customers** | 62 | 7.82% | Rp 36.8M | 43 Hari | 3.2 Order |

---

##  Temuan Strategis & Implikasi Bisnis
* **Core Revenue Engines:** Kombinasi segmen *Champions* dan *Potential Loyalist* menyumbang lebih dari 45% total pendapatan (*Revenue*), sehingga memerlukan program VIP eksklusif untuk menjaga retensi.
* **Ancaman Revenue Leakage:** Segmen *At Risk* mencakup 18.28% basis pelanggan dengan nilai belanja yang besar (Rp 214.0M) namun memiliki resensi rata-rata 221 hari, menuntut kampanye reaktivasi segera.
* **Peluang Onboarding:** *Recent Customers* memiliki keaktifan resensi yang baik (43 hari) namun frekuensi rendah, sehingga membutuhkan alur *welcome email* dan insentif agar beralih menjadi *Loyal Customers*.

---

##  Teknologi yang Digunakan
* **Bahasa Pemrograman:** Python 3 (Google Colab)
* **Business Intelligence:** Power BI (Interactive Dashboard & Data Modeling)
* **Pustaka Utama (Libraries):** Pandas, NumPy, Matplotlib, Seaborn
* **Environment:** Google Colab
* **Presentasi:** Canva Presentation (13 Slide Profesional)

---

## 👤 Author
**Joko Santoso**
* Email: santosoj160@gmail.com
* 💻 **Google Colab Notebook:** [Customer Segmentation RFM Analysis.ipynb](https://colab.research.google.com/drive/1BNZFEzJQW7hLKybvd2eZLCKWrjHTaHSy?usp=sharing)
* 🔗 **Business Report :** [Business Report](https://canva.link/tcvfr88imlxodph)
* 🔗 **Linkedin :** [LinkedIn Profile](http://www.linkedin.com/in/joko-santoso160)
