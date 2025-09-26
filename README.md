# 🔍🛒 E-Commerce Trustworthiness Chrome Extension

A **Chrome Extension** built with **React + TypeScript + Tailwind CSS + MongoDB** that evaluates the **trustworthiness of e-commerce websites** by combining **user-submitted reviews** and **government registration verification**. It also uses **OpenAI-powered sentiment analysis API** to generate real-time insights and safety indicators.

---

## 🚀 Key Highlights

✅ Government registration verification
✅ Bayesian Average Algorithm for accuracy
✅ User ratings with AI review summaries
✅ Real-time trust score & safety badge
✅ Clean two-slide UI for summary & review submission

---

## 📌 How It Works

The extension provides a **Trust Score** for any visited site by considering:

* **Government registration status**
* **User reviews & ratings**
* **Bayesian scoring algorithm**
* **AI-generated review summaries (OpenAI LLMA V3)**

---

## 🛠 Features

### 🔹 Section 1 – Site Overview

* Site **logo & URL** display
* **5-star rating bar** with color-coded trust levels:

  * 🔴 **0.0 – 2.6** → Low trust
  * 🟡 **2.7 – 3.7** → Medium trust
  * 🟢 **3.8 – 5.0** → High trust
* **Government registration badge**
* Optional **PhishTank API** phishing detection
* **Confidence bar** with dynamic gradient fill
---

### 🔹 Section 2 – Top Feedback Options

* Displays **Top 5 feedback choices** with reviewer counts
* Interactive **button-style layout** for clarity
---

### 🔹 Section 3 – Recent Reviews

* Shows **latest textual reviews**
* Option to **view all reviews**
* Minimalist UI with clean dividers
---

### 🔹 Section 4 – User Reviews

* **Three review categories**:

  1. **Product Quality** (e.g., Good Quality, Poor Quality)
  2. **Service Satisfaction** (e.g., Fast Delivery, Poor Support)
  3. **Platform Experience** (e.g., Easy to Use, Hard to Navigate)
* **Multi-checkbox rating system** (80% predefined, 20% AI-generated)
* **Text input field** supporting Bangla, English, and Banglish
* AI summarization into **keyword-based insights**

---

## 📊 Scoring & Storage

* **Scoring System:**

  * Feedback option scores + Gov. registration bonus
  * Bayesian Average Algorithm applied
 

* **Storage:**

  * Ratings saved in **MongoDB**
  * Retrieved instantly when site is revisited

---

## 🖥 Tech Stack

* **Frontend:** React, TypeScript, Tailwind CSS
* **Backend:** Node.js, Express
* **Database:** MongoDB
* **AI Processing:** OpenAI LLMA V3
* **Optional API:** PhishTank

---

## 📐 Workflow

- [MIRO](https://miro.com/app/board/uXjVJDszxXw=/?share_link_id=450949282203) 

---

## 🖼 UI Preview

### 🔸 First View – Overview (Sections 1, 2 & 3)

<img src="https://github.com/irrfanulhoque/ecommerce-extension/blob/main/Image/Passive%201st%20Scroll%20Panel.png" width="400">  

---

### 🔸 Registered Business Badge

<img src="" width="400">  

---

### 🔸 Most Selected Review
<img src="https://github.com/irrfanulhoque/ecommerce-extension/blob/main/Image/Most%20Selected%20Review.png" width="400">  

---


### 🔸 Recent Feedbacks

<img src="https://github.com/irrfanulhoque/ecommerce-extension/blob/main/Image/Recent%20Feedbacks.png" width="400">  

---

### 🔸 Review Dropdown Menu (Section 4)

<img src="https://github.com/irrfanulhoque/ecommerce-extension/blob/main/Image/Passive%202nd%20Scroll%20Panel.png" width="400">  

---

### 🔸 Extension Preview GIF

<img src="" width="400">  

---

## ⚙️ Installation

```bash
# 1. Clone repository
git clone https://github.com/irrfanulhoque/ecommerce-extension.git
cd ecommerce-trust-extension

# 2. Install dependencies
npm install

# 3. Build the extension
npm run build
```

Then:

* Open `chrome://extensions/`
* Enable **Developer Mode**
* Click **Load unpacked** → select the `build/` folder

---

## 🔮 Future Roadmap

* 🌐 Multi-language sentiment analysis
* 🚨 Phishing detection alerts
* 🔔 Real-time update notifications

---

## 🤝 Contributors  

- [Jaawad Tashick](https://github.com/JAWAD645)   
- [Istiak Islam](https://github.com/isttiiak) 

