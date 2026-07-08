# Bliss Out Dance Studio — Frontend Web App

The public-facing frontend web application for Bliss Out Dance Studio's Garba Workshop registration, scheduling, and digital pass checkout system. Built purely on core web fundamentals to maximize performance and cross-device responsiveness.

## 🚀 Live Demo
* **Live Website:** [https://bliss-out-frontend.vercel.app](https://bliss-out-frontend.vercel.app)

## 📁 Repository Architecture
This is a decoupled application architecture. This repository contains the complete frontend UI and client-side logic. 

* **Backend Repository:** The corresponding Node.js/Express server and API logic can be found here: [Insert link to your Backend GitHub Repo here]
* **Live API Endpoint:** [https://bliss-out-backend.vercel.app](https://bliss-out-backend.vercel.app)

## 🛠️ Tech Stack & Tools
* **Languages:** Vanilla HTML5, CSS3, JavaScript (ES6+)
* **UI Utilities:** Google Fonts, Custom CSS Design tokens (Variables)
* **Animation:** Native Browser `IntersectionObserver` API for lightweight scroll reveals
* **Payment Form Interaction:** Integrated script loading via `checkout.js` for secure checkout layers

## ✨ Key Frontend Features
* **Design Token System:** Implemented a unified system of custom root CSS variables for colors, spacing, and animations, making the design fully cohesive and easy to scale.
* **Intersection Observer Logic:** Configured smooth, client-side fade-in animations as elements enter the viewport without relying on bulky external animation packages.
* **State Preservation:** Utilized `localStorage` to securely pass structured session datasets (batch choice, customer records) seamlessly to the payment gateway view.
* **Digital Ticket Wrapper:** Implemented state verification logic on the final pass layout page, safely rendering the user's PDF ticket or providing direct WhatsApp outreach capabilities.