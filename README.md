# DHG Pharma — SWOT Analysis 2025

A web presentation for the DHG Pharma strategic SWOT analysis, built with **Streamlit**.  
Deployable directly on [Streamlit Cloud](https://streamlit.io/cloud).

## Run locally

```bash
# 1. Enter the project folder
cd dhg_pharma

# 2. (Recommended) Create a virtual environment
python -m venv venv
source venv/bin/activate        # macOS / Linux
venv\Scripts\activate           # Windows

# 3. Install dependencies
pip install -r requirements.txt

# 4. Run
streamlit run app.py
```

Then open **http://localhost:8501** in your browser.

## Deploy to Streamlit Cloud

1. Push this folder to a GitHub repository
2. Go to https://share.streamlit.io → New app
3. Select your repo, branch, and set **Main file path** to `app.py`
4. Click **Deploy** — no extra config needed

## Project structure

```
dhg_pharma/
├── app.py              ← Streamlit entry point (HTML embedded)
├── requirements.txt    ← streamlit==1.45.1
├── README.md
└── templates/
    └── index.html      ← Full presentation (also used standalone)
```

## Features

- 7 navigable sections: Overview, SWOT Matrix, Strengths, Weaknesses, Opportunities, Threats, Recommendations
- 8 interactive Chart.js charts (market forecast, revenue, margins, channel mix, ratios, radar)
- DHG Pharma brand colors: green #0D7A4E · red #C41E3A
- Fully responsive — works on desktop and mobile

## Team

- Dang Nguyen Vinh Tuong — 10625077
- Le Hien Tri — 10325024
- Nguyen Truong Thinh — 1065090
- Nguyen Minh Tuan — 10625055

Instructor: Nguyen Thanh Duoc · Academic Year 2025
