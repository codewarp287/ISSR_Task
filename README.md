**GSoC Candidate Assessment Submission**  

## 📌 Overview  
This project analyzes crisis-related social media discussions, applying **NLP, sentiment analysis, and geospatial mapping** to detect mental health distress trends.  

---

## ✅ Tasks & Deliverables  

### **1️⃣ Data Extraction & Preprocessing**  
- Retrieved crisis-related posts from **Reddit** using it's API.  
- Filtered posts using **mental health keywords** (e.g., *depressed, overwhelmed, suicidal*).  
- Cleaned and pre-process text and stored structured data in **CSV format**.  

### **2️⃣ Sentiment & Crisis Risk Classification**  
- Applied **TextBlob** for sentiment classification.  
- Categorized posts into **High, Moderate, or Low Risk** using BERT embeddings of the posts.    

### **3️⃣ Geolocation & Crisis Mapping**  
- Extracted locations from **NLP-based place recognition**.  
- Generated:  
  - 🗺️ **Heatmap of all crisis discussions**  
  - 📍 **Top 5 crisis locations mapped separately**  
