# 🗑️ Smart Garbage Collection System (Python – OOP Based)

## 📌 Project Overview
Sylhet city’s traditional garbage collection system suffers from inefficiencies that cause environmental pollution and public inconvenience.  
This project presents a **Smart Garbage Collection System** implemented using **Python and Object-Oriented Programming (OOP)** to digitally manage garbage collection, classification, billing, and warning generation.

The system simulates **source bins**, **underground suction tunnels**, and a **central garbage management plant (GMP)** that intelligently processes waste.

---

## 🎯 Objectives
- Digitally manage garbage collection
- Automatically classify garbage by type
- Generate user billing based on garbage type
- Reduce garbage mismanagement
- Apply real-world OOP concepts using Python

---

## 🏗️ Garbage Sources
- Household
- SME (Small & Medium Enterprises)
- Industrial
- Government / NGO Offices
- Transportation

---

## 🧪 Types of Garbage
- **Biodegradable**
- **Non-Biodegradable**
  - Recyclable
  - Non-Recyclable

---

## 💰 Billing Policy

| Garbage Type | Cost per Item |
|-------------|---------------|
| Biodegradable | 0 TK |
| Recyclable | 2 TK |
| Non-Recyclable | 5 TK |

---

## ⚙️ System Components

### 👤 User
- Name and address
- Receives warning messages
- Can view total billing
- Has a personal billing catalog

### 🗑️ Source Bin
- Receives garbage from user
- Fixed capacity
- Sends garbage to GMP-bin
- Sends warning if close to full

### 🏭 GMP Bin
- Central garbage management unit
- Separates garbage into:
  - Biodegradable Bin (B-bin)
  - Non-Biodegradable Bin (NB-bin)
- Sends warnings to source bins
- Updates user billing

### 🌱 B-bin (Biodegradable)
- Unlimited capacity
- Sends garbage to processing plant

### ♻️ NB-bin (Non-Biodegradable)
- Fixed capacity
- Separates garbage into:
  - R-bin (Recyclable)
  - NR-bin (Non-Recyclable)
- Sends warning to GMP-bin
- Updates billing

### 🔄 R-bin & 🚫 NR-bin
- Unlimited capacity
- Send garbage to plant for processing

---

## ✨ Key Features
- Object-Oriented Programming (OOP)
- Inheritance and encapsulation
- Inter-bin communication
- Warning message propagation
- Automated billing system
- Bonus: User login system
- Google Colab compatible

---

## 🛠️ Technologies Used
- Python 3
- OOP Concepts
- Google Colab

---

## ▶️ How to Run (Google Colab)

1. Go to https://colab.research.google.com
2. Create a **New Notebook**
3. Paste the entire project code into a **single code cell**
4. Run the cell using:
5. Observe garbage flow, warnings, and billing output

---

## 📂 Project Structure

---

## 📊 Sample Output
Login successful

Biodegradable garbage sent to plant

Recyclable garbage sent to plant

Non-recyclable garbage sent to plant


--- Billing Summary ---

biodegradable: 2 items → 0 TK

recyclable: 2 items → 4 TK

non_recyclable: 1 items → 5 TK

TOTAL BILL: 9 TK


---

## 🧠 Concepts Demonstrated
- Classes & Objects
- Inheritance
- Encapsulation
- Local & Global Variables
- Conditional Statements
- Loops
- Data Structures

---

## 🚀 Future Improvements
- Menu-driven user interaction
- Multiple users and bins
- Database integration
- Web-based dashboard
- IoT sensor simulation

---

## 👨‍💻 Author
**Rashedul Albab**  
Sylhet, Bangladesh

---

## 📜 License
This project is developed for **academic and educational purposes only**.

