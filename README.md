

# Hotel Booking Data Analysis

## Overview
This project focuses on analyzing hotel booking data to uncover customer behavior, booking trends, reservation patterns, and hotel business insights using Python.

The analysis includes:
- Monthly booking trends
- Average Daily Rate (ADR) analysis
- Market segment analysis
- Customer type analysis
- Room reservation trends
- Repeated guest percentage

---

## Tools & Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Dataset
The dataset contains hotel booking information including:
- Reservation status
- Customer types
- Market segments
- Room types
- ADR (Average Daily Rate)
- Booking dates
- Guest information

Dataset File:
```txt
hotel_booking.csv
```

---

# Project Visualizations

## Monthly Booking Trends
![Monthly Booking Trends](images/Monthly%20Booking%20Trends)

---

## Average Daily Rate (ADR) Analysis
![ADR Analysis](images/ADR.png)

---

## Market Segment Distribution
![Market Segment Distribution](<src="https://github.com/user-attachments/assets/43d98d17-9e83-4349-8b24-6a4db0d3814d")

---

## Most Reserved Room Types
![Room Types](images/room_types.png)

---

## Customer Type Analysis
![Customer Type Analysis](images/Customer%20Type%20Analysis.png)

---

## Key Insights
- Certain months show significantly higher hotel bookings, indicating seasonal demand.
- Online travel agencies contributed a major portion of bookings.
- Repeated guests represented a smaller percentage compared to new customers.
- Some room types were consistently preferred over others.
- ADR varied across customer categories and booking periods.

---

## Folder Structure

```txt
Hotel-Booking-Analysis/
│
├── README.md
├── requirements.txt
├── .gitignore
│
├── data/
│   └── hotel_booking.csv
│
├── notebook/
│   └── Hotel_booking.ipynb
│
└── images/
    ├── monthly_booking_trends.png
    ├── adr_analysis.png
    ├── market_segment.png
    ├── room_types.png
    └── customer_types.png
```

---

## How to Run

1. Clone the repository

```bash
git clone <your-repo-link>
```

2. Install required libraries

```bash
pip install -r requirements.txt
```

3. Open Jupyter Notebook

```bash
jupyter notebook
```

4. Run all cells in:
```txt
Hotel_booking.ipynb
```

---

## Requirements

```txt
pandas
numpy
matplotlib
seaborn
jupyter
```

---

## Conclusion
This project demonstrates practical data analysis and visualization skills using real-world hotel booking data. It highlights the use of exploratory data analysis (EDA) techniques to extract meaningful business insights and trends.
