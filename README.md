# 💱 CURRENCY-CONVERTER

🔗 **Live Preview**  
https://main--currencyconverterapi.netlify.app/

---

## ✨ Features

- Converts currency values in real time using a reliable exchange rate API  
- Dropdown selection for both source and target currencies  
- One-click button to swap currencies instantly  
- Clear result display with current conversion rate  
- Input validation for better user experience  
- Designed to be mobile-friendly and responsive

---

## 🛠 Technologies Used

- **HTML** – For the page structure  
- **CSS** – For styling and layout  
- **JavaScript** – For logic and API handling  
- **ExchangeRate-API** – For fetching real-time currency exchange rates

---

## 🚀 How to Run Locally

1. Clone or download the repository  
2. Make sure these files exist in your folder:  
   `index.html`, `style.css`, `script.js`, `currencyCodes.js`, `logo.jpg`  
3. Open `index.html` in any modern web browser  
4. Enter amount, select currencies, and click **Convert**

---

## 🔐 API Key Setup

- Visit: https://www.exchangerate-api.com  
- Get your free API key after signing up  
- Open `currencyCodes.js`  
- Replace the existing API key with your own:

  ```js
  export const api = "your-api-key";
