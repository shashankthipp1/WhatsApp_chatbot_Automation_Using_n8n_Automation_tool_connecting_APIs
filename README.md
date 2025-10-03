# WhatsApp_chatbot_Automation_Using_n8n_Automation_tool_connecting_APIs
This project is a WhatsApp chatbot for food delivery built with n8n, Google Gemini AI, and Google Sheets. It lets customers browse menus, place orders, and get updates via WhatsApp. Though designed for food delivery, it can be adapted for e-commerce, healthcare, support, and other business needs.
# WhatsApp Chatbot for Food Delivery (Powered by n8n + AI)

This project is an **automation workflow** built using [n8n](https://n8n.io), integrated with **WhatsApp** and **Google Sheets**, and powered by **Google Gemini AI**.  
It acts as a **WhatsApp chatbot** for **food delivery orders**, but the same architecture can be extended to **any business use case** (e-commerce, appointment booking, customer support, etc.).



![Alt text](path/to/image.png)

---

## 🚀 Features
- 📱 **WhatsApp Chatbot** → Customers can place food delivery orders directly on WhatsApp.  
- 🤖 **AI Agent** → Handles conversation flow using **Google Gemini AI** with memory support.  
- 📊 **Google Sheets Integration** → Stores and retrieves inventory, appends new orders, and keeps track of customer interactions.  
- ⏰ **Automated Triggers** → Supports both:
  - **Schedule Trigger** → Runs on defined intervals.  
  - **WhatsApp Trigger** → Responds instantly when a new message arrives.  
- ⚡ **Scalable for Any Business** → Easily customizable for:
  - Restaurant orders  
  - Grocery delivery  
  - Appointment booking  
  - Customer support FAQs  
  - Lead generation  

---

## 🛠️ Tech Stack
- **n8n** (workflow automation engine)  
- **WhatsApp API** (for customer interaction)  
- **Google Gemini Chat Model** (AI conversation agent)  
- **Google Sheets** (inventory + order tracking)  

---

## 🔄 Workflow Overview
1. **Trigger**: Workflow starts with either a **Schedule Trigger** or a **WhatsApp Trigger**.  
2. **AI Agent**: The message is processed by the AI agent (Google Gemini + memory).  
3. **Inventory Management**: Reads available items from Google Sheets.  
4. **Order Logging**: Appends confirmed orders back into Google Sheets.  
5. **Customer Reply**: Sends acknowledgment/updates via WhatsApp.  

---

## 📦 Example Use Cases
- 🍔 **Food Delivery** → Customers order meals from a restaurant.  
- 🏥 **Clinic Appointments** → Patients book slots via WhatsApp.  
- 🛒 **E-commerce Shop** → Customers ask about stock, place orders, and track delivery.  
- 💼 **Business Support Bot** → Handles FAQs and lead capture automatically.  

---

## ⚙️ Setup & Hosting
1. Clone or set up this workflow in your **n8n instance**.  
2. Configure:
   - **WhatsApp API credentials**  
   - **Google Sheets API credentials**  
   - **Google Gemini AI key**  
3. Activate the workflow in n8n.  
4. Host n8n on:
   - [n8n Cloud](https://n8n.io/cloud) (easiest)  
   - Self-hosted (Docker, VPS, Render, Railway, etc.)  

---

## 📌 Future Improvements
- Add **payment gateway integration** (Razorpay, Stripe, PayPal).  
- Multi-language support for different customers.  
- Dashboard for live order tracking.  
- CRM integration for better customer management.  

---

## 🤝 Contribution
Feel free to fork this repo and adapt it for your own business requirements. PRs are welcome!

---

## 📧 Contact
For questions or business integration support, reach out at: **your-email@example.com**
