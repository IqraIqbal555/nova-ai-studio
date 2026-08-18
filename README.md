# NOVA//AI Studio — Responsive Landing Page

**Student:** Iqra Iqbal
**GitHub:** Iqralqbal555

## 1. Project overview

**NOVA//AI Studio** is an original, responsive landing page for a fictional cutting-edge digital creative service. The studio offers photorealistic portraits, cinematic animation and 3D avatar systems for modern brands and creators.

### Target audience
- Startups and digital brands
- Creative directors and marketing teams
- Content creators
- Product and campaign teams looking for distinctive digital visuals

## 2. Live deployed URL
>repository URL
>https://github.com/IqraIqbal555/nova-ai-studio.git
>
>website url
> https://iqraiqbal555.github.io/nova-ai-studio/

## 3. Features

- Original custom visual identity and dark editorial interface
- Responsive layout for desktop, tablet and mobile
- Sticky navigation bar
- CSS Flexbox and CSS Grid
- CSS custom properties for reusable design tokens
- Fluid typography with `clamp()`
- Responsive media queries
- CSS keyframe animations for the orbital hero visual, pulse effect and marquee
- Hover transitions on cards and buttons
- CSS-only responsive interaction; **no JavaScript**
- Services / tiers section using **Premium Access, Standard Quota and Credits** instead of prices
- Accessible semantic HTML sections, labels and navigation
- Contact form using `mailto:` so it can be used without a backend or JavaScript

## 4. Design architecture

### File structure

```text
nova-ai-studio/
├── index.html
├── style.css
└── README.md
```

### HTML structure

The page is divided into:
1. Sticky navigation
2. Hero / visual engine
3. Capabilities marquee
4. Services
5. Studio tiers
6. Process
7. Contact form
8. Footer

### CSS architecture

All styling is contained in one external stylesheet.

Reusable variables are defined in `:root` for:
- Background and surface colors
- Text and muted text colors
- Accent colors
- Borders
- Maximum content width
- Border radius

The layout uses CSS Grid for major page sections and Flexbox for navigation, buttons, metadata and smaller groups.

### Responsive breakpoints

- Desktop: default layout
- Tablet: `max-width: 900px`
- Mobile: `max-width: 650px`
- Small mobile: `max-width: 390px`

The design is intentionally tested conceptually around the assignment requirement of mobile widths below 600px.

## 5. CSS techniques demonstrated

### Box model
Cards, sections, buttons and form controls use controlled `padding`, `margin`, `border` and `border-radius`.

### Positioning
- `sticky` is used for the navigation bar.
- `absolute` positioning is used for decorative orbital elements.
- `relative` positioning creates local positioning contexts for cards and the hero artwork.

### Flexbox
Used for:
- Navigation
- Hero actions
- Metadata
- Footer
- Tier header
- Marquee alignment

### CSS Grid
Used for:
- Hero two-column layout
- Service cards
- Tier rows
- Process layout
- Contact layout

### Animations
- `pulse` for the availability indicator
- `orbit` for decorative orbital motion
- `breathe` for the visual engine core
- `marquee` for the capabilities strip
- Hover transitions for cards and buttons

No JavaScript is used anywhere in the project.

## 6. How to run locally

### Option A — simplest
1. Download the project files.
2. Keep `index.html` and `style.css` in the same folder.
3. Double-click `index.html`.
4. Open the page in a browser.

### Option B — VS Code
1. Open the project folder in VS Code.
2. Install the **Live Server** extension if available.
3. Open `index.html`.
4. Choose **Open with Live Server**.
5. Resize the browser to test desktop, tablet and mobile views.

## 7. How to deploy

### Vercel
1. Create a GitHub repository.
2. Upload `index.html`, `style.css` and `README.md`.
3. Make the repository public.
4. Import the repository into Vercel.
5. Deploy it as a static site.
6. Copy the public deployment URL into section 2 of this README.

### GitHub Pages
1. Push the project to a public GitHub repository.
2. Open **Settings → Pages**.
3. Select the main branch as the deployment source.
4. Save.
5. Copy the generated public URL into section 2.

## 8. Screenshot 

### Desktop view
`![Desktop ](desktop.png)`

### Mobile view
`![Mobile](mobile.png)`

## 9. Compliance checklist

- [x] Original custom design
- [x] Vanilla HTML + CSS
- [x] No Bootstrap
- [x] No Tailwind
- [x] No JavaScript
- [x] Responsive desktop/tablet/mobile layouts
- [x] Flexbox
- [x] CSS Grid
- [x] Media queries
- [x] Fluid typography
- [x] Sticky navigation
- [x] Custom keyframe animations
- [x] Services / tier section
- [x] No price values or currency symbols
- [x] Public GitHub repository ready
- [x] Live public deployment URL
- [x] Final desktop screenshot
- [x] Final mobile screenshot
