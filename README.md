# ICU Risk Alert & Patient Record App

## 📌 Overview

This application is designed to help hospital staff efficiently **record and monitor patient data** from both **casualty and ICU wards**. Each patient has an individual profile that displays basic information, test results, and other medical attachments. If a patient is flagged as being in a **critical condition**, the app triggers an **automated alert email** to the designated doctor to ensure timely medical intervention.


## 🏥 Who is it for?

- Hospital ward and ICU staff
- Casualty emergency responders
- On-call doctors needing prompt notifications
- Healthcare administrators overseeing patient care


## ⚙️ Features

- Patient profile creation and editing
- Uploading attachments (e.g., test results, scans)
- Real-time risk status monitoring
- Email alert automation for critical patients
- Data submission and storage in a secure backend

## 🧰 Technologies Used

- **Microsoft Power Apps** – for building the UI and business logic
- **Power Automate** – to send automated email alerts
- **Power BI** - for patient data analysis
- **SQL Server / SharePoint / Dataverse** – backend for storing patient records
- **Outlook 365 Connector** – for sending emails to doctors

## 🚀 How to Set It Up

1. **Import the Power Apps canvas app** from source.
2. Connect the app to your data source (SQL, SharePoint, or Dataverse).
3. Set up permissions for users (ICU staff, doctors).
4. Import the Power Automate flow for email alerts and connect it to your app.
5. Test submission of a patient record and verify email delivery.
6. Customize doctor contact lists or risk criteria if needed.

## App Screen Details
- Home screen
- Patient profile screen
- Risk analysis and Email confirmation or success screen
