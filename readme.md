# Landing Page README

## Overview
This document provides details about the structure, design, and basic CSS positioning techniques used in the landing page.

---

## Files Included
- **`index.html`**: Contains the HTML structure for the landing page.  
- **`logo.png`**: Placeholder for the company logo.  
- **`landing.png`**: Placeholder for the landing page banner image.  

---

## HTML Structure
The landing page is divided into three main sections:

1. **Header**  
   - Contains the navigation bar with links to *Signup, About, Products, Pricing,* and *Support*.  

2. **Main Banner**  
   - Displays the main banner image.

3. **Content Section**  
   - Includes a heading, a brief description, and a call-to-action button.

---

## Basic CSS Positioning
Inline styles have been used to demonstrate basic CSS positioning techniques.  

### 1. **Flexbox for Layout**
Flexbox is used extensively to create a flexible and responsive layout:  
- `display: flex;` sets the container to use the flexbox layout model.  
- `justify-content: space-between;` ensures even spacing between child elements.  
- `justify-content: center;` centers child elements horizontally.

### 2. **Padding and Margins**
- **Padding**: Provides space inside the elements' borders for proper spacing.  
  *Example:* `padding-left: 150px;` and `padding-right: 150px;` are applied to the header.  
- **Margins**: Space outside elements, though not used in this version, can complement padding.

### 3. **Box Shadow**
- Adds depth to the header using:  
  ```css
  box-shadow: 2px 1px 2px #eee;
### Live Link https://zerodhalandingpageflex.netlify.app/