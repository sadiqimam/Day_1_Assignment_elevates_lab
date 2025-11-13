# Day_1_Assignment_elevates_lab

# Marketing Campaign Data Cleaning

## 📊 Project Overview
End-to-end data cleaning and preparation of a customer marketing dataset. Transformed raw data into analysis-ready format for customer behavior analysis and marketing optimization.

## 🚀 Quick Start

```bash
# Clone and run
git clone [repository-url]
cd marketing-campaign-cleaning
python scripts/data_cleaning.py
```

## 📈 Dataset
- **Original**: 2,240 customers × 29 features
- **Cleaned**: 2,240 customers × 33 features
- **Data Types**: Fixed from all 'object' to proper types

## 🔧 What Was Fixed

### Data Issues Resolved:
- ✅ Fixed tab-separated file parsing
- ✅ Converted all columns from text to proper data types
- ✅ Handled missing values in Income
- ✅ Added 4 new business metrics
- ✅ Zero missing values in final dataset

### New Features Created:
- `Total_Spending` - Combined product spending
- `Total_Children` - Family size indicator  
- `Total_Purchases` - Multi-channel purchase behavior
- `Customer_Tenure_Days` - Loyalty duration

## 📁 Files
```
marketing-campaign-cleaning/
├── data/
│   ├── marketing_campaign.csv          # Raw data
│   └── marketing_campaign_cleaned.csv  # Cleaned data
├── scripts/
│   └── data_cleaning.py               # Main script
└── README.md
```

## 🛠️ Usage
```python
import pandas as pd
df = pd.read_csv('data/marketing_campaign_cleaned.csv')
print(f"Ready for analysis: {df.shape}")
```

## 📊 Results
- **100% clean data** - No missing values
- **Optimized types** - Reduced memory usage
- **Enhanced features** - Added business metrics
- **Analysis-ready** - Perfect for segmentation and modeling

## 💡 Business Applications
- Customer segmentation
- Campaign effectiveness analysis  
- Purchase behavior patterns
- Customer lifetime value calculation

---

**Ready for analysis!** 🎯

