# Responsive Footer Component — Tailwind CSS 🦶

This project showcases a fully responsive, accessible **footer component** built using **HTML5** and **Tailwind CSS**. It includes a styled newsletter subscription form and two categorized navigation sections, all optimized for mobile-first design and scalability. 


## 📸 Preview

![alt text](assets/images/responsive-desktop.png)

## 🔧 Features

- ✅ **Responsive Layout** using Tailwind's grid and flex utilities
- ✅ **Newsletter Signup Form** with semantic, accessible markup
- ✅ **Quick Navigation Links**
- ✅ **Technologies Section** for stack reference or tech branding
- ✅ **Custom Colors** with brand-consistent palette
- ✅ **Accessible Labels** using screen-reader-only (`sr-only`) classes
- ✅ **Animated Hover Effects** on buttons

## 📁 Project Structure
```
footer-component/
│
├── index.html # Main footer component
└── tailwind.config.js # (Optional for customization if local Tailwind is used)


Tailwind is included via CDN in this project.
```

<br>

### 🔗 CDN Setup (Current)

No build tools required — just open `index.html` in a browser.

```html
<script src="https://cdn.tailwindcss.com"></script>
<link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
```


## 📦 Grid Layout
This grid setup adapts based on breakpoints:
```html
<div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-4">
```

## ♿ Accessibility
- This component follows accessibility best practices:
- Proper use of aria-label and aria-hidden
- Screen-reader-friendly labels (.sr-only)
- Semantic HTML5 structure
