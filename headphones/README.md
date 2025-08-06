# 🎨 Responsive Web Page - Figma to HTML/CSS (No JS)

> Implemented from scratch based on a design by [Nicolas Philippot](https://www.figma.com/@nicophlpp), this project showcases a responsive, accessible, and pixel-perfect webpage using only **HTML** and **CSS** — no JavaScript, no external frameworks.

## 📌 Project Overview

This project is part of the **ALX Software Engineering Program**. The objective is to **replicate a professional web design** provided through Figma using only semantic HTML and CSS. It is designed to test mastery of:

- HTML semantics
- CSS styling and layout
- Responsive design techniques
- Accessibility best practices

I am **not allowed** to use:
- JavaScript
- Any external CSS framework like Bootstrap, Tailwind, etc.

## 🖼 Final Design Reference

The design was created by Nicolas Philippot (UI/UX Designer).  
Access the Figma file here:  
🔗 [Figma Design File](https://www.figma.com/file/yQfDM0VsmM6XaykNVyd8vU/Final-Project-Design?type=design&node-id=0%3A1&mode=design&t=Qq77tQHXv1zXwF3y-1)

👉 **Make sure to duplicate the file to your drafts** in order to inspect spacing, typography, font sizes, colors, and responsive behavior.

If the fonts are missing on your system, download and install:
- [Source Sans Pro](https://fonts.google.com/specimen/Source+Sans+Pro)
- [Spin Cycle OT](https://www.dafont.com/spin-cycle-ot.font)

## 💡 Key Features

- 🎯 **Exact replication of Figma design**
- 📱 **Fully responsive design** down to mobile view (≤ 480px)
- ♿️ **Accessibility**: Semantic HTML5, alt attributes, and color contrast
- 🎨 **Custom fonts**: Source Sans Pro and Spin Cycle OT
- 🖱️ **Link & button interactions**:
  - Links hover/active: `#FF6565`
  - Buttons hover/active: `opacity: 0.9`
- 📏 **Content max-width**: `1000px`, centered on screen

## 📱 Responsive Design

This website was developed using **mobile-first** approach and includes a **media query for 480px screen width**:

| Screen Width      | Layout              |
|-------------------|---------------------|
| > 480px           | Desktop layout      |
| ≤ 480px           | Mobile layout       |

The layout automatically adapts to smaller screens while maintaining readability and visual hierarchy.

## 🧩 Technologies Used

- ✅ HTML5
- ✅ CSS3 (Flexbox, media queries, custom properties)
- ✅ No JavaScript
- ✅ No frameworks

## 🎨 Styling & Fonts

### Colors:
- Link hover/active: `#FF6565`
- Other colors are extracted directly from the Figma file

### Fonts:
- **Primary Font**: `Source Sans Pro`
- **Display Font**: `Spin Cycle OT`

Fonts are loaded using `@font-face` in `style.css`.


## 📦 Assets

All images and icons used are stored in the `/images` directory and properly optimized.

Font files are included in the `/fonts` directory and referenced in CSS like this:

```css
@font-face {
  font-family: 'Spin Cycle OT';
  src: url('../fonts/Spin-Cycle-OT.ttf') format('truetype');
}

