# IT Human Resource — Custom HRIS & Payroll System

> **PRB IT Global Sdn Bhd** | Custom Software for SME Engineering & Construction Clients (Malaysia)

## Overview

A fully customised **Human Resource Information System (HRIS) and Payroll** platform built for the unique requirements of Malaysian engineering and construction SMEs. The system manages the full employee lifecycle — from onboarding to offboarding — while ensuring full compliance with Malaysian labour laws, EPF, SOCSO, EIS, and PCB/MTD tax regulations.

## Key Features

| Module | Description |
|---|---|
| Employee Management | Digital employee profiles, contracts, and documents |
| Payroll Processing | Automated payroll with EPF, SOCSO, EIS, and PCB calculations |
| Leave Management | Annual, medical, maternity, and emergency leave workflows |
| Claims & Expenses | Site allowance, travel, and overtime claims |
| Attendance Integration | Syncs with biometric and mobile attendance systems |
| Statutory Compliance | EA 1955, IRB, EPF Act, SOCSO Act compliance |
| Payslip Generation | Automated digital payslips (Arial font, computer-generated) |
| Reporting | HR analytics, headcount, and cost reports |

## Technology Stack

- **Frontend:** React.js, TypeScript, TailwindCSS
- **Backend:** Python (Django) / Node.js
- **Database:** PostgreSQL
- **Auth:** OAuth2 / RBAC
- **Integration:** EPF i-Akaun API, LHDN e-PCB, PERKESO
- **Hosting:** AWS / Azure (Malaysia region)

## Compliance

This system is designed in compliance with:
- **Employment Act 1955 (Malaysia)**
- **EPF Act 1991**
- **SOCSO Act 1969**
- **Income Tax Act 1967 (PCB/MTD)**
- **EIS (Employment Insurance System)**

## Getting Started

```bash
git clone https://github.com/PRB-IT-Global-Sdn-Bhd/hr-custom-hris-payroll.git
cd hr-custom-hris-payroll
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
```

## Licence

Proprietary — © 2024 PRB IT Global Sdn Bhd. All rights reserved.
