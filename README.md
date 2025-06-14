
# 💱 Currency Converter App

A simple and intuitive Currency Converter built using Python. This project allows users to convert one currency into another using live exchange rates (via Fixer API) or fallback static rates. Supports both CLI and GUI modes.

---

## 📌 Project Details

- **Project Type**: Desktop Utility
- **Tech Stack**: Python, Tkinter (for GUI), Fixer API (for real-time rates)

---

## 🎯 Features

| Feature               | CLI | GUI |
|----------------------|-----|-----|
| Convert currency     | ✅  | ✅  |
| Show converted value | ✅  | ✅  |
| Full-form dropdowns  | ✅  | ✅  |
| Live API support     | ✅  | ✅  |
| Static fallback rates| ✅  | ✅  |

---

## 🚀 How to Run (GUI)

### ✅ Prerequisites:
- Python 3.x
- Install required modules:
```bash
pip install requests python-dotenv
```

### 🔧 Fixer API Setup:
1. Create a `.env` file in the project root.
2. Add the line:
```bash
FIXER_API_KEY=your_api_key_here
```

### ▶️ Run GUI:
```bash
python currency_converter.py
```

---

## 🚀 How to Run (CLI)

Run directly via terminal:
```bash
python currency_converter.py
```

You’ll be prompted:
```text
Please specify the amount of currency to convert, from currency, to currency (with space in between).
Press SHOW to see list of currencies available.
Press Q to quit.
```

### Example:
```
Input: 100 USD INR
Output: 100 of currency USD amounts to 8250.0 of currency INR today
```

---

## 📦 File Structure

```bash
currency_converter/
├── currency_converter.py
├── .env
└── README.md
```

---

## 🧠 Concepts Practiced
- File I/O
- REST API (Fixer)
- Tkinter GUI
- Data parsing
- Dropdown with full-form currencies

---

## ✨ Add-On Suggestions
- Add currency flags next to dropdown items in GUI
- Support for currency history (last 7 days)
- Add currency chart using matplotlib
- Option to auto-refresh rates every 5 minutes (GUI)

---

## 📃 License
This project is open-source and free to use for learning or demo purposes.

---

## Made with ❤️ by Shakyasimha Das.
