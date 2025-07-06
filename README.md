# 🎮 GameIntel AI – Sentiment and Visual Intelligence for Game Analytics

GameIntel AI is a two-part intelligent system for gaming analytics that analyzes player feedback and classifies gameplay screenshots.

## 📋 Project Components
✅ Sentiment analysis from Steam reviews (NLP)  
✅ Scene classification using ResNet50 + Grad-CAM (simulated data)  
✅ Streamlit dashboard (optional)

## 📂 Directory Structure
```
GameIntel-AI/
├── data/                  # Place datasets here (not included)
├── notebooks/             # Jupyter notebooks
├── models/                # Trained models (.h5, .pkl)
├── streamlit_app/         # Streamlit app files
├── scripts/               # Utility scripts
├── README.md              # This file
├── requirements.txt       # Python dependencies
└── .gitignore             # Ignored files
```

## 🚀 How to Run
1️⃣ Run `notebooks/GameIntel_AI_Final_Annotated.ipynb` to demonstrate both parts.  
2️⃣ Replace simulated CV data with real screenshots when available.  
3️⃣ (Optional) Run Streamlit dashboard:  
```bash
cd streamlit_app
streamlit run gameintel_dashboard.py
```

## 📄 License
MIT License (or specify).