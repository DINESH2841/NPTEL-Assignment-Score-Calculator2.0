# 📊 NPTEL Assignment Score Calculator 3.0

A slick React + Tailwind web app to **calculate your final NPTEL score** based on official grading rules. Fully client-side, responsive, and built with modern UI components using ShadCN and Lucide.

![Screenshot](https://github.com/DINESH2841/NPTEL-Assignment-Score-Calculator2.0/blob/main/preview_screenshot.png)

---

## 🌟 Features

- ✅ **Modern Design** – Tailwind + ShadCN UI with dark mode  
- ✅ **Live Calculations** – Real-time result updates  
- ✅ **Smart Validation** – Prevents wrong inputs  
- ✅ **Certificate Eligibility Checker**  
- ✅ **Responsive & Offline-Ready**  
- ✅ **Built with React + Vite** – Fast & lightweight

---

## 📌 How to Use

1. Select your **course duration** (4, 8, or 12 weeks)
2. Enter your **assignment marks** (comma-separated)
3. Enter your **exam score** (out of 100)
4. Click **“Calculate Final Score”**
5. See the breakdown + eligibility status instantly!

---

## 🧮 Calculation Logic

- **Assignment Score (best of):**
  - 4 weeks → best **3** scores
  - 8 weeks → best **6** scores
  - 12 weeks → best **8** scores

- **Final Score**  
  `Final = (Assignment × 0.25) + (Exam × 0.75)`

- **Eligibility Rules**
  - Assignment ≥ **10/25**
  - Exam ≥ **30/75**
  - Final Score ≥ **40/100**

---

## 🚀 Try It Out

👉 [**Launch Web App**](https://dinesh2841.github.io/NPTEL-Assignment-Score-Calculator2.0/)

> No login. No data tracking. Just scores. 🔐

---

## 🛠️ Tech Stack

| Tech       | Usage                        |
|------------|------------------------------|
| React      | UI & component logic         |
| Tailwind   | Utility-first styling        |
| ShadCN UI  | Prebuilt UI components       |
| Lucide     | Icon set                     |
| Framer Motion | Animations               |
| Vite       | Lightning-fast dev/build     |

---

## 💻 Run Locally

```bash
git clone https://github.com/DINESH2841/NPTEL-Assignment-Score-Calculator2.0.git
cd NPTEL-Assignment-Score-Calculator2.0
npm install
npm run dev
