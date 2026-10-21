# GSV — Beauty Beyond Expectations ✨

<p align="center">
  <strong>BEAUTY. STYLE. YOU.</strong>
</p>

<p align="center">
  A premium digital experience for beauty, elegance and self-care.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" />
  <img src="https://img.shields.io/badge/Responsive-Design-F28B50?style=for-the-badge" alt="Responsive Design" />
  <img src="https://img.shields.io/badge/Frontend-Only-343434?style=for-the-badge" alt="Frontend Only" />
</p>

---

## Overview

**GSV — Beauty Beyond Expectations** is a luxury-inspired, multi-page beauty services website designed to deliver an elegant, intuitive and responsive online experience.

Created with HTML5, CSS3 and Vanilla JavaScript, the project combines refined editorial aesthetics with practical features that help users explore beauty services, discover different looks, review pricing information and prepare appointment requests.

The visual identity is built around pearl white, warm ivory, shimmer silver and soft peach-orange accents, creating a sophisticated and consistent brand experience.

## ✨ Highlights

| Feature | Description |
|---|---|
| Luxury Interface | Minimal, editorial-inspired beauty brand design |
| Six Website Pages | Home, Services, Gallery, Prices, Booking and Contact |
| Service Discovery | Searchable service catalogue with category filters |
| Beauty Gallery | Image categories, interactive lightbox and look-based navigation |
| Price List | Organised pricing information with editable placeholders |
| Appointment Experience | Service selection, customer details and booking summary |
| Form Validation | Required fields, date validation and Indian mobile number checks |
| WhatsApp Ready | Configurable WhatsApp booking and contact links |
| Responsive Layout | Designed for mobile, tablet and desktop |
| Accessible Interactions | Semantic markup, keyboard support and visible focus states |

## 🖥️ Website Pages

**01 — Home**  
An editorial landing page introducing the GSV brand, featured services, benefits, gallery preview and beauty packages.

**02 — Services**  
A searchable catalogue of makeup, mehendi, hair styling, nails, skincare, waxing, threading, bridal services and saree draping.

**03 — Gallery**  
A visual portfolio layout featuring category filters, image previews and interactive lightbox navigation.

**04 — Prices**  
A clean, easy-to-scan service price list with editable rates, package information and booking links.

**05 — Book Appointment**  
A guided appointment-request interface with service selection, preferred date and time, customer details and a request summary.

**06 — Contact**  
A dedicated contact interface with configurable business details, a contact-form demonstration and frequently asked questions.

## 🛠️ Technology Stack

| Technology | Role |
|---|---|
| HTML5 | Semantic structure and content |
| CSS3 | Visual design, responsive layouts and transitions |
| Vanilla JavaScript | Search, filters, gallery, form validation and interactions |
| LocalStorage | Optional browser-local demonstration data |
| Google Fonts | Enhanced typography with system-font fallbacks |

Built without React, Vue, Angular, Node.js, npm, build tools, backend APIs or a database.

## 🎨 Design System

The GSV visual language prioritises elegance, whitespace, subtle details and readability.

| Design Token | Colour |
|---|---|
| Pearl White | `#FFFEFC` |
| Warm Ivory | `#F7F4F0` |
| Shimmer Silver | `#E5E7EB` |
| Soft Peach | `#F7C7A5` |
| Glossy Orange | `#F28B50` |
| Soft Orange | `#E9A477` |
| Primary Text | `#343434` |
| Body Text | `#666666` |

**Typography:** Playfair Display or Cormorant Garamond for headings, paired with Inter or Manrope for body text.

**Design principles:** Editorial layouts, balanced whitespace, fine borders, elegant image crops, restrained animations and mobile-first usability.

## 📁 Project Structure

```text
GSV/
├── index.html
├── services.html
├── gallery.html
├── prices.html
├── booking.html
├── contact.html
├── css/
│   └── style.css
├── js/
│   └── script.js
├── assets/
│   └── images/
│       └── README.md
└── README.md
```

