
## **Cuisine Recommender App 🍽️**  

A simple **Streamlit web app** that provides information about traditional cuisines of different countries. This app uses **LangChain** with **Ollama's Mistral model** to generate cuisine descriptions in a specified language and number of paragraphs.  

---

### **📌 Features**
- Get information about **traditional cuisines** from a given country.  
- Generate responses in **multiple languages**.  
- Choose the **number of paragraphs** for the response.  
- Uses **LangChain's Ollama integration** for AI-powered text generation.  

---

### **🚀 Installation & Setup**  

#### **1️⃣ Clone the Repository**  
```bash
git clone https://github.com/vaishnavidesai09/cuisine_recommender.git
cd cuisine_recommender
```

#### **2️⃣ Create a Virtual Environment (Optional but Recommended)**
```bash
python -m venv venv
source venv/bin/activate   # On macOS/Linux
venv\Scripts\activate      # On Windows
```

#### **3️⃣ Install Dependencies**  
```bash
pip install -r requirements.txt
```

#### **4️⃣ Run the Application**  
```bash
streamlit run app.py
```

---

### **📜 Usage**
1. **Enter a country** name in the text box.  
2. **Specify the number of paragraphs** (1 to 5).  
3. **Choose the language** for the response.  
4. Click **Enter**, and the app will generate information about the country's traditional cuisine.  

---

### **🛠️ Dependencies**
- `streamlit`
- `langchain`
- `langchain_ollama`

You can install them using:
```bash
pip install streamlit langchain langchain_ollama
```

---

### **💡 Example**
**Input:**  
- Country: **Italy**  
- No. of paragraphs: **2**  
- Language: **English**  

**Output:**  
*"Italy is famous for its diverse and flavorful cuisine, which varies by region. Some of the most well-known traditional dishes include pasta, pizza, and risotto..."*  

---

### **📌 Future Enhancements**
- Add **more customization options** (e.g., dish type, ingredients).  
- Improve **response formatting**.  
- Support for **image generation** of dishes.  

---

### **🤝 Contributing**
Contributions are welcome! Feel free to fork the repo, open an issue, or submit a pull request.  

---

### **📜 License**
This project is licensed under the **MIT License**.  

