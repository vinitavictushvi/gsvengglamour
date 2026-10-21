# GSV® — Beauty Beyond Expectations



<p align="center">
  <strong>BEAUTY. STYLE. YOU.</strong>
  <br />
  An elevated digital experience for beauty, confidence and self-care.
</p>

<p align="center">
  <a href="https://github.com/YOUR-USERNAME/YOUR-REPOSITORY">
    <img src="https://img.shields.io/badge/PROJECT-GSV-F28B50?style=flat-square" alt="GSV Project" />
  </a>
  <img src="https://img.shields.io/badge/HTML5-SEMANTIC-E34F26?style=flat-square&logo=html5&logoColor=white" alt="HTML5" />
  <img src="https://img.shields.io/badge/CSS3-RESPONSIVE-1572B6?style=flat-square&logo=css3&logoColor=white" alt="CSS3" />
  <img src="https://img.shields.io/badge/JAVASCRIPT-VANILLA-F7DF1E?style=flat-square&logo=javascript&logoColor=black" alt="Vanilla JavaScript" />
  <img src="https://img.shields.io/badge/DEPENDENCIES-NONE-6C9A7F?style=flat-square" alt="No required dependencies" />
  <img src="https://img.shields.io/badge/DEPLOYMENT-STATIC-343434?style=flat-square" alt="Static deployment" />
</p>

<p align="center">
  <a href="#-overview">Overview</a> ·
  <a href="#-experience">Experience</a> ·
  <a href="#-architecture">Architecture</a> ·
  <a href="#-getting-started">Get Started</a> ·
  <a href="#-customization">Customization</a>
</p>

---

## 01 — The Vision

**Beauty deserves a digital experience as thoughtful as the service itself.**

GSV — Beauty Beyond Expectations is a luxury-inspired, multi-page website concept for a modern women's beauty and personal-care brand.

Designed around a refined editorial aesthetic, GSV brings together beauty service discovery, visual inspiration, transparent pricing, appointment-request preparation and customer contact into one cohesive experience.

The result is a frontend project that balances **visual sophistication, practical functionality and maintainable code** without relying on a JavaScript framework or backend infrastructure.

> A quieter aesthetic. A more thoughtful experience. A brand that puts you first.

---

## 02 — The Experience

GSV is organised into six dedicated pages, each serving a distinct purpose within the customer journey.

| Page | Experience | Purpose |
|---|---|---|
| `Home` | Brand introduction | Discover the GSV identity and featured experiences |
| `Services` | Service discovery | Search, filter and explore beauty services |
| `Gallery` | Visual inspiration | Browse beauty looks and explore images |
| `Prices` | Pricing transparency | Review service rates or request a quote |
| `Book Appointment` | Request preparation | Select preferences and prepare an appointment request |
| `Contact` | Customer communication | Explore contact options and frequently asked questions |

### The customer journey

`DISCOVER` → `EXPLORE` → `GET INSPIRED` → `REVIEW PRICES` → `PREPARE REQUEST`

Every page follows the same visual language, navigation system and brand identity.

---

## 03 — Signature Features

### ✦ Luxury Interface Design

- Pearl-white and warm-ivory foundations.
- Soft peach and restrained glossy-orange accents.
- Elegant serif headlines paired with readable sans-serif typography.
- Delicate silver separators, fine borders and understated shadows.
- Editorial image treatments, carefully balanced spacing and refined transitions.

### ✦ Intelligent Service Discovery

- Organised beauty service catalogue.
- Category-based filtering.
- Search across service names and categories.
- Clear empty states and filter-reset controls.
- Direct navigation from a selected service to the booking form.

### ✦ Editorial Beauty Gallery

- Curated category-based image layouts.
- Responsive image compositions.
- Hover effects and interactive image lightbox.
- Previous and next image navigation.
- Keyboard support and Escape-key dismissal.
- Service-aware booking links.

### ✦ Transparent Pricing Experience

- Structured service price lists.
- Editable pricing data.
- Category filters.
- Service-specific booking links.
- `Price on request` placeholders where official rates are unavailable.
- Clear notes for policies and potential additional charges.

### ✦ Appointment Request Interface

- Service and optional package selection.
- Preferred date and time.
- Salon or home-visit preference.
- Customer information and booking summary.
- Indian mobile-number validation.
- Past-date prevention.
- Demonstration reference number.
- Optional browser-local demo history.
- Configurable WhatsApp message preparation.

### ✦ Contact & Support

- Editable business contact information.
- Contact-form demonstration.
- WhatsApp contact option when configured.
- Accessible FAQ accordions.
- Clear messaging when a real communication endpoint is unavailable.

### ✦ Responsive & Accessible Foundations

- Semantic HTML landmarks.
- Keyboard-accessible controls.
- Visible focus states.
- Form labels and validation feedback.
- Reduced-motion support.
- Lazy-loaded below-the-fold images.
- Responsive layouts designed for mobile, tablet and desktop.

