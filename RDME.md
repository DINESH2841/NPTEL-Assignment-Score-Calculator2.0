# 📊 NPTEL Assignment Score Calculator 2.0

A sleek, fully client-side web app to **calculate your final NPTEL course score** based on your assignment and exam marks. It auto-checks **certificate eligibility** using NPTEL’s official rules — no backend, no fuss.  

![Demo Screenshot](https://github.com/DINESH2841/NPTEL-Assignment-Score-Calculator2.0/blob/main/preview_screenshot.png)

---

## 🌟 Features

✅ **Modern UI** – Clean, glassmorphism-inspired layout  
✅ **Live Calculations** – Scores update as you type  
✅ **Smart Validation** – Catches input errors instantly  
✅ **Certificate Checker** – Tells you if you're eligible  
✅ **100% Offline-Ready** – Runs entirely in your browser  

---

## 📌 How It Works

1. **Pick Course Duration**: 4, 8, or 12 weeks  
2. **Drop Your Assignment Marks**: Like `85, 90, 78, ...`  
3. **Enter Your Exam Score**: Out of 100  
4. **Click “Calculate Final Score”** – Boom, results 🔥

---

### 📐 Calculation Logic

- **Assignment Average** (Best of):
  - 🟩 4 weeks → Best **3** assignments  
  - 🟦 8 weeks → Best **6** assignments  
  - 🟥 12 weeks → Best **8** assignments  

- **Final Score**:
  - 📘 Assignment Weight: `25%`  
  - 📙 Exam Weight: `75%`

- **Eligibility Criteria**:
  - ✅ Min **10/25** in assignments  
  - ✅ Min **30/75** in exam  
  - ✅ Final total score ≥ **40/100**

---

## 🚀 Try It Live

👉 [**Launch Web App**](https://dinesh2841.github.io/NPTEL-Assignment-Score-Calculator2.0/)  
_(Built with love & logic – no login, no data tracking!)_

---

## 🛠️ Tech Stack

- **HTML5** – Clean semantic structure  
- **CSS3** – Glassmorphism styling & responsive layout  
- **JavaScript (Vanilla)** – Logic, calculations, validation

---

## 💻 Local Installation

Want to run it offline? Easy:

```bash
git clone https://github.com/DINESH2841/NPTEL-Assignment-Score-Calculator2.0.git
cd NPTEL-Assignment-Score-Calculator2.0
open index.html   # Or just double-click the file
