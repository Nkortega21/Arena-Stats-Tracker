# Arena-Stats-Tracker
A fun little personal project I built to track my League of Legends Arena progress using match data pulled from the Riot API. This Jupyter Notebook tracks how many champions I’ve played, how many I’ve placed first with, and how many matches it took me to get there.

# 🛡️ Arena God Tracker

This Jupyter Notebook tracks my obsession with Arena mode in League of Legends. Using the Riot API, it pulls my match history and logs every champion I’ve played, how many games they took to win, and how close I am to finishing my **Arena God** challenge.

---

## 🔍 What It Does

- Connects to Riot's API using my Riot ID and API key  
- Filters Arena matches based on a specific patch or event date  
- Parses and stores match details in a DataFrame  
- Calculates:
  - **Total Arena matches played**  
  - **Unique champions played**  
  - **Champions won with**  
  - **Wins on the first try**  
  - **Matches it took to get a win per champ**  
- Exports all data to Excel for easy tracking  

---

## 🏆 Goals Tracked

| **Goal**         | **Description**                                                 |
|------------------|-----------------------------------------------------------------|
| **Arena Legend** | Place 1st with *every* champion that can appear in Arena        |
| **Arena God**    | Place 1st with all 60 champions currently in the rotation       |

---

## 📊 Summary Output

The script automatically prints:
- **Total matches played**
- **Progress toward Arena God and Arena Legend**
- **Top 10 most played champions**
- **Top 10 champions that took the most matches to win with**
- **A full list of first-try wins**

---

## 📁 Output

All relevant data is exported to an Excel file for deeper analysis or progress tracking.  
Use it to brag (or cry) over how long it took to get that **Sett** win.

---

