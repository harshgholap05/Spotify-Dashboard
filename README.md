# Spotify-Dashboard (PowerBI, Excel, PowerQuary, DAX)

**This project transforms Spotify’s **Top 50 dataset** into an **interactive dashboard** that helps stakeholders (music analysts, playlist managers, marketing teams) gain actionable insights. The dashboard enables monitoring of KPIs, song/artist performance, trends, and comparisons in an easy-to-understand format.**


## 🚀 Problem Statement

Spotify’s raw dataset provides only **lists & rankings**, making it difficult to track KPIs, trends, or compare performances.
Key challenges solved:

* ❌**No clear KPI monitoring** → ✅ Dashboard with **Total Songs, Distinct Artists, Popularity, Duration**.
* ❌ **No explicit vs non-explicit analysis** → ✅ Compare **explicit vs clean songs**.
* ❌ **No visibility of song/album distribution** → ✅ Breakdown by **album type & year**.
* ❌ **Missing trend insights** → ✅ Track **monthly & yearly popularity trends**.
* ❌ **Artist vs Song-level gap** → ✅ Drill-down to detailed **artist/song pages**.

## 🏠 Home Dashboard

<img width="1324" height="760" alt="Screenshot 2025-09-28 122036" src="https://github.com/user-attachments/assets/a3d0c961-2a23-4d20-b595-11fb111041b6" />

##

     📊 Overview Dashboard
     🎙️ Artists Dashboard
     🎵 Songs Dashboard

---

## 📊 Overview Dashboard 

**The Overview Dashboard contains information on individual Spotify tracks, including artist name, duration, popularity, album type and explicit and Non-explicit content. It helps analyze music trends, artist contributions, popularity distribution, and listener preferences.**

<img width="1424" height="805" alt="Screenshot 2025-09-28 123211" src="https://github.com/user-attachments/assets/b83a41ad-d743-49eb-bdb5-9463218c8bce" />



## 👉 KPIs Supported in Overview Dashboard
* **Songs (Songs by Artists)** – The list of songs along with their respective artists.
* **Total Distinct Songs** – The total number of unique songs in the dataset. Helps in understanding overall track availability.
* **Count of Artists** – The total number of unique artists. Useful for analyzing artist diversity and contributions.
* **Average Duration** – The mean length of songs. Helps identify duration trends across tracks.
* **Average Popularity** – The mean popularity score of songs. Useful for measuring general audience engagement.
* **Songs by Artist (Distinct Songs)** – The number of unique songs created by each artist. Helps identify top-contributing artists.
* **Songs by Popularity** – Classification of songs based on popularity scores. Useful for trend analysis of hit vs. less popular songs.
* **Songs by Album Type** – Distribution of songs across different album types (Album, Single, Compilation).
* **Explicit vs. Non-Explicit Songs** – Comparison between explicit and clean tracks. Helps analyze listener preferences and content mix.
* **Songs by Year** – Number of songs released each year. Useful for identifying release patterns over time.
* **Average Popularity by Album Type** – Comparison of average popularity scores across different album types.
* **Average Popularity by Month** – Average popularity trend across months. Helps track seasonal listening patterns.
* **Month / Quarter (Slicer Option)** – A filter option that enables time-based analysis by month or quarter.
* **Distinct Songs by Month** – Number of unique songs released each month. Useful for understanding monthly release trends.

---

## 🎙️ Artists Dashboard 

**The Artist Dashboard table contains aggregated artist-level metrics about their songs, albums, and popularity. It is useful for understanding listening behavior, top artists, and music distribution.**

* **Artist Name** – The performer or band name 

* **Total Songs** – Count of all unique songs by the artist.

* **Songs per Artist** – Average share of songs contributed by each artist relative to dataset.

* **Total Popularity** – Sum of popularity scores across all songs of the artist.

* **Avg Popularity** – Average popularity score of the artist’s songs. Shows consistency in success.

* **Albums Count **– Number of albums linked to the artist.

* **Avg Tracks per Album** – Average number of tracks per album for the artist.

* **Album Type Distribution** – Count of songs by type (Album, Single, Compilation, etc.) for that artist.

* **Most Popular Song Name** – Name of the artist’s highest-popularity track.
  
## 
<img width="1426" height="805" alt="Screenshot 2025-09-28 123225" src="https://github.com/user-attachments/assets/01429675-79c7-4951-8277-905e9233bdc8" />

## 👉 KPIs Supported in Artist Dashboard

* **Songs by Artist** → Total Songs / Songs per Artist

* **Popularity by Artist** → Total Popularity + Avg Popularity

* **Album Type Split** → Album Type Distribution

* **Artist Productivity** → Albums Count + Avg Tracks per Album

* **Most Popular Song** → Most Popular Song Name

---

## 🎵 Songs Dashboard
**The Songs Dashboard contains information on individual tracks, their artists, release details, album type, popularity, and duration. It helps analyze artist contributions, track performance, and yearly song release trends.**

<img width="1424" height="805" alt="Screenshot 2025-09-28 123241" src="https://github.com/user-attachments/assets/c52d1e72-07a8-4b15-92da-f38596019150" />

## 👉 KPIs Supported in Songs Dashboard

* **Songs (Songs by Artist)** – List of songs with their respective artists.

* **Songs by Artist (Distinct Artists by Songs)** – Count of distinct artists based on their songs.

* **Total Songs by Artist (Sum of Popularity)** – Total popularity score of all songs per artist.

* **Songs Hit per Artist (Position 1)** – Tracks ranked at the top position for each artist.

* **Song Name, Release Date, Album Type (Single, Album)** – Details of track identity, release timing, and album classification.

* **Average Popularity** – Mean popularity score across songs.

* **Average Duration (Minutes)** – Mean length of tracks in minutes.

* **Songs per Year** – Total number of songs released each year.

* **Total Songs by Artist** – Count of songs contributed by each artist.


## 🛠️ Tools & Technologies

* **Power BI**
* **Excel** 
* **PowerQuery**
* **DAX**
* **Chatgpt**
