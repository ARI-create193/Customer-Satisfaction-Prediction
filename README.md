# 🎯 Customer Satisfaction Prediction System
A comprehensive machine learning project that analyzes customer support data and predicts satisfaction ratings. Built with Python and Gradio for an interactive web interface.

## 📖 Introduction
This project helps analyze customer support ticket data to understand:
- Customer satisfaction patterns and trends  
- Support ticket distributions (priority, channel, status)
- Customer demographics and behavior analysis
- Satisfaction prediction using Random Forest ML model
- Product performance and customer insights

Perfect for hackathons, data science competitions, and customer service optimization projects!

## 🚀 How to Run

### 1. Setup
```bash
# Clone the repository
git clone https://github.com/yourusername/customer-satisfaction-prediction.git
cd customer-satisfaction-prediction

# Install requirements
pip install gradio pandas numpy scikit-learn matplotlib seaborn
```

### 2. Run the Dashboard
```bash
# Run the Python script
python Customer_Satisfaction_Prediction.ipynb

# Or run in Jupyter Notebook/Google Colab
jupyter notebook
# Open Customer_Satisfaction_Prediction.ipynb and run all cells
```

### 3. Open your browser
The Gradio interface will automatically open in your browser with a shareable public URL

## 📊 Dashboard Features

### 📁 Data Upload & Analysis
- Upload your customer support CSV file or use sample data
- Data cleaning and preprocessing
- Dataset summary statistics
- Sample data table viewer

### 👥 Customer Distribution Analysis
- **Customer Gender Distribution**: Pie chart of customer demographics
- **Customer Age Distribution**: Histogram with statistical indicators
- **Age Groups Analysis**: Categorized analysis with satisfaction correlation
- Interactive charts with comprehensive insights

### 🎫 Tickets Related Distribution
- **Priority Level Analysis**: High/Medium/Low/Critical distribution
- **Channel Analysis**: Email, Chat, Phone, Social media, Web form usage
- **Status Distribution**: Open, Closed, In Progress, Escalated breakdown
- **Ticket Type Analysis**: Technical issues, billing inquiries, etc.
- **Trends Over Time**: Monthly patterns and temporal analysis

### 😊 Satisfaction Distribution
- **Overall Satisfaction**: 1-5 rating scale breakdown with labels
- **Satisfaction by Gender**: Gender-based satisfaction comparison
- **Satisfaction Analytics**: Detailed insights and statistics

### 🏆 Top Product Analysis (Enhanced)
- **Top 10 Products**: Most purchased products with volume analysis
- **Gender-Filtered Analysis**: Product preferences by customer demographics
- **Product Performance**: Average satisfaction ratings per product
- **Customer Segmentation**: Age and satisfaction analysis per product

### 🤖 ML: Satisfaction Prediction
- Train RandomForest model for satisfaction prediction
- Feature importance analysis
- Interactive prediction interface
- Predict satisfaction for new customers based on profile

### 🎯 ML: Customer Insights Engine
- Advanced customer segmentation
- Satisfaction pattern recognition
- Predictive analytics for customer behavior
- Actionable recommendations based on ML insights

## 📊 Dataset

**Sample Data**: Included in the code (1000+ customer records)

**Format**: CSV with columns:
- Customer Age, Customer Gender, Customer Name
- Product Purchased, Ticket Type, Ticket Subject  
- Ticket Status, Ticket Priority, Ticket Channel
- Customer Satisfaction Rating (1-5), Date of Purchase

**Source**: [Kaggle - Customer Support Ticket Dataset](https://www.kaggle.com/datasets/suraj520/customer-support-ticket-dataset)

## 🛠️ Technologies Used
- **Python** - Main programming language
- **Gradio** - Interactive web interface
- **Pandas** - Data processing and analysis
- **Matplotlib/Seaborn** - Data visualizations
- **Scikit-learn** - Machine learning models
- **NumPy** - Numerical computations
- **Random Forest** - Satisfaction prediction model

## 📁 Project Structure
```
customer-satisfaction-system/
├── Customer_Satisfaction_Prediction.ipynb  # Main dashboard script
├── requirements.txt                        # Python dependencies
├── README.md                              # This file
├── Dataset                           
└── Screenshots/                           # Dashboard screenshots
```

## 📧 Contact
*Aryan Kaminwar* - aryankaminwar@gmail.com

**GitHub**: [Customer-Satisfaction-Prediction](https://github.com/ARI-create193/Customer-Satisfaction-Prediction/tree/main)
