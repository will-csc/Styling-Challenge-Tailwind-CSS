# 🚀 Front-end Styling Challenge – Tailwind CSS Migration

This project aims to modernize the UI of an e-commerce dashboard by replacing all traditional CSS with **Tailwind CSS utility classes**. The base layout and interaction logic are already provided in **HTML** and **JavaScript**, including page navigation, simulated data handling, and Chart.js visualizations.

---

## 🎯 Objective

Remove the old `style.css` file and rewrite **100% of the styling directly in the HTML** using Tailwind utility classes in the `class` attributes.

---

## 📌 Provided Files

| File | Description |
|--------|------------|
| `index.html` | Contains the structure of all dashboard pages (Home, Dashboard, Products, Customers) |
| `script.js` | Handles navigation, simulated register actions, and chart rendering |
| `tailwind.config.js` (simulated) | Tailwind configuration including the company’s primary color |

---

## 🖌️ Styling Requirements

### **1. Colors & Typography**
- Primary brand color: `#29e361`
- Must be set in Tailwind theme as `primary`
- Class usage examples: `bg-primary-500`, `text-primary-600`, `border-primary-500`
- Typography: modern and clean — `font-sans`

### **2. Layout & Sidebar**
- Use **Flexbox** for main structure
- Sidebar on the left, vertical navigation
- Must remain fixed with `overflow-y-auto` in the main content

**Sidebar requirements:**
- Dark background (`bg-gray-800`)
- Fixed width on desktop (`w-64`)
- Menu items with padding, hover effects, and smooth transitions  
  Example: `p-3 transition duration-200 hover:bg-gray-700 text-primary-400`

**Header:**
- Light background (`bg-white`)
- Soft shadow (`shadow-sm`)
- Flexbox horizontal alignment

### **3. Cards, Forms & Tables**
**Stat Cards:**
- Responsive grid: `grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4`
- White background, rounded corners, shadow, and left border in primary color

**Forms:**
- Modern input styles with focus states, e.g. `focus:ring-primary-500`

**Tables:**
- Professional look with a primary-colored header
- Subtle borders and alternating row stripes

### **4. Buttons**
- Primary button example:  
  `bg-primary-500 hover:bg-primary-600 text-white font-semibold transition`

---

## 📱 Responsiveness

The layout must adapt to all screens using Tailwind breakpoints:

---

## ✅ Evaluation Criteria

| Requirement | Condition |
|------------|-----------|
| Tailwind-only styling | No CSS files or `<style>` tags |
| Responsive design | Works on mobile and desktop |
| Visual quality | Clean, modern, and professional |
| Brand identity | Uses `#29e361` consistently |

---

## 📅 Submission

**Deadline:** `November 28, 2025`  
**Send to:** `rafael.venancio@pro.fecaf.com.br`  
or  
Submit via **GitHub repository link**

---

## 🛠️ Tech Stack

- Tailwind CSS  
- Vanilla JavaScript  
- Chart.js  
- HTML5

---

## 💡 Expected Result

A modern, polished, fully responsive dashboard interface — styled **exclusively with Tailwind CSS**, without a single line of traditional CSS.

---


