# Multi-Page App - HNG STAGE 1

This project consists of a responsive **Profile Card** page, an **About Me** page and a **Contact Me** page, demonstrating semantic HTML, accessibility best practices, and modern frontend design principles.

---

## View Live Demo

Check out the live version of this project here:  
[🔗 View Live Demo](https://dejhii.github.io/HNG-Task---Stage-1/)

---

## Project Overview

This project showcases my personal portfolio information and provides a way for visitors to contact me. It focuses on:

- Semantic HTML
- Clean and modern CSS design
- Responsive layout for desktop, tablet, and mobile
- Accessibility for all users

---

## Pages

### About Me Page

- Displays a reflective summary of my skills, goals, and growth areas.
- Sections include:
  - **Bio** (`data-testid="test-about-bio"`)
  - **Goals in this program** (`data-testid="test-about-goals"`)
  - **Areas of low confidence** (`data-testid="test-about-confidence"`)
  - **Note to future self** (`data-testid="test-about-future-note"`)
  - **Extra thoughts** (`data-testid="test-about-extra"`)
- Semantic structure with `<main>` and `<section>` tags.
- Uses headings `<h1>` and `<h2>` for clarity.

### Contact Us Page

- Simple form for visitors to send a message.
- Fields:
  - Full Name (`data-testid="test-contact-name"`)
  - Email (`data-testid="test-contact-email"`)
  - Subject (`data-testid="test-contact-subject"`)
  - Message (`data-testid="test-contact-message"`)
- Submit button (`data-testid="test-contact-submit"`)
- Validation rules:
  - All fields required
  - Email must be valid
  - Message must be at least 10 characters
- Shows inline error messages (`data-testid="test-contact-error-<field>"`) and a success message (`data-testid="test-contact-success"`)
- Accessible and keyboard navigable

---

## Features

- **Responsive Navbar**: Sticky, highlights the current page, adapts to screen sizes
- **Form Validation**: Prevents invalid submissions and provides immediate feedback
- **Success/Error Handling**: Inline error messages and accessible success notifications
- **Semantic HTML**: Structured content for SEO and screen readers
- **Smooth Hover & Focus Effects**: For interactive elements

---

## Technologies

- HTML5
- CSS3 (Flexbox & Media Queries)
- Vanilla JavaScript (Form validation & navbar interactivity)

---

## Accessibility

- Labels linked with inputs using `for` attributes
- ARIA attributes for error and success messages
- Keyboard navigation supported
- Semantic HTML structure

---

## Responsive Design

- Fully responsive layout for:
  - **Desktop**
  - **Tablet**
  - **Mobile**
- Adaptive spacing, font sizes, and layout adjustments using media queries

---

## 👨‍💻 Author
**Aderibigbe Lateef Adedeji**  
[GitHub](https://github.com/dejhii) • [Twitter](https://x.com/dejhii_) • [LinkedIn](#)
