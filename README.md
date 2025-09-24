 API Automation – Exchange Rate Data Collection  

## 🚀 Overview  
This project automates the process of collecting real-time exchange rate data using an **API**, and storing the results in **Google Sheets** for easy access.  
We used **Make (formerly Integromat)** to set up the workflow and connect APIs with Google Sheets.  

The automation fetches the latest **USD exchange rate** and converts it into:  
- 🇮🇳 INR (Indian Rupee)  
- 🇪🇺 EUR (Euro)  

---

## ⚙️ Tech Stack  
- **Make (Integromat)** → For workflow automation  
- **Exchange Rate API** → To fetch live currency conversion rates  
- **Google Sheets** → For storing and tracking results  

---

## 📊 Workflow  
1. API call fetches latest exchange rates for USD.  
2. The rates are converted into **INR** and **EUR**.  
3. Data is automatically appended to **Google Sheets**.  
4. The process runs at scheduled intervals.  

---

## 📂 Repo Contents  
- `workflow/` → JSON export of the Make workflow  
- `screenshots/` → Visuals of the Google Sheet & workflow  
 

---

## 🖼️ Screenshots  

### 🔹 Make Workflow  
<img width="6000" height="3375" alt="workflow" src="https://github.com/user-attachments/assets/83e2a3ed-5a4f-49f6-909f-db0b5c6e9616" />


### 🔹 Google Sheets Output  
<img width="6000" height="3375" alt="API connected google sheet" src="https://github.com/user-attachments/assets/978a9bf6-ed99-418f-8324-f4d1ead9c838" />

---

## 📌 How to Reproduce  

1. **Get an Exchange Rate API Key**  
   - Sign up at [ExchangeRate API](https://exchangerate.host/) or any free exchange rate API provider.  

2. **Set up Google Sheet**  
   - Create a sheet with columns: `Date`, `USD → INR`, `USD → EUR`.  

3. **Build Workflow in Make**  
   - Add an HTTP request module → connect to exchange rate API.  
   - Parse JSON response.  
   - Append data to Google Sheets.  

4. **Export Workflow**  
   - Save/export the workflow JSON for future use.  

---

## 🎯 Key Learnings  
- Hands-on with **API integration**.  
- Automating **data pipelines** without manual effort.  
- Using **Google Sheets** as a lightweight database.  

---


