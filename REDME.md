# 📊 NPTEL Assignment Score Calculator 3.0

A slick React + Tailwind web app to **calculate your final NPTEL score** based on official grading rules. Fully client-side, responsive, and built with modern UI components using ShadCN and Lucide.

![Screenshot](https://github.com/DINESH2841/NPTEL-Assignment-Score-Calculator2.0/blob/main/preview_screenshot.png)

---
🧠 Creator
Made with 💙 by @DINESH2841(https://github.com/DINESH2841)
## 🌟 Features

- ✅ **Modern Design** – Tailwind + ShadCN UI with dark mode  
- ✅ **Live Calculations** – Real-time result updates  
- ✅ **Smart Validation** – Prevents wrong inputs  
- ✅ **Certificate Eligibility Checker**  
- ✅ **Auto Certificate Type Detection**  
- ✅ **Responsive & Offline-Ready**  
- ✅ **Built with React + Vite** – Fast & lightweight

---

## 📌 How to Use

1. Select your **course duration** (4, 8, or 12 weeks)
2. Enter your **assignment marks** (comma-separated)
3. Enter your **exam score** (out of 100)
4. Click **“Calculate Final Score”**
5. See your final score, certificate eligibility, and exact certificate type!

---

## 🧮 Calculation Logic

- **Assignment Score (best of):**
  - 4 weeks → best **3** scores
  - 8 weeks → best **6** scores
  - 12 weeks → best **8** scores

- **Final Score Formula**  
  `Final = (Assignment × 0.25) + (Exam × 0.75)`

---

## 🏆 Eligibility & Certificate Type

To be eligible for a certificate:

- 🟢 **Assignment Score** ≥ 10 / 25  
- 🟢 **Exam Score** ≥ 30 / 75  
- 🟢 **Final Score** ≥ 40 / 100  

Once eligible, your **certificate type** is decided by final score:

| Final Score     | Certificate Type        |
|------------------|-------------------------|
| `≥ 90`           | 🥇 **Elite + Gold**      |
| `75 - 89`        | 🥈 **Elite + Silver**    |
| `60 - 74`        | 🟦 **Elite**             |
| `40 - 59`        | ✅ **Successfully Completed** |
| `< 40` or not eligible | ❌ **No Certificate**    |

---

## 🚀 Try It Live

👉 [**Launch Web App**](https://dinesh2841.github.io/NPTEL-Assignment-Score-Calculator2.0/)

> No login. No tracking. Just real results.

---

## 🛠️ Tech Stack

| Tech       | Usage                        |
|------------|------------------------------|
| React      | UI & component logic         |
| Tailwind   | Utility-first styling        |
| ShadCN UI  | Prebuilt UI components       |
| Lucide     | Icon set                     |
| Framer Motion | Smooth animations         |
| Vite       | Fast dev & build pipeline    |

---

## 💻 Run Locally

```bash
git clone https://github.com/DINESH2841/NPTEL-Assignment-Score-Calculator2.0.git
cd NPTEL-Assignment-Score-Calculator2.0
npm install
npm run dev
