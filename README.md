# Intelligent Invoice Data Extraction Agent

An automated pipeline designed to extract structured data from unstructured PDF invoices using AI-powered OCR agents and export the results directly into structured formats like Excel (`.xlsx`).

## 🚀 Workflow Overview

The system processes incoming billing documents through an AI agent to accurately map out and extract key-value pairs and tabular line items.

1. **Input:** Raw unstructured PDF documents (e.g., `demo-onv1.pdf`).
2. **Processing:** The AI Agent extracts header information, buyer/vendor details, and individual line items.
3. **Output:** Structured Excel file (`data_export.xlsx`) containing fields and line items mapped to unique database columns.

---

## 📸 Results & System Screenshots

### 1. AI Agent Data Extraction
The AI Agent successfully extracts header data, totals, and individual tabular line items (Product Name, Quantity, Unit Price, Total Price) directly from the invoice PDF.

<img src="path/to/your/Screenshot_(22).png" alt="AI Extraction Interface" width="800"/>

### 2. Exported Excel Data Schema
Once processing is complete, data is exported into a clean, key-value tabular schema separating invoice metadata, totals, and buyer information.

<img src="path/to/your/Screenshot_(23).png" alt="Excel Export Results" width="800"/>

---

## 📊 Extracted Data Sample

| Schema Field | Extracted Value |
| :--- | :--- |
| **Invoice Number** | USF-INV-10234 |
| **Issue Date** | October 5, 2023 |
| **Total Amount** | $1,084.10 |
| **Buyer Name** | Cloud Kitchens |
| **Line Items Extracted** | 5 Items (Poultry, Spinach, Bread, Olive Oil, Cheese) |

## 🛠️ Tech Stack & Tools
* **AI/OCR Processing:** Nanonets Intelligent Document Processing (IDP)
* **Data Formatting:** Excel / CSV Engine
* **Document Format:** PDF
