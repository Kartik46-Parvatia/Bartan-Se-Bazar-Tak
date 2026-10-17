# 🍃 Bartan Se Bazar Tak (बर्तन से बाज़ार तक) ♻️

> **An Ethical, Transparent, and Circular Lifecycle Platform for Pre-Owned Products.**  
> Helping everyday consumers decide whether an old item should be **Repaired**, **Sold**, **Donated**, or **Recycled**.

---

## 📌 Problem Statement

In today's consumption-driven economy, millions of household items—from cracked smartphones and wobbly wooden chairs to used textbooks and toys—end up either neglected in storage or dumped into open landfills. 

**The core issue:** Everyday users simply do not know what to do with an old product:
* *Is it worth repairing, or will parts cost more than buying new?*
* *Can I sell it for a fair price without getting scammed?*
* *Is there a trustworthy local NGO that will actually pick it up for free?*
* *How do I recycle dead electronics safely without polluting groundwater?*

**Bartan Se Bazar Tak** bridges this knowledge gap with a clean, calm, mobile-first web guide built strictly on transparent local data, real trust certifications, and zero dark patterns.

---

## 🎨 Color Psychology & Visual Architecture

Our design system is anchored around four psychologically purposeful colors:

| Color | Element & Theme | Meaning & Purpose in Project |
| :--- | :--- | :--- |
| 🟢 **Green** | **Sustainability & Growth** | Represents eco-friendly choices, circular economy, primary action buttons, and certified **Recycling** drop-offs. |
| 🔵 **Blue** | **Trust & Reliability** | Anchors the **Sell** pathway—representing verified buyer consortiums, recent 30-day market sales data, and direct payout security. |
| 🟠 **Orange** | **Value & Attention** | Highlights the **Repair** pathway—focusing on personal savings (40%–70% vs. buying new), local technician hubs, and warranty coverage. |
| 🟣 **Purple** | **Smart Recommendations** | Powers the **Decision Guide Banner**—providing quick heuristic rules and condition-based recommendations. |

---

## 🛡️ The 6 Ethical UX Principles (Anti-Dark Pattern Standard)

Unlike commercial resale apps that trap users with deceptive dark patterns, **Bartan Se Bazar Tak** is built strictly around 6 transparent commitments:

1. ⏳ **No Fake Countdowns**: We never display artificial scarcity or ticking clocks like *"Offer expires in 04:12 mins"*. Users can research and decide in their own time.
2. 🎯 **No Misleading Claims**: We provide realistic market brackets (e.g. ₹800–₹1,500) rather than inflated *"Get up to ₹50,000"* marketing gimmicks.
3. 🗺️ **Clear Next Steps**: Every pathway outlines an unambiguous **Step 1 → Step 2 → Step 3** progression so users always know what happens next.
4. 🧾 **No Hidden Charges**: The comparison guide is 100% free. Quoted repair costs include GST upfront, and NGO doorstep pickups are ₹0.
5. 🛡️ **Real Trust Indicators**: All listed partners are verified with legitimate government credentials:
   * State Pollution Control Board (CPCB / GPCB) EPR Authorizations
   * Govt. MSME Refurbisher Registrations (UDYAM)
   * Registered Charitable Trusts with 80G Tax Certificates
6. 🔓 **No Forced Sign-Up**: Complete open access. Users can compare options, search directories, and evaluate products without entering a phone number, email, or OTP.

---

## ✨ Key Features

### 1. Two Product Evaluation Pathways
* 📷 **Option 1: Scan & Fetch via Barcode / Model Sticker**  
  Features an interactive scanner viewfinder and manual serial-code input to automatically identify model specs, age, and estimated market value.
* ✍️ **Option 2: Manually Enter Every Detail**  
  A clean, 4-step guided form covering category selection, item brand/model, current physical condition, and original purchase price to calculate the optimal route.

### 2. The 5 Market Categories
Every product in the household is classified into 5 core taxonomies:
1. 📱 **Electronics**: Phones, laptops, appliances, mixers (Screen/battery repairs, certified CPCB e-waste shredding).
2. 🛋️ **Furniture & Home (Wooden Items)**: Chairs, tables, beds, desks (Carpentry polishing, joint tightening, rural school donation).
3. 📚 **Books & Education**: Textbooks, reference guides, stationery (High-impact student library donations, exam guide resale).
4. 🧸 **Toys & Sports Items**: Bicycles, cricket gear, board games (Chain/brake servicing, orphanages & community sports clubs).
5. 👕 **Clothing & Daily Goods**: Linens, curtains, wearables (Doorstep NGO drives & industrial fiber recycling).

### 3. Side-by-Side Honest Comparison Matrix
A transparent table comparing **Repair**, **Sell**, **Donate**, and **Recycle** across financial outcomes, real-world turnaround times, hidden costs, environmental impact, and required effort.

---

## 💻 Tech Stack & Architecture

This project is built purely using **Standard Semantic Web Technologies**:

* **HTML5**: Semantic document structure (`<header>`, `<main>`, `<article>`, `<details>`, `<footer>`), fully accessible to screen readers.
* **CSS3**:
  * CSS Custom Properties (Variables) for color palettes and spacing.
  * Modern **CSS Grid** & **Flexbox** for layout management.
  * Fluid responsive typography using `clamp()`.
  * Pure CSS animations (barcode laser viewfinder scan).
  * Native `<details>` / `<summary>` accordion for zero-JS interactivity.
* **Dependencies**: Zero external JS libraries, zero NPM packages, zero frameworks. 100% lightweight and fast-loading.

---

## 📱 Mobile-First Responsive Design

* **Fluid Breakpoints**: Optimized for ultra-small phones (< 380px), standard smartphones, tablets, and full desktop monitors.
* **Zero Horizontal Scroll**: Strict `overflow-x: hidden` and `min-width: 0` constraints across all flex and grid inputs.
* **Sticky Bottom Navigation**: Quick thumb-friendly mobile menu on smartphones that automatically hides on desktops.
* **Touch-Optimized**: Generous tap targets (min 44px) and smooth elastic horizontal swipe indicators on tables.

---

## 🚀 How to Run Locally

Since this project requires zero build steps or compilers, you can run it immediately on any machine:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/bartan-se-bazar-tak.git
   cd bartan-se-bazar-tak