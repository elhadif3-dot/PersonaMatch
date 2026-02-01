<div align="center">

# 🌍 PersonaMatch
### Persona-Oriented Urban Context Scoring for Airbnb Listings

🔗 **Live Demo**: https://persona-match-6b33514a.base44.app

[![Python](https://img.shields.io/badge/Python-3.9+-blue.svg)]
[![PySpark](https://img.shields.io/badge/PySpark-3.x-orange.svg)]
[![Databricks](https://img.shields.io/badge/Platform-Databricks-red.svg)]
[![Course](https://img.shields.io/badge/Course-Data%20Collection%20%26%20Management%20Lab-green.svg)]

**Technion – Israel Institute of Technology**  
Data Collection & Management Lab (00940290)

</div>

---

## 🧠 Project Idea

**PersonaMatch** is a data-driven system that evaluates Airbnb listings **through the lens of different user personas**,  
by combining **internal Airbnb data** with **external urban signals** such as Google Maps reviews, neighborhood context, and semantic text analysis.

---

## 🎯 Core Contribution

The key contribution of this project is a **persona-aware scoring pipeline** that:
- Separates **expectations** from **reality**
- Aggregates **urban context signals**
- Produces **persona-specific relevance scores**

---

## 🧩 Personas Modeled

- 🧍 Singles  
- 💑 Couples  
- 👨‍👩‍👧 Families  
- 💻 Remote Workers  

---

## 🗂️ Data Sources (High Level)

⚠️ **No data is included in this repository.**

- Internal Airbnb listings data  
- External Google Maps reviews  
- Urban spatial context  

All data is stored externally (Azure / Databricks).

---

## 🧪 Methodology Overview

1. Secure data loading from Azure  
2. Text vectorization using GloVe embeddings  
3. Persona-based lexical matching  
4. Spatial and semantic aggregation  
5. Persona-oriented scoring  

---

## ▶️ How to Run

1. Upload notebook to Databricks  
2. Insert your SAS token in the config cell  
3. Run all cells  

---

## 🔐 Security Notice

- No credentials stored  
- No datasets published  
- Code only  

---

## 📍 Live Demo

👉 https://persona-match-6b33514a.base44.app

---

## 🏁 Summary

PersonaMatch demonstrates how **persona-aware urban intelligence**  
can improve personalization in short-term rentals.
