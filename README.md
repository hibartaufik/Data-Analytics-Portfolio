# Data Analyst Portfolio

Menganalisa COVID-19 Cases menggunakan COVID-19 dataset dari [Our World in Data](https://ourworldindata.org/) dengan rentang waktu 28 Januari 2020 - 20 September 2021. Dataset dapat diakses [disini](https://ourworldindata.org/covid-deaths). Tahapan analisa terbagi menjadi 4 tahap:
- SQL Data Exploration
- Tableau Visualization
- SQL Data Cleansing
- Python Analysing

## 1. SQL Data Exploration

### 1.1 Dataset
Download dataset pada situs Our World In Data khusus untuk COVID-19, lalu menetukan rentang waktu dataset yang akan diambil

<img width=500 src=https://user-images.githubusercontent.com/74480780/134254497-cdc353f5-f27f-4769-b2e7-21e99498b860.png>

File akan ter-download dengan extensi csv, tampilkan pada excel dengan beberapa perubahan format agar tampilan dataset pada excel berupa tabel

- comma-separated shape

<img width=500 src=https://user-images.githubusercontent.com/74480780/134254840-19f0fd4a-8a2e-451c-bb1f-01601c191e76.png>

- Perubahan menjadi tampilan tabel

<img width=500 src=https://user-images.githubusercontent.com/74480780/134255525-18e1b3a8-4da6-46bf-beec-e797c34455b0.png>

### 1.2 Membuat Tabel Baru dari Dataset Utama

Membuat dua tabel baru dari dataset utama, yaitu mengenai data kematian COVID-19 dan data vaksinasi COVID-19

- CovidDeaths.xlsx

<img width=500 src=https://user-images.githubusercontent.com/74480780/134256471-4c43c718-a55b-4de4-aa91-8104a4f1de2a.png>

- CovidVaccinations.xlsx

<img width=500 src=https://user-images.githubusercontent.com/74480780/134256531-f835053b-60eb-4efc-9005-8901719a8027.png>

### 1.3 Membuat Database dan Import Dataset

Membuat Database dengan Microsoft SQL Server Management Studio

<img width=500 src=https://user-images.githubusercontent.com/74480780/134482443-05337d06-de9f-463a-89c5-38a300ddd472.png>

Import CovidDeaths.xlxs dan CovidVaccinations.xlxs ke dalam database
