# Expense Tracker with Cloud Backup 💰☁️

A professional-grade Python application that allows users to track their daily expenses and securely back them up to the cloud using Firebase Realtime Database. This project demonstrates basic cloud integration, real-time updates, and data-driven insights.

## ✨ Features

- Add daily expenses with amount, category, and date
- Real-time cloud sync using Firebase
- Basic data structure for future analytics/insights
- Lightweight and easy to use

## 🔧 Technologies Used

- **Python**
- **Firebase Realtime Database**
- `firebase-admin` Python SDK

## 🛠️ Setup Instructions

1. Clone the repo:
   ```bash
   git clone https://github.com/your-username/expense-tracker-cloud-backup
   cd expense-tracker-cloud-backup
   ```

2. Install the required package:
   ```bash
   pip install firebase-admin
   ```

3. Setup Firebase:
   - Create a Firebase project at [https://console.firebase.google.com](https://console.firebase.google.com)
   - Add a Realtime Database
   - Generate a private key (`.json`) from Service Accounts and name it `firebase_config.json`
   - Place it in the same folder as the Python script

4. Run the script:
   ```bash
   python expense_tracker.py
   ```

## 📁 Sample Data Structure

```json
{
  "expenses": {
    "2025-03-10": {
      "category": "Groceries",
      "amount": 500
    }
  }
}
```

## 🚀 Future Enhancements

- Visualize monthly spending
- Add authentication
- Export data to CSV

## 📜 License

This project is licensed under the MIT License. Feel free to use, modify, and share!

