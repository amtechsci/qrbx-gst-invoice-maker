# QRBX: Free Rule 46 GST Tax Invoice & Bill Maker

> Instant Rule 46-compliant GST tax invoice generator, statutory HSN/SAC code lookup, and group expense splitting engine.

🌐 **Live Tool**: [https://qrbx.tech/gst-invoice-maker](https://qrbx.tech/gst-invoice-maker)  
🔍 **HSN/SAC Directory**: [https://qrbx.tech/hsn-sac-codes](https://qrbx.tech/hsn-sac-codes)  
📱 **Android App (Google Play)**: [QRBX on Google Play](https://play.google.com/store/apps/details?id=tech.qrbx.settle)  
🏠 **Official Website**: [https://qrbx.tech](https://qrbx.tech)

---

## 🚀 Key Features

- **Rule 46 Statutory Compliance**: Automatically formats invoices according to Indian GST Rule 46 standards, including supplier and recipient GSTINs, state codes, sequential invoice numbering, and HSN/SAC breakdowns.
- **3 Print-Ready A4 Layouts**:
  - **Modern Corporate**: Professional layout tailored for B2B contracts and IT service billing.
  - **Classic Boxed Grid**: Traditional boxed format familiar to chartered accountants and traders.
  - **Compact Service Slip**: Snug receipt format designed for freelancers and micro-enterprises.
- **Automated Tax Calculation**: Automatic split between **CGST + SGST** (for intra-state supply) and **IGST** (for inter-state supply) based on 2-digit GST state codes.
- **Numbers to Indian Words Converter**: Native conversion of final invoice amounts to official INR currency words (Lakhs and Crores).
- **Custom Branding**: Custom logo upload, signature block, bank account details, and instant vector PDF download or direct printing.
- **100% Free & Private**: Client-side execution with zero ads, zero tracking, and no signup required for public tools.

---

## 🛠️ Tech Stack & Architecture

- **Frontend**: React 19, TypeScript, Tailwind CSS
- **Vector PDF Rendering**: HTML5 Canvas & Vector Print CSS
- **Tax Calculation Engine**: Client-side pure mathematical reducer with floating-point precision guards
- **State Code Detection**: Official Indian GST State Code Directory (01 to 38)

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).
