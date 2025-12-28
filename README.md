# 🚐 Noorha Transport – Booking Flow Experience

**Noorha Transport Booking Flow** is a modern, multilingual booking experience designed to simplify private transport reservations with accuracy, performance, and reliability.

This project focuses on delivering a **smooth, user-friendly booking journey** — from route selection to lead submission — optimized for both local and international users.

---

## 📌 Overview

This project was developed as part of a professional engagement with **Noorha Transport**.  
My responsibility was **limited to the booking flow only**, delivered as a standalone MVP and integrated into the existing platform.

The work included translating complex logistics requirements into a **pixel-perfect, performant, and scalable booking experience**.

> 🧭 The updated booking flow is currently deployed on a staging environment.  
> The main production website has not yet released these updates.

---

## 🚀 Live Links

- 🔄 **Booking Flow (Staging / Preview):**  
  https://noorha-transport-booking.vercel.app/booking-flow

- 🌐 **Main Website (Production):**  
  https://noorhatransport.com/

---

## ✨ Key Contributions

### 🎯 MVP Booking Application
- Pixel-perfect **Figma → Next.js** implementation (TypeScript + Tailwind CSS)
- Fully **responsive booking screens**
- **Google Maps Place Autocomplete** integration
- **Google Maps distance calculation** for routes
- Optimized UX for booking clarity and speed

---

### 🌍 Internationalization (i18n)
- **Bilingual support:** English (EN) & Arabic (AR)
- Full **RTL support** for Arabic:
  - `dir="rtl"` handling
  - Localized routes & content
  - Correct layout mirroring
- Clean, scalable localization setup using `next-intl`

---

### 📊 Analytics & Tracking
- **Google Analytics 4 (GA4)** event wiring:
  - `begin_checkout`
  - `select_item`
  - `generate_lead`
  - Page view tracking
- Analytics structured to support funnel analysis and conversion tracking

---

### 🔐 Security & Anti-Spam
- Security headers implementation:
  - Content Security Policy (CSP)
  - Referrer Policy
  - Additional best-practice headers
- Bot protection using **reCAPTCHA / hCaptcha**
- PDPL consent handling within booking submission

---

### 🔗 Server Integrations & Launch Scope

#### 🧾 Zoho CRM
- OAuth authentication
- Lead creation with full booking payload:
  - Customer name
  - Phone / Email
  - Route & distance
  - Date & time
  - Passenger count
  - Vehicle type
  - UTM parameters
  - PDPL consent flag

#### 📅 Google Calendar
- Automatic calendar event creation per booking
- Event includes:
  - Start & end time
  - Customer details
  - Route notes
- Calendar Event ID returned and stored

---

### ⚡ Performance Optimization
- Met **Core Web Vitals targets**:
  - **LCP ≤ 2.5s**
  - **INP ≤ 200ms**
  - **CLS ≤ 0.1**
- Optimized rendering, data flow, and layout stability

---

## ⚙️ Tech Stack

| Technology        | Version    | Description                                   |
|-------------------|------------|-----------------------------------------------|
| **Next.js**        | 16.0.10    | App routing & rendering engine                |
| **React**          | 19.2.0     | UI library                                    |
| **TypeScript**     | 5.9.3      | Type-safe development                         |
| **Tailwind CSS**   | 3.4.18     | Utility-first styling                         |
| **next-intl**      | 4.4.0      | Internationalization (EN / AR, RTL)           |
| **Google Maps API**| —          | Places Autocomplete & distance calculation   |
| **GA4**            | —          | Analytics & event tracking                    |
| **Zoho CRM API**   | —          | Lead management integration                  |
| **Google Calendar API** | —    | Booking event automation                     |
| **Vercel**         | —          | Staging & preview deployments                |

---

## 🔐 Privacy & Security Notice

> ⚠️ **Important**  
> This project was developed for a **private client**.  
>
> Due to **confidentiality, security, and intellectual property constraints**, the full **source code cannot be shared publicly**.  
>
> This repository exists strictly for **portfolio and professional showcase purposes**.

---

## 🧑‍💻 Developer Note

> The booking flow was engineered with a strong focus on **accuracy, international usability, performance, and real-world business requirements**.  
>  
> Special attention was given to RTL behavior, analytics reliability, CRM integration, and production-grade security practices — ensuring the solution is scalable and launch-ready.

---

## 📫 Contact

Interested in building enterprise-grade booking systems, dashboards, or multilingual platforms?

- 💼 **Upwork:** https://www.upwork.com/freelancers/~01bf24b7725d70b752  
- 🌐 **Portfolio:** https://shahinuralambhuiyan.vercel.app  
- 📧 **Email:** shahinur.alam.bhuiyan01@gmail.com  

---

## 📄 License

This repository is **not licensed for redistribution or reuse**.  
All content is provided for **demonstration and portfolio purposes only**.

---

> © 2025 – **Noorha Transport Booking Flow**  
> _Booking Flow UI & Integrations developed by Shahinur Alam Bhuiyan_
