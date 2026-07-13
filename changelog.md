# Changelog — IFG Returns & Withdrawals

🇬🇧 **English** · [🇮🇹 Italiano](it/changelog.html) · [🇩🇪 Deutsch](de/changelog.html) · [🇫🇷 Français](fr/changelog.html) · [🇪🇸 Español](es/changelog.html)

A running record of what's new and improved. The app is updated frequently as we refine the returns and EU withdrawal-rights workflow.

## 0.3.207 – 0.3.220 — July 2026
- **Added** — The in-app Support chat now runs on a real conversational AI (Claude, with a Gemini fallback), remembers the conversation instead of answering message-by-message, and replies in whichever language you write in.
- **Added** — When you ask to speak with a person, the conversation stays open and the merchant's reply now appears directly in the same chat — no more "we'll email you back."
- **Improved** — The Support page was redesigned around 20 clearly explained FAQs (up from 10), fully translated into all 30 languages; the chat itself now lives only in the floating widget, available from every page.
- **Added** — New setting for who covers the cost of return shipping (customer or merchant), automatically disclosed to the customer on the return form and in the confirmation email.
- **Added** — A legal reminder now tracks the EU refund deadline from the customer's original request date, not from when the merchant approves it.
- **Fixed** — A multi-package order no longer gets its return window blocked just because one package is still in transit; the window now starts once every package has arrived.
- **Fixed** — Return requests on older orders (return windows longer than 60 days) are now verified correctly instead of showing "order not found."
- **Changed** — New installs of the app now start in English by default, including throughout the guided onboarding; the interface and email language can still be changed to any of the 30 supported languages at any time.

## 0.3.206 — July 2026
- **Improved** — Analytics overview redesigned into a clearer 6-card summary: return count, approval rate, average processing time, refunds issued, average item value, and full/partial split.

## 0.3.205 — July 2026
- **Fixed** — Resolved a page that failed to load correctly inside the Shopify Admin's embedded session refresh.
- **Fixed** — Buttons for already-completed actions now visibly turn inactive instead of staying in an actionable color.
- **Improved** — Tightened the legal reference text describing the EU withdrawal right across the app and storefront form.
- **Fixed** — A single-category chart on the Analytics page no longer renders as one oversized bar; layout and product-category tags now wrap correctly on small screens.

## 0.3.203 – 0.3.204 — July 2026
- **Improved** — The storefront return form is now available to shoppers everywhere, with the same 30-language and legal-text logic applied consistently.
- **Fixed** — Refined the in-form legal disclaimer to precisely cite the EU withdrawal-rights directive and its 2026 amendment.

## 0.3.198 – 0.3.202 — June–July 2026
- **Added** — Redesigned case review flow: Approve request → Confirm goods received → select items and amount → Refund, with a confirmation step before any refund is issued.
- **Added** — Distinct status colors for every stage (pending, approved, partially approved, refunded, partially refunded, rejected) shown consistently across the dashboard, case list, and case detail view.
- **Improved** — Analytics rebuilt with clearer summary cards and status/reason breakdowns.
- **Improved** — The support assistant now replies in the same language the merchant writes in.

## Earlier releases
Introduced the core of the app: guided onboarding with legal-entity and return-address setup, the three storefront return blocks (embedded, pop-up and floating), direct in-app refunds on eligible plans, PDF receipts and CSV export, Product Restrictions, and full localization into 30 languages — including right-to-left layout for Arabic and Hebrew.

---
IFG Returns & Withdrawals — built by IFG eCommerce. Questions about a specific release? [info@ifgecommerce.com](mailto:info@ifgecommerce.com)
