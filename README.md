# 🏦 Sanad Capital Website

A clean, modern static website for Sanad Capital—a financial services firm—highlighting investment solutions, company information, and contact details.

---

## Table of Contents

- [About](#about)  
- [Features](#features)  
- [Tech Stack](#tech-stack)  
- [Folder Structure](#folder-structure)  
- [Getting Started](#getting-started)  
  - [Prerequisites](#prerequisites)  
  - [Installation](#installation)  
  - [Running Locally](#running-locally)  
- [Deployment](#deployment)  
- [Contributing](#contributing)  
- [Future Enhancements](#future-enhancements)  
- [Contact](#contact)  
- [License](#license)  

---

## About

This repository contains the source code and assets for the Sanad Capital website—a responsive, single-page (or multi-section) site built with HTML5, CSS3, and vanilla JavaScript to present Sanad Capital’s services, team, and get in touch information in a polished, professional layout.

---

## Features

- **Responsive design** for all screen sizes (desktop, tablet, mobile)  
- Hero banner with call-to-action  
- Services overview section  
- “About Us” / company mission section  
- Team profiles / advisor bios  
- Contact form with client-side validation  
- Smooth scroll navigation  
- Style guide documentation (`Style_guide.md`)  

---

## Tech Stack

- **HTML5** — semantic markup  
- **CSS3** — Flexbox, CSS Grid, CSS variables, media queries  
- **JavaScript (vanilla)** — DOM manipulation, form handling  
- **No build tools** — zero-dependency, instantly viewable

---

## Folder Structure

```

Sanad\_Capital\_Website/
│
├── assets/               # Images, icons, logos
│   ├── img/
│   └── fonts/
│
├── css/                  # Stylesheets
│   └── style.css
│
├── js/                   # JavaScript files
│   └── main.js
│
├── Style\_guide.md        # Design tokens & typography guidelines
├── index.html            # Main landing page
└── README.md             # ← you are here

````

> **Note:** adjust file/folder names above if your layout differs.

---

## Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Edge, Safari)  
- (Optional) [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) for VS Code  

### Installation

1. Clone the repo  
   ```bash
   git clone https://github.com/Moaz-Allam/Sanad_Capital_Website.git
   cd Sanad_Capital_Website
   ````

2. (Optional) Open in VS Code and enable **Live Server** for hot-reload:

   ```bash
   code .
   # then right-click index.html → Open with Live Server
   ```

### Running Locally

* **Without a server:**
  Simply open `index.html` in your browser.

* **With Live Server:**
  Right-click `index.html` → **Open with Live Server**.
  Changes to HTML/CSS/JS will auto-refresh.

---

## Deployment

You can host this static site on any platform:

* **GitHub Pages**:

  1. In your repository’s **Settings → Pages**, choose the `main` branch and `/ (root)` folder.
  2. Save. Your site will be published at:

     ```
     https://moaz-allam.github.io/Sanad_Capital_Website/
     ```

* **Netlify / Vercel / Surge**:
  Drag & drop the project folder (or link your GitHub repo) to deploy instantly.

---

## Contributing

Contributions welcome!

1. Fork the repository
2. Create a branch (`git checkout -b feature/YourFeature`)
3. Commit your changes (`git commit -m "Add YourFeature"`)
4. Push to your branch (`git push origin feature/YourFeature`)
5. Open a Pull Request

Please ensure consistency with existing code style and update `Style_guide.md` if new design tokens or typography rules are added.

---

## Future Enhancements

* 📊 Interactive investment calculator widget
* 🗺️ Map integration for regional offices
* 🔔 Newsletter signup / mail-chimp integration
* 🌐 Multi-language support
* 🏆 Testimonials / client success stories

Feel free to open issues or feature requests!

---

## License

Licensed under the **MIT License**. See [LICENSE](LICENSE) for details.

```
```
