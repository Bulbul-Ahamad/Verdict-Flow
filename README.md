![VerdictFlow Banner](banner.png)
# 🚀 VerdictFlow

**Track • Analyze • Improve**

VerdictFlow is a Python-based analytics tool designed to help competitive programmers analyze their Codeforces submissions and improve their problem-solving skills using data-driven insights.

---

## 📌 About the Project

**VerdictFlow** fetches submission data from Codeforces and provides a detailed analysis of a user's performance.  
It highlights strengths, identifies weak areas, and visualizes trends to help programmers practice more effectively.

---

## ✨ Features

- Track total submissions, solved problems, and unique attempts  
- Verdict analysis (AC, WA, TLE, MLE, CE, RE)  
- Tag-wise problem analysis  
- Weak tag identification using acceptance ratio  
- Programming language usage analysis  
- Visual insights for better decision-making  

---

## 📊 Analysis Overview

### 🔹 Submission Summary
- Total submissions  
- Unique problems attempted  
- Total problems solved  

### 🔹 Verdict Distribution
- Accepted (OK)  
- Wrong Answer  
- Time Limit Exceeded  
- Compilation Error  
- Runtime Error  
- Memory Limit Exceeded  

### 🔹 Tag Analysis
- Most frequently attempted tags  
- Tags with the highest wrong answers  
- Tags causing the most TLEs  
- Weak tags based on low acceptance ratio  

### 🔹 Language Usage Analysis
- Number of submissions per programming language  

---

## 🛠️ Tech Stack

- **Programming Language:** Python  
- **Libraries:**  
  - requests  
  - pandas  
  - matplotlib / seaborn  
- **Data Source:** Codeforces API  

---

## ⚙️ How to Run

1. Clone the repository
   ```bash
   git clone https://github.com/your-username/VerdictFlow.git
   cd VerdictFlow
