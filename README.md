# ✈️ Travel Agency Inquiry Form Automation using n8n

## Overview

This project is an automated **Travel Agency Inquiry Form** built using **n8n**, **JavaScript**, **Google Sheets**, and **Email Integration**. It streamlines the travel inquiry process by collecting customer travel preferences, validating the submitted information, storing inquiries in Google Sheets, and automatically sending a personalized confirmation email to the customer.

The workflow reduces manual effort, improves data accuracy, and enables travel agencies to efficiently manage and respond to customer inquiries.

---

## Features

* 🌍 Online travel inquiry form
* ✅ Custom JavaScript validation for submitted data
* 📅 Collects complete travel preferences and trip details
* 📊 Automatically stores inquiries in Google Sheets
* 📧 Sends a personalized confirmation email to the customer
* ⚡ Fully automated workflow built with n8n
* 🔄 Eliminates manual data entry and improves workflow efficiency

---

## Workflow

```text
Customer
   │
   ▼
Travel Agency Inquiry Form
   │
   ▼
JavaScript Validation
   │
   ▼
Store Data in Google Sheets
   │
   ▼
Generate & Send Confirmation Email
   │
   ▼
Customer Receives Confirmation
```

---

## Tech Stack

* **n8n** – Workflow Automation
* **JavaScript** – Custom validation logic
* **Google Sheets API** – Store and manage inquiry records
* **Gmail / SMTP** – Send automated confirmation emails
* **REST APIs** – Communication between integrated services

---

## How It Works

1. A customer fills out the Travel Agency Inquiry Form with travel details such as destination, departure city, travel dates, trip duration, number of travelers, budget, hotel preference, flight booking, visa assistance, and special requests.
2. The submitted information is validated using custom JavaScript to ensure all required fields are complete and accurate.
3. Once validation is successful, the inquiry is automatically saved to Google Sheets for easy tracking and management.
4. A personalized confirmation email summarizing the customer's travel inquiry is generated and sent to the provided email address.
5. The travel agency can review the inquiry and contact the customer with customized travel packages and recommendations.

---

## Learning Outcomes

This project demonstrates:

* Workflow automation using n8n
* Custom JavaScript validation
* Google Sheets integration
* Automated email notifications
* REST API integration
* Business process automation
* End-to-end travel inquiry management

---

## License

This project is created for educational purposes and portfolio demonstration. Feel free to fork, modify, and extend the workflow to build your own automated travel inquiry management system.
