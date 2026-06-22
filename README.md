# Amazon Home Page Clone

A responsive front-end web development project that replicates the layout, styling, and structural design of the Amazon desktop homepage. This project was built using semantic HTML5 and custom layout-driven CSS3.

##  Features

* **Amazon Navbar:** Complete header implementation featuring a custom localized layout, utility border-hover highlights, an integrated search container, language picker options, and a stylized shopping cart component.
* **Sub-Navigation Menu Panel:** A sleek options ribbon containing dynamic item spaces and dedicated deal highlights.
* **Hero Section:** A full-bleed background banner image supporting standard promotional layout modules.
* **Product Grid Layout:** A responsive multi-box flex wrap layout for storefront category displays.
* **Three-Tier Footer:** Comprehensive multi-stage footer capturing structural elements like "Back to Top," dynamic informational columns, and global localization options.

---

##  Tech Stack & Dependencies

* **HTML5:** Semantic architecture for layout structuring.
* **CSS3:** Flexbox-oriented alignments, media/asset integration, and interface state transitions.
* **FontAwesome (v6.4.0):** External CDN dependencies utilized to power accurate interface iconography (e.g., location markers, magnifying search utility, menu toggles, and cart symbols).

---

##  File Structure

```
Amazon_HomePage_Clone/
├── index.html          # Structure & Semantic markup
├── style.css           # Layout configurations & style logic
├── amazon_logo.png     # Brand asset image
├── flag.png            # Country localization image asset
└── hero_image.jpg      # Storefront banner image asset
```

##  Architecture & Layout Logic

### Global System Core
* **Reset Rules:** The system initializes utilizing a full browser reset (`*`) removing default tracking margins.
* **Box Model:** Applies `box-sizing: border-box` globally to guarantee predictable border and height calculations across all elements.

### Flexbox Execution
* **Alignment:** The `.navbar` and `.panel` containers use a flexible box implementation setting `align-items: center` along with `justify-content: space-evenly` to cleanly distribute navigation fields across the viewport.
* **Grid Layout:** The `.shopsection` employs `flex-wrap: wrap` paired with a strict width calculation setting `.box` containers to a precise `width: 24%`, creating a clean 4-column item display.

### Media & Design Triggers
* **Asset Scaling:** Uses `background-size: contain` and `background-size: cover` to control the presentation scale of assets, preventing visual distortion during container resizing.
* **Interactive Transitions:** Leverages transparent placeholder boundaries (`border: 2px solid transparent`) changing on `:hover` to standard white values, preventing layout shifting when interacting with navigation elements.
