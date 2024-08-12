
---

# **MarketView Dashboard**

**MarketView Dashboard** is a full-stack web app offering real-time financial data, market trends, and insights. It features a responsive React and Chakra UI frontend, and a Flask backend integrating financial APIs for dynamic data visualization.

## **Features**

- **Real-time financial data**
- **Responsive UI** with React and Chakra UI
- **Secure Flask backend** with JWT authentication
- **Dynamic data visualization** using Chart.js

## **Technologies**

- **Frontend:** React, Chakra UI, Chart.js
- **Backend:** Flask, Python, SQLite
- **CI/CD:** GitHub Actions

## **Installation**

### **1. Clone the repository:**

```bash
git clone https://github.com/yourusername/marketview-dashboard.git
cd marketview-dashboard
```

### **2. Install dependencies:**

- **Frontend:**

  ```bash
  cd frontend
  npm install
  npm run start
  ```

- **Backend:**

  ```bash
  cd backend
  python -m venv venv
  . venv/bin/activate
  pip install -r requirements.txt
  flask run
  ```

## **Usage**

- **Frontend:** [http://localhost:5173/](http://localhost:5173/)
- **Backend:** [http://127.0.0.1:5000/](http://127.0.0.1:5000/)
- **Update API server URL** in `src/config/constant.js` if needed.

## **API Endpoints**

- `GET /api/stocks`: Real-time stock data
- `POST /api/user/login`: User authentication
- `GET /api/user/profile`: User profile data

## **Contributing**

Contributions are welcome! Submit issues or pull requests.

## **License**

Licensed under the MIT License.

---

