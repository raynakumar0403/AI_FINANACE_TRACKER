# 💰 AI Finance Tracker

An intelligent finance tracking application built using **Python**, **Streamlit**, and the **Groq API**. The application allows users to upload CSV and Excel files containing financial data, automatically analyzes spending patterns, categorizes transactions, generates insights, and provides AI-powered financial recommendations.

---

## 🚀 Features

### 📂 Data Upload
- Upload CSV files
- Upload Excel (.xlsx) files
- Automatic data validation and cleaning

### 📊 Financial Analysis
- Income and expense tracking
- Monthly spending summaries
- Category-wise expense breakdown
- Budget monitoring
- Cash flow analysis

### 🤖 AI-Powered Insights
- Smart transaction categorization
- Personalized spending insights
- Financial health assessment
- Savings recommendations
- Expense trend analysis
- Natural language financial queries

### 📈 Interactive Dashboard
- Dynamic charts and graphs
- Expense distribution visualization
- Monthly trend reports
- Financial performance metrics

---

## 🛠️ Tech Stack

- **Python**
- **Streamlit**
- **Pandas**
- **OpenPyXL**
- **Groq API**
- **Plotly**
- **NumPy**

---

## 📂 Project Structure

```
AI-Finance-Tracker/
│
├── app.py
├── finance_analyzer.py
├── requirements.txt
├── .env
├── assets/
├── sample_data/
└── README.md
```

---

## ⚙️ Installation

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/AI-Finance-Tracker.git
cd AI-Finance-Tracker
```

### 2. Create a Virtual Environment

```bash
python -m venv venv
```

Activate it:

**Windows**

```bash
venv\Scripts\activate
```

**Mac/Linux**

```bash
source venv/bin/activate
```

### 3. Install Required Libraries

```bash
pip install -r requirements.txt
```

---

## 🔑 Groq API Configuration

Create a `.env` file in the root directory:

```env
GROQ_API_KEY=your_groq_api_key_here
```

Get your API key from:

https://console.groq.com

---

## ▶️ Running the Application

Start the Streamlit application:

```bash
streamlit run app.py
```

The application will launch in your browser automatically.

---

## 📊 Supported File Formats

| Format | Supported |
|----------|----------|
| CSV | ✅ |
| XLSX | ✅ |
| XLS | ✅ |

---

## 📋 Requirements

```txt
streamlit
pandas
numpy
plotly
openpyxl
groq
python-dotenv
```

---

## 💡 Example Workflow

1. Upload a CSV or Excel financial statement.
2. The system processes and cleans the data.
3. Transactions are categorized automatically.
4. AI analyzes spending behavior.
5. Dashboard displays visual insights.
6. Users receive personalized financial recommendations.

---

## 🔮 Future Enhancements

- Multi-user authentication
- Budget planning assistant
- PDF bank statement support
- Investment portfolio tracking
- Financial forecasting
- Exportable reports
- Mobile application integration

---

## 🎯 Use Cases

- Personal finance management
- Student budget tracking
- Expense monitoring
- Savings optimization
- Financial data visualization
- AI-powered financial advisory

---

## 🤝 Contributing

Contributions are welcome.

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push to your branch
5. Open a Pull Request

---

## 📜 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

Developed using Python, Streamlit, and Groq AI to simplify personal finance management through intelligent data analysis and actionable insights.

⭐ Star this repository if you found it useful!
