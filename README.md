# ☕ Airbean API

Ett REST-API för **Airbean** — en fiktiv kaffebar där användare kan beställa kaffe och få det levererat via drönare.  
Projektet byggdes som en gruppuppgift i kursen **Backendutveckling** (KYH FE24, VT 2025).

---

## 📌 **Funktionalitet**

- REST-API byggt med **Express.js**  
- **SQLite** databas med full CRUD  
- Middleware-validering för data i body/URL  
- Hantering av användarkonton med slumpgenererat ID  
- Orderhistorik per användar-ID  
- Möjlighet att bygga ut med kampanjfunktioner och WebSockets

---

## 🛠️ **Tekniker**

- Node.js / Express  
- SQLite  
- JavaScript (ES Modules)

---

## 🚀 **Kom igång lokalt**

1. **Klona repot**
   ```bash
   git clone https://github.com/ditt-användarnamn/airbean-api.git
   cd airbean-api

2. **Installera beroenden**
    ```bash
    npm install

3. **Starta servern**
    ```bash
    npm start

API:et körs nu vanligtvis på http://localhost:3000

## 🧪 **Testning**

Använd t.ex. Postman
 eller curl för att göra anrop till API:et.

Exempel:
curl http://localhost:3000/api/menu

## 👥 **Grupp & Bidrag**

Detta projekt utvecklades i grupp som en del av utbildningen.
Min roll: implementering av databasstruktur och order-endpoints

Originalrepo: [länk till originalrepo här]