## 🚀 Getting Started

GSV is designed to run as a static website without installation or compilation.

### Run Locally

1. Clone or download this repository.
2. Open the project folder.
3. Double-click `index.html`.
4. Navigate through the website using the main menu.

Alternatively, open the folder in Visual Studio Code and use a local preview extension.

### Clone the Repository

Replace the example URL below with your actual GitHub repository URL.

```bash
git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY.git
```

```bash
cd YOUR-REPOSITORY
```

Then open `index.html` in your browser.

## ⚙️ Configuration

Before using the website for a real business, update the following information.

- **Services:** Edit service names, categories, descriptions, prices and durations in the JavaScript configuration.
- **Pricing:** Replace placeholder rates with actual business-approved prices.
- **Images:** Replace demonstration imagery with original GSV photography or appropriately licensed images.
- **WhatsApp:** Configure the official business number in the JavaScript settings.
- **Contact Details:** Add the actual phone number, email address, Instagram profile, location and operating hours where applicable.

Keep business details centralised in the configuration where practical, so future changes remain easy to maintain.

## 📅 Appointment Request Flow

The booking interface is a frontend demonstration designed to illustrate the appointment-request experience.

1. Select a service or package.
2. Choose a preferred date, time and service location.
3. Enter the requested customer details.
4. Review the booking summary.
5. Prepare the request and receive a demonstration reference number.
6. Use the configured WhatsApp option to contact the business when available.

**Important:** Submitting the form does not confirm an appointment or send the request to GSV. Optional demo records may be saved in the current browser using LocalStorage. They are not shared with other devices or stored in a business database.

No payment processing, live availability, authentication, SMS delivery or automatic email delivery is implemented.

## 🔐 Privacy & Security

- No backend or shared customer database is included.
- Optional demo booking records remain in the current browser.
- No real appointment confirmation is generated.
- WhatsApp messages are only delivered if the user sends them through a correctly configured contact link.
- Avoid entering sensitive personal information into the demonstration form.

A real production booking system should use an appropriate backend or trusted booking service and publish an accurate privacy policy.

## 🌐 Deployment

The website can be deployed to any suitable static hosting provider.

For GitHub Pages:

1. Push the project files to GitHub.
2. Open the repository's **Settings → Pages**.
3. Select the appropriate deployment source and branch.
4. Choose the root directory if the HTML files are stored there.
5. Save the settings and open the published website URL.

Before publishing, verify all navigation links, image paths, contact details, responsive layouts and form behaviour.

## 🧪 Quality Checklist

- [ ] All six HTML pages are present.
- [ ] Navigation and active-page states work correctly.
- [ ] Service search and category filters work.
- [ ] Gallery filtering and lightbox controls work.
- [ ] Booking links preselect the appropriate service.
- [ ] Required fields and date validation work.
- [ ] Booking messages clearly explain the frontend-only limitations.
- [ ] Contact links use real configured business details.
- [ ] Mobile layouts have no horizontal overflow.
- [ ] Images have suitable alt text and graceful fallbacks.
- [ ] No placeholder prices or contact details are presented as genuine.

Mark these items complete only after testing the corresponding functionality.

## 🗺️ Future Improvements

- Replace demonstration images with original brand photography.
- Add verified prices, service durations and package details.
- Configure official business and social media links.
- Complete desktop and mobile browser testing.
- Publish the static website using GitHub Pages.
- Integrate a real booking solution if the business requires shared appointment management.

## 📄 License

No open-source license is specified by default. Add an appropriate license file before granting permissions for reuse, modification or redistribution.

---

<p align="center">
  <strong>GSV — Beauty Beyond Expectations</strong><br/>
  <em>Beauty. Style. You.</em>
</p>

<p align="center">
  Designed for elegance. Built for the modern beauty experience.
</p>
