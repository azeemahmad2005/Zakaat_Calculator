# Zakat Calculator ✨

A calm, trustworthy, warm, and fully private Zakat calculator designed for ordinary Muslims worldwide. It runs entirely within the web browser with zero server storage, ensuring complete financial privacy.

Inspired by an original Excel sheet concept by **Haji Naseer Ahmad**.

## 🌟 Key Features

* **Five-Step Guided Wizard:** Seamlessly walks users through *Details → Assets → Debts → Review → Your Zakat*.
* **Live Metal & Currency Rates:** Automatically fetches real-time spot prices for gold/silver and international exchange rates with reliable offline fallbacks.
* **Strictly Private & Secure:** All calculations happen 100% locally in the browser using `localStorage`. Your financial data is never sent to any server.
* **Multi-Language Support:** Fully localized for English, Urdu (`اردو`), Arabic (`العربية`), and Hindi (`हिन्दी`), complete with automatic right-to-left (RTL) layout mirroring.
* **Smart Number Parsing:** Gracefully accepts inputs in various formats (European decimals, Indian grouping like `1,50,000`, Arabic-Indic numerals, etc.).
* **Responsive & Accessible:** Fully optimized for mobile phones, tablets, and desktops (with safe-area support for notched devices), high contrast, and keyboard navigation.
* **Printable & Shareable Reports:** Easily print results, copy text summaries, or use the device native share sheet.

## 🛠️ Technical Architecture

* **Zero Build Steps:** Built using pure semantic HTML5, modern CSS3 (Variables, Grid, Flexbox, custom typography, light/dark themes), and vanilla ES6+ JavaScript. No npm install, Webpack, React, or heavy frameworks required.
* **Resilient Networking:** Features robust parallel promise handlers with fallback rates to ensure the calculator always loads instantly even if spot price APIs are temporarily unreachable.

## 🐛 Reporting Issues & Feedback

If you encounter any bugs, unexpected calculation behaviors, layout issues, or have suggestions for improvement, please open an issue in the repository's [Issues section](https://github.com/your-username/your-repo-name/issues). 

When reporting a defect, kindly include:
1. A brief description of the issue.
2. Steps to reproduce it.
3. Your browser type and device information (mobile/desktop).

## 📄 License & Disclaimer

* **License:** Distributed under the MIT License. Feel free to fork, adapt, and improve for your community.
* **Disclaimer:** This tool provides an estimate to assist with your personal Zakat planning and is not an official religious ruling (*fatwa*). Zakat obligations can vary based on individual circumstances and madhabs; for complex financial scenarios, please consult a qualified Islamic scholar.