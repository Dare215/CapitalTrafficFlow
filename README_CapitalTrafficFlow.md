# CapitalTrafficFlow: White House Visitor Access Analysis

**Author:** Darious Brown  
**GitHub:** [Dare215](https://github.com/Dare215)  
**Email:** dariousbrown3@icloud.com  

## 1) Project Overview
CapitalTrafficFlow analyzes visitor access records for the White House from January 2022 to May 2022.  
The objective is to identify periods of high visitor retention, peak hours, and common locations visited in order to optimize security personnel deployment and enhance safety protocols.

## 2) Dataset
- **Source:** WAVES (White House Access Records) dataset  
- **Files:**  
  - `2022.01_WAVES-ACCESS-RECORDS.numbers`  
  - `2022.02_WAVES-ACCESS-RECORDS.csv`  
  - `2022.03_WAVES-ACCESS-RECORDS-.numbers`  
  - `2022.04_WAVES-ACCESS-RECORDS.csv`  
  - `2022.05-WAVES-ACCESS-RECORDS.numbers`  
- **Key Variables:** `Date`, `Visitor Type`, `Location`, `Entry Time`

## 3) Key Features
- **Visitor Type Analysis:** Breakdown of VA (Visitor Appointment) vs. PA (Prescheduled Appointment) categories.
- **Daily Trends:** Identification of days with exceptional visitor volume.
- **Monthly Trends:** Highlight months with highest traffic (April & May).
- **Time-of-Day Analysis:** Discover peak access times (5 AM–3 PM).
- **Security Insights:** Provide actionable recommendations for security staff allocation.

## 4) Project Structure
```
CapitalTrafficFlow/
│── 2022 WAVES ACCESS RECORDS.ipynb   # Main analysis notebook
│── CapitaltrafficFlow.docx           # Written summary & visuals
│── Access Data Files/                # Monthly visitor logs
│── README.md                         # Project documentation
```

## 5) How to Run

### Option A — Python / Terminal
```bash
# Create and activate a virtual environment
python -m venv .venv
source .venv/bin/activate   # Mac/Linux
.venv\Scripts\activate      # Windows

# Install dependencies
pip install -r requirements.txt

# Launch Jupyter
jupyter notebook "2022 WAVES ACCESS RECORDS.ipynb"
```

### Option B — PyCharm
1. Open the folder in PyCharm  
2. Configure a Python interpreter (point to `.venv`)  
3. Install dependencies from `requirements.txt`  
4. Run the notebook

### Option C — GitHub Desktop
1. Add the local repository to GitHub Desktop  
2. Commit all files (including `README.md` and `requirements.txt`)  
3. Push to a public GitHub repository  

## 6) Results Summary
- **Visitor Type:** Most visitors were VA or PA, indicating predictable scheduling patterns.
- **Peak Months:** April and May saw the highest volume of visitors.
- **Peak Hours:** 5 AM–3 PM was the busiest period daily.
- **East Wing Tours:** Associated with over 12,000 daily visitors.
- **Recommendation:** Increase security staffing during April–May, especially 5 AM–3 PM.

## 7) Ethical Considerations
- Respect privacy by anonymizing personal visitor details.
- Limit use of data to operational improvement and public safety.
- Ensure recommendations are applied fairly without discriminatory profiling.

## 8) Future Enhancements
- Extend analysis to full year for seasonal trend validation.
- Incorporate event calendars to correlate spikes with scheduled activities.
- Build predictive models for visitor forecasting.

## 9) License
MIT License — Free to use with attribution.
