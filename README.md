# Body Work Club

### Premium Fitness, Strength Training & Wellness Web Platform

<p align="center">
  <strong>An elite, ultra-responsive fitness website built with semantic HTML5, modern CSS3, and vanilla JavaScript.</strong>
</p>

<p align="center">
  Designed to deliver an exceptional digital experience for modern fitness enthusiasts, featuring a 5-theme switcher engine, interactive health calculators, program showcases, and comprehensive direct & alternative contact channels.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Brand-Body%20Work%20Club-e6533c?style=for-the-badge" alt="Brand: Body Work Club" />
  <img src="https://img.shields.io/badge/HTML5-Semantic%20Markup-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5" />
  <img src="https://img.shields.io/badge/CSS3-Custom%20Properties-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3" />
  <img src="https://img.shields.io/badge/JavaScript-Vanilla%20ES6+-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" />
  <img src="https://img.shields.io/badge/Responsive-Mobile%20First-0F766E?style=for-the-badge" alt="Mobile First" />
  <img src="https://img.shields.io/badge/License-MIT-2563EB?style=for-the-badge" alt="MIT License" />
</p>

---

## Table of Contents

- [Overview](#overview)
- [Key Features](#key-features)
- [Brand & Contact Channels](#brand--contact-channels)
- [Multi-Theme System](#multi-theme-system)
- [Project File Structure](#project-file-structure)
- [Interactive Components](#interactive-components)
- [Getting Started](#getting-started)
- [Design System & CSS Variables](#design-system--css-variables)
- [Browser Compatibility](#browser-compatibility)
- [License](#license)

---

## Overview

**Body Work Club** is a modern frontend fitness club website that merges athletic energy with sleek digital design. The platform showcases premium workout disciplines, certified master trainers, transparent membership tiers, an interactive BMI health utility, and multiple avenues for member inquiries and consultations.

Built purely with standard web technologies—without heavy runtime frameworks—Body Work Club ensures instantaneous load times, fluid transitions, and seamless responsiveness across smartphones, tablets, laptops, and ultra-wide displays.

---

## Key Features

- **Hero Banner with Dynamic Statistics:** Live animated counters, floating metric cards (Calories Burned, Heart Rate, Workouts Logged), and direct call-to-action buttons.
- **5-Theme Customization Engine:** Switch effortlessly between Default Dark, Clean Light, Ocean Blue, Emerald Green, and Royal Purple, with preferences automatically saved to `localStorage`.
- **Interactive BMI Calculator:** Real-time Body Mass Index calculation taking height, weight, age, sex, and activity factor into account with visual status classification.
- **Dedicated Contact & Consultation Hub:** Includes dedicated information cards with primary and alternative contact channels (phone, email, locations, hours, and instant chat).
- **Interactive Inquiry Form:** Equipped with client-side validation and toast notification feedback for inquiries, consultations, and support requests.
- **Dynamic Pricing Tier Toggle:** Instant monthly vs. annual pricing switch with automated discounts calculation.
- **Testimonials Carousel:** Auto-sliding testimonial cards featuring member reviews and success stories, pausing on user hover.
- **Mobile-First Navigation:** Responsive hamburger drawer menu with animated backdrop overlay and smooth anchor scrolling.
- **Toast Notification Engine:** Elegant floating status notifications for newsletter subscription and contact form submissions.

---

## Brand & Contact Channels

Body Work Club provides accessible support with both **primary** and **alternative** communication channels to ensure seamless member communication:

| Channel | Primary Details | Alternative / Secondary Details |
| :--- | :--- | :--- |
| **Phone Lines** | `+1 (800) 263-9675` *(+1 800 BODY-WRK)* | `+1 (888) 555-0199` *(24/7 Member Helpline)* |
| **Email Inquiries** | `info@bodyworkclub.com` *(General & Memberships)* | `support@bodyworkclub.com` *(Concierge & VIP)* |
| **Club Facilities** | **Main Facility:** 742 Evergreen Fitness Way, Suite 300, NY 10001 | **Downtown Studio:** 108 Hudson Street, 4th Floor, NY 10013 |
| **Operating Hours** | **Mon &ndash; Fri:** 5:00 AM &ndash; 11:00 PM | **Sat &ndash; Sun:** 6:00 AM &ndash; 10:00 PM |
| **Instant Chat** | Website Consultation Form | WhatsApp Support: `+1 (800) 263-9675` |
| **Member Perks** | On-site Valet & Dedicated Parking | Digital Member Portal & Nutrition Guides |

---

## Multi-Theme System

Body Work Club includes five pre-configured color themes driven entirely by CSS custom properties. The active theme persists across page reloads:

| Theme Icon | Theme Name | Primary Accent | Background Mode |
| :---: | :--- | :--- | :--- |
| 🏋️ | **Default (Dark)** | Sunset Orange (`#e6533c`) | Deep Charcoal (`#0f0f0f`) |
| ☀️ | **Light** | Sunset Orange (`#e6533c`) | Crisp White / Slate (`#f8fafc`) |
| 🌊 | **Blue** | Electric Cyan (`#3b82f6`) | Midnight Navy (`#0f172a`) |
| 🍃 | **Green** | Emerald (`#10b981`) | Forest Obsidian (`#0c0f0c`) |
| 💎 | **Purple** | Neon Violet (`#8b5cf6`) | Deep Plum (`#0f0f23`) |

---

## Project File Structure

```text
Body-Work-Club/
├── index.html              # Main HTML5 landing page & semantic structure
├── LICENSE                 # MIT License terms
├── README.md               # Project documentation and guide
├── js/
│   └── script.js           # Theme engine, mobile menu, BMI logic, sliders & form handlers
├── styles/
│   └── fitness.css         # CSS3 styling, color themes, grid/flexbox layouts & media queries
└── images/                 # Optimized visual assets and trainer photography
    ├── exercise1.jpg ... exercise6.jpg
    ├── trainer1.png ... trainer6.png
    ├── image 2.png ... image 5.png
    ├── roni.jpg, run.jpg, samiul.jpg, k.jpg
    └── Images 2.png
```

---

## Interactive Components

### 1. Contact & Consultation Section (`#contact`)
- Presents **Primary** and **Alternative** contact cards side-by-side with an inquiry submission form.
- The form captures full name, primary email, alternative phone/email, inquiry department (Memberships, Personal Training, Consultation, Support), and message.
- Upon submission, inputs are validated and a responsive toast notification confirms delivery without page reload.

### 2. BMI Calculator (`#bmi`)
- Accepts metric inputs: height (cm), weight (kg), age, and activity factor.
- Computes BMI using the formula:
  $$\text{BMI} = \frac{\text{weight (kg)}}{(\text{height (m)})^2}$$
- Automatically highlights the health classification:
  - **Underweight:** BMI < 18.5
  - **Normal weight:** 18.5 &le; BMI < 25.0
  - **Overweight:** 25.0 &le; BMI < 30.0
  - **Obese:** BMI &ge; 30.0

### 3. Dynamic Pricing Switch
- Toggling the billing frequency updates cards between Monthly and Annual rates (incorporating a 20% annual discount) with instant UI updates.

### 4. Interactive Testimonials Slider
- Automatically cycles through member transformation stories every 5 seconds.
- Automatically pauses on mouse hover so users can comfortably read reviews.

---

## Getting Started

### Prerequisites
Body Work Club is completely self-contained and requires no build tools or package managers. Any modern web browser is sufficient.

### Running Locally

1. **Clone the repository:**
   ```bash
   git clone https://github.com/md-abu-kayser/fitnesspro-ui.git Body-Work-Club
   cd Body-Work-Club
   ```

2. **Open in browser:**
   - Double-click `index.html` to open directly in your preferred browser, or:
   - Use VS Code **Live Server** extension, or:
   - Run a lightweight HTTP server:
     ```bash
     # Using Python 3
     python -m http.server 3000

     # Using Node.js (npx)
     npx serve .
     ```

3. **Navigate to:** `http://localhost:3000`

---

## Design System & CSS Variables

The website is constructed around a clean tokenized variable palette in `styles/fitness.css`:

```css
:root {
  --primary-color: #e6533c;
  --secondary-color: #ff7b5c;
  --background-color: #0f0f0f;
  --surface-color: #1a1a1a;
  --card-color: #222222;
  --text-primary: #ffffff;
  --text-secondary: rgba(255, 255, 255, 0.7);
  --text-muted: rgba(255, 255, 255, 0.5);
  --border-color: rgba(255, 255, 255, 0.1);
  --gradient: linear-gradient(135deg, #e6533c 0%, #ff7b5c 100%);
  --shadow: 0 10px 30px rgba(0, 0, 0, 0.3);
  --shadow-lg: 0 20px 60px rgba(0, 0, 0, 0.4);
}
```

Typography relies on **Inter** and **Poppins** via Google Fonts, and iconography is powered by **Font Awesome 6**.

---

## Browser Compatibility

- **Google Chrome** (v90+)
- **Mozilla Firefox** (v88+)
- **Apple Safari** (v14+)
- **Microsoft Edge** (v90+)
- **Mobile Browsers** (Chrome Android, Safari iOS, Samsung Internet)

---

## License

This project is open-source and distributed under the [MIT License](./LICENSE).

---

<p align="center">
  <strong>Body Work Club &bull; Elevating Movement, Health & Longevity</strong>
</p>
