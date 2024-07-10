# Capstone-Project-Modul-2

# 1. Latar Belakang dan Rumusan Masalah

Transjakarta adalah sistem transportasi bus rapid transit (BRT) di Jakarta yang melayani jutaan penumpang setiap harinya. Data transjakarta ini dapat memberikan wawasan berharga tentang pola penggunaan, efisiensi operasional, dan kepuasan pelanggan. Analisis data ini penting untuk meningkatkan layanan dan membuat keputusan yang lebih baik.

# 2. Tujuan
- Mengidentifikasi dan menangani anomali dalam data pola penggunaan Transjakarta.
- Melakukan visualisasi data untuk memahami distribusi.
- Melakukan analisis statistik untuk mendapatkan insight yang dapat digunakan untuk meningkatkan layanan Transjakarta.
- Memberikan rekomendasi yang dapat diimplementasikan oleh manajemen Transjakarta.

# 3. Data
Transjakarta.csv
1.	transID: Unique transaction id for every transaction
2.	payCardID: Customers main identifier. The card customers use as a ticket for entrance and exit.
3.	payCardBank: Customers card bank issuer name
4.	payCardName: Customers name that is embedded in the card.
5.	payCardSex: Customers sex that is embedded in the card
6.	payCardBirthDate: Customers birth year
7.	corridorID: Corridor ID / Route ID as key for route grouping.
8.	corridorName: Corridor Name / Route Name contains Start and Finish for each route.
9.	direction: 0 for Go, 1 for Back. Direction of the route.
10.	tapInStops: Tap In (entrance) Stops ID for identifying stops name
11.	tapInStopsName: Tap In (entrance) Stops Name where customers tap in.
12.	tapInStopsLat: Latitude of Tap In Stops
13.	tapInStopsLon: Longitude of Tap In Stops
14.	stopStartSeq: Sequence of the stops, 1st stop, 2nd stops etc. Related to direction.
15.	tapInTime: Time of tap in. Date and time
16.	tapOutStops: Tap Out (Exit) Stops ID for identifying stops name
17.	tapOutStopsName: Tap out (exit) Stops Name where customers tap out.
18.	tapOutStopsLat: Latitude of Tap Out Stops
19.	tapOutStopsLon: Longitude of Tap Out Stops
20.	stopEndSeq: Sequence of the stops, 1st stop, 2nd stops etc. Related to direction.
21.	tapOutTime: Time of tap out. Date and time
22.	payAmount: The number of what customers pay. Some are free. Some not.

# 4. Proses
## A. Data Cleaning
a. Identifikasi dan Penanganan Missing Values
b. Identifikasi dan Penanganan Outliers
c. Data Formatting
d. Identifikasi dan Penanganan Data Duplikat
## B. Data Visualisation
- Menggunakan histogram untuk distribusi waktu penggunaan
- Menggunakan line plot untuk melihat tren penggunaan harian
## C. Analisis
a. Statistika Deskriptif
b. Statistika Inferensial

# 6. Rekomendasi dan Insight
Jam sibuk pagi: 6:00 - 7:00
Jam sibuk sore: 17:00 - 18:00
Rekomendasi:
1. Penambahan armada pada jam sibuk pagi dan sore hari untuk mengurangi kepadatan.
2. Penyesuaian jadwal keberangkatan untuk mengakomodasi peningkatan jumlah penumpang pada jam sibuk.
3. Peningkatan layanan pelanggan dengan menyediakan informasi real-time tentang jadwal dan ketersediaan armada.

Link Visualisasi Tableau : https://public.tableau.com/app/profile/gugun.muhammad.fauzi/viz/DashboardTransjakarta-PurwadhikaJCDSOL-14-GugunMuhammadFauzi/Dashboard1?publish=yes

