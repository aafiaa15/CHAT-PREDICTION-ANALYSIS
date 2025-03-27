
# **📊 WhatsApp Chat Analyzer 🚀**  
A simple **WhatsApp Chat Analyzer** that processes exported chat files and provides useful insights like **most active users, word frequency, message trends, media usage**, and more!  

---

## **📌 Features**
✅ **Total Messages, Words, and Media Count**  
✅ **Most Active Users in Group Chats**  
✅ **Word Cloud & Most Used Words**  
✅ **Daily & Monthly Message Trends**  
✅ **Emoji Usage Analysis**  
✅ **Sentiment Analysis (Optional)**  

---

## **📌 Technologies Used**
- **Python** 🐍  
- **Pandas** 📊 (Data Handling)  
- **Matplotlib & Seaborn** 📈 (Visualization)  
- **NLTK / WordCloud** ☁️ (Text Processing)  
- **Flask (Optional)** 🌐 (For Web App)  

---

## **📌 Installation & Setup**
### **1️⃣ Clone the Repository**
```bash
git clone https://github.com/YOUR_USERNAME/whatsapp-chat-analyzer.git
cd whatsapp-chat-analyzer
```

### **2️⃣ Install Required Libraries**
```bash
pip install -r requirements.txt
```

### **3️⃣ Run the Script**
```bash
python app.py
```
Or use **Jupyter Notebook** to analyze your chat step by step.  

---

## **📌 How to Export WhatsApp Chats**
1️⃣ Open the **WhatsApp chat/group** you want to analyze.  
2️⃣ Tap on **More Options (⋮) → More → Export Chat**  
3️⃣ Select **Without Media** (for better analysis)  
4️⃣ Save the `.txt` file and move it to this project folder.  

---

## **📌 Running the Analysis**
1️⃣ Place your **exported chat file** in the project folder.  
2️⃣ Run:
   ```python
   python chat_analyzer.py "whatsapp_chat.txt"
   ```
3️⃣ View the generated **graphs, statistics, and insights!**  

---

## **📌 Insights You Get**
📅 **Message Trends** – See **when** users are most active.  
💬 **Most Active Users** – Who sends the most messages?  
🔠 **Most Common Words** – What topics are discussed?  
😂 **Emoji Analysis** – Which emojis are used the most?  
📈 **Word Cloud** – A fun visual of most used words!  

---

## **📌 Future Improvements**
🔹 Web-based version using **Flask or Streamlit**  
🔹 Sentiment analysis for **positive & negative messages**  
🔹 Adding **media & link** tracking  

---

## **📌 License**
This project is licensed under the **MIT License**.  

