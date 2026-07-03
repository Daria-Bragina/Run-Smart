<img width="1269" height="1121" alt="2026 07 03 15-17-32" src="https://github.com/user-attachments/assets/dbd52a97-e1a2-42ce-82aa-07d9fef03abc" />
# 🏃 Run Smart

A landing page for a heart rate monitor shop. Built with vanilla HTML, CSS, and JavaScript — no frameworks, no build tools, just clean hand-written code.

**[Live Demo →](https://daria-bragina.github.io/Run-Smart/)**

---

## Screenshots

> _Add a screenshot of the landing page here — drag an image directly into the GitHub editor_

---

## Features

- 🎠 **Image carousel** — product slider built with Slick.js
- 🗂️ **Tabbed catalog** — products grouped by category (fitness / running / triathlon) with flip-card detail view
- 📋 **Lead capture forms** — consultation request and order forms with validation and phone masking
- 💬 **Modal windows** — consultation modal, order modal, and thank-you confirmation
- ✨ **Scroll animations** — elements animate in on scroll via WOW.js + Animate.css
- 🗺️ **Google Maps embed** — store location in the footer
- 📧 **PHP mailer** — form submissions handled server-side
- 📱 **Responsive layout** — mobile-friendly with Bootstrap Reboot

---

## Tech Stack

| Category | Technology |
|---|---|
| Markup | HTML5 |
| Styles | CSS3 (custom), Bootstrap Reboot |
| Scripts | JavaScript, jQuery 1.11 |
| Slider | Slick.js |
| Animations | WOW.js + Animate.css |
| Form validation | jQuery Validate |
| Phone masking | jQuery Masked Input |
| Mailer | PHP |
| Deployment | GitHub Pages |

---

## Project Structure

```
Run-Smart/
├── index.html          # Single-page layout with all sections
├── styles/
│   ├── style.min.css   # Main stylesheet
│   ├── font.css        # Custom font declarations
│   ├── slick.css       # Slider styles
│   └── bootstrap-reboot.min.css
├── js/
│   ├── script.js       # Custom JS: tabs, modals, carousel init
│   ├── slick.min.js
│   ├── wow.min.js
│   ├── jquery.validate.min.js
│   └── jquery.maskedinput.min.js
├── mailer/             # PHP form handler
├── images/             # Product images, icons, review avatars
└── fonts/              # Custom web fonts
```

---

## Page Sections

| Section | Description |
|---|---|
| Hero | Main CTA with brand partners (Garmin, Polar, Suunto) |
| Advantages | Three key selling points with icons |
| Consultation form | Lead capture with name, phone, email |
| Carousel | Product image slider |
| Catalog | Tabbed product grid with flip-card details and prices |
| Reviews | Three customer testimonials with scroll animations |
| Footer | Google Maps embed, address, phone, social links |

---

## Running Locally

No build step required — open `index.html` directly in a browser.

```bash
git clone https://github.com/Daria-Bragina/Run-Smart.git
cd Run-Smart
open index.html   # or just drag index.html into your browser
```

> Note: PHP mailer requires a server environment (e.g. XAMPP, MAMP, or a hosting provider). Form submissions will not work when opened as a local file.

---

## Author

**Daria Bragina** — Frontend Developer  
[GitHub](https://github.com/Daria-Bragina)
