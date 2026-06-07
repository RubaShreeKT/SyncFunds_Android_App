# SyncFunds – Digital Money Lending & Borrowing Management

## 📌 Overview

SyncFunds is an Android-based Peer-to-Peer (P2P) lending and borrowing management application designed to digitize and formalize informal financial transactions between friends, family members, classmates, and colleagues.

Informal lending is a common part of everyday life, yet it is often managed through chat messages, handwritten notes, spreadsheets, or memory. This frequently results in forgotten loan amounts, missed repayment deadlines, unclear interest calculations, and disputes between parties.

SyncFunds addresses these challenges by providing a secure and structured digital platform that manages the complete lending lifecycle—from loan requests and digital agreements to payment tracking, interest management, and final settlement.

---

## 🎯 Problem Statement

Traditional informal lending systems suffer from:

- Lack of proper transaction records
- Missed repayment deadlines
- Unclear interest calculations
- Absence of legally documented agreements
- Poor transparency between lenders and borrowers
- Difficulty tracking multiple loans simultaneously

SyncFunds solves these issues through automation, accountability, and real-time tracking.

---

## 🚀 Key Features

### 🔐 Secure Authentication
- OTP-based phone number login using Firebase Authentication
- Secure user onboarding process

### 👤 User Onboarding
- Personal profile setup
- Aadhaar verification
- Basic financial literacy assessment

### 💰 Lending & Borrowing Management
- Users can act as both lenders and borrowers
- Manage multiple loans simultaneously
- Dedicated creditor and debtor dashboards

### 🤝 Loan Request System
- Structured mechanism for connecting lenders and borrowers
- Loan request and approval workflow

### 📄 Digital Loan Agreements
- Automated agreement generation
- PDF contract export
- Improved accountability and transparency

### 📊 Financial Dashboard
- Total amount lent
- Total amount borrowed
- Net financial balance
- Loan status monitoring

### 📈 Interest Tracking
- Automated interest calculation
- Due amount tracking
- Interest payment records

### 🔔 Automated Notifications
- Real-time payment reminders
- Interest due notifications
- Settlement updates using Firebase Cloud Messaging (FCM)

### 💵 Payment Management
- Record loan repayments
- Lender-side verification
- Transaction history maintenance

### ✅ Settlement Workflow
- Formal loan closure process
- Settlement confirmation for both parties

### 📝 Audit Trail
- Complete history of lending and borrowing activities
- Transparent transaction records

---

## 🏗️ System Architecture

The application follows a modern Android-Firebase architecture:

### Frontend
- Java
- XML Layouts
- Material Design Components

### Backend
- Firebase Realtime Database
- Firebase Storage

### Authentication
- Firebase Phone Authentication (OTP Login)

### Notifications
- Firebase Cloud Messaging (FCM)

### Platform Support
- Minimum SDK: 23
- Target SDK: 34

---

## 🛠️ Technology Stack

| Component | Technology |
|------------|------------|
| Programming Language | Java |
| UI Design | XML Layouts, Material Design |
| Authentication | Firebase Phone Auth |
| Database | Firebase Realtime Database |
| Storage | Firebase Storage |
| Notifications | Firebase Cloud Messaging (FCM) |
| Document Generation | PDF Export |
| Platform | Android |

---

## 🔄 Workflow

1. User Registration & OTP Verification
2. Profile Setup & Verification
3. Loan Request Creation
4. Loan Approval
5. Digital Agreement Generation
6. Loan Disbursement
7. Interest Tracking
8. Payment Recording
9. Automated Reminders
10. Loan Settlement
11. Audit Trail Maintenance

---

## ✨ Highlights

- End-to-end digital lending lifecycle management
- Secure OTP-based authentication
- Digital loan agreements with PDF generation
- Automated interest scheduling
- Real-time push notifications
- Dual-role support (Lender & Borrower)
- Complete transaction transparency
- Formal settlement workflow
- Scalable Firebase-powered architecture

---

## 🔮 Future Enhancements

Planned improvements include:

- UPI Payment Integration
- Aadhaar e-Sign via DigiLocker
- Credit Score Calculation
- SMS Reminder Gateway
- WhatsApp Reminder Integration
- Multi-language Support
- Advanced Financial Analytics
- Loan Risk Assessment

---

## 📚 Project Summary

SyncFunds successfully digitizes the entire informal lending process by providing secure authentication, digital agreements, automated interest tracking, payment management, settlement workflows, and real-time notifications. The platform aims to improve trust, transparency, and accountability in personal lending and borrowing transactions while offering a scalable foundation for future financial services.
