# 🏠 AI-Powered Home Inventory Assistant

A smart **AI-powered inventory assistant** that helps you track household items, manage stock levels, and get alerts when items are running low. Built using **Airtable** as the backend database and **NA10NA10** as the automation platform, this system allows you to update your inventory simply by sending messages—no manual tracking required.

---

## 🌟 Project Overview

Managing household items can be tricky—how often do you forget how many soaps, rice, or cleaning supplies you have left?  
This project automates inventory management using AI and no-code tools.  
You can send a simple message like:
"I bought 2 soaps and 3 toothpastes"
…and the system will automatically update your stock in Airtable and notify you if items are running low.

This project combines:  
- **Airtable** → for storing structured data like item names, quantities, and thresholds.  
- **NA10NA10** → a no-code automation platform to build AI-powered workflows.  
- **AI Agent** → interprets natural language messages and updates inventory dynamically.  

---

## ⚙️ Tech Stack

| Component       | Description |
|-----------------|-------------|
| **Airtable**    | Stores inventory items, quantities, and thresholds. Provides API access for automation. |
| **NA10NA10**    | No-code automation platform for building workflows and connecting tools like WhatsApp, Google Sheets, OpenAI, and Airtable. |
| **AI Agent**    | Processes natural language messages and updates inventory dynamically. |

---

## 📌 Key Features

- **AI Chat Trigger**: Users can update inventory by sending natural language messages.  
- **Automated Inventory Updates**: Quantities in Airtable are updated automatically.  
- **Threshold Alerts**: Get notified when stock levels fall below defined thresholds.  
- **Contextual Memory**: Chat remembers previous messages for accurate updates.  
- **Integration with WhatsApp**: Send and receive inventory updates through WhatsApp messages.  
- **No-Code Automation**: Build complex workflows visually without programming.  

---

## 💡 How It Works

1. Send a message to the AI agent (e.g., “I bought 2 soaps”).  
2. The AI agent parses the message and identifies items and quantities.  
3. Searches the corresponding Airtable records.  
4. Updates the item quantities in Airtable.  
5. Checks if quantities fall below thresholds and optionally sends alerts.  
6. AI chat maintains memory, allowing context-aware interactions like continuing a previous sequence.  

---

## 🔮 Future Enhancements

- Multi-channel notifications: WhatsApp, Telegram, Slack  
- Automatic reordering via e-commerce APIs  
- Barcode scanning for faster item updates  
- AI analytics to predict consumption trends  
- Mobile app interface for on-the-go inventory management  

---


---

Built with ❤️ by [Baratam Gayatri].  
AI-powered home inventory made simple with no-code automation.



