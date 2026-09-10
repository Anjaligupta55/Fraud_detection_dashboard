# Fraud Detection System — Report Content

## 1. Title Page

- **Project Title:** Fraud Detection System
- **No. of Students:** 4
- **Date:** 10-09-2026
- **Submitted By:** Akshay Pratab Singh, Anjali Gupta, Anjali Gehra, Anchal Yadav
- **Submitted To:** Ms Karuna Kaushik

---

## 1) Objective

The main objective of the **Fraud Detection System** is to identify potentially fraudulent transactions and activities using predefined rules and/or machine learning techniques.

The system analyzes transaction-related information such as transaction amount, location, time, frequency, and user behavior to determine whether a transaction is genuine or suspicious.

### Objectives:
- To detect fraudulent transactions at an early stage.
- To reduce financial losses caused by fraud.
- To analyze transaction patterns and user behavior.
- To classify transactions as Fraudulent or Genuine.
- To provide alerts for suspicious transactions.
- To help fraud analysts investigate suspicious activities.

---

## 2) Questionnaire Design

A questionnaire can be used to understand user requirements.

### Sample Questionnaire

1. **Have you ever experienced or encountered an online transaction fraud?**
   - Yes
   - No

2. **What information should be checked during fraud detection?**
   - Transaction amount
   - Location
   - Time
   - Device
   - Transaction history

3. **How should the system notify users about suspicious transactions?**
   - Email
   - SMS
   - Dashboard alert
   - All of these

4. **What action should be taken for a high-risk transaction?**
   - Block transaction
   - Ask for verification
   - Send alert
   - Manual investigation

5. **How important is real-time fraud detection?**
   - Very Important
   - Important
   - Moderately Important
   - Not Important

---

## 3) User Persona Creation

We can create personas for the main users of the Fraud Detection System.

### Persona 1 — Customer
- **Name:** Rahul
- **Role:** Bank/Online Payment Customer
- **Goal:** Make secure online transactions.
- **Needs:**
  - Secure transactions
  - Fraud alerts
  - Transaction history
  - Quick notification of suspicious activity
- **Problem:** Wants to know immediately if someone performs an unauthorized transaction.

### Persona 2 — Fraud Analyst
- **Name:** Priya
- **Role:** Fraud Analyst
- **Goal:** Identify and investigate fraudulent transactions.
- **Needs:**
  - Suspicious transaction alerts
  - Risk score
  - Transaction details
  - User transaction history
  - Investigation dashboard
- **Problem:** Large numbers of transactions make manual fraud detection difficult.

### Persona 3 — Administrator
- **Name:** Amit
- **Role:** System Administrator
- **Goal:** Manage the fraud detection system.
- **Needs:**
  - Manage users
  - Monitor system activity
  - Configure fraud detection rules
  - View reports
  - Manage access permissions

---

## 4) Observation / Interview Simulation

For requirements gathering, we observe and interview the people who would use or manage the fraud detection system.

### Interview Questions

- **Q1. How do you currently identify fraudulent transactions?**  
  **Answer:** Fraud is identified using transaction history, predefined rules, customer complaints, and suspicious activity patterns.

- **Q2. What information is important for detecting fraud?**  
  **Answer:** Transaction amount, transaction time, location, device information, transaction frequency, and previous transaction history are important.

- **Q3. What should happen when a suspicious transaction is detected?**  
  **Answer:** The system should generate an alert and mark the transaction as suspicious for further investigation.

- **Q4. Should every suspicious transaction be blocked?**  
  **Answer:** No. High-risk transactions may be blocked, while medium-risk transactions can be flagged for manual verification.

- **Q5. Who should have access to the system?**  
  **Answer:** Customers should be able to view their transactions, while fraud analysts and administrators should have access to investigation and management features.

---

## 5) System — Query

### System Query
The proposed Fraud Detection System receives transaction information from the user/payment system and analyzes it using fraud detection rules or a machine learning model.

#### Basic Flow:
```
User → Transaction → Fraud Detection System → Data/ML Model → Risk Score → Decision → Alert/Approve/Block
```

The system can classify transactions into:
- **Low Risk** → Genuine / Approve
- **Medium Risk** → Flag for Verification
- **High Risk** → Fraud / Block and Alert

