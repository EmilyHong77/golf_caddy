# golf_caddy
Computer vision-powered golf caddy, in your pocket! Simple, data-driven swing tips and tools for beginners.

Upload your swing video → it extracts your body pose → compares your key angles to a professional reference → gives gentle improvement suggestions.  

## Features
⛳️ Upload a front-facing golf swing video  
💀 Extracts skeleton using MediaPipe Pose  
📐 Computes key angles: spine tilt, lead arm angle, shoulder rotation  
🏌️ Compares your swing vs a pro template  
✅ Outputs basic tips for improvement  

---

## 🚀 How to Run

# **1. Clone the repo:**
```bash
  git clone https://github.com/yourusername/golf_swing_analyzer.git
  cd golf_swing_analyzer

# **2. Install dependencies:**
  pip install -r requirements.txt

 #**3. Run the app:**
  streamlit run app.py
  Open your browser → upload your golf swing video!
