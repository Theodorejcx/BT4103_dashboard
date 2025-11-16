# Data-Driven Analytics and Gen AI to Improve Adult Learner-Course Matching at NUS Business Executive Education

## Business Analytics Capstone Project (BT4103) Group 8 

## Streamlit Dashboard
A full-featured analytics dashboard that helps NUS Executive Education programme advisors and marketing officers explore participant trends, programme performance, demographics, and revenue insights.

### Prerequisites
Before running this project, ensure you have:

- Python 3.10+
- pip installed
- (Optional) A curated CSV dataset
- If not available, the dashboard can generate one automatically from raw Programme & Cost files

## Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/Theodorejcx/BT4103_dashboard
cd BT4103_dashboard
```

### 2. Install Dependencies
```bash
pip install -r requirements.txt
```

### 3. Run the Streamlit App
```bash
streamlit run streamlit_app.py
```

The dashboard will open in your browser at:
http://localhost:8501

### 4. Uploading Data 

You must load data before the dashboard becomes interactive.

Option A — You already have a curated CSV
➡️ Upload it directly under “Curated CSV Upload”
Load time: ~10 seconds

Option B — You have raw Programme & Cost files
Upload both raw files
Click Run Curation (takes ~3 minutes)
Download the generated dashboard_curated.csv
Re-upload it under Curated CSV

⚠ No data is saved to GitHub or the server — all files stay local in the user's browser session.

### 5. Project Structure
.
├── app.py                        # Main Streamlit dashboard
├── CSVCuration.py                # Raw→curated data processing logic
├── requirements.txt              # Python dependencies
├── sample_dashboard_curated.csv  # A sample curated csv of 5 rows 
└── README.md                     # This file
