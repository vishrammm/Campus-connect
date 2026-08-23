# Campus Connect 🎓

> **A modern, centralized campus engagement and collaboration platform tailored for college students, club organizers, staff members, and administrators.**

---

## 🌟 Overview

**Campus Connect** is a responsive web application designed to bridge communication gaps, streamline student interactions, and foster an active, engaged campus community. By consolidating essential campus utilities into a unified hub, students, staff, and faculty can seamlessly collaborate, share announcements, buy/sell academic goods, and locate misplaced belongings.

---

## ✨ Key Features & Modules

### 🔍 1. Lost & Found Hub
- **Browse & Search:** Filter lost or found items across campus by category (Electronics, Accessories, Books, Stationery, Personal Items) and location.
- **Reporting System:** Instant reporting flow for misplaced or discovered items with descriptions, timestamps, and locations.
- **Staff Security Desk Integration:** Staff members can record found items deposited at the campus Security Desk.

### 📢 2. Digital Notice Board
- **Official Announcements:** View institutional notices, academic circulars, exam schedules, and committee guidelines in real time.
- **Category Badges & Priority Tags:** Distinct visual markers for *Important* and category-specific updates (Academic, Examination, NSS, Guidelines).
- **Document Attachments:** Quick preview and download options for PDFs and official circulars.

### 🎪 3. Club & Event Hub
- **Club Directory:** Discover student clubs, technical societies (Coding Club, Robotics Club, IEEE), and cultural organizations.
- **Event Discovery & Registration:** Browse upcoming hackathons, workshops, fests, and sports tournaments with single-click registration tracking.
- **Co-Admin Club Management:** Club leads can create, update, or remove events for their respective organizations.

### 🛍️ 4. Campus Marketplace (P2P Exchange)
- **Student Peer-to-Peer Trading:** Buy and sell textbooks, scientific calculators, Arduino starter kits, lab coats, and campus cycles.
- **Condition Grading & Pricing:** Transparent price tags and verified condition chips (*Like New*, *Good*, *Fair*, *Used*).
- **Direct Seller Inquiries:** In-app contact modals enabling safe, localized campus meetups.

### 👥 5. Role-Based Access & Dashboards
- **Student:** Access personalized feeds, item reporting, event RSVP, marketplace listing, and profile management.
- **Co-Admin (Club Lead):** Publish departmental notices, manage club events, track RSVPs, and view analytics.
- **Staff Member:** Official staff reporting desk for lost & found items and campus operations.
- **System Administrator:** High-level platform statistics, student directory management, and system-wide moderation.

### 🌓 6. Adaptive Design & Dark/Light Theme
- Fully responsive layout optimized for mobile, tablet, and desktop viewports.
- Integrated Dark Mode and Light Mode toggles with fluid transitions and backdrop-blur glassmorphism.

---

## 🛠️ Tech Stack

- **Frontend Core:** React 18, TypeScript, Vite 6
- **Styling & UI:** Tailwind CSS v4, Radix UI Primitives, Lucide React Icons
- **Typography:** Plus Jakarta Sans & Inter (Google Fonts)
- **Tooling:** PostCSS, ESBuild, npm

---

## 🚀 Getting Started

### Prerequisites
- [Node.js](https://nodejs.org/) (version 18 or higher recommended)
- [npm](https://www.npmjs.com/) (or yarn / pnpm)

### Installation

1. **Clone or navigate to the project directory:**
   ```bash
   cd "Campus Connect Web Application"
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Start the development server:**
   ```bash
   npm run dev
   ```
   Open your browser and navigate to `http://localhost:5173`.

4. **Build for production:**
   ```bash
   npm run build
   ```

---

## 📁 Project Structure

```
├── public/                 # Static assets (campus hero image, icons)
├── src/
│   ├── app/
│   │   ├── components/
│   │   │   └── ui/         # Reusable UI component library (buttons, inputs, dialogs, etc.)
│   │   └── App.tsx         # Main application component, routing & role views
│   ├── styles/
│   │   ├── fonts.css       # Web font imports (Plus Jakarta Sans, Inter)
│   │   ├── index.css       # Core stylesheet entry point
│   │   ├── tailwind.css    # Tailwind CSS v4 setup & animations
│   │   └── theme.css       # Design tokens, CSS variables & typography rules
│   └── main.tsx            # React application entry point
├── index.html              # HTML5 entry template
├── package.json            # Project dependencies and npm scripts
├── postcss.config.mjs      # PostCSS configuration
├── vite.config.ts          # Vite build configuration & path aliases
├── prd.md                  # Product Requirements Document
├── design.md               # Design System & UI/UX Architecture
└── techstack.md            # Technical Architecture & Stack Specifications
```

---

## 📄 Documentation

- [Product Requirements Document (PRD)](./prd.md)
- [Design Architecture & System](./design.md)
- [Technical Stack & Architecture](./techstack.md)

---

## 📄 License
This project is developed for academic and campus community use under the [MIT License](LICENSE).