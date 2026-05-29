# css-PART-2-WEDE
# Cozziano Streetwear Website

## Student Information

| Field          | Details         |
|----------------|-----------------|
| Name           | Andzani Gopane  |
| Student Number | ST10538025      |
| Group          | Group 4         |
| Subject        | WEDE5020        |

---

## Project Overview

This is a website I built for a South African streetwear brand called Cozziano. The brand sells urban fashion like tracksuits, shorts, skull caps, and basketball shorts. The website is meant to give people a place to learn about the brand, see the products, and get in touch.

---

## Website Goals

- Show people what products Cozziano sells and their prices
- Tell visitors about the brand's mission and vision
- Let people send an enquiry through a form
- Provide contact details so customers can reach out

---

## What I Included

- A navigation menu on every page so users can move between pages easily
- A homepage that introduces the brand
- An about page that explains the brand, its mission, vision, and target market
- A products page showing the items with images and prices
- An enquiry form where users can submit their name, email, and a message
- A contact page with the brand's email and phone number

---

## Pages and File Names

| Page Name    | File Name      |
|--------------|----------------|
| Home         | index.html     |
| About        | about.html     |
| Products     | products.html  |
| Enquiry      | enquiry.html   |
| Contact      | contact.html   |
| Budget       | budget.html    |

---

## Folder Structure

```
cozziano-website/
│
├── index.html
├── about.html
├── products.html
├── enquiry.html
├── contact.html
├── budget.html
├── style.css
│
├── images/
│   ├── Cozziano.jpg
│   ├── track.jpg
│   ├── shorts.jpg
│   ├── Skully.jpg
│   └── bshort.jpg
│
└── README.md
```

---

## Sitemap

```
Home (index.html)
├── About (about.html)
├── Products (products.html)
├── Enquiry (enquiry.html)
├── Contact (contact.html)
└── Budget (budget.html)
```

---

## Colours Used

| Element         | Colour                  |
|-----------------|-------------------------|
| Background      | Dark charcoal `#0d0d0d` |
| Surface/Header  | Dark grey `#161616`     |
| Cards           | Dark `#1e1e1e`          |
| Accent/Buttons  | Gold `#e8c84a`          |
| Secondary Accent| Red-orange `#ff4c29`    |
| Text            | Off-white `#f0ede6`     |
| Muted Text      | Grey `#888880`          |

I chose dark colours because they suit the streetwear and urban culture feel of the brand. The gold accent gives it a premium look.

---

## Fonts Used

| Font        | Where I Used It              |
|-------------|------------------------------|
| Bebas Neue  | Headings and display text    |
| DM Sans     | Body text and navigation     |

Both fonts are loaded from Google Fonts. Bebas Neue has that bold streetwear energy and DM Sans keeps the body text clean and readable.

---

## How I Built It

- **Editor:** Visual Studio Code
- **Languages:** HTML, CSS
- **Version Control:** GitHub
- **Browser Testing:** Google Chrome, Mozilla Firefox
- **CSS Features Used:** Flexbox, CSS Grid, media queries, CSS custom properties (variables), pseudo-classes (`:hover`, `:focus`, `:active`)

---

## Questions I Asked While Building

- How do I link an external CSS file to multiple HTML pages?
- How do I use CSS Grid to make a product layout that works on mobile?
- How do I make the navigation bar stay at the top when scrolling?
- What is the correct way to make images responsive with CSS?
- How do I style a form so it looks clean and modern?
- Where do I put references in a student project like this?
- How do I use media queries to change the layout for mobile screens?

---

## Changelog

### Part 2 – CSS Styling and Responsive Design

| Date        | Change Made                                                                 |
|-------------|-----------------------------------------------------------------------------|
| 2025-04-06  | Created `style.css` and linked it to all six HTML pages                     |
| 2025-04-06  | Set up CSS custom properties for colours, fonts, and spacing                |
| 2025-04-06  | Added base styles including CSS reset, font imports, and body defaults      |
| 2025-04-06  | Styled the header and navigation with sticky positioning and hover effects  |
| 2025-04-09  | Applied CSS Grid to the products page for a responsive product layout       |
| 2025-04-09  | Styled the enquiry form with focus states and a hover submit button         |
| 2025-04-09  | Styled the budget table with custom header colours and row hover effects    |
| 2025-04-09  | Added media queries for tablet (max-width: 900px) and mobile (max-width: 600px) |
| 2025-04-09  | Made images responsive using `max-width: 100%` and `object-fit: cover`     |
| 2025-04-09  | Updated README with Part 2 information and changelog entries                |

---

## Testing

I tested the website on the following browsers and screen sizes:

| Browser         | Result  |
|-----------------|---------|
| Google Chrome   | Passed  |
| Mozilla Firefox | Passed  |

**Screen sizes tested:**
- Desktop (1280px and above) — full multi-column layout
- Tablet (768px) — adjusted spacing and grid columns
- Mobile (375px) — single column layout, stacked navigation

I used the browser developer tools (F12) to test different screen sizes and fix any layout issues.

> Screenshot evidence of desktop, tablet, and mobile views is included in the repository under `/screenshots/`.

---

## References

### Images
- Product and brand images are my own or sourced from [Pexels](https://www.pexels.com) — a free stock photo platform that allows use without attribution, though I have credited them here.

### Fonts
- Google Fonts. (n.d.). *Bebas Neue*. Retrieved from https://fonts.google.com/specimen/Bebas+Neue
- Google Fonts. (n.d.). *DM Sans*. Retrieved from https://fonts.google.com/specimen/DM+Sans

### Content
- All written content (brand description, mission, vision, product names and prices) was written by me. It is fictional and created for educational purposes only.

### Tools
- Microsoft. (n.d.). *Visual Studio Code*. Retrieved from https://code.visualstudio.com
- GitHub, Inc. (n.d.). *GitHub*. Retrieved from https://github.com
- Google. (n.d.). *Google Chrome DevTools*. Retrieved from https://developer.chrome.com/docs/devtools
- Mozilla. (n.d.). *Firefox Developer Tools*. Retrieved from https://firefox-source-docs.mozilla.org/devtools-user

### Harvard References

Google. (n.d.). *Google Fonts*. [Online]. Available at: https://fonts.google.com [Accessed: April 2025].

MDN Web Docs. (n.d.). *CSS: Cascading Style Sheets*. Mozilla. [Online]. Available at: https://developer.mozilla.org/en-US/docs/Web/CSS [Accessed: April 2025].

MDN Web Docs. (n.d.). *Using media queries*. Mozilla. [Online]. Available at: https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_media_queries/Using_media_queries [Accessed: April 2025].

Pexels. (n.d.). *Free stock photos*. [Online]. Available at: https://www.pexels.com [Accessed: April 2025].

W3Schools. (n.d.). *CSS Flexbox*. [Online]. Available at: https://www.w3schools.com/css/css3_flexbox.asp [Accessed: April 2025].

W3Schools. (n.d.). *CSS Grid Layout*. [Online]. Available at: https://www.w3schools.com/css/css_grid.asp [Accessed: April 2025].


Contact

**Andzani Gopane**
Student Number: ST10538025
Subject: WEDE5020 | Group 4
