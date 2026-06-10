# DHG Pharma — SWOT Analysis Presentation

A web presentation for the DHG Pharma strategic SWOT analysis, built with Flask and Chart.js.

## Prerequisites

- Python 3.8 or higher

## Setup & Run

```bash
# 1. Clone or download the project folder
cd dhg_pharma

# 2. (Recommended) Create a virtual environment
python -m venv venv
source venv/bin/activate        # macOS / Linux
venv\Scripts\activate           # Windows

# 3. Install dependencies
pip install -r requirements.txt

# 4. Run the app
python app.py
```

Then open your browser at: **http://localhost:5000**

## Project Structure

```
dhg_pharma/
├── app.py                  # Flask application entry point
├── requirements.txt        # Python dependencies
├── README.md
└── templates/
    └── index.html          # Main presentation page (all-in-one)
```

## Features

- 7 navigable sections: Overview, SWOT Matrix, Strengths, Weaknesses, Opportunities, Threats, Recommendations
- Interactive charts powered by Chart.js (market size forecast, revenue, gross margin, revenue breakdown)
- DHG Pharma brand colors (green #0D7A4E, red #C41E3A)
- Fully responsive design
- No database required — all data is embedded in the template

## Team

- Dang Nguyen Vinh Tuong — 10625077  
- Le Hien Tri — 10325024  
- Nguyen Truong Thinh — 1065090  
- Nguyen Minh Tuan — 10625055  

Instructor: Nguyen Thanh Duoc · Academic Year 2025
