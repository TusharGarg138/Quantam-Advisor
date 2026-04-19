# 📊 Quantum Advisor (Agentic AI Investment Advisory System)

## 🚀 Overview
Quantum Advisor is an Agentic AI-based investment advisory system that provides personalized, explainable, and risk-aware investment recommendations to retail investors.

The system uses a multi-agent architecture to analyze market data, evaluate portfolios, and generate intelligent suggestions based on user preferences and risk profile.

---

## 📸 UI Preview

### 📌 Where to add screenshots
Create a folder named `screenshots` in your project root and add your UI images there.

Project structure:

🖼️ Screenshots
🏠 Home Page
<img width="1625" height="841" alt="image" src="https://github.com/user-attachments/assets/0906126d-cff0-4053-9eed-49642e6e396b" />


📊 Dashboard
<img width="1202" height="652" alt="image" src="https://github.com/user-attachments/assets/3fec4a7e-f4dc-437a-a37b-1d05fa189b5c" />


🤖 Recommendations
<img width="1071" height="634" alt="image" src="https://github.com/user-attachments/assets/209a327c-3a15-4f53-a019-13933007322a" />

---------------------------------------------
## 🎯 Objectives
- Provide personalized investment recommendations  
- Analyze and normalize global market data  
- Use multi-agent architecture for decision-making  
- Generate explainable and ethical financial advice  

---

## 🧠 System Architecture
The system follows an Agent-Orchestrator pattern:

- Orchestrator → Manages communication between agents  
- Agents:
  - Market Analysis  
  - Portfolio Evaluation  
  - Risk Assessment  
- Backend (Flask) → Handles logic and APIs  
- Frontend (HTML/CSS) → User interface  

---

## 🛠️ Tech Stack

### Backend
- Python
- Flask
- SQLite

### Frontend
- HTML
- CSS

### Libraries
- Flask-CORS
- SQLite3

---

📂 Project Structure

Quantum_Advisor/
│
├── app.py
├── orchestrator.py
├── config.py
├── agents/
├── services/
├── database/
├── static/
├── templates/
├── screenshots/
└── README.md

---

## ⚙️ Installation & Setup

1. Clone the repository
git clone https://github.com/your-username/Quantum_Advisor.git
cd Quantum_Advisor


2. Create virtual environment
python -m venv venv

3. Activate environment  
Windows:
source venv/bin/activate   # Linux/Mac
venv\Scripts\activate      # Windows


4. Install dependencies
pip install -r requirements.txt


5. Run the app
python app.py


---

## ▶️ Usage
- Open the app in your browser  
- Register/Login  
- Enter your investment preferences  
- Get personalized recommendations  

---

## 🔍 Features
- Multi-agent AI system  
- Personalized investment advice  
- Risk-aware recommendations  
- Modular architecture  
- Simple UI  

---

## ⚠️ Limitations
- Depends on available data  
- Limited real-time integration  
- Basic UI  

---

## 🔮 Future Improvements
- Real-time market data APIs  
- Advanced ML models  
- Better UI/UX  
- Portfolio tracking  

---

## 🤝 Contributing
Feel free to fork the repo and submit a pull request.
