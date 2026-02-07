# Cursor Landing Page Recreation

A recreation of the Cursor IDE landing page built with HTML, CSS, and semantic markup. This project showcases a modern developer tool landing page with clean typography, smooth navigation, and a professional layout.

---

## � Live Demo

**View the deployed website:** https://dev-tool-landing-page-cursor-woad.vercel.app/

---

## �🎯 Sections Recreated

### 1. **Navigation Bar**
- Fixed sticky navigation at the top
- Logo and icon container on the left
- Navigation links: Features, Enterprise, Pricing, Resources (centered)
- CTA buttons: Sign In and Download (right side)

### 2. **Hero Section**
- Large headline: "Built to make you extraordinarily productive, Cursor is the best way to code with AI."
- Call-to-action button: "Download for Windows ⤓"
- Hero image showcase below the text

### 3. **Trusted Companies Section**
- Heading: "Trusted every day by millions of professional developers."
- Logo grid displaying 8 company logos:
  - Stripe
  - OpenAI
  - Linear
  - Datadog
  - NVIDIA
  - Figma
  - Ramp
  - Adobe

### 4. **Features Section**
- Feature cards highlighting key capabilities
- **Agents Feature**: "Agents turn ideas into code" with supporting description and image
- **Autocomplete Feature**: "Magically accurate autocomplete" showcasing Tab model capabilities
- **Integration Feature**: "In every tool, at every step" highlighting GitHub, Slack, and terminal integration
- Clean layout with alternating text and image positions for better visual flow

### 5. **Testimonials Section**
- Heading: "The new way to build software."
- 6 testimonial cards featuring quotes from industry leaders:
  - Diana Hu (General Partner, Y Combinator)
  - Jensen Huang (President & CEO, NVIDIA)
  - Andrei Karpathy (CEO, Eureka Labs)
  - Patrick Collison (Co-Founder & CEO, Stripe)
  - shadcn (Creator of shadcn/ui)
  - Greg Brockman (President, OpenAI)
- Each card displays author name, title, and a professional headshot
- Grid layout for responsive design

---

## 🎨 Typography & Color Scheme

### **Fonts Used**

| Element | Font Family | Details |
|---------|-------------|---------|
| Headings (H1, H3) | `CursorGothic` (custom) | Font weight: 400, Letter spacing: -0.0125em |
| Body Text | `Segoe UI`, system-ui | Font weight: 400 (regular) |
| Navigation & Buttons | `Segoe UI`, system-ui | Font size: 14-16px |

### **Color Palette**


| Color | Hex Value | Usage |
|-------|-----------|-------|
| Primary Black | `#000000` | Main background color |
| White | `#FFFFFF` | Primary text color |
| Light Gray | `#CCCCCC` | Hover states for links |
| Dark Brown | `#1b1913` | Secondary background (cards, feature sections) |
| Light Gray Text | `#edecec` | Heading text color |
| Silver Gray | `#888888` | Secondary text color (paragraphs, captions) |
| Orange Accent | `#f54e00` | Feature button text and interactive elements |
| Dark Gray (Testimonials) | `#0c0c0c` | Testimonials section background |
| Darker Gray | `#121212` | Testimonial card background |
| Border Gray | `#1e1e1e` | Card borders |
| Quote Text | `#e5e5e5` | Testimonial quote text color |

### **CSS Variables Defined**
```css
--primary-color: #000000
--secondary-color: #FFFFFF
--font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif
--hover-color: #CCCCCC
--bg-color: #1b1913
--h1-font-family: "CursorGothic", "CursorGothic Fallback", system-ui, "Helvetica Neue", "Helvetica", "Arial", "sans-serif"
--silver-color: #888888
```
---

## 📐 Layout Features

- **Responsive Grid Layout**: Company logos arranged in an 8-column grid
- **Flexbox Navigation**: Responsive navigation with space-between distribution
- **Feature Sections**: Alternating text and image layouts with background containers
- **Width Constraint**: All sections maintain 85% width for optimal readability
- **Rounded Corners**: Subtle border-radius (4-30px) for modern appearance
- **Color Contrast**: High contrast dark mode design with light text on dark backgrounds

---

## � Screenshot


---

## �🖼️ Final Output Preview

The landing page features:
- **Dark theme** with pure black background and white text
- **Professional typography** using custom CursorGothic font for headings
- **Company logo showcase** with 8 major tech companies
- **Interactive elements** including hover states on navigation links
- **Clean spacing** with consistent 50px margins and gutters

### Key Visual Elements:
- Sticky navigation bar for easy access
- High-contrast hero section with prominent CTA
- Logo grid with subtle background containers
- Feature sections with integrated imagery
- Professional button styling with rounded edges

---

## 📁 Project Structure

```
Dev_Tool_Landing_Page-Cursor/
├── index.html              # Main HTML structure
├── styles.css              # All styling and layout
├── README.md              # This file
├── Feature/               # Feature images
│   ├── Feature_1.jpeg
│   ├── Feature_2.jpeg
│   └── Feature_3.jpeg
├── Logos/                 # Company logos
│   ├── Adobe/
│   ├── Datadog/
│   ├── Figma/
│   ├── Linear/
│   ├── NVIDIA/
│   ├── OpenAI/
│   ├── Ramp/
│   └── Stripe/
└── [Additional assets: Images, SVG files]
```

---

## 🚀 Getting Started

1. Clone or download the project
2. Open `index.html` in your web browser
3. No build process or dependencies required - pure HTML and CSS

---

## 💡 Design Highlights

✨ **Modern dark mode design** - Professional appearance with high contrast
✨ **Custom typography** - CursorGothic font for distinctive branding
✨ **Responsive layout** - Clean grid system and flexible flexbox layouts
✨ **Interactive navigation** - Hover states and smooth transitions
✨ **Company social proof** - 8-company logo display for credibility