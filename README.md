# 📥 Lead Capture & Automated Response System

An automated lead processing system built with **n8n**, **Google Sheets API**, and **Gmail API**. It captures incoming sales leads from webforms in real time, records entry metadata into a Google Sheets database, and sends tailored confirmation emails to potential clients.

---

## 📽️ System Live Demo
📺 **[Click Here to Watch the 1-Minute Live Demo Video](https://www.loom.com/share/d26054758f2d400fb74527aa4cf525b3)**

---

## 📸 System Screenshots & Visual Proof

| n8n Workflow Canvas | Google Sheets Database | Gmail Confirmation Email |
| :---: | :---: | :---: |
| ![Workflow](./workflow-screenshot.png) | ![Database](./sheets-screenshot.png) | ![Email](./email-screenshot.png) |

---

## 🔑 Key Features
* **Real-Time Webform Trigger**: Captures submissions instantaneously without manual intervention.
* **Structured Data Logging**: Appends incoming lead data directly to a Google Sheets document.
* **Automated Email Outreach**: Delivers personalized confirmation emails via Gmail OAuth 2.0 integration.

---

## 🛠️ Tech Stack
* **Workflow Engine**: n8n
* **Database / CRM**: Google Sheets API
* **Email Engine**: Gmail API (OAuth 2.0)

---

## 🚀 How to Import and Run

1. Download the JSON workflow file: [`lead system form.json`](./lead%20system%20form.json).
2. Open your n8n canvas and click **Import from File**.
3. Upload `lead system form.json`.
4. Configure your **Google Sheets** and **Gmail** OAuth2 credentials.
5. Activate the workflow and test the webform URL!
