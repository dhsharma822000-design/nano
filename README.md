# 📄 Invoice Data Extraction using Nanonets OCR

## 📌 Overview

This project demonstrates how Nanonets OCR can automatically extract structured information from invoices and convert unstructured document data into machine-readable fields.

The workflow processes supplier invoices and extracts key business information such as invoice details, buyer information, purchase order references, GST details, and financial amounts.

This automation helps organizations reduce manual data entry, improve accuracy, and accelerate invoice processing.

---

## 🎯 Objective

The primary objective of this project is to:

- Automate invoice data extraction using AI-powered OCR.
- Reduce manual effort in invoice processing.
- Improve accuracy and efficiency of financial operations.
- Convert unstructured invoice documents into structured data.
- Enable seamless integration with ERP and accounting systems.
- Demonstrate Intelligent Document Processing (IDP) using Nanonets.

---

## 🏢 Business Problem

Organizations receive a large number of invoices from vendors and suppliers.

Manual processing often results in:

- Time-consuming data entry
- Human errors
- Delayed approvals
- Increased operational costs
- Compliance risks

Using Nanonets OCR, invoice data can be automatically extracted and converted into structured fields for further processing.

---

## 🛠️ Technology Used

- Nanonets OCR
- Optical Character Recognition (OCR)
- Artificial Intelligence (AI)
- Intelligent Document Processing (IDP)
- JSON Data Extraction
- GitHub

---

## 🔄 Workflow

### Step 1: Upload Invoice
The invoice document is uploaded to Nanonets.

### Step 2: OCR Processing
The OCR engine scans and reads text from the invoice.

### Step 3: Field Detection
The AI model identifies important invoice fields.

### Step 4: Data Extraction
Relevant information is extracted and converted into structured format.

### Step 5: Validation
Extracted values are verified for completeness and accuracy.

### Step 6: Output Generation
Structured output is generated in JSON format for downstream systems.

---

## 📊 Extracted Fields

### Invoice Information
- Invoice Number
- Invoice Date

### Buyer Information
- Buyer Name
- Buyer Address
- Buyer GSTIN

### Purchase Order Information
- PO Number
- PO Date

### Financial Information
- Item Description
- Quantity
- Unit Price
- Amount
- Subtotal
- GST Amount
- Total Invoice Amount

---

## 📋 Sample Output

```json
{
  "invoice_number": "INV-2026-001",
  "invoice_date": "09 June 2026",
  "buyer_name": "XYZ Enterprises Ltd.",
  "buyer_address": "456 Corporate Avenue, Gurugram, Haryana, India",
  "buyer_gstin": "06XYZAB5678K1Z2",
  "po_number": "PO-2026-145",
  "po_date": "05 June 2026",
  "subtotal": 100000,
  "gst_amount": 18000,
  "total_invoice_amount": 118000
}
```

---

## 💼 Business Applications

### Finance & Accounting
- Accounts Payable Automation
- Invoice Digitization
- GST Compliance

### Procurement
- Purchase Order Matching
- Vendor Invoice Verification

### ERP Integration
- SAP Integration
- Oracle ERP Integration
- Microsoft Dynamics Integration
- Tally Integration

### Audit & Compliance
- Digital Record Keeping
- Automated Reporting

---

## 🚀 Benefits

- Faster Invoice Processing
- Reduced Manual Data Entry
- Improved Data Accuracy
- Lower Operational Costs
- Better Compliance Management
- Scalable Document Processing

---

## 📂 Repository Structure

```
Invoice-Data-Extraction-Nanonets/
│
├── Sample_Invoice/
│   └── invoice.pdf
│
├── Screenshots/
│   └── extraction_result.png
│
├── Output/
│   └── extracted_data.json
│
└── README.md
```

---

## 🔮 Future Enhancements

- Multi-page invoice processing
- Invoice-to-PO matching
- Duplicate invoice detection
- Vendor validation
- ERP integration
- Power BI dashboard reporting

---

## 👨‍💼 Author

Dhruv Sharma

MBA (Finance)

Learning AI Automation, Nanonets OCR, n8n, Dialogflow, Data Analytics, and Business Process Automation.

---

⭐ If you found this project useful, feel free to star the repository.
