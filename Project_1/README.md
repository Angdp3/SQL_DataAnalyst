# 🎬 DVDRental SQL Analysis

Project ini bertujuan untuk mengeksplorasi database penyewaan DVD menggunakan PostgreSQL. Dataset ini disediakan oleh PostgreSQL dan cocok untuk latihan query analitis.

PREVIEW Database Diagram
![printable-postgresql-sample-database-diagram_page-0001](https://github.com/user-attachments/assets/297e1369-6846-492f-a45d-f07776561f56)



## ✅ Business Questions
- Siapa pelanggan terbaik berdasarkan total pembayaran?
- Film apa yang paling banyak disewa?
- Kategori Film Terpopuler

## 🧠 Skills Used
- Filtering (`ORDER BY, GROUP BY`)
- JOIN antar tabel (`JOIN`)
- Aggregation (`SUM`,  `COUNT`)



## 📊 Hasil Analisis

### 1. 5 Pelanggan Terbaik Berdasarkan Total Pembayaran
![Syntak 1](https://github.com/user-attachments/assets/849ba43b-e6e0-4bee-8806-96a433e1aca3)
  - Kueri menggunakan `concat`, `sum`, `join`, `group by`, `order by`, `limit`

![Query 1](https://github.com/user-attachments/assets/b8ecd325-308e-45d0-b8ab-be4adf9fa0f4)
![Pie chart 5 pelanggan teratas](https://github.com/user-attachments/assets/8110fa7f-4d14-4dfb-8e00-b6c8cb108f55)
  - Pelanggan dengan pembayaran tertinggi berasal dari kota **Eleanor Hunt**, dengan total transaksi `$211.55`.
  - Pie Chart dihasilkan langsung menggunakan postgree (!Tampilan kurang informatif)

### 2. 5 Film Paling Banyak Disewa
![Syntak 2](https://github.com/user-attachments/assets/ba895c71-e93c-477f-8d40-0efe8cca3aed)
  - Kueri menggunakan `count`, `join`, `group by`, `order by`, `limit`

![Query 2](https://github.com/user-attachments/assets/318d142c-b33c-4851-bf72-849a0768afbf)
![Pie 5 fim teratas](https://github.com/user-attachments/assets/920008ea-0745-4518-afb5-63c0bc184db6)
  - Film dengan total sewa tertinggi adalah `Bucket Brotherhood` dengan total sewa `34`
  - Pie Chart dihasilkan langsung menggunakan postgree (!Tampilan kurang informatif)

### 3. 5 Kategori Film 
![Syntak 3](https://github.com/user-attachments/assets/8701b5a0-e06f-4642-82e8-9f432c919402)
  - Kueri menggunakan `join` dengan 4 tabel

![Query 3](https://github.com/user-attachments/assets/abdbec08-9939-46ff-851a-0b2794c056a3)
![Bar Chart film kategoru](https://github.com/user-attachments/assets/f2398ff8-eede-4a43-942c-e8fc600349ec)
  - Film populer adalah `Sport` dengan total rental `1179`
  - Bar Chart dihasilkan langsung menggunakan postgree (!Tampilan kurang informatif)


