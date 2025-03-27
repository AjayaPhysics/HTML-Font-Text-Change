# HTML-Font-Text-Change
ALL METHODS TO CHANGE FONT IN HTML
# 📝 All Methods to Change Font in HTML

| **Method** | **Description** | **Example Code** |
|-----------|------------------|------------------|
| **1. Inline CSS** | Apply font directly to an element using `style`. | `<p style="font-family: Arial;">This is Arial font.</p>` |
| **2. Internal CSS** | Define fonts within a `<style>` tag inside `<head>`. | `<style>p { font-family: Verdana; }</style>` |
| **3. External CSS** | Use a separate `.css` file linked with `<link>`. | `style.css → .custom-font { font-family: Georgia; }` |
| **4. CSS Classes & IDs** | Use `.class` or `#id` selectors for styling. | `.title { font-family: Garamond; }` |
| **5. Google Fonts** | Load fonts via a link to Google Fonts. | `<link href="https://fonts.googleapis.com/css2?family=Roboto&display=swap" rel="stylesheet">\n<p style="font-family: 'Roboto', sans-serif;">Text</p>` |
| **6. Adobe Fonts** | Use Typekit to load Adobe fonts. | `<script src="https://use.typekit.net/xyz123.js"></script>` |
| **7. @font-face** | Use custom font files hosted on your server. | `@font-face { font-family: 'MyFont'; src: url('MyFont.woff'); }` |
| **8. CSS Variables** | Define and reuse font styles using `--variables`. | `:root { --main-font: Arial; } body { font-family: var(--main-font); }` |
| **9. Tailwind CSS** | Use utility classes for font styling. | `<p class="font-sans text-lg font-bold">Text</p>` |
| **10. JavaScript DOM** | Dynamically change font using JS. | `document.getElementById("myText").style.fontFamily = "Lucida Console";` |
| **11. HTML <font> Tag** ❌ | Deprecated method (not for HTML5). | `<font face="Comic Sans MS">Old method</font>` |
| **12. SVG Fonts** | Define font inside `<svg>` elements. | `<svg><text font-family="Verdana">SVG Font</text></svg>` |
| **13. Shadow DOM/Web Components** | Scoped styling using shadow DOM templates. | `<template><style>p { font-family: Courier; }</style></template>` |
| **14. Email Fonts** | Use inline fonts for safe rendering in emails. | `<p style="font-family: Arial, sans-serif;">Email text</p>` |
| **15. Media Queries** | Set fonts based on screen size/resolution. | `@media (max-width: 600px) { body { font-family: sans-serif; } }` |
| **16. Inherit / Initial / Unset** | Use CSS defaulting or inheritance. | `p { font-family: inherit; }` |
| **17. Bootstrap** | Use Bootstrap classes for font style. | `<p class="fw-bold fst-italic">Bootstrap text</p>` |