### Example:
A customer usually makes transactions of ₹500–₹2,000 from India. Suddenly, a transaction of ₹80,000 is made from another location/device.

The system identifies this unusual behavior and assigns a high fraud risk score. The transaction can then be flagged or blocked for verification.

---

## 6) Stakeholder Identification

The major stakeholders of the Fraud Detection System are:
- Customer/User
- Fraud Analyst
- Bank/Business Manager
- System Administrator

### Stakeholder Responsibilities

| Stakeholder | Requirement / Role |
| :--- | :--- |
| **Customer** | Make transactions and receive fraud alerts |
| **Fraud Analyst** | Investigate suspicious transactions |
| **Manager** | View fraud reports and overall statistics |
| **Administrator** | Manage users, rules, and system access |

---

## 7) Requirement Elicitation Techniques

The following techniques are used to collect requirements for the Fraud Detection System:

1. **Observation:** Observe how banks/payment platforms currently monitor transactions and identify suspicious activities.
2. **Interview:** Interview customers, fraud analysts, managers, and administrators to understand their needs and problems.
3. **Questionnaire:** Collect requirements from a large number of users through structured questions.
4. **User Persona Creation:** Create personas representing different types of users to understand their goals, expectations, and problems.

---

## 8) Consolidated Requirements

### Functional Requirements

- **FR1 — User Registration/Login:** The system should allow authorized users to securely log in.
- **FR2 — Transaction Monitoring:** The system should monitor and analyze transaction details.
- **FR3 — Fraud Detection:** The system should identify potentially fraudulent transactions.
- **FR4 — Risk Score:** The system should generate a risk score for each transaction.
- **FR5 — Transaction Classification:** The system should classify transactions as:
  - Genuine
  - Suspicious
  - Fraudulent
- **FR6 — Fraud Alert:** The system should notify users or fraud analysts when suspicious activity is detected.
- **FR7 — Transaction History:** The system should maintain transaction history for analysis.
- **FR8 — Fraud Investigation:** Fraud analysts should be able to view and investigate suspicious transactions.
- **FR9 — Reports:** The manager/administrator should be able to generate fraud detection reports.
- **FR10 — User Management:** The administrator should be able to add, remove, and manage users.

### Non-Functional Requirements

- **NFR1 — Security:** The system should protect sensitive transaction and user information.
- **NFR2 — Performance:** The system should analyze transactions within a reasonable response time.
- **NFR3 — Reliability:** The system should provide consistent and accurate results.
- **NFR4 — Scalability:** The system should be capable of handling a large number of transactions.
- **NFR5 — Availability:** The system should be available whenever transaction monitoring is required.
- **NFR6 — Usability:** The interface should be simple and easy to understand.
- **NFR7 — Maintainability:** The system should be easy to update and maintain.
- **NFR8 — Accuracy:** The fraud detection model should minimize both false positives and false negatives.

---

## 9) Requirement Traceability

| ID | Requirement | Stakeholder |
| :--- | :--- | :--- |
| **FR1** | User Login | Customer, Administrator |
| **FR2** | Transaction Monitoring | Fraud Analyst |
| **FR3** | Fraud Detection | Fraud Analyst, Manager |
| **FR4** | Risk Score Generation | Fraud Analyst |
| **FR5** | Transaction Classification | Fraud Analyst |
| **FR6** | Fraud Alerts | Customer, Fraud Analyst |
| **FR7** | Transaction History | Customer, Fraud Analyst |
| **FR8** | Fraud Investigation | Fraud Analyst |
| **FR9** | Fraud Reports | Manager |
| **FR10** | User Management | Administrator |

### Example Traceability

- **FR3 — Fraud Detection**
  - **Requirement:** The system should detect potentially fraudulent transactions.
  - **Stakeholder:** Fraud Analyst, Manager
  - **Source:** Interview + Questionnaire
  - **Priority:** High

---

## 10) Conclusion

The Fraud Detection System is designed to identify suspicious and fraudulent transactions efficiently. Through observation, interviews, questionnaires, and user persona creation, the major requirements of different stakeholders were identified.

The consolidated functional and non-functional requirements provide a clear understanding of the system. Requirement traceability ensures that every requirement is connected to the appropriate stakeholder and system functionality.

Overall, the system aims to improve transaction security, reduce financial fraud, provide timely alerts, and support fraud analysts in making better decisions.
