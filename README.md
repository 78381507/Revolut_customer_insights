# Revolut Customer Insights Analysis

Customer sentiment analysis of 14,749 Revolut app reviews to identify satisfaction drivers, complaint patterns, and actionable improvement areas.

[Dashboard Preview](Dashboard_Revolut_V8.pdf)

## Project Overview

**Objective:** Analyze customer feedback to identify pain points and satisfaction drivers for strategic decision-making.

**Dataset:** 21,967 reviews (IBM Coursera certification project) → cleaned to 14,749 records (33% reduction)

**Key Metrics:**
- Overall Score: 3.85/5
- Positive Sentiment: 70.4%
- Emotional Score: 0.43/1
- Geographic Coverage: USA dominant (88%)

## Key Findings

### Satisfaction Drivers
- **Top Features:** "Love" (1.5k), "Fast" (1k), "Best" (859)
- **Trust Indicators:** "Secure" (471), "Trust" (434), "Excellent" (214)
- **5-star reviews:** 9.3k (63% of total) - strong product-market fit

### Critical Issues
- **Main Complaints:** Support (308), Fraud (258), Scam (210), Fees (185)
- **Technical Problems:** Locked accounts (180), Withdrawal issues (141), Bugs (124)
- **1-star reviews:** 3.3k (22%) - concentrated around support failures

### Temporal Patterns
- **October spike:** Negative sentiment peak
- **December recovery:** Positive sentiment increase
- **Trend:** Overall improvement in customer satisfaction

### Geographic Insights
- **USA dominance:** 88% of reviews (13,101 records)
- **Limited international data:** Insufficient for regional analysis

## Strategic Recommendations

1. **Immediate Priority:** Redesign customer support workflow
   - 308 support complaints = primary dissatisfaction driver
   - Fraud/scam concerns (468 combined) require enhanced security communication

2. **Product Optimization:** Leverage satisfaction drivers
   - Amplify "fast" and "simple" messaging in marketing
   - Maintain security and trust positioning

3. **Risk Mitigation:** Address technical reliability
   - Account locking issues (180 complaints)
   - Withdrawal friction (141 complaints)

## Technical Implementation

**Data Cleaning (Google Sheets):**
- Removed 7,218 invalid/duplicate records (33%)
- Standardized country codes
- Normalized star ratings
- Extracted complaint keywords
- Classified sentiment categories

**Analysis & Visualization (Looker Studio):**
- KPI cards with aggregated metrics
- Temporal trend analysis
- Geographic distribution mapping
- Complaint frequency analysis
- Feature sentiment extraction

## Files Structure

```
revolut-customer-insights/
│
├── README.md
├── data/
│   ├── reviews_raw.csv              # Original dataset (21,967 records)
│   └── reviews_cleaned.csv          # Cleaned dataset (14,749 records)
│
├── dashboard/
│   └── Dashboard_Revolut_V8.pdf     # Final dashboard export
│
└── assets/
    └── dashboard_preview.png         # Dashboard screenshot
```

## Methodology

1. **Data Acquisition:** IBM Coursera certification project dataset
2. **Data Cleaning:** 
   - Removed duplicates and null values
   - Standardized formatting
   - Validated geographic data
3. **Sentiment Analysis:** 
   - Manual keyword extraction
   - Positive/negative/neutral classification
   - Complaint pattern identification
4. **Visualization:** 
   - Looker Studio dashboard development
   - KPI design and metric selection

## Skills Demonstrated

- Data cleaning and validation
- Sentiment analysis
- Business intelligence dashboard design
- Customer insight generation
- Strategic recommendation development

## Tools & Technologies

- **Data Processing:** Google Sheets
- **Visualization:** Looker Studio
- **Data Source:** IBM Coursera Data Analyst certification

## Contact

**François Tilkin**  
Data Analyst | Data Engineering

- LinkedIn: [Your LinkedIn]
- GitHub: [Your GitHub]
- Email: [Your Email]

---

## Insights Summary

**Strengths:** High overall satisfaction (70.4% positive), strong 5-star dominance (63%), positive feature associations

**Weaknesses:** Customer support gaps, fraud/scam perception issues, account access problems

**Action Required:** Support system overhaul, enhanced fraud communication, technical reliability improvements

---

*Part of IBM Data Analyst Professional Certificate portfolio*
