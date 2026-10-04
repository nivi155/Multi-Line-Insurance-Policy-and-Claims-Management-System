# Multi-Line-Insurance-Policy-and-Claims-Management-System

📌 Project Overview

The Multi-Line Insurance Policy and Claims Management System is a Salesforce-based application designed to manage insurance policies and claims efficiently in a centralized platform.

The system supports multiple insurance lines such as Auto, Property, and Life Insurance. It automates policy creation, premium calculation, claim processing, approval workflows, and claim monitoring using Salesforce features such as Custom Objects, Record Types, Fields, Validation Rules, Flows, Apex, Lightning Web Components, and Security Controls.

---

🎯 Objectives

- Manage multiple types of insurance policies.
- Maintain customer and policy information efficiently.
- Automate policy quotation and premium calculation.
- Manage insurance claims from submission to approval.
- Implement automated claim processing.
- Provide a dashboard for claim monitoring.
- Improve data security using Salesforce security features.
- Reduce manual work through automation.

---

🛠️ Technologies Used

- Salesforce
- Salesforce Object Manager
- Apex
- Lightning Web Components (LWC)
- Screen Flows
- Record-Triggered Flows
- Validation Rules
- Custom Objects
- Record Types
- Field Sets
- Approval Processes
- Salesforce Security & Access Control

---

📂 Main Modules

1. Policy Management

The Policy module manages insurance policy information for different insurance types.

Supported policy types:

- Auto Insurance
- Property Insurance
- Life Insurance

Features include:

- Policy creation
- Policy-specific fields
- Record Types
- Field Sets
- Policy validation
- Customer information management

---

2. Auto Quoting

The Auto Quoting module provides a guided process for creating an Auto Insurance policy quote.

The Screen Flow collects required policy information and performs the required processing before creating the policy record.

---

3. Premium Calculation

The system uses Apex to calculate the insurance premium based on the required policy information.

Apex Class:

"PremiumCalculator"

---

4. Claims Management

The Claims module manages insurance claims associated with policies.

Features include:

- Claim creation
- Claim record types
- Claim status management
- Claim amount management
- Claim approval status
- Automated claim processing

---

5. Claim Approval

The system provides an approval workflow for processing insurance claims.

Approval Status values include:

- New
- Submitted for Approval
- Approved
- Rejected

---

6. Automated Claim Processing

A Record-Triggered Flow is used to automate claim-related processes when claim records are created or updated.

This reduces manual processing and improves workflow efficiency.

---

7. Claims Dashboard

The project includes Lightning Web Components for displaying claim information in a user-friendly dashboard.

Main components include:

- "claimsDashboardLwc"
- "claimTileLwc"

These components help users view and monitor claim details efficiently.

---

⚙️ Salesforce Components

Component| Purpose
Policy__c| Stores insurance policy information
Claim__c| Stores insurance claim information
Record Types| Separates Auto, Property, and Life policies
Field Sets| Groups policy-specific fields
Validation Rules| Ensures valid policy data
Screen Flow| Creates Auto Insurance quotes
Record-Triggered Flow| Automates claim processing
PremiumCalculator| Calculates policy premium
ClaimsAdjusterController| Handles claim-related Apex logic
claimsDashboardLwc| Displays claim dashboard
claimTileLwc| Displays individual claim information

---

🔐 Security

The application uses Salesforce security features to control access to insurance data.

Security configuration includes:

- Profiles
- Permission Sets
- Object-Level Security
- Field-Level Security
- Record-Level Access
- Role-Based Access

---

🔄 Project Workflow

Customer
   ↓
Create Insurance Policy
   ↓
Select Policy Type
   ↓
Auto / Property / Life
   ↓
Enter Policy Information
   ↓
Validate Policy Data
   ↓
Calculate Premium
   ↓
Create Policy
   ↓
Submit Claim
   ↓
Claim Processing
   ↓
Claim Approval
   ↓
Approved / Rejected
   ↓
Claims Dashboard

---

📊 Key Features

- ✅ Multi-line insurance policy management
- ✅ Auto, Property, and Life policy support
- ✅ Automated Auto Insurance quotation
- ✅ Premium calculation using Apex
- ✅ Claim management
- ✅ Claim approval workflow
- ✅ Automated claim processing
- ✅ Lightning Web Component dashboard
- ✅ Validation and data quality controls
- ✅ Salesforce security implementation

---

👥 Team

This project was developed as a team-based Salesforce project.

Team Members

- Nivetha
- Porpavai
- Mathubala
- Manimekalai
- Hari Prasath

---

🚀 Project Outcome

The project demonstrates how Salesforce can be used to build an end-to-end insurance management solution with automation, custom development, workflow processing, and secure access to business data.

It provides a centralized platform for managing policies and claims while reducing manual processing and improving operational efficiency.

---

📌 Project Type

Salesforce CRM Project

Domain: Insurance

Application: Multi-Line Insurance Policy and Claims Management System
