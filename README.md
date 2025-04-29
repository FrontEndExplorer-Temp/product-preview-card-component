# Frontend Mentor - Product Preview Card Component Solution

This repository contains my solution to the [Product Preview Card Component challenge](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa) on Frontend Mentor.

## Table of Contents

- [Overview](#overview)
  - [The Challenge](#the-challenge)
  - [Screenshots](#screenshots)
  - [Live Links](#live-links)
- [Development Process](#development-process)
  - [Technologies Used](#technologies-used)
  - [Key Takeaways](#key-takeaways)
  - [Helpful Resources](#helpful-resources)
- [Author](#author)

## Overview

### The Challenge

The goal of this challenge was to build a responsive product preview card component. Users should be able to:

- View the layout optimized for different screen sizes (desktop & mobile)
- See hover and focus effects on interactive elements

### Screenshots

Desktop View  
![](screenshots/product-prev-desktop-screen.png)

Mobile View  
![](screenshots/product-prev-mobile-screen.png)

### Live Links

- [Solution on GitHub](https://github.com/FrontEndExplorer-Temp/product-preview-card-component)
- [Live Site](https://frontendexplorer-temp.github.io/product-preview-card-component/)

## Development Process

### Technologies Used

- Semantic HTML5
- CSS custom properties (variables)
- Flexbox for layout
- Visual Studio Code as the code editor

### Key Takeaways

One of the key concepts I practiced in this project was responsive images. Below is an example of how I handled image responsiveness using `srcset` and `sizes`:

```html
<img
  srcset="
    images/image-product-desktop.jpg 600w,
    images/image-product-mobile.jpg  686w
  "
  sizes="(max-width: 600px) 686px, 300px"
  src="images/image-product-desktop.jpg"
  alt="A bottle of perfume surrounded by foliage"
/>
```

This ensures the appropriate image loads based on the user's screen width.

### Helpful Resources

- 📘 [CSS Tricks – Complete Guide to Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)
- 🖼️ [ImageKit – Responsive Images Guide](https://imagekit.io/responsive-images/)

These were instrumental in understanding layout and image responsiveness.

## Author

- Frontend Mentor Profile: [@ymaudlinmandrake](https://www.frontendmentor.io/profile/FrontEndExplorer-Temp)
