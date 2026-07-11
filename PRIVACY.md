# Privacy & Data Handling — IFG Returns & Withdrawals

This page describes how the app itself collects, uses, and retains data. It documents the app's technical behavior — it is not a substitute for IFG eCommerce's company-wide privacy policy, and it is not legal advice.

## What is collected

When a customer submits a return through the storefront form: name, surname, shipping address, email, order number, and optionally phone number and notes. The app also reads order data from Shopify (order number, email, order date, fulfillment status) to verify the request is genuine.

Merchants additionally provide their own company legal details and return address during onboarding, used to generate compliant withdrawal notices and receipts.

## Why it's collected

- To verify a return request corresponds to a real order (fraud prevention).
- To process the return/refund and generate confirmation emails and PDF receipts.
- To meet EU consumer-rights obligations (Directive 2011/83/EU and its 2023/2673 amendment), which require identifying the customer and the contract.

## Who it's shared with

- **Shopify** — to verify orders and, on eligible plans, to issue refunds directly (Shopify Admin API).
- **Email delivery** (Nodemailer / Resend) — to send the customer's confirmation, receipt, and status-update emails.
- **Google Gemini** — powers the in-app Support chat used by merchants to ask questions about the app. It processes the merchant's support question text, not customer order data.

Data is not sold or used for advertising.

## Retention

If a merchant uninstalls the app, or requests erasure, customer personal data (name, email, phone, notes) is anonymized. Order-level accounting fields (order number, resolution, amounts) are kept, anonymized, since retaining them is a standard fiscal accounting requirement (up to 10 years) — the anonymized records can no longer be linked back to an individual.

## Security

- Shopify access uses expiring offline access tokens, refreshed automatically — no long-lived credentials.
- The database (Firestore) is only reachable through the app's own backend service identity; there is no public read/write access.

## Questions or requests

To exercise a data access or erasure request, contact the merchant whose store you placed the order with, or write to [info@ifgecommerce.com](mailto:info@ifgecommerce.com).