*Feature availability depends on the implementation in the repository; verify the corresponding interactions before describing them as production-tested.*

---

## 04 — Visual Identity

The GSV design system is inspired by premium beauty editorials: clean compositions, subtle reflective details and warm, understated accents.

### Colour palette

| Token | Hex | Application |
|---|---|---|
| Pearl White | `#FFFEFC` | Main backgrounds |
| Warm Ivory | `#F7F4F0` | Soft section backgrounds |
| Shimmer Silver | `#E5E7EB` | Borders and separators |
| Soft Peach | `#F7C7A5` | Decorative highlights |
| Glossy Orange | `#F28B50` | Primary actions and accents |
| Soft Orange | `#E9A477` | Secondary highlights |
| Primary Text | `#343434` | Headings and prominent text |
| Body Text | `#666666` | Supporting content |

### Typography

- **Editorial headings:** Playfair Display or Cormorant Garamond.
- **Body typography:** Inter or Manrope.
- **Brand treatment:** Refined serif wordmark with generous spacing.

### Design principles

`CLARITY` · `WHITESPACE` · `CONSISTENCY` · `ACCESSIBILITY` · `RESTRAINT`

The visual direction prioritises a recognisable brand experience over excessive gradients, decorative clutter or unnecessary animation.

---

## 05 — Technology & Engineering

<p align="center">
  <img src="https://skillicons.dev/icons?i=html,css,js,git,github,vscode" alt="HTML, CSS, JavaScript, Git, GitHub and Visual Studio Code" />
</p>

| Technology | Implementation |
|---|---|
| HTML5 | Semantic page structure and accessible content |
| CSS3 | Design tokens, layouts, responsive styling and motion |
| Vanilla JavaScript | Navigation, search, filters, lightbox and forms |
| LocalStorage | Optional browser-local demonstration data |
| Git & GitHub | Version control and source hosting |
| Static Hosting | Optional deployment without server-side code |

**Architecture decisions**

- No React, Next.js, Vue or Angular.
- No Node.js, npm or build pipeline.
- No required backend or database.
- No authentication or payment gateway.
- Shared CSS and JavaScript across the six pages.
- Page-specific initialisation guarded by element availability.
- Business data and configuration organised for straightforward editing.

---

## 06 — Project Architecture

```text
GSV/
│
├── index.html
├── services.html
├── gallery.html
├── prices.html
├── booking.html
├── contact.html
│
├── css/
│   └── style.css
│
├── js/
│   └── script.js
│
├── assets/
│   └── images/
│       └── README.md
│
└── README.md
```

### Separation of responsibilities

**HTML — Structure**

Defines page content, navigation, forms, accessible labels and semantic sections.

**CSS — Presentation**

Controls brand colours, typography, spacing, reusable components, responsive behaviour and motion.

**JavaScript — Interaction**

Manages navigation states, service discovery, gallery interactions, booking summaries, validation and contact-form behaviour.

**Assets — Visual identity**

Documents image sources and provides a place for original GSV photography and brand assets.

---

## 07 — Getting Started

GSV is designed to run as a static website without installing dependencies or compiling source code.

### Option A — Run directly

1. Download or clone the repository.
2. Open the project folder.
3. Double-click `index.html`.
4. Explore the website through its navigation.

### Option B — Clone with Git

Replace the example URL with the actual repository URL.

```bash
git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY.git
cd YOUR-REPOSITORY
```

Open `index.html` in a modern browser.

### Option C — Use Visual Studio Code

1. Open the project folder in VS Code.
2. Open `index.html`.
3. Preview the website in your browser.
4. Edit `css/style.css` and `js/script.js` as required.

A local preview extension is optional, not a project dependency.

---

## 08 — Configuration & Customization

Before presenting GSV as a real business website, replace all demonstration content with verified information.

### Services & Categories

Edit the service data in `js/script.js`.

Update:

- Service names and descriptions.
- Category assignments.
- Price values or request-based pricing.
- Estimated durations.
- Related images and booking links.

Keep the service data centralised wherever possible so the catalogue, pricing page and booking interface remain consistent.

### Brand & Styling

Edit the CSS custom properties in `css/style.css`.

```css
:root {
  --color-pearl: #FFFEFC;
  --color-ivory: #F7F4F0;
  --color-silver: #E5E7EB;
  --color-peach: #F7C7A5;
  --color-orange: #F28B50;
  --color-orange-soft: #E9A477;
  --color-text: #343434;
  --color-muted: #666666;
}
```

Adjust the design tokens rather than duplicating colour values across multiple components.

### Photography

Replace demonstration imagery with original GSV photographs or appropriately licensed images.

For each image, provide:

- A descriptive alt attribute.
- An appropriate crop and aspect ratio.
- A stable local or remote image path.
- A graceful fallback for failed image loads.

