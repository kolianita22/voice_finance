# VoiceFinance – AI Personal Finance Tracker

VoiceFinance is a smart web application that helps users track daily expenses using **voice commands** or manual input. The app automatically categorizes expenses, visualizes spending patterns, and predicts future spending using a simple machine learning model.

This project demonstrates the integration of **React, Web Speech API, NLP-style parsing, data visualization, and ML-based prediction** in a single application.

---

## Features

### 1. Voice Expense Entry

* Add expenses by speaking naturally.
* Example voice commands:

  * "Add 500 rupees for groceries"
  * "Spent 200 for lunch"
  * "Paid 1500 electricity bill"
* The system extracts:

  * Amount
  * Category
  * Description
  * Date

### 2. Automatic Expense Categorization

Expenses are automatically categorized into:

* Groceries
* Food & Dining
* Transport
* Shopping
* Utilities
* Health
* Entertainment
* Education
* Rent
* Other

### 3. Dashboard

The dashboard provides:

* Total spending for the current month
* Total spending for the current year
* Machine learning prediction for next month
* Category distribution chart
* Monthly spending trend

### 4. Expense Management

Users can:

* Add expenses manually
* View monthly expense history
* Delete entries
* Filter expenses by month

### 5. Data Visualization

The application includes:

* Pie chart for category spending distribution
* Bar chart for monthly spending trends
* Category breakdown with percentage insights

### 6. Machine Learning Prediction

The application predicts **next month's spending** using **Linear Regression** based on historical monthly data.

Insights include:

* Forecasted next month spending
* Average monthly spending
* Highest spending month
* Spending trend (increasing or decreasing)

### 7. Local Storage Persistence

All expense data is saved in **browser localStorage**, so user data persists even after refreshing the page.

---

## Tech Stack

Frontend:

* React (Hooks)
* JavaScript (ES6+)
* HTML5
* CSS3

APIs & Browser Features:

* Web Speech API (Voice Recognition)

Data & Visualization:

* SVG Charts
* Custom Pie Chart
* Custom Bar Chart

Machine Learning:

* Linear Regression algorithm implemented in JavaScript

Storage:

* Browser LocalStorage

---

## Project Structure

```
voice-finance-app
│
├── public
│   └── index.html
│
├── src
│   ├── App.js
│   ├── index.js
│   └── App.css
│
├── package.json
└── README.md
```

All application logic, voice processing, analytics, and charts are implemented in **App.js**.

---

## Installation & Setup

1. Clone the repository

```
git clone https://github.com/your-username/voice-finance.git
```

2. Navigate to the project directory

```
cd voice-finance
```

3. Install dependencies

```
npm install
```

4. Start the development server

```
npm start
```

5. Open the application in your browser

```
http://localhost:3000
```

---

## Example Voice Commands

You can try commands like:

```
Add 500 rupees for groceries
Spent 200 on lunch
Paid 1500 electricity bill
Bought medicine for 350
```

The application will automatically detect the amount and category.

---

## Screens in the Application

The application contains four main sections:

Dashboard
Overview of spending, charts, and ML prediction.

Voice Input
Add expenses using microphone speech recognition.

Expenses
View, filter, and delete expense entries.

Analytics
Detailed spending insights and machine learning predictions.

---

## Future Improvements

Possible improvements include:

* MongoDB cloud database integration
* User authentication
* Multi-language voice recognition (Hindi / English)
* Mobile responsive design
* Progressive Web App (PWA)
* AI-based expense categorization using NLP models

---

## Learning Outcomes

This project demonstrates:

* Building a modern React application
* Using voice recognition in web apps
* Implementing basic NLP text parsing
* Creating custom SVG data visualizations
* Applying simple machine learning in JavaScript
* Managing application state with React Hooks

---

## Author

Anita Pralhad Koli
Master of Computer Applications (MCA)
Kavayitri Bahinabai Chaudhari North Maharashtra University

---

## License

This project is for educational and portfolio purposes.

