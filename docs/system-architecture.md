# System Architecture

## Loan Application Automation Flow

The loan application system follows a structured workflow from application submission to automated loan number generation and email notification.

```text
Executive
   │
   ▼
Loan Application Form
   │
   ├── Executive Email
   ├── Loan Agreement Number
   ├── Loan Type
   ├── Branch
   ├── Borrower ID
   ├── Customer Name
   ├── Mobile
   ├── Vehicle Number
   ├── Loan Amount
   ├── Loan Tenure
   ├── Business Executive
   └── Loan Approval Name
   │
   ▼
Form Validation
   │
   ▼
System Status Check
   │
   ├── OPEN → Continue
   │
   └── CLOSED → Stop Submission
   │
   ▼
Loan Number Generation
   │
   ▼
Loan Sequence Management
   │
   ▼
First EMI Date Calculation
   │
   ▼
Maturity Date Calculation
   │
   ▼
Loan Record Saved
   │
   ▼
Automated Email Notification
   │
   ▼
Executive Receives Loan Number