Image-source and replacement notes belong in `assets/images/README.md`.

### Business Information

Configure the genuine:

- WhatsApp business number.
- Phone number and email.
- Instagram profile.
- Business address, if applicable.
- Operating hours.
- Verified service prices and policies.

Do not publish example values as actual business details.

---

## 09 — Appointment Requests & Data Boundaries

The appointment workflow is a **frontend-only demonstration**, not a live booking platform.

### What it can demonstrate

1. Selecting a service and package.
2. Choosing a preferred date, time and location.
3. Entering customer details.
4. Reviewing a booking summary.
5. Generating a local demonstration reference.
6. Preparing a WhatsApp message when a real number is configured.

### What it does not provide

- A shared booking database.
- Real-time appointment availability.
- Automatic business notifications.
- Automatic WhatsApp message delivery.
- SMS or email delivery.
- Payment processing.
- User authentication.
- Guaranteed appointment confirmation.

Optional LocalStorage data remains in the current browser profile and is not automatically shared with GSV or other devices.

**A prepared request is not a confirmed appointment.** The customer must use a configured communication channel to send the request to the business.

For a production deployment, integrate an appropriate booking service or backend and implement suitable privacy and data-protection measures.

---

## 10 — Privacy & Responsible Use

GSV does not include a backend or shared customer database.

- Demo records may remain in browser storage until cleared.
- Shared-device users may be able to access locally stored demonstration data.
- Sensitive personal information should not be entered into a demonstration form.
- Real contact details should only be published with appropriate authorisation.
- Privacy, cancellation and terms documents should reflect the actual business policies.

The website's frontend validation improves usability but is not a substitute for server-side validation in a production booking system.

---

## 11 — Deployment

GSV can be published through GitHub Pages or another static hosting provider.

### GitHub Pages

1. Push the website files to GitHub.
2. Open the repository.
3. Navigate to **Settings → Pages**.
4. Select the appropriate deployment source and branch.
5. Select the root folder if the HTML pages are stored there.
6. Save and open the published URL.

### Before publishing

- Verify all six pages.
- Check every navigation and booking link.
- Confirm all images load correctly.
- Configure actual business details.
- Test forms and error states.
- Review mobile and tablet layouts.
- Check browser-console errors.
- Ensure no demonstration prices or testimonials are presented as genuine.
- Add a privacy policy and applicable business policies.

A static deployment does not turn the demonstration booking flow into a live booking service.

---

## 12 — Quality Assurance

Use this checklist when testing the actual implementation.

- [ ] All six HTML pages exist.
- [ ] All pages share a consistent navbar and footer.
- [ ] Active navigation and mobile-menu states work.
- [ ] Service category filters and search work.
- [ ] Empty states and filter resets work.
- [ ] Gallery filtering and lightbox navigation work.
- [ ] Escape and click-outside lightbox dismissal work.
- [ ] Service links preselect the intended booking option.
- [ ] Booking summaries update with form selections.
- [ ] Invalid and past dates are rejected.
- [ ] Indian mobile-number validation behaves as intended.
- [ ] Duplicate submissions are prevented during processing.
- [ ] Demo confirmations explain their limitations.
- [ ] WhatsApp links work with a configured number.
- [ ] Missing contact configuration is handled clearly.
- [ ] No broken local asset paths remain.
- [ ] Layouts work at mobile, tablet and desktop widths.
- [ ] No unintended horizontal overflow is present.
- [ ] Keyboard focus and reduced-motion preferences are respected.

Only mark a test complete after verifying it in the running website.

---

## 13 — Roadmap

- [ ] Replace demonstration imagery with original GSV photography.
- [ ] Finalise the service catalogue and verified pricing.
- [ ] Configure official business contact information.
- [ ] Refine responsive behaviour using real-device testing.
- [ ] Complete accessibility and browser testing.
- [ ] Publish the static website.
- [ ] Consider a trusted booking integration if shared appointment management is needed.

---

## 14 — Project Goals

GSV is designed to demonstrate practical frontend engineering through a polished beauty-brand experience.

The project brings together:

- Responsive web design.
- Consistent visual systems.
- Semantic HTML and accessible interactions.
- Vanilla JavaScript application logic.
- Searchable and filterable content.
- Client-side form validation.
- Honest frontend-only data handling.
- Maintainable project structure.
- Static website deployment.

The emphasis is on creating a cohesive experience rather than simply assembling individual pages.

---

## 15 — License

No open-source license is included by default. Add an appropriate license file before authorising redistribution, modification or reuse of the project.

---

<p align="center">
  <strong>GSV — BEAUTY BEYOND EXPECTATIONS</strong>
  <br />
  <em>Beauty. Style. You.</em>
  <br /><br />
  Crafted with intention. Designed for elegance.
</p>
