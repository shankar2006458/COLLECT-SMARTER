# UPI QR Code Generator

A simple, responsive web application for generating **scan-ready UPI payment QR codes** directly in the browser.

It supports automatic payment splitting for amounts above **₹1,999**, payment tracking, QR downloads, and printable payment summaries.

## ✨ Features

- Generate UPI QR codes instantly
- Supports all major UPI apps
- Automatically splits amounts above **₹1,999**
- Add UPI ID, account holder name, amount, and payment note
- Quick amount presets
- Payment Summary dashboard
- Track collected payments with **Mark as Paid**
- Live collection progress bar
- Download individual QR codes as PNG
- Print all QR codes in a clean A4 layout
- Responsive and mobile-friendly design
- Accessible keyboard navigation and focus states
- No sign-up required
- No database required
- Data stays in the current browser session

## 🛠️ Technologies Used

- HTML5
- CSS3
- JavaScript
- Tailwind CSS
- QRCode.js
- Lucide Icons
- Google Fonts

## 🚀 How to Use

1. Open the application.
2. Enter your **UPI ID**.
3. Enter the **Account Holder Name**.
4. Enter the **Total Amount** you want to collect.
5. Optionally add a payment note.
6. Click **Generate QR Codes**.
7. Share or download the generated QR code(s).
8. Mark each payment as **Paid** when the money is received.
9. Use **Print All** to print the complete collection sheet.

### Automatic Amount Splitting

A single QR code is limited to **₹1,999** in this application.

For example:

```text
₹5,000
↓
₹1,999 + ₹1,999 + ₹1,002
```

Each amount gets its own QR code.

## 📱 Payment Summary

The Payment Summary provides:

- Total amount to collect
- Number of QR codes
- Account holder information
- UPI ID
- Individual payment QR codes
- Collection progress
- Completed payment count
- Payment checklist

## 🖨️ Print & Download

Each QR code can be downloaded as a PNG containing:

- Payment amount
- QR code
- Account holder name
- UPI ID
- Payment note
- Collection step

The **Print All** option creates a printer-friendly A4 layout containing all generated QR codes.

## 🔒 Privacy

The application does not require an account or database.

Payment details are processed directly in the browser and are not intentionally sent to a custom backend.

> Always verify the UPI ID, account holder name, and payment amount before sharing a QR code.

## ⚠️ Important

This project generates **UPI payment links and QR codes**. It does not verify whether a payment has actually been received.

The **Mark as Paid** feature is only a manual tracking tool. Always confirm successful payments through your bank or UPI application.


---

**UPI QR Code Generator**  
*Collect Smarter.*